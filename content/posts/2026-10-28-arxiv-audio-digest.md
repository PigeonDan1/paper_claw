<div align="center">

# 📰 Paper Claw

**2026-10-28**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-27 13:44:29 CST → 2026-10-28 14:23:18 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Speech LLM 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Beyond Answer Changes: Matched Same-Class Controls for Local Audio Evidence

👤 **作者**: Yunuo Wang, Maoyuan Chen, Yuanjin Huang, Xing Liu
🔗 **来源**: [https://arxiv.org/abs/2610.37605v1](https://arxiv.org/abs/2610.37605v1)

**摘要**
> For audio-language models, an answer change after a local sound-event edit can reflect a response to the event's class, sensitivity to waveform rewriting, or both. We compare matched same-class and different-class replacements of a queried event. Both use the same interval, level estimate, donor fitting, and crossfade, while the same-class replacement preserves the correct answer. Across 600 synthetic soundscapes and three models from two architecture families, different-class replacements produce 49.7 to 60.9 percentage points more answer changes than same-class replacements. Same-class accuracy remains within 5.2 percentage points of original accuracy. Among trials with correct original and same-class answers, soundscape-weighted selective accuracy for the inserted class is 73.7 to 81.9%, averaging eligible trials within each soundscape and then weighting eligible soundscapes equally. This protocol tests how model answers respond to local changes in event class.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Beyond Answer Changes: Matched Same-Class Controls for Local Audio Evidence》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We compare matched same-class and different-class replacements of a queried event. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model。 |

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

### 1. Understanding Everyday Communication Patterns, Stress, and Productivity in Hybrid Work through Egocentric Wearable Audio Sensing

👤 **作者**: Tiantian Feng, Aditya Kommineni, Emily Zhou, Burcin Becerik-Gerber, Gale Lucas, Shawn C. Roll, Shrikanth Narayanan
🔗 **来源**: [https://arxiv.org/abs/2610.37270v1](https://arxiv.org/abs/2610.37270v1)

**摘要**
> The hybrid work trend in the post-COVID period has transformed how people communicate while at work. However, there is a lack of quantitative understanding of how home and office environments shape communicative behavior and affective well-being. To study this, as a part of a larger study of the role of work environment on stress, we designed an egocentric wearable audio sensing system that captured interpersonal communication across both working locations. The system extracts real-time acoustic features on a wearable audio sensor and performs offline foreground speaker diarization to derive speaking load and activeness features. To improve diarization performance under low-dimensional feature constraints, we apply a teacher-student knowledge distillation framework that transfers knowledge from large-scale speech foundation models into a compact ResNet-based model, achieving consistent improvements in diarization performance over the baseline across three public egocentric speech datasets. In a four-month longitudinal deployment with 16 participants, our system revealed location-dependent differences in work communication patterns. Moreover, the mixed linear model analyses showed that office-based speaking load was significantly associated with higher self-reported stress and lower self-reported productivity, while speaking activeness during home-based work amplified both productivity and affective load in this cohort.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Understanding Everyday Communication Patterns, Stress, and Productivity in Hybrid Work through Egocentric Wearable Audio Sensing》所界定。 从摘要看，作者主要围绕 understanding、everyday、communication 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To improve diarization performance under low-dimensional feature constraints, we apply a teacher-student knowledge distillation framework that transfers knowledge from large-scale speech foundation models into a compact ResNet-based model, achieving consistent improvements in diarization performance over the baseline across three public egocentric speech datasets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：understanding, everyday, communication。 |

---
### 2. EmbeddingGemma 2: Unified and Efficient Multimodal Representations

👤 **作者**: Henrique Schechter Vera, Sahil Dua, Jovan Andonov, Sara Smoot, Sebastian Russo, Ivan Llanos, Max Matveev, Jae Hyeon Yoo, Kat Black, Shih-Cheng Huang, Josiah Aklilu, Maarten Grootendorst, Omar Sanseviero, Chandramouli Amarnath, Ian Ballantyne, Zhe Li, Daniel Salz, Ibrahim Alabdulmohsin, Ilya Philippov, Kristen Quan, Glenn Cameron, Edouard Yvinec, Luciano Martins, Doug Reid, Sindhu Raghuram Panyam, Weiyi Wang, Hengxuan Ying, Madhuri Shanbhogue, Tanmaya Dabral, Shanfeng Zhang, Juyeong Ji, Renjie Wu, Joe Zou, Xu Chen, Yunan Zhang, Yu-Hui Chen, Matthew Soulanille, Vinod Mamillapalli, Yi-Chun Kuo, Wai Hon Law, Matt Kreileder, Alice Zheng, Suril Shah, Mogan Shieh, Pooja Consul, Alberto Montes, Andreas Hess, Andres Sevilla, Babak Samari, Brendan McCloskey, Brian Potetz, Daniel Cer, Georgios Kathareios, Gustavo Hernández Ábrego, Hesen Zhang, Ji Ma, Jiaxing Wu, Keegan Mosley, Paul Suganthan, Rui Meng, Shen Gao, Shengcao Cao, Yi-Ting Chen, Yichang Chen, Zhongli Ding, Kendra Byrne, Cormac Brick, Olivier Lacombe, Qin Yin, Tris Warkentin, Armand Joulin, Tom Duerig, Mojtaba Seyedhosseini
🔗 **来源**: [https://arxiv.org/abs/2610.37364v1](https://arxiv.org/abs/2610.37364v1)

**摘要**
> We present EmbeddingGemma 2, an open multimodal embedding model which natively represents text, images, audio, video, and combinations thereof in a unified space. Our approach introduces improvements such as simplified per-layer embeddings and a multi-stage curriculum with modality and objective progression which ensure strong quality across unimodal, cross-modal, and mixed-modal evaluations. Notably, in comprehensive embedding benchmarks across all modalities, EmbeddingGemma 2 establishes a new Pareto frontier, outperforming both specialist models and models two to twelve times larger. Furthermore, our design offers flexibility for resource-constrained environments, supporting selective modality encoder loading, adjustable vision token budgets, truncatable embedding dimensions, and quantized weights. We present ablations analyzing key decisions and release EmbeddingGemma 2 to promote further research.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《EmbeddingGemma 2: Unified and Efficient Multimodal Representations》所界定。 从摘要看，作者主要围绕 embeddinggemma、unified、efficient 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our approach introduces improvements such as simplified per-layer embeddings and a multi-stage curriculum with modality and objective progression which ensure strong quality across unimodal, cross-modal, and mixed-modal evaluations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：embeddinggemma, unified, efficient。 |

---
### 3. Partially Edited Audio: Generation, Defense, and Open Problems

👤 **作者**: Lin Zhang, You Zhang, Nicholas Evans, Xin Wang, David Harwath, Abhinav Dhall, Bowen Shi, Chengzhe Sun, Siwei Lyu, Sanjeev Khudanpur
🔗 **来源**: [https://arxiv.org/abs/2610.37640v1](https://arxiv.org/abs/2610.37640v1)

**摘要**
> Recent advances in generative audio models facilitate increasingly flexible and selective editing of linguistic content and paralinguistic, extralinguistic, and other attributes. This paradigm, named partially edited audio, differs from full audio generation as only portions of the real recording are edited. This technique can serve both beneficial and harmful applications. We therefore present a concise survey from both generation and defense perspectives, focusing on audio, as a contribution to the ICASSP 2027 special session entitled "Partially Edited Media: Perspectives from Synthesis and Defense." We first define partially edited audio and argue that what counts as ``fake'' or harmful is an application-dependent judgment, not a fixed property of the edit. We then survey audio editing by editing target, approaches, and evaluation, and then defense methods by detection, localization, diarization, and interpretability, summarizing representative benchmarks and toolkits. Finally, we discuss future directions and open problems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Partially Edited Audio: Generation, Defense, and Open Problems》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paradigm, named partially edited audio, differs from full audio generation as only portions of the real recording are edited. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
