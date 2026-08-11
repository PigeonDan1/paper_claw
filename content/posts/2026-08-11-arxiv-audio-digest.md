<div align="center">

# 📰 Paper Claw

**2026-08-11**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-10 11:02:47 CST → 2026-08-11 10:55:56 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, TTS 1, Enhancement 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Structured Phonological Representations for Audio-Articulatory rtMRI Speech Classification

👤 **作者**: Abner Hernandez, Tomás Arias Vergara, Daiqi Liu, Andreas Maier, Paula Andrea Pérez-Toro
🔗 **来源**: [https://arxiv.org/abs/2608.09767v1](https://arxiv.org/abs/2608.09767v1)

**摘要**
> Real-time MRI makes it possible to observe vocal-tract articulation during speech, but mapping these articulatory patterns to phonetic and phonological categories remains challenging. We investigate whether PhonoQ, an audio-based model trained to recognize structured phonological features, provides useful information for audio--articulatory modeling. Specifically, we extract representations from PhonoQ's Conformer module, whose training is shaped by supervision for manner, place, voicing, and vowel features. Using articulatory contours with synchronized audio-derived features, we compare WavLM-large and HuBERT-large baselines with models that incorporate PhonoQ-derived representations. Across unseen-speech and unseen-subject settings, these features improve macro-F1 for phonological targets including manner, place, voicing, vowel height, and vowel backness, and also improve fine-grained 39-phoneme classification. In a contour-only inference setting, audio-derived teacher supervision yields modest but consistent gains over contour-only training, indicating that phonological information from synchronized audio can be partially transferred to articulatory models. Finally, posterior analyses show interpretable surface-sensitive patterns consistent with flapping-like /t/ realizations, /t/-/r/ retraction or affrication, and nasal place assimilation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Structured Phonological Representations for Audio-Articulatory rtMRI Speech Classification》所界定。 从摘要看，作者主要围绕 conformer、hubert 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across unseen-speech and unseen-subject settings, these features improve macro-F1 for phonological targets including manner, place, voicing, vowel height, and vowel backness, and also improve fine-grained 39-phoneme classification. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：conformer, hubert。 |

---
## 🏷️ TTS

### 1. MADBench: A Benchmark for Modality-Aware Audio Deepfake Detection

👤 **作者**: Yanqiu Li, Yang Xiao, Jisheng Bai, Bin Chen, Hong Jia, Ting Dang
🔗 **来源**: [https://arxiv.org/abs/2608.09593v1](https://arxiv.org/abs/2608.09593v1)

**摘要**
> Recent advances in speech synthesis and audio generation have made high-fidelity acoustic forgery low-cost and difficult to attribute, enabling a realistic attack scenario in which speech and background audio are independently manipulated over otherwise authentic video. Yet existing research either focuses on visual manipulation, addresses speech detection in isolation, or conflates speech and non-speech audio as a single undifferentiated audio stream, overlooking the distinct forensic challenges posed by background audio. This conflation is consequential: the two acoustic components arise from fundamentally different generative mechanisms, exhibit distinct artifact profiles, and pose different challenges to detection systems. We introduce MADBench, the first benchmark that treats speech and environmental audio as distinct acoustic components, enabling component-aware evaluation of audio deepfake detection across independently manipulated forgery sources. We benchmark representative state-of-the-art detectors and multimodal large language models under a unified protocol. Our experiments reveal that environmental audio manipulation is more detectable than synthetic speech across general-purpose encoders, while existing pretrained detectors fail on both acoustic components, and manipulated environmental audio asymmetrically degrades speech deepfake detection, findings entirely invisible under the single-label paradigm of prior benchmarks. MADBench establishes a rigorous foundation for future research into robust, component-aware audio deepfake detection.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《MADBench: A Benchmark for Modality-Aware Audio Deepfake Detection》所界定。 从摘要看，作者主要围绕 speech synthesis、audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We benchmark representative state-of-the-art detectors and multimodal large language models under a unified protocol. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis, audio generation。 |

---
## 🏷️ Enhancement

### 1. Dynamic Clustering for Cross-Segment Permutation Alignment in Long Speech Separation

👤 **作者**: Yuzhu Wang, Archontis Politis, Konstantinos Drossos, Tuomas Virtanen
🔗 **来源**: [https://arxiv.org/abs/2608.09451v1](https://arxiv.org/abs/2608.09451v1)

**摘要**
> Long speech separation typically employs a segment-separation-stitch paradigm where recordings are divided into short segments, processed independently, and stitched together. Its challenge lies in predicting cross-segment permutations. This paper proposes a training-free dynamic clustering approach for cross-segment permutation alignment using speaker embedding reference pools. The method predicts the permutation using the cosine similarity between current segment embeddings and the reference pools. The approach updates reference pools by retaining the most representative speaker embeddings based on their overall cosine similarity with existing references. As a plug-and-play post-processing module compatible with existing separation models, the proposed method demonstrates superior performance compared to existing methods on dense and sparse long speech scenarios, particularly in challenging sparse scenarios with extended utterance gaps, and further shows robustness to speaker count estimation errors in unknown speaker count scenarios.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Dynamic Clustering for Cross-Segment Permutation Alignment in Long Speech Separation》所界定。 从摘要看，作者主要围绕 speech separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：As a plug-and-play post-processing module compatible with existing separation models, the proposed method demonstrates superior performance compared to existing methods on dense and sparse long speech scenarios, particularly in challenging sparse scenarios with extended utterance gaps, and further shows robustness to speaker count estimation errors in unknown speaker count scenarios. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. AudioMap: Cloze-and-Choice Reinforcement Learning for Time-Aware Dense Audio Captioning

👤 **作者**: Yan Rong, Fengji Ma, Xu Li, Jinting Wang, Chen Zhang, Li Liu
🔗 **来源**: [https://arxiv.org/abs/2608.09559v1](https://arxiv.org/abs/2608.09559v1)

**摘要**
> Time-aware dense audio captioning (TDAC) aims to generate multiple fine-grained attributes (dense) of the audio with precise time boundaries (time-aware). Existing methods struggle to achieve these two goals and mainly rely on supervised fine-tuning, yielding sub-optimal performance. While reinforcement learning (RL) shows promise, applying it to TDAC faces two main challenges: (1) existing rewards are too coarse to supervise multi-event, multi-attribute, and multi-relation descriptions in a fine-grained manner; and (2) temporal supervision is difficult for free-form captions, where flexible event-time expressions make reliable event-time correspondence challenging. To address these challenges, we propose AudioMap, a novel RL-based TDAC framework, which shifts to a unified cloze-and-choice reward paradigm. Specifically, we introduce the Evidence Sufficiency Reward (ESR) with an asymmetric hierarchical scoring mechanism to promote fine-grained accuracy and descriptive richness across diverse acoustic dimensions. Furthermore, we design the Event-Conditioned Temporal Reward (ECTR) to structurally bind timestamps to event semantics via temporal IoU, accompanied by a dual-curriculum learning strategy to facilitate the training process. Finally, to support this task, we construct the first time-aware fine-grained audio captioning dataset, AudioMapCap-44K, which contains 44K carefully annotated captions. Extensive experiments across diverse benchmarks show that AudioMap achieves state-of-the-art (SOTA) performance among open-source models and delivers competitive or superior results relative to proprietary models. Project page and release updates are available at https://github.com/ryysayhi/AudioMap.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AudioMap: Cloze-and-Choice Reinforcement Learning for Time-Aware Dense Audio Captioning》所界定。 从摘要看，作者主要围绕 audiomap、cloze-and-choice、reinforcement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Existing methods struggle to achieve these two goals and mainly rely on supervised fine-tuning, yielding sub-optimal performance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audiomap, cloze-and-choice, reinforcement。 |

---
### 2. SonicWeave: Chunk-Routed Mixture-of-Experts for Unified Audio Scene Generation

👤 **作者**: Yunrui Cai, Xu Li, Yucheng Zhou, Jinchao Li, Dingdong Wang, Dongchao Yang, Xixin Wu, Chen Zhang, Zhiyong Wu, Pengfei Wan, Helen Meng
🔗 **来源**: [https://arxiv.org/abs/2608.09571v1](https://arxiv.org/abs/2608.09571v1)

**摘要**
> Text-conditioned general audio generation is moving beyond isolated speech, music, and sound-effect synthesis toward a single model that can compose them into controllable, coherent audio scenes. This unified setting is particularly challenging: heterogeneous components impose conflicting structural requirements on a shared backbone, while a complex mixed scene may contain locally distinct or overlapping content that demands fine-grained adaptation within the same clip. Existing audio mixture-of-experts (MoEs) mainly route at the domain level, while token-wise routing overlooks the local continuity inherent to acoustic signals. We propose SonicWeave, a flow-matching model for unified audio scene generation. At its core is a chunk-routed MoE with a conflict-gated prior-evidence routing mechanism (CPE-MoE). CPE-MoE routes contiguous acoustic chunks by combining a global prior that encodes the structured text condition and diffusion phase with local evidence from the evolving acoustic state. A learned conflict gate favors the prior when local states are unreliable, while allowing local evidence to influence routing when a region departs from the global scene context. SonicWeave supports speech, music, sound effects, singing, and their fine-grained mixtures with a single set of weights. Across TTS, TTA, and TTM benchmarks, SonicWeave consistently improves over controlled Dense and Base-MoE baselines. Complex-scene evaluation further demonstrates improved compositional quality, while routing analyses reveal content-dependent expert specialization across diffusion phases. These results suggest that temporally coherent, prior-evidence routing is an effective conditional-computation strategy for unified audio generation. Project page: https://caiyunrui.github.io/SonicWeave.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SonicWeave: Chunk-Routed Mixture-of-Experts for Unified Audio Scene Generation》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across TTS, TTA, and TTM benchmarks, SonicWeave consistently improves over controlled Dense and Base-MoE baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
