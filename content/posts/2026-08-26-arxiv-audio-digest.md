<div align="center">

# 📰 Paper Claw

**2026-08-26**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-25 10:09:40 CST → 2026-08-26 10:15:40 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 5 篇新论文，主要分布在 Enhancement 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. REDnet: Recursive Encoder and Decoder for Speech Separation under Unknown Number of Speakers and Variable Number of Microphones

👤 **作者**: Fulin Wu, Zhong-Qiu Wang
🔗 **来源**: [https://arxiv.org/abs/2608.24659v1](https://arxiv.org/abs/2608.24659v1)

**摘要**
> We propose $\textit{recursive encoder and decoder}$ (RED) for building a single deep neural network (DNN) model that can separate multi-speaker mixtures containing unknown numbers of speakers and variable numbers of microphones arranged in an unknown geometry, a task that has not been studied yet. The decoder of RED recursively detects whether there are active speakers left and separates one speaker at a time. It is designed to be trained in an end-to-end fashion to improve separation performance. The encoder of RED recursively encodes each microphone channel of the input mixture, sequentially incorporating spatial cues. Combining both, the DNN can be trained to separate mixtures not only with unknown numbers of speakers but also with variable numbers of microphones, achieving state-of-the-art performance on multiple public datasets.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《REDnet: Recursive Encoder and Decoder for Speech Separation under Unknown Number of Speakers and Variable Number of Microphones》所界定。 从摘要看，作者主要围绕 speech separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：It is designed to be trained in an end-to-end fashion to improve separation performance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. CoSTALA: Compositional Spatio-Temporal Audio-Language Alignment via Multi-Grain Hierarchical Contrastive Learning

👤 **作者**: Peiwei Ren, Jinbo Hu, Fang Kang, Shan Liang, Yin Cao
🔗 **来源**: [https://arxiv.org/abs/2608.24374v1](https://arxiv.org/abs/2608.24374v1)

**摘要**
> Conventional audio language models (ALMs) have made significant progress in achieving alignment between auditory and textual representations, including recent explorations in spatial audio. However, in daily spatial scenarios, they still cannot effectively process multi-event audio sequences. Current approaches primarily rely on coarse-grained contrastive learning with global auditory and textual features, lacking the resolution to distinguish multiple sequential events. To overcome these limitations, we propose CoSTALA-a novel training paradigm that transitions from purely global alignment to fine-grained spatio-temporal reasoning. By constructing a multi-granularity hierarchical loss function system, we achieve explicit modeling of temporal dependencies, and successfully anchors individual acoustic events to preserve their semantic purity. Extensive experiments demonstrate that CoSTALA significantly establish a powerful new framework for spatio-temporal audio understanding.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CoSTALA: Compositional Spatio-Temporal Audio-Language Alignment via Multi-Grain Hierarchical Contrastive Learning》所界定。 从摘要看，作者主要围绕 costala、compositional、spatio-temporal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Conventional audio language models (ALMs) have made significant progress in achieving alignment between auditory and textual representations, including recent explorations in spatial audio. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：costala, compositional, spatio-temporal。 |

---
### 2. Array-Agnostic Ambisonics Encoding via Diffusion Posterior Sampling

👤 **作者**: Amit Milstein, Nir Shlezinger, Boaz Rafaely
🔗 **来源**: [https://arxiv.org/abs/2608.24558v1](https://arxiv.org/abs/2608.24558v1)

**摘要**
> Spatial audio enhances user immersion by reproducing 3D sound fields, with Ambisonics being a widely adopted representation. While Ambisonics is theoretically independent of the recording setup, practical microphone arrays introduce hardware-dependent encoding artifacts. Moreover, existing data-driven solutions lack flexibility, as they are typically restricted to fixed array geometries. To overcome these limitations, we propose ADEPS, a generative framework that explicitly embeds the physical acquisition model into the inference process. By leveraging this formulation, ADEPS effectively compensates for array-specific distortions while enabling zero-shot encoding across arbitrary array topologies. We train the underlying generative prior in an unsupervised manner solely on target Ambisonic representations. Extensive evaluations across diverse simulated and real microphone arrays demonstrate that ADEPS consistently outperforms both traditional linear and parametric baselines in spatial fidelity and spectral quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Array-Agnostic Ambisonics Encoding via Diffusion Posterior Sampling》所界定。 从摘要看，作者主要围绕 array-agnostic、ambisonics、encoding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive evaluations across diverse simulated and real microphone arrays demonstrate that ADEPS consistently outperforms both traditional linear and parametric baselines in spatial fidelity and spectral quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：array-agnostic, ambisonics, encoding。 |

---
### 3. Visually-Guided Spatial Audio Generation for $360^\circ$ In-the-Wild Speech Scenes

👤 **作者**: Qingyu Luo, Peng Zhang, Wenwu Wang, Philip J. B. Jackson
🔗 **来源**: [https://arxiv.org/abs/2608.24579v1](https://arxiv.org/abs/2608.24579v1)

**摘要**
> Spatial audio is a key component of immersive $360^\circ$ media, yet high-quality spatial capture remains limited in real-world speech-dominant scenes. We study visually guided First-Order Ambisonics (FOA) speech spatialization in the wild: given aligned $360^\circ$ video and an omnidirectional audio track, we recover the missing directional FOA components. To support this task, we introduce YT-SPEECH, a speech-oriented $360^\circ$ video-FOA dataset curated from YouTube. We propose a two-stage Localizer-Renderer framework, where an audio-visual segmentation backbone provides frame-wise spatial heatmaps and a conditional complex-domain U-Net reconstructs directional FOA signals from the omnidirectional channel. A confidence-based gating strategy stabilizes conditioning under ambiguous acoustic conditions. Experiments show improved reconstruction fidelity, spatial accuracy, and perceptual speech quality relative to ablated variants and prior approaches.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Visually-Guided Spatial Audio Generation for $360^\circ$ In-the-Wild Speech Scenes》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show improved reconstruction fidelity, spatial accuracy, and perceptual speech quality relative to ablated variants and prior approaches. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---
### 4. Investigating voiced and unvoiced regions of speech for audio deepfake detection

👤 **作者**: Ganesh Sivaraman, Hemlata Tak, Elie Khoury
🔗 **来源**: [https://arxiv.org/abs/2608.24639v1](https://arxiv.org/abs/2608.24639v1)

**摘要**
> Deep neural network based deepfake detection systems have achieved high levels of accuracy on benchmark datasets and competitions. However, most models lack interpretability. It is challenging to extract reasoning from the network that can convince the human evaluator to trust the decision. Humans often rely on acoustic cues like unnatural pitch jitter, robotic intonation, acoustic artifacts, and unnatural sounding fricatives to judge the quality of the synthetic audio. This study explores the role played by the voiced and unvoiced regions of speech in discriminating synthetic from bonafide speech. A measure of signal periodicity is used to analyze speech into voiced and unvoiced components. Then, the graph attention based AASIST detection system is trained independently on each component. This work compares the accuracy of deepfake detection system using voiced and unvoiced components and analyzes the results on the MLAAD dataset. Our results show that unvoiced regions are particularly more effective in distinguishing synthetic (deepfake) speech from bonafide, and achieves an equal error rate of 6.62%. When combined with voice regions through score-level fusion, the overall performance improves further, yielding a 5.82% EER, a relative improvement of 49% over the baseline system that uses the full audio.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Investigating voiced and unvoiced regions of speech for audio deepfake detection》所界定。 从摘要看，作者主要围绕 investigating、voiced、unvoiced 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Deep neural network based deepfake detection systems have achieved high levels of accuracy on benchmark datasets and competitions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：investigating, voiced, unvoiced。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
