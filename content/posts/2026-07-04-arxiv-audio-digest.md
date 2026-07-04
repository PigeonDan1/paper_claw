<div align="center">

# 📰 Paper Claw

**2026-07-04**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-02 12:49:35 CST → 2026-07-04 12:25:37 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 2 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 2, Enhancement 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. An Efficient vLLM-Based Inference Pipeline for Unified Audio Understanding and Generation

👤 **作者**: Haoran Wang, Jinchuan Tian, Siddhant Arora, Shinji Watanabe
🔗 **来源**: [https://arxiv.org/abs/2607.02119v1](https://arxiv.org/abs/2607.02119v1)

**摘要**
> While Large Multimodal Models excel in comprehension, high-throughput inference engines lack native support for multimodal generation. This is severe in Speech Language Models, where generating multi-layered audio tokens via decoupled AR+NAR or synchronous Multi-Token Prediction (MTP) with delay-pattern interleaving conflicts with standard single-stream loops. We present a vLLM-based inference pipeline for unified speech understanding and generation. We extend autoregressive decoding to natively execute delay-pattern de-interleaving and coordinated multi-stream sampling, integrating an on-GPU acoustic decoder for end-to-end waveform synthesis. Crucially, we overcome the shared intuition that Classifier-Free Guidance (CFG) halves throughput. By co-scheduling paired conditional and unconditional requests within a continuous batch, our CFG implementation sustains 80% of non-CFG throughput, absorbing dual-request and logit merging overheads. We open-source our framework.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《An Efficient vLLM-Based Inference Pipeline for Unified Audio Understanding and Generation》所界定。 从摘要看，作者主要围绕 speech language model、speech understanding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This is severe in Speech Language Models, where generating multi-layered audio tokens via decoupled AR+NAR or synchronous Multi-Token Prediction (MTP) with delay-pattern interleaving conflicts with standard single-stream loops. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech language model, speech understanding。 |

---
### 2. Unlocking Speech-Text Compositional Powers: Instruction-Following Speech Language Models without Instruction Tuning

👤 **作者**: Congrui Du, Yang Zhang, Kaizhi Qian, Shiyu Chang
🔗 **来源**: [https://arxiv.org/abs/2607.02214v1](https://arxiv.org/abs/2607.02214v1)

**摘要**
> Instruction tuning for speech language models (SLMs) is substantially more challenging than for text-based large language models (LLMs), as it requires learning a new modality and a wide range of speech-specific instructions in addition to those supported by text LLMs. Existing SLM training approaches largely replicate the text LLM training paradigm by synthesizing large-scale speech pre-training and instruction-tuning datasets. However, this strategy is difficult to scale, since speech sequences are significantly longer than text sequences. In this paper, we propose SpeechCombine, an instruction-following speech language model trained without any instruction tuning, using only a single round of speech pre-training on 30k hours of data. Starting from a text LLM base model, we perform continuous pre-training on speech utterances to obtain a speech-adapted model, and then directly combine its weights with the weight difference between the instruction-tuned and base versions of the text LLM. Our results show that this simple combination strategy not only preserves the knowledge and capabilities of the original text LLM, but also effectively transfers them to the speech domain. These findings suggest a new direction for SLM training that avoids reliance on massive speech data.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Unlocking Speech-Text Compositional Powers: Instruction-Following Speech Language Models without Instruction Tuning》所界定。 从摘要看，作者主要围绕 speech language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that this simple combination strategy not only preserves the knowledge and capabilities of the original text LLM, but also effectively transfers them to the speech domain. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. Spatial Speech Perception Systems: A Survey of Sound Source Localization, Directional Enhancement, and Speech Recognition

👤 **作者**: Pengyuan Shao, Dimitrios Kanoulas
🔗 **来源**: [https://arxiv.org/abs/2607.02296v1](https://arxiv.org/abs/2607.02296v1)

**摘要**
> Robust speech understanding in real-world acoustic environments remains a fundamental challenge for intelligent auditory systems such as robot audition, hearing aids, teleconferencing systems, smart speakers, and voice-controlled assistants. These systems must operate under background noise, reverberation, competing speakers, and dynamic acoustic conditions. Spatial speech perception addresses this challenge by exploiting microphone-array information to localize, enhance, and interpret target speech in complex acoustic scenes. This paper surveys spatial speech perception systems with emphasis on the roles of sound source localization (SSL), directional speech enhancement (DSE), and automatic speech recognition (ASR), both individually and within integrated processing pipelines. We review classical signal-processing approaches and recent learning-based methods for microphone-array localization, beamforming, neural enhancement, speech separation, and modern recognition architectures. Beyond component-level analysis, we discuss robustness to noise and reverberation, multi-speaker operation, real-time constraints, and computational efficiency. We also examine representative applications in robot audition, hearing assistance, smart speakers, and teleconferencing, and identify open challenges and future directions toward robust, low-latency, and perception-aware speech systems for complex acoustic environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Spatial Speech Perception Systems: A Survey of Sound Source Localization, Directional Enhancement, and Speech Recognition》所界定。 从摘要看，作者主要围绕 speech understanding、automatic speech recognition、speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These systems must operate under background noise, reverberation, competing speakers, and dynamic acoustic conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech understanding, automatic speech recognition, speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Speaker head orientation estimation with a single microphone array using phase spectrogram features

👤 **作者**: Balint Turi, Archontis Politis, Parthasaarathy Sudarsanam, Tuomas Virtanen
🔗 **来源**: [https://arxiv.org/abs/2607.02129v1](https://arxiv.org/abs/2607.02129v1)

**摘要**
> Estimating a speaker's head orientation from audio can provide valuable information in smart environments, meetings, and driver monitoring. We propose a novel approach that leverages the phase component of the short-time Fourier transform from a single microphone array as input to a deep neural network combining convolutional, recurrent, and self-attention layers. Unlike prior methods that use physics-informed handcrafted features or raw waveform inputs, our approach enables robust learning from simulated and real data. Trained on a large-scale dataset generated with voice directivity patterns and fine-tuned on real recordings, our model achieves state-of-the-art accuracy, outperforming baselines under both clean and noisy conditions. Personalization experiments further demonstrate significant gains, reaching a mean angular error of 11.3 degrees when adapting to individual users and environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Speaker head orientation estimation with a single microphone array using phase spectrogram features》所界定。 从摘要看，作者主要围绕 speaker、head、orientation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Trained on a large-scale dataset generated with voice directivity patterns and fine-tuned on real recordings, our model achieves state-of-the-art accuracy, outperforming baselines under both clean and noisy conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speaker, head, orientation。 |

---
### 2. Cross Domain Few-Shot Class-Incremental Audio Classification Via Adversarial Contrastive Learning

👤 **作者**: Yongjie Si, Yanxiong Li, Sen Huang, Beibei Liu
🔗 **来源**: [https://arxiv.org/abs/2607.02254v1](https://arxiv.org/abs/2607.02254v1)

**摘要**
> Current Few-shot Class-incremental Audio Classification (FCAC) methods assume that samples of base and incremental classes are in the same domain (following the same distribution). However, there is generally a domain shift between the above two types of samples. In this paper, we explore the problem of Cross Domain FCAC where samples of base and incremental classes have domain shift. We propose a strategy of adversarial contrastive training which enables the model to effectively classify samples of different classes from unseen domains. The model consists of an encoder and a classifier. The encoder is trained in base session but frozen in incremental sessions, whereas the classifier is trained in all sessions. Experiments are done on six pairs of cross-domain datasets. Results show that our method exceeds state-of-the-art methods in average accuracy. The code is at https://github.com/YongjieSi/ACL.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Cross Domain Few-Shot Class-Incremental Audio Classification Via Adversarial Contrastive Learning》所界定。 从摘要看，作者主要围绕 audio classification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that our method exceeds state-of-the-art methods in average accuracy. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio classification。 |

---
### 3. SelectTSL: Prompt-Guided Selective Target Sound Localization in Complex Scenarios

👤 **作者**: Ziyang Jiang, Yu Chen, Zexu Pan, Xinyuan Qian, Bowen Xing, Ivor W. Tsang, Xu-Cheng Yin, Haizhou Li
🔗 **来源**: [https://arxiv.org/abs/2607.02343v1](https://arxiv.org/abs/2607.02343v1)

**摘要**
> Humans can selectively attend to a target sound and estimate its direction in complex scenarios, whereas such selective localization remains challenging for current deep learning-based systems. Sound source localization (SSL) has achieved remarkable success with deep learning, yet most methods localize all active sources without selectivity. Conversely, target sound extraction (TSE) extracts sources using multimodal prompts but typically fails to preserve the multichannel spatial information required for accurate localization. To bridge this gap, we formulate the task of prompt-guided selective target sound localization and propose SelectTSL, an end-to-end architecture that localizes only the user-specified target in multi-source acoustic scenes. Specifically, we design a target-aware selective localization strategy that employs a Prompt-Guided Selective Attention Module (PGSA) to generate prompt-informed embeddings. These embeddings guide an inter-channel phase difference (IPD) enhancer to refine raw phase cues, fusing with target magnitudes to jointly estimate direction of arrival (DoA) and target-source cardinality, i.e., the number of target sound sources. This coupled design effectively focuses on the user-specified target spatial cues for selective localization and also handles time-varying numbers of target sources. Extensive experiments on both synthetic data and real-world recordings demonstrate that our proposed method consistently outperforms other baselines and exhibits robust generalization to real acoustic environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SelectTSL: Prompt-Guided Selective Target Sound Localization in Complex Scenarios》所界定。 从摘要看，作者主要围绕 acoustic scene 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Sound source localization (SSL) has achieved remarkable success with deep learning, yet most methods localize all active sources without selectivity. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic scene。 |

---
### 4. Audio-Based Understanding of Audiobook Narration Appeal

👤 **作者**: Shahar Elisha, Mariano Beguerisse-Díaz, Emmanouil Benetos
🔗 **来源**: [https://arxiv.org/abs/2607.02473v1](https://arxiv.org/abs/2607.02473v1)

**摘要**
> Narration is central to the audiobook listening experience, shaping how listeners engage with and understand the content. This work explores how narration qualities shape an audiobook's appeal, noting that their effects can vary by genre, title, and audience. We extract vocal and acoustic features (e.g., tone, pace, loudness) from LibriVox using pre-trained audio models and analyse their relationship with consumption data (specifically, view-rate) and their interplay with genre and title. Despite limited consumption data, we find that acoustic information alone has a robust association with appeal, even after accounting for title effects. We further validate these findings using more nuanced proprietary engagement metrics. To our knowledge, this is the first systematic computational study linking narration qualities, genre, title, and audiobook consumption, highlighting the potential of data-driven insights to improve audiobook personalisation and narrator casting.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Audio-Based Understanding of Audiobook Narration Appeal》所界定。 从摘要看，作者主要围绕 audio-based、understanding、audiobook 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To our knowledge, this is the first systematic computational study linking narration qualities, genre, title, and audiobook consumption, highlighting the potential of data-driven insights to improve audiobook personalisation and narrator casting. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-based, understanding, audiobook。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
