<div align="center">

# 📰 Paper Claw

**2026-10-14**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-13 15:09:53 CST → 2026-10-14 13:32:15 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 2 篇

> 💡 今日共收录 3 篇新论文，主要分布在 Paralinguistics 1, Audio 2。
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

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

### 1. GeoMER: A Joint Euclidean-Hyperbolic Geometry Framework for Multimodal Emotion Recognition

👤 **作者**: Ting Zhu, Huizhi Liang, Boguslaw Obara, Shufei Duan, Varun Ojha
🔗 **来源**: [https://arxiv.org/abs/2610.18587v1](https://arxiv.org/abs/2610.18587v1)

**摘要**
> Multimodal Emotion Recognition (MER) aims to understand human emotions by integrating information from multiple modalities such as speech and text. Psychological studies suggest that emotions exhibit latent hierarchical structured relationships in their semantic representations. However, most MER approaches rely on Euclidean representations, which capture fine-grained cross-modal interactions but do not explicitly provide a geometric prior for organizing hierarchical emotional structures. To mitigate this gap, we propose GeoMER, a joint Euclidean-Hyperbolic modeling framework that introduces hyperbolic emotion-core routing to capture higher-level, abstract emotional representations for MER. The proposed framework jointly models token-level cross-modal semantic interactions and latent emotion representations in two complementary geometric spaces. Specifically, GeoMER consists of a Euclidean Multimodal Fusion Module (EuclFusion) for multimodal representation fusion and a Hyperbolic Geometric Core Routing (HypGeoRoute) module that performs geometry-aware core assignment and aggregation in a hyperbolic manifold to capture more abstract feature representations. The HypGeoRoute module complements the Euclidean token-level modeling. We experiment on the IEMOCAP multimodal MER benchmark and demonstrate that the proposed method achieves the best performance, with 83.54% weighted accuracy and 83.35% unweighted accuracy, outperforming Euclidean baselines, including MemoCMT.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《GeoMER: A Joint Euclidean-Hyperbolic Geometry Framework for Multimodal Emotion Recognition》所界定。 从摘要看，作者主要围绕 emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We experiment on the IEMOCAP multimodal MER benchmark and demonstrate that the proposed method achieves the best performance, with 83.54% weighted accuracy and 83.35% unweighted accuracy, outperforming Euclidean baselines, including MemoCMT. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：emotion recognition。 |

---
## 🏷️ Audio

### 1. PhysicsSliders: Learning Physical Controls for Audio Foley Generation

👤 **作者**: Peiwei Chang, Yongqiang Chen, Yuelan Cheng, Liting Gao, Yishun Lu, Li Zhang, Mark D. Plumbley, Philip J. B. Jackson, Wenwu Wang
🔗 **来源**: [https://arxiv.org/abs/2610.18597v1](https://arxiv.org/abs/2610.18597v1)

**摘要**
> Physical properties provide intuitive controls for sounds made by interacting objects. The challenge is to make a generative model respond predictably to these controls, both individually and in combination. We present \method\ (PXS), trained on simulated contact sounds with 15 material, geometry and contact parameters. Two separately trained variants accept direct parameter inputs or numerical captions. PXS controls hardness, size, speed and damping, supports room descriptions and produces spectrally distinct outputs at fixed targets. When controlling damping and size together, specifying thickness improves frequency accuracy and joint target delivery. Measurements from real recordings define effective-damping targets, which simulator inversion maps to generation inputs without real-audio fine-tuning. Across 18 impact classes from five real-audio datasets, PXS-Physical follows these targets with mean grouped Spearman correlation $ρ=0.976$ and class-median error 0.094 dex (a factor of 1.24).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《PhysicsSliders: Learning Physical Controls for Audio Foley Generation》所界定。 从摘要看，作者主要围绕 physicssliders、learning、physical 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：When controlling damping and size together, specifying thickness improves frequency accuracy and joint target delivery. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：physicssliders, learning, physical。 |

---
### 2. AMemOps: Evaluating Memory Updates in Long Audio Streams

👤 **作者**: Peiwei Chang, Li Zhang, Mark D. Plumbley, Philip J. B. Jackson, Wenwu Wang
🔗 **来源**: [https://arxiv.org/abs/2610.18652v1](https://arxiv.org/abs/2610.18652v1)

**摘要**
> Audio memory must recognise recurring sources across acoustic changes while keeping their attributes up to date. Overall accuracy does not reveal how these demands interact. We introduce Audio Memory Operations (AMemOps), a benchmark for latest-attribute retrieval, preservation of unchanged attributes and absent-source rejection in long audio streams. Paired controls vary recordings, training identities and earlier events to examine their effects on updating. Training on other recordings of the test instruments increases a reference delta-rule memory's update advantage over matched attention by 13.4 percentage points. At retrieval delays of 120\,s, matched histories separate benefits of consistent repetition from costs of conflicting earlier values, while additive-memory controls identify benefits of erasure.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AMemOps: Evaluating Memory Updates in Long Audio Streams》所界定。 从摘要看，作者主要围绕 amemops、evaluating、memory 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Overall accuracy does not reveal how these demands interact. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：amemops, evaluating, memory。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
