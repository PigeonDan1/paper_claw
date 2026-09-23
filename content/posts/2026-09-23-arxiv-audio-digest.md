<div align="center">

# 📰 Paper Claw

**2026-09-23**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-22 13:31:07 CST → 2026-09-23 13:18:26 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 2 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, ASR 1, TTS 1, Enhancement 1, Paralinguistics 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Spoken Language Models that Think Aloud

👤 **作者**: Junyi Ao, Kainan Peng, Mingbo Ma, Shun Zhang, Zhenyu Tang, Xutai Ma, Xiang Li, Yinghao Li, Yuancheng Wang, Zhizheng Wu, Haizhou Li, Qing He, Xubo Liu
🔗 **来源**: [https://arxiv.org/abs/2609.26488v1](https://arxiv.org/abs/2609.26488v1)

**摘要**
> While Chain-of-Thought (CoT) reasoning has improved the capability of language models, directly applying it to Spoken Language Models (SLMs) may introduce long silent intervals under the serial "think-then-speak" paradigm, disrupting real-time spoken interaction. To address this issue, we propose an asynchronous think-aloud framework for reasoning-based SLMs within the Thinker-Talker architecture. The framework maintains a primary reasoning stream for logical deduction and a lightweight think-aloud stream that generates short, task-grounded progress utterances conditioned on the user input and the evolving reasoning state. A dynamic balance strategy coordinates the two streams at runtime, triggering additional think-aloud speech to avoid silent gaps and canceling pending utterances when the final response becomes ready. Experiments on spoken reasoning and question-answering benchmarks show that our approach substantially reduces user-audible silence during reasoning while maintaining answer accuracy comparable to that of a serial "think-then-speak" baseline, demonstrating the potential of asynchronous think-aloud for responsive interaction in SLMs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Spoken Language Models that Think Aloud》所界定。 从摘要看，作者主要围绕 spoken language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While Chain-of-Thought (CoT) reasoning has improved the capability of language models, directly applying it to Spoken Language Models (SLMs) may introduce long silent intervals under the serial "think-then-speak" paradigm, disrupting real-time spoken interaction. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken language model。 |

---
## 🏷️ ASR

### 1. Persistent Delivery Optimization for Streaming Speech-to-Text Translation with Revisions

👤 **作者**: Zixiang Wan, Delin Chen, Wei Shi, Haihua Xu, Youxi Xie, Yuexian Zou
🔗 **来源**: [https://arxiv.org/abs/2609.26427v1](https://arxiv.org/abs/2609.26427v1)

**摘要**
> Revision-capable streaming speech-to-text translation (S2TT) can correct earlier drafts, but process rewards based on visible text may credit content later withdrawn. Persistent Delivery Optimization (PDO) assigns intermediate reward only to content that survives revisions while scoring final quality separately. With 7.49 h of task-specific FLEURS adaptation, PDO achieves the best BLEU on four of five directions and higher COMET than every external streaming baseline in all five directions. Relative to its History-SFT initialization, PDO reduces mean/P90 finalization-aware latency by 10.8\%/11.3\% and normalized erasure by 15.8\%, while emitting at the first permitted 2-s update and improving macro BLEU. Zero-shot evaluation on Europarl-ST and CoVoST 2 confirms that these gains are not confined to the FLEURS training domain.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Persistent Delivery Optimization for Streaming Speech-to-Text Translation with Revisions》所界定。 从摘要看，作者主要围绕 speech-to-text 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：With 7.49 h of task-specific FLEURS adaptation, PDO achieves the best BLEU on four of five directions and higher COMET than every external streaming baseline in all five directions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech-to-text。 |

---
## 🏷️ TTS

### 1. Not Quite My Tempo: Voice Activity-aware Speech Synthesis for Lip-Synchronous Dubbing

👤 **作者**: Alejandro Pérez-González-de-Martos, Florian Lux, Angelina Elizarova, Milana Shkhanukova, Andreas Kellner, Mattia Antonino Di Gangi
🔗 **来源**: [https://arxiv.org/abs/2609.26486v1](https://arxiv.org/abs/2609.26486v1)

**摘要**
> Automatic lip-synchronous dubbing requires a speech synthesis model to generate alternating voice and silence patterns in the target language that match the timing of the source clip precisely to ensure an optimal viewing experience. Prior works address this problem by conditioning the speech synthesis process on lip movements extracted from the video signal. In this work, we condition the speech generation on a binary voice-activity signal, which has a lightweight representation and can be produced in multiple ways. We show that the model follows the voice-activity signal with high accuracy while maintaining natural prosody and semantically appropriate pause placement within sentences, as demonstrated through extensive objective and subjective evaluations. By randomly masking this condition during training, we make the feature entirely optional during inference, allowing editors to enforce or relax lip-sync constraints when desired.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Not Quite My Tempo: Voice Activity-aware Speech Synthesis for Lip-Synchronous Dubbing》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that the model follows the voice-activity signal with high accuracy while maintaining natural prosody and semantically appropriate pause placement within sentences, as demonstrated through extensive objective and subjective evaluations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

---
## 🏷️ Enhancement

### 1. MambaVoice: Lightweight Audiovisual Singing Voice Separation Via A Hybrid Mamba-Transformer Model

👤 **作者**: Adithi Shankar, Gopika Krishnan, Gloria Haro, Xavier Serra, Martín Rocamora
🔗 **来源**: [https://arxiv.org/abs/2609.26635v1](https://arxiv.org/abs/2609.26635v1)

**摘要**
> Isolating a target singing voice from a music video remains challenging, particularly in the presence of multiple vocalists and dense instrumental accompaniment. We propose MambaVoice, a lightweight audiovisual framework that leverages a hybrid Mamba--Transformer architecture for targeted singing voice separation. The model jointly encodes audio and visual streams using an attention-based band-split audio encoder and a spatio-temporal graph convolutional network (ST-GCN) for facial motion features. These modalities are fused through a multiplicative gating mechanism, enabling visual cues to selectively modulate audio representations. The fused features are processed by a hybrid backbone that combines Transformer self-attention with Selective State Space Models (SSMs), achieving efficient long-range temporal modeling with linear complexity. We evaluated MambaVoice on the Acappella and URSing datasets under challenging conditions, including mixtures with interfering singers. At 16.2 million parameters, the model demonstrates comparable performance, achieving 14.18 dB SDR on Acappella and strong cross-dataset performance on URSing, comparable to larger models at a fraction of the parameter count. These findings highlight the effectiveness of hybrid SSM--attention architectures for scalable, efficient audiovisual source separation, suggesting they are well-suited as lightweight components within larger pipelines. We conduct a perceptual study that further supports our improvements in objective metrics. We provide our implementation online.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《MambaVoice: Lightweight Audiovisual Singing Voice Separation Via A Hybrid Mamba-Transformer Model》所界定。 从摘要看，作者主要围绕 source separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The fused features are processed by a hybrid backbone that combines Transformer self-attention with Selective State Space Models (SSMs), achieving efficient long-range temporal modeling with linear complexity. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

### 1. Enriching Speech Emotion Representations with Conversational Context

👤 **作者**: Arthur Peuvot, Romaric Besançon, Gaël de Chalendar, Bianca Vieru, Ioana Vasilescu
🔗 **来源**: [https://arxiv.org/abs/2609.26422v1](https://arxiv.org/abs/2609.26422v1)

**摘要**
> Detecting emotions is necessary for building systems that can accurately and adaptively interact with humans. Speech Emotion Recognition (SER) has become an important research focus to develop intelligent spoken interfaces. However, most studies predict emotions at the utterance level, ignoring the conversational context, along with the emotional flow and speaker interactions it carries. In this paper, we introduce ACERT (Averaged Contextual Emotion Representation through Time), a module that integrates a flexible-length window of conversational context to better capture emotional evolution in spoken interactions. To evaluate the robustness of this method, we conducted experiments on datasets spanning diverse emotionally expressive styles and contexts. ACERT outperforms current state-of-the-art (SOTA) approaches on IEMOCAP, establishes the first context-aware benchmark on SAFE, and obtains strong results on MELD for unweighted, class-balanced metrics. Ablation studies show that ACERT's gains come from emotional and conversational continuity, rather than from speaker identity or acoustic conditions.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Enriching Speech Emotion Representations with Conversational Context》所界定。 从摘要看，作者主要围绕 emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：ACERT outperforms current state-of-the-art (SOTA) approaches on IEMOCAP, establishes the first context-aware benchmark on SAFE, and obtains strong results on MELD for unweighted, class-balanced metrics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：emotion recognition。 |

---
## 🏷️ Audio

### 1. Transcribe, Translate, and Optimize: Joint Reward Learning for Speech Translation

👤 **作者**: Yanghe Dong, Wanting Huang, Weiran Wang
🔗 **来源**: [https://arxiv.org/abs/2609.26536v1](https://arxiv.org/abs/2609.26536v1)

**摘要**
> In LLM-based speech translation, transcription-based chain-of-thought (CoT) suffers from a mismatch between reference transcripts used in supervised fine-tuning (SFT) and model-generated transcripts at inference. To address this, we propose joint recognition and translation fine-tuning via group relative policy optimization (GRPO). We score both transcripts and translations, with translation conditioned on model-generated transcripts, and compare three token advantage strategies. Using Qwen2.5-Omni-3B across four languages, we evaluate CoT against direct speech translation (Direct ST) under SFT and GRPO, training on CoVoST 2 and testing on CoVoST 2 and FLEURS. CoT GRPO outperforms Direct ST GRPO by 1.77 and 0.83 average BLEU points on CoVoST 2 and FLEURS. Compared to CoT SFT, GRPO boosts BLEU by 0.82 and 0.67 points and reduces word error rate (WER) by 8.8% and 7.2% relatively. These results highlight reinforcement fine-tuning as an effective method to mitigate the training-inference mismatch, jointly improving recognition and translation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Transcribe, Translate, and Optimize: Joint Reward Learning for Speech Translation》所界定。 从摘要看，作者主要围绕 transcribe、translate、optimize 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：CoT GRPO outperforms Direct ST GRPO by 1.77 and 0.83 average BLEU points on CoVoST 2 and FLEURS. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：transcribe, translate, optimize。 |

---
### 2. ROAM-ASD: Robust Open-World Active Speaker Detection with Flexible Multimodal Fusion

👤 **作者**: Pu Wang, Yujun Wang, Hugo Van hamme
🔗 **来源**: [https://arxiv.org/abs/2609.26648v1](https://arxiv.org/abs/2609.26648v1)

**摘要**
> Active speaker detection (ASD) requires reliable association between visible faces and acoustic speech, yet existing systems often degrade under challenging domains or incomplete observations. We introduce ROAM-ASD, a robust audiovisual framework that jointly models audio, full-face, and fine-grained mouth representations. A unified joint self-attention mechanism processes all input streams together with modality-agnostic query tokens, enabling direct interaction among available modality inputs. Modality dropout further improves robustness when input streams are unavailable. ROAM-ASD achieves state-of-the-art performance across five ASD benchmarks: 98.8% mAP on WASD, 87.9% on UniTalk, 96.5% on AVA, 99.3% on ASW, and 98.2% on Talkies, improving over previous best systems by 5.1, 4.7, 0.9, 1.0, and 2.1 mAP points, respectively. ROAM-ASD also substantially improves zero-shot cross-dataset generalization and remains robust to missing observations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ROAM-ASD: Robust Open-World Active Speaker Detection with Flexible Multimodal Fusion》所界定。 从摘要看，作者主要围绕 roam-asd、robust、open-world 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Modality dropout further improves robustness when input streams are unavailable. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：roam-asd, robust, open-world。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
