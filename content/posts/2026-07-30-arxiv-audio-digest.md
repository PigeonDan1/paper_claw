<div align="center">

# 📰 Paper Claw

**2026-07-30**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-29 11:56:33 CST → 2026-07-30 11:47:52 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 3 篇新论文，主要分布在 Speech LLM 1, Enhancement 1, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Qwen-Audio-3.0-Gen-Preview Technical Report

👤 **作者**: Junyu Dai, Xiaoyue Duan, Xinyue Fan, Yihan Feng, Xiangang Li, Yunjia Li, Lejun Min, Yufei Shi, Xingchen Song, Yiran Wang, Cheng Wen, Menglin Wu, Bajian Xiang, Huaicheng Zhang, Han Zhao, Ruichen Zheng
🔗 **来源**: [https://arxiv.org/abs/2607.27011v1](https://arxiv.org/abs/2607.27011v1)

**摘要**
> Existing single-domain and multi-task audio systems remain limited in directly organizing speech, music, sound effects, ambience, and multiple roles into long-form temporal scenes. We present Qwen-Audio-3.0-Gen-Preview, a unified non-autoregressive framework that uses a Diffusion Transformer (DiT) and a shared variational autoencoder (VAE) to generate the complete mixed waveform. Prompt enhancement converts free-form requests into structured temporal records that are rendered as textual conditions, while a two-stage data curriculum and semantic conditional views train the proposed model to use these conditions across domains. A shared continuous VAE compresses 48kHz stereo waveforms into 25Hz latent sequences and incorporates semantic supervision, providing one representation for speech, music, sound effects, and their mixtures. On Seed-TTS-Eval, speaker similarity is the proposed model's clearest strength across all three subsets, and on the multi-speaker benchmark, the proposed model shows higher cross-turn consistency than Seed-Audio-1.0 in both languages. On AudioCaps, its advantages are concentrated in evaluations using large audio-language models and AudioBox. Relative to Seed-Audio-1.0, it achieves stronger temporal localization. Using approximately 10% music data of a dedicated in-house model, the proposed model remains close across all seven SongBench components and leads in three while retaining speech and general-audio capabilities. These results demonstrate the potential of unified generation for temporally structured, multi-domain audio.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Qwen-Audio-3.0-Gen-Preview Technical Report》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On Seed-TTS-Eval, speaker similarity is the proposed model's clearest strength across all three subsets, and on the multi-speaker benchmark, the proposed model shows higher cross-turn consistency than Seed-Audio-1.0 in both languages. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. Detection of AI-generated stems within hybrid human-AI music

👤 **作者**: François Rigaud, Gabriel Meseguer-Brocal, Benjamin Martin, Romain Hennequin
🔗 **来源**: [https://arxiv.org/abs/2607.26874v1](https://arxiv.org/abs/2607.26874v1)

**摘要**
> This paper presents, to the best of our knowledge, the first study on detecting human-AI hybrid music tracks created by mixing human-produced and AI-generated stems. Building on recent work showing that AI music detectors can identify decoder-related artifacts in fully generated music, we investigate whether such artifacts remain detectable at the stem level after mixing. Using MUSDB18-HQ database in a two-stem vocals + accompaniment setting, we simulate hybrid mixtures by autoencoding individual stems with a neural codec. We compare two strategies combining AI-generated mix detection and source separation. A naive sequential pipeline, where source separation is followed by detection on separated sources, confirms that artifacts associated with an AI-generated stem are not reliably recovered by generic source separation systems. We therefore propose a parallel architecture in which source separation is only used to estimate source-relative energy within the mixture. We then train simple stem-specific binary classifiers that take as input the generated mix prediction together with the relative energy of the target stem on short audio chunks. Averaging chunk-level predictions yields encouraging track-level results, highlighting the potential of such approaches for detecting AI-generated stems in hybrid music.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Detection of AI-generated stems within hybrid human-AI music》所界定。 从摘要看，作者主要围绕 source separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Building on recent work showing that AI music detectors can identify decoder-related artifacts in fully generated music, we investigate whether such artifacts remain detectable at the stem level after mixing. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. MMAC: A Massive Multi-dimensional Benchmark for Audio Captioning

👤 **作者**: Weijie Wu, Junbo Li, Lin Li, Jun Fang, Qingyang Hong
🔗 **来源**: [https://arxiv.org/abs/2607.27109v1](https://arxiv.org/abs/2607.27109v1)

**摘要**
> With the development of audio large language models (AudioLLMs), audio captioning needs to move from brief descriptions toward open-ended and fine-grained free-form descriptions. Existing evaluations often focus on generation quality or task performance, making it difficult to diagnose information coverage and description reliability. We propose MMAC, a \textbf{M}assive \textbf{M}ulti-dimensional benchmark for \textbf{A}udio \textbf{C}aptioning. MMAC contains 5,638 audio clips from more than 20 data sources, covering 6 capability categories and 15 evaluation dimensions. Given a model-generated caption, MMAC checks whether it mentions relevant information in the target dimension and whether the mentioned content is consistent with the reference label. We evaluate representative open-source and proprietary AudioLLMs. Results show clear differences across evaluation dimensions, information coverage, and description reliability. We will release the MMAC benchmark and evaluation code.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MMAC: A Massive Multi-dimensional Benchmark for Audio Captioning》所界定。 从摘要看，作者主要围绕 mmac、massive、multi-dimensional 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show clear differences across evaluation dimensions, information coverage, and description reliability. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：mmac, massive, multi-dimensional。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
