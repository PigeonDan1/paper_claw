<div align="center">

# 📰 Paper Claw

**2026-10-07**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-06 14:55:58 CST → 2026-10-07 14:37:42 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Speech LLM 1, ASR 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Audiovisual joint learning for end-to-end hearing aids

👤 **作者**: You-Jin Li, Yu Tsao, Borching Su, Kuan-Chung Ting, Fan-Gang Zeng
🔗 **来源**: [https://arxiv.org/abs/2610.08579v1](https://arxiv.org/abs/2610.08579v1)

**摘要**
> Speech understanding in noise remains challenging for hearing-aid users, particularly in the presence of competing speakers. Conventional hearing aids typically perform speech enhancement (SE) and hearing-loss compensation in separate stages, which may cause enhancement errors and signal distortions to carry over to the amplification stage. Moreover, audio-only SE often provides limited benefits under competing-speech conditions because the target and interfering speech share similar acoustic characteristics, making them difficult to separate. To address these limitations, we propose AV-NeuroAMP, an end-to-end audiovisual framework that integrates noisy speech, target-talker video, and the listener's audiogram to jointly perform SE, personalized amplification, and dynamic-range compression. We further introduce audiogram-conditioned feature-wise linear modulation (AC-FiLM) to effectively incorporate listener-specific hearing profiles. Objective evaluations showed that AV-NeuroAMP outperformed conventional amplification, the audio-only NeuroAMP model, and two-stage systems on an in-domain English test set, and that these improvements were retained on an unseen Mandarin test set. Listening tests involving normal-hearing participants under simulated hearing loss and listeners with hearing loss further demonstrated improvements in speech quality and intelligibility, with the greatest benefits observed under competing-speech conditions. These findings support end-to-end audiovisual personalized amplification as a promising approach for improving hearing-aid performance in challenging acoustic environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Audiovisual joint learning for end-to-end hearing aids》所界定。 从摘要看，作者主要围绕 speech understanding、speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Objective evaluations showed that AV-NeuroAMP outperformed conventional amplification, the audio-only NeuroAMP model, and two-stage systems on an in-domain English test set, and that these improvements were retained on an unseen Mandarin test set. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech understanding, speech enhancement。 |

---
## 🏷️ ASR

### 1. InterCorrect: Intersection-Aware Correction of Demographic Model Merging for Fair ASR

👤 **作者**: Ashley E. Bravo-Bravo, Yuchen Zhang, Haralambos Mouratidis, Ravi Shekhar, Monorama Swain
🔗 **来源**: [https://arxiv.org/abs/2610.08604v1](https://arxiv.org/abs/2610.08604v1)

**摘要**
> Automatic Speech Recognition (ASR) systems often show uneven performance across demographic groups, and errors can be especially difficult to address for speakers belonging to multiple demographic groups. This work studies demographic-aware model merging for fair Speech-LLM-based ASR. Starting from a SLAM-ASR-based model, we fine-tune only the connector on demographic-specific subsets and merge the resulting subgroup-adapted connectors into a global model. We then identify critical cross-axis demographic pairs using subgroup WER and task-vector conflict, and apply intersection-specific correction vectors to the global merged model. Experiments on Fair-Speech show that global demographic merging improves overall WER over the base model, while intersection correction provides additional gains for several merging strategies. In particular, TIES with WER-based correction achieves the best overall WER, reducing it from 7.38\% to 5.13\%. Subgroup and disparity analyses further show that the proposed approach improves performance across demographic axes, while highlighting that lower average WER does not always imply reduced subgroup disparity.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《InterCorrect: Intersection-Aware Correction of Demographic Model Merging for Fair ASR》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Automatic Speech Recognition (ASR) systems often show uneven performance across demographic groups, and errors can be especially difficult to address for speakers belonging to multiple demographic groups. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

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

### 1. Beyond Perturbation Magnitude: Direction-Dependent Responses in Multimodal Geometric Representations

👤 **作者**: Yongsheng Luo, Wengan He, Yu Li, Rouying Wu, Wei Lv
🔗 **来源**: [https://arxiv.org/abs/2610.08533v1](https://arxiv.org/abs/2610.08533v1)

**摘要**
> Geometric alignment scores based on Gram determinants provide a compact way to model higher-order consistency among modalities, yet how such scores respond to modality degradation is poorly understood. This paper asks whether the response of a multimodal geometric score is determined primarily by the magnitude of the perturbation-induced displacement. Using frozen cohorts from MSR-VTT (N=878) and DiDeMo (N=980), we apply controlled video blur and audio noise and analyze the response in the relational geometry on which the score is defined. Displacement magnitude explains at most 15% of the out-of-sample variance in the absolute response, and magnitude-matched pairs respond systematically differently, so scalar magnitude does not organize the response. The closed-form first-order expansion of the Gramian volume yields the Directional Geometric Response (DGR): the projection of the displacement onto the local volume gradient, which jointly captures the clean operating point, displacement magnitude, and displacement direction. The absolute first-order DGR term explains the observed response with out-of-sample R^2 of 0.838-0.969, matched-magnitude ranking accuracies of 0.864-0.963, and response-sign accuracies of 0.909-0.989, whereas the tested direction-free alternatives remain weak or unstable under the corresponding evaluation protocols. A pre-specified gain-normalization candidate, V/(g_V+eps), fails its predictability and clean-order gates. DGR uses the observed degraded-state displacement and is therefore an explanatory quantity, not a deployment-time predictor: geometric response depends on where the representation operates, how far degradation moves the relational geometry, and in which direction it moves.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond Perturbation Magnitude: Direction-Dependent Responses in Multimodal Geometric Representations》所界定。 从摘要看，作者主要围绕 beyond、perturbation、magnitude 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper asks whether the response of a multimodal geometric score is determined primarily by the magnitude of the perturbation-induced displacement. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：beyond, perturbation, magnitude。 |

---
### 2. WorldSonus: Bringing Sound to Worlds

👤 **作者**: Pengjun Fang, Jingyi Fa, Kam Man Wu, Jiaming Wang, Haoyuan Huang, Yaguang Wu, Xiangjun Huang, Ziyang Ma, Weijia Chen, Hongyu Liu, Zeyue Tian, Qifeng Chen
🔗 **来源**: [https://arxiv.org/abs/2610.08760v1](https://arxiv.org/abs/2610.08760v1)

**摘要**
> Recent advances in world models have enabled increasingly realistic visual synthesis. However, these generated environments remain largely silent. Bringing sound to world models poses three core challenges: real-time generation to keep pace with interactive video streams, interactive control to respond to mid-stream sound instructions, and spatially aligned stereo to reflect scene geometry and camera motion. To address these demands, we introduce WorldSonus, an interactive video-to-audio framework designed for real-time spatial sound synthesis in world models. For real-time generation, WorldSonus employs a streaming causal autoregressive diffusion architecture that synthesizes audio chunks at a low real-time factor (RTF) of 0.41. For interactive control, we incorporate an audio-centric captioning pipeline with chunk-indexed prompt scheduling, enabling dynamic manipulation of sound events during generation. For spatial alignment, we leverage high-quality stereo supervision curated from diverse stereo and ambisonic data. Extensive experiments demonstrate that while tailored for world models, WorldSonus generalizes effectively to open-domain video-to-audio benchmarks, matching or outperforming state-of-the-art bidirectional models in both acoustic quality and spatial alignment. Project page: https://noizai.github.io/WorldSonus/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《WorldSonus: Bringing Sound to Worlds》所界定。 从摘要看，作者主要围绕 sound synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experiments demonstrate that while tailored for world models, WorldSonus generalizes effectively to open-domain video-to-audio benchmarks, matching or outperforming state-of-the-art bidirectional models in both acoustic quality and spatial alignment. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sound synthesis。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
