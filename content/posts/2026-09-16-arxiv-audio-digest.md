<div align="center">

# 📰 Paper Claw

**2026-09-16**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-12 13:11:32 CST → 2026-09-16 13:23:17 CST |
| 📄 论文总数 | **55** 篇 |

### 分类统计

- **Speech LLM**: 5 篇
- **ASR**: 4 篇
- **TTS**: 7 篇
- **Enhancement**: 1 篇
- **SLU**: 1 篇
- **Paralinguistics**: 2 篇
- **Audio**: 35 篇

> 💡 今日共收录 55 篇新论文，主要分布在 Speech LLM 5, ASR 4, TTS 7, Enhancement 1, SLU 1, Paralinguistics 2, Audio 35。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Exploiting Speech LLM Representations for Multilingual and Cross-Lingual Parkinson's Disease Detection

👤 **作者**: Sarthak Giri, Zi Haur Pang, Tatsuya Kawahara
🔗 **来源**: [https://arxiv.org/abs/2609.14431v1](https://arxiv.org/abs/2609.14431v1)

**摘要**
> Speech Large Language Models (Speech LLMs) have shown strong performance across diverse tasks, yet their utility for pathological speech analysis remains underexplored. In this work, we investigate the effectiveness of internal representations from encoder and decoder components of Speech LLMs for Parkinson's Disease (PD) detection across multilingual and cross-lingual settings. Our findings reveal that encoder representations consistently outperform their decoder counterparts in most models and settings and that pathological cues may be progressively attenuated as audio representations are projected into the language model space. We further show that generative outputs are less reliable for clinical tasks compared to internal representations. To leverage information spread across multiple layers, we propose a Squeeze-and-Excitation (SE)-based dynamic layer aggregation framework, which surpasses best-layer selection in multiple experiments, suggesting that PD-relevant acoustic cues are distributed across transformer layers rather than concentrated in one.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Exploiting Speech LLM Representations for Multilingual and Cross-Lingual Parkinson's Disease Detection》所界定。 从摘要看，作者主要围绕 speech llm 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Speech Large Language Models (Speech LLMs) have shown strong performance across diverse tasks, yet their utility for pathological speech analysis remains underexplored. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech llm。 |

---
### 2. Bridging the Modality Gap in Long-Form Clinical Audio: A Comparative Study of Lightweight and Heavyweight End-to-End SOAP Generation

👤 **作者**: Ziyu Zhang, Mingchen Shao, Wenjie Tian, Tianlun Zuo, Longhao Li, Lei Xie
🔗 **来源**: [https://arxiv.org/abs/2609.14467v1](https://arxiv.org/abs/2609.14467v1)

**摘要**
> Automating clinical documentation from long-form doctor-patient conversations remains challenging for modern audio-language models. While cascaded ASR systems perform well, end-to-end (E2E) models often struggle with information loss and hallucinations on extended audio. For the BeTraC 2026 challenge, the ASLP team presents a fully E2E multimodal system that generates structured SOAP notes directly from audio, bypassing intermediate transcripts. We constructed a 1.41-million-sample multi-task corpus and applied a multi-stage pipeline: domain pre-training, supervised fine-tuning, and reward optimization. Evaluating the architecture under both Lightweight (3B) and Heavyweight (30B) constraints reveals that each training stage progressively enhances performance. Furthermore, scaling to 30B parameters substantially boosts concept extraction and summarization quality. Ultimately, our E2E systems consistently outperform representative cascaded ASR+LLM baselines, proving the efficacy of direct multimodal optimization for clinical documentation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Bridging the Modality Gap in Long-Form Clinical Audio: A Comparative Study of Lightweight and Heavyweight End-to-End SOAP Generation》所界定。 从摘要看，作者主要围绕 audio-language model、asr system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Ultimately, our E2E systems consistently outperform representative cascaded ASR+LLM baselines, proving the efficacy of direct multimodal optimization for clinical documentation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model, asr system。 |

---
### 3. Augmenting Large Audio-Language Models with Frame-Level Grounding for Fine-Grained Temporal Perception

👤 **作者**: Yanfeng Shi, Yan Song, Junhui Li, Tinggan Huang, Wu Guo, Haoyu Song, Ian McLoughlin
🔗 **来源**: [https://arxiv.org/abs/2609.15215v1](https://arxiv.org/abs/2609.15215v1)

**摘要**
> Large Audio-Language Models (LALMs) have substantially advanced general audio understanding, yet they remain limited in fine-grained temporal perception, particularly in precise event localization. Existing approaches primarily post-train LALMs to predict event boundaries as timestamp tokens. However, this generative formulation lacks explicit correspondence between the timestamp predictions and fine-grained acoustic evidence, limiting the precision and reliability of temporal localization. To address this issue, we augment the LALM with a dedicated frame-level grounding model while leveraging its semantic modeling capability to represent the event query. Specifically, the frozen LALM encodes the event query with audio as context, and the grounding model combines these query representations with fine-grained audio features to localize the target event at the frame level. Extensive experiments across diverse temporal grounding benchmarks demonstrate strong and consistent improvements over existing methods. Further evaluation shows that the grounding model can provide temporal evidence to support downstream reasoning.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Augmenting Large Audio-Language Models with Frame-Level Grounding for Fine-Grained Temporal Perception》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experiments across diverse temporal grounding benchmarks demonstrate strong and consistent improvements over existing methods. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-language model。 |

---
### 4. Reducing the Output-Mode Gap in Speech Language Models via Joint-Output On-Policy Distillation

👤 **作者**: Daxin Tan, Dehua Tao, Chengxi Deng, Hanlin Zhang, Xiao Chen
🔗 **来源**: [https://arxiv.org/abs/2609.15313v1](https://arxiv.org/abs/2609.15313v1)

**摘要**
> Autoregressive generation of interleaved text and acoustic tokens is a common approach to spoken-response generation in speech large language models. Although this design enables streaming generation with explicit textual guidance, generated acoustic tokens become part of the context for subsequent text predictions. Given identical speech inputs, we observe markedly lower answer accuracy for the internal text generated in speech-to-text-and-speech (S2TS) mode than for speech-to-text (S2T) responses. We term this discrepancy the \emph{output-mode gap} (OMG). To reduce OMG, we propose \emph{Joint-Output On-Policy Distillation} (JO-OPD), which distills the model's stronger S2T policy into joint generation using student-generated S2TS trajectories. At each text position, the S2T teacher provides soft targets from a text-only projection of the student's preceding outputs, while the student predicts from the corresponding full interleaved history. A preservation objective further regularizes native non-text predictions. Experiments on Step-Audio-2-mini and Baichuan-Audio-Instruct reveal OMG across two interleaved generation architectures. On Step-Audio-2-mini, JO-OPD reduces OMG from 42.87 to 16.26 percentage points on Spoken-MQA and from 29.72 to 13.04 points on speech-rendered GSM8K, with little change in S2T accuracy and substantially larger reductions than matched SFT baselines. ASR-based evaluation further shows a 7.49-point improvement in spoken-answer accuracy on Spoken-MQA.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Reducing the Output-Mode Gap in Speech Language Models via Joint-Output On-Policy Distillation》所界定。 从摘要看，作者主要围绕 speech language model、speech-to-text 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：ASR-based evaluation further shows a 7.49-point improvement in spoken-answer accuracy on Spoken-MQA. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model, speech-to-text。 |

---
### 5. LACE: Layer-Wise Compression for Dynamic Frame Rate Codecs

👤 **作者**: Thanapat Trachu, Samuele Cornell, William Chen, Shinji Watanabe
🔗 **来源**: [https://arxiv.org/abs/2609.17509v1](https://arxiv.org/abs/2609.17509v1)

**摘要**
> Neural audio codecs are a key component in speech language modeling. However, their high frame rates lead to long sequence lengths, increasing computational costs. Dynamic frame rate codecs mitigate this by reducing the effective frame rate using a compression step to merge multiple frames together. However, most prior methods either operate on single-codebook codecs or apply a single compression step before multi-layer quantization. This forces all quantization layers to share the same segmentation boundaries, despite the residual embeddings at different quantization layers exhibiting different rates of change over time. We propose LACE (Layer-Adaptive Codec Encoding), a dynamic frame rate codec that applies an independent compression step at each quantization layer, enabling layer-specific segmentation boundaries. To use LACE tokens in downstream text-to-speech (TTS), we further introduce union alignment and boundary anchor mechanisms to make durations consistent across layers while preserving compression benefits. Experiments on LibriTTS show that LACE offers a better rate-quality tradeoff than prior dynamic frame rate methods on the reconstruction task and improves TTS inference efficiency while maintaining competitive synthesis quality. Our code is released as part of the ESPnet3 codec recipe.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《LACE: Layer-Wise Compression for Dynamic Frame Rate Codecs》所界定。 从摘要看，作者主要围绕 speech language model、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on LibriTTS show that LACE offers a better rate-quality tradeoff than prior dynamic frame rate methods on the reconstruction task and improves TTS inference efficiency while maintaining competitive synthesis quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model, text-to-speech。 |

---
## 🏷️ ASR

### 1. Grounded in Sound: Reinforcement Learning with a Frozen Acoustic Judge to Curb ASR Insertion Hallucinations

👤 **作者**: Tingzhen Xiong, Rilin Chen, Weiwei Li, Wentao Zhang, Qicong Xie
🔗 **来源**: [https://arxiv.org/abs/2609.14455v1](https://arxiv.org/abs/2609.14455v1)

**摘要**
> When reinforcement learning (RL) is used for post-training automatic speech recognition (ASR), the reward almost always lives in the text space: it compares a hypothesis with the reference and never checks whether the hypothesis is supported by the audio. On highly regular speech this licenses a shortcut - guessing from a strong language prior rather than listening. Once the acoustics degrade, the shortcut runs unchecked and emits fluent but ungrounded words, i.e., insertion errors. We propose an acoustic-fidelity reward: a GRPO reward augmented with a separately pretrained, permanently frozen, non-autoregressive character-level wav2vec2-CTC acoustic judge, used strictly at training and absent at inference, where a single model decodes greedily. Trained on LibriSpeech and evaluated across a six-tier difficulty gradient including real AMI meeting speech (33,282 utterance-condition instances), the method reduces insertion errors by 28.3% on close-talking AMI-IHM and 22.3% on far-field AMI-SDM, while lowering WER on AMI-SDM from 35.89% to 34.71% and showing no detectable WER difference on the other five tiers, against a schedule-matched WER-GRPO baseline. The insertion reduction holds under a meeting-level clustered bootstrap. Four prespecified analyses support content-conditioned insertion calibration: output collapses 85-90% on unintelligible audio that preserves energy and voice activity; the gain is not recovered by the evaluated 32-best CTC rescoring configuration, yet RL internalizes it into a single greedy decoding run; and policy-only confidence yields lower insertion-AURC in all four evaluated settings. We frame this as a mechanism paper, demonstrated in one instantiation: a 7B speech LLM with a 0.3B CTC judge.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Grounded in Sound: Reinforcement Learning with a Frozen Acoustic Judge to Curb ASR Insertion Hallucinations》所界定。 从摘要看，作者主要围绕 speech llm、automatic speech recognition、wav2vec 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Trained on LibriSpeech and evaluated across a six-tier difficulty gradient including real AMI meeting speech (33,282 utterance-condition instances), the method reduces insertion errors by 28.3% on close-talking AMI-IHM and 22.3% on far-field AMI-SDM, while lowering WER on AMI-SDM from 35.89% to 34.71% and showing no detectable WER difference on the other five tiers, against a schedule-matched WER-GRPO baseline. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech llm, automatic speech recognition, wav2vec。 |

---
### 2. Neyshekar: An Open Persian Read-Speech Corpus for Automatic Speech Recognition

👤 **作者**: Ahmad Amirivojdan, Farzad Nadiri, Abolfazl Alizadeh, Shaghayegh Yaraghi
🔗 **来源**: [https://arxiv.org/abs/2609.14542v1](https://arxiv.org/abs/2609.14542v1)

**摘要**
> Neyshekar is presented as an open Persian read-speech corpus designed for coverage of both formal and informal language, named entities, and longer utterances. In version 6, 62,279 validated recordings totalling 99.02 hours are provided from 190 contributors, with 34,541 distinct recorded prompts. The prompt pool was assembled from human-written material, contextualised homographs, and reviewed language-model-generated text. Text entries were normalised with the shekar library, which supports both formal and informal Persian, and every submitted recording was reviewed against a common validation rubric. About 24% of released clips are classified as informal by an automatic classifier; these register labels are not human-validated. Item-level rater labels are provided for reproducible agreement estimation, opaque per-clip contributor identifiers make the speaker-disjoint partitioning auditable and support contributor-clustered uncertainty estimates, and a text-disjoint test subset is included for evaluation beyond previously seen prompts. Per-contributor recording load and reference-free signal quality are characterised for every released clip. Corpus characteristics are compared with Persian Common Voice under shared processing. Utility is assessed through two ASR architectures, three optimisation seeds, WER and CER, and independent evaluation on the public PSRB sample. Against duration-matched Common Voice training at approximately 32 hours, in-domain WER is reduced by 9.5 points for Whisper and 11.6 points for XLS-R, and by approximately eight points for both architectures on the independent PSRB sample. Transfer and mixture benefits are not consistently observed across architectures and training budgets. The corpus is released under CC0; code and data are made available through the project repository at https://github.com/amirivojdan/neyshekar.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Neyshekar: An Open Persian Read-Speech Corpus for Automatic Speech Recognition》所界定。 从摘要看，作者主要围绕 automatic speech recognition、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In version 6, 62,279 validated recordings totalling 99.02 hours are provided from 190 contributors, with 34,541 distinct recorded prompts. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, whisper。 |

---
### 3. Typhoon ASR Streaming: Steerable Low-Latency Thai Speech Recognition with Real-Time Shallow Fusion

👤 **作者**: Warit Sirichotedumrong, Tanawin Samutsin, Shah Faisal Wani, Sittipong Sripaisarnmongkol, Kunat Pipatanakul
🔗 **来源**: [https://arxiv.org/abs/2609.14991v1](https://arxiv.org/abs/2609.14991v1)

**摘要**
> Open Thai automatic speech recognition (ASR) is dominated by offline, Whisper-based models that read the whole utterance before transcribing, ruling out low-latency uses such as live captioning and voice agents. We present a deployable system for streaming Thai ASR that lets a user steer its vocabulary at decode time, without retraining. A widely used open Thai model, trained with full context, collapses when run as a true stream; we restore streaming with a cache-aware encoder, by converting it or adapting a natively streaming one, and add a shallow-fusion layer that re-ranks candidates inside the streaming decoder with a GPU n-gram language model and phrase boosting. Across two Thai benchmarks and two model sizes, the streaming models stay usable where the full-context model fails, cutting character error rate 4.3-4.5x at a one-second look-ahead while running faster than real time. Decode-time steering then lifts keyword recall from 16.6% to 20.7% at no accuracy cost and negligible overhead; most of the gain comes from an n-gram over ordinary training transcripts, which resolves the written form of code-switched words the model hears but spells inconsistently, with phrase boosting adding targeted control over rare domain terms.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Typhoon ASR Streaming: Steerable Low-Latency Thai Speech Recognition with Real-Time Shallow Fusion》所界定。 从摘要看，作者主要围绕 automatic speech recognition、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We present a deployable system for streaming Thai ASR that lets a user steer its vocabulary at decode time, without retraining. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, whisper。 |

---
### 4. Differentiable and Severity-invariant Discrete Tokens for Dysarthric Speech Recognition

👤 **作者**: Huimeng Wang, Xurong Xie, Mengzhe Geng, Haoning Xu, Jiajun Deng, Youjun Chen, Chengxi Deng, Xunying Liu
🔗 **来源**: [https://arxiv.org/abs/2609.16855v1](https://arxiv.org/abs/2609.16855v1)

**摘要**
> This paper proposes novel differentiable and severity-invariant (DSI) discrete token approaches that are not only tightly integrated with downstream dysarthric speech recognition tasks, but also minimise discrete token diversity across speech impairment severity groups. Experiments conducted on the UASpeech and TORGO corpora suggest that Conformer models trained using the DSI tokens outperform the comparable baseline HuBERT discrete/continuous features by statistically significant WER reductions of 2.22\%/0.78\% absolute (9.14\%/3.41\% relative) and 1.78\%/1.06\% absolute (18.43\%/11.86\% relative) on the two tasks, respectively. After system combination, the lowest WERs of 18.90\% and 6.38\% were obtained on UASpeech and TORGO. Phoneme-specific T-SNE visualizations show that severity-invariant regularization reduces severity-dependent variation by producing greater overlap and less distinct boundaries among severity-group distributions.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Differentiable and Severity-invariant Discrete Tokens for Dysarthric Speech Recognition》所界定。 从摘要看，作者主要围绕 conformer、hubert 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments conducted on the UASpeech and TORGO corpora suggest that Conformer models trained using the DSI tokens outperform the comparable baseline HuBERT discrete/continuous features by statistically significant WER reductions of 2.22\%/0.78\% absolute (9.14\%/3.41\% relative) and 1.78\%/1.06\% absolute (18.43\%/11.86\% relative) on the two tasks, respectively. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：conformer, hubert。 |

---
## 🏷️ TTS

### 1. Bridging Data, Reasoning, and Alignment: A Unified Framework for Context-Aware Instruction-Following TTS

👤 **作者**: Jingbin Hu, Luyu Wang, Wenjie Tian, Kangxiang Xia, Qirui Zhan, Haoyu Zhang, Yunxiang Chen, Houdun Liu, Lei Xie, Liumeng Xue
🔗 **来源**: [https://arxiv.org/abs/2609.14740v1](https://arxiv.org/abs/2609.14740v1)

**摘要**
> The ISCSLP 2026 CoT-TTS Challenge requires TTS systems to generate Chain-of-Thought (CoT) reasoning from dialogue history before synthesizing contextually appropriate speech. While the official baseline establishes a unified architecture, it remains constrained by limited contextual comprehension, weak instruction fidelity, and suboptimal audio quality. We present a systematic optimization pipeline to address these limitations. First, we develop a data process framework that cleans raw data via FullSubNet denoising, Qwen3-ASR re-transcription, and Qwen3.5-35B-A3B-based history-CoT consistency analysis, while distilling 545K high-fidelity instruction samples using Qwen3-TTS and Seed-VC under strict quality filtration. Second, we propose a Context-Aware Direct Preference Optimization (CA-DPO) method. By employing a cascaded filtering strategy, ASR prescreening, LLM tournament ranking, and speaker similarity verification, we obtain high-confidence preference pairs that significantly enhance holistic ``Context$\rightarrow$CoT$\rightarrow$Speech'' consistency during DPO training. Third, we establish an evaluation method featuring a 500-sample test set and an LLM-as-Judge framework to independently assess reasoning and execution fidelity. Experiments demonstrate that our system significantly outperforms the baseline across all objective and subjective metrics, validating our data governance and alignment strategies.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Bridging Data, Reasoning, and Alignment: A Unified Framework for Context-Aware Instruction-Following TTS》所界定。 从摘要看，作者主要围绕 tts system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments demonstrate that our system significantly outperforms the baseline across all objective and subjective metrics, validating our data governance and alignment strategies. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：tts system。 |

---
### 2. Cross-Lingual F5-TTS 2: A Simplified Framework for Language-Agnostic Voice Cloning

👤 **作者**: Qingyu Liu, Rixi Xu, Yushen Chen, Zhikang Niu, Haitao Li, Pengcheng Zhu, Bowen Zhang, Jian Zhao, Yunting Yang, Qinyuan Cheng, Xipeng Qiu, Berrak Sisman, Kai Yu, Xie Chen
🔗 **来源**: [https://arxiv.org/abs/2609.15184v1](https://arxiv.org/abs/2609.15184v1)

**摘要**
> Zero-shot text-to-speech (TTS) can clone a speaker's voice from a short audio prompt, yet most TTS systems still require the audio prompt transcript during inference. This dependency prevents cross-lingual voice cloning when the audio prompt transcript is unavailable, particularly for unseen languages. Cross-Lingual F5-TTS removes this dependency and enables transcript-free cross-lingual voice cloning, but it prepares its training data with forced alignment. Forced alignment is sensitive to boundary errors, and its cost grows as more languages are covered. Its speaking rate predictor is also unreliable at estimating duration when the audio prompt begins or ends with silence. In this paper, we present Cross-Lingual F5-TTS 2, a simplified framework for transcript-free cross-lingual voice cloning without forced alignment. Instead of using forced alignment to segment real utterances, we build same-speaker prompt and target pairs using a pretrained F5-TTS model and fine-tune the same model on these constructed pairs. This simplifies data preparation and preserves the acoustic modeling capability of the pretrained model, enabling adaptation with only a short fine-tuning stage. We further make the syllable-level speaking rate predictor robust to leading and trailing silence through silence-aware augmentation. Experiments show that Cross-Lingual F5-TTS 2 reaches higher speaker similarity than F5-TTS and Cross-Lingual F5-TTS while maintaining intelligibility. All related resources are publicly available.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Cross-Lingual F5-TTS 2: A Simplified Framework for Language-Agnostic Voice Cloning》所界定。 从摘要看，作者主要围绕 text-to-speech、tts system、acoustic model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that Cross-Lingual F5-TTS 2 reaches higher speaker similarity than F5-TTS and Cross-Lingual F5-TTS while maintaining intelligibility. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, tts system, acoustic model。 |

---
### 3. Acoustic Image Source Interpolation with Optimal Transport Barycenter

👤 **作者**: Yuyang Liu, Rumeshika Pallewela, Jesper Brunnström, Isabel Haasler, Filip Elvander
🔗 **来源**: [https://arxiv.org/abs/2609.15981v1](https://arxiv.org/abs/2609.15981v1)

**摘要**
> Room impulse responses can be estimated via the image source model (ISM) using the image source point cloud (ISPC) of a physical source. However, because the source movement changes the ISPC, estimating the ISPC at a new source position typically requires repeated acoustic measurements. We propose an optimal transport (OT) barycenter framework to interpolate the ISPC of a new source location from ISPCs of known sources. The method jointly estimates image-source associations and the ISPC at the new location. The OT ground cost exploits the property that the image sources undergo the same displacement as their physical sources. This approach is realized for both grid-based and support-free configurations. The support-free method addresses the resulting nonconvex joint estimation problem by alternating between identifying image-source associations across the ISPCs and refining the target image-source locations. This enables the interpolation of ISPCs without repeated measurements, facilitating efficient and flexible room-acoustic modeling.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Acoustic Image Source Interpolation with Optimal Transport Barycenter》所界定。 从摘要看，作者主要围绕 acoustic model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, because the source movement changes the ISPC, estimating the ISPC at a new source position typically requires repeated acoustic measurements. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic model。 |

---
### 4. Language Orthogonalization for Zero-Shot Cross-Lingual Audio Deepfake Detection

👤 **作者**: Minu Kim, Ji Sub Um, Hoirin Kim
🔗 **来源**: [https://arxiv.org/abs/2609.16458v1](https://arxiv.org/abs/2609.16458v1)

**摘要**
> Audio deepfake detectors need to transfer to languages absent from training, as multilingual speech synthesis outpaces labeled anti-spoofing resources. While detectors increasingly rely on self-supervised speech models (S3Ms), these backbones encode language-dependent structure that confounds spoof cues. We address this confound through language orthogonalization, a target-free ridge map that removes S3M variation projected onto continuous language-identification (LID) embeddings. Across six languages, six S3M backbones, and all Leave-N-Out settings, it consistently reduces EER across unseen languages. Cross-lingual EER correlates with LID-space distance, where orthogonalization yields larger gains for more distant transfers.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Language Orthogonalization for Zero-Shot Cross-Lingual Audio Deepfake Detection》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While detectors increasingly rely on self-supervised speech models (S3Ms), these backbones encode language-dependent structure that confounds spoof cues. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech synthesis。 |

---
### 5. The Evolving Bottleneck in Speech Generation: Interface Co-design and Staged Alignment from CosyVoice to Qwen-Audio-3.0-TTS

👤 **作者**: Qian Chen, Xiangang Li, Xiang Lv, Han Zhao, Tianyu Zhao
🔗 **来源**: [https://arxiv.org/abs/2609.16514v1](https://arxiv.org/abs/2609.16514v1)

**摘要**
> Speech synthesis systems are commonly narrated as a sequence of larger models, better tokenizers, and broader data. This technical retrospective offers a different account of the CosyVoice lineage, from CosyVoice through CosyVoice 2 and CosyVoice 3 to Qwen-Audio-3.0-TTS: progress came from repeatedly relocating the system's dominant bottleneck. Across the lineage, a stable decomposition separates an autoregressive language model that plans speech from a flow-matching model that renders acoustics. What changes is the contract between them. CosyVoice establishes supervised semantic tokens as a content-aligned interface; CosyVoice 2 makes that interface causally available for streaming and removes the utterance-level speaker embedding from the language model; CosyVoice 3 improves the learnability and coverage of the interface through multitask supervision, scaling, and differentiable reward optimization; and Qwen-Audio-3.0-TTS reduces token rate, conditions its renderer on continuous language-model hidden states instead of token embeddings, and progressively aligns the coupled system. We formalize this history through four interface dimensions---representation, ownership, availability, and gradient reach---and separate within-paper evidence from cross-paper comparison. The resulting synthesis connects discrete autoregressive, continuous non-autoregressive, hybrid, and continuous autoregressive speech-generation paradigms, and yields practical principles for diagnosing and training modular speech generators.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《The Evolving Bottleneck in Speech Generation: Interface Co-design and Staged Alignment from CosyVoice to Qwen-Audio-3.0-TTS》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：CosyVoice establishes supervised semantic tokens as a content-aligned interface; CosyVoice 2 makes that interface causally available for streaming and removes the utterance-level speaker embedding from the language model; CosyVoice 3 improves the learnability and coverage of the interface through multitask supervision, scaling, and differentiable reward optimization; and Qwen-Audio-3.0-TTS reduces token rate, conditions its renderer on continuous language-model hidden states instead of token embeddings, and progressively aligns the coupled system. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

---
### 6. Taming Long-form Text-to-Speech

👤 **作者**: Rongxiang Wang, Berkin Durmus, Aysegul Orhon, Eduardo Pacheco, Atila Orhon
🔗 **来源**: [https://arxiv.org/abs/2609.16989v1](https://arxiv.org/abs/2609.16989v1)

**摘要**
> Long-form text-to-speech (TTS) enables multi-turn conversations with consistent prosody and higher quality voice cloning from longer reference audio. Recent open-weights autoregressive TTS models such as Qwen3-TTS and VoxCPM2 attain state-of-the-art word error rate (WER) and speaker similarity (SIM) on short-form prompts but significantly deteriorate when used with long-form prompts. We propose Localized Attention-Constrained Inference (LACI), an inference-only method to detect TTS errors in near real-time, roll back to the error onset and regenerate with temporary guardrails, adding negligible computational overhead. Using LACI, we improve worst-of-N WER across 10 RNG seeds for Qwen3-TTS-0.6B from 35.2% to 3.4% on prompts longer than 1500 words, even surpassing its short-form reliability of 5.4\% on prompts with fewer than 500 words. To demonstrate the efficacy of LACI on voice cloning reliability, we propose a sliding-window version of the SIM metric that we call wSIM. wSIM exposes several novel failure patterns that are not captured by SIM. LACI improves worst-of-N wSIM from 0.01 to 0.47 on 120 seconds of reference audio while reducing the rate of catastrophic generations with WER above 30% from 26% to below 1%

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Taming Long-form Text-to-Speech》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Recent open-weights autoregressive TTS models such as Qwen3-TTS and VoxCPM2 attain state-of-the-art word error rate (WER) and speaker similarity (SIM) on short-form prompts but significantly deteriorate when used with long-form prompts. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech。 |

---
### 7. Self-Distilled Pronunciation and Accent Control for Neural Text-to-Speech

👤 **作者**: Shuhei Kato
🔗 **来源**: [https://arxiv.org/abs/2609.17234v1](https://arxiv.org/abs/2609.17234v1)

**摘要**
> Text-to-speech that reads raw text has no lexicon: a rare word is read as guessed. Remedies train a reading-and-accent channel on recorded speech or edit words one at a time from exemplars. We do neither. The frozen backbone reads a sentence containing a common word it already says correctly, and its own output then serves as the teacher for the same sentence, with that word replaced by a tagged, accented reading; this training pair is the whole idea. On Sarashina2.2-TTS, screened raters at Fleiss' kappa = 0.85 hear the prescribed accent on 0.89 of unseen words against 0.57 for kana, which cannot express one; kana wins no pair; naturalness is not measurably hurt. Moved untuned to autoregressive, diffusion, and encoder-decoder backbones, it transfers reading, 0.25 to 0.47 above no edit on 319 words, and on CosyVoice 2 accent on two words in three, but not on Irodori; the paper locates why.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Self-Distilled Pronunciation and Accent Control for Neural Text-to-Speech》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Remedies train a reading-and-accent channel on recorded speech or edit words one at a time from exemplars. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech。 |

---
## 🏷️ Enhancement

### 1. Directivity-Conditioned Low-Latency Neural Filtering for Speech Enhancement in Hearing Aids

👤 **作者**: Lennart Uphaus, André Merboldt, Markus Hofbauer, Timo Gerkmann
🔗 **来源**: [https://arxiv.org/abs/2609.15760v1](https://arxiv.org/abs/2609.15760v1)

**摘要**
> Latest advances in neural directional filtering show exceptional results in adapting the direction and shape of directivity patterns during the inference phase. However, in the existing methods for adapting directivity patterns during inference, important real-world constraints have been disregarded. Particularly for hearing devices, scenarios are often much more dynamic, microphone positions vary with head diameter and hearing aid placement, head-shadow effects occur, and strict latency constraints apply. In this work, we propose a novel low-latency (10 ms) deep neural network (DNN) taking the above requirements of hearing devices into account. As in recent work, we use feature-wise linear modulation (FiLM) to steer the directivity patterns during testing. To preserve the desired directivity pattern, a loss function is proposed that maintains the spectral cross-channel relationships. Interestingly, we are able to achieve similar results to methods with relaxed latency constraints.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Directivity-Conditioned Low-Latency Neural Filtering for Speech Enhancement in Hearing Aids》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Latest advances in neural directional filtering show exceptional results in adapting the direction and shape of directivity patterns during the inference phase. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

### 1. Exploring Multimodal Turn-Taking Cues in Face-to-Face Conversation using Voice Activity Projection

👤 **作者**: Willem Berner, Julio Cesar Cavalcanti, Kalle Åström, Gabriel Skantze
🔗 **来源**: [https://arxiv.org/abs/2609.14666v1](https://arxiv.org/abs/2609.14666v1)

**摘要**
> Turn-taking is a fundamental component of spoken interaction, and while humans naturally rely on both verbal and non-verbal signals, dialogue systems usually depend on audio cues alone. This paper investigates whether visual features from face-to-face conversations can enhance turn-taking prediction beyond what is achievable from audio-only. We extend the Voice Activity Projection (VAP) model, a self-supervised transformer-based model for predicting future voice activity, by incorporating visual features extracted from the large-scale Meta Seamless Interaction dataset of dyadic face-to-face conversations. The visual features include gaze direction, head movement, body and hand pose, and facial action units (FAU). For incorporating the visual features, we explore concatenation, cross-attention fusion, delta features, and trainable gating mechanisms. Results show that visual information improves performance over the audio-only baseline, with FAU being significantly more informative than other feature groups. Body and gaze features nevertheless contribute complementary information, as the model combining all features performs best. Furthermore, results indicate that performance on specific tasks varies depending on whether training and test data come from improvised (acted) or naturalistic (non-acted) conversations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「口语理解」方向，核心任务由题目《Exploring Multimodal Turn-Taking Cues in Face-to-Face Conversation using Voice Activity Projection》所界定。 从摘要看，作者主要围绕 dialogue system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper investigates whether visual features from face-to-face conversations can enhance turn-taking prediction beyond what is achievable from audio-only. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dialogue system。 |

---
## 🏷️ Paralinguistics

### 1. A New Transformer-Based Approach for Audio-Based Kinship Verification and a New Uncontrolled Mandarin Kinship Speech Dataset

👤 **作者**: Qiyang Sun, Langqing Zhang, Yupei Li, Björn Schuller
🔗 **来源**: [https://arxiv.org/abs/2609.14145v1](https://arxiv.org/abs/2609.14145v1)

**摘要**
> Kinship verification is a task involving determining whether two individuals share a first-order kin relation. To tackle this task, we propose CONVTRAP-TN, a new architecture for audio-based kinship verification, and conduct an ablation study on the proposed model. To the best of our knowledge, we are the first to apply the successful transformer architecture to the task of audio-based kinship verification. Furthermore, we also collect a custom speech dataset, ARKIN, which accurately reflects everyday recording conditions. We do this because only a few speech datasets with kinship labels currently exist, all of which either source extremely noisy in-the-wild data from the internet, or instruct speakers to record in specific environments. These settings fail to reflect real-world scenarios where users record on personal devices under unrestrained conditions. Additionally, we perform a series of preliminary baseline experiments on the collected dataset, including speaker verification and recognition, speech recognition, age estimation, and kinship verification, as well as cross-dataset kinship verification experiments to show that existing methods are not robust across datasets.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《A New Transformer-Based Approach for Audio-Based Kinship Verification and a New Uncontrolled Mandarin Kinship Speech Dataset》所界定。 从摘要看，作者主要围绕 speaker verification、age estimation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Additionally, we perform a series of preliminary baseline experiments on the collected dataset, including speaker verification and recognition, speech recognition, age estimation, and kinship verification, as well as cross-dataset kinship verification experiments to show that existing methods are not robust across datasets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speaker verification, age estimation。 |

---
### 2. Interpreting hierarchical organisation of speaker embeddings

👤 **作者**: Yanze Xu, Wenwu Wang, Mark D. Plumbley
🔗 **来源**: [https://arxiv.org/abs/2609.15203v1](https://arxiv.org/abs/2609.15203v1)

**摘要**
> Speaker recognition neural networks learn latent representations (i.e. speaker embeddings) from input utterances to recognise speaker identities. However, the internal mechanisms of these networks remain largely opaque, motivating research in explainable artificial intelligence (XAI) to understand them. Nevertheless, existing studies have analysed how speaker embeddings are organised, but rarely frame these analyses within XAI. Hence, this work proposes to explain and interpret the organisation of speaker embeddings from an XAI perspective. To this end, we apply a hierarchical clustering algorithm, Single-Linkage Clustering (SLINK), to analyse whether some speaker embeddings naturally form clusters with hierarchical relationships. The resulting hierarchical organisation (i.e. hierarchical clusters) is evaluated using the Cluster-Class Matching (CCM) method. Moreover, we propose a new method, termed Hierarchical Cluster-Class Matching (HCCM), to identify which hierarchical clusters best match individual semantic classes (e.g. male) and conjunctive semantic classes (e.g. UK & male), thereby interpreting the clusters using their matched classes. The matching degree is quantified using a new metric called the L-score, which makes imperfect matches diagnosable. HCCM's results show that hierarchical clusters analysed by SLINK are interpreted using different classes related to speaker identity, gender, and nationality, providing insight into semantics within the hierarchical organisation of our examined speaker embeddings.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Interpreting hierarchical organisation of speaker embeddings》所界定。 从摘要看，作者主要围绕 speaker recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：HCCM's results show that hierarchical clusters analysed by SLINK are interpreted using different classes related to speaker identity, gender, and nationality, providing insight into semantics within the hierarchical organisation of our examined speaker embeddings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speaker recognition。 |

---
## 🏷️ Audio

### 1. StepAudio 3 Realtime Technical Report

👤 **作者**: Bin Lin, Bo Zhao, Boyang Zhang, Boyong Wu, Chao Yan, Chen Geng, Chen Wu, Cheng Yi, Chengli Feng, Chenglin Zhu, Chengting Feng, Chengyuan Yao, Daijiao Liu, DanNi Wan, Daxin Jiang, Dongjian Li, Dongqing Pang, Fei Tian, Feng Tian, Future Li, Gang Yu, Guanglong Yang, Haoyang Zhang, Hongyuan Wang, Jia Peng, Jiahao Song, Jialong Xue, Jiamin Fan, Jiangjie Zhen, Jianzheng Gao, Jincheng Wen, Jinghua Liang, Jinglan Gong, Jun Chen, Li Xie, Liang Zhao, Lifang Zhang, Lingli Ji, Lun Cai, Min Xu, Peilin Li, Peng Yang, Pengfei Tan, Qingjian Lin, Qinxin Du, Ruijie Xiong, Runze Li, Shenghua Hu, Shengqian Qin, Shi Qiu, Siqi Tu, Siyi Zhou, Tianjiao Deng, Wanying Lu, Weiming Niu, Wen Sun, WenWen Qu, Xiangyu Zhang, Xianwei Zhang, Xiaosu Su, Xing Chen, Xinyu Liu, Xuerui Yang, Yan Wu, Yang Li, Yang Yang, Yechang Huang, Yibo Zhu, Yifan Zhang, Yinuo Yan, Youjun Chen, Yu Fu, Yu Luo, Yu Zhou, Yujie Chen, Yumang Wang, Yunzhou Ju, Yuxiang Yang, Yuxin Li, Yuxin Zhang, Zekai Liu, Zengwei Yao, Zhaoxin Yuan, Zhenwei Mou, Zhiquan Zhang, Zhiyue Wu, Zichao Li, Zichao Zhou, Ziqi Ren, Zixuan Wang
🔗 **来源**: [https://arxiv.org/abs/2609.14005v1](https://arxiv.org/abs/2609.14005v1)

**摘要**
> Realtime spoken interaction demands deep reasoning, prompt responses, and fluid turn-taking. We present StepAudio 3 Realtime, an audio-language foundation model organized around a continuous listen-converse-think-act loop. Deep Perception captures rich acoustic cues to interpret user intent, while Seamless Duplex models synchronized audio streams to handle pauses, backchannels, and interruptions naturally. Crucially, we resolve the tension between deep deliberation and latency via Think-While-Speaking, executing private reasoning in parallel with spoken delivery. In reasoning mode, StepAudio 3 reaches a 73.0 macro average on StepAudioChat. With Think-While-Speaking, it achieves dialogue and reasoning performance comparable to dedicated reasoning models while speaking in real time. Furthermore, an integrated Voice Agent handles asynchronous tool execution without disrupting the dialogue flow. StepAudio 3 Realtime achieves top-tier performance across key dimensions: an exceptional 90.6 on the MMSU benchmark, 98.9 Overall on the Artificial Analysis Full-Duplex Bench, and a 56.0% macro task-success rate on $τ$-Voice.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《StepAudio 3 Realtime Technical Report》所界定。 从摘要看，作者主要围绕 stepaudio、realtime、technical 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：With Think-While-Speaking, it achieves dialogue and reasoning performance comparable to dedicated reasoning models while speaking in real time. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：stepaudio, realtime, technical。 |

---
### 2. HARP: Agentic Hybrid Retrieval and Analysis for Long-Form Audio

👤 **作者**: Chin-Jou Li, Masao Someki, Woojeong Jin, Yashish M. Siriwardena, Tanmay Laud, Shanil Puri, Shinji Watanabe
🔗 **来源**: [https://arxiv.org/abs/2609.14116v1](https://arxiv.org/abs/2609.14116v1)

**摘要**
> Long-form audio analysis requires systems to localize and integrate evidence distributed across extended recordings. While existing work primarily retrieves semantic content through structured textual representations, many real-world queries depend on acoustic evidence that is better preserved in continuous representations or raw audio. We introduce HARP (Hybrid Audio Retrieval Pipeline), an agentic framework and benchmark for systematically studying retrieval and evidence representations in long-audio analysis. Hybrid retrieval combining keyword and vector search shows the most robust performance. When paired with both metadata and retrieved audio as evidence, average answer accuracy improves by around 10% and rationale accuracy by around 6% over single-modality retrieval and evidence. Fine-grained evaluation shows that answer accuracy alone overestimates system capability and that HARP mostly follows human performance trends across query types. These results highlight the importance of combining structured retrieval with flexible access to audio evidence and evaluating long-audio systems beyond answer accuracy.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《HARP: Agentic Hybrid Retrieval and Analysis for Long-Form Audio》所界定。 从摘要看，作者主要围绕 harp、agentic、hybrid 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Hybrid retrieval combining keyword and vector search shows the most robust performance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：harp, agentic, hybrid。 |

---
### 3. Robust Cross-Domain Speech-Based Alzheimer's Disease Detection via Iterative Adversarial Self-Training

👤 **作者**: Luqi Sun, Shreeram Suresh Chandra, Aurosweta Mahapatra, Emily Mower Provost, Brian MacWhinney, Berrak Sisman
🔗 **来源**: [https://arxiv.org/abs/2609.14139v1](https://arxiv.org/abs/2609.14139v1)

**摘要**
> As Alzheimer's disease (AD) has increasingly become a major global public health issue, speech-based AD detection has attracted widespread attention. However, most existing methods are trained and evaluated on a single dataset, often leading to severe cross-domain performance degradation due to reliance on dataset-specific artifacts rather than disease-related speech cues. In real-world applications, reliable Alzheimer's disease detection requires models that are robust to variations in recording environments, speakers and data collection conditions. To address this challenge, this paper adopts unsupervised domain adaptation to learn robust, domain-invariant feature representations in the absence of target-domain diagnosis labels. On this basis, a novel unsupervised domain adaptation method, Iterative Adversarial Self-Training (IAST), is proposed. Results demonstrate that IAST significantly improves the generalization ability and robustness under various cross-domain settings.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Robust Cross-Domain Speech-Based Alzheimer's Disease Detection via Iterative Adversarial Self-Training》所界定。 从摘要看，作者主要围绕 robust、cross-domain、speech-based 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results demonstrate that IAST significantly improves the generalization ability and robustness under various cross-domain settings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：robust, cross-domain, speech-based。 |

---
### 4. Inherited Heads: Audio language models track speakers with their text backbone's attention, and an attention-mass ranking retrieves a different set

👤 **作者**: Bojro Das
🔗 **来源**: [https://arxiv.org/abs/2609.14174v1](https://arxiv.org/abs/2609.14174v1)

**摘要**
> Asked to describe what one of six speakers in a recording talks about, audio language models describe the right one on 6 to 16% of trials, below the 16.7% a guess would give. Adding a fixed bias to the attention logits of a hundred heads, under a tenth of the model's and with no training, redirects the description to whichever speaker we choose, on 90.7% to 99.0% of trials. Those heads are largely not specific to audio. Rank the text-only language model an audio model was built from, or a released model of the same family, on a written version of the task, take its top hundred heads, and carry them over unchanged: they redirect the audio model on 80.8% to 95.0% of trials, with nothing about audio entering the selection. The audio and text head sets share 66 to 74 of 100 where chance would give about 20, and the shared part alone reproduces almost all of the steering. What that does not show is that sharing is what makes the heads work: an equal-sized draw from the same discovered hundred does nearly as well, and none of our three models separates the two explanations. A second finding concerns how such heads are found. Ranking heads by how much attention they place on the segment asked about, as an established score does, or by how much of their attention moves with the question, as a per-head normalised variant does, gives top hundreds that share 69, 37 and 4 heads across our three models. In Ultravox, where they share 4, the established score's heads leave output the judge cannot place on any segment on 69.7% of trials, against 40.0% with no intervention and 1.0% for the normalised variant. That is one arm of six; on the other five the established score steers above a random draw.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Inherited Heads: Audio language models track speakers with their text backbone's attention, and an attention-mass ranking retrieves a different set》所界定。 从摘要看，作者主要围绕 inherited、heads、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：What that does not show is that sharing is what makes the heads work: an equal-sized draw from the same discovered hundred does nearly as well, and none of our three models separates the two explanations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：inherited, heads, audio。 |

---
### 5. Modeling, Scaling, and Decoding: Optimizing Controllable Speech Generation with Nonverbal Vocalizations

👤 **作者**: Ziyu Zhang, Yun Chen, Taihui Wang, Hanzhao Li, Qicong Xie, Rilin Chen, Zhixian Zhao, Lei Xie
🔗 **来源**: [https://arxiv.org/abs/2609.14231v1](https://arxiv.org/abs/2609.14231v1)

**摘要**
> Controllable synthesis of nonverbal vocalizations (NVVs) is es- sential for natural and expressive speech, but remains challeng- ing due to their acoustic diversity and imbalanced distribution in existing corpora. To address these challenges, we develop an NVV-aware DiTAR system that models continuous speech latents, encodes the 16 target NVV categories as dedicated to- kens, and adapts stop prediction to distinguish mid-utterance vocalizations from utterance boundaries. Training begins with large-scale bilingual pre-training on diverse NVV speech, fol- lowed by continued supervised fine-tuning on a corpus en- hanced through targeted synthetic augmentation and frequency- aware rebalancing. At inference time, we select the acoustic prompt, tune the LM-guidance and noise-injection scales, and apply Best-of-N sampling with multi-metric selection to re- duce generation failures. The final system achieves an official weighted bilingual score of 62.786, ranking first in Mandarin, second in English, and first overall among participating systems in Track 2 of the ISCSLP 2026 NVVSpeech Challenge. Ab- lation studies show that targeted augmentation benefits under- represented NVV categories the most, while robust candidate selection requires balancing NVV correctness, lexical fidelity, and perceptual quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Modeling, Scaling, and Decoding: Optimizing Controllable Speech Generation with Nonverbal Vocalizations》所界定。 从摘要看，作者主要围绕 modeling、scaling、decoding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The final system achieves an official weighted bilingual score of 62.786, ranking first in Mandarin, second in English, and first overall among participating systems in Track 2 of the ISCSLP 2026 NVVSpeech Challenge. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：modeling, scaling, decoding。 |

---
### 6. AURA: Unified Multimodal Framework for Conversational Music Editing

👤 **作者**: Quoc-Huy Trinh, Minh-Van Nguyen, Debesh Jha
🔗 **来源**: [https://arxiv.org/abs/2609.14344v1](https://arxiv.org/abs/2609.14344v1)

**摘要**
> Instruction-guided music editors typically process each request independently, limiting their ability to support workflows in which users progressively refine a track. We introduce AURA, a unified multimodal framework for conversational music editing. AURA uses a multimodal large language model to interpret the complete dialogue history, an optional image, and reference audio, distilling the editing intent into compact concept tokens. A concept-to-audio module injects these tokens and frame-aligned reference features into a frozen MusicGen backbone, enabling precise edits while preserving unaffected content. AURA optimizes only 91M parameters while retaining 1.9B frozen backbone parameters. Experiments on Slakh2100 and MoisesDB demonstrate substantial improvements in edit correctness and content preservation over existing instruction-guided methods, including a 4-5 times reduction in FAD for out-of-domain addition and removal.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AURA: Unified Multimodal Framework for Conversational Music Editing》所界定。 从摘要看，作者主要围绕 aura、unified、multimodal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on Slakh2100 and MoisesDB demonstrate substantial improvements in edit correctness and content preservation over existing instruction-guided methods, including a 4-5 times reduction in FAD for out-of-domain addition and removal. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：aura, unified, multimodal。 |

---
### 7. Differentiable Digital Signal Processing Mixture Model-Guided Diffusion for Synthesis Parameter Estimation from Harmonic Sound Mixtures

👤 **作者**: Kengo Takemoto, Tomohiko Nakamura, Hiroshi Saruwatari
🔗 **来源**: [https://arxiv.org/abs/2609.14427v1](https://arxiv.org/abs/2609.14427v1)

**摘要**
> A differentiable digital signal processing (DDSP) autoencoder reconstructs a monophonic harmonic sound through three types of synthesis parameters: fundamental frequency, loudness, and timbre features. To handle mixtures of harmonic sounds within the DDSP approach, we have previously proposed a DDSP mixture model (DDSPMM). It represents a mixture as the sum of source signals synthesized by the decoders of pretrained DDSP autoencoders. Although DDSPMM enables direct estimation of synthesis parameters of each source from mixtures, it does not explicitly model temporal variations in the synthesis parameters and can produce excessive temporal fluctuations. In this paper, we propose a method for estimating synthesis parameters with temporally plausible trajectories by incorporating a denoising diffusion probabilistic model (DDPM) into the DDSPMM-based estimation. The DDPM is trained as a generative model of synthesis parameters. During estimation, the proposed method guides the DDPM reverse diffusion process with the reconstruction error between the observed mixture and the mixture synthesized by DDSPMM from the current estimates. Experiments on woodwind and string instrument ensembles showed that the DDPM-based regularization improves synthesis parameter estimation by imposing temporal plausibility on the estimated trajectories.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Differentiable Digital Signal Processing Mixture Model-Guided Diffusion for Synthesis Parameter Estimation from Harmonic Sound Mixtures》所界定。 从摘要看，作者主要围绕 differentiable、digital、signal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on woodwind and string instrument ensembles showed that the DDPM-based regularization improves synthesis parameter estimation by imposing temporal plausibility on the estimated trajectories. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：differentiable, digital, signal。 |

---
### 8. Parameter isolation with domain-specific experts for incremental audio classification

👤 **作者**: Jongyeon Park, Do-Hyeon Lim, Sang-won Park, Hong Kook Kim, Kyungdeuk Ko, Hyeongcheol Geum, Jeong Eun Lim
🔗 **来源**: [https://arxiv.org/abs/2609.14730v1](https://arxiv.org/abs/2609.14730v1)

**摘要**
> To successfully deploy a model in time-varying environments such as streaming data prediction and sensing control, domain-incremental learning (DIL) has attracted attention since it aims to adapt a previously trained model to newly arriving domains, while reserving knowledge from earlier domains without accessing their data. Incremental learning across domains can be regarded as a recurrent update, in which the current model is obtained by updating the model carried over from previous domains. Conventional DIL approaches that rely on domain-invariant feature learning and weight regularization gradually overwrite or constrain parameters learned in previous domains, leading to catastrophic forgetting. Instead, this paper proposes a new domain-specific parameter-isolation architecture that retains all past domains. The proposed architecture mitigates catastrophic forgetting through a full-order recurrent update, constructing a new expert using domain-specific data conditioned on all previously frozen models. To achieve this, we incorporate data-free generative replay to reconstruct previous-domain data and cross-domain feature generation to recover later expert features missing from earlier domain samples. Finally, we apply the proposed model architecture to domain-agnostic incremental learning for audio classification, as defined in the DCASE 2026 Challenge Task 7. Consequently, we achieve micro and macro accuracies of 78.4% and 78.9%, respectively, representing increases of 33 and 25 percentage points over the Challenge baseline. Ablation studies are conducted to examine the effectiveness of each processing component in terms of classification accuracy.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Parameter isolation with domain-specific experts for incremental audio classification》所界定。 从摘要看，作者主要围绕 audio classification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To achieve this, we incorporate data-free generative replay to reconstruct previous-domain data and cross-domain feature generation to recover later expert features missing from earlier domain samples. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio classification。 |

---
### 9. CCMAN: Cognitive Instability-Aware Cross-Modal Attention Network for Interpretable Temporal Biomarkers of Verbal Fluency Speech

👤 **作者**: Madhurananda Pahar, Caitlin Illingworth, Dorota Braun, Daniel Blackburn, Heidi Christensen
🔗 **来源**: [https://arxiv.org/abs/2609.14764v1](https://arxiv.org/abs/2609.14764v1)

**摘要**
> Early detection of cognitive decline from speech offers a scalable and non-invasive alternative to conventional clinical assessment. Verbal fluency tasks are particularly informative, but most automated approaches aggregate features across an entire recording, overlooking temporal speech dynamics. We propose the Cognitive Instability-Aware Cross-Modal Attention Network (CCMAN), a transfer learning framework that learns task-agnostic cognitive speech representations from multiple memory-probing tasks before fine-tuning on a minute-long semantic and phonemic verbal fluency task. CCMAN integrates semantic, acoustic, and linguistic information through bidirectional cross-attention, gated multimodal fusion, and transformer-based temporal modelling to derive interpretable biomarkers of cognitive decline. Experiments were conducted on 165.44 hours of speech from 843 participants (498 healthy controls, 245 with mild cognitive impairment, and 100 with dementia). CCMAN achieved Macro-F1 scores of 0.81 and 0.59 for binary and multiclass semantic fluency classification, and 0.77 and 0.53 for phonemic fluency, consistently outperforming strong static and temporal baselines. Statistical analyses showed that semantic drift variance and pause variance, but not mean semantic drift, were significantly elevated in both MCI and dementia relative to healthy controls, while pause duration increased progressively over the task with the steepest slope in dementia, supporting global and progressive temporal speech instability as interpretable biomarkers. Evaluation on the independent PROCESS-2 benchmark further demonstrated the generalisability of the proposed framework, improving the baseline Macro-F1 by up to 9%. These findings support temporal speech instability as a dynamic speech biomarker for robust, interpretable, and generalisable early detection of cognitive decline.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CCMAN: Cognitive Instability-Aware Cross-Modal Attention Network for Interpretable Temporal Biomarkers of Verbal Fluency Speech》所界定。 从摘要看，作者主要围绕 ccman、cognitive、instability-aware 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：CCMAN achieved Macro-F1 scores of 0.81 and 0.59 for binary and multiclass semantic fluency classification, and 0.77 and 0.53 for phonemic fluency, consistently outperforming strong static and temporal baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：ccman, cognitive, instability-aware。 |

---
### 10. POLARIS: Training-Free Audio Fingerprinting with Saliency-Based Landmarks and Delaunay Grouping

👤 **作者**: Jiheng Li
🔗 **来源**: [https://arxiv.org/abs/2609.14820v1](https://arxiv.org/abs/2609.14820v1)

**摘要**
> This work presents POLARIS, a training-free audio fingerprinting system that selects landmarks from a locally normalized saliency field and groups them into sparse fingerprints using Delaunay triangulation. To deal with query distortion, POLARIS adds fingerprints from two-hop Delaunay neighborhoods only at query time, without enlarging the reference index. An adaptive configuration applies this expansion only when the original fingerprints do not produce a confident match. We evaluate POLARIS on synthetic distortions from the public PEX Hard Medium benchmark, excluding queries with pitch or tempo shifts, and on a new benchmark of real re-recorded music. POLARIS achieves the best performance among the evaluated training-free methods on both benchmarks. On the real recordings, its adaptive configuration also outperforms the neural NMFP baseline with a comparable measured query time and a smaller logical reference payload. Code, dataset, and instructions for reproducing all experiments are available at https://github.com/JihengLi/POLARIS.git.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《POLARIS: Training-Free Audio Fingerprinting with Saliency-Based Landmarks and Delaunay Grouping》所界定。 从摘要看，作者主要围绕 polaris、training-free、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：POLARIS achieves the best performance among the evaluated training-free methods on both benchmarks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：polaris, training-free, audio。 |

---
### 11. Tracing the Origins: Legacy Codec Identification in Neural Audio Transcoding

👤 **作者**: Wonje Heo, Shinee Youn, Yooshin Kim, Chuck Chae, Donghoon Shin
🔗 **来源**: [https://arxiv.org/abs/2609.14916v1](https://arxiv.org/abs/2609.14916v1)

**摘要**
> Residual Vector Quantization (RVQ)-based neural audio codecs (NACs) enable high-fidelity audio distribution at unprecedentedly low bitrates through discrete token-based representations. However, this shift disrupts traditional forensics, as non-linear neural transcoding obscures the underlying traces of legacy compression. This study defines the forensic gap and proposes a Transformer-based framework designed to leverage the hierarchical and temporal dependencies inherent in RVQ sequences. By modeling inter-layer causal relationships and dynamic forensic significance, our model effectively disentangles superimposed artifacts from legacy-to-neural transcoding. Experimental results achieve 97%+ accuracy for codec identification and robust joint identification performance across 32-128 kbps. These results demonstrate that traditional codec traces persist even after neural transcoding, supporting the feasibility and necessity of neural-codec-aware audio forensics.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Tracing the Origins: Legacy Codec Identification in Neural Audio Transcoding》所界定。 从摘要看，作者主要围绕 tracing、origins、legacy 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results achieve 97%+ accuracy for codec identification and robust joint identification performance across 32-128 kbps. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：tracing, origins, legacy。 |

---
### 12. CAL-MOS: Bridging Layers with Adapters for Robust MOS Prediction Across Speech Foundation Models

👤 **作者**: Alef Iury Siqueira Ferreira, Pedro Lustosa Rege Botelho, Fernanda Silva, Daniel Casanova, Rafael Faustino, Frederico Oliveira, Arlindo Galvão Filho, Anderson da Silva Soares
🔗 **来源**: [https://arxiv.org/abs/2609.14956v1](https://arxiv.org/abs/2609.14956v1)

**摘要**
> Speech Quality Assessment (SQA) is essential for modern speech technologies, and recent non-intrusive SQA predictors increasingly rely on Speech Foundation Models (SFMs). However, because SFMs expose representations from many layers, it remains unclear which depths are most informative for MOS prediction and how multi-layer information should be combined reliably across backbones and datasets. We benchmark ten SFMs on four MOS datasets under three regimes: full fine-tuning, last-layer probing with a frozen encoder, and naive cross-layer weighted aggregation. We find that the best layer is strongly backbone- and dataset-dependent, and that naive weighted fusion can be unstable across settings. We further evaluate a layer-calibrated aggregation variant that applies per-layer adapters before pooling, which improves the robustness of multi-layer fusion and narrows the gap to full fine-tuning while keeping the backbone frozen.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CAL-MOS: Bridging Layers with Adapters for Robust MOS Prediction Across Speech Foundation Models》所界定。 从摘要看，作者主要围绕 cal-mos、bridging、layers 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We further evaluate a layer-calibrated aggregation variant that applies per-layer adapters before pooling, which improves the robustness of multi-layer fusion and narrows the gap to full fine-tuning while keeping the backbone frozen. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：cal-mos, bridging, layers。 |

---
### 13. Learned Bow Control on a Measured Bowed-String Model: a Revised Minimum-Bow-Force Law, a Recurrent Controller, and the Domain of a Supervision Ceiling

👤 **作者**: Homayoon Beigi, Grace Conneely
🔗 **来源**: [https://arxiv.org/abs/2609.14990v1](https://arxiv.org/abs/2609.14990v1)

**摘要**
> A finite-difference bowed-string model with implicitly resolved Stribeck friction is presented, with a regime diagnostic, the Schelleng bow-force limits on four strings, and a comparison of learned bow controllers. Implicit resolution is necessary, and quantitatively so: a lagged contact force cannot capture the string on a discrete grid, so no stick phase forms at any bow force. With friction, impedance and quality factor taken from published measurement rather than fitted, all four strings return a stick fraction of 89.1% against an ideal 90%. Schelleng's maximum bow force is recovered on every string. The minimum is not: it follows $Z v_b β^{-1}$ rather than the predicted $Z^2 v_b β^{-2}$, reducing both squared dependences to first powers. Six controllers at matched capacity, over four strings and twenty seeds each, place a gated recurrent network ahead of a feedforward one, by most under a mid-stroke disturbance. The feedforward network completes more strokes only from a start the model's own playability map places outside the Helmholtz region. A minimal gated variant fails because gates computed from the input alone cannot clear a latched state. Training loss selects neither the capacity nor the context length, and no learned controller improves on the lookup rule that generated its labels. That bound has a domain. Regressing the controller's score on the rule's gives a slope of 0.32, more than ten standard errors below unity, so the controller overtakes the rule where the rule fails and is bounded by it where it holds. Under a rigid finger stop the plant is provably invariant, so transfer loss between pitches belongs to the controller alone and is traced to one feature. A regime classifier without a stick test labels small-amplitude periodic slipping as Helmholtz motion, and a harmonicity measure rates a string the bow never grips above Helmholtz motion.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Learned Bow Control on a Measured Bowed-String Model: a Revised Minimum-Bow-Force Law, a Recurrent Controller, and the Domain of a Supervision Ceiling》所界定。 从摘要看，作者主要围绕 learned、control、measured 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Training loss selects neither the capacity nor the context length, and no learned controller improves on the lookup rule that generated its labels. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：learned, control, measured。 |

---
### 14. Rethinking Procedural Audio Pre-training: Source Scaling and Objective Adaptation

👤 **作者**: Jiajun Peng, Fengrui Liu, Xinyu Liu, Feng Liu
🔗 **来源**: [https://arxiv.org/abs/2609.15067v1](https://arxiv.org/abs/2609.15067v1)

**摘要**
> Procedural audio has emerged as a viable source for transferable audio representation learning, but its design principles remain unclear.We revisit two questions: how a procedural source should be scaled, and whether training choices developed on natural audio should transfer unchanged to procedural data.Using a controlled source, we separate scale into formula-class coverage C and within-class rendering diversity I.Experiments with FDSL and AudioMAE show that these two forms of scale provide different benefits and depend on the learning formulation and downstream task. A matched AudioMAE study further shows that procedural audio favors low mask ratios (10%--25%), whereas AudioSet-28K favors 50%--75%. Shared-codebook analysis reveals lower patch diversity and stronger temporal predictability in procedural audio. These results motivate source-aware procedural pre-training, where source scaling and learning configuration are considered jointly.Code is available at https://github.com/Cross-Innovation-Lab/Formula-Bank.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Rethinking Procedural Audio Pre-training: Source Scaling and Objective Adaptation》所界定。 从摘要看，作者主要围绕 rethinking、procedural、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Procedural audio has emerged as a viable source for transferable audio representation learning, but its design principles remain unclear.We revisit two questions: how a procedural source should be scaled, and whether training choices developed on natural audio should transfer unchanged to procedural data.Using a controlled source, we separate scale into formula-class coverage C and within-class rendering diversity I.Experiments with FDSL and AudioMAE show that these two forms of scale provide different benefits and depend on the learning formulation and downstream task. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：rethinking, procedural, audio。 |

---
### 15. Word Timestamps and Speaker Attribution with a Non-Autoregressive LLM

👤 **作者**: Zvi Kons, Avihu Dekel, Hagai Aronowitz, Vishal Sunder, Ron Hoory
🔗 **来源**: [https://arxiv.org/abs/2609.15218v1](https://arxiv.org/abs/2609.15218v1)

**摘要**
> Timestamps and speaker attribution are useful additions to speech recognition, creating a rich text transcript. This information can either be extracted during transcription or aligned to a given transcript. In this paper we present models that add timestamps and speaker information to a given transcript using a non-autoregressive LLM-based architecture. Compared to an autoregressive model built from similar components, the models are more accurate and annotate a given transcript one to two orders of magnitude faster. Compared to other models, our models achieve state-of-the-art timestamp accuracy and the best cpWER for speaker attribution.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Word Timestamps and Speaker Attribution with a Non-Autoregressive LLM》所界定。 从摘要看，作者主要围绕 word、timestamps、speaker 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Compared to other models, our models achieve state-of-the-art timestamp accuracy and the best cpWER for speaker attribution. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：word, timestamps, speaker。 |

---
### 16. MAST: Label-Efficient, Robust, and Generalizable Sound Detection for Biodiversity Monitoring via Masked Audio Pretraining and Self-Training

👤 **作者**: Tianyi Xu, Daniel Pimentel-Alarcón, Zuzana Buřivalová, Claudia Solís-Lemus
🔗 **来源**: [https://arxiv.org/abs/2609.15221v1](https://arxiv.org/abs/2609.15221v1)

**摘要**
> Passive acoustic monitoring can measure biodiversity at larger scales, but time--frequency annotation of animal vocalizations is expensive, site-specific, and difficult to sustain at scale. We present a label-efficient sound detection framework that combines masked audio pretraining with a lightweight detector on mel spectrograms, then further improves robustness through iterative self-training on unlabeled audio. We first pretrain a ViT-based encoder on unlabeled recordings via masked reconstruction and transfer the encoder to a detection backbone. To better separate animal sounds from confounding background, we add a box-level contrastive loss that pulls matched event regions together while pushing noisy negatives apart. We then apply a two-stage pseudo-labeling curriculum to exploit large unlabeled pools without additional annotation. We evaluate the performance on two ecologically distinct domains: tropical rainforest soundscapes (Indonesia) and bird vocalizations in Mediterranean habitats (Spain). On both domains, masked audio pretraining and contrastive learning consistently improve time--frequency detection under temporal and cross-site distribution shift, and self-training yields further gains in out-of-distribution performance. On the rainforest domain, MAST with self-training achieves +0.22 mAP and +0.24 F1 over the strongest baseline under cross-site shift. On the bird domain, self-training achieves +0.12 mAP and +0.10 F1 over the strongest baseline under cross-site shift. Overall, our results show that MAST can effectively extend self-supervised audio representations from clip-level tasks to robust box-level localization across diverse bioacoustic settings, providing a practical path for biodiversity monitoring with limited labels.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MAST: Label-Efficient, Robust, and Generalizable Sound Detection for Biodiversity Monitoring via Masked Audio Pretraining and Self-Training》所界定。 从摘要看，作者主要围绕 mast、label-efficient、robust 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We present a label-efficient sound detection framework that combines masked audio pretraining with a lightweight detector on mel spectrograms, then further improves robustness through iterative self-training on unlabeled audio. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：mast, label-efficient, robust。 |

---
### 17. Generating the Unheard: Phylogeny-Guided Latent Generation for Ancestral Sound Reconstruction

👤 **作者**: Tianyi Xu, Shrinaath Narasimhan, Evan Gorstein, Santiago Perea, Yunyi Shen, Claudia Solís-Lemus
🔗 **来源**: [https://arxiv.org/abs/2609.15240v1](https://arxiv.org/abs/2609.15240v1)

**摘要**
> What did an ancestral bird species sound like? Existing ancestral state reconstruction methods can infer low-dimensional traits such as morphological characters at internal nodes of a phylogenetic tree, but no one has tried to produce rich perceptual signals such as audio. Some of the challenges include inferred representations that are either too low-dimensional to decode or lie in non-generative feature spaces, so no method to date can produce ancestral audio. We introduce the first framework that generates plausible ancestral vocalizations. Our pipeline encodes bird recordings into a VAE latent space, learns a low-dimensional trait projection aligned with phylogenetic distances, performs ancestral inference in this trait space, and recovers decodable latents through an anchored inverse lift before emitting novel waveforms for each ancestral node. Because the entire pipeline stays within a decodable latent space, every internal node receives a genuinely new audio output representing plausible intermediate ancestral sounds unavailable to retrieval-based alternatives. Experiments on two phylogenetically distant bird clades, 21-species Tyrannidae and 19-species Paridae, show that our method is the only approach that simultaneously achieves genuine generation, phylogenetic consistency, and naturalistic audio quality across both datasets.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Generating the Unheard: Phylogeny-Guided Latent Generation for Ancestral Sound Reconstruction》所界定。 从摘要看，作者主要围绕 generating、unheard、phylogeny-guided 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on two phylogenetically distant bird clades, 21-species Tyrannidae and 19-species Paridae, show that our method is the only approach that simultaneously achieves genuine generation, phylogenetic consistency, and naturalistic audio quality across both datasets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：generating, unheard, phylogeny-guided。 |

---
### 18. BioDCASE: Active Learning for Bioacoustics

👤 **作者**: Ben McEwen, Rupa Kurinchi-Vendhan, Shiqi Zhang, Lukas Rauch, Marek Herde, Sara Beery
🔗 **来源**: [https://arxiv.org/abs/2609.15255v1](https://arxiv.org/abs/2609.15255v1)

**摘要**
> Ecological monitoring increasingly relies on machine learning models, whose performance depends on the quality and quantity of labelled data. However, obtaining these labels is costly, particularly in passive acoustic monitoring, where vast amounts of data are collected but only a small proportion can feasibly be annotated. Active learning addresses this bottleneck by prioritizing which samples should be labelled. However, progress is difficult to measure, because published methods are evaluated under different models, budgets, evaluation metrics and datasets. To address this challenge, we present the 2026 Active Learning for Bioacoustics BioDCASE challenge: a systematic evaluation of sampling methods designed to identify effective AL strategies. Participant methods were evaluated across four subsets composed of terrestrial and marine data. Across ten proposed sampling methods from seven teams, the top-ranked method achieved an area under the learning curve 26.4 % higher than random sampling at the same annotation budget, averaged over four data subsets. Significant variation in performance was observed across subsets, with the top-performing submission achieving a 67.1 % gain for the HSN subset over random sampling and a gain of 8 % for the ATBFL subset. Top-ranking submissions combined multiple acquisition signals, and diversity-based selection outperformed pure uncertainty sampling. Furthermore, there is evidence that transitioning from diversity-based to uncertainty-based selection and explicitly reducing redundancy within acquisition batches improve model training. There is also initial evidence that larger acquisition batch sizes may be increasingly beneficial later in the labelling process.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《BioDCASE: Active Learning for Bioacoustics》所界定。 从摘要看，作者主要围绕 biodcase、active、learning 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across ten proposed sampling methods from seven teams, the top-ranked method achieved an area under the learning curve 26.4 % higher than random sampling at the same annotation budget, averaged over four data subsets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：biodcase, active, learning。 |

---
### 19. MUUNRiver-Bench: Diagnosing Relation-Dependent Music Retrieval with Multimodal Instructions

👤 **作者**: Zhancheng Guo, Congren Dai, Shangda Wu, Jianhuai Hu, Danni Zhao, Xiaobing Li, Maosong Sun
🔗 **来源**: [https://arxiv.org/abs/2609.16090v1](https://arxiv.org/abs/2609.16090v1)

**摘要**
> Music retrieval is relation-dependent: given a reference track, a listener may seek its style with a new theme, a cover, or a comparable voice, and these intents demand contradictory rankings. We present MUUNRiver-Bench, a diagnostic benchmark whose reference-audio queries use natural-language instructions to define relevance. A pipeline combining expert genre priors, LLM-generated prompts and lyrics, synthesis, and expert review yields 3,440 tracks spanning 13 genres and 116 sub-genres, and seven tasks: similar-music, style-preserving lyric-rewriting, lyric-preserving style-rewriting, cover, vocal-timbre, isolated-vocal, and segment retrieval. Across six models in eight configurations, task-wise rank reversals reveal complementary biases: acoustic encoders favour local identity, whereas text-aligned encoders favour semantic relations. Frozen encoders diagnose default similarity preferences; instruction-aware and audio-text fusion systems provide exploratory tests of textual conditioning, with neither simple fusion scheme consistently improving its backbone

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MUUNRiver-Bench: Diagnosing Relation-Dependent Music Retrieval with Multimodal Instructions》所界定。 从摘要看，作者主要围绕 muunriver-bench、diagnosing、relation-dependent 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Frozen encoders diagnose default similarity preferences; instruction-aware and audio-text fusion systems provide exploratory tests of textual conditioning, with neither simple fusion scheme consistently improving its backbone 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：muunriver-bench, diagnosing, relation-dependent。 |

---
### 20. Listening for Airway Stenosis: A Foundation Model-Based Method for Rapid and Accessible Detection

👤 **作者**: Jean Groeninger, Zihao Zhao, Juliana de Castilhos, Sven Nebelung, Daniel Truhn
🔗 **来源**: [https://arxiv.org/abs/2609.15453v1](https://arxiv.org/abs/2609.15453v1)

**摘要**
> Airway stenosis can cause severe respiratory complications, yet its detection often relies on specialized examinations and medical imaging. This study explores the potential of acoustic AI for rapid and accessible airway stenosis detection using readily acquired patient voice recordings. We systematically investigate whether acoustic foundation models (AFMs) can extract acoustic representations associated with airway stenosis-related speech patterns. Experiments are conducted on a cohort of 748 participants from the Bridge2AI-Voice dataset, 134 with airway stenosis and 614 without. The best-performing model achieves an AUROC of 0.952 and an accuracy of 0.924 (means over five-fold cross-validation), highlighting the potential of AFMs to transfer beyond general-purpose speech applications to clinical diagnostic tasks. Further analysis reveals that the model primarily relies on connected-speech recordings rather than isolated acoustic tasks, such as sustained phonation and breathing. Overall, these results suggest that voice-based acoustic AI could complement existing diagnostic workflows by enabling rapid, low-burden, and widely accessible screening for airway stenosis.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Listening for Airway Stenosis: A Foundation Model-Based Method for Rapid and Accessible Detection》所界定。 从摘要看，作者主要围绕 listening、airway、stenosis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The best-performing model achieves an AUROC of 0.952 and an accuracy of 0.924 (means over five-fold cross-validation), highlighting the potential of AFMs to transfer beyond general-purpose speech applications to clinical diagnostic tasks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：listening, airway, stenosis。 |

---
### 21. Building a Dataset for Music Sample Identification

👤 **作者**: R. Oguz Araz, Xavier Lizarraga, Xavier Serra, Dmitry Bogdanov
🔗 **来源**: [https://arxiv.org/abs/2609.15465v1](https://arxiv.org/abs/2609.15465v1)

**摘要**
> Sample identification (SI) is the task of matching an element of a musical work to its musically transformed versions used to create new works. The task has received little attention and lacks large-scale publicly available data. In this work, we mine sampling annotations from a music database and split them for training and evaluation. The resulting dataset is nearly three orders of magnitude larger than the existing SI benchmarks, with training, validation, and test sets of 114 k, 6 k, and 10 k tracks. We find that naively splitting the annotations places the same tracks in different sets. To avoid this, we construct a graph from the annotations and split it over connected components. We further find that a single mega-component contains half of the annotations, making component-wise splitting incompatible with balanced splits; we trim it, yielding a leakage-aware pipeline. We share the dataset for non-commercial scientific research purposes only and make the data-analysis and splitting code publicly available. We hope that our work fosters research on SI.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Building a Dataset for Music Sample Identification》所界定。 从摘要看，作者主要围绕 building、dataset、music 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The task has received little attention and lacks large-scale publicly available data. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：building, dataset, music。 |

---
### 22. OLAC: An Overlapped Lossless Audio Codec in the Time-Domain with MDCT Compatibility

👤 **作者**: Jean-Marc Valin
🔗 **来源**: [https://arxiv.org/abs/2609.15616v1](https://arxiv.org/abs/2609.15616v1)

**摘要**
> Lossless audio coding is a highly mature field of research, with limited potential for significant improvements in pure compression performance. However, emerging real-time wireless applications increasingly require dynamic transitions between lossy and lossless coding to adapt to fluctuating network capacities. Existing standalone lossless codecs cannot achieve this seamless switching without discontinuity. In this paper, we propose a lossless codec based on time-domain aliasing cancellation (TDAC) that can match the overlap in the CELT mode of the Opus codec. This allows the transition between lossy and lossless coding to be achieved without discontinuity or the transmission of redundant information. We show that the proposed codec still achieves state-of-the-art lossless compression without being penalized by its use of TDAC.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《OLAC: An Overlapped Lossless Audio Codec in the Time-Domain with MDCT Compatibility》所界定。 从摘要看，作者主要围绕 olac、overlapped、lossless 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Lossless audio coding is a highly mature field of research, with limited potential for significant improvements in pure compression performance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：olac, overlapped, lossless。 |

---
### 23. Graph Attention Design Choices Matter: A Controlled Study of LoRA-Adapted Audio Anti-Spoofing

👤 **作者**: Haoyu Wang, Jing Yang, Chenyu Liu, Yushan Du, Yifan Liao, Ningning Pan, Gongping Huang, Yu Zhao, Gang Li, Jian Luan
🔗 **来源**: [https://arxiv.org/abs/2609.15650v1](https://arxiv.org/abs/2609.15650v1)

**摘要**
> Audio anti-spoofing systems increasingly combine self-supervised learning, parameter-efficient fine-tuning, and graph-attention-based backends. However, performance gains in such systems are often entangled with concurrent changes in the backbone, fine-tuning strategy, and training protocol, making the independent contribution of graph attention design difficult to isolate. To address this issue, we conduct a systematic controlled study of the graph attention layer under a unified experimental setting. We decompose the layer into three independently testable design dimensions: scoring symmetry, temperature learnability, and routing granularity. These are instantiated as a concat-based scoring branch, a LearnT branch with learnable temperature, and a multi-temperature routing branch, respectively. Each dimension is implemented as an independently gated residual branch, enabling the evaluation of both individual variants and their combinations under the same experimental setting. Experiments on five evaluation sets with five random seeds show that the LearnT branch achieves the best average equal error rate (EER), yielding a 16.1% relative improvement over the baseline. In contrast, the multi-temperature routing branch does not improve average performance on its own, but substantially reduces cross-seed standard deviation when combined with the concat-based scoring branch. Moreover, two individually effective branches degrade performance when used together, resulting in a 25.6% relative deterioration compared with the baseline. This finding reveals strong non-additive interactions among graph attention design dimensions. Overall, the results suggest that, under parameter-constrained fine-tuning, improvements in graph attention layers depend more on capacity allocation and branch interaction than on simply adding more learnable parameters.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Graph Attention Design Choices Matter: A Controlled Study of LoRA-Adapted Audio Anti-Spoofing》所界定。 从摘要看，作者主要围绕 graph、attention、design 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on five evaluation sets with five random seeds show that the LearnT branch achieves the best average equal error rate (EER), yielding a 16.1% relative improvement over the baseline. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：graph, attention, design。 |

---
### 24. OpenEnded: An Open-Response Speech Corpus for Speaking Proficiency Assessment with Human Annotations and ALM Supervision

👤 **作者**: Yu-Wen Chen, Eric Zhou, Evelyn Ding, Tianyi Shen, Zhou Yu, Julia Hirschberg
🔗 **来源**: [https://arxiv.org/abs/2609.15666v1](https://arxiv.org/abs/2609.15666v1)

**摘要**
> The development of automated speaking assessment (ASA) is limited by the scarcity of public datasets, with most existing work relying on read-aloud speech, which limits applicability to real-world communication scenarios. In this work, we introduce OpenEnded, a corpus of English practice speech from Mandarin speakers in open-response tasks. Unlike prior open-response datasets that provide only holistic proficiency scores, OpenEnded offers utterance-level assessments of accuracy, fluency, and prosody. Approximately 10,000 utterances are collected and annotated using a hybrid framework: 1,000 are manually labeled via multi-rater scoring with discrepancy resolution to form a high-quality test set, while the remaining are pseudo-labeled by an audio language model (ALM) for training and development sets. We evaluate ALMs and existing ASA models on the OpenEnded test set and introduce VoxPA as an additional baseline. Results show that ALM-generated pseudo-labels improve training over original ALM scoring, while VoxPA achieves the best performance among all baselines.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《OpenEnded: An Open-Response Speech Corpus for Speaking Proficiency Assessment with Human Annotations and ALM Supervision》所界定。 从摘要看，作者主要围绕 openended、open-response、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that ALM-generated pseudo-labels improve training over original ALM scoring, while VoxPA achieves the best performance among all baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：openended, open-response, speech。 |

---
### 25. Sectional Structure and Emotional Dynamics in Chinese Pop Songs: An Empirical Analysis of Valence-Arousal Trajectories across 100 Songs

👤 **作者**: Jingyi Lyu
🔗 **来源**: [https://arxiv.org/abs/2609.15675v1](https://arxiv.org/abs/2609.15675v1)

**摘要**
> Music Emotion Recognition (MER) aims to identify and represent emotional information in music through computational methods and is an important research area within Music Information Retrieval (MIR). To address the limited consideration of song sectional structure in existing dynamic MER research, this study examines 100 Chinese pop songs by aligning 1,046 manually annotated sections with continuous Valence-Arousal (VA) trajectories and analyzing them from the perspectives of section type, adjacent section transitions, repeated sections, and whole-song trajectories. The results show that emotional differences across sections are reflected more strongly in Arousal. Verse typically forms a relatively low-activation baseline, Pre-chorus exhibits a progressive buildup, and Chorus produces a more pronounced high-arousal arrival, while Interlude, Bridge, and Outro tend to show transitional, divergent, and closing functions, respectively. Although whole-song sectional configurations are diverse, high-frequency local transitions are relatively concentrated. High-arousal positions occur more often in the later part of a song, but are not fixed to the final Chorus. Based on these findings, this study summarizes the emotional organization of the selected pop songs as an empirical framework of "local cycles-global accumulation", in which local sectional cycles are accompanied by emotional pullbacks, while the overall trajectory exhibits a later-stage rise in VA and a tendency for high-Arousal positions to occur later in the song.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Sectional Structure and Emotional Dynamics in Chinese Pop Songs: An Empirical Analysis of Valence-Arousal Trajectories across 100 Songs》所界定。 从摘要看，作者主要围绕 emotion recognition、music information retrieval 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that emotional differences across sections are reflected more strongly in Arousal. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：emotion recognition, music information retrieval。 |

---
### 26. SongCraft: Unified Song Generation and Editing with Reconstructive Learning

👤 **作者**: Haohe Liu, Varun Nagaraja, Gael Le Lan, Xinhao Mei, Zhaoheng Ni, Vikas Chandra, Abdelrahman Mohamed, Yangyang Shi
🔗 **来源**: [https://arxiv.org/abs/2609.16315v1](https://arxiv.org/abs/2609.16315v1)

**摘要**
> Song generation and editing have mostly been treated as separate tasks. Existing editing methods often require noise injection and regeneration or curated paired training data. We propose a unified approach for song generation and editing based on reconstructive pretraining, in which a model is trained to reconstruct audio from varying numbers of interpretable conditions. With conditions such as text and lyrics, the model learns to generate diverse songs. With dense conditions specifying fine-grained music attributes, the model learns to reconstruct the target and enables editing by modifying any single attribute while keeping others fixed. This leads to SongCraft, a latent flow matching based model trained for both generation and fine-grained editing. To improve song generation quality, we further introduce word-level phoneme alignment that improves pronunciation learning and accelerates convergence, beat conditioning that improves general musicality, and representation alignment on VAE latent space that produces semantically meaningful latents for improved generation quality. Experiments show that SongCraft achieves the lowest word error rate among evaluated song generation baselines while maintaining competitive audio quality. We further show that a single model can support editing of lyrics, vocal melody, beats, and singer identity, and we also study the trade-off between reconstruction quality and editability.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SongCraft: Unified Song Generation and Editing with Reconstructive Learning》所界定。 从摘要看，作者主要围绕 songcraft、unified、song 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To improve song generation quality, we further introduce word-level phoneme alignment that improves pronunciation learning and accelerates convergence, beat conditioning that improves general musicality, and representation alignment on VAE latent space that produces semantically meaningful latents for improved generation quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：songcraft, unified, song。 |

---
### 27. Segmental Posterior Decoding for Audio Moment Retrieval

👤 **作者**: Seungdeok Choi, Seongmin Choi, Inhan Choi, Junho Kim, Jeong-gyu Ban, Yong-Hwa Park
🔗 **来源**: [https://arxiv.org/abs/2609.16495v1](https://arxiv.org/abs/2609.16495v1)

**摘要**
> Audio moment retrieval (AMR) identifies temporal segments in long recordings that best match a free-form text query. Existing systems largely rely on fixed-slot DETR decoders that assign proposal-level confidence scores without explicitly normalizing over competing explanations of the full timeline. We propose segmental posterior decoding, which defines a globally normalized distribution over temporal segmentations and scores each candidate moment by its exact segment marginal posterior computed through forward-backward inference. We further expand the training segmentation space by treating a foreground span and its adjacent subdivisions as distinct hypotheses, thereby increasing competition among alternative segmentations. On CASTELLA, our method achieves 41.15% R1@0.7 and 34.68% mAP, outperforming the same network decoded with DETR slot confidence by 10.91 and 9.20 percentage points, respectively.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Segmental Posterior Decoding for Audio Moment Retrieval》所界定。 从摘要看，作者主要围绕 segmental、posterior、decoding 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On CASTELLA, our method achieves 41.15% R1@0.7 and 34.68% mAP, outperforming the same network decoded with DETR slot confidence by 10.91 and 9.20 percentage points, respectively. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：segmental, posterior, decoding。 |

---
### 28. Multimodal Emergency Vehicle Classification via Audio-Visual Transformers and Knowledge Distillation

👤 **作者**: Vijay John, Amar Dabaja
🔗 **来源**: [https://arxiv.org/abs/2609.16535v1](https://arxiv.org/abs/2609.16535v1)

**摘要**
> Emergency vehicle detection in autonomous driving is a safety-critical perception task that demands robustness under diverse and adverse real-world conditions. Existing approaches rely on a single modality, either audio or video, which leads to systematic failure when that modality is degraded: microphone-based systems fail in noisy urban environments, and camera-based systems fail at night or under occlusion. This report presents AVNet, a multimodal audio-visual transformer that classifies emergency vehicles (ambulance, fire engine, police car) and road background using both audio and video, while gracefully handling the absence of either modality at inference time. AVNet introduces three key contributions: (1) a temporally aligned cross-modal fusion module that performs second-level cross-attention between audio spectrogram tokens and video frame tokens, exploiting their exact temporal correspondence without any learned alignment mechanism; (2) learned null embeddings that substitute for missing modality tokens, enabling a single unified model to operate in audio-only, video-only, or joint audio-visual mode without retraining; and (3) a knowledge distillation training strategy in which specialist unimodal teacher models transfer inter-class dark knowledge into the multimodal student fusion branch via soft probability targets. Evaluated on 281 clips from the Google AudioSet dataset, AVNet achieves 66.6% overall accuracy in audio-visual mode, outperforming the audio-only branch by +10.4% and the video-only branch by +15.0%. The largest per-class gain is observed for the hardest class, Ambulance, where fusion achieves +29.5% over either unimodal branch alone, demonstrating that the two modalities provide complementary information that the aligned cross attention mechanism successfully exploits.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Multimodal Emergency Vehicle Classification via Audio-Visual Transformers and Knowledge Distillation》所界定。 从摘要看，作者主要围绕 multimodal、emergency、vehicle 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluated on 281 clips from the Google AudioSet dataset, AVNet achieves 66.6% overall accuracy in audio-visual mode, outperforming the audio-only branch by +10.4% and the video-only branch by +15.0%. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：multimodal, emergency, vehicle。 |

---
### 29. CLASH: Counterfactual Auditing of Lexical and Prosodic Reliance in Spoken Sarcasm Detection

👤 **作者**: Qiyang Sun, Xudong Li, Yupei Li, Jiabin Xue, Yuhang Dai, Jiaming Li, Bjorn W. Schuller
🔗 **来源**: [https://arxiv.org/abs/2609.16582v1](https://arxiv.org/abs/2609.16582v1)

**摘要**
> Spoken sarcasm detectors may exploit lexical content, prosody, or their interaction, yet conventional evaluation cannot reveal which cues drive their predictions. We introduce CLASH (Controlled Lexical-Acoustic Separation Harness), a bilingual counterfactual diagnostic framework that evaluates each utterance under original, lexical-preserving, prosody-preserving, and approximately neutralised conditions. We evaluate handcrafted acoustic-feature systems, self-supervised learning (SSL) probes, and large audio language models (LALMs) on CMMA and MUStARD. For target-only Qwen3-Omni, lexical-preserving speech retains a 0.135--0.148 AUROC advantage over prosody-preserving speech after duration balancing, with cluster-bootstrap intervals above zero; alternative lexical resynthesis preserves this advantage. Acoustic interventions shift scores without consistently improving discrimination or changing binary predictions under the evaluated conditions. Context and interaction estimates vary across corpora. These findings distinguish acoustic sensitivity from sarcasm discrimination while exposing duration, identity, and transformation effects.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CLASH: Counterfactual Auditing of Lexical and Prosodic Reliance in Spoken Sarcasm Detection》所界定。 从摘要看，作者主要围绕 clash、counterfactual、auditing 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Acoustic interventions shift scores without consistently improving discrimination or changing binary predictions under the evaluated conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：clash, counterfactual, auditing。 |

---
### 30. Structure Across Voices: Comparing acoustic-event type accumulation and sequence dependence across four vocal repertoires using frozen audio encoders

👤 **作者**: Mudit Sinha, Sanika Chavan
🔗 **来源**: [https://arxiv.org/abs/2609.16612v1](https://arxiv.org/abs/2609.16612v1)

**摘要**
> Vocal repertoires can differ in acoustic-event type accumulation and temporal organization, yet direct comparison is difficult because corpora use different native events and unequal amounts of sequence. We compare sperm whale codas, human speech phones, Bengalese finch syllables, and common marmoset calls using the same frozen-audio-encoder procedure while matching event count and local sequence opportunity. Whale shows the fastest type accumulation; Finch shows the strongest immediate dependence and repeated-subsequence recurrence. Physically interpretable acoustics recover complementary parts of this profile, continuous analyses without clustering support broad Whale acoustic coverage, and source- and position-preserving nulls retain both Finch order effects. Extending predictive context shifts the comparison toward Whale. Thus repertoire differences depend on the acoustic property and temporal scale measured rather than forming a single hierarchy.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Structure Across Voices: Comparing acoustic-event type accumulation and sequence dependence across four vocal repertoires using frozen audio encoders》所界定。 从摘要看，作者主要围绕 structure、across、voices 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Whale shows the fastest type accumulation; Finch shows the strongest immediate dependence and repeated-subsequence recurrence. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：structure, across, voices。 |

---
### 31. Audio-Visual Turn-taking Prediction in Cocktail Party Scenarios

👤 **作者**: Long-Vu Hoang, Naomi Harte
🔗 **来源**: [https://arxiv.org/abs/2609.17056v1](https://arxiv.org/abs/2609.17056v1)

**摘要**
> Current predictive turn-taking models (PTTMs) achieve strong performance on benchmarks with controlled acoustic conditions and clean audio signals. Their generalisation to conversations with overlapping speech and background interference remains underexplored. In this research, we evaluate audio-visual PTTMs trained with clean data on a challenging cocktail-party testbed derived from the AVCocktail dataset, and analyse their adaptation behaviour to this new domain. Experimental results show consistent performance degradation across audio and visual modalities under noisy conditions, with up to 38% relative drop in weighted F1. Fine-tuning on the new domain improves robustness, but gains vary across modalities and depend on the size of the available pre-training data. These findings provide insights into the different generalisation and adaptation capabilities of the audio and visual modalities, and indicate the need for robust modelling strategies to adapt to the complexities of human interactions in noise. All code and turn labels are made publicly available to facilitate further research.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Audio-Visual Turn-taking Prediction in Cocktail Party Scenarios》所界定。 从摘要看，作者主要围绕 audio-visual、turn-taking、prediction 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Current predictive turn-taking models (PTTMs) achieve strong performance on benchmarks with controlled acoustic conditions and clean audio signals. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-visual, turn-taking, prediction。 |

---
### 32. Sample-Conditioned Representation Selection for Audio Few-Shot Learning

👤 **作者**: Fengrui Liu, Ningxin Shen, Yi Li, Yiwei Fu, Feng Liu, Jiangmeng Li
🔗 **来源**: [https://arxiv.org/abs/2609.17076v1](https://arxiv.org/abs/2609.17076v1)

**摘要**
> Few-shot audio classifiers may rely on foreground-background co-occurrences and fail when those correlations shift. On SpurAudio, the resulting representation shift is concentrated and class dependent: for ResNet12, the top 10 percent of channels explain 82.80 percent of the null-corrected shift contribution. We propose SAMPLESELECT, which predicts a fixed-budget feature mask independently for each input while keeping the encoder and source classifier frozen. Training uses differentiable Gumbel Top-k selection with foreground classification and cross-background contrastive losses; inference uses deterministic Top-k masks and support-only linear adaptation. Across ResNet12 and Conv64 in 5-way 1-shot and 5-shot evaluation, SAMPLESELECT gives the best OOD accuracy among the compared methods and improves the matched full-representation control by 4.90-8.38 percentage points. Ablations and representation analyses further support the learned selection mechanism. Code is available at https://github.com/Cross-Innovation-Lab/SAMPLESELECT/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Sample-Conditioned Representation Selection for Audio Few-Shot Learning》所界定。 从摘要看，作者主要围绕 sample-conditioned、representation、selection 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across ResNet12 and Conv64 in 5-way 1-shot and 5-shot evaluation, SAMPLESELECT gives the best OOD accuracy among the compared methods and improves the matched full-representation control by 4.90-8.38 percentage points. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sample-conditioned, representation, selection。 |

---
### 33. Optimal transport of image sources for interpolation of room impulse responses with moving sources

👤 **作者**: Jesper Brunnström, Filip Elvander, Isabel Haasler
🔗 **来源**: [https://arxiv.org/abs/2609.17237v1](https://arxiv.org/abs/2609.17237v1)

**摘要**
> In geometrical acoustics, room impulse responses (RIRs) can be represented by a set of image sources in free space. For a fixed source position, the image sources allow for computing RIRs at arbitrary receiver positions. However, for a moving physical source, the image sources also move, making interpolation more difficult. In this paper we develop an interpolation method for image source positions of a moving source, given image source positions at the start and end of the trajectory. The method exploits the fact that each image source moves the same distance as the physical source. A statistical model is developed to derive cost functions and an appropriate dummy cost used in the proposed partial optimal transport (POT) approach. Through simulated experiments, POT using the proposed cost functions is shown to be effective compared to the alternatives.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Optimal transport of image sources for interpolation of room impulse responses with moving sources》所界定。 从摘要看，作者主要围绕 optimal、transport、image 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Through simulated experiments, POT using the proposed cost functions is shown to be effective compared to the alternatives. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：optimal, transport, image。 |

---
### 34. SpiroPhonia: Non-Invasive Respiratory Health Assessment from Spontaneous Speech

👤 **作者**: Roksana Khanom, Shafia Supty, Nirupam Roy, Ashok Agrawala
🔗 **来源**: [https://arxiv.org/abs/2609.17350v1](https://arxiv.org/abs/2609.17350v1)

**摘要**
> Chronic Obstructive Pulmonary Disease (COPD) remains a major global health challenge, emphasizing the need for accessible and non-invasive detection. Since speech production is fundamentally linked to respiratory physiology, its disruptions can serve as indirect indicators of pulmonary impairment. This study introduces SpiroPhonia, a machine learning framework that leverages spontaneous speech for respiratory health assessment. We evaluated SpiroPhonia on a new dataset of 201 speakers (102 with COPD, 99 healthy controls). By integrating statistical analysis with recursive feature selection, we identified a compact set of discriminative speech markers. Our best model achieved 78% accuracy, 80% F1-score, and 87% AUC. This performance on spontaneous speech is competitive with methods using controlled laboratory recordings. Findings demonstrate that everyday speech encodes robust respiratory biomarkers, paving the way for continuous health monitoring via voice-enabled technologies.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SpiroPhonia: Non-Invasive Respiratory Health Assessment from Spontaneous Speech》所界定。 从摘要看，作者主要围绕 spirophonia、non-invasive、respiratory 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our best model achieved 78% accuracy, 80% F1-score, and 87% AUC. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：spirophonia, non-invasive, respiratory。 |

---
### 35. Counting Closures in Spanish Trills: A Multi-Corpus Acoustic Study

👤 **作者**: Mateo Cámara, Maria F. Alcala-Durand
🔗 **来源**: [https://arxiv.org/abs/2609.17424v1](https://arxiv.org/abs/2609.17424v1)

**摘要**
> The Spanish trill /r/ is canonically described as a short sequence of lingual closures, yet large-scale acoustic evidence across corpora is scarce, and automatic counters locating envelope peaks tend to conflate each closure with its release. We present a closure-based detector that locates closures gated by a quality filter and cross-checked against an independent autocorrelation-based period estimator. Applied to 3,560 well-formed (voiced, periodic) trill tokens from 356 speakers across six Spanish corpora, the detector yields a median of two closures and an inter-closure period near 36ms, matching the descriptive literature on all corpora. At the speaker level, phonotactic context is the only factor with a robust, medium effect: onset trills (word-initial and post-/n,l,s/) show more closures than intervocalic rr. We find no robust evidence of a sex effect once closures are counted directly. We report reference values and release a reproducible measurement pipeline for Spanish trills.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Counting Closures in Spanish Trills: A Multi-Corpus Acoustic Study》所界定。 从摘要看，作者主要围绕 counting、closures、spanish 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：At the speaker level, phonotactic context is the only factor with a robust, medium effect: onset trills (word-initial and post-/n,l,s/) show more closures than intervocalic rr. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：counting, closures, spanish。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
