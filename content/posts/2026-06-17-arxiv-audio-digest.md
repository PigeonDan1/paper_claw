<div align="center">

# 📰 Paper Claw

**2026-06-17**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-16 14:19:18 CST → 2026-06-17 13:54:42 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, TTS 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Grounding Spoken LLMs in Multi-Speaker Audio via Diarization Conditioning

👤 **作者**: Alexander Polok, Samuele Cornell, Sathvik Udupa, Jan Černocký, Shinji Watanabe, Lukáš Burget
🔗 **来源**: [https://arxiv.org/abs/2606.18134v1](https://arxiv.org/abs/2606.18134v1)

**摘要**
> We propose diarization-conditioned spoken language models (SLMs), a strategy for extending SLMs to far-field multi-talker audio. Rather than adapting the decoder via Serialized Output Training, which risks catastrophic forgetting, we condition the acoustic encoder on diarization masks to extract target-speaker representations, keeping the decoder frozen. We instantiate this as Dixtral, integrating a Diarization Conditioned Whisper (DiCoW) encoder into the Voxtral SLM. On AMI, NOTSOFAR-1, LibriSpeechMix, and Mixer6, Dixtral outperforms Gemini 3.0 Flash, VibeVoice, and Voxtral Mini Transcribe V2 on speaker-attributed transcription by 29.0%, 19.8%, and 16.0% absolute cpWER respectively. On a novel long-form multi-speaker QA benchmark, zero-shot Dixtral matches Gemini on far-field content understanding, and when fine-tuned surpasses both Gemini and Voxtral operating on close-talk across all tasks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Grounding Spoken LLMs in Multi-Speaker Audio via Diarization Conditioning》所界定。 从摘要看，作者主要围绕 spoken language model、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On AMI, NOTSOFAR-1, LibriSpeechMix, and Mixer6, Dixtral outperforms Gemini 3.0 Flash, VibeVoice, and Voxtral Mini Transcribe V2 on speaker-attributed transcription by 29.0%, 19.8%, and 16.0% absolute cpWER respectively. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：spoken language model, whisper。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

### 1. One-Step Token-to-Waveform Generation with MeanFlow in Latent Space

👤 **作者**: Zheqi Dai, Guangyan Zhang, Zhen Ye, Jingyu Li, Haolin He, Chunyat Wu, Yiwen Guo, Qiuqiang Kong
🔗 **来源**: [https://arxiv.org/abs/2606.18072v1](https://arxiv.org/abs/2606.18072v1)

**摘要**
> Neural audio codecs are central to modern LLM-based Text-to-Speech (TTS) and multimodal systems. As low-bitrate semantic codecs gain prominence, the Token-to-Waveform (Token2Wav) decoder becomes a bottleneck determining both perceptual quality and system efficiency. Conventional multi-step flow-matching decoders offer superior quality but suffer from high inference latency due to iterative sampling, creating a severe quality-speed trade-off. In this paper, we propose a novel Token2Wav architecture that overcomes this limitation by applying MeanFlow in a highly compressed latent space. By modeling the average velocity rather than the instantaneous velocity field, MeanFlow enables true one-step generation. Operating in the latent domain mitigates the memory and stability issues of waveform-level flows, yielding up to a 17$\times$ improvement in Real-Time Factor (RTF) compared to multi-step baselines with negligible quality degradation. Furthermore, we introduce refinement strategies that mitigate latent mismatch, including decoder-only fine-tuning with the MeanFlow generator frozen and end-to-end joint fine-tuning, improving fidelity without increasing inference-time cost. Code and demo are publicly available.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《One-Step Token-to-Waveform Generation with MeanFlow in Latent Space》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Operating in the latent domain mitigates the memory and stability issues of waveform-level flows, yielding up to a 17$\times$ improvement in Real-Time Factor (RTF) compared to multi-step baselines with negligible quality degradation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

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

### 1. Reading between the Lines: Leveraging Large Language Models for Global Dementia and Depression Assessment from Clinical Interviews

👤 **作者**: Franziska Braun, Alea Rüggeberg, Thomas Ranzenberger, Hartmut Lehfeld, Thomas Hillemacher, Tobias Bocklet, Korbinian Riedhammer
🔗 **来源**: [https://arxiv.org/abs/2606.18019v1](https://arxiv.org/abs/2606.18019v1)

**摘要**
> Dementia and depression are the most prevalent neuropsychiatric disorders in geriatric populations, and their overlapping symptoms pose major challenges for differential diagnosis. In this study, we investigate open-weights Large Language Models (LLMs) for predicting dementia and depression severity from speech samples collected during standardized history taking interviews with 154 German-speaking subjects. We introduce an observer-based Global Depression Scale (GDS-D) aligned with the established Global Deterioration Scale (GDS), enabling parallel global staging of affective and cognitive symptoms. We compare three LLMs (Mistral 3.1, DeepHermes, Qwen3) in two settings: (1) zero-shot prediction and (2) LLM-based feature extraction for Support Vector Regression, using human and pause-enriched transcripts. Results show that LLMs effectively predict depression severity in zero-shot settings (best MAE of 0.60), while dementia assessment benefits substantially from structured feature extraction (best MAE of 0.78), reducing errors by up to 35% over zero-shot baselines. Pause-enriched transcripts achieve competitive performance with human transcriptions, demonstrating the viability of fully automatic screening pipelines for differential neuropsychiatric assessment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Reading between the Lines: Leveraging Large Language Models for Global Dementia and Depression Assessment from Clinical Interviews》所界定。 从摘要看，作者主要围绕 reading、between、lines 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that LLMs effectively predict depression severity in zero-shot settings (best MAE of 0.60), while dementia assessment benefits substantially from structured feature extraction (best MAE of 0.78), reducing errors by up to 35% over zero-shot baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：reading, between, lines。 |

---
### 2. AI-based Cognitive-linguistic Features for Dementia Assessment in Picture Description

👤 **作者**: Lingfeng Xu, Prad Kadambi, Samuel Goldinger, Visar Berisha, Kimberly D. Mueller, Julie Liss
🔗 **来源**: [https://arxiv.org/abs/2606.18054v1](https://arxiv.org/abs/2606.18054v1)

**摘要**
> Picture descriptions provide valuable insights into several clinical constructs related to cognitive-linguistic abilities. However, operationalizing these constructs into quantitative measures remains challenging, limiting interpretability and clinical utility. We introduced seven constructs tailored to the Cookie Theft picture description task and prompted large language models (LLMs) to evaluate them, generating severity scores and example-based explanations. Among the examined LLMs, Claude 3.5 Sonnet performed the best, producing severity scores that significantly distinguish cognitively impaired individuals from healthy controls. The model achieves a high accuracy of 85% on the ADReSS dataset. Expert evaluation of Claude's scores and explanations yields a 3.99/5 average agreement. The findings demonstrate the potential of LLMs to operationalize clinical constructs and generate interpretable evaluations, offering a promising approach for accessible cognitive screening tools.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AI-based Cognitive-linguistic Features for Dementia Assessment in Picture Description》所界定。 从摘要看，作者主要围绕 ai-based、cognitive-linguistic、features 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The model achieves a high accuracy of 85% on the ADReSS dataset. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：ai-based, cognitive-linguistic, features。 |

---
### 3. Next-Turn: Duration-Aware Streaming Endpoint Detection via Time-to-Next-Speech-Onset Prediction

👤 **作者**: Tristan Tsoi, Jiajun Deng, Yingke Zhu, Huu Quyen Dang, Tianxiang Cao, Nikita Kuzmin, Tao Zhong, Simon Lui
🔗 **来源**: [https://arxiv.org/abs/2606.18094v1](https://arxiv.org/abs/2606.18094v1)

**摘要**
> Endpoint detection (EPD) is essential for natural turn-taking in streaming speech systems. However, reliably determining the endpoint of an utterance is challenging because speakers often pause mid-utterance due to hesitations and disfluencies. Semantic EPD has emerged as a promising direction to address this issue but is hindered by ambiguous supervision and strict streaming constraints. We propose Next-Turn that uses the time-to-next-speech-onset as the training objective, where targets are derived directly from speech timestamps and require no additional annotation. Experiments show that the proposed method outperforms conventional acoustic and recent semantic EPD baselines, achieving a 25.9% absolute improvement in endpoint accuracy within 320 ms over the strongest baseline. In addition, joint training with the duration-aware objective complements standard binary EPD, with gains that increase monotonically with increasing pauses.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Next-Turn: Duration-Aware Streaming Endpoint Detection via Time-to-Next-Speech-Onset Prediction》所界定。 从摘要看，作者主要围绕 next-turn、duration-aware、streaming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that the proposed method outperforms conventional acoustic and recent semantic EPD baselines, achieving a 25.9% absolute improvement in endpoint accuracy within 320 ms over the strongest baseline. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：next-turn, duration-aware, streaming。 |

---
### 4. Embedded Machine Learning for Microcontroller-Class Edge Devices: Data, Feature, Evaluation, and Deployment Pipelines

👤 **作者**: Mostafa Darvishi
🔗 **来源**: [https://arxiv.org/abs/2606.18122v1](https://arxiv.org/abs/2606.18122v1)

**摘要**
> Embedded machine learning moves inference from cloud services to resource-constrained devices that must acquire data, preprocess signals, run a model, and act within tight limits on memory, energy, and latency. This paper presents a systems-oriented synthesis of an embedded machine-learning workflow for microcontroller-class platforms. The emphasis is placed on engineering decisions that are often hidden in generic machine-learning introductions: sampling and buffering, feature extraction as dimensionality reduction, validation under class imbalance, model/runtime co-design, and streaming deployment. Two representative signal families are used throughout the paper. The first is inertial motion recognition, where a two-second, three-axis accelerometer window is transformed from raw samples into root-mean-square and spectral features before classification. The second is keyword spotting, where audio is sampled, anti-aliased, transformed into mel-frequency cepstral coefficients, and processed by a compact one-dimensional convolutional network. The paper concludes with practical design rules for robust on-device inference, including data curation, quantization, thresholding, scheduling, and field monitoring.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Embedded Machine Learning for Microcontroller-Class Edge Devices: Data, Feature, Evaluation, and Deployment Pipelines》所界定。 从摘要看，作者主要围绕 embedded、machine、learning 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper presents a systems-oriented synthesis of an embedded machine-learning workflow for microcontroller-class platforms. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：embedded, machine, learning。 |

---
### 5. Descriptor: Certus Caliber Classification Gunshot Dataset (C3GD)

👤 **作者**: Sinclair Gurny, Ryan Quinn
🔗 **来源**: [https://arxiv.org/abs/2606.18135v1](https://arxiv.org/abs/2606.18135v1)

**摘要**
> In this work, we introduce the Certus Caliber Classification Gunshot Dataset (C3GD), a publicly accessible data set developed for the analysis of firearm muzzle blast sounds. The dataset aims to provide a wide variety of firearms, calibers, cartridges, microphones, and microphone locations with metadata detailed beyond what is currently otherwise available. It comprises more than 8000 field-collected data points from 28 firearms across 16 calibers. Because data collection in the field is costly, much of the existing research has been done using gunshot audio collected from the internet, which increases the risk of low-quality data and label noise. This dataset is primarily focused on caliber classification, but can also be used for gunshot detection, audio separation, and audio signal processing, providing a diversified and real-world reference. The dataset aims to provide enough diversity to be able to generalize to more real-world applications while also providing enough metadata for detailed academic analysis.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Descriptor: Certus Caliber Classification Gunshot Dataset (C3GD)》所界定。 从摘要看，作者主要围绕 descriptor、certus、caliber 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The dataset aims to provide a wide variety of firearms, calibers, cartridges, microphones, and microphone locations with metadata detailed beyond what is currently otherwise available. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：descriptor, certus, caliber。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
