<div align="center">

# 📰 Paper Claw

**2026-08-27**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-26 10:15:40 CST → 2026-08-27 18:40:58 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 Speech LLM 1, Paralinguistics 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. VoiceMem: Streaming Dual-Brain Memory for Real-Time Interaction

👤 **作者**: Zhifei Xie, Jiaqi Lang, Ze An, Yifan Zhao, Dongchao Yang, Kai Li, Ziyang Ma, Mingbao Lin, Chunyan Miao, Shuicheng Yan
🔗 **来源**: [https://arxiv.org/abs/2608.26005v1](https://arxiv.org/abs/2608.26005v1)

**摘要**
> Conversational systems, such as duplex speech language models (SLMs), still lack a streaming, accurate, and empathetic memory system as their soul. We introduce VoiceMem, a simple memory architecture with a parallel informational left brain, an emotional right brain, and streaming memory I/O mechanisms. We further build a complete pipeline for memory-aware SLM training, long-horizon evaluation, and decoupled deployment with interchangeable memory backends. Experiments and real-world deployment show three advantages: i) Accuracy: under top-5 retrieval, the left brain outperforms classical systems such as Mem0 at top-200 by nearly 30 points; ii) Emotional & Personal: the right brain, with short- and long-horizon affective attribution and dual-node persona modeling, achieves state-of-the-art performance across three persona benchmarks and improves the aggregate score by 4.29 points over the previous best system; and iii) Real-Time & Cheap: VoiceMem completes retrieval in 134 ms, well within standard VAD latency, adding no extra conversational delay while maintaining high accuracy and low cost. These results show that VoiceMem provides a practical memory foundation for real-time, personalized, and emotionally aware speech interaction.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《VoiceMem: Streaming Dual-Brain Memory for Real-Time Interaction》所界定。 从摘要看，作者主要围绕 speech language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments and real-world deployment show three advantages: i) Accuracy: under top-5 retrieval, the left brain outperforms classical systems such as Mem0 at top-200 by nearly 30 points; ii) Emotional & Personal: the right brain, with short- and long-horizon affective attribution and dual-node persona modeling, achieves state-of-the-art performance across three persona benchmarks and improves the aggregate score by 4.29 points over the previous best system; and iii) Real-Time & Cheap: VoiceMem completes retrieval in 134 ms, well within standard VAD latency, adding no extra conversational delay while maintaining high accuracy and low cost. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

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

### 1. Dissonance Spectrum explicitly models perceptual frequency interactions for better music understanding

