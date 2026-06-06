<div align="center">

# 📰 Paper Claw

**2026-06-06**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-04 13:29:34 CST → 2026-06-06 12:43:36 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 2 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 2 篇

> 💡 今日共收录 6 篇新论文，主要分布在 Speech LLM 1, ASR 2, Paralinguistics 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. USAD 2.0: Scaling Representation Distillation for Universal Audio Understanding

👤 **作者**: Heng-Jui Chang, Alexander H. Liu, Saurabhchand Bhati, Mrudula Athi, Anton Ratnarajah, Amit Chhetri, James Glass
🔗 **来源**: [https://arxiv.org/abs/2606.06444v1](https://arxiv.org/abs/2606.06444v1)

**摘要**
> Audio encoders are critical to modern audio applications as large language models (LLMs) increasingly rely on a single encoder for diverse inputs. While self-supervised learning (SSL) has yielded strong domain-specific encoders like speech or music experts, multi-domain approaches like USAD and SPEAR remain limited in coverage and evaluation. Recent studies also suggest supervised encoders align better with audio LLMs. We present USAD 2.0, a universal encoder integrating knowledge from both SSL and supervised foundation models. USAD 2.0 introduces domain-aware distillation to address teacher mismatch, extends coverage to the music domain, and adds second-stage supervised distillation for downstream use. We further scale the model to one billion parameters via depth scaling. Experiments show USAD 2.0 achieves strong or state-of-the-art performance across probing and LLM-based evaluations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《USAD 2.0: Scaling Representation Distillation for Universal Audio Understanding》所界定。 从摘要看，作者主要围绕 audio llm 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show USAD 2.0 achieves strong or state-of-the-art performance across probing and LLM-based evaluations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio llm。 |

---
## 🏷️ ASR

### 1. CoSTA: Cognitive-State-Conditioned TTS Data Augmentation Using ASR Transcripts for Alzheimer's Disease Detection

👤 **作者**: Yin-Long Liu, Yuanchao Li, Yiming Wang, Yue Li, Rui Feng, Jiaxin Chen, Shaobo Liu, Liu He, Yuang Chen, Jiahong Yuan, Zhen-Hua Ling
🔗 **来源**: [https://arxiv.org/abs/2606.06170v1](https://arxiv.org/abs/2606.06170v1)

**摘要**
> Speech-based Alzheimer's Disease (AD) detection is constrained by scarce pathological speech data. To address this, we propose CoSTA, a Text-to-Speech (TTS)-based data augmentation framework. Specifically, we first develop two Cognitive-State-Conditioned (CS-Cond) TTS models by adapting CosyVoice2 and F5-TTS to synthesize speech with distinct AD and Healthy Control characteristics. Furthermore, by constructing a transcript pool comprising Manual Transcripts (MT) and 36 Automatic Speech Recognition (ASR) transcripts, we investigate the impact of text sources on TTS-based augmentation. We also perform augmentation-factor analysis and test-time augmentation. Experiments on the ADReSS dataset show that CS-Cond TTS significantly improves synthetic speech utility, and ASR-driven augmentation frequently outperforms MT-driven augmentation. Finally, CoSTA yields a 4.16% gain over the baseline, achieving an audio-only accuracy of 85.83% on the ADReSS test set and outperforming prior methods.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《CoSTA: Cognitive-State-Conditioned TTS Data Augmentation Using ASR Transcripts for Alzheimer's Disease Detection》所界定。 从摘要看，作者主要围绕 automatic speech recognition、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the ADReSS dataset show that CS-Cond TTS significantly improves synthetic speech utility, and ASR-driven augmentation frequently outperforms MT-driven augmentation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, text-to-speech。 |

---
### 2. FiLM-Based Speaker Conditioning of a SpeechLLM for Pathological Speech Recognition

👤 **作者**: Fernando López, Santosh Kesiraju, Jordi Luque
🔗 **来源**: [https://arxiv.org/abs/2606.06211v1](https://arxiv.org/abs/2606.06211v1)

**摘要**
> Automatic speech recognition (ASR) has advanced remarkably for standard speech; however, pathological speech from neurological conditions remains a significant challenge. We investigate speaker conditioning via Feature-wise Linear Modulation (FiLM), injecting x-vector-derived information into each transformer layer of a frozen ASR encoder to adapt internal representations to individual pathological speakers without modifying base model weights. We benchmark this for the ASR task against standard and parameter-efficient fine-tuning baselines, complemented by post-processing, on Spanish and English pathological speech. Additionally, we evaluate if the adapted model preserves the ability to answer speech-related questions. Results show that speaker-conditioned ASR is competitive with established adaptation strategies while retaining performance on non-conditioned speech.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《FiLM-Based Speaker Conditioning of a SpeechLLM for Pathological Speech Recognition》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that speaker-conditioned ASR is competitive with established adaptation strategies while retaining performance on non-conditioned speech. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automatic speech recognition。 |

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

### 1. Learning Emotion-discriminative Representations for Zero-Shot Cross-lingual Speech Emotion Recognition

👤 **作者**: Jinyi Mi, Ding Ma, Tomoki Toda
🔗 **来源**: [https://arxiv.org/abs/2606.06200v1](https://arxiv.org/abs/2606.06200v1)

**摘要**
> Zero-shot cross-lingual speech emotion recognition (SER) remains challenging due to distribution mismatches across languages and the lack of emotion annotations in target language. Under such conditions, models trained solely on source-language data frequently suffer from degraded generalization when evaluated on unseen target languages. To address this limitation, we propose an emotion-discriminative representation learning method that integrates supervised contrastive learning and speaker adversarial learning. The contrastive learning promotes cross-lingual emotion alignment, while speaker adversarial learning suppresses speaker-related cues to encourage speaker-invariant representations. Experimental results under a zero-shot cross-lingual SER setting demonstrate that the proposed method significantly improves SER performance over conventional training strategies.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Learning Emotion-discriminative Representations for Zero-Shot Cross-lingual Speech Emotion Recognition》所界定。 从摘要看，作者主要围绕 emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results under a zero-shot cross-lingual SER setting demonstrate that the proposed method significantly improves SER performance over conventional training strategies. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：emotion recognition。 |

---
## 🏷️ Audio

### 1. Revisiting Lexicon Evaluation in Unsupervised Word Discovery

👤 **作者**: Simon Malan, Danel Slabbert, Herman Kamper
🔗 **来源**: [https://arxiv.org/abs/2606.06183v1](https://arxiv.org/abs/2606.06183v1)

**摘要**
> Building a lexicon from discovered word-like units is a central goal in zero-resource speech processing. But do our evaluations provide a trustworthy indication of lexicon quality? A common metric, normalized edit distance, averages the phoneme edit distances between discovered units in each cluster. We show that this metric has an inherent bias toward the quality of large clusters, inhibiting fair evaluation. Moreover, it ignores how well true classes are distributed across clusters. Based on established theory in clustering literature, we propose two metrics that address these shortcomings: a modified metric that weighs cluster size when assessing within-cluster consistency, and an inverse metric that assesses how true words are spread across clusters. Through experiments on synthetic and real-world lexicons, we demonstrate that combined, these metrics are: (1) more closely correlated with how similar a lexicon is to the ground-truth distribution, and (2) more robust to biases that skew lexicon evaluations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Revisiting Lexicon Evaluation in Unsupervised Word Discovery》所界定。 从摘要看，作者主要围绕 revisiting、lexicon、evaluation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that this metric has an inherent bias toward the quality of large clusters, inhibiting fair evaluation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：revisiting, lexicon, evaluation。 |

---
### 2. F3-Tokenizer: Taming Audio Autoencoder Latents for Understanding and Generation

👤 **作者**: Dinghao Zhou, Xingchen Song, Di Wu, Pengyu Cheng, Shengfan Shen, Sixiang Lv
🔗 **来源**: [https://arxiv.org/abs/2606.06357v1](https://arxiv.org/abs/2606.06357v1)

**摘要**
> Continuous audio autoencoders reconstruct waveforms well but often produce latents with weak structure for understanding, while self-supervised audio encoders capture semantics but are not directly decodable. This mismatch complicates a single audio tokenizer that must support both understanding and generation. We adapt continuous autoencoder latents to this setting with two components: a noise-regularized autoencoder bottleneck and a latent-side representation encoder. The bottleneck uses channel normalization and stochastic perturbation instead of KL-based variational training, yielding scale-controlled continuous latents for reconstruction and autoregressive generation. The representation encoder is trained on frozen autoencoder latents with RQ-MTP and frozen-LLM supervision. The resulting tokenizer provides high-dimensional representations for understanding while preserving normalized continuous latents as generation targets

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《F3-Tokenizer: Taming Audio Autoencoder Latents for Understanding and Generation》所界定。 从摘要看，作者主要围绕 tokenizer、taming、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This mismatch complicates a single audio tokenizer that must support both understanding and generation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：tokenizer, taming, audio。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
