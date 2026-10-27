<div align="center">

# 📰 Paper Claw

**2026-10-27**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-26 13:28:59 CST → 2026-10-27 13:44:29 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 6 篇新论文，主要分布在 Speech LLM 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Integrate the Reward, Don't Sample It: Window Likelihood for Interruptions and Backchannels in Full-Duplex Speech Models

👤 **作者**: Guoqiang Hu, Lichao Zhang, Yizhou Peng, Yuhao Luo, Haifeng Hu, Sallen Sun, Will Yang, Eng Siong Chng
🔗 **来源**: [https://arxiv.org/abs/2610.35581v1](https://arxiv.org/abs/2610.35581v1)

**摘要**
> A full-duplex spoken dialogue model must yield when the user cuts in and hold when the user merely backchannels. Sequence-level RL with a timing reward (GRPO) is the usual recipe; we test its whole-rollout form on four open models and find two failures. A binary window reward gives zero advantage on exactly the windows that most need learning (a zero-gradient trap), and the one score per rollout is spread over listening-state decisions the reward is not written in terms of (credit leakage), so the model talks into silence or stops answering. Both come from sampling a reward that is a known function of a few binary control decisions. We propose \emph{window likelihood} (\WL): sample a continuation per window, but integrate in closed form over the stop decisions it visits and maximise the log-probability of acting correctly---a noisy-OR for yielding, a survival product for holding. On HumDial-FDBench, \WL\ gives the best yield/hold F1 on all six structurally different open models we post-train, exceeds Kyutai's released GRPO checkpoints (trained on different data), and adds no re-opening of the floor on any model.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Integrate the Reward, Don't Sample It: Window Likelihood for Interruptions and Backchannels in Full-Duplex Speech Models》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Sequence-level RL with a timing reward (GRPO) is the usual recipe; we test its whole-rollout form on four open models and find two failures. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：spoken dialogue。 |

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

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Dolphin broadband transient vocalization detection in impulsive ambient noise

👤 **作者**: Hari Vishnu, Jin Xinhui, Mandar Chitre, Simen Hexeberg, Koay Teong Beng
🔗 **来源**: [https://arxiv.org/abs/2610.35641v1](https://arxiv.org/abs/2610.35641v1)

**摘要**
> Passive acoustic monitoring in tropical waters such as those in Southeast Asia is hampered by the persistent, high-level impulsive noise of snapping shrimp. This is a particularly daunting challenge for detecting broadband transient vocalizations of dolphins - clicks, buzzes and burst-pulses. These vocalizations, unlike frequency-modulated whistles, share the broadband, impulsive character of the shrimp snaps and cannot be easily separated from them by frequency-localized or energy-based means. We develop TRIDENT, a lightweight waveform-based detector for these vocalizations, and apply it to 54.2 recorder-months of data from ten island sites around Singapore. We show that the training-data pipeline and the architecture are both important: controlled signal-to-noise-ratio based mixing to generate training data, appropriate normalization and hard negative mining, together steer the detector toward learning transient temporal structure rather than energy shortcuts. A single joint detector handles all three signal types better than specialized models for each, and outperforms established baselines. Applied to long-term recordings, it reveals tightly clustered, predominantly daytime activity, motivating days-with-detections as a robust indicator of cetacean presence.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Dolphin broadband transient vocalization detection in impulsive ambient noise》所界定。 从摘要看，作者主要围绕 dolphin、broadband、transient 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that the training-data pipeline and the architecture are both important: controlled signal-to-noise-ratio based mixing to generate training data, appropriate normalization and hard negative mining, together steer the detector toward learning transient temporal structure rather than energy shortcuts. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dolphin, broadband, transient。 |

---
### 2. Graph Neural Network for Wide-Area 6DoF Ambisonic Rendering

👤 **作者**: Gioele Greco, Filippo Marri, Mirco Pezzoli, Fabio Antonacci
🔗 **来源**: [https://arxiv.org/abs/2610.35741v1](https://arxiv.org/abs/2610.35741v1)

**摘要**
> Wide-area 6DoF rendering from sparse Ambisonic recordings is commonly addressed by interpolating parametric spatial descriptors rather than the waveforms themselves. This preserves the fidelity of a nearby measured signal and avoids phase artifacts caused by mixing distant arrays. However, existing DirAC-based approaches rely on geometric interpolation weights that do not depend on the acoustic scene observed by the microphones. We propose a lightweight Graph Neural Network (GNN) that refines only this interpolation stage. The known Ambisonic arrays and the query position are represented as a graph whose nodes contain local DirAC features and whose edges encode relative distance and directional relations. The network predicts positive query-conditioned weights over the measured arrays, while the target energy, diffuseness, and direction of arrival are reconstructed by an analytical DirAC layer. Experiments on unseen rooms, unseen speech signals, and unseen array configurations show that the proposed weighting improves energy reconstruction and radiation-pattern similarity with respect to baseline interpolation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Graph Neural Network for Wide-Area 6DoF Ambisonic Rendering》所界定。 从摘要看，作者主要围绕 acoustic scene 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on unseen rooms, unseen speech signals, and unseen array configurations show that the proposed weighting improves energy reconstruction and radiation-pattern similarity with respect to baseline interpolation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic scene。 |

---
### 3. Correspondence Is Not Transfer: A Pairing-Controlled Audit of Clinical Audio-Metadata Alignment

👤 **作者**: Liu He, Xi Wang, Jiahong Yuan, Yuanchao Li
🔗 **来源**: [https://arxiv.org/abs/2610.35747v1](https://arxiv.org/abs/2610.35747v1)

**摘要**
> Clinical audio models increasingly align recordings with participant metadata or metadata-derived text. This supervision is useful but ambiguous: the paired target can contain symptoms, demographics, missingness, and cohort structure, not just disease information. We study this ambiguity by making the audio-metadata pairing itself the intervention. Our Pairing-Controlled Transfer Audit trains matched contrastive trajectories under correct pairing, global shuffling, disease-label-preserving shuffling, and label-and-recorded-sex-preserving shuffling. Each endpoint is then frozen and tested with three readouts: profile correspondence, attribute decodability, and matched disease prediction. On UKCOVID, correct improves retrieval and sex decodability over label-only shuffling, showing that the pairing intervention worked. The sex-probe contrast is largely absorbed by the sex-preserving control, while smaller retrieval differences remain. Disease-transfer contrasts, however, remain uncertain. After UKCOVID discovery fixed the pipeline, CODA TB, Cambridge COVID-19 Sounds, and Coswara were rerun as a locked external panel with the same arms, backbones, matching, readout, calibration, primary contrast, and primary metric. The external panel preserves the descriptive separation without proving a universal null. Successful profile correspondence and improved disease transfer are therefore different empirical claims.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Correspondence Is Not Transfer: A Pairing-Controlled Audit of Clinical Audio-Metadata Alignment》所界定。 从摘要看，作者主要围绕 correspondence、transfer、pairing-controlled 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On UKCOVID, correct improves retrieval and sex decodability over label-only shuffling, showing that the pairing intervention worked. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：correspondence, transfer, pairing-controlled。 |

---
### 4. A Robust, Explainable, and Efficient Deep Metric for Speech and General Audio Quality

👤 **作者**: Konstantin Schmidt, Pablo M. Delgado, Andreas Brendel
🔗 **来源**: [https://arxiv.org/abs/2610.35810v1](https://arxiv.org/abs/2610.35810v1)

**摘要**
> We present a robust Speech and Audio Quality Metric (SAQM) that merges features of traditional quality metrics with a CNN trained on a large amount of data using contrastive learning methods. To overcome the problem of limited amounts of human-labeled training data, we propose two pretraining strategies relying on pseudo-labels. One uses an established objective metric PEAQ-2f (based on ITU-R BS.1387) as surrogate loss, the other is based on contrasting a wide range of coding modes by a rule-of-thumb ordering based on expected perceived quality. As a key novelty, our approach lets us generate saliency maps by propagating gradients to identify which feature has the greatest impact on the final metric outcome and enables our system to provide insights regarding the type and extent of distortions present in the tested audio signal. The resulting (SAQM) operates at low computational complexity, performs comparably to (SOTA) metrics on speech while still performing well on general audio content.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Robust, Explainable, and Efficient Deep Metric for Speech and General Audio Quality》所界定。 从摘要看，作者主要围绕 robust、explainable、efficient 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To overcome the problem of limited amounts of human-labeled training data, we propose two pretraining strategies relying on pseudo-labels. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：robust, explainable, efficient。 |

---
### 5. Multimodal Concert Video Editing: System Design and Exploratory Evaluation

👤 **作者**: Lennart Schiweck, Adrian Kempf, Michelle Retig, Moritz Feucht, Tim Mangliers, Benjamin Himpel
🔗 **来源**: [https://arxiv.org/abs/2610.35816v1](https://arxiv.org/abs/2610.35816v1)

**摘要**
> Editing multi-camera concerts requires coordinated decisions about musical relevance, visual quality and cut timing. We present a modular framework that combines instrument activity from multitrack audio, visible instruments and image sharpness with beat-based timing and probabilistic camera selection. An interpretable scoring model links these components to the choice of views over complete shot intervals. Component tests and an exploratory expert study on a four-camera concert yield mixed assessments across the editing variants. The findings motivate extending local audiovisual relevance with contextual and sequence-level criteria. The architecture provides a basis for testing these extensions and studying how component behaviour affects the quality of complete edits.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Multimodal Concert Video Editing: System Design and Exploratory Evaluation》所界定。 从摘要看，作者主要围绕 multimodal、concert、video 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We present a modular framework that combines instrument activity from multitrack audio, visible instruments and image sharpness with beat-based timing and probabilistic camera selection. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：multimodal, concert, video。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
