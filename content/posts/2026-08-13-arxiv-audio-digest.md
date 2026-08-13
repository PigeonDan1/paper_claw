<div align="center">

# 📰 Paper Claw

**2026-08-13**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-12 11:14:50 CST → 2026-08-13 11:19:21 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 2 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 0 篇

> 💡 今日共收录 3 篇新论文，主要分布在 ASR 1, Enhancement 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. The SLT 2026 SmartGlasses Challenge: Benchmarking Egocentric Multi-Talker Speech Recognition and Understanding with Audio-Language Models

👤 **作者**: Dehui Gao, Zhixian Zhao, Zhennan Lin, Yujie Liao, Yuhang Dai, Yike Zhu, Longshuai Xiao, Hui Bu, Xin Xu, Xie Chen, Shuai Wang, Liumeng Xue, Zhonghua Fu, Jun Du, Eng-Siong Chng, Jun Zhou, Lei Xie
🔗 **来源**: [https://arxiv.org/abs/2608.12034v1](https://arxiv.org/abs/2608.12034v1)

**摘要**
> Recent advances in large language models (LLMs) and multimodal LLMs (MLLMs) have created new opportunities for wearable speech interfaces, with smart glasses providing an egocentric platform for continuous audio sensing and assistance. However, speech recognition and understanding in this setting remain challenging because of dynamic acoustic conditions, speaker overlap, and the spatial ambiguity introduced by wearer-centered recording geometry. To support systematic evaluation in this setting, we introduce the IEEE SLT 2026 SmartGlasses Challenge for egocentric multi-speaker speech processing. The challenge consists of two tracks, Dyadic Dialogue Understanding and Multi-party Meeting Understanding, and jointly evaluates Time-Stamped Speaker-Attributed Automatic Speech Recognition (TSA-ASR) and Spoken Language Understanding (SLU). It is built on a 106-hour four-channel egocentric speech dataset containing 714 sessions collected in real-world scenarios. This paper describes challenge tasks, dataset construction, submissions, and summarizes the main findings from the shared evaluation. The results show that heavy speaker overlap remains a major factor affecting TSA-ASR performance, while paralinguistic acoustic understanding continues to be difficult for current audio-language models in complex SLU settings. Further details can be found on the official challenge website.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《The SLT 2026 SmartGlasses Challenge: Benchmarking Egocentric Multi-Talker Speech Recognition and Understanding with Audio-Language Models》所界定。 从摘要看，作者主要围绕 audio-language model、automatic speech recognition、spoken language understanding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that heavy speaker overlap remains a major factor affecting TSA-ASR performance, while paralinguistic acoustic understanding continues to be difficult for current audio-language models in complex SLU settings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model, automatic speech recognition, spoken language understanding。 |

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. Rethinking Language Model-Based Generative Speech Enhancement in the Latent Space of a Neural Audio Codec

👤 **作者**: Yihui Fu, Zhengyang Li, Tim Fingscheidt
🔗 **来源**: [https://arxiv.org/abs/2608.12082v1](https://arxiv.org/abs/2608.12082v1)

**摘要**
> Language model (LM)-based speech enhancement (SE) has recently emerged rapidly using latent space features of neural audio codecs (NACs). In this paper, first, we present a unified framework covering six popular LM-based generative SE modeling paradigms based on discrete/continuous latent NAC features: discrete or continuous autoregressive (D/CAR) SE, discrete or continuous non-autoregressive (D/CNAR) SE, discrete diffusion (DDiff) SE, and continuous flow matching (CFM) SE. Second, we are the first to compare their performance in a unified experimental setup and synopsis with diverse intrusive and non-intrusive metrics, enabling a fair and comprehensive evaluation. Third, we propose a fine-tuning strategy with auxiliary losses on reconstructed speech to improve both intrusive and non-intrusive metrics. Trained and evaluated on URGENT 2025 Speech Enhancement Challenge data splits, all continuous-domain paradigms excel their discrete-domain counterparts. The overall best approach turns out to be CNAR. We further show that our proposed auxiliary loss fine-tuning strategy helps to improve DNSMOS, NISQA, PESQ, and POLQA consistently in all six paradigms.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Rethinking Language Model-Based Generative Speech Enhancement in the Latent Space of a Neural Audio Codec》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Third, we propose a fine-tuning strategy with auxiliary losses on reconstructed speech to improve both intrusive and non-intrusive metrics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
### 2. RT-SEMamba: Real-Time Speech Enhancement Mamba via Progressive Knowledge Distillation

👤 **作者**: Rong Chao, Sung-Feng Huang, Moreno La Quatra, Sabato Marco Siniscalchi, Wen-Huang Cheng, Szu-Wei Fu, Yu Tsao
🔗 **来源**: [https://arxiv.org/abs/2608.12099v1](https://arxiv.org/abs/2608.12099v1)

**摘要**
> We present RT-SEMamba, a fully causal speech enhancement (SE) model built upon causal time-frequency Mamba blocks. Unlike Transformer-based architectures that rely on a growing key-value cache, Mamba propagates a fixed-size recurrent state per layer, enabling memory- and bandwidth-efficient long-form inference. We further introduce a progressive knowledge distillation (KD) strategy that compresses an 8-layer teacher into a shallow 1-layer student by jointly distilling complex spectral outputs and intermediate representations. On Voicebank-DEMAND, the 8-layer RT-SEMamba achieves 3.32 PESQ with a 25 ms algorithmic latency constraint, and the distilled 1-layer student improves over a naive 1-layer baseline from 3.06 to 3.18 PESQ while preserving the same steady-state RTF, delivering a 2.75x speedup over the teacher. These results demonstrate that state-space models with progressive KD provide a competitive quality-latency trade-off for real-time SE.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《RT-SEMamba: Real-Time Speech Enhancement Mamba via Progressive Knowledge Distillation》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On Voicebank-DEMAND, the 8-layer RT-SEMamba achieves 3.32 PESQ with a 25 ms algorithmic latency constraint, and the distilled 1-layer student improves over a naive 1-layer baseline from 3.06 to 3.18 PESQ while preserving the same steady-state RTF, delivering a 2.75x speedup over the teacher. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

> 📭 今日该分类暂无新论文。

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
