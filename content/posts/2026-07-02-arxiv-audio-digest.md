<div align="center">

# 📰 Paper Claw

**2026-07-02**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-01 13:13:12 CST → 2026-07-02 12:49:35 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 0 篇

> 💡 今日共收录 3 篇新论文，主要分布在 ASR 1, TTS 1, Paralinguistics 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. NPUsper: Eliminating Redundant Computation for Real-Time Whisper on Mobile NPUs

👤 **作者**: Sihyeon Lee, Hojeong Lee, Sungwon Woo, Chengpo Yan, Suman Banerjee, Seyeon Kim
🔗 **来源**: [https://arxiv.org/abs/2607.01108v1](https://arxiv.org/abs/2607.01108v1)

**摘要**
> We present NPUsper, a live transcription system that makes Whisper efficient on mobile NPUs by eliminating redundant computation. To avoid the heavy padding used by prior streaming systems, NPUsper detects hallucinated tokens online from temporal patterns in decoder cross-attention, allowing each inference round to process short audio inputs with minimal carryover. For efficient mobile-NPU execution, we propose controlled unrolling, which executes autoregressive decoding as K-step chunk graphs, removing unnecessary KV-cache computation and reducing graph-dispatch overhead. NPUsper achieves up to 4.84x lower per-word latency, up to 33.2x lower time-to-first-token (TTFT), and up to 88.64% lower average power consumption compared with baselines, while maintaining comparable transcription accuracy. The code is available at https://github.com/npusper/NPUsper.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《NPUsper: Eliminating Redundant Computation for Real-Time Whisper on Mobile NPUs》所界定。 从摘要看，作者主要围绕 whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：NPUsper achieves up to 4.84x lower per-word latency, up to 33.2x lower time-to-first-token (TTFT), and up to 88.64% lower average power consumption compared with baselines, while maintaining comparable transcription accuracy. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：whisper。 |

---
## 🏷️ TTS

### 1. A Geometric Perspective on Composable Emotion Steering in Text-to-Speech Models

👤 **作者**: Siyi Wang, James Bailey, Ting Dang
🔗 **来源**: [https://arxiv.org/abs/2607.00946v1](https://arxiv.org/abs/2607.00946v1)

**摘要**
> While prior work has explored emotion control in hybrid text-to-speech systems, the geometric properties of these modules, and their implications for steerability, remain poorly understood. We present the first comparative study of speech language model (SLM) and conditional flow-matching (CFM) modules as activation steering sites for mixed emotion speech synthesis. We first characterize emotion representations using linear probing and local intrinsic dimensionality (LID), and then evaluate single-site and joint steering for mixed-emotion synthesis. Our results show that SLM offers a clean, low-dimensional emotion-specific subspace with strong speaker--emotion disentanglement, while CFM exhibitspoor cross-speaker generalization due to speaker--emotion entanglement. Joint steering increases emotion intensity but degrades proportional control and speech quality on in-distribution data. These findings provide practical guidance for multi-site activation steering in hybrid TTS systems and highlight the importance of representation geometry in controllable speech generation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《A Geometric Perspective on Composable Emotion Steering in Text-to-Speech Models》所界定。 从摘要看，作者主要围绕 speech language model、text-to-speech、tts system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that SLM offers a clean, low-dimensional emotion-specific subspace with strong speaker--emotion disentanglement, while CFM exhibitspoor cross-speaker generalization due to speaker--emotion entanglement. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model, text-to-speech, tts system。 |

---
## 🏷️ Enhancement

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

### 1. Disentangling Speaker and Language Effects in Cross-Lingual Speaker Verification for Iberian Languages

👤 **作者**: Pol Buitrago, Javier Hernando
🔗 **来源**: [https://arxiv.org/abs/2607.01161v1](https://arxiv.org/abs/2607.01161v1)

**摘要**
> Cross-lingual speaker verification (SV) systems typically exhibit performance degradation when enrollment and test utterances are spoken in different languages. However, standard evaluation protocols confound language mismatch with inter-speaker variability, as evaluation is generally performed with different speakers across languages. In this work, we introduce a bilingual same-speaker evaluation set for five Iberian languages, enabling analysis of cross-lingual SV under constant speaker identity. We apply this setup to a HuBERT-based SV system previously shown to exhibit strong language dependence, and analyze results using the Cross-Lingual Transfer Matrix (CLTM) to study pairwise cross-lingual transfer. Our results show that speaker-related variability accounts for part of the observed degradation, but language mismatch remains the main driver of cross-lingual performance loss. These findings provide a more precise characterization of language dependence in cross-lingual SV.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Disentangling Speaker and Language Effects in Cross-Lingual Speaker Verification for Iberian Languages》所界定。 从摘要看，作者主要围绕 hubert、speaker verification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We apply this setup to a HuBERT-based SV system previously shown to exhibit strong language dependence, and analyze results using the Cross-Lingual Transfer Matrix (CLTM) to study pairwise cross-lingual transfer. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：hubert, speaker verification。 |

---
## 🏷️ Audio

> 📭 今日该分类暂无新论文。

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
