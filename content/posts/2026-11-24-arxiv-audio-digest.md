<div align="center">

# 📰 Paper Claw

**2026-11-24**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-11-23 16:20:45 CST → 2026-11-24 18:29:45 CST |
| 📄 论文总数 | **2** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 2 篇新论文，主要分布在 ASR 1, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. CAST: A Deployed Speech-to-Text Cascade for Closed Captioning of Entertainment Television

👤 **作者**: Aditya Mishra, Thanish Bolla, Bidisha Sharma, Balaji Pitchaikannu, Surbhi Sinha, Anup Kotalwar
🔗 **来源**: [https://arxiv.org/abs/2611.31055v1](https://arxiv.org/abs/2611.31055v1)

**摘要**
> Despite rapid progress in automatic speech recognition (ASR), caption generation for long-form entertainment video remains challenging for content dense in music and effects, rich in accents, crosstalk, and noise. The transcript quality depends on segmentation and surrounding modules as much as the acoustic model. A single pass voice activity detection (VAD) can miss faint, low-energy voice while forwarding near-silent segments that induce hallucination and repetition in an autoregressive decoder. These competing errors motivate a hierarchical VAD that revisits rejected segments under semantic and acoustic retention checks. We present Captioning ASR Stack for Television (CAST), an integrated speech-to-text pipeline for closed captioning (CC) combining frozen Whisper large-v3 with segmentation, language identification, lyrics routing, and targeted hallucination detection and repair on a single NVIDIA L4 GPU. On 100 in-house assets spanning 60.46 hours, CAST reduces normalized WER from 6.99% to 5.36% and subtitle edit rate from 254.2 to 221.9 min/hour against the WhisperX pipeline, and improves deletion rate by 11% on public datasets. We also present the behavior of each stage in the pipeline. CAST entered the production speech-to-text (STT) stage of our CC pipeline in late August 2026; we report the evaluation evidence and path to full-scale operation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《CAST: A Deployed Speech-to-Text Cascade for Closed Captioning of Entertainment Television》所界定。 从摘要看，作者主要围绕 automatic speech recognition、speech-to-text、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On 100 in-house assets spanning 60.46 hours, CAST reduces normalized WER from 6.99% to 5.36% and subtitle edit rate from 254.2 to 221.9 min/hour against the WhisperX pipeline, and improves deletion rate by 11% on public datasets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, speech-to-text, whisper。 |

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

### 1. What Do Sound Event Embeddings Reveal? Auditing Speaker Leakage in Audio Representations

👤 **作者**: Bhawana Chhaglani
🔗 **来源**: [https://arxiv.org/abs/2611.31043v1](https://arxiv.org/abs/2611.31043v1)

**摘要**
> Pretrained audio embeddings are increasingly used as intermediate representations for sound event detection (SED) and other always-on acoustic sensing tasks. While these representations are selected for their utility on downstream tasks, they may also retain sensitive information unrelated to their intended purpose, creating privacy risks even when raw audio is not exposed. In this work, we present an empirical framework for auditing privacy leakage from pretrained audio embeddings using two complementary approaches. First, we quantify representation-level leakage by measuring statistical dependence between an audio embedding and a representation specialized for encoding sensitive information. Second, we measure attack-level leakage by training lightweight adversarial probes to recover sensitive attributes directly from the embedding. We apply this framework to four widely used audio representations (CLAP, PANNs, AST, and YAMNet) and evaluate leakage of speaker identity and gender. We found that speaker identification balanced accuracy ranges from $0.43$ to $0.72$, while gender information is also strongly recoverable. Moreover, representation-level and attack-based measurements exhibit consistent trends, with CLAP leaking the most and YAMNet leaking the lest speaker identity. These results demonstrate that intermediate audio representations are not inherently privacy-preserving interfaces and motivate privacy leakage as an explicit criterion, alongside downstream utility, when selecting representations for acoustic sensing systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《What Do Sound Event Embeddings Reveal? Auditing Speaker Leakage in Audio Representations》所界定。 从摘要看，作者主要围绕 speaker identification、sound event detection 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These results demonstrate that intermediate audio representations are not inherently privacy-preserving interfaces and motivate privacy leakage as an explicit criterion, alongside downstream utility, when selecting representations for acoustic sensing systems. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speaker identification, sound event detection。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
