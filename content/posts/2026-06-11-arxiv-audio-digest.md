<div align="center">

# 📰 Paper Claw

**2026-06-11**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-10 13:07:54 CST → 2026-06-11 13:16:46 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Speech LLM 1, Enhancement 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Which Speech Representation Better Matches Text-Native Reasoning? A Study of Speech-Text Alignment on Frame Rate and Representation

👤 **作者**: Zhen Ye, Xu Tan, Yiming Li, Guangyan Zhang, Chimin Chan, Haohe Liu, Zhengxi Liu, Hongzhan Lin, Zheqi Dai, Xinshen Zhang, Peiwen Sun, Qiuqiang Kong, Wei Xue
🔗 **来源**: [https://arxiv.org/abs/2606.12199v1](https://arxiv.org/abs/2606.12199v1)

**摘要**
> Spoken dialogue models typically start from text LLM backbones, yet reasoning often degrades when conditioning on speech instead of text. We attribute part of this modality gap to a temporal-granularity mismatch: speech tokens are temporally redundant and far longer than text under matched semantics, diluting per-token semantic density and weakening text-native reasoning dynamics. We study speech token design as a representation selection problem and sweep frame rates under a frozen LLM backbone with a fixed information rate. To make low frame rates feasible, we introduce factorized FSQ and a lightweight non-autoregressive audio LM head, scaling capacity to nearly 300\,bits/frame without sacrificing efficient prediction. With the bottleneck removed, we sweep frame rates (50$\rightarrow$2.08\,Hz) and alignment depth, and observe a consistent best regime for speech QA at 4.17\,Hz with intermediate-layer representation alignment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Which Speech Representation Better Matches Text-Native Reasoning? A Study of Speech-Text Alignment on Frame Rate and Representation》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We attribute part of this modality gap to a temporal-granularity mismatch: speech tokens are temporally redundant and far longer than text under matched semantics, diluting per-token semantic density and weakening text-native reasoning dynamics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken dialogue。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. HALO: Half-Frame-Rate Adaptive Learnable Operator for Lightweight STFT-Based Speech Enhancement

👤 **作者**: Jiadong Zhao, Dahan Wang, Yu Sun, Leyan Yang, Xiaobin Rong, Shiruo Sun, Yuxiang Hu, Jing Lu
🔗 **来源**: [https://arxiv.org/abs/2606.12328v1](https://arxiv.org/abs/2606.12328v1)

**摘要**
> STFT-based speech enhancement typically adopts overlapping analysis frames. While overlap is essential for stable STFT processing, it makes adjacent frames highly correlated, causing redundant computation in lightweight models. We propose Half-frame-rate Adaptive Learnable Operator (HALO), a causal plug-in module that halves the internal frame rate without altering the STFT procedure. Broadly applicable to many lightweight models, HALO applies adaptive rate reduction before the backbone and restoration afterward, reconstructing the full-rate spectrum on the original STFT grid. Both reduction and restoration are implemented with lightweight dynamic convolutions. By halving the processed frame rate, HALO reduces backbone compute cost with no added algorithmic latency, freeing budget for channel widening. Experiments on the DNS3 dataset show consistent gains across diverse lightweight models under matched complexity, demonstrating the effectiveness of reducing overlap-induced redundancy.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《HALO: Half-Frame-Rate Adaptive Learnable Operator for Lightweight STFT-Based Speech Enhancement》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the DNS3 dataset show consistent gains across diverse lightweight models under matched complexity, demonstrating the effectiveness of reducing overlap-induced redundancy. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. PianoKontext: Expressive Performance Rendering from Deadpan Context

👤 **作者**: Dmitrii Gavrilev
🔗 **来源**: [https://arxiv.org/abs/2606.12282v1](https://arxiv.org/abs/2606.12282v1)

**摘要**
> Expressive performance rendering (EPR) aims to generate realistic performances constrained on sequences of notes. However, flow matching audio editing models manipulate only synchronized music samples of the same duration, limiting their understanding of expressive timing. We introduce PianoKontext, a flow matching rendering model for classical piano music that generates variable-length performances in the latent space of a pretrained Music2Latent model. We synthesize MIDI scores into deadpan audio and employ Dynamic Time Warping (DTW) in the latent space to construct paired data for training. The aligned embeddings are concatenated in DiT blocks, allowing for a simple and effective learning of the dependencies between the score and performances. Audio samples are available at our demo page: https://realfolkcode.github.io/pianokontext_demo/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《PianoKontext: Expressive Performance Rendering from Deadpan Context》所界定。 从摘要看，作者主要围绕 pianokontext、expressive、performance 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, flow matching audio editing models manipulate only synchronized music samples of the same duration, limiting their understanding of expressive timing. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：pianokontext, expressive, performance。 |

---
### 2. Fast-SDE: Efficient Single-Microphone Sound Source Distance Estimation in Reverberant Environments

👤 **作者**: Jiang Wang, Runwu Shi, Yaozhong Kang, Benjamin Yen, Takeshi Ashizawa, Kazuhiro Nakadai
🔗 **来源**: [https://arxiv.org/abs/2606.12339v1](https://arxiv.org/abs/2606.12339v1)

**摘要**
> Sound source distance estimation (SDE) is a critical capability in human-robot interaction. An inappropriate interaction distance not only reduces the reliability of speech acquisition and understanding, but also compromises the naturalness and comfort of the interaction. Most existing SDE methods rely on microphone arrays, however, multi-microphone systems typically require careful hardware synchronization, geometric calibration, and additional space and computational resources, which limits applicability to size-constrained and computability-limited embodied platforms. To alleviate these issues, we propose Fast-SDE, a lightweight single-microphone SDE framework that is suited for deployment on robot platforms with limited computational resources and strict size constraints. Specifically, Fast-SDE employs a subband-based backbone that decomposes the frequency axis into multiple subbands, rather than processing the entire spectrum with a wide full-band backbone. A shared subband encoder then maps each subband to a compact latent representation and learns the relationship between acoustic structure and time-frequency patterns. Finally, a lightweight regression head converts the fused subband representations into the estimated distance. Extensive simulation and real-world experiments demonstrate the merits of the proposed method. To benefit the broader research community, we have open-sourced our code at https://github.com/JiangWAV/FAST-SDE.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Fast-SDE: Efficient Single-Microphone Sound Source Distance Estimation in Reverberant Environments》所界定。 从摘要看，作者主要围绕 fast-sde、efficient、single-microphone 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive simulation and real-world experiments demonstrate the merits of the proposed method. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：fast-sde, efficient, single-microphone。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
