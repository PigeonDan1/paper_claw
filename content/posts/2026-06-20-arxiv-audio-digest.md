<div align="center">

# 📰 Paper Claw

**2026-06-20**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-18 13:25:53 CST → 2026-06-20 13:01:20 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 2 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 6 篇新论文，主要分布在 ASR 2, TTS 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Transcript-Free Flow-Matching Text-to-Speech via Speech Feature Conditioning

👤 **作者**: SooHwan Eom, Hee Suk Yoon, Eunseop Yoon, Mark Hasegawa-Johnson, Chang D. Yoo
🔗 **来源**: [https://arxiv.org/abs/2606.20266v1](https://arxiv.org/abs/2606.20266v1)

**摘要**
> Recent flow-matching text-to-speech (TTS) models, such as F5-TTS, rely on a reference transcript at inference time, obtained from an external ASR system. This dependency makes zero-shot TTS brittle for accented or dysarthric speakers, precisely the scenarios where it is most needed. Moreover, we find that text-based reference conditioning can propagate atypical acoustic patterns from atypical speech into synthesis, even when ground-truth transcripts are available. To address this, we propose RTFree-F5, which replaces the reference transcript with continuous self-supervised speech representations mapped into F5-TTS's text-conditioning space via a lightweight adapter, while reusing the pretrained checkpoint. On dysarthric speech, RTFree-F5 reduces WER from 24.6% to 10.4%, surpassing even the ground-truth reference transcript baselines, while improving naturalness and remaining competitive on standard benchmarks without requiring any reference transcript.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Transcript-Free Flow-Matching Text-to-Speech via Speech Feature Conditioning》所界定。 从摘要看，作者主要围绕 asr system、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On dysarthric speech, RTFree-F5 reduces WER from 24.6% to 10.4%, surpassing even the ground-truth reference transcript baselines, while improving naturalness and remaining competitive on standard benchmarks without requiring any reference transcript. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：asr system, text-to-speech。 |

---
### 2. Stuttering Classification and Segmentation with Attention-Based Multiple Instance Learning

👤 **作者**: Petar Sušac, Sebastian P. Bayerl, Hrvoje Džapo
🔗 **来源**: [https://arxiv.org/abs/2606.20338v1](https://arxiv.org/abs/2606.20338v1)

**摘要**
> Stuttering detection and classification using deep learning methods has the potential to improve the process of stuttering severity assessment. Most stuttering classification datasets provide clip-level labels, making them unsuitable for fine-grained frame-level classification needed to determine the duration of individual stuttering dysfluencies. To overcome this challenge, we present a multiple instance neural network architecture based on fine-tuned wav2vec 2.0, WavLM and Whisper encoders. We apply instance- and embedding-based multiple instance learning approaches to train models on a clip-level dataset for both clip-level and frame-level stuttering classification tasks. Our results show a 23% improvement in frame-level F1 score and between 2% and 9% in clip-level F1 score, demonstrating the ability of our models to utilize clip-level data for frame-level segmentation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Stuttering Classification and Segmentation with Attention-Based Multiple Instance Learning》所界定。 从摘要看，作者主要围绕 wav2vec、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Stuttering detection and classification using deep learning methods has the potential to improve the process of stuttering severity assessment. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：wav2vec, whisper。 |

---
## 🏷️ TTS

### 1. Repurposing a Speech Classifier for Guided Diffusion-Based Speech Generation

👤 **作者**: Rostislav Makarov, Timo Gerkmann
🔗 **来源**: [https://arxiv.org/abs/2606.20457v1](https://arxiv.org/abs/2606.20457v1)

**摘要**
> Classifier guidance is a way to control diffusion generation by using a noise-conditioned classifier to steer the sampling process toward a target class. One drawback of classifier guidance is that it requires two separately trained models: a classifier and a diffusion model. We therefore study a more compact alternative in which a conventionally trained speech classifier is repurposed as the backbone for diffusion generation. Starting from a frozen noise-conditioned classifier in log-Mel space, we attach a lightweight subnetwork that reuses intermediate classifier representations and train only this subnetwork under a Denoising Score Matching objective. Our work shows that a pretrained classifier can be repurposed for conditional generation, providing an appealing bridge between discriminative modeling and conditional speech synthesis resulting in high speech quality within a single-backbone model, with reduced memory footprint and computational cost.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Repurposing a Speech Classifier for Guided Diffusion-Based Speech Generation》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our work shows that a pretrained classifier can be repurposed for conditional generation, providing an appealing bridge between discriminative modeling and conditional speech synthesis resulting in high speech quality within a single-backbone model, with reduced memory footprint and computational cost. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

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

### 1. Zero-VC: Zero-Lookahead Streaming Voice Conversion via Speaker Anonymization

👤 **作者**: Yudong Li, Zihao Fang, Junwen Qiu, Ruihai Jing, Ruixiang Hang, Yingda Shen, Zhizheng Wu
🔗 **来源**: [https://arxiv.org/abs/2606.20218v1](https://arxiv.org/abs/2606.20218v1)

**摘要**
> Streaming zero-shot voice conversion struggles to disentangle timbre from linguistic content without degrading utility or inflating latency. Current methods rely on information bottleneck (IB) or speaker perturbation. While IB filters out timbre, it discards prosody, forcing models to explicitly inject features like fundamental frequency. This often requires buffering future frames, creating algorithmic lookahead latency. On the other hand, existing perturbation methods largely overlook the crucial trade-off between timbre leakage and utility preservation. Recognizing this neglected trade-off, we find that the inherent objective of Speaker Anonymization (SA) aligns well with balancing these factors. Thus, we introduce SA as a novel perturbation mechanism to explicitly mitigate timbre leakage while retaining prosodic utility. Crucially, SA's robust representations significantly alleviate the generator's reliance on future context, enabling our strictly causal, zero-lookahead network. Audio samples are available at https://amphionteam.github.io/Zero-VC-demo/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Zero-VC: Zero-Lookahead Streaming Voice Conversion via Speaker Anonymization》所界定。 从摘要看，作者主要围绕 zero-vc、zero-lookahead、streaming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Current methods rely on information bottleneck (IB) or speaker perturbation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：zero-vc, zero-lookahead, streaming。 |

---
### 2. MixProLAP: Mixture-Induced Uncertainty Modeling for Probabilistic Language-Audio Pretraining

👤 **作者**: Yu Nakagome, Jaesong Lee, Soo-Whan Chung
🔗 **来源**: [https://arxiv.org/abs/2606.20418v1](https://arxiv.org/abs/2606.20418v1)

**摘要**
> Acoustic environments often contain multiple overlapping sound events, and the same acoustic scene can be described using diverse textual expressions, making audio-text alignment inherently ambiguous. This paper proposes a probabilistic audio-language pretraining framework to model many-to-many correspondence ambiguity in audio-text alignment. Unlike conventional contrastive methods that learn deterministic point embeddings, our approach represents each modality as a distribution and learns uncertainty-aware cross-modal alignment. Rather than relying on masking-based uncertainty simulation, we mix audio-text pairs to create overlapping sounds that better reflect real acoustic mixtures and capture semantic inclusion relations among sound events. We further introduce a multi-level inclusion loss to enforce representations consistent with these relations. Experiments on audio-text retrieval benchmarks show that the proposed method outperforms deterministic baselines.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MixProLAP: Mixture-Induced Uncertainty Modeling for Probabilistic Language-Audio Pretraining》所界定。 从摘要看，作者主要围绕 acoustic scene 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on audio-text retrieval benchmarks show that the proposed method outperforms deterministic baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic scene。 |

---
### 3. Beyond Speaker Independence: Evaluating Cross-Lingual Acoustic-to-Articulatory Inversion Across Finnish and Russian

👤 **作者**: Ruchi Pandey, Tomi Kinnunen
🔗 **来源**: [https://arxiv.org/abs/2606.20478v1](https://arxiv.org/abs/2606.20478v1)

**摘要**
> Acoustic-to-articulatory inversion (AAI) remains challenging under domain shifts where changes in speaker attributes and cross-language conditions often degrade performance. We conduct a systematic evaluation under such shifts and establish baseline benchmarks on FROST-EMA, a Finnish-Russian bilingual EMA corpus. FROST-EMA addresses the English bias and limited speaker diversity of existing resources. We benchmark (i) articulatory targets (raw EMA coordinates vs tract variables), (ii) acoustic front-ends (MFCC vs SSL features), and (iii) inversion back-ends (BiLSTM vs a lightweight attention-based sequence model). We further define evaluation protocols for cross-gender transfer (within language) and cross-language transfer (within gender). The results indicate that cross-gender mismatch introduces moderate Pearson correlation declines (approximately 0.05 to 0.10) relative to the in-domain baseline, whereas cross-language mismatch causes larger drops (approximately 0.10 to 0.20).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond Speaker Independence: Evaluating Cross-Lingual Acoustic-to-Articulatory Inversion Across Finnish and Russian》所界定。 从摘要看，作者主要围绕 beyond、speaker、independence 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We conduct a systematic evaluation under such shifts and establish baseline benchmarks on FROST-EMA, a Finnish-Russian bilingual EMA corpus. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beyond, speaker, independence。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
