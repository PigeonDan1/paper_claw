<div align="center">

# 📰 Paper Claw

**2026-07-21**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-20 12:27:53 CST → 2026-07-21 12:01:09 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 1 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 3 篇新论文，主要分布在 TTS 1, Enhancement 1, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

### 1. Harness TTS: Towards Context-Aware Expressive Speech Synthesis with Harness Layer

👤 **作者**: Shengfan Shen, Di Wu, Xingchen Song, Dinghao Zhou, Pengyu Cheng, Sixiang Lyu, Jian Luan, Shuai Wang
🔗 **来源**: [https://arxiv.org/abs/2607.17900v1](https://arxiv.org/abs/2607.17900v1)

**摘要**
> Expressive speech synthesis for voice assistants requires flexible style control that adapts to explicit requests and broader interaction context. We propose Harness TTS, a lightweight control layer that wraps around a TTS engine to externalize and govern its expressive behavior. It reformulates style control as closed-set prompt-tool routing: offline, a compact registry of stylistic prompt tools is constructed with structured metadata; online, an LLM planner selects the appropriate tool based on a priority-aware observation schema, and the TTS executor synthesizes speech using the corresponding prompt audio. We evaluate Harness TTS on both routing and synthesis tasks. In routing, Qwen3-4B achieves Top-1 accuracies of 74.3%, 43.0%, and 64.6% on explicit, implicit, and conflict subsets. For synthesis, experiments on CosyVoice3 and VoxCPM2 show that Harness TTS outperforms instruction-only control, achieving higher instruction-following win rates (margins of 23.1-35.6 points on CosyVoice3 and 13.8-20.0 points on VoxCPM2) and improving UTMOSv2 scores by 0.11-0.38. Moreover, the 4B planner delivers its first tool recommendation in under 50 ms in standard mode, introducing negligible latency for real-time interaction. These results demonstrate that equipping TTS engines with a dedicated Harness layer offers a practical, auditable, and context-aware solution for voice assistant expression control.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Harness TTS: Towards Context-Aware Expressive Speech Synthesis with Harness Layer》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In routing, Qwen3-4B achieves Top-1 accuracies of 74.3%, 43.0%, and 64.6% on explicit, implicit, and conflict subsets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech synthesis。 |

---
## 🏷️ Enhancement

### 1. Dense-Sparse Dynamic Time Warping for Customizing Piano Concerto Accompaniments

👤 **作者**: TJ Tsai, Kavi Dey, Yigitcan Ozer, Meinard Muller
🔗 **来源**: [https://arxiv.org/abs/2607.18189v1](https://arxiv.org/abs/2607.18189v1)

**摘要**
> In this study, we explore how pianists can customize Music Minus One (MMO) concerto accompaniments to match their playing style. Bypassing the need for a symbolic score, often not available digitally, we use three types of audio data: solo piano recordings, MMO orchestra-only recordings, and mixed recordings of both piano and orchestra (e.g., from YouTube). The mixed recording serves as an intermediary reference to align the solo and orchestra parts, with only the orchestral part being adjusted through time-scale modification to synchronize with the user's playing. The main challenge with estimating these alignments is the spectral mismatch between recordings containing different musical parts. Motivated by this application scenario, we introduce Dense-Sparse DTW, a variant of Dynamic Time Warping (DTW) that is designed to improve robustness of alignments to spectral mismatch by focusing on aligning a selected subset of audio frames containing prominent timing cues. We collect and annotate data from four piano concerto movements and establish a framework for generating and evaluating customized accompaniment recordings. On this benchmark, we show that Dense-Sparse DTW has better or comparable performance than more complex approaches based on source separation and spectral subtraction techniques.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Dense-Sparse Dynamic Time Warping for Customizing Piano Concerto Accompaniments》所界定。 从摘要看，作者主要围绕 source separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Motivated by this application scenario, we introduce Dense-Sparse DTW, a variant of Dynamic Time Warping (DTW) that is designed to improve robustness of alignments to spectral mismatch by focusing on aligning a selected subset of audio frames containing prominent timing cues. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Audio Cross Verification Using Dual Alignment Likelihood Ratio Test

👤 **作者**: Heidi Lei, Arm Wonghirundacha, Irmak Bukey, TJ Tsai
🔗 **来源**: [https://arxiv.org/abs/2607.18190v1](https://arxiv.org/abs/2607.18190v1)

**摘要**
> This paper explores a way to verify that audio has not been maliciously tampered in a specific context: short viral videos taken from news recordings. Rather than trying to detect artifacts of tampering (internal inconsistency), we focus on positively verifying a query against a trusted source such as a news recording (external consistency). We propose a method for cross verifying a short audio query against a reference recording from which it was taken. Our approach is to define two hypotheses (non-tampered vs tampered), calculate the most likely alignment between query and reference for each hypothesis, and then perform a likelihood ratio test on the two alignments. We show that this method is fast to compute, much more robust than using MFCC features with Euclidean distance, and has the key benefit of explainability. Our cross verification approach provides an alternative perspective and complementary tool to existing tampering detection methods.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Audio Cross Verification Using Dual Alignment Likelihood Ratio Test》所界定。 从摘要看，作者主要围绕 audio、cross、verification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that this method is fast to compute, much more robust than using MFCC features with Euclidean distance, and has the key benefit of explainability. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio, cross, verification。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
