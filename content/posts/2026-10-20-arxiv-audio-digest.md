<div align="center">

# 📰 Paper Claw

**2026-10-20**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-19 13:24:50 CST → 2026-10-20 13:27:00 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 3 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Paralinguistics 1, Audio 3。
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

### 1. Label Authority in Speech Emotion Recognition: Intended and Perceived Ground Truth in Emozionalmente

👤 **作者**: Marco Giordano, Stefano Giacomelli, Claudia Rinaldi, Fabio Graziosi
🔗 **来源**: [https://arxiv.org/abs/2610.26446v1](https://arxiv.org/abs/2610.26446v1)

**摘要**
> Ground truth in Speech Emotion Recognition (SER) is often presented as a single categorical fact, yet an acted emotion and the emotion heard by listeners describe different aspects of the same recording. We examine this distinction in Emozionalmente, an acted Italian corpus that provides both an elicited production label and five listener judgements for every clip. Using frozen XLS-R, HuBERT, and WavLM representations with matched probes, we compare three label authorities: the expressed condition, the listeners' hard plurality, and their complete vote distribution. The results tell a consistent story. Recovering the expressed condition is easier than predicting a tie-broken listener plurality, but that gap compares two different questions rather than revealing a general loss of SER ability. As listener agreement weakens, the plurality becomes an increasingly brittle hard target. Training on the full vote distribution does not substantially change which class wins the model's hard decision, but it produces probability assignments that more closely follow the alternatives selected by listeners, especially for ambiguous clips. No authority therefore replaces the others. Expressed labels describe how speech was produced, pluralities provide an operational single-class decision, and vote distributions preserve perceptual uncertainty. For human-facing Internet of Sounds applications, evaluations should state which authority is being predicted, retain its aggregation rule and agreement information, and use distributional scores when disagreement is part of the target.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Label Authority in Speech Emotion Recognition: Intended and Perceived Ground Truth in Emozionalmente》所界定。 从摘要看，作者主要围绕 hubert、emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We examine this distinction in Emozionalmente, an acted Italian corpus that provides both an elicited production label and five listener judgements for every clip. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：hubert, emotion recognition。 |

---
## 🏷️ Audio

### 1. Expert L2 English Speech Evaluation on a Gaming PC: Accuracy, Fluency, and Prosody with XLS-R, XEUS, and PhoneticXeus

👤 **作者**: Richard Rose
🔗 **来源**: [https://arxiv.org/abs/2610.26406v1](https://arxiv.org/abs/2610.26406v1)

**摘要**
> oollim is a locally executable system for evaluating L2 English pronunciation accuracy, fluency, and prosody on a consumer computer. The system combines pretrained XLS-R, XEUS, and PhoneticXeus representations with reference-text features and ridge regressions trained on SpeechOcean762, the Korean Learners' L2 Speech Corpus (English), J-AESOP, and their combinations. On 305 independently held-out recordings assessed by three expert raters, several ridge configurations substantially outperform archived Azure API scores obtained in January 2026 in both Spearman correlation and quadratic weighted kappa across all three constructs. These results support expert speech evaluation on consumer hardware using pretrained representations and construct-specific regressions, without neural-model fine-tuning or calibration on the private evaluation data.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Expert L2 English Speech Evaluation on a Gaming PC: Accuracy, Fluency, and Prosody with XLS-R, XEUS, and PhoneticXeus》所界定。 从摘要看，作者主要围绕 expert、english、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On 305 independently held-out recordings assessed by three expert raters, several ridge configurations substantially outperform archived Azure API scores obtained in January 2026 in both Spearman correlation and quadratic weighted kappa across all three constructs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：expert, english, speech。 |

---
### 2. TeleASR-Amharic: A Benchmark for Robust Amharic ASR in Realistic Telecommunication Conditions

👤 **作者**: Dagnachew Mekonnen Marilign, Enrique Molero, Abrham Haile, Louis Powell, Israel Abebe Azime
🔗 **来源**: [https://arxiv.org/abs/2610.26448v1](https://arxiv.org/abs/2610.26448v1)

**摘要**
> The real-world usability of ASR models remains challenging, particularly for low-resource languages, where existing speech resources are often collected in clean studio environments. In this work, we introduce TeleASR-Amharic, a benchmark for evaluating Amharic ASR under various acoustic and telecommunication conditions. We analyze the major degradations observed in real telecommunications recordings and develop a benchmark that covers multiple channel conditions, environmental disturbances, and telecom-domain variations. Our results show that telecommunication degradation can substantially reduce recognition performance, making even high-performing ASR models impractical under severe conditions. For example, the WER of the best-performing model increases from 0.23 to 0.79 under severe telecommunication degradation, corresponding to a relative increase of 243% in recognition errors. We further investigate the effects of different noise and channel distortions and show that scaling training data and applying carefully designed telecommunication-aware augmentation substantially improve robustness. In particular, our best training configuration achieves a 23.6% relative WER reduction under extreme noise conditions. Together with the release of our telecommunications-domain data, these findings provide a reproducible benchmark for measuring progress in Amharic ASR while highlighting open challenges in developing robust speech technologies for real-world deployment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《TeleASR-Amharic: A Benchmark for Robust Amharic ASR in Realistic Telecommunication Conditions》所界定。 从摘要看，作者主要围绕 teleasr-amharic、benchmark、robust 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that telecommunication degradation can substantially reduce recognition performance, making even high-performing ASR models impractical under severe conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：teleasr-amharic, benchmark, robust。 |

---
### 3. MuLaCover: Flexible Cover Song Generation via Symbolic Tonal Control

👤 **作者**: Lynn Yi, Zihan Xiong, Junjie Cao, Xiaolong Weng, Yingzhe Ma, Gus Xia, Jinliang Liu, Yuxin Xie, Xianwei Zhuang, Yuguo Yin, Qiao Jin, Gongxi Zhu, Jiayu Wang, Junjie Liang, Qin Yue, Ziyu Wang, Dading Chong, Meng Cao, Jiahuan Zhou, Dongchao Yang
🔗 **来源**: [https://arxiv.org/abs/2610.26684v1](https://arxiv.org/abs/2610.26684v1)

**摘要**
> A cover song re-renders an existing piece, most commonly by preserving its tonal content -- melody and chord progression -- while reshaping other musical attributes. This suggests a natural formulation for generative cover synthesis with pretrained music language models: explicitly control tonal content, while specifying lyrics and style through text. Existing approaches condition on frame-level features, tightly coupling generation to the reference's timing and structure, and limiting flexibility such as tempo variation, structural rearrangement, or partial conditioning. To this end, we present MuLaCover, a cover generation model that conditions a pretrained text-to-song foundation model on an editable symbolic lead sheet. Our design enables alignment-free control: generated outputs preserve the tonal signature of the source without frame-level alignment, allowing flexible timing, structure, and segment-level generation. We further introduce a training curriculum with partially mismatched audio-symbolic pairs, improving diversity and robustness. We evaluate MuLaCover with objective metrics, standard subjective ratings, and in-depth expert interviews that provide fine-grained diagnostic insights. Experiments show that MuLaCover achieves state-of-the-art performance among open-source systems and is competitive with leading commercial models such as Suno-v5.5. Audio samples and code are available at our project page: https://mulalabs.ai/mulacover/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MuLaCover: Flexible Cover Song Generation via Symbolic Tonal Control》所界定。 从摘要看，作者主要围绕 mulacover、flexible、cover 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We further introduce a training curriculum with partially mismatched audio-symbolic pairs, improving diversity and robustness. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：mulacover, flexible, cover。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
