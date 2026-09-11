<div align="center">

# 📰 Paper Claw

**2026-09-11**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-10 13:23:06 CST → 2026-09-11 13:20:57 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 2 篇
- **TTS**: 4 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 7 篇新论文，主要分布在 ASR 2, TTS 4, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Whisper-Based Speech Transcription from Videos Across Multiple Languages for Cross-Cultural Understanding

👤 **作者**: Michael Picheny
🔗 **来源**: [https://arxiv.org/abs/2609.11772v1](https://arxiv.org/abs/2609.11772v1)

**摘要**
> Cross-cultural understanding has become increasingly important in today's highly connected, cross-national world. The success of LLM-based technologies is now driving the development of automated tools to aid understanding for nonnative people trying to succeed in cross-cultural environments. Building such automated tools is often done by leveraging in-thewild text, audio, and video data. This paper presents techniques for improving speech recognition-based transcript creation in multiple languages from videos to better train these automated tools. The focus is on processes and speech tools that can easily be used by cross-cultural tool builders without requiring deep speech processing expertise. Using publicly available videos from YouTube and Whisper-based tools, average transcription error rate across seven languages (Spanish, Japanese, Korean, Mandarin, Turkish, Russian, and Hebrew) of 30% are observed. With a modest amount of fine-tuning data, the average error rate can be reduced to 20% making such output much more usable for downstream processing. Speech and metadata associated with these videos that can be used by the community to further refine these experiments are released as well.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Whisper-Based Speech Transcription from Videos Across Multiple Languages for Cross-Cultural Understanding》所界定。 从摘要看，作者主要围绕 speech transcription、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper presents techniques for improving speech recognition-based transcript creation in multiple languages from videos to better train these automated tools. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech transcription, whisper。 |

---
### 2. RetroThinker: Enabling Retrospective Thinking in Speech LLMs

👤 **作者**: Yi-Jen Shih, Puyuan Peng, Abdelrahman Mohamed, David Harwath
🔗 **来源**: [https://arxiv.org/abs/2609.11864v1](https://arxiv.org/abs/2609.11864v1)

**摘要**
> Speech large language models (SpeechLLMs) offer reduced latency and retain paralinguistic nuances that are typically lost in cascaded automatic speech recognition (ASR) and text-based LM architectures. However, they continue to lag behind text-only LLMs on complex reasoning tasks, while real-time spoken interaction imposes strict latency constraints. Although prior works employ Chain-of-Thought (CoT) and concurrent reasoning to enhance reasoning capabilities without inducing prohibitive delays, an inherent accuracy-latency trade-off persists. In this paper, we investigate whether a streaming SpeechLLM can dynamically revise its reasoning traces on the fly. We introduce RetroThinker, a multi-stage post-training framework that equips the Moshi model to self-verify and forward-correct CoT steps during inference. RetroThinker combines supervised fine-tuning (SFT) on curated retrospective thinking data with length-based direct preference optimization (DPO) to optimize retrospective during early reasoning (i.e., reasoning concurrently while the user speaks). Evaluated on the GSM8K benchmark, RetroThinker significantly improves the accuracy-latency trade-off over non-retrospective baselines, achieving an 11% absolute accuracy gain at a comparable latency.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《RetroThinker: Enabling Retrospective Thinking in Speech LLMs》所界定。 从摘要看，作者主要围绕 speech llm、automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluated on the GSM8K benchmark, RetroThinker significantly improves the accuracy-latency trade-off over non-retrospective baselines, achieving an 11% absolute accuracy gain at a comparable latency. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech llm, automatic speech recognition。 |

---
## 🏷️ TTS

### 1. Post-Training Zero-Shot TTS for Fine-Grained Emotion and Duration Control via Natural Language

👤 **作者**: Lianru Gao, Yujie Guo, Yong Qin
🔗 **来源**: [https://arxiv.org/abs/2609.11523v1](https://arxiv.org/abs/2609.11523v1)

**摘要**
> Audiobook narration, conversational agents, and audiovisual dubbing require speech that conveys changing emotions and adapts its pacing within a single utterance. But most existing TTS systems typically rely on utterance-level style conditioning, making such fine-grained control difficult to achieve. In light of this, and inspired by the success of post-training in large language models, we propose a unified post-training framework that equips pretrained text-to-speech models with natural-language control over segment-level emotion and duration. Supervised fine-tuning establishes instruction-conditioned speech generation, while reinforcement learning with group relative policy optimization refines control accuracy using emotion and duration rewards alongside content and speaker preservation objectives. By reusing the pretrained architecture, our approach avoids additional inference-time control modules. Experiments demonstrate significantly improved fine-grained controllability while maintaining speech intelligibility and speaker identity, highlighting post-training as a practical approach to extending existing speech synthesis models.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Post-Training Zero-Shot TTS for Fine-Grained Emotion and Duration Control via Natural Language》所界定。 从摘要看，作者主要围绕 text-to-speech、tts system、speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：But most existing TTS systems typically rely on utterance-level style conditioning, making such fine-grained control difficult to achieve. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, tts system, speech synthesis。 |

---
### 2. Complex-Text Robustness Evaluation and Failure Diagnosis for Low-Resource Multilingual Text-to-Speech

👤 **作者**: Tianlun Zuo, Ziyu Zhang, Tingzhi Mao, Zhonghua Fu, Lei Xie
🔗 **来源**: [https://arxiv.org/abs/2609.11545v1](https://arxiv.org/abs/2609.11545v1)

**摘要**
> Low-resource multilingual text-to-speech (TTS) systems have expanded language coverage, but their robustness under complex text inputs remains insufficiently diagnosed. Existing evaluations mainly focus on naturalness, speaker similarity, and content consistency using regular test sentences, while providing limited insight into how multilingual TTS systems fail when handling challenging inputs such as numbers, dates, named entities, long sentences, code-switched expressions, and punctuation-related structures. This paper proposes a complex-text robustness diagnosis framework for low-resource multilingual TTS. We evaluate robustness from three dimensions: content consistency, language consistency, and generation stability. A multilingual robustness testing scheme is designed for Thai, Vietnamese, Swahili, and Indonesian, covering ordinary sentences and multiple types of complex text inputs. We further introduce automatic diagnostic metrics, including character error rate, language identification accuracy, and duration abnormal rate. To support input-level risk analysis before speech generation, we propose a lightweight Text Risk Score (TRS), which estimates synthesis risk from interpretable text features without manual annotation or model training. Experiments on three representative multilingual TTS systems, including OmniVoice, VoxCPM2, and MMS-TTS, show that complex text inputs expose systematic failure patterns that are not fully reflected by ordinary short-sentence evaluation. Different systems exhibit distinct vulnerabilities in number normalization, named entity handling, long-text generation, and code-switched input processing. Furthermore, TRS shows a positive correlation with content errors and duration abnormalities, demonstrating its usefulness as a low-cost pre-synthesis indicator for complex-text risk diagnosis in low-resource multilingual TTS.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Complex-Text Robustness Evaluation and Failure Diagnosis for Low-Resource Multilingual Text-to-Speech》所界定。 从摘要看，作者主要围绕 text-to-speech、tts system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on three representative multilingual TTS systems, including OmniVoice, VoxCPM2, and MMS-TTS, show that complex text inputs expose systematic failure patterns that are not fully reflected by ordinary short-sentence evaluation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, tts system。 |

---
### 3. Continuous-Time Acoustic Modelling with Neural Controlled Differential Equations

👤 **作者**: Mattias Cross, Minghui Zhao, Anton Ragni
🔗 **来源**: [https://arxiv.org/abs/2609.11725v1](https://arxiv.org/abs/2609.11725v1)

**摘要**
> Text-to-speech (TTS) models commonly address text--speech alignment by expanding phone-level encoder states to frame-level decoder inputs using predicted durations. While this length-regulation step resolves alignment structurally, this use of duration typically changes only where and how often latent states appear, not the values of the states themselves. This paper proposes a continuous-time mechanism for duration-aware acoustic modelling in TTS using neural controlled differential equations (CDEs). We formulate the phone representation as a temporally parameterised control path and use a neural acoustic vector field to produce a continuous-time hidden state whose values evolve with phonetic content and duration-derived timing. The resulting trajectory can be sampled at discrete points and integrated into a standard acoustic decoder pipeline. Objective results contrast CDEs and typical recurrent models. Subjective results suggest that CDE-based models evaluating one phone per step can improve rank-order agreement between synthesised and reference emotion intensity while maintaining comparable emotion-expression quality to a strong baseline. Additional experiments with half-phone step-sizes suggest that temporal resolution changes the trade-off between style tracking and absolute calibration. These results position CDEs as a promising design space for continuous-time and duration-aware style-sensitive TTS.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Continuous-Time Acoustic Modelling with Neural Controlled Differential Equations》所界定。 从摘要看，作者主要围绕 text-to-speech、acoustic model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Subjective results suggest that CDE-based models evaluating one phone per step can improve rank-order agreement between synthesised and reference emotion intensity while maintaining comparable emotion-expression quality to a strong baseline. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, acoustic model。 |

---
### 4. Not All Attacks Are Learned Equally in Speech Deepfake Detection

👤 **作者**: Avantika Singh, Aurosweta Mahapatra, Ismail Rasim Ulgen, Nicholas Andrews, Kong Aik Lee, Berrak Sisman
🔗 **来源**: [https://arxiv.org/abs/2609.11763v1](https://arxiv.org/abs/2609.11763v1)

**摘要**
> Speech deepfake detection (SDD) models are trained on multi-attack datasets containing diverse spoofing systems, such as text-to-speech (TTS) and voice conversion (VC). In standard classifier training on multi-attack datasets, all attacks are treated as one spoofed class, and performance is reported using overall Equal Error Rate (EER). This aggregate view obscures how individual attacks shape learning and generalization. To better understand this attack-level behavior, we first balance TTS and VC exposure using sample and attack omission. We then measure attack-wise EER at inference and analyze attack-wise training loss and predictive entropy to characterize optimization. Results show that attacks contribute unequally: some attacks have high EER sensitivity and concentrated entropy with low loss, indicating strong influence on the decision boundary. We define these as high-impact attacks. To reduce uneven generalization across attacks, we propose a replay-regularized, attack-aware curriculum that steps exposure based on measured attack influence. Experiments on ASVspoof 2019, 2021, ASVspoof 5, and Fake-or-Real show improved overall robustness and reduced attack-level imbalance compared with standard multi-attack training.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Not All Attacks Are Learned Equally in Speech Deepfake Detection》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that attacks contribute unequally: some attacks have high EER sensitivity and concentrated entropy with low loss, indicating strong influence on the decision boundary. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech。 |

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

### 1. ZipCodec: Ultra-Low-Frame-Rate Streaming Speech Coding

👤 **作者**: Luca Della Libera, Cem Subakan, Mirco Ravanelli
🔗 **来源**: [https://arxiv.org/abs/2609.11642v1](https://arxiv.org/abs/2609.11642v1)

**摘要**
> Neural audio codecs are a fundamental component of modern speech generation systems. While recent codecs achieve increasingly low bitrates, reducing frame rate remains challenging, as each token must preserve more information while maintaining reconstruction quality. We present ZipCodec, a streaming neural speech codec operating at 6.25 Hz and 0.80 kbps with a theoretical latency of 160 ms. Our approach combines large-scale WavLM distillation with a redesigned transformer-based architecture, a scalar spherical quantizer, and a latency-aware streaming decoder. Experiments show that ZipCodec substantially outperforms existing streaming codecs at comparable bitrates in both reconstruction and downstream tasks, while operating at a significantly lower frame rate. Despite its 842M parameters, ZipCodec achieves real-time single-stream inference on a consumer-grade CPU. Demo samples, code and checkpoints are available at https://lucadellalib.github.io/zipcodec-web/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ZipCodec: Ultra-Low-Frame-Rate Streaming Speech Coding》所界定。 从摘要看，作者主要围绕 zipcodec、ultra-low-frame-rate、streaming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While recent codecs achieve increasingly low bitrates, reducing frame rate remains challenging, as each token must preserve more information while maintaining reconstruction quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：zipcodec, ultra-low-frame-rate, streaming。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
