<div align="center">

# 📰 Paper Claw

**2026-05-26**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-05-25 13:12:45 CST → 2026-05-26 12:54:23 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 2 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, TTS 2, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Thaka at KSAA-2026 Task 2: Regularized Fine-Tuning for Arabic Speech Diacritization

👤 **作者**: Meshal Alamr, Hassan Alqaeri, Abdullah Aldahlawi
🔗 **来源**: [https://arxiv.org/abs/2605.25928v1](https://arxiv.org/abs/2605.25928v1)

**摘要**
> We describe the winning system for Task 2 of the KSAA-2026 Shared Task on Arabic Speech Dictation with Automatic Diacritization. The task requires producing fully diacritized Arabic text from speech audio and undiacritized transcripts, with only 2,327 training samples available and no external data permitted. Our system fine-tunes CATT-Whisper, a character-level multimodal model combining a pretrained CATT text encoder with a frozen Whisper speech encoder. The key to our approach is training regularization: R-Drop consistency regularization, Optuna-optimized hyperparameters with high weight decay, and Focal Loss. At inference, we average 200 stochastic forward passes across four model checkpoints using Monte Carlo Dropout at the softmax probability level. The system achieves 23.26% WER on the primary leaderboard metric (with case endings, including no-diacritic positions), placing 1st among all participants.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Thaka at KSAA-2026 Task 2: Regularized Fine-Tuning for Arabic Speech Diacritization》所界定。 从摘要看，作者主要围绕 whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The system achieves 23.26% WER on the primary leaderboard metric (with case endings, including no-diacritic positions), placing 1st among all participants. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：whisper。 |

---
## 🏷️ TTS

### 1. CosyEdit2: Speech-Editing-Oriented Reinforcement Learning Unlocks Better Zero-Shot TTS

👤 **作者**: Junyang Chen, Yuhang Jia, Hui Wang, Jiaming Zhou, Yongchang Gan, Yong Qin
🔗 **来源**: [https://arxiv.org/abs/2605.25930v1](https://arxiv.org/abs/2605.25930v1)

**摘要**
> Speech editing and zero-shot Text-to-Speech (TTS) share a similar generative foundation conditioned on speech prompts, yet speech editing demands far stricter local acoustic consistency with surrounding unedited content. While prior work has shown that Supervised Fine-Tuning (SFT) enables TTS models to acquire functional editing capability, this approach remains fundamentally bottlenecked by imperfect paired editing data and coarse-grained optimization signals. To address these limitations, we propose CosyEdit2, a speech editing model built on a two-stage post-training framework that progresses from supervised editing initialization to editing-oriented Group Relative Policy Optimization (GRPO) over target-speech-free data. Extensive experiments demonstrate that CosyEdit2 not only substantially advances speech editing performance, but also unlocks better zero-shot TTS capability, revealing a deeper mutual relationship between the two tasks. Audio samples are available at https://cjy1018.github.io/CosyEdit2.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《CosyEdit2: Speech-Editing-Oriented Reinforcement Learning Unlocks Better Zero-Shot TTS》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While prior work has shown that Supervised Fine-Tuning (SFT) enables TTS models to acquire functional editing capability, this approach remains fundamentally bottlenecked by imperfect paired editing data and coarse-grained optimization signals. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
### 2. Continual Speaker Identity Unlearning with Minimal Interference

👤 **作者**: Jinju Kim, Yunsung Kang, Gyeong-Moon Park, Jong Hwan Ko
🔗 **来源**: [https://arxiv.org/abs/2605.25962v1](https://arxiv.org/abs/2605.25962v1)

**摘要**
> Machine unlearning removes designated concepts or knowledge from pre-trained models. Recent work has extended this paradigm to speaker identity unlearning in zero-shot text-to-speech (ZS-TTS), the task of selectively erasing a model's ability to replicate a speaker's voice. Existing methods, however, quietly assume all unlearning requests arrive at once; an unrealistic assumption, since privacy-motivated removals arrive sequentially over time. We show this assumption breaks state-of-the-art methods: unlearning each new speaker fully revives previously unlearned speakers, reintroducing the very privacy risk unlearning was meant to eliminate. We present Cumulative ORThogonal Identity Suppression (CORTIS), the first framework for continual speaker identity unlearning in ZS-TTS that requires no access to previously-unlearned speaker data. CORTIS combines Fisher-information-based parameter masking, which localizes updates to speaker-relevant weights, with orthogonal projection against subspaces spanned by prior unlearning updates. With VoiceBox, CORTIS unlearns each requested speaker while keeping previously unlearned speakers forgotten across long request sequences, substantially outperforming sequential application of prior methods. The demo is available at https://cumulativeortis.github.io/ .

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Continual Speaker Identity Unlearning with Minimal Interference》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show this assumption breaks state-of-the-art methods: unlearning each new speaker fully revives previously unlearned speakers, reintroducing the very privacy risk unlearning was meant to eliminate. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
## 🏷️ Enhancement

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Score-Agnostic Structure Analysis in Large-Scale Performance Datasets

👤 **作者**: Patricia Hu, Silvan Peter, Gerhard Widmer
🔗 **来源**: [https://arxiv.org/abs/2605.25951v1](https://arxiv.org/abs/2605.25951v1)

**摘要**
> In recent years, thanks to advances in automatic music transcription (AMT), several large-scale datasets of automatically transcribed piano solo music have been released. While these datasets undoubtedly offer extensive material for performance studies, they vary substantially in quality. In the case of classical music, performances often differ not only in expressive aspects such as tempo, but also in their structural interpretation of the score (including repeat patterns and edition-specific variants). To meaningfully use large-scale transcribed datasets for performance research, transcriptions of the same piece must be grouped according to their underlying structural realisation to support valid comparison. We address this by applying sequence-to-sequence alignment followed by hierarchical clustering: we create pairwise alignments for all pairs of transcriptions of a given piece, and use the alignment cost and (dis)similarity of performed sequence lengths to resolve structural mismatches as features for grouping. We propose this approach as a first step towards automatically evaluating large-scale transcribed datasets that lack ground-truth score and/or audio, shifting the evaluation criterion from truth-based accuracy to musical coherence and plausibility. We demonstrate our score-agnostic approach on around 1,500 transcriptions of 88 compositions from a recently published large-scale transcribed piano performance dataset.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Score-Agnostic Structure Analysis in Large-Scale Performance Datasets》所界定。 从摘要看，作者主要围绕 score-agnostic、structure、analysis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We demonstrate our score-agnostic approach on around 1,500 transcriptions of 88 compositions from a recently published large-scale transcribed piano performance dataset. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：score-agnostic, structure, analysis。 |

---
### 2. Hidden in Plain Tokens: Simply Robust, Gradient-Free Watermark for Synthetic Audio

👤 **作者**: Georgios Milis, Yubin Qin, Yihan Wu, Heng Huang
🔗 **来源**: [https://arxiv.org/abs/2605.25967v1](https://arxiv.org/abs/2605.25967v1)

**摘要**
> As policy catches up with the capabilities of generative AI, watermarking is central to content provenance efforts. Inference-time watermarks for autoregressive models are unfit for continuous modalities due to discretization inconsistencies. Existing methods overcome this by finetuning the modality tokenizers, nullifying the watermark's training-free advantage. In this work, motivated by the vocabulary redundancy of discretization, we propose an elegant solution for powerful and robust watermarking of synthetic audio. We theoretically analyze the impact of token errors on watermark detection, and effectively mitigate them using a reduced vocabulary obtained via community detection. Thorough experiments showcase that our gradient-free method can boost detectability by several orders of magnitude, while also achieving built-in robustness to audio modifications. Broadly, we discover a new state-of-the-art for token-level watermarks in multimedia, which simply arises from the nature of discrete representation learning.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Hidden in Plain Tokens: Simply Robust, Gradient-Free Watermark for Synthetic Audio》所界定。 从摘要看，作者主要围绕 hidden、plain、tokens 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Thorough experiments showcase that our gradient-free method can boost detectability by several orders of magnitude, while also achieving built-in robustness to audio modifications. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：hidden, plain, tokens。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
