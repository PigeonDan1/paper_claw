<div align="center">

# 📰 Paper Claw

**2026-07-08**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-07 12:39:15 CST → 2026-07-08 11:59:46 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 7 篇新论文，主要分布在 ASR 1, TTS 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. InsideSSL: Understanding Self-Supervised Speech Representations using a Model-Centric Perspective

👤 **作者**: Samir Sadok, Xavier Alameda-Pineda
🔗 **来源**: [https://arxiv.org/abs/2607.06392v1](https://arxiv.org/abs/2607.06392v1)

**摘要**
> Self-supervised learning (SSL) models, such as Wav2Vec2, HuBERT, and WavLM, have become foundational across a wide range of speech and audio tasks. Despite their success, understanding their internal layer-wise dynamics remains an ongoing challenge. To address this, we propose a two-part model-centric framework called InsideSSL. First, we establish a task-agnostic analysis from three intrinsic per-layer perspectives: compression (entropy), geometry (curvature), and robustness to perturbations. We show that varying training objectives induce distinct regimes of acoustic compression and manifold unfolding. Second, we introduce the cross-layer Generative Compatibility Matrix (GCM) to evaluate functional transferability, exposing stable phonetic cores, identity volatility, and deep-layer semantic pruning. In addition to these evaluations, linear probing connects the model-centric perspective to downstream tasks, demonstrating how layer topology dictates phoneme, pitch, and speaker encoding.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《InsideSSL: Understanding Self-Supervised Speech Representations using a Model-Centric Perspective》所界定。 从摘要看，作者主要围绕 wav2vec、hubert 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that varying training objectives induce distinct regimes of acoustic compression and manifold unfolding. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：wav2vec, hubert。 |

---
## 🏷️ TTS

### 1. WordVoice: Explicit and Decoupled Multi-Dimensional Word-Level Control for LLM-Based TTS

👤 **作者**: Sihang Nie, Jinxin Ji, Xiaofen Xing, Deyi Tuo, Chengbin Jin, Jialong Mai, Xiangmin Xu
🔗 **来源**: [https://arxiv.org/abs/2607.06461v1](https://arxiv.org/abs/2607.06461v1)

**摘要**
> While recent Large Language Model (LLM)-based Text-to-Speech (TTS) systems have achieved remarkable naturalness, they predominantly rely on implicit end-to-end generation paradigms, resulting in coarse-grained control. In scenarios demanding precise stylistic interventions and strict temporal alignment, such as audiobook narration and video dubbing, the inability to explicitly manipulate word-level acoustic attributes remains a critical bottleneck. This limitation is primarily amplified by the severe scarcity of fine-grained annotated datasets and the architectural challenge of integrating multi-dimensional control signals into discrete autoregressive generation. To address this, we propose a unified framework for highly precise word-level control. First, we construct WordVoice-5A, a massive 4.7k-hour bilingual dataset featuring five-dimensional word-level annotations (duration, boundary, energy, pitch and tone) developed through a rigorous linguistically-guided pipeline. Second, we introduce WordVoice to transform the implicit generation process into an explicit, highly controllable paradigm. Specifically, we introduce a bound-token mechanism within the LLM to formulate an explicit ``acoustic planning'' process, enabling adaptive multi-task prosodic planning and flexible manual intervention. Furthermore, we augment the token-to-waveform stage with a fine-grained acoustic modulation module, bridging the resolution gap to strictly align word-level attributes between highly compressed discrete tokens and continuous waveforms. Extensive experiments demonstrate that WordVoice achieves superior, decoupled control over multiple acoustic dimensions while maintaining competitive zero-shot synthesis stability. The code and audio samples are publicly available at https://xxh333.github.io/wordvoice-demo/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《WordVoice: Explicit and Decoupled Multi-Dimensional Word-Level Control for LLM-Based TTS》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While recent Large Language Model (LLM)-based Text-to-Speech (TTS) systems have achieved remarkable naturalness, they predominantly rely on implicit end-to-end generation paradigms, resulting in coarse-grained control. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

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

### 1. Goodbye Equal Error Rate, Hello Local Information Disclosure: Evaluating Voice Anonymisation against 1-to-N Linkage Threats

👤 **作者**: Dāvis Šterns, Konstantinos Drossos, Natasha Fernandes, Tom Bäckström, Catuscia Palamidessi
🔗 **来源**: [https://arxiv.org/abs/2607.06259v1](https://arxiv.org/abs/2607.06259v1)

**摘要**
> Voice anonymisation aims to protect speaker identity. Currently, its empirical privacy evaluation heavily relies on the Equal Error Rate (EER). Originally designed for biometric verification, EER aggregates scores globally, implicitly assuming an attacker is only trying to verify if two specific voice samples match (a 1-to-1 comparison). This introduces a threat model mismatch with real-world database linkage attacks, where an attacker searches across a fixed set of N enrolled identities (a 1-to-N closed-set search), allowing global averages to obscure localised privacy failures. While recent 1-to-N metrics address this aggregation issue, they abstract away the magnitude of the biometric evidence. In this paper, we propose a modular, information-theoretic evaluation framework explicitly designed for the 1-to-N linkage threat model. Within this framework, our core metric, Local Information Disclosure (LID), quantifies the exact privacy loss of a single trial utterance in bits by calibrating its raw similarity scores into the attacker's posterior confidence for each enrolled identity. Evaluating top-performing systems from the VoicePrivacy 2024 Challenge reveals that systems exhibiting near-perfect EERs (48 %) can still suffer from localised vulnerabilities with worst-case disclosures reaching 1 bit per trial utterance (effectively doubling the attacker's success rate over a random guess). We demonstrate that adopting localised privacy metrics is essential for capturing worst-case risks and aligning with strict privacy regulations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Goodbye Equal Error Rate, Hello Local Information Disclosure: Evaluating Voice Anonymisation against 1-to-N Linkage Threats》所界定。 从摘要看，作者主要围绕 goodbye、equal、error 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We demonstrate that adopting localised privacy metrics is essential for capturing worst-case risks and aligning with strict privacy regulations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：goodbye, equal, error。 |

---
### 2. Learning-based Physics-Constrained Neural Kernel for Sound Field Estimation With Source-Position-Dependent Directional Weighting

👤 **作者**: Mattia Marella, Shoichi Koyama
🔗 **来源**: [https://arxiv.org/abs/2607.06274v1](https://arxiv.org/abs/2607.06274v1)

**摘要**
> A learning-based physics-constrained neural kernel for sound field estimation is proposed. Sound field estimation aims to estimate the spatial distribution of an acoustic field from a discrete set of microphone measurements, which have a wide range of applications. Among existing sound field estimation methods, kernel-regression-based methods offer a flexible and principled framework for incorporating physical constraints and allow inference through linear operation. It is also possible to adapt the kernel function to the target acoustic environment by representing the directional weighting function as an implicit neural representation (INR) and optimizing hyperparameters using measurements. However, the kernel function is generally optimized for single snapshot measurements of the microphones, which can lead to strong overfitting and poor generalization. We propose a source-position-dependent INR for the directional weighting function, enabling the kernel function to capture common directional patterns and to generalize to unseen source positions in the target acoustic environment. Experimental results indicate that our proposed method outperforms the snapshot-based method by estimating a directional weighting function that matches the directivity of the target sound field.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Learning-based Physics-Constrained Neural Kernel for Sound Field Estimation With Source-Position-Dependent Directional Weighting》所界定。 从摘要看，作者主要围绕 learning-based、physics-constrained、neural 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results indicate that our proposed method outperforms the snapshot-based method by estimating a directional weighting function that matches the directivity of the target sound field. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：learning-based, physics-constrained, neural。 |

---
### 3. Designing Maintainable Hybrid Generative Systems: A Quantum-Inspired Approach to Automated Music Harmony Generation

👤 **作者**: Josef Pavlicek
🔗 **来源**: [https://arxiv.org/abs/2607.06296v1](https://arxiv.org/abs/2607.06296v1)

**摘要**
> This paper presents the design and evaluation of a maintainable hybrid generative architecture for automated music harmony generation from melody. The proposed system combines quantum-inspired candidate exploration over overlapping melodic contexts with explicit rule-based optimization to balance generative flexibility and structural control. The architecture is evaluated using explicit and reproducible metrics covering structural coherence, functional agreement, harmonic similarity, and robustness. The results show that the proposed approach produces harmonizations that preserve tonal structure and cadential behavior while allowing multiple valid harmonic realizations. Furthermore, the optimization layer improves structural coherence, stability, and predictability without requiring a training corpus. The study demonstrates that transparent and controllable hybrid generative systems can be systematically designed and evaluated within the context of Information Systems Development.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Designing Maintainable Hybrid Generative Systems: A Quantum-Inspired Approach to Automated Music Harmony Generation》所界定。 从摘要看，作者主要围绕 designing、maintainable、hybrid 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that the proposed approach produces harmonizations that preserve tonal structure and cadential behavior while allowing multiple valid harmonic realizations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：designing, maintainable, hybrid。 |

---
### 4. ForestIR: Physics-Informed Forest Sound Simulation for Array-Based Bioacoustic Remote Sensing

👤 **作者**: Xin Shen, Jennifer N. Kampe, Changwoo J. Lee, Braden Scherting, Panu Somervuo, Ari Lehtiö, Sandro von Brandenburg, Ossi Nokelainen, Otso Ovaskainen, David B. Dunson
🔗 **来源**: [https://arxiv.org/abs/2607.06299v1](https://arxiv.org/abs/2607.06299v1)

**摘要**
> Microphone array-based passive acoustic monitoring is increasingly used for biodiversity sensing in forests. However, design and evaluation of array systems and configurations remains difficult since field recordings are costly, difficult to reproduce, and provide limited control over forest and atmospheric conditions. We present ForestIR, a physics-informed and reproducible simulation framework that links forest and environmental conditions to microphone-array recordings for bioacoustic remote sensing. Through a more realistic sound propagation method and a systematic control over array design and environmental factors, ForestIR provides a practical simulation framework for optimizing array-based monitoring systems, especially for sound source localization purposes. ForestIR generates source-microphone impulse responses (IRs) under user-controlled forest and atmospheric conditions, and renders synthetic array recordings by convolving test signals with controlled background noise. We evaluate and demonstrate realistic features of ForestIR through experiments based on localization sensitivity to forest layout and atmospheric conditions, and also comparison between simulated IRs with sine-sweep IR measurements from a field experiment. ForestIR provides a practical way to test how forest and ground conditions, atmospheric state, and array geometry affect bioacoustic localization, and can support microphone-array design, robustness testing, and synthetic-data generation for passive acoustic monitoring.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ForestIR: Physics-Informed Forest Sound Simulation for Array-Based Bioacoustic Remote Sensing》所界定。 从摘要看，作者主要围绕 forestir、physics-informed、forest 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We evaluate and demonstrate realistic features of ForestIR through experiments based on localization sensitivity to forest layout and atmospheric conditions, and also comparison between simulated IRs with sine-sweep IR measurements from a field experiment. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：forestir, physics-informed, forest。 |

---
### 5. Precise Video-to-Audio Generation with Cross-Modal Alignment in Latent Space

👤 **作者**: Thanh V. T. Tran, Ngoc-Son Nguyen, Luong Tran, Long-Khanh Pham, Paarth Neekhara, Shezheen Hussain, Van Nguyen
🔗 **来源**: [https://arxiv.org/abs/2607.06405v1](https://arxiv.org/abs/2607.06405v1)

**摘要**
> Video-to-audio (V2A) generation aims to synthesize realistic audio that is both semantically consistent with and temporally synchronized to a silent video. Despite recent progress, many methods still rely on multi-stage training, resulting in high computational costs and long runtimes, or transform visual input into text to leverage pretrained text-to-audio models, sacrificing fine-grained temporal cues. To overcome these limitations, we propose Flowley, an end-to-end, single-stage training architecture that produces soundtracks by combining visual features with textual prompts. Crucially, we introduce Progressive Soft-masked Cross-Attention, which embeds audio-visual synchronization directly within its attention mechanism, adding zero additional computational cost compared to standard attention layers. We further observe that existing V2A benchmarks lack sound-oriented descriptive captions, which can potentially degrade the quality of the synthesized audio. To remedy this, we propose SoundCap, a plug-and-play pipeline for creating detailed, sound-aware captions that guide the model. Remarkably, without integrating any pretrained audio-visual alignment modules, Flowley achieves state-of-the-art performance on VGGSound across multiple metrics. Moreover, by incorporating SoundCap, we further exceed the performance of the strongest existing close-sourced methods in terms of audio quality in the zero-shot setting.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Precise Video-to-Audio Generation with Cross-Modal Alignment in Latent Space》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Remarkably, without integrating any pretrained audio-visual alignment modules, Flowley achieves state-of-the-art performance on VGGSound across multiple metrics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
