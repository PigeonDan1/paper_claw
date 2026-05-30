<div align="center">

# 📰 Paper Claw

**2026-05-30**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-05-28 13:01:12 CST → 2026-05-30 12:41:52 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 2 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 Speech LLM 2, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. HoliTok:A Coutinuous Holistic Tokenization with Robust Dual Capabilities of Speech Generation and Understanding

👤 **作者**: Bohan Li, Shi Lian, Hankun Wang, Yiwei Guo, Yu Xi, Zhihan Li, Da Zheng, Colin Zhang, Kai Yu
🔗 **来源**: [https://arxiv.org/abs/2605.29948v1](https://arxiv.org/abs/2605.29948v1)

**摘要**
> Unified speech foundation models require a holistic tokenization space that is both learnable by language models and decodable into high-quality waveforms. Existing speech tokenizers, however, often fail to satisfy these requirements simultaneously, leading to increased architectural complexity and more involved training designs. We propose HoliTok, a continuous Holistic speech Tokenization model designed for unified generation-understanding modeling. HoliTok encodes 48~kHz speech into a compact 25~Hz sequence of 128-dimensional latents. It is trained with a progressive strategy that jointly preserves signal-level fidelity, incorporates semantic information, and maintains strong latent learnability. Based on this tokenization, we build a unified AR+DiT model for speech synthesis and recognition, where the same latent sequence supports both generation-specific and unified generation-understanding tasks. Experiments show that HoliTok achieves competitive reconstruction fidelity, improves generative learnability for high-quality and controllable synthesis, and, among the evaluated representations, is the only one that operates robustly in our unified generation-understanding architecture without additional optimization tricks. These results suggest that HoliTok serves as an effective speech tokenizer and a foundational representation interface for unified spoken language modeling. The code is available at: https://github.com/bovod-sjtu/HoliTok.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《HoliTok:A Coutinuous Holistic Tokenization with Robust Dual Capabilities of Speech Generation and Understanding》所界定。 从摘要看，作者主要围绕 spoken language model、speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that HoliTok achieves competitive reconstruction fidelity, improves generative learnability for high-quality and controllable synthesis, and, among the evaluated representations, is the only one that operates robustly in our unified generation-understanding architecture without additional optimization tricks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken language model, speech synthesis。 |

---
### 2. Audio Jailbreaks in Large Audio-Language Models: Taxonomy, Attack-Defense Analysis, and Cost-Aware Evaluation

👤 **作者**: Bo-Han Feng, Yu-Hsuan Li Liang, Chien-Feng Liu, You-Hsuan Chang, Yun-Nung Chen
🔗 **来源**: [https://arxiv.org/abs/2605.30031v1](https://arxiv.org/abs/2605.30031v1)

**摘要**
> Large Audio Language Models (LALMs) expand jailbreak risks from token-level prompting to the full speech perception-to-reasoning pipeline, where unsafe behavior can be induced through semantics, acoustic style, signal artifacts, or internal representations. Existing work studies these risks under heterogeneous threat models and evaluation protocols, making it difficult to compare attack practicality or defense utility. This paper provides a unified taxonomy and a controlled empirical evaluation of LALM jailbreak attacks and defenses. We organize prior work into semantic, acoustic, signal, and embedding-layer attacks; guard-based, training-free, and training-based defenses; and cross-modal, audio-native, and interactive benchmarks. We then evaluate representative attacks and defenses across ten open-source LALMs, measuring not only attack success rate but also benign refusal and latency. Our results show that Acoustic Best-of-N reveals strong worst-case audio-space vulnerabilities, Narrative Framing is an effective low-latency semantic threat, and current defenses trade robustness against benign usability. These findings support cost- and utility-aware evaluation as a necessary complement to success-rate-only LALM safety benchmarks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Audio Jailbreaks in Large Audio-Language Models: Taxonomy, Attack-Defense Analysis, and Cost-Aware Evaluation》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that Acoustic Best-of-N reveals strong worst-case audio-space vulnerabilities, Narrative Framing is an effective low-latency semantic threat, and current defenses trade robustness against benign usability. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model。 |

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

### 1. It`s All About Speed: AI`s Impact on Workflow in Music Production

👤 **作者**: Finn McClellan, Fabio Morreale
🔗 **来源**: [https://arxiv.org/abs/2605.29931v1](https://arxiv.org/abs/2605.29931v1)

**摘要**
> In this paper, we present the results of an ethnographic study into the impact of AI and automated tools on music production workflow. Focusing specifically on professional participants who identified as recording engineers, mixers, and producers, we discuss their usage of common AI and automated software, as well as their sentiments on the proliferation of these tools. We discuss tensions that may be created between users and automated tools in key areas such as the need for speed and efficiency, controllability, and maintaining creative agency, and how these tensions may be alleviated through tool design.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《It`s All About Speed: AI`s Impact on Workflow in Music Production》所界定。 从摘要看，作者主要围绕 about、speed、impact 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Focusing specifically on professional participants who identified as recording engineers, mixers, and producers, we discuss their usage of common AI and automated software, as well as their sentiments on the proliferation of these tools. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：about, speed, impact。 |

---
### 2. Frequency-Modulated and Single-Tone Excitation to Reveal Vibro-Acoustic Nonlinearities in Loosened Bolted Joints

👤 **作者**: Berkay Kullukcu, Robin Pianowski, Dina Hannebauer
🔗 **来源**: [https://arxiv.org/abs/2605.29950v1](https://arxiv.org/abs/2605.29950v1)

**摘要**
> Preload loss in bolted joints results in alterations of the stiffness, damping, and nonlinearity of the structure, but existing monitoring techniques for rail-vehicle systems are often not capable of combining controlled shaker tests and sensing of nonlinear features. This paper proposes a method for detecting bolt loosening using a vibro-acoustic technique, where the structure is subjected to controlled shaker tests to sense the nonlinear features. A triaxial accelerometer was attached to the demonstrator, a microphone was placed in close proximity, and one of the bolts was tested under 0%, 20%, 40%, and 80% preload conditions. Single-tone and frequency-modulated (FM) signals close to the main natural frequency of 130 Hz, which was identified using sine sweep and narrow-band excitation, were applied to the demonstrator. When the structure was subjected to 130 Hz single-tone excitation, the loose state of the bolt exhibited several additional high-frequency spectral peaks. FM excitation between 125 and 135 Hz further distinguished between the states. Harmonic band power ratios, normalized to the carrier, distinguished between the loose state and the 80% preload state, where the difference between the loose and 80% preload states was 17.5 dB for l = 2 and 36.5 dB for l = 6.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Frequency-Modulated and Single-Tone Excitation to Reveal Vibro-Acoustic Nonlinearities in Loosened Bolted Joints》所界定。 从摘要看，作者主要围绕 frequency-modulated、single-tone、excitation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：A triaxial accelerometer was attached to the demonstrator, a microphone was placed in close proximity, and one of the bolts was tested under 0%, 20%, 40%, and 80% preload conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：frequency-modulated, single-tone, excitation。 |

---
### 3. Benchmarking Single-Factor Physical Video-to-Audio Generation

👤 **作者**: Tingle Li, Siddharth Gururani, Kevin J. Shih, Gantavya Bhatt, Sang-gil Lee, Zhifeng Kong, Arushi Goel, Gopala Anumanchipalli, Ming-Yu Liu
🔗 **来源**: [https://arxiv.org/abs/2605.30339v1](https://arxiv.org/abs/2605.30339v1)

**摘要**
> Generative video-to-audio (V2A) models produce highly plausible soundtracks, but it remains unclear whether they capture the underlying physical processes. Existing evaluations emphasize perceptual realism and overlook physical correctness under controlled interventions. In this paper, we introduce FlatSounds, a benchmark that audits the physical reasoning of V2A models through: 1) controlled counterfactual pairs in which a single physical factor is varied, and 2) single-video pattern tests that probe internal consistency and directional trends. These settings test whether the generated audio correctly reflects specific physical properties and timings. Our evaluation of state-of-the-art models reveals a consistent trade-off: models rely more on text captions than the visual stream to infer physics and semantics. Captions generally improve physical and semantic accuracy, but paradoxically degrade temporal alignment. Our results highlight the need to move beyond audio quality toward learning physical processes directly from pixels. Finally, we find that our physics-based metrics correlate strongly with human preference tests on our own data. Project webpage: https://research.nvidia.com/labs/cosmos-lab/flatsounds/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Benchmarking Single-Factor Physical Video-to-Audio Generation》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our evaluation of state-of-the-art models reveals a consistent trade-off: models rely more on text captions than the visual stream to infer physics and semantics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
