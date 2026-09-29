<div align="center">

# 📰 Paper Claw

**2026-09-29**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-28 14:00:05 CST → 2026-09-29 14:18:45 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 6 篇新论文，主要分布在 Speech LLM 1, ASR 1, TTS 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Probing Large Audio-Language Models for Compositional Understanding of Sounding Actions

👤 **作者**: Michel Olvera, Paraskevas Stamatiadis, Changhong Wang, Ga{ë}l Richard
🔗 **来源**: [https://arxiv.org/abs/2609.35345v1](https://arxiv.org/abs/2609.35345v1)

**摘要**
> Large audio-language models (LALMs) excel at understanding and reasoning tasks over atomic sound events, yet their ability to infer higher-level human activities from such fine-grained events remains largely unexamined. Everyday human actions and activities, such as setting a table, cleaning the house, or preparing a breakfast emerge compositionally from temporally distributed sound events, requiring abstraction beyond the event-centric granularity that dominates current training and evaluation paradigms. Our benchmark evaluates a wide set of LALMs under a principled framework that tests how language-based reasoning, grounded in acoustic perception, structures sound abstractions into higher-level understanding. By systematically varying exemplar typicality and distractor similarity, our evaluation exposes \added{that current models do not reliably perform compositional inference from atomic acoustic events to higher-level human activities solely from audio.} All data, taxonomies, and evaluation scripts are publicly available on our companion website: https://alm-sounding-actions.onrender.com/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Probing Large Audio-Language Models for Compositional Understanding of Sounding Actions》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Everyday human actions and activities, such as setting a table, cleaning the house, or preparing a breakfast emerge compositionally from temporally distributed sound events, requiring abstraction beyond the event-centric granularity that dominates current training and evaluation paradigms. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model。 |

---
## 🏷️ ASR

### 1. CoSE-E: A Benchmark for Code-switched Speech Evaluation in Enterprise Settings

👤 **作者**: Shama Gupta, Hoang H Nguyen, Chelsea Huang, Lindsay Devon Brin, Fanny Riols
🔗 **来源**: [https://arxiv.org/abs/2609.35645v1](https://arxiv.org/abs/2609.35645v1)

**摘要**
> Code-switching (CS), a seamless alternation between languages within a single utterance, remains a critical challenge in automatic speech recognition (ASR). While prior works focus on conversational CS-ASR, enterprise settings demand evaluation of operational impact beyond edit-distance errors: how code-switching transcription errors propagate to downstream voice agent task failures. In this work, we propose (1) a CS-ASR synthetic benchmark and multidimensional evaluation framework tailored to enterprise domains, (2) systematic evaluation of frontier ASR systems across 5 language pairs, (3) diagnostic analysis of the additional transcription errors that code-switching introduces across language pairs and models. We release COSE-E to support enterprise-focused CSASR evaluation for multilingual voice agents in enterprise deployment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《CoSE-E: A Benchmark for Code-switched Speech Evaluation in Enterprise Settings》所界定。 从摘要看，作者主要围绕 automatic speech recognition、asr system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While prior works focus on conversational CS-ASR, enterprise settings demand evaluation of operational impact beyond edit-distance errors: how code-switching transcription errors propagate to downstream voice agent task failures. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automatic speech recognition, asr system。 |

---
## 🏷️ TTS

### 1. GLAD: Global-Local Adaptive Detector for Robust Speech Deepfake Detection

👤 **作者**: Zelin Zhao, Guanjie Huang, Danny Hin Kwok Tsang, Li Liu
🔗 **来源**: [https://arxiv.org/abs/2609.35411v1](https://arxiv.org/abs/2609.35411v1)

**摘要**
> Recent advances in AI-based speech synthesis have enabled highly realistic speech, increasing the importance of speech deepfake detection (SDD) in preventing misuse. While mainstream Self-Supervised Learning (SSL)-based detectors achieve strong performance, they suffer from poor generalization to unseen domains and often overlook fine-grained signal artifacts due to a bias towards global semantic consistency. In this paper, we conduct the first detailed empirical and visual analysis to validate these limitations explicitly. Our investigation reveals two critical architectural vulnerabilities: (1) a systemic failure to capture localized spoofing traces, and (2) a severe lack of adaptability to domain-driven shifts in SSL layer importance, rendering static aggregation strategies prone to overfitting. To address these vulnerabilities, we propose the Global-Local Adaptive Detector (GLAD). Specifically, to capture localized forgeries, GLAD employs a Hierarchical Global-Local (HGL) backbone that explicitly bridges the granularity gap by fusing global linguistic and acoustic features with fine-grained local signal details. To counter layer importance shifts in out-of-distribution (OOD) scenarios, we introduce a Hierarchical Adaptive Gating (HAG) mechanism that dynamically recalibrates layer-wise focus in a sample-specific manner. Finally, to address shortcut learning induced by environmental biases, we introduce SaniBoost, a composite data augmentation strategy for robust signal standardization and noise sanitization. Extensive experiments demonstrate that GLAD significantly outperforms state-of-the-art methods, particularly on unseen domain cases.The code will be released upon publication.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《GLAD: Global-Local Adaptive Detector for Robust Speech Deepfake Detection》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While mainstream Self-Supervised Learning (SSL)-based detectors achieve strong performance, they suffer from poor generalization to unseen domains and often overlook fine-grained signal artifacts due to a bias towards global semantic consistency. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

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

### 1. Simulation-Based Inference for Plate Reverb System Identification

👤 **作者**: Dylan Sechet, Marc Evrard, Matthieu Kowalski
🔗 **来源**: [https://arxiv.org/abs/2609.35295v1](https://arxiv.org/abs/2609.35295v1)

**摘要**
> We address Task A of the 1st DAFx Parameter Estimation Challenge, which aims to retrieve the physical parameters of a plate model from an impulse response. To do so, we use the Simulation-Based Inference (SBI) framework, in which we train a neural network to estimate a density over plate parameters given an impulse response, using a dataset generated by the simulator. Inference for a new impulse response then requires only a forward pass through the network, without involving the simulator. For each test observation, we fine-tune a specific network: additional simulation rounds are performed by sampling parameters from the current estimated distribution, simulating the corresponding impulse responses, and fine-tuning to produce the specialized network.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Simulation-Based Inference for Plate Reverb System Identification》所界定。 从摘要看，作者主要围绕 simulation-based、inference、plate 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To do so, we use the Simulation-Based Inference (SBI) framework, in which we train a neural network to estimate a density over plate parameters given an impulse response, using a dataset generated by the simulator. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：simulation-based, inference, plate。 |

---
### 2. Multimodal Target Speaker Extraction: Towards Unified Speaker Cues Across Modalities

👤 **作者**: Xinyuan Qian, Yanghao Zhou, Ziyang Jiang, Yu Chen, Xinjia Zhu, Xueyan Chen, Qiquan Zhang, Zexu Pan, Jiaying Wang, Xianghu Yue, Jiadong Wang, Björn Schuller, Haizhou Li
🔗 **来源**: [https://arxiv.org/abs/2609.35613v1](https://arxiv.org/abs/2609.35613v1)

**摘要**
> Target Speaker Extraction (TSE) is pivotal in speech communication and human-computer interaction, enabling the isolation of a specific speaker's voice from complex acoustic environments, i.e., the cocktail party scenario. Although traditional TSE systems conditioned on enrollment speech have progressed substantially, enrollment speech as a cue has inherent limitations. Its reliability degrades when the target and interfering speakers have similar voice characteristics, when intra-speaker variability (e.g. changes in emotion or speaking style) creates a mismatch between the enrollment and target speech, or when the enrollment itself is contaminated by noise or competing speakers. This review surveys deep-learning-based TSE from the perspective of auxiliary target cues drawn from multiple modalities. We organize existing methods according to five types of information used to isolate the target speaker: audio enrollment, visual, spatial, textual/semantic, and neural cues. We also trace the evolution from discriminative estimators to variational, diffusion, flow, codec, and foundation-model-based systems and summarize representative datasets and evaluation metrics. We review the benefits and limitations of different cues and discuss challenges involving synchronization, missing or unreliable observations, data scarcity, privacy, computational cost, and real-time operation. Finally, we summarize future directions concerning adaptive cue fusion, instruction-driven extraction, realistic evaluation, and trustworthy deployment. By jointly reviewing cue design, model architecture, training objectives, datasets, and evaluation metrics, this article provides an overview of the current landscape and open problems in multimodal TSE.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Multimodal Target Speaker Extraction: Towards Unified Speaker Cues Across Modalities》所界定。 从摘要看，作者主要围绕 multimodal、target、speaker 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Although traditional TSE systems conditioned on enrollment speech have progressed substantially, enrollment speech as a cue has inherent limitations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：multimodal, target, speaker。 |

---
### 3. Retrieving Individual Stems from Music Mixtures with Slot Embeddings

👤 **作者**: David Braun, Junyi Fan, Pranay Manocha, Donald S. Williamson, Adam Finkelstein
🔗 **来源**: [https://arxiv.org/abs/2609.35672v1](https://arxiv.org/abs/2609.35672v1)

**摘要**
> Music producers search libraries of isolated instrument recordings, called stems, for sounds resembling parts of an existing song. Neural retrieval systems address this by mapping audio to embeddings and ranking library stems by their similarity to the query. The leading method, Contrastive Instrument Retrieval (CIR), encodes the mixture as a single embedding, but it works best when a user specifies the target's instrument family. We introduce Stembed, which encodes a mixture as several slot embeddings representing candidate stems. During training, we construct mixtures from stems of the same song and match their slot embeddings to those of the isolated stems. The slot embeddings from mixtures inherit the stem identities of their assigned solo embedding, enabling a contrastive loss. On mixtures from held out MoisesDB artists, Stembed outperforms a CIR-style baseline when both search the full stem library. Even when predicting the stem count itself without family labels, Stembed exceeds the baseline's family-filtered R@1. Our website demonstrates how users can select a slot by inspecting the tags of its retrieved stems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Retrieving Individual Stems from Music Mixtures with Slot Embeddings》所界定。 从摘要看，作者主要围绕 retrieving、individual、stems 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On mixtures from held out MoisesDB artists, Stembed outperforms a CIR-style baseline when both search the full stem library. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：retrieving, individual, stems。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
