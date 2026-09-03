<div align="center">

# 📰 Paper Claw

**2026-09-03**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-02 13:09:33 CST → 2026-09-03 13:14:26 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 2 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 2, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Choosing a PEFT Variant for Per-Patient Dysarthric ASR: A Single-Speaker Case Study on Two ASR Bases

👤 **作者**: Bernard Muller, László Tóth, LaVonne Roberts
🔗 **来源**: [https://arxiv.org/abs/2609.02735v1](https://arxiv.org/abs/2609.02735v1)

**摘要**
> Per-patient adapters are the preferred production architecture for dysarthric automatic speech recognition (ASR), yet parameter-efficient fine-tuning (PEFT) variants have not been compared in the speaker-dependent, per-patient regime. We present a single-speaker case study comparing seven LoRA-family methods (LoRA, QLoRA, AdaLoRA, DoRA, LoHA, VeRA, VB-LoRA) on two production bases (Whisper-large-v3 with Hungarian fine-tuning, and a multilingual Qwen3-ASR-1.7B checkpoint) for one post-stroke Hungarian male speaker (S1, 409 utterances; severe dysarthria on auditory-perceptual clinical assessment). Attention-projection adapters substantially improve CER on both bases. Across three seeds, a paired bootstrap detects no significant LoRA-DoRA difference (p>0.5; 13.86/13.90 % CER on Whisper, 28.10/28.33 % on Qwen3-ASR), so we adopt the simpler, cheaper LoRA. Real 4-bit (NF4) QLoRA is worse on every seed and both bases (14.56/30.09 % CER) with no memory saving at this scale, and LoHA, VeRA, VB-LoRA and AdaLoRA do not reach the LoRA family, though LoHA still gives an 18.6 % relative CER reduction on Whisper. On the same base, full fine-tuning is more accurate (11.43 % CER), but a 115 MB LoRA that also adapts the feed-forward blocks reaches within 0.66 pp of it at approximately 3.7 % of the per-patient storage. A 6-point enrollment grid shows about 5 min of patient audio captures 45.6 % of the zero-shot-to-30-min CER reduction, with further gains at 10 and 30 min (caveat: one speaker, one language, severe post-stroke dysarthria). Training scripts and recipes will be released, source-available under a research-use licence, on publication.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Choosing a PEFT Variant for Per-Patient Dysarthric ASR: A Single-Speaker Case Study on Two ASR Bases》所界定。 从摘要看，作者主要围绕 automatic speech recognition、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Attention-projection adapters substantially improve CER on both bases. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automatic speech recognition, whisper。 |

---
### 2. VibeVoice-ASR-Streaming Technical Report

👤 **作者**: Yujie Tu, Zhiliang Peng, Jianwei Yu, Li Dong, Songchen Xu, Yaoyao Chang, Wenhui Wang, Zilong Wang, Zehua Wang, Yan Xia, Jiajun Zhang, Xie Chen, Furu Wei
🔗 **来源**: [https://arxiv.org/abs/2609.02812v1](https://arxiv.org/abs/2609.02812v1)

**摘要**
> Traditional speaker-attributed ASR systems treated ASR and speaker diarization as two separate tasks. Recently, end-to-end models such as VibeVoice-ASR have unified the two tasks within a single model. However, existing unified models still mainly support offline recognition, making it difficult to meet the low-latency requirements of real-time voice assistants and agents. To tackle this issue, we present VibeVoice-ASR-Streaming, one of the first LLM-based end-to-end approaches to streaming speaker-attributed ASR. It interleaves fixed-size audio chunks, a small amount of lookahead audio and previous text. This allows the model to produce ''who said what'' as speech arrives, without a separate diarization stage. For transcription accuracy, our 7B model achieves the lowest average WER/CER across five evaluation sets. For speaker attribution, it achieves the best or tied-best on 12 of 13 evaluation settings. We release the 1.5B and 7B model weights together with inference code.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《VibeVoice-ASR-Streaming Technical Report》所界定。 从摘要看，作者主要围绕 asr system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：For transcription accuracy, our 7B model achieves the lowest average WER/CER across five evaluation sets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：asr system。 |

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

### 1. Scalable Direction-Following TTS via Voice Impression-Guided Pseudo Triplet Construction

👤 **作者**: Kenichi Fujita, Yusuke Ijima
🔗 **来源**: [https://arxiv.org/abs/2609.02623v1](https://arxiv.org/abs/2609.02623v1)

**摘要**
> Voice actors often re-read the same script while modifying their delivery in response to performance directions. We study this setting as direction-following TTS, where a system generates a new utterance that reflects a given direction relative to a reference utterance while preserving speaker identity and linguistic content. A key challenge is the lack of training data capturing such relative modifications. To address this, we propose a scalable pseudo-triplet construction pipeline that generates~(reference utterance, direction text, modified utterance) triplets. It generates controlled style variations using an impression-controllable TTS model and uses an LLM to produce natural language directions from estimated impression differences. Experimental results demonstrate that pseudo-triplets alone enable stable speaker-preserving modification, and that combining pseudo and recorded data further improves direction alignment while maintaining speaker similarity. Audio examples are available on our demo page https://ntt-hilab-gensp.github.io/IS2026pseudo/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Scalable Direction-Following TTS via Voice Impression-Guided Pseudo Triplet Construction》所界定。 从摘要看，作者主要围绕 scalable、direction-following、voice 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results demonstrate that pseudo-triplets alone enable stable speaker-preserving modification, and that combining pseudo and recorded data further improves direction alignment while maintaining speaker similarity. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：scalable, direction-following, voice。 |

---
### 2. ARFT: A Synchronized Multimodal RF-Acoustic Dataset for Positioning in Distributed Environments

👤 **作者**: Daan Delabie, Jarne Van Mulders, Bert Pyck, Gustav Nilsson Gisleskog, Gilles Callebaut
🔗 **来源**: [https://arxiv.org/abs/2609.02657v1](https://arxiv.org/abs/2609.02657v1)

**摘要**
> This paper documents the acoustic-radio fusion in Techtile (ARFT) dataset, a synchronized measurement campaign for distributed wireless sensing and positioning in the Techtile testbed. Ultrasonic and radio frequency (RF) signals are simultaneously transmitted and captured at multiple positions in a 2D spatial grid inside the Techtile testbed. Each acquisition cycle corresponds to one rover stop, one position sample, one acoustic recording and one RF snapshot. The RF modality is recorded as per-host pilot measurements and released as channel state information (CSI) tensors for 42 antennas mounted at the ceiling of the room. The acoustic chirp is recorded with 91 synchronized microphones and transmitted by a synchronized quasi omni-directional speaker. The campaign spans 5011 spatial position samples spanning a 5.57 m by 2.89 m area with complete RF and acoustic data. We detail how the measurements are recorded, quantify per-experiment coverage, describe the RF and acoustic data contents, and explain how the aligned modalities support RF-only, acoustic-only, and joint positioning workflows. Furthermore, a static acoustic positioning pipeline that performs anchor selection, pulse-compression ranging, and least squares (LS) localization is elaborated.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ARFT: A Synchronized Multimodal RF-Acoustic Dataset for Positioning in Distributed Environments》所界定。 从摘要看，作者主要围绕 arft、synchronized、multimodal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Ultrasonic and radio frequency (RF) signals are simultaneously transmitted and captured at multiple positions in a 2D spatial grid inside the Techtile testbed. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：arft, synchronized, multimodal。 |

---
### 3. Understanding Automatic Mixing: A Subtask-Oriented Analysis of Two-Stage Mixing System

👤 **作者**: Jinjie Shi, Wei Hua, Kunzhu Xie, Make Li, Yuchen Liu, Joshua Reiss
🔗 **来源**: [https://arxiv.org/abs/2609.02835v1](https://arxiv.org/abs/2609.02835v1)

**摘要**
> Automatic mixing transforms multitrack recordings into perceptually coherent, balanced, and aesthetically consistent mixes. In real-world production, this task is challenging due to large track counts, diverse instrumentation, and strong inter-track dependencies. Two-stage systems address this complexity by separating intra-group processing from inter-group mixing, yet it remains unclear whether their gains arise from stronger component models or from explicit task decomposition. We present a subtask-oriented analysis of automatic mixing through three controlled listening experiments. We investigate whether full-mix models transfer to intra-group mixing, whether downstream models compensate for grouping and loudness errors, and whether two-stage decomposition improves full-mix quality. Across three dense pop and rock excerpts, transfer differs between the evaluated models; inappropriate grouping causes clear downstream degradation, while altered loudness relationships have weaker and model-dependent effects. Both two-stage variants significantly outperform their corresponding single-stage baselines. These findings support explicit separation of local balance and global mix coordination as a useful design principle for automatic mixing. Code and audio examples are available online.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Understanding Automatic Mixing: A Subtask-Oriented Analysis of Two-Stage Mixing System》所界定。 从摘要看，作者主要围绕 understanding、automatic、mixing 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We investigate whether full-mix models transfer to intra-group mixing, whether downstream models compensate for grouping and loudness errors, and whether two-stage decomposition improves full-mix quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：understanding, automatic, mixing。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
