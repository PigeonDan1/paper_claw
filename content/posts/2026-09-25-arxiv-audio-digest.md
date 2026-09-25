<div align="center">

# 📰 Paper Claw

**2026-09-25**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-24 13:33:38 CST → 2026-09-25 13:31:55 CST |
| 📄 论文总数 | **13** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 2 篇
- **TTS**: 1 篇
- **Enhancement**: 3 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 6 篇

> 💡 今日共收录 13 篇新论文，主要分布在 Speech LLM 1, ASR 2, TTS 1, Enhancement 3, Audio 6。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. To Trust or Not to Trust: Retrieval-Augmented Fact Checking in Speech

👤 **作者**: Debajyoti Mazumder, Mamta, Abhirama Subramanyam Penamakuri
🔗 **来源**: [https://arxiv.org/abs/2609.30227v1](https://arxiv.org/abs/2609.30227v1)

**摘要**
> Online misinformation increasingly appears in spoken formats such as news clips, podcasts, interviews, political speeches, and social media videos, creating a need for fact-checking systems that can verify claims directly from speech. We introduce VeriSpeak, a probe benchmark for studying speech-based fact verification in Large Audio Language Models (LALMs). VeriSpeak contains 3,879 spoken claims spanning temporal, geographical, and relational facts, with balanced true and false labels. The benchmark is designed to examine whether factual verification ability transfers from text to speech, and whether retrieval-augmented LALMs can use textual evidence to correctly support or refute spoken claims. Our experiments reveal a consistent text-speech modality gap: LALMs that verify written claims reliably often fail on the same claims when spoken. Moreover, retrieval alone provides limited gains because models frequently conflate retrieved evidence with the spoken claim. In contrast, retrieval combined with explicit reasoning improves claim-evidence comparison, with a thinking-tuned LALM reaching 86.1% accuracy. VeriSpeak highlights that effective speech misinformation detection requires not only speech understanding, but also grounded reasoning over retrieved evidence. The dataset is publicly available via Hugging Face at https://huggingface.co/datasets/abhiram4572/VeriSpeak.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《To Trust or Not to Trust: Retrieval-Augmented Fact Checking in Speech》所界定。 从摘要看，作者主要围绕 speech understanding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In contrast, retrieval combined with explicit reasoning improves claim-evidence comparison, with a thinking-tuned LALM reaching 86.1% accuracy. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech understanding。 |

---
## 🏷️ ASR

### 1. VietPrism: A large-scale Vietnamese speech and deepfake corpus with diverse dialects and code-switching

👤 **作者**: Minh Hoang, Thai Le
🔗 **来源**: [https://arxiv.org/abs/2609.30005v1](https://arxiv.org/abs/2609.30005v1)

**摘要**
> Vietnamese speech research is constrained by resources that isolate automatic speech recognition from speaker, dialect, code-switching, and deepfake analysis. We introduce VietPrism, an open, multi-domain corpus that brings these dimensions together at scale: 993.4 hours and 403,941 bona fide utterances from 1,262 verified speakers across 8,388 real-world videos. To our knowledge, it is the first large-scale Vietnamese corpus to jointly provide transcripts, consistent speaker identities, five dialect groups, and naturally occurring Vietnamese--English code-switching, which constitutes nearly half of the corpus by duration. We further create over 3.1K hours of spoof speech with four open-source and commercial synthesis systems. Every spoof is conditioned on a verified speaker reference and paired with a transcript- and speaker-matched bona fide utterance, enabling unique controlled evaluation with reduced lexical and identity confounds. Zero-shot evaluation of five pretrained multilingual detectors reveals striking brittleness: EER greatly varies across detector--generator pairings, while recent multilingual detector DFA-1B degrades from 16.3% to 33.6% as speaker similarity increases. Dialect-stratified results expose further model-dependent disparities. By unifying natural linguistic diversity with controlled spoof generation, VietPrism provides a challenging foundation for Vietnamese speech modeling and trustworthy audio-deepfake detection.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《VietPrism: A large-scale Vietnamese speech and deepfake corpus with diverse dialects and code-switching》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We introduce VietPrism, an open, multi-domain corpus that brings these dimensions together at scale: 993.4 hours and 403,941 bona fide utterances from 1,262 verified speakers across 8,388 real-world videos. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

---
### 2. A Training Criterion with Token-Level Tolerance to Transcription Ambiguity for Automatic Speech Recognition

👤 **作者**: Saurabh Kumar, Diptiman Mohanta, Prasanta Kumar Ghosh
🔗 **来源**: [https://arxiv.org/abs/2609.30160v1](https://arxiv.org/abs/2609.30160v1)

**摘要**
> Automatic speech recognition is typically trained assuming that the reference transcript is the only valid labeling of an utterance, yet even nominally verbatim transcripts contain localized differences in pronunciation, spelling, or lexical realization that the acoustics do not uniquely determine. Omni-temporal Classification (OTC) tolerates such noise by adding wildcard paths to the connectionist temporal classification (CTC) alignment graph, but its word-level arcs are too coarse, since bypassing one unsupported token discards supervision for the whole word. We move wildcard arcs to token granularity so unsupported tokens can be bypassed while the rest of the word stays supervised, and we combine token- and word-level arcs as complementary escape paths. Across 19 languages and three corpora, token-level OTC improves over CTC on all 25 tasks. We also replace epoch-indexed relaxation of the wildcard weights with a predictive-entropy-indexed schedule, which performs comparably while reducing dependence on training length. Combining this schedule with the hybrid graph gives the lowest mean word error rate (WER) on every corpus and a 9.45% average relative WER reduction over CTC. Independent validator transcriptions show that token-level models place significantly more wildcard-bypass probability than CTC on disputed characters, indicating that token-level tolerance targets localized transcript ambiguity.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《A Training Criterion with Token-Level Tolerance to Transcription Ambiguity for Automatic Speech Recognition》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across 19 languages and three corpora, token-level OTC improves over CTC on all 25 tasks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

---
## 🏷️ TTS

### 1. EditVoice: Variable-Length Non-Autoregressive Zero-Shot TTS and Speech Editing with Edit Flows

👤 **作者**: Hongyao Deng, Wenhao Guan, Xuetao Lin, Peijie Chen, Weijie Wu, Lin Li, Qingyang Hong
🔗 **来源**: [https://arxiv.org/abs/2609.29889v1](https://arxiv.org/abs/2609.29889v1)

**摘要**
> Recent non-autoregressive (NAR) zero-shot text-to-speech (TTS) models generate in parallel but typically require the target sequence length to be specified before generation. We introduce EditVoice, to our knowledge the first variable-length NAR zero-shot TTS model, which uses Edit Flows to jointly update speech content and sequence length through insertions, deletions, and substitutions. EditVoice adopts speech-infilling training, which unifies zero-shot TTS and text-based speech editing and allows both prefix and suffix speech prompt placements at inference. We introduce Complementary Prompt Sampling (CPS) to leverage the complementary Edit Flow predictions induced by the two prompt placements. We further find that EditVoice can edit source and model-generated speech beyond its training sources. We use this generalization for end-to-end editing and training-free post-generation refinement. With the Edit Flow model trained on 10K h of GigaSpeech, EditVoice demonstrates competitive zero-shot TTS performance on Seed-TTS Eval EN and LibriSpeech-PC and speech editing performance on RealEdit.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《EditVoice: Variable-Length Non-Autoregressive Zero-Shot TTS and Speech Editing with Edit Flows》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：With the Edit Flow model trained on 10K h of GigaSpeech, EditVoice demonstrates competitive zero-shot TTS performance on Seed-TTS Eval EN and LibriSpeech-PC and speech editing performance on RealEdit. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
## 🏷️ Enhancement

### 1. STAM-ASR: Speaker-Temporal Anchoring with Memory for Multi-Speaker ASR

👤 **作者**: Victor Tolulope Olufemi, Syeda Faiza Ahmed Sara, Shammur Absar Chowdhury
🔗 **来源**: [https://arxiv.org/abs/2609.29805v1](https://arxiv.org/abs/2609.29805v1)

**摘要**
> Natural conversations make both speech recognition and speaker attribution challenging for ASR, as speakers take turns, overlap, and reappear over time. We propose STAM-ASR, Speaker-Temporal Anchoring with Memory, a lightweight framework that extends an already pretrained AudioLLM for multi-speaker ASR. Without relying on an external diarization system, STAM-ASR learns speaker activity and speaker-aware representations directly from intermediate AudioLLM features. Hence providing explicit who and when cues to modulate the AudioLLM's semantic representation without explicit speech separation. STAM-ASR further maintains fixed-size speaker and conversational memories to carry complementary context across turns. We evaluate STAM-ASR on AMI, ICSI, LibriCSS, and NOTSOFAR-1 across close-talk, far-field, overlapping, and cross-domain conditions. Our reported results shows that speaker-temporal conditioning and memory provide complementary benefits, while the gap between reference and predicted speaker activity identifies robust speaker tracking as a key remaining challenge.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《STAM-ASR: Speaker-Temporal Anchoring with Memory for Multi-Speaker ASR》所界定。 从摘要看，作者主要围绕 speech separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our reported results shows that speaker-temporal conditioning and memory provide complementary benefits, while the gap between reference and predicted speaker activity identifies robust speaker tracking as a key remaining challenge. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech separation。 |

---
### 2. Beyond Model Size: Redesigning LiSenNet for embedded speech enhancement

👤 **作者**: Clément Laroche, Rasmus Kongsgaard Olsson
🔗 **来源**: [https://arxiv.org/abs/2609.29866v1](https://arxiv.org/abs/2609.29866v1)

**摘要**
> Deploying real-time speech enhancement on resource-constrained devices requires meeting strict latency, memory, and energy constraints. Microcontroller NPUs can accelerate neural inference under these constraints, but only through a restricted set of operators in static, integer-quantized graphs. Recent speech-enhancement networks have reduced parameter counts and MACs to levels nominally suitable for microcontrollers, but their operators and execution patterns often remain incompatible with restricted NPUs. We address this gap by redesigning LiSenNet, a 37k parameter sub-band dual-path model, for the STM32N6570-DK Neural-ART accelerator. We replace its recurrent bottleneck with convolutional frequency and temporal mixers, reformulate unsupported operations as static int8-compatible primitives, and use bounded decoder activations to preserve quality after quantization. On VoiceBank-DEMAND, the final NPU-compatible model matches or exceeds the recurrent LiSenNet baseline, reaching PESQ 3.08 versus 3.01 in FP32 and 3.01 versus 2.93 in int8. Deployed on a microcontroller, it processes each 16 ms input hop in 4.83 ms, corresponding to a real-time factor of 0.30. Stateless receptive-field recomputation is an order of magnitude slower at the same frame rate despite higher accelerator utilization. These results show that parameter count and operator compatibility, quantization range, and persistent streaming state must be co-designed to achieve efficient real-time speech enhancement on restricted NPUs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Beyond Model Size: Redesigning LiSenNet for embedded speech enhancement》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These results show that parameter count and operator compatibility, quantization range, and persistent streaming state must be co-designed to achieve efficient real-time speech enhancement on restricted NPUs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
### 3. Does per-frame early exit pay? A compute-matched study of dynamic depth for on-device speech enhancement

👤 **作者**: Clément Laroche, Riccardo Miccini
🔗 **来源**: [https://arxiv.org/abs/2609.29867v1](https://arxiv.org/abs/2609.29867v1)

**摘要**
> Deep learning-based speech enhancement is increasingly deployed on-device in hearing aids, headsets, and earbuds. Most of these devices, however, can only accelerate static int8 graphs, so a depth-varying network must be implemented as several graphs, orchestrated by a policy. In this paper, we supervise every intermediate depth of one causal model, then we fine-tune its output heads to guarantee that deeper outputs are never worse than shallower ones. Using this training protocol, we can derive a family of static models that are more Pareto-efficient than their equivalently-sized counterparts trained from scratch on the same budget. Specifically, we achieve up to 0.11 higher PESQ for equivalent compute, and match the best PESQ at 30% less compute. We then quantize the models to int8 and measure the latency-quality frontier on an STM32N6 microcontroller. On VoiceBank-DEMAND, the dynamic enhancer lies on the same frontier as the static models, rather than trading quality for dynamic execution. Running the policy on the companion Cortex-M55 takes only 26 $μ$s per frame, while splitting the enhancer into separate NPU graphs adds 2.2% latency overhead. The cost of dynamic execution is therefore small.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Does per-frame early exit pay? A compute-matched study of dynamic depth for on-device speech enhancement》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Specifically, we achieve up to 0.11 higher PESQ for equivalent compute, and match the best PESQ at 30% less compute. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. AV-GRPO: Modality-Anchored Decoupling Diffusion Reinforcement Learning for Joint Audio-Video Generation

👤 **作者**: Zhiyu Xu, Weilong Yan, Yufei Shi, Shiyang Li, Yihao Liu, Kin-Man Lam, Yuewen Cao
🔗 **来源**: [https://arxiv.org/abs/2609.29816v1](https://arxiv.org/abs/2609.29816v1)

**摘要**
> Recent years have witnessed major progress in joint audio-video generation. Existing models still suffer from limited per-modality fidelity, insufficient text-modality alignment and weak cross-modal synchronization. While reinforcement-learning post-training offers a promising remedy, directly adapting it to joint audio-video generation is challenging. Heterogeneous multimodal rewards entangle learning signals and complicate credit assignment. Joint optimization of two modality towers is computationally expensive given their divergent dynamics. Moreover, synchronization evaluation difficulty depends on paired samples, preventing fair reward comparisons. We propose AV-GRPO, a modality-anchored online diffusion RL framework, and 5DAV, a decoupled, difficulty-controllable training dataset. AV-GRPO includes three key modules: (1) modality-anchored rollouts to disentangle learning signals and stabilize difficulty; (2) trajectory-locked frozen-tower optimization to reduce cost and reassign credit; (3) adaptive objectives and perturbation strengths tailored to modality-specific dynamics. This converts coupled multimodal preference learning into unimodal subproblems for precise reward attribution and better synchronization. Our 5DAV dataset decouples samples across five dimensions for systematic training. Experiments on JavisBench and VABench demonstrate AV-GRPO outperforms LTX-2.3 in generation quality, semantic alignment and cross-modal synchronization under LoRA and full fine-tuning. Ablations confirm our designs. Code and data: https://github.com/zhiyuxu03/AV-GRPO

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AV-GRPO: Modality-Anchored Decoupling Diffusion Reinforcement Learning for Joint Audio-Video Generation》所界定。 从摘要看，作者主要围绕 av-grpo、modality-anchored、decoupling 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on JavisBench and VABench demonstrate AV-GRPO outperforms LTX-2.3 in generation quality, semantic alignment and cross-modal synchronization under LoRA and full fine-tuning. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：av-grpo, modality-anchored, decoupling。 |

---
### 2. ARIS: Low-Resource Glass-Box Neural Source-Filter Synthesis for Phonetic Stimulus Manipulation

👤 **作者**: Yiran Ding, Wenwei Xu
🔗 **来源**: [https://arxiv.org/abs/2609.29923v1](https://arxiv.org/abs/2609.29923v1)

**摘要**
> Phoneticians often need to construct stimuli in which specific acoustic cues are precisely manipulated while preserving decent speech quality. Classical synthesis and modern neural methods sit along a trade-off between precise parametric control and high fidelity, and neural synthesis typically demands more data than phoneticians can easily obtain. We present ARIS (Analytic Resonant Interpretable Synthesis), a neural source-filter model that pairs neural parameter estimation with deterministic DSP synthesis. Every control is a coefficient of the synthesizer, so F0, formants and the glottal source can be edited directly. On five small single-speaker corpora in three languages, ARIS resynthesizes speech with quality comparable to WORLD and edits single parameters more accurately than Praat KlattGrid, with negligible crosstalk between cues. Compared with HiFi-Glot, pre-trained on a large corpus and fine-tuned on the same data, ARIS scores slightly lower on predicted naturalness but reproduces the recordings more faithfully and manipulates them more precisely. Audio samples: https://n1r.github.io/ARIS_nsf/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《ARIS: Low-Resource Glass-Box Neural Source-Filter Synthesis for Phonetic Stimulus Manipulation》所界定。 从摘要看，作者主要围绕 aris、low-resource、glass-box 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Classical synthesis and modern neural methods sit along a trade-off between precise parametric control and high fidelity, and neural synthesis typically demands more data than phoneticians can easily obtain. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：aris, low-resource, glass-box。 |

---
### 3. TEMA: Evidence-Grounded Temporal Question Answering in Multi-Turn Multi-Audio Dialogs

👤 **作者**: Kaidi Yang, Hualei Wang, Zhaohui Wang, Chenxuan Wang, Hong Liu, Xiangdong Wang
🔗 **来源**: [https://arxiv.org/abs/2609.30029v1](https://arxiv.org/abs/2609.30029v1)

**摘要**
> Multi-turn, multi-audio temporal question answering requires models to track target events across follow-up questions, recording switches, and historical references, recovering complete instances and their boundaries for temporal calculation and comparison. We propose TEMA, which connects event perception with evidence-based answering through Route, specifying the audio scope, and Span, describing all relevant intervals as conditional audio captions. We construct TEMA-Dialog with 40,704 dialogs and per-turn evidence and answer supervision, and TEMA-Bench for joint evaluation of evidence and final answers. Training combines temporal grounding initialization, full-dialog supervised fine-tuning, and completeness-first Span-only GRPO. Experiments on Qwen2.5-Omni and AF-Next show improved temporal question answering, particularly event localization and cross-audio comparison. Reinforcement learning applied solely to evidence further improves interval recovery and answer accuracy.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《TEMA: Evidence-Grounded Temporal Question Answering in Multi-Turn Multi-Audio Dialogs》所界定。 从摘要看，作者主要围绕 tema、evidence-grounded、temporal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on Qwen2.5-Omni and AF-Next show improved temporal question answering, particularly event localization and cross-audio comparison. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：tema, evidence-grounded, temporal。 |

---
### 4. A Native-Reference Phone-Class Geometry for Second-Language Pronunciation Analysis

👤 **作者**: Tina Raissi, Nhan Phan, Chenxiao Wang, Mikko Kurimo
🔗 **来源**: [https://arxiv.org/abs/2609.30075v1](https://arxiv.org/abs/2609.30075v1)

**摘要**
> Automatic speaking assessment systems can provide holistic proficiency scores, but often lack interpretable measures that characterize pronunciation quality. We propose a native-reference phone-class geometry for measuring second language (L2) pronunciation deviation without requiring pronunciation labels, read-aloud prompts, or matched recordings of the same text from native and L2 speakers. Given a native speech corpus, we average frame-level self-supervised representations for each context-dependent phone-class and use singular value decomposition (SVD) to derive a compact native-reference coordinate system. For each L2 utterance, we compute the corresponding averages and project them into the native-reference space. We then demonstrate that the distances between L2 and native-reference coordinates for matched phone-classes show consistent negative correlations with holistic speaking proficiency on the Dev subset of the Speak and Improve Corpus 2025 (Spearman's $ρ\!=\!-0.53$) and with pronunciation quality on the learner subset of the English Read by Japanese Students dataset ($ρ\!=\!-0.34$). These findings suggest that the proposed geometry captures acoustic-phonetic information relevant for proficiency rating while remaining applicable to spontaneous L2 speech without matched native recordings.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Native-Reference Phone-Class Geometry for Second-Language Pronunciation Analysis》所界定。 从摘要看，作者主要围绕 native-reference、phone-class、geometry 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We then demonstrate that the distances between L2 and native-reference coordinates for matched phone-classes show consistent negative correlations with holistic speaking proficiency on the Dev subset of the Speak and Improve Corpus 2025 (Spearman's $ρ\!=\!-0.53$) and with pronunciation quality on the learner subset of the English Read by Japanese Students dataset ($ρ\!=\!-0.34$). 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：native-reference, phone-class, geometry。 |

---
### 5. COSED: Setting the Bar for Open-Vocabulary Sound Event Detection

👤 **作者**: Florian Schmid, Sanjeel Parekh, Chi Ian Tang, Juan Azcarreta, Yijun Qian, Arnoldas Jasonas, Andrew Frederick Francl, Çağdaş Bilen
🔗 **来源**: [https://arxiv.org/abs/2609.30083v1](https://arxiv.org/abs/2609.30083v1)

**摘要**
> Open-vocabulary Sound Event Detection detects and temporally localizes acoustic events described by arbitrary text queries. Progress in this emerging field is hard to assess: recent methods report on disjoint task subsets under incompatible protocols without a benchmark spanning the acoustic domains and query types the task presents. We establish a comprehensive benchmark by assembling six temporally-annotated tasks: four with fixed class vocabularies over domestic, urban and mixed indoor/outdoor scenes, plus two free-text grounding tasks. We evaluate five recent methods on identical data and metrics under a label-space zero-shot criterion. Our benchmark demonstrates that no prior method is competitive across all six tasks. We then introduce COSED, which surpasses prior work on five out of six tasks while staying on par with the best method on the sixth, with margins of 12-33% on three of them. COSED is the only system in our comparison competitive on every task, and so generalizes across acoustic domains and query types better than prior work. We also provide a leave-one-out ablation study that isolates the sources of the performance benefits: scoping negatives to their corpus of origin (25.8%), combining closed- and open-world supervision (16.8%), and improving temporal processing (16.4%).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《COSED: Setting the Bar for Open-Vocabulary Sound Event Detection》所界定。 从摘要看，作者主要围绕 sound event detection 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our benchmark demonstrates that no prior method is competitive across all six tasks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：sound event detection。 |

---
### 6. Do Audio Language Models Hear and Read Distinctive Features Alike?

👤 **作者**: Yuanhao Chen, Peter Chin
🔗 **来源**: [https://arxiv.org/abs/2609.30167v1](https://arxiv.org/abs/2609.30167v1)

**摘要**
> Audio language models pass speech and text through a single decoder. We ask whether that decoder represents a distinctive feature in the same direction when a phoneme is heard and when it is read. For minimal pairs of phonemes differing in one feature, we take the offset between the two members' mean representations. Averaging those offsets gives a direction for each stream, and we measure the cosine between the two. Because the two streams already agree about arbitrary phoneme pairs, we compare every measure against a reference built from random pairings rather than against zero. We apply this to 6 models, 7 features and 15 languages from 11 families. Only voicing in the two Qwen2.5-Omni models exceeds that reference after correction for multiple testing, and the reference varies by a factor of seven between models. In three of the six models, voicing has one direction in audio across the 14 languages with enough minimal pairs to measure it, and every language pair agrees in two of them. The model family, not the model size, predicts which stream represents a feature.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Do Audio Language Models Hear and Read Distinctive Features Alike?》所界定。 从摘要看，作者主要围绕 audio、language、models 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We ask whether that decoder represents a distinctive feature in the same direction when a phoneme is heard and when it is read. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio, language, models。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
