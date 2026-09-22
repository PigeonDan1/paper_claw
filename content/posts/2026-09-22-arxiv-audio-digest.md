<div align="center">

# 📰 Paper Claw

**2026-09-22**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-21 13:34:45 CST → 2026-09-22 13:31:07 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, TTS 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. XSQ-AST: An Explainable Audio Spectrogram Transformer Framework for Localising Synthetic Speech Artifacts

👤 **作者**: Ben Heritage, Luca Resti, Mónica Villanueva Aylagas, Timothy Mehlenbacher, Konrad Tollmar, James Alfred Walker
🔗 **来源**: [https://arxiv.org/abs/2609.24770v1](https://arxiv.org/abs/2609.24770v1)

**摘要**
> Localising artifacts in synthetic speech remains challenging, as most evaluation methods yield only global quality scores. This paper presents XSQ-AST, a framework that combines the SQ-AST speech quality model with WhisperX phoneme alignment and multiple saliency methods to produce temporally localised artifact diagnostics without model retraining. Saliency maps are projected onto continuous distributions via kernel density estimation and onto phoneme boundaries via phoneme-discretised saliency maps. A 40-participant listening test validated the framework across five perceptual dimensions. Attention Rollout, Attention Flow and an adapted GradCAM produced temporal distributions that correlated with listener highlights, with different methods best suited to different artifact types. An AUC-ROC analysis confirmed discrimination above chance.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《XSQ-AST: An Explainable Audio Spectrogram Transformer Framework for Localising Synthetic Speech Artifacts》所界定。 从摘要看，作者主要围绕 whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper presents XSQ-AST, a framework that combines the SQ-AST speech quality model with WhisperX phoneme alignment and multiple saliency methods to produce temporally localised artifact diagnostics without model retraining. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：whisper。 |

---
## 🏷️ TTS

### 1. CycleSpeech: Reciprocal Alignment for Instruction-Controlled Speech Synthesis and Paralinguistic Understanding

👤 **作者**: Huan Liao, Haonan Han, Xingwen Han, Dekun Chen, Yuancheng Wang, Zhizheng Wu
🔗 **来源**: [https://arxiv.org/abs/2609.24771v1](https://arxiv.org/abs/2609.24771v1)

**摘要**
> Instruction-controlled speech synthesis and paralinguistic understanding are often trained independently, leaving reciprocal feedback between the two tasks underexplored. We introduce CycleSpeech, a framework that connects generation and understanding through a shared, structured voice profile that serves as a common target for supervision and reciprocal feedback. The forward cycle assesses whether synthesized speech expresses the intended attributes by comparing recovered and target profiles. The backward cycle evaluates whether profiles inferred from real speech can guide reconstruction of the source speaking style. To support both directions, we construct a bilingual dataset of 20,046 examples pairing instructions, target speech, speaker references, and structured profiles. Building on joint supervised fine-tuning, CycleGRPO alternates policy updates using reciprocal rewards grounded in profile consistency and speaking-style reconstruction. Fixed target profiles anchor feedback from the evolving counterpart. This procedure requires neither human preference annotations nor an additional preference-trained reward model. Evaluations on Chinese and English benchmarks show improved instruction adherence and profile recovery while maintaining competitive synthesis quality. Compared with Step-Audio-2-mini, CycleSpeech improves instruction-match accuracy by 4.50 and 10.06 percentage points in Chinese and English, respectively. Controlled ablations further support the contribution of cycle feedback to generation control. These results support structured voice profiles as an interface for reciprocal training between speech generation and paralinguistic understanding. An online demo is available at https://cyclespeech.github.io.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《CycleSpeech: Reciprocal Alignment for Instruction-Controlled Speech Synthesis and Paralinguistic Understanding》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluations on Chinese and English benchmarks show improved instruction adherence and profile recovery while maintaining competitive synthesis quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
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

### 1. Understanding Hyperspherical Geometry of ECAPA-TDNN Embedding and Its Impact on Zero-Shot Voice Conversion

👤 **作者**: Mathilde Abrassart, Nicolas Obin, Axel Roebel
🔗 **来源**: [https://arxiv.org/abs/2609.24688v1](https://arxiv.org/abs/2609.24688v1)

**摘要**
> Angular-margin speaker encoders are widely used in voice conversion, yet the geometry of their classifier prototypes remains poorly understood. We analyze ECAPA-TDNN classifier prototypes as points on the unit hypersphere and characterize their organization using rotation-invariant angular statistics together with global and local effective dimensionality measures. Our analysis shows that standard training can induce angular concentration and a substantial reduction in effective dimensionality. To address this, we investigate two geometric regularization strategies (hinged Riesz log-energy and effective-dimension maximization) applied to classifier prototypes to encourage more uniform hyperspherical coverage. The resulting prototype sets exhibit higher effective dimensionality and improved isotropy, with configuration-dependent effects on speaker-recognition performance. When the corresponding ECAPA-TDNN models are used as speaker encoders for Fast-VGAN, the regularized systems also exhibit improved robustness in zero-shot voice conversion, particularly for previously unseen speakers.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Understanding Hyperspherical Geometry of ECAPA-TDNN Embedding and Its Impact on Zero-Shot Voice Conversion》所界定。 从摘要看，作者主要围绕 understanding、hyperspherical、geometry 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our analysis shows that standard training can induce angular concentration and a substantial reduction in effective dimensionality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：understanding, hyperspherical, geometry。 |

---
### 2. Fast Time-Varying Exponentiated Convolution Methods for Generative Direction Dependent Reverberation

👤 **作者**: Yuancheng Luo
🔗 **来源**: [https://arxiv.org/abs/2609.24809v1](https://arxiv.org/abs/2609.24809v1)

**摘要**
> Spherical harmonic encoded acoustic sound-fields capture directional characteristics of room impulse responses that are useful for accurate spatial audio reproduction. However, high costs of multi-microphone measurements and numerical simulations motivate alternative data-set augmentation and synthetic data generation methods that supplement small collections. This paper introduces time-varying exponentiated convolution methods that transform both Gaussian noise and impulse responses into reverberation and modified spectral-decay fields respectively. We derive two recursive and fast convolution algorithms that extend into the spherical harmonic domain, model smooth reverberation time distributions with non-stationary Gaussian processes, and realize an optimal filter design. Experiments evaluate computational performance, and validate out-of-distribution generated impulse responses.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Fast Time-Varying Exponentiated Convolution Methods for Generative Direction Dependent Reverberation》所界定。 从摘要看，作者主要围绕 fast、time-varying、exponentiated 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, high costs of multi-microphone measurements and numerical simulations motivate alternative data-set augmentation and synthetic data generation methods that supplement small collections. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：fast, time-varying, exponentiated。 |

---
### 3. Automated Assessment of L2 Speech Rhythm Using Low-Frequency Amplitude Modulations

👤 **作者**: João Lima, Lucas Ueda, Paula Costa
🔗 **来源**: [https://arxiv.org/abs/2609.24818v1](https://arxiv.org/abs/2609.24818v1)

**摘要**
> Automated Speaking Assessment of non-native speech must effectively evaluate prosody, including speech rhythm, to align with human perception. However, commonly employed rhythm metrics rely on segmental duration, requiring an additional alignment step, which is error-prone in non-native speech containing disfluencies and mispronunciations. We propose an acoustics-based assessment approach that employs a convolutional neural network to extract rhythm features directly from the speech amplitude envelope, motivated by evidence linking low-frequency modulations to rhythm perception. The proposed models are trained on a proficiency score regression task using the speechocean762 dataset and compared against duration-based models. Our results show that a model using the amplitude envelope's first derivative achieves the highest correlation with human-assigned scores on the Fluency and Prosody dimensions, producing significantly lower errors than one using segment durations among less fluent speakers. The findings support acoustic envelope features as robust, alignment-free alternatives for L2 rhythm assessment. Code is released publicly.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Automated Assessment of L2 Speech Rhythm Using Low-Frequency Amplitude Modulations》所界定。 从摘要看，作者主要围绕 automated、assessment、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that a model using the amplitude envelope's first derivative achieves the highest correlation with human-assigned scores on the Fluency and Prosody dimensions, producing significantly lower errors than one using segment durations among less fluent speakers. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automated, assessment, speech。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
