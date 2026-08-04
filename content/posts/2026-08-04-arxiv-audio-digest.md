<div align="center">

# 📰 Paper Claw

**2026-08-04**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-03 12:21:42 CST → 2026-08-04 11:55:42 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 Speech LLM 1, Enhancement 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Can Foundation Models Hear What Made That Sound? A Tiered Benchmark of Audio-Language Models and Traditional Classifiers for Closed-Set Sound Source Identification

👤 **作者**: Sajjad Abdoli, Ghassan Al-Sumaidaee, Ahmad ElShiekh, Ahmed Rashad
🔗 **来源**: [https://arxiv.org/abs/2608.02397v1](https://arxiv.org/abs/2608.02397v1)

**摘要**
> We benchmark eleven audio classification methods: five task-aware closed-set LLMs (four Gemini models plus open-weight Kimi-Audio-7B-Instruct), four fixed-vocabulary taggers (YAMNet, PANNs, Whisper-AT, and SSLAM), a zero-shot audio-text model (CLAP), and an audio-grounded LLM (BAT). We evaluate them on a closed-set sound-source identification task over 2,242 clips spanning 23 fine-grained classes and 11 categories. Since these methods differ fundamentally in how they receive the task and how outputs are scored, we group them into four evaluation tiers rather than one leaderboard, reporting macro Precision, Recall, F1, and false-negative rate per tier. The best model, Gemini-3.1-Pro-Preview, reaches 85.6 percent category-level F1 and 56.7 percent fine-grained F1. Kimi-Audio is competitive for its size, reaching 67.5 percent category-level F1 and 32.9 percent fine-grained F1, but fails to answer 1.6 percent of samples. SSLAM and CLAP match or exceed the best closed-set model at the category level without seeing the candidate list, but fall behind at the fine-grained level. Analyzing the Gemini models' chain-of-thought across 8,968 responses, we find that response length does not predict accuracy, an apparent "holistic judgment beats detailed analysis" effect is better explained as a difficulty confound, and wrong answers are stated confidently 92 to 100 percent of the time. We report full per-class confusion matrices and metrics for all eleven methods, identify the structural error modes behind most of the accuracy loss between granularities, and give practical guidance for choosing among these method families.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Can Foundation Models Hear What Made That Sound? A Tiered Benchmark of Audio-Language Models and Traditional Classifiers for Closed-Set Sound Source Identification》所界定。 从摘要看，作者主要围绕 audio-language model、whisper、audio classification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We evaluate them on a closed-set sound-source identification task over 2,242 clips spanning 23 fine-grained classes and 11 categories. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model, whisper, audio classification。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. Deep Learning-Based Active Trim Panels for Enhanced Aircraft Interior Noise Control

👤 **作者**: Boxiang Wang, Malte Misol, Zhengding Luo, Junwei Ji, Xiaoyi Shen, Dongyuan Shi, Woon-Seng Gan
🔗 **来源**: [https://arxiv.org/abs/2608.02421v1](https://arxiv.org/abs/2608.02421v1)

**摘要**
> Active noise control (ANC) trim panels offer an effective solution to suppress multi-tonal noise in aircraft. The selective fixed-filter ANC (SFANC) method, characterized by low computational complexity, high robustness and rapid response, is suitable to handle multi-tonal engine noise that varies in frequency due to changes in the rotational speed of the engine shaft. However, real-world conditions introduce variations in lining temperature, altering acoustic and structural paths and degrading noise reduction performance. To address this challenge, a temperature-perceptive SFANC (TP-SFANC) approach is proposed that employs a lightweight one-dimensional convolutional neural network (1D CNN) trained using a multi-task learning strategy. By processing both reference and error signals, the 1D CNN learns frequency and temperature characteristics to dynamically select the optimal control filter. Numerical simulations demonstrate the effectiveness of the proposed method in attenuating multi-tonal noise across varying frequencies and lining temperatures.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Deep Learning-Based Active Trim Panels for Enhanced Aircraft Interior Noise Control》所界定。 从摘要看，作者主要围绕 noise reduction 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Numerical simulations demonstrate the effectiveness of the proposed method in attenuating multi-tonal noise across varying frequencies and lining temperatures. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：noise reduction。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. MEMS Microphones as Ultrasonic Transducers: Nonlinear Electrostatic Actuation and a Parametric Array Prototype

👤 **作者**: Xiaoyu Niu, Zihuan Liu, Ehsan Vatankhah, Yuqi Meng, Neal A. Hall
🔗 **来源**: [https://arxiv.org/abs/2608.02203v1](https://arxiv.org/abs/2608.02203v1)

**摘要**
> This paper investigates commercial-style capacitive MEMS microphone dies as air-coupled ultrasonic transmitters under nonlinear pull-in and snap-back actuation and demonstrates a compact parametric-array prototype. A single die produces large diaphragm displacement and measurable ultrasonic pressure in air. A 28-die array driven at 83 and 93 kHz generates a directional component at the 10 kHz difference frequency. Measurements are compared with analytical radiation theory and finite-element modeling, and the effects of aperture, fill factor, device uniformity, and receiver nonlinearity are discussed.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MEMS Microphones as Ultrasonic Transducers: Nonlinear Electrostatic Actuation and a Parametric Array Prototype》所界定。 从摘要看，作者主要围绕 mems、microphones、ultrasonic 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper investigates commercial-style capacitive MEMS microphone dies as air-coupled ultrasonic transmitters under nonlinear pull-in and snap-back actuation and demonstrates a compact parametric-array prototype. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：mems, microphones, ultrasonic。 |

---
### 2. Sounding Canvas: Embedding Algorithms in Networked, Sensorial Sound Art

👤 **作者**: Luciano Ciamarone, Dora Motèque, Marco Giordano
🔗 **来源**: [https://arxiv.org/abs/2608.02219v1](https://arxiv.org/abs/2608.02219v1)

**摘要**
> Sounding Canvas turns painting into a touch-responsive multimodal installation by embedding capacitive sensors, real-time decision models, and networking inside the canvas. Touches trigger spatialised sounds that appear to emanate from the painting itself. The work embeds algorithms physically, as sensing and computation concealed behind the artwork; perceptually, through an offline visual-to-sonic mapping that aligns a painting's features with sound descriptors; and performatively, through online models that shape live interaction with visitors and with remote canvases over a network. We describe the artistic rationale and technical implementation, combining a CNN-based offline mapping that defines the sound vocabulary with two online event managers, a higher-order Markov model and an LSTM-based policy, that balance responsiveness with guided exploration. We discuss how these layers make algorithms perceptible through behaviour rather than code, how networking transforms solitary touch into distributed co-authorship, and how the system raises questions of authorship, agency, and evaluation in embedded algorithmic artworks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Sounding Canvas: Embedding Algorithms in Networked, Sensorial Sound Art》所界定。 从摘要看，作者主要围绕 sounding、canvas、embedding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Touches trigger spatialised sounds that appear to emanate from the painting itself. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sounding, canvas, embedding。 |

---
### 3. An End-to-End Workflow for Fin Whale Song Detection, Note Characterization, and Localization with Distributed Acoustic Sensing

👤 **作者**: Dídac Diego-Tortosa, Miriam Romagosa, Arantza Ugalde, Hugo Latorre, Sergi Ventosa, Jose Enrique García, Antonio Villaseñor
🔗 **来源**: [https://arxiv.org/abs/2608.02387v1](https://arxiv.org/abs/2608.02387v1)

**摘要**
> Submarine fiber-optic cables instrumented with distributed acoustic sensing (DAS) provide an effective approach for large-scale monitoring of fin whales. We present an end-to-end workflow for detecting, characterizing, and localizing fin whale notes, tested on two submarine telecom cables in the Strait of Gibraltar and western Alboran Sea. The workflow applies a kurtosis-value picker adapted to narrow-band fin whale notes. Channel-wise detections are grouped into individual notes using density-based spatio-temporal clustering, cluster agglomeration, and hyperbolic fitting to reject incoherent picks. The retained clusters are characterized through temporal, spectral, and energy-related descriptors that support note-type discrimination and estimation of inter-note intervals. Relative arrival times across DAS channels are then used in a grid-search procedure to estimate candidate source locations. Evaluation against manually annotated detections from six fin whale songs yielded median pick-level precision of 0.990 and recall of 0.744, and median cluster-level precision of 0.880 and recall of 0.806. Representative applications demonstrate separation of overlapping vocalizations, characterization of type-A and type-B notes, and the inference of apparent source movement. By transforming dense DAS recordings into compact note-level bioacoustic information, the workflow provides an integrated framework for fin whale monitoring and a basis for adaptation to other synchronized acoustic receiver arrays.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《An End-to-End Workflow for Fin Whale Song Detection, Note Characterization, and Localization with Distributed Acoustic Sensing》所界定。 从摘要看，作者主要围绕 end-to-end、workflow、whale 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Representative applications demonstrate separation of overlapping vocalizations, characterization of type-A and type-B notes, and the inference of apparent source movement. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：end-to-end, workflow, whale。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
