<div align="center">

# 📰 Paper Claw

**2026-09-09**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-08 13:23:09 CST → 2026-09-09 13:25:32 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 6 篇新论文，主要分布在 Speech LLM 1, TTS 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Omni Interaction Agent Technical Report

👤 **作者**: Orantqing, Shengpeng Ji, Junlong Tong, Jialong Zuo, Dongjie Fu, Di Cao, Yangzhuo Li, Shangda Wu, Franz, Evan, Theron Veyra, Changhao Pan, Jingyu Lu, Dongchao Yang, Zhifei Xie, Yang Tan, Xiaoyu Shen, Xiaoda Yang, Wenfu Wang, Teddysun, Steveyves, Zhou Zhao, Bryanytian
🔗 **来源**: [https://arxiv.org/abs/2609.08977v1](https://arxiv.org/abs/2609.08977v1)

**摘要**
> In this work, we present Gander, an end-to-end model that unifies omni perception, realtime interaction, and agentic capabilities within a single framework. In contrast to turn-based conventional paradigms, Gander continuously receives streaming inputs across multiple modalities, including video, speech, and text, enabling natural full-duplex interaction in both everyday conversations and complex workflow-oriented agent scenarios. Users can interrupt the model at any time, while the model can also proactively provide intermediate feedback or ask follow up questions. To natively support these capabilities, Gander adopts two key architectural designs: 1) It employs a Cerebellum-Brain collaborative framework, in which the Cerebellum is responsible for realtime interaction and omni conversational capabilities, while the Brain handles complex reasoning and higher-level agentic tasks. The two components interact continuously through tool calling and the agent orchestration runtime. 2) The Cerebellum is built upon a streaming Thinker-Talker architecture, user inputs and model outputs are further flattened into an ordered token stream at the chunk level, providing a unified representation for low latency, continuous interaction. We conduct comprehensive evaluations of Gander across four dimensions: conversational ability, omni understanding, interactive capability, and agentic intelligence. Internal human evaluations demonstrate that Gander maintains the natural and expressive spoken dialogue capabilities of SOTA open source models while achieving competitive performance in omni interaction. Gander also demonstrates robustness in challenging real-world scenarios, including background noise interference, multi-party interactions, and backchannel communication. We release Gander together with its models, code, and data to facilitate further research and development in the community.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Omni Interaction Agent Technical Report》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Internal human evaluations demonstrate that Gander maintains the natural and expressive spoken dialogue capabilities of SOTA open source models while achieving competitive performance in omni interaction. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken dialogue。 |

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

### 1. Disentangled Global-Local Feature Learning with E-Branchformer for Audio Deepfake Detection

