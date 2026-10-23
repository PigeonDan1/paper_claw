<div align="center">

# 📰 Paper Claw

**2026-10-23**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-22 13:31:21 CST → 2026-10-23 13:29:17 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 2 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 2, ASR 1, Enhancement 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Query-Conditioned Liquid Temporal Grounding for Long-Form Audio

👤 **作者**: Yuelan Cheng, Yonggang Zhu, Yongqiang Chen, Peiwei Chang, Yingyi Chen, Wenwu Wang
🔗 **来源**: [https://arxiv.org/abs/2610.31252v1](https://arxiv.org/abs/2610.31252v1)

**摘要**
> Long-form temporal audio grounding (TAG) is challenging because target events often occupy only a small portion of a recording, while queries may impose multiple semantic constraints over a large temporal search space. We propose a query-conditioned liquid temporal grounding framework that injects query semantics through FiLM before a closed-form continuous-time (CfC) network models long-range temporal dependencies. Multiple query-relevant candidates are generated, from which a frozen large audio-language model selects the most compatible one for lightweight local boundary refinement. The pretrained backbone remains frozen, with only lightweight grounding modules optimized. Experiments on the English TAG subset of LAT-Bench show consistent improvements across MOSS-Audio and Qwen3-Omni, while ablations confirm the complementary roles of FiLM and CfC.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Query-Conditioned Liquid Temporal Grounding for Long-Form Audio》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the English TAG subset of LAT-Bench show consistent improvements across MOSS-Audio and Qwen3-Omni, while ablations confirm the complementary roles of FiLM and CfC. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model。 |

---
### 2. Spark-Audio 1.0 Technical Report

👤 **作者**: Chenyue Zhang, Cong Liu, Dingshu Tian, Dong Sun, Genshun Wan, Guanming Meng, Guolong Zhong, Hang Chen, Hankun Yang, Haoming Wang, Haoyang Wang, Hengquan Mei, Huaxin Wu, Jiahao Li, Jiahuan Fan, Jiamin Ma, Jianqing Gao, Jigang Tang, Jin Liu, Jingchen Li, Jinjie Fu, Kaixuan Guo, Kun Song, Li Xu, Li Zhang, Lijuan Liu, Liyan Luo, Ming Sheng, Mingen Zhao, Mingting Hu, Ningqian Wu, Pan Xu, Pei Xu, Qiangyu Tan, Rui Wang, Ruzi Li, Saier Jin, Shibo Xu, Shifu Xiong, Shihao Jiang, Tan Liu, Wei Wu, Wei Xu, Wenyu Wang, Xiangyu Jia, Xiao Li, Xiaowen Duan, Xiaoxue Guo, Xin Chen, Xinyi Liang, Xu Chen, Yanan Song, Yang Xu, Yexia Huang, Yibo Li, Yifan Xu, Yikang Liu, Yikun Li, Yiting Lin, Yi Fang, Yuxin Wang, Zan Feng, Zhenchuan Li, Zhuo Chen, Zichao Zhang, Ziwen Wang
🔗 **来源**: [https://arxiv.org/abs/2610.31292v1](https://arxiv.org/abs/2610.31292v1)

**摘要**
> This paper introduces Spark-Audio 1.0, a speech foundation model trained on domestically produced computing infrastructure. The model accepts text and speech inputs and generates text outputs. It supports multilingual (99 languages) and multi-dialect (202 dialects) speech recognition, speech translation, audio perception and understanding, and both text- and speech-based dialogue, marking a shift from merely ``hearing clearly'' to genuinely ``understanding'' speech. Architecturally, Spark-Audio 1.0 couples a 0.65B-parameter dense audio encoder with a 30B-A3B Mixture-of-Experts (MoE) large language model (LLM). The audio encoder is pretrained with representation-enhanced BEST-RQ and then refined through multi-task supervised training. The audio--LLM is trained through staged pretraining, followed by post-training that combines supervised fine-tuning with on-policy distillation. In total, the model is trained on 13 million hours of audio data together with large-scale text data. We evaluate Spark-Audio 1.0 on mainstream audio and text benchmarks, as well as on in-house test sets drawn from real-world application scenarios. Despite using substantially less audio training data than Qwen3.5-Omni-Flash, Spark-Audio 1.0 achieves comparable performance on most audio and text tasks, outperforms it in multilingual speech recognition, spoken dialogue, and real-world application scenarios, and approaches the performance of larger closed-source models. Nevertheless, there remains room for improvement in instruction following and complex audio reasoning. Finally, the successful training of Spark-Audio 1.0 on domestic hardware, including Huawei Ascend 910B and Hygon BW1000 chips, demonstrates the feasibility of a domestic technical pathway for building speech foundation models.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Spark-Audio 1.0 Technical Report》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Despite using substantially less audio training data than Qwen3.5-Omni-Flash, Spark-Audio 1.0 achieves comparable performance on most audio and text tasks, outperforms it in multilingual speech recognition, spoken dialogue, and real-world application scenarios, and approaches the performance of larger closed-source models. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken dialogue。 |

---
## 🏷️ ASR

### 1. Measuring the Verifier's Floor: How Much Apparent Rare-Word Text-to-Speech Error Is ASR Error?

👤 **作者**: Kirill Borodin, Vasilii Kudryavtsev, Nikita Vasiliev, Grach Mkrtchian
🔗 **来源**: [https://arxiv.org/abs/2610.31470v1](https://arxiv.org/abs/2610.31470v1)

**摘要**
> Text-to-speech (TTS) is usually evaluated by transcribing its output with an automatic speech recognition (ASR) system, so the word error rate also counts recognizer errors. We measure these errors on human recordings of the test sentences. On LibriSpeech and FLEURS, the evaluation recognizer misses 33-67% of very rare words even in human speech, and all three recognizers miss 22-42%. Checking every word with two more recognizer families lowers the apparent TTS error on words that at least one recognizer hears two- to three-fold (very rare LibriSpeech words: from 10-13% to 3-5%), yet very rare words remain the hardest. Ignoring words the recognizer misses in human speech is biased: the other recognizers find TTS errors far more often on these words (4-6% vs. 0.2-0.3%) and overturn about half of the errors this mask keeps. As half of the remaining adjudicated errors may be spelling variants, a listening test is needed.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Measuring the Verifier's Floor: How Much Apparent Rare-Word Text-to-Speech Error Is ASR Error?》所界定。 从摘要看，作者主要围绕 automatic speech recognition、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We measure these errors on human recordings of the test sentences. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, text-to-speech。 |

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. From Signals to Evidence: Interpretable Underwater Acoustic Target Sensing with Large Language Models - Part II: Passive Detection

👤 **作者**: Zhiyuan Li, Yuge Zhang, Jie Chen, Xiruo Su, Zhengqiao Zhao, Xiling Yao, Lingji Xu, Jingdong Chen, Yixin Yang
🔗 **来源**: [https://arxiv.org/abs/2610.31346v1](https://arxiv.org/abs/2610.31346v1)

**摘要**
> Underwater acoustic passive detection is essential to maritime surveillance and intelligent ocean sensing. Existing detection systems typically collapse multichannel array observations into a binary decision or a scalar confidence score, offering limited insight into the physical evidence that supports or contradicts a target declaration. This limitation is acute at low signal-to-noise ratio (SNR), where isolated spectral peaks and transient beamforming responses are inherently ambiguous and physically verifiable targets are characterized by an ensemble of coupled reinforcing cues. Building on the unified from-signals-to-evidence framework introduced in the companion Part I, this paper instantiates the framework for passive target detection. A physics-aware multichannel acoustic encoder encodes the array observations into complementary acoustic evidence tokens through a direction-guided architecture that combines minimum variance distortionless response (MVDR) processing with time-frequency and fine-frequency representations. These tokens are combined with environmental priors and fed into a pretrained large language model (LLM) that evaluates target-present and noise-only hypotheses and generates a structured detection report detailing target presence, bearing, spectral-line locations, received SNR, range, and per-field confidence scores. A physics-parameterized data engine extended to realistic oceanic channels provides traceable supervision at both discrete-label and structured-description levels. Experiments under white-noise and mixed ocean-background conditions demonstrate reliable detection, accurate bearing estimation, and physically interpretable structured reports, validating the feasibility of evidence-grounded underwater acoustic detection.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《From Signals to Evidence: Interpretable Underwater Acoustic Target Sensing with Large Language Models - Part II: Passive Detection》所界定。 从摘要看，作者主要围绕 beamforming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments under white-noise and mixed ocean-background conditions demonstrate reliable detection, accurate bearing estimation, and physically interpretable structured reports, validating the feasibility of evidence-grounded underwater acoustic detection. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beamforming。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. PerMix: Anomalous sound detection by predicting the perturbation ratio of mixed samples

👤 **作者**: Jihoon Choi, Jung-Woo Choi
🔗 **来源**: [https://arxiv.org/abs/2610.31434v1](https://arxiv.org/abs/2610.31434v1)

**摘要**
> In anomalous sound detection based on self-supervised learning, the performance of the detection model largely depends on the selection of the pretext task through which the characteristics of normal data are learned. A common pretext task is to mix samples from different classes and classify the mixed sample as its target class with an angular margin loss. However, this supervision becomes mismatched when the target sample is the minority component of the mixture and the margin remains fixed irrespective of the mixing ratio. To address these issues, we propose a pretext task that directly predicts the perturbation ratio of mixed samples by reformulating the logit so that the angular margin is scaled by the perturbation ratio. In addition, we adopt a supervised contrastive loss modified for mixed samples, in which positive pairs are formed according to the dominant class. Experiments show that our approach achieves state-of-the-art results on the DCASE 2020 Task 2 benchmark. Our code is available at https://github.com/kaistss/PerMix.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《PerMix: Anomalous sound detection by predicting the perturbation ratio of mixed samples》所界定。 从摘要看，作者主要围绕 permix、anomalous、sound 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that our approach achieves state-of-the-art results on the DCASE 2020 Task 2 benchmark. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：permix, anomalous, sound。 |

---
### 2. Piano2Pop: Expanding Piano Demos into Pop Productions Without Aligned Supervision

👤 **作者**: Yun-Chen Cheng, Chih-Pin Tan, Tzu-Hung Huang, Yi-Hsuan Yang
🔗 **来源**: [https://arxiv.org/abs/2610.31510v1](https://arxiv.org/abs/2610.31510v1)

**摘要**
> We introduce Piano2Pop, a music-expansion task that transforms piano MIDI into instrumental pop productions. Enabled by recent advances in music generation and polyphonic music transcription, our pseudo-supervised approach conditions a pretrained flow-matching model on piano rolls without aligned piano-pop supervision. We train on synthetic piano-instrumental pairs derived from pop recordings, comparing pair-free transcription, including function-selective (FST) and register-density (RDA) augmentations, with a pair-supervised piano-cover generator as pseudo-demo sources. On 476 testing real-world piano-cover/pop pairs, the pair-supervised approach achieves the best Frechet Audio Distance, Accompaniment Prompt Adherence, and spectral shape on real-piano inputs, while FST mitigates piano-heavy outputs in pair-free training and remains a promising alternative. All fine-tuned systems significantly outperform the zero-shot baselines, which suggests a role for task-specific modeling.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Piano2Pop: Expanding Piano Demos into Pop Productions Without Aligned Supervision》所界定。 从摘要看，作者主要围绕 piano、expanding、demos 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On 476 testing real-world piano-cover/pop pairs, the pair-supervised approach achieves the best Frechet Audio Distance, Accompaniment Prompt Adherence, and spectral shape on real-piano inputs, while FST mitigates piano-heavy outputs in pair-free training and remains a promising alternative. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：piano, expanding, demos。 |

---
### 3. Signed Wasserstein distance for room impulse response comparison

👤 **作者**: Linda Fabiani, Sebastian J. Schlecht, Filip Elvander
🔗 **来源**: [https://arxiv.org/abs/2610.31596v1](https://arxiv.org/abs/2610.31596v1)

**摘要**
> The nature of room impulse response signals is often adverse to a clear evaluation of similarity: they are sparse, rapidly varying, signed signals resulting from the complex interaction of room reflections and phase relationships. Therefore, conventional point-wise metrics may be sensitive to small temporal shifts and provide poor loss surfaces for optimization. In this paper, we propose an optimal transport-based distance for RIR similarity that explicitly accounts for the structure of impulse responses, inspired by the signed Wasserstein distance formulation. Optimal transport provides a natural framework for this problem, by comparing signals based on how their underlying distributions are displaced rather than requiring a one-to-one correspondence. We evaluate the proposed distance against commonly used audio baseline metrics through a series of room-parameter perturbation studies. The results demonstrate the advantage of using the signed Wasserstein metric for geometric evaluation tasks and show a promising performance for room parameter optimization within a differentiable Image-Source model.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Signed Wasserstein distance for room impulse response comparison》所界定。 从摘要看，作者主要围绕 signed、wasserstein、distance 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results demonstrate the advantage of using the signed Wasserstein metric for geometric evaluation tasks and show a promising performance for room parameter optimization within a differentiable Image-Source model. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：signed, wasserstein, distance。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
