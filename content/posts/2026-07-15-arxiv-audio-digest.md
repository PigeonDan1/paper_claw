<div align="center">

# 📰 Paper Claw

**2026-07-15**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-14 11:49:21 CST → 2026-07-15 11:50:16 CST |
| 📄 论文总数 | **8** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 8 篇新论文，主要分布在 ASR 1, TTS 1, Enhancement 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Audio-Native Speech Recognition with a Frozen Discrete-Diffusion Language Model

👤 **作者**: Harsha Vardhan Khurdula, Abhinav Kumar Singh, Yoeven D Khemlani, Vineet Agarwal
🔗 **来源**: [https://arxiv.org/abs/2607.13013v1](https://arxiv.org/abs/2607.13013v1)

**摘要**
> Automatic speech recognition is dominated by autoregressive decoders that emit one token at a time. We ask whether a discrete diffusion language model can transcribe speech instead, refining a whole transcript in parallel over a small number of denoising steps. We train an audio-native interface for DiffusionGemma, a 26B mixture-of-experts model that generates text by uniform, random-token discrete diffusion rather than the absorbing-mask scheme common to recent diffusion language models. A frozen Whisper encoder supplies acoustic features, a lightweight projector maps them into the model embedding space, and low-rank adapters let the frozen backbone attend to the new modality. About 42M parameters are trained, which is 0.16 percent of the backbone. We find that the natural training objectives fail to ground the audio because their gradient reaches the projector only through attention that has already dismissed it. A connectionist temporal classification loss applied through the frozen output head breaks this deadlock. The resulting model reaches 6.6 percent word error rate on LibriSpeech test-clean, transcribes in roughly eight parallel steps regardless of utterance length, and uses a single adapter trained on six languages, which we evaluate here on English, Hindi, and Mandarin.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Audio-Native Speech Recognition with a Frozen Discrete-Diffusion Language Model》所界定。 从摘要看，作者主要围绕 automatic speech recognition、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We ask whether a discrete diffusion language model can transcribe speech instead, refining a whole transcript in parallel over a small number of denoising steps. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automatic speech recognition, whisper。 |

---
## 🏷️ TTS

### 1. AutoSIFT: Automatic Style Sifting for Controllable Speech Generation with Arbitrary Style Infilling

👤 **作者**: Haowei Lou, Junda Wu, Chengkai Huang, Tong Yu, Hye-young Paik, Wen Hu, Lina Yao
🔗 **来源**: [https://arxiv.org/abs/2607.12706v1](https://arxiv.org/abs/2607.12706v1)

**摘要**
> State-of-the-art text-to-speech (TTS) models achieve impressive naturalness and expressiveness, yet fine-grained, disentangled control over speaking styles remains challenging. In professional scenarios such as film dubbing, game voice acting, and video content generation, users often need to modify a specific style category, such as emotion, age, or gender, while preserving all others. Existing style-controllable TTS methods typically rely on either text-described styles or speech-reference style transfer, making it difficult to jointly control explicit semantic attributes and preserve subtle, text-undescribed prosodic details. We propose AutoSIFT, a controllable speech generation framework for category-level style editing. AutoSIFT decomposes speaking style into known text-describable categories and unknown residual styles that capture non-verbal prosody and speaker-specific nuances. It consists of a generalized Style Disentangler, which extracts category-aware style prototypes from reference speech, and an Arbitrary Style Infiller, which selectively infills unspecified style categories from the reference. By replacing only text-specified style categories while preserving residual speech-derived styles, AutoSIFT enables natural, expressive, and highly customizable speech generation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《AutoSIFT: Automatic Style Sifting for Controllable Speech Generation with Arbitrary Style Infilling》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：State-of-the-art text-to-speech (TTS) models achieve impressive naturalness and expressiveness, yet fine-grained, disentangled control over speaking styles remains challenging. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
## 🏷️ Enhancement

### 1. Low-Latency Neural Models for Real-Time Music Enhancement

👤 **作者**: Emmanouil Karystinaios, Jonathan Greif, David Nadrchal, Paul Primus, Gerhard Widmer
🔗 **来源**: [https://arxiv.org/abs/2607.12872v1](https://arxiv.org/abs/2607.12872v1)

**摘要**
> Music recordings and live streams are often affected by noise, reverberation, spectral imbalances, or artifacts that degrade listening quality. While speech enhancement has matured into a well-defined research area, music enhancement is less established because musical signals combine overlapping sources, wide bandwidths, strong dynamics, and intentional production effects. We study real-time music enhancement under strict causal and low-latency constraints. We formulate the task around recovery of the intended produced mix from acoustic and production-oriented degradations, adapt compact causal networks to music, and compare speech-derived real-time baselines, an external music-denoising model, an offline restoration reference, and a music-specific MusicFilterNet-MS variant. On the tested hardware, all causal models run faster than real time, but improvements depend strongly on the dataset, degradation type, and metric family; under several objective criteria, indiscriminate enhancement can worsen the degraded input. The main contribution is therefore a benchmark and an analysis rather than a universal best model: real-time music enhancement is feasible, but robust improvement requires degradation-aware modeling, stereo-aware processing, identity-preserving correction, and evaluation beyond a single objective score.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Low-Latency Neural Models for Real-Time Music Enhancement》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On the tested hardware, all causal models run faster than real time, but improvements depend strongly on the dataset, degradation type, and metric family; under several objective criteria, indiscriminate enhancement can worsen the degraded input. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Contrasting statistical patterns in melodic and molecular evolution reveal distinctive constraints in a culturally evolving system

👤 **作者**: John M McBride, W Tecumseh Fitch
🔗 **来源**: [https://arxiv.org/abs/2607.12673v1](https://arxiv.org/abs/2607.12673v1)

**摘要**
> Evolved sequences can be used to infer the rules of evolution. Orally transmitted folk melodies are evolved sequences whose similarity to protein sequences (one-dimensional, drawn from a limited alphabet) invites application of bioinformatics methods to study cultural evolution. A major obstacle is that melodies encode rhythm, which breaks some assumptions of standard sequence-alignment algorithms. We develop a rhythm-aware alignment method and apply it to \num{40000} Irish dance tune variants, enabling the first large-scale automated melodic alignment. Four canonical bioinformatics analyses -- mutability, substitution matrices, positional conservation, and covariance -- reveal patterns distinct from those of molecular evolution, revealing the forces that shape each domain: biochemical and biophysical constraints for proteins; memory, motor, and social biases for melodies. Together the results show that bioinformatics provides a powerful framework -- conceptual as much as algorithmic -- for studying cultural evolution. Although the cultural transmission of music has been discussed for centuries, here we show how to analyze it at large scale.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Contrasting statistical patterns in melodic and molecular evolution reveal distinctive constraints in a culturally evolving system》所界定。 从摘要看，作者主要围绕 contrasting、statistical、patterns 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Together the results show that bioinformatics provides a powerful framework -- conceptual as much as algorithmic -- for studying cultural evolution. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：contrasting, statistical, patterns。 |

---
### 2. Audio Diarization: A New Paradigm for Exploring Audio Recordings with Unknown Event Classes

👤 **作者**: Alexander Werning, Reinhold Haeb-Umbach
🔗 **来源**: [https://arxiv.org/abs/2607.12703v1](https://arxiv.org/abs/2607.12703v1)

**摘要**
> We propose a new task, audio diarization. The motivation is that there are applications, such as audio monitoring in an unknown environment, where initially the sound event classes to be recognized are unknown. For such a scenario, we propose to first localize in time relevant sound events and to classify them, e.g., by comparing with known event classes, in a second step. This contribution is dedicated to the first step, which we call audio diarization, as it is reminiscent of the speaker diarization stage that precedes and simplifies the second stage, speech recognition, in multi-talker conversational speech processing. In this contribution, we define audio diarization as detecting onset and offset times of sound events with overlap for an open set of classes and without user prompts. We show how a speaker diarization system can be adjusted for audio diarization and propose an evaluation setup. Compared to a closed-set sound event detection system, the proposed system achieves similar performance with the additional ability to detect novel sounds.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Audio Diarization: A New Paradigm for Exploring Audio Recordings with Unknown Event Classes》所界定。 从摘要看，作者主要围绕 sound event detection 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show how a speaker diarization system can be adjusted for audio diarization and propose an evaluation setup. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sound event detection。 |

---
### 3. Neural Morphing: Sequence-Optimized Token-Level Morphing in Neural Audio Codecs

👤 **作者**: Emmanouil Karystinaios
🔗 **来源**: [https://arxiv.org/abs/2607.12725v1](https://arxiv.org/abs/2607.12725v1)

**摘要**
> Neural audio codecs were originally developed for high-fidelity compression; however, their latent token representations and expressive decoders also constitute a powerful substrate for controllable audio transformation. This work introduces Neural Morphing, a training-free token-domain audio effect that selects residual-vector-quantized (RVQ) token grains from a user palette and decodes the edited stream through a pretrained codec. The method combines an RVQ-group transfer policy that separates coarse, middle, and fine codebook groups with a continuity-constrained sequence matcher that replaces independent greedy selection with bounded beam search. The intended output is a controlled hybrid: the source preserves rhythmic organization while the palette contributes timbral color and residual detail. We focus on the implementation and realtime behavior of a deployable VST3/AU system, including chunked rendering, palette-size scaling, and backend health checks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Neural Morphing: Sequence-Optimized Token-Level Morphing in Neural Audio Codecs》所界定。 从摘要看，作者主要围绕 neural、morphing、sequence-optimized 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This work introduces Neural Morphing, a training-free token-domain audio effect that selects residual-vector-quantized (RVQ) token grains from a user palette and decodes the edited stream through a pretrained codec. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：neural, morphing, sequence-optimized。 |

---
### 4. Spatial-Frequency Cued Generative Fixed-Filter Active Noise Control Based on Deep Learning in Reverberant Environments

👤 **作者**: Boxiang Wang, Haowen Li, Dongyuan Shi, Junwei Ji, Ziyi Yang, Zhengding Luo, Woon-Seng Gan
🔗 **来源**: [https://arxiv.org/abs/2607.12807v1](https://arxiv.org/abs/2607.12807v1)

**摘要**
> Generative fixed-filter active noise control (GFANC) effectively attenuates noise with diverse frequency characteristics through the combination of sub control filters. However, it does not incorporate the spatial information of the noise source, which limits its performance, particularly in reverberant environments. To address this limitation, this paper proposes a novel spatial-frequency cued GFANC (SF-GFANC) method that exploits both three-dimensional (3D) spatial and frequency information of the noise source. Specifically, a multi-task convolutional recurrent neural network (CRNN) is designed to estimate the source distance, elevation angle, and azimuth angle as spatial cues, while predicting the combination weights of sub control filters as frequency cues. These spatial-frequency cues jointly guide the generation of the appropriate control filter. In addition, a theoretical analysis of the optimal control filter in reverberant environments is presented, highlighting the importance of 3D spatially conditioned control filter design. Evaluations using both simulated and measured acoustic paths demonstrate that the CRNN is robust to unseen acoustic environments and noise types. Furthermore, the results confirm that SF-GFANC outperforms representative ANC algorithms when handling noise sources across diverse 3D locations and frequency characteristics in reverberant environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Spatial-Frequency Cued Generative Fixed-Filter Active Noise Control Based on Deep Learning in Reverberant Environments》所界定。 从摘要看，作者主要围绕 spatial-frequency、cued、generative 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluations using both simulated and measured acoustic paths demonstrate that the CRNN is robust to unseen acoustic environments and noise types. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spatial-frequency, cued, generative。 |

---
### 5. ChartGenEval: Corruption-Tested Multi-Dimensional Feedback for Rhythm-Game Chart Generation

👤 **作者**: Jhen-Ke Lin
🔗 **来源**: [https://arxiv.org/abs/2607.12857v1](https://arxiv.org/abs/2607.12857v1)

**摘要**
> A generated rhythm-game chart need not reproduce one official note sequence: many note choices can fit the same song and difficulty. Reference-note agreement therefore measures reconstruction, not the full design problem. We introduce ChartGenEval, a six-question evaluation framework with an automatic, corruption-tested core. It leaves note choice open while anchoring timing to the song: the matched official chart supplies only its authored timing map, never target notes. We test each core output with dose-controlled failures rather than assume that a familiar statistic measures chart quality. Across 80 held-out song groups, seven output axes satisfy prespecified sensitivity and invariance criteria in nine nonredundant tests. Complementary stress tests on the 40-song development panel expose two broader lessons. A chart-wide phase estimate recovers injected shifts of 15, 30, and 60 ms while chart-only outputs remain essentially unchanged. Common-pattern rewriting lowers mean language-model perplexity by 37%, and loop collapse raises mean self-similarity by 62%. ChartGenEval therefore reports separate, role-specific signals instead of one proxy or total score. This profile provides automatic feedback for comparing and iterating generators; selected outputs are candidate optimization targets or constraints after task-specific stress testing.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ChartGenEval: Corruption-Tested Multi-Dimensional Feedback for Rhythm-Game Chart Generation》所界定。 从摘要看，作者主要围绕 chartgeneval、corruption-tested、multi-dimensional 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Reference-note agreement therefore measures reconstruction, not the full design problem. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：chartgeneval, corruption-tested, multi-dimensional。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