👤 **作者**: Phuong Tuan Dat, Ho Bao Thu, Nguyen Tran Trung, Pham Viet Hoang, Nguyen Thi Thu Trang
🔗 **来源**: [https://arxiv.org/abs/2609.08948v1](https://arxiv.org/abs/2609.08948v1)

**摘要**
> The rapid advancement of voice synthesis technologies such as text-to-speech and voice conversion poses significant threats to speech-based authentication systems, necessitating robust deepfake detection methods. In this work, we propose a novel E-Branchformer-based architecture that effectively leverages self-supervised speech representations for audio deepfake detection. Our model employs parallel branches to simultaneously capture global contextual dependencies through multi-head self-attention and local temporal patterns through convolutional processing. To enhance discriminative capability, we integrate depthwise convolution and Squeeze-and-Excitation modules that enrich the classification token with refined patch token information after feature merging. Extensive experiments on ASVspoof 2021 LA, DF, and In-the-Wild datasets demonstrate state-of-the-art performance with equal error rates of 0.88%, 1.85%, and 6.30% respectively, substantially outperforming existing methods. Comprehensive ablation studies validate that the dual-branch architecture provides complementary discriminative information, Squeeze-and-Excitation Aggregation significantly improves SSL feature integration, and the combination of DWConv and SE modules is critical for effective class token enhancement. The superior performance on real-world scenarios demonstrates strong generalization capability to diverse acoustic conditions and unseen spoofing attacks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Disentangled Global-Local Feature Learning with E-Branchformer for Audio Deepfake Detection》所界定。 从摘要看，作者主要围绕 text-to-speech、voice synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experiments on ASVspoof 2021 LA, DF, and In-the-Wild datasets demonstrate state-of-the-art performance with equal error rates of 0.88%, 1.85%, and 6.30% respectively, substantially outperforming existing methods. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech, voice synthesis。 |

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

### 1. Interpreting Dolphin Vocal Sequences via Multiple Sequence Alignment

👤 **作者**: Daniel Kohlsdorf, Denise Herzing, Thad Starner
🔗 **来源**: [https://arxiv.org/abs/2609.08795v1](https://arxiv.org/abs/2609.08795v1)

**摘要**
> Dolphin communication understanding is essential for uncovering the linguistic complexity and social structures of wild pods. We adapt the ClustalW bioinformatics algorithm to analyze continuous acoustic data, treating vocalizations as high-dimensional spectral feature vectors. By replacing discrete scoring with a continuous Gaussian kernel similarity measure, our framework generates Multiple Sequence Alignment (MSA) visualizations that reveal shared structural patterns. These alignments highlight temporal motifs such as synchronized burst pulses in aggressive contexts that are difficult to detect through standard spectrogram inspection.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Interpreting Dolphin Vocal Sequences via Multiple Sequence Alignment》所界定。 从摘要看，作者主要围绕 interpreting、dolphin、vocal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We adapt the ClustalW bioinformatics algorithm to analyze continuous acoustic data, treating vocalizations as high-dimensional spectral feature vectors. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：interpreting, dolphin, vocal。 |

---
### 2. From Scores to Evidence: Auditable Decisions Can Improve Speech Deepfake Detection

👤 **作者**: Mengzhe Geng, Yujia Lu, Patrick Littell, Manuela Kunz, Xie Chen
🔗 **来源**: [https://arxiv.org/abs/2609.08899v1](https://arxiv.org/abs/2609.08899v1)

**摘要**
> Speech deepfakes can mimic a speaker's voice convincingly enough to deceive listeners and automated systems. This has driven strong progress in speech deepfake detection, but most detectors still end with one score per utterance. That score is useful for ranking systems, yet it says little about why a borderline item should be trusted, deferred, or reviewed. Two utterances can fall in the same score band for different reasons, for example because passive and retrieval evidence disagree or because the keyed probe is unavailable. We ask whether the final decision can remain scalar without discarding that provenance. We answer this question with an auditable decision record that carries four aligned cues into a late calibration step: a passive detector score, a conditional keyed-probe score on a marked derivative, retrieval support, and a speaker-profile margin, together with explicit disagreement coordinates. On the 4,080-example ASVspoof 5 Track 1 matched subset, the fixed retrieval-augmented rule improves on retrieval-only evidence, from 15.84 percent to 11.91 percent EER, and late calibration over the full record reaches 8.43 percent EER. At a 33.75 percent review budget, the exposed cue union covers 82.85 percent of the calibrated model's errors. The best passive WavLM run still reaches 6.71 percent EER, so we do not present the decision record as a stronger standalone detector. Its contribution is to preserve the evidence behind each surfaced utterance while still producing one operating score for thresholding and review.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《From Scores to Evidence: Auditable Decisions Can Improve Speech Deepfake Detection》所界定。 从摘要看，作者主要围绕 from、scores、evidence 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On the 4,080-example ASVspoof 5 Track 1 matched subset, the fixed retrieval-augmented rule improves on retrieval-only evidence, from 15.84 percent to 11.91 percent EER, and late calibration over the full record reaches 8.43 percent EER. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：from, scores, evidence。 |

---
### 3. AuK Technical Report: An Open-Source Foundational Model for Speech Generation and Editing

👤 **作者**: Ziyang Ma, Zhikang Niu, Wenming Tu, Tianrui Wang, Ruiqi Yan, Junxi Liu, Yanru Huo, Nickk Huang, Yang Liu, Qicong Xie, Zeyu Xie, Hui Wang, Haitao Li, Zixuan Jiang, Yalin Li, Jie Fang, Yifan Duan, Zeyue Tian, Guangzheng Li, Haina Zhu, Shuyi Wang, Jinwen Wang, Mingyu Cui, Tian Tan, Auden, Sen Liang, Steve Yves, Shan Yang, Liefeng Bo, Zilong Zheng, Kai Yu, Eng-Siong Chng, Xie Chen
🔗 **来源**: [https://arxiv.org/abs/2609.08936v1](https://arxiv.org/abs/2609.08936v1)

**摘要**
> We introduce AuK, an open-source foundational model that unifies speech generation and editing through a common interface of natural-language instructions and audio context. To support this broad capability set, we construct approximately 3.03 billion instruction--audio instances and 1.95 million hours of effective supervision across five task families: speech generation, content editing, enhancement and separation, paralinguistic editing, and acoustic editing. AuK combines a multimodal large language model for semantic conditioning, an VAE jointly trained on speech, general audio, and music for acoustic conditioning, and a hybrid rectified-flow Transformer that performs dual-stream MMDiT blocks followed by unified single-stream DiT blocks for generation. Training begins with generation-only warm-up and proceeds to joint generation--editing pre-training. We then apply complementary post-training strategies: human-feedback preference optimization for open-ended editing and reward-based reinforcement learning for speech generation. To reduce inference cost, we further distill the model with consistency initialization and task-routed Decoupled DMD. The resulting AuK-Flash performs 4-step inference without classifier-free guidance and achieves a 4.5 wall-clock speedup over the full model under matched conditions. Experiments demonstrate leading performance on zero-shot and instruction-controlled speech generation and general instruction-guided editing, while remaining competitive on signal-level restoration tasks. We release both the source code and model weights to support reproducibility and further research.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AuK Technical Report: An Open-Source Foundational Model for Speech Generation and Editing》所界定。 从摘要看，作者主要围绕 technical、report、open-source 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The resulting AuK-Flash performs 4-step inference without classifier-free guidance and achieves a 4.5 wall-clock speedup over the full model under matched conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：technical, report, open-source。 |

---
### 4. TASTE2: Text-Aligned Speech Modeling and Deployment toward Full-Duplex Voice Interaction

👤 **作者**: Yi-Chang Chen, Chun Wei Chen, Dien-Ruei Wu, Jie Lin, Yu-Kuan Fu, Yang-Hsien Lin, Eddie TC Huang, Simon See, Hung-yi Lee, Da-Shan Shiu
🔗 **来源**: [https://arxiv.org/abs/2609.08956v1](https://arxiv.org/abs/2609.08956v1)

**摘要**
> Full-duplex voice interaction requires more than utterance-level conversion. It must process streaming speech, manage turn-taking and interruptions, while preserving pretrained linguistic competence and acoustic paralinguistic cues. We ask whether TASTE (Text-Aligned Speech Tokenization and Embedding) provides a viable path toward this goal. We present TASTE2, which transforms utterance-level TASTE into an incremental dialogue stack. A shared text-token vocabulary removes word-level averaging, while modality-aligned dialogue training predicts one continuous audio latent per text token without interleaving heterogeneous token streams. An incremental Speech Detokenizer enables streaming synthesis through CosyVoice2. After speech and dialogue training, TASTE2 (Merge) reaches 56.3% on LLaMA-Questions against a 57.3% Qwen2.5-7B Instruct text-only reference (98.2% accuracy retention), and TASTE2 (Direct) reaches 53.0% (92.4% retention). We build TASTE2 VoiceBot, which processes user speech incrementally, streams synthesized audio, and stops generation on barge-in. On Full-Duplex-Bench v1.0, TASTE2 and TASTE2 VoiceBot handle interruptions well while maintaining high conversational coherence. Natural conversation remains challenging, and deployed mean time to first audio is 2.701 s on two NVIDIA RTX A6000 after TensorRT acceleration. Finally, to our knowledge, we provide the first systematic characterization of explicit paralinguistic control in a TASTE based model. Fast speaking rate serves as a cross-strategy proof of concept after dialogue SFT, while emotion control is strategy dependent and the remaining attributes stay weak. Together, these results establish TASTE based modeling as a practical route toward full-duplex systems while identifying natural conversation robustness, speech generation latency, and feature general paralinguistic control as open challenges. Explore TASTE2 online.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《TASTE2: Text-Aligned Speech Modeling and Deployment toward Full-Duplex Voice Interaction》所界定。 从摘要看，作者主要围绕 taste、text-aligned、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：It must process streaming speech, manage turn-taking and interruptions, while preserving pretrained linguistic competence and acoustic paralinguistic cues. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：taste, text-aligned, speech。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
