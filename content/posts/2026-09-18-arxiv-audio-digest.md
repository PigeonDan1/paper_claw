<div align="center">

# 📰 Paper Claw

**2026-09-18**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-17 13:32:15 CST → 2026-09-18 13:19:52 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 3 篇新论文，主要分布在 ASR 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Model-Agnostic and Language-Agnostic Voice Pipeline Improvement for the Agriculture Domain

👤 **作者**: Aakash Singh, Lakshmi Pedapudi, Chandrashekar M S, Sanyam Singh, Naga Ganesh, Vineet Singh
🔗 **来源**: [https://arxiv.org/abs/2609.20504v1](https://arxiv.org/abs/2609.20504v1)

**摘要**
> FarmerChat is Digital Green's AI-powered agricultural advisory assistant for smallholder farmers, who access it in their own language through text, voice, or photographs. Voice is a critical channel for this population, yet field-recorded speech is challenging for general-purpose automatic speech recognition (ASR) because recordings frequently contain machinery noise, background media, competing speakers, and domain-specific agricultural vocabulary. These conditions disproportionately affect crop, pest, chemical, and quantity terms that carry the meaning of a farmer's query. We present a modular, model-agnostic pipeline for improving ASR quality in FarmerChat without fine-tuning or replacing the underlying ASR model. The pipeline combines gated audio enhancement, speaker diarization and target-speaker selection, ASR, domain-aware correction using a weighted agricultural lexicon, and a quality gate for detecting unreliable transcripts. Only the diarization stage is fine-tuned; all other stages use off-the-shelf models behind common interfaces. We evaluate the pipeline on human-annotated FarmerChat recordings in Hindi, Telugu, and Odia using word error rate (WER) and a domain-weighted error rate that gives greater importance to agricultural terminology. The largest improvements occur on multi-speaker recordings, where target-speaker selection prevents competing speech from entering the transcript. Across the full corpus, the pipeline reduces WER by 16-23% relative on three cloud ASR models and by 5% on an on-device model. On multi-speaker recordings, the reductions are 32-42% for the cloud models and 16% for the on-device model. All reported reductions are statistically significant. These results show that targeted preprocessing, speaker selection, and domain-aware post-processing can substantially improve agricultural speech transcription while preserving the underlying ASR model.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Model-Agnostic and Language-Agnostic Voice Pipeline Improvement for the Agriculture Domain》所界定。 从摘要看，作者主要围绕 automatic speech recognition、speech transcription、audio enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We present a modular, model-agnostic pipeline for improving ASR quality in FarmerChat without fine-tuning or replacing the underlying ASR model. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, speech transcription, audio enhancement。 |

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

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Beyond the Stability--Plasticity Frontier in Streaming Target Speaker Extraction

👤 **作者**: Yuesheng Ma, Linyang He, Nima Mesgarani
🔗 **来源**: [https://arxiv.org/abs/2609.20463v1](https://arxiv.org/abs/2609.20463v1)

**摘要**
> Streaming target speaker extraction must maintain a representation of whom to extract while the target may fall silent, be masked by interference, or drift acoustically away from enrollment. Existing systems typically hold this state as a stored embedding updated by hand-designed rules. Across 22 configurations, including confidence-gated and oracle-activity-gated updates, we show that this family lies on a stability-plasticity frontier: even perfect target-activity information cannot combine robustness to target absence with adaptation to enrollment-mixture mismatch. We therefore meta-train speaker-state dynamics through the closed streaming loop, exposing the updater to its own contaminated evidence. Our proposed 41k-parameter anchored fast-weights (AFW) memory moves beyond the measured heuristic frontier, gaining 3.0 dB over the best heuristic under severe mismatch while staying within 0.9 dB of static enrollment after 30 s of absence, at under 5% runtime overhead. A gated recurrent unit (GRU) control confirms that the gain is not AFW-specific, while AFW is smaller and more interpretable: under severe mismatch, its write residual grows and aligns with the target rather than the interferer. Code is publicly available at https://github.com/ym2976/anchor-fast-weight.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond the Stability--Plasticity Frontier in Streaming Target Speaker Extraction》所界定。 从摘要看，作者主要围绕 beyond、stability--plasticity、frontier 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across 22 configurations, including confidence-gated and oracle-activity-gated updates, we show that this family lies on a stability-plasticity frontier: even perfect target-activity information cannot combine robustness to target absence with adaptation to enrollment-mixture mismatch. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：beyond, stability--plasticity, frontier。 |

---
### 2. A Deep Neural Network for Predicting Continuous Human EEG Across the Auditory Pathway in Response to Sound

👤 **作者**: Thomas J Stoll, Ross K Maddox
🔗 **来源**: [https://arxiv.org/abs/2609.20595v1](https://arxiv.org/abs/2609.20595v1)

**摘要**
> Computational models of auditory physiology commonly target specific responses or stages of the auditory pathway, limiting their ability to integrate findings across experimental paradigms and neural timescales. We present a foundation model of human auditory electrophysiology: a causal neural network trained to map binaural acoustic waveforms directly to high-sample-rate EEG. The model was trained on approximately 250 hours of EEG data from 92 subjects, with varied electrode montages and stimuli spanning tonebursts, speech, and music. We tested whether the model recovered effects of stimulus rate, frequency, and presentation method on auditory brainstem responses (ABRs); subcortical and cortical temporal response functions (TRFs) to continuous speech; and the click-evoked binaural interaction component (BIC). Predicted ABRs and TRFs reproduced established response morphology and stimulus-dependent effects, with model-grand-average correlations falling within the corresponding subject-level human distributions. The model-predicted BIC metrics closely resembled the values reported in the literature. These findings demonstrate that a single audio-to-EEG model can capture auditory physiology across paradigms and timescales, supporting future in silico experimentation and hearing technology applications.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Deep Neural Network for Predicting Continuous Human EEG Across the Auditory Pathway in Response to Sound》所界定。 从摘要看，作者主要围绕 deep、neural、network 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These findings demonstrate that a single audio-to-EEG model can capture auditory physiology across paradigms and timescales, supporting future in silico experimentation and hearing technology applications. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：deep, neural, network。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
