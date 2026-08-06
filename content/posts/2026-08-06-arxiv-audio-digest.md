<div align="center">

# 📰 Paper Claw

**2026-08-06**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-05 11:50:39 CST → 2026-08-06 11:55:27 CST |
| 📄 论文总数 | **2** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 2 篇新论文，主要分布在 Audio 2。
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

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Visual Representation Matters: Exploiting Temporal Differences in Video-to-Audio Generation

👤 **作者**: Zehua Chen, Junyou Wang, Yuxuan Jiang, Zhenying Fang, Yusheng Dai, Jianfei Chen, Ziwei Liu, Jun Zhu
🔗 **来源**: [https://arxiv.org/abs/2608.04902v1](https://arxiv.org/abs/2608.04902v1)

**摘要**
> Video-to-audio (V2A) generation extends image-to-audio generation (I2A) by introducing consecutive frames that provide essential temporal cues for audio synthesis. However, existing conditional diffusion-based V2A methods typically enhance visual conditioning with additional audio-visual supervision, acoustic structure prediction, or reasoning from large multimodal models, requiring extra networks or strong inductive biases. Inspired by recent advances in visual representation learning, we introduce TD-V2A, which leverages temporal differences (TD) as the key representation that distinguishes V2A from I2A, enriching visual conditioning with minimal architectural modification. We first investigate TD at both the frame and feature levels to identify the most effective representation level at which TD complements visual representations. Based on these findings, we develop a hierarchically continual learning strategy and an annealed temporal differences guidance method to progressively learn and exploit TD information during diffusion training and sampling process, respectively. Extensive experiments on benchmark datasets demonstrate that effectively exploiting TD through our proposed framework significantly improves end-to-end V2A generation quality, even outperforming dedicated V2A representations such as contrastive audio-visual pretraining.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Visual Representation Matters: Exploiting Temporal Differences in Video-to-Audio Generation》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experiments on benchmark datasets demonstrate that effectively exploiting TD through our proposed framework significantly improves end-to-end V2A generation quality, even outperforming dedicated V2A representations such as contrastive audio-visual pretraining. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---
### 2. Teaching Nemotron Greek: Mining a Corpus, Adapting Retrieval, and Grounding Generation for Modern Greek across Specialist Domains

👤 **作者**: Ayoub Kirouane, Christos Petrocheilos
🔗 **来源**: [https://arxiv.org/abs/2608.05138v1](https://arxiv.org/abs/2608.05138v1)

**摘要**
> Modern Greek is absent from NVIDIA's Nemotron retrieval models and from major multilingual retrieval benchmarks, despite being important for retrieval-augmented generation (RAG) in legal, energy, financial, and medical applications. We present an end-to-end adaptation of the Nemotron retrieval stack for Modern Greek, including corpus mining, synthetic supervision, retrieval model training, reranker adaptation, reader fine-tuning, and a new benchmark called HERA. Our study shows that a parameter-free BM25 baseline outperforms several off-the-shelf multilingual dense retrieval models on specialist Greek corpora. After fine-tuning on 65,773 Greek retrieval pairs, a Nemotron 1B embedder improves nDCG@10 from 0.362 to 0.835 and substantially outperforms its unadapted counterpart. The learned language competence transfers to general-domain Greek, although the advantage over BM25 remains domain-dependent. We further adapt a cross-encoder reranker and demonstrate consistent improvements across specialist domains. Finally, we LoRA-tune a Nemotron 30B-A3B mixture-of-experts reader for grounded generation, increasing judged answer correctness from 29.4% to 66.9% while significantly improving faithfulness and citation quality. We also introduce HERA, the first large-scale Greek benchmark for retrieval-augmented generation, and release our adapted models and benchmark to support future research on Greek-language RAG systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Teaching Nemotron Greek: Mining a Corpus, Adapting Retrieval, and Grounding Generation for Modern Greek across Specialist Domains》所界定。 从摘要看，作者主要围绕 teaching、nemotron、greek 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our study shows that a parameter-free BM25 baseline outperforms several off-the-shelf multilingual dense retrieval models on specialist Greek corpora. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：teaching, nemotron, greek。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
