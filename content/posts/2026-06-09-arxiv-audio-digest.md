<div align="center">

# 📰 Paper Claw

**2026-06-09**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-08 13:20:40 CST → 2026-06-09 12:56:38 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 2 篇
- **Enhancement**: 2 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 6 篇新论文，主要分布在 ASR 1, TTS 2, Enhancement 2, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Overcoming Decoder Inconsistencies in Whisper for Dravidian and Low-Resource Languages

👤 **作者**: Chowdam Venkata Kumar, Kumud Tripathi, Pankaj Wasnik
🔗 **来源**: [https://arxiv.org/abs/2606.09535v1](https://arxiv.org/abs/2606.09535v1)

**摘要**
> Multilingual ASR models such as Whisper perform well on high-resource languages but exhibit substantially higher Word Error Rates (WER) for Dravidian languages compared to Indo-Aryan ones. Through linguistic and dataset analysis, we show that Dravidian languages have longer words, higher vocabulary diversity, and lower repetition, resulting in sparse token distributions and frequent character-level substitution errors. Baseline fine-tuning further reveals decoder imbalance between self-attention (linguistic context) and cross-attention (acoustic cues). Although synthetic token-repetition experiments indicate potential gains, they are impractical. Motivated by these observations, we introduce two decoder-level enhancements: Weighted-Attention, which adaptively balances attention sources, and Self-Conditioning, which reinjects intermediate predictions to improve token consistency. Experiments demonstrate consistent WER reductions for low-resource and agglutinative languages.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Overcoming Decoder Inconsistencies in Whisper for Dravidian and Low-Resource Languages》所界定。 从摘要看，作者主要围绕 whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Through linguistic and dataset analysis, we show that Dravidian languages have longer words, higher vocabulary diversity, and lower repetition, resulting in sparse token distributions and frequent character-level substitution errors. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：whisper。 |

---
## 🏷️ TTS

### 1. Cross-Modal Masking for Robust Silent Speech Synthesis Using sEMG and Lipreading

👤 **作者**: Eder del Blanco, David Gimeno-Gómez, Eva Navas, Carlos-D. Martínez-Hinarejos, Inma Hernáez
🔗 **来源**: [https://arxiv.org/abs/2606.09667v1](https://arxiv.org/abs/2606.09667v1)

**摘要**
> Speech restoration through silent speech interfaces (SSIs) has emerged as a promising assistive technology for individuals with impaired or absent laryngeal voice production. Among non-invasive SSI modalities, surface electromyography (sEMG) and video-based lipreading provide complementary articulatory information, yet their integration for continuous speech synthesis remains underexplored. Moreover, existing multimodal approaches rarely address robustness to modality degradation or temporary sensor failure, limiting their applicability in realistic scenarios. In this work, we propose a masked multimodal speech synthesis framework that jointly leverages sEMG and lipreading signals through modality masking during training. Under multispeaker settings, the proposed approach reduces word error rate by up to 14 absolute percentage points compared to the strongest unimodal baseline. Experimental results not only show that masking strategies are critical for these performance gains and robustness under low-bitrate conditions, but also that they generalize better than degradation-specific data augmentations in the presence of modality absence conditions. Phone-level analyses further reveal complementary contributions across modalities, with particularly strong benefits for vowels and for specific consonant groups. Overall, these findings demonstrate the effectiveness and robustness of masked multimodal integration for silent speech synthesis, although adaptation to laryngectomized speakers remains an open research challenge.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Cross-Modal Masking for Robust Silent Speech Synthesis Using sEMG and Lipreading》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results not only show that masking strategies are critical for these performance gains and robustness under low-bitrate conditions, but also that they generalize better than degradation-specific data augmentations in the presence of modality absence conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

---
### 2. What Makes Synthetic Speech Sound Sarcastic? A Prosody-Controlled Perception Study

👤 **作者**: Zhu Li, Shekhar Nayak, Matt Coler
🔗 **来源**: [https://arxiv.org/abs/2606.09717v1](https://arxiv.org/abs/2606.09717v1)

**摘要**
> Prosody plays a central role in sarcasm perception, yet previous studies have relied on naturally produced speech that lacks fine-grained control over individual acoustic dimensions. As prosodic cues co-vary in natural data, isolating their independent contributions remains challenging. We introduce a controlled framework using neural text-to-speech (TTS) with prompt-based prosodic conditioning to manipulate speech rate, pitch variation, and loudness. An orthogonal stimulus set was constructed to enable causal testing of prosodic cue effects. Human listeners rated sarcasm and naturalness, and their judgments were compared with predictions from a foundation model capable of processing audio input. Results show that loudness primarily drives human sarcasm perception, whereas the model assigns greater weight to speech rate, leading to distinct cue-weighting patterns. This study shows how controllable neural TTS enables investigation of prosodic cue weighting in speech perception.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《What Makes Synthetic Speech Sound Sarcastic? A Prosody-Controlled Perception Study》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that loudness primarily drives human sarcasm perception, whereas the model assigns greater weight to speech rate, leading to distinct cue-weighting patterns. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
## 🏷️ Enhancement

### 1. Your U-Net Dereverberation Model is Secretly an RIR Encoder

👤 **作者**: Sina Khanagha, Timo Gerkmann
🔗 **来源**: [https://arxiv.org/abs/2606.09557v1](https://arxiv.org/abs/2606.09557v1)

**摘要**
> In this work, we analyze the ability of NCSN++ U-Net based audio dereverberation models to capture global room characteristics in their intermediate representations. Through an empirical study of both a state-of-the-art diffusion-based model and a discriminative counterpart, we show that deeper layers encode structured room impulse response (RIR)-dependent embeddings. Moreover, the discriminative ability of this implicit room representation correlates with dereverberation performance across objective metrics. Motivated by this observation, we propose a training strategy that explicitly conditions the network on pre-trained RIR embeddings, obtained via self-supervised contrastive learning. Incorporating RIR conditioning improves representation quality, accelerates convergence, and enhances dereverberation performance, while significantly reducing the number of reverse diffusion steps required by the diffusion-based model during inference.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Your U-Net Dereverberation Model is Secretly an RIR Encoder》所界定。 从摘要看，作者主要围绕 dereverberation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Through an empirical study of both a state-of-the-art diffusion-based model and a discriminative counterpart, we show that deeper layers encode structured room impulse response (RIR)-dependent embeddings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dereverberation。 |

---
### 2. MeCo: One-Step MeanFlow-based Corrector for Multi-Channel Speech Separation

👤 **作者**: Dohwan Kim, Jung-Woo Choi
🔗 **来源**: [https://arxiv.org/abs/2606.09677v1](https://arxiv.org/abs/2606.09677v1)

**摘要**
> While discriminative models for multi-channel speech separation excel in reference-based metrics, they often exhibit suboptimal human listening quality. To address this, we propose a novel MeanFlow-based one-step generative corrector (MeCo). MeCo learns a conditional average velocity field to map discriminative estimates directly onto the clean speech manifold in a single step. To maximize one-step generation performance, we introduce Data-Space Optimization (DSO). DSO integrates an $\mathbf{x}_r$-loss, which penalizes prediction errors on longer displacement intervals to serve as a generative objective for human listening quality, with an Endpoint SI-SDR loss that directly optimizes terminal signal fidelity. Experiments demonstrate that MeCo achieves state-of-the-art (SOTA) performance with minimal computational overhead, simultaneously achieving superior signal fidelity and human listening quality in both in-domain and out-of-domain scenarios.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《MeCo: One-Step MeanFlow-based Corrector for Multi-Channel Speech Separation》所界定。 从摘要看，作者主要围绕 speech separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments demonstrate that MeCo achieves state-of-the-art (SOTA) performance with minimal computational overhead, simultaneously achieving superior signal fidelity and human listening quality in both in-domain and out-of-domain scenarios. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Quality-Diversity Search in Sound Generation: Investigating Innovation Engines for Audio Exploration

👤 **作者**: Björn Þór Jónsson, Çağrı Erdem, Stefano Fasciani, Kyrre Glette
🔗 **来源**: [https://arxiv.org/abs/2606.09780v1](https://arxiv.org/abs/2606.09780v1)

**摘要**
> This study addresses the challenges composers and sound designers face in creating and refining tools to achieve their musical goals. Using evolutionary processes to promote diversity and foster serendipitous discoveries, we automate the search through uncharted sonic spaces for sound discovery, arguing that diversity-promoting algorithms can bridge the gap between the theoretical realisation and practical accessibility of sounds. We describe a system for generative sound synthesis combining Quality Diversity (QD) algorithms with a supervised discriminative model, inspired by the Innovation Engine algorithm, and explore different configurations and the interplay between the chosen synthesis approach and the discriminative model. We examine the interaction between Compositional Pattern Producing Networks (CPPNs) and Digital Signal Processing (DSP) graphs, introducing a novel approach that uses multiple specialised CPPNs for different frequency ranges; this yields simpler networks while maintaining performance comparable to single-CPPN setups. We also investigate evolutionary stepping stones by analysing goal switches between musical and non-musical contexts, revealing how lineages traverse unlikely paths to current elites. Expanding the behaviour space of a previous study to include various sound durations, we uncover specialisation within temporal niches. Results indicate that CPPN and DSP graphs coupled with a Multi-dimensional Archive of Phenotypic Elites (MAP-Elites) and a deep learning classifier can generate a substantial variety of synthetic sounds, diverse and innovative across temporal and contextual dimensions. We present the generated sound objects through an online explorer and as rendered sound files, and, in the context of music composition, an experimental application that showcases their creative potential across various durations and contexts.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Quality-Diversity Search in Sound Generation: Investigating Innovation Engines for Audio Exploration》所界定。 从摘要看，作者主要围绕 sound synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This study addresses the challenges composers and sound designers face in creating and refining tools to achieve their musical goals. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sound synthesis。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