👤 **作者**: Tianle Wang, Xinyi Tong, Liangke Zhao, Jishang Chen, Sirui Zhang, Haoxin Zhang, Xin Jin, Duo Xu, Xiaobing Li, Song-Chun Zhu
🔗 **来源**: [https://arxiv.org/abs/2608.25621v1](https://arxiv.org/abs/2608.25621v1)

**摘要**
> Conventional music representations describe acoustic energy over time and frequency but do not explicitly expose relations among simultaneous frequency components. We introduce the \emph{Dissonance Spectrum} (DS), a nonnegative time--frequency representation that applies a tolerance-based rational pitch-relation kernel with logarithmic harmonic distance to a constant-Q spectrum and attributes aggregate pairwise interactions back to individual frequency bins. Controlled music-theory tests show strong ordinal agreement for intervals, harmonic-function connections, and church modes, and weaker but significant agreement across diverse chord voicings. DS is then encoded by a lightweight parallel branch whose zero-initialized residual projection preserves the baseline function at initialization. Across six paired training seeds in open-ended music question answering and categorical and dimensional music emotion recognition, DS obtains the highest mean on every reported endpoint relative to the unchanged baseline, a parameter-matched Gaussian-input branch, and an architecture-matched magnitude-CQT branch. These results support DS as an interpretable, complementary representation, while listener-specific perception and broader task coverage remain open problems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Dissonance Spectrum explicitly models perceptual frequency interactions for better music understanding》所界定。 从摘要看，作者主要围绕 emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Controlled music-theory tests show strong ordinal agreement for intervals, harmonic-function connections, and church modes, and weaker but significant agreement across diverse chord voicings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：emotion recognition。 |

---
## 🏷️ Audio

### 1. Cooperative Multi-Agent Reinforcement Learning for Adaptive Aggregation in Semi-Supervised Federated Learning with non-IID Data

👤 **作者**: Rene Glitza, Luca Becker, Rainer Martin
🔗 **来源**: [https://arxiv.org/abs/2608.25794v1](https://arxiv.org/abs/2608.25794v1)

**摘要**
> Federated Learning (FL) enables distributed training of machine learning models while preserving data privacy. However, FL struggles with heterogeneous, non-IID client data distributions, resulting in sub-optimal and biased global models. In this paper, we propose pFedMARL, a novel approach leveraging Multi-Agent Reinforcement Learning (MARL) with Twin Delayed Deep Deterministic Policy Gradient (TD3) to dynamically adapt aggregation strategies in FL settings. Our method employs a server-side agent adjusting client contributions to optimize global model robustness and client-side agents balancing global and local updates to personalize models effectively without pre-training. We demonstrate superior performance of pFedMARL for training a semi-supervised audio spectrogram transformer, matching or outperforming FedAvg, Ditto, and local training approaches across multiple non-IID scenarios and in the presence of adversarial clients. Our results indicate that pFedMARL actively improves accuracy, robustness, and fairness, making it suitable for real-world deployments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Cooperative Multi-Agent Reinforcement Learning for Adaptive Aggregation in Semi-Supervised Federated Learning with non-IID Data》所界定。 从摘要看，作者主要围绕 cooperative、multi-agent、reinforcement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We demonstrate superior performance of pFedMARL for training a semi-supervised audio spectrogram transformer, matching or outperforming FedAvg, Ditto, and local training approaches across multiple non-IID scenarios and in the presence of adversarial clients. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：cooperative, multi-agent, reinforcement。 |

---
### 2. Why ML-based cough models do not generalize: a systematic cross-dataset evaluation for tuberculosis screening

👤 **作者**: Wensi Zhang, Tomas Teijeiro, Jérôme Thevenot, David Atienza
🔗 **来源**: [https://arxiv.org/abs/2608.25846v1](https://arxiv.org/abs/2608.25846v1)

**摘要**
> Cough acoustics are promising for non-invasive tuberculosis (TB) screening, yet whether machine learning (ML) models capture disease-related acoustics or artifacts of data collection remains unresolved. We evaluated the cross-dataset generalizability of classical ML and deep learning (DL) cough-based TB classifiers across three independent datasets. Despite moderate within-dataset performance (ROC-AUC up to $0.755 \pm 0.056$), both pipelines fail to generalize, with external performance frequently below 0.6, indicating a possible limitation of the data. We further observed audio representations are organized by recording device and dataset rather than TB status, predicted TB probability tracks country-level prevalence in CODA, and device mismatch degrades transfer while device-diverse training improves it. Additionally, a clinical-variable baseline generalizes more consistently (ROC-AUC $0.655 - 0.711$), indicating acquisition-specific variability is a stronger driver of poor generalizability than population shift. High within-dataset performance is not enough. External validation is essential before cough-based TB models are clinically ready.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Why ML-based cough models do not generalize: a systematic cross-dataset evaluation for tuberculosis screening》所界定。 从摘要看，作者主要围绕 ml-based、cough、models 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We further observed audio representations are organized by recording device and dataset rather than TB status, predicted TB probability tracks country-level prevalence in CODA, and device mismatch degrades transfer while device-diverse training improves it. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：ml-based, cough, models。 |

---
### 3. Formal, Executable and Explainable Runtime Monitoring of Spoken Air Traffic Control Operational Procedures

👤 **作者**: Roberto Luvini, Giacomo Longo, Alessandro Armando, Enrico Russo
🔗 **来源**: [https://arxiv.org/abs/2608.25926v1](https://arxiv.org/abs/2608.25926v1)

**摘要**
> Air traffic control procedures are executed through spoken exchanges between controllers and pilots. These interactions are essential to the safety of air transportation: failures in their execution can create severe operational hazards, as evidenced by past fatal accidents. Assessing whether an instruction has been followed requires relating what was said to the aircraft concerned, its state, and the obligations that pilots must meet. We present a runtime verification framework that monitors such procedures by checking controller-pilot exchanges, surveillance data, and onboard observations. The framework parses radio communications into events linked to the entities they concern and merges them with surveillance and onboard observations into a time-stamped trace. The ICAO-derived obligations as formalized as temporal formulas with explicit time bounds and evaluated over execution traces. Every violation is reported along with the breached obligations and the observations that support the verdict. With real traffic, the complete pipeline reaches an F1 of 0.85 against blind human-annotated violations; in 1,495 synthetic situations derived from two public corpora, the monitor logic returns the expected verdict in every case. In two historical accidents reconstructed from official investigation reports, the monitor identifies the same procedural deviations documented by the investigators.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Formal, Executable and Explainable Runtime Monitoring of Spoken Air Traffic Control Operational Procedures》所界定。 从摘要看，作者主要围绕 formal、executable、explainable 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These interactions are essential to the safety of air transportation: failures in their execution can create severe operational hazards, as evidenced by past fatal accidents. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：formal, executable, explainable。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
