<div align="center">

# 📰 Paper Claw

**2026-05-22**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-05-17 12:44:42 CST → 2026-05-22 12:53:12 CST |
| 📄 论文总数 | **55** 篇 |

### 分类统计

- **Speech LLM**: 3 篇
- **ASR**: 4 篇
- **TTS**: 4 篇
- **Enhancement**: 4 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 40 篇

> 💡 今日共收录 55 篇新论文，主要分布在 Speech LLM 3, ASR 4, TTS 4, Enhancement 4, Audio 40。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Synchronization and Turn-Taking in Full-Duplex Speech Dialogue Models

👤 **作者**: Pablo Riera, Pablo Brusco, Cristina Kuo, Marcelo Sancinetti, S. R. K. Branavan
🔗 **来源**: [https://arxiv.org/abs/2605.20356v1](https://arxiv.org/abs/2605.20356v1)

**摘要**
> Full-duplex spoken dialogue models (SDMs) can listen and speak simultaneously, enabling interaction dynamics closer to human conversation than turn-based systems. Inspired by neural coupling in human communication, we study how such models coordinate their internal representations during interaction. We simulate full-duplex dialogues between two instances of the pretrained \textit{Moshi} model under controlled conditions, manipulating channel noise and decoding bias. Synchronization is measured using Centered Kernel Alignment (CKA) across temporal lags, while anticipatory turn-taking cues are probed from delayed internal activations using causal LSTM models, from both speaker and listener perspectives. We find strong representational synchronization under no noise conditions, peaking near zero lag and degrading with noise, and we show that internal states encode anticipatory information that supports turn-taking prediction ahead of time.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Synchronization and Turn-Taking in Full-Duplex Speech Dialogue Models》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We find strong representational synchronization under no noise conditions, peaking near zero lag and degrading with noise, and we show that internal states encode anticipatory information that supports turn-taking prediction ahead of time. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken dialogue。 |

---
### 2. Codec-Robust Attacks on Audio LLMs

👤 **作者**: Jaechul Roh, Jean-Philippe Monteuuis, Jonathan Petit, Amir Houmansdar
🔗 **来源**: [https://arxiv.org/abs/2605.20519v1](https://arxiv.org/abs/2605.20519v1)

**摘要**
> Prior attacks on Audio Large Language Models (Audio LLMs) demonstrated that carefully crafted waveform-domain perturbations can force targeted adversarial outputs. As a defense mechanism against these attacks, real-world codec compression preprocessing has been studied to both detect and remove the perturbations. Yet no existing attack has demonstrated robustness against these compressions. We introduce CodecAttack, which optimizes a perturbation in a neural audio codec's continuous latent space rather than directly perturbing the audio waveform. We show that the codec's compression channel, which discards waveform perturbations, transmits perturbations crafted in its own latent space. To further harden the attack across real-world compression channels, we apply multi-bitrate straight-through Expectation-over-Transformation (EoT), all without modifying the target model. Across three realistic Audio LLM deployment scenarios and three target models, CodecAttack achieves an average 85.5% target-substring attack success rate (ASR) on Opus at moderate bitrates, while the waveform baseline trained with identical EoT hardening does not exceed 26% at any bitrate. The attack transfers to held-out codecs, reaching up to 100% ASR on MP3 and 84% on AAC-LC without retraining. A per-band energy analysis shows that the latent perturbation concentrates below 4kHz, exactly where codecs allocate the most bits, while the waveform baseline spreads into higher frequencies that codecs discard. These results demonstrate that lossy compression is not a reliable defense against adversarial audio and that codec-aware attacks pose a practical threat to deployed Audio LLM systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Codec-Robust Attacks on Audio LLMs》所界定。 从摘要看，作者主要围绕 audio llm 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Prior attacks on Audio Large Language Models (Audio LLMs) demonstrated that carefully crafted waveform-domain perturbations can force targeted adversarial outputs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio llm。 |

---
### 3. DuplexSLA: A Full-Duplex Spoken Language Model with Synchronized Speech, Language, and Action

👤 **作者**: Haoyang Zhang, Jun Chen, Donghang Wu, Yuxin Li, Yuxin Zhang, Xiangyu Tony Zhang, Che Liu, Qingjian Lin, Yizhou Peng, Hexin Liu, Eng Siong Chng, Chao Yan, Boyong Wu, Yechang Huang, Xuerui Yang, Fei Tian
🔗 **来源**: [https://arxiv.org/abs/2605.20755v1](https://arxiv.org/abs/2605.20755v1)

**摘要**
> Recent advances in spoken dialogue language models have shifted from turn-based to full-duplex designs, where the model continuously listens to the user while generating responses. However, existing duplex backbones still lack a native channel for in-conversation planning and tool calling, leaving real-time agentic behaviour either tied to turn boundaries or relegated to an external cascade. We propose DuplexSLA, a native full-duplex Speech-Language-Action foundation model that decodes assistant audio together with a structured action stream on a shared 160 ms chunk timeline. DuplexSLA is built on a dual-stream three-channel formulation: a continuous user audio channel, a discrete assistant audio channel, and a rate-limited textual action channel, all decoded jointly by a single backbone, so that listening, speaking, planning, and tool calling unfold on one shared clock. Two capabilities define the model: (1) semantic-driven turn-taking control, where interruption, pause, and backchannel are handled inside the same backbone instead of by an external semantic VAD; and (2) in-conversation planning and tool calling, where planning text and structured tool calls are emitted on the action channel without halting assistant audio, so that multi-action and backchannel-triggered tool use are interleaved with ongoing speech. To evaluate these capabilities together, we further construct DuplexSLA-Bench, a duplex benchmark covering pause, interrupt, and backchannel turn-taking together with three styles of in-conversation tool calling. Our project page, interactive demos, and the DuplexSLA-Bench evaluation suite are publicly available at https://github.com/hyzhang24/DuplexSLA.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《DuplexSLA: A Full-Duplex Spoken Language Model with Synchronized Speech, Language, and Action》所界定。 从摘要看，作者主要围绕 spoken language model、spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, existing duplex backbones still lack a native channel for in-conversation planning and tool calling, leaving real-time agentic behaviour either tied to turn boundaries or relegated to an external cascade. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken language model, spoken dialogue。 |

---
## 🏷️ ASR

### 1. Analyzing Error Propagation in Korean Spoken QA with ASR-LLM Cascades

👤 **作者**: Donghyuk Jung, Youngwon Choi
🔗 **来源**: [https://arxiv.org/abs/2605.17443v1](https://arxiv.org/abs/2605.17443v1)

**摘要**
> We analyze how automatic speech recognition (ASR) errors propagate through ASR-LLM cascades in Korean spoken question answering (SQA), focusing on downstream semantic failures that conventional ASR metrics cannot fully capture. Our analysis shows that the relative downstream degradation caused by ASR errors is consistent across LLMs with different absolute performance, suggesting that cascade degradation largely tracks ASR-stage information loss. We further identify single-character Korean ASR errors as a distinct semantic-failure channel, where the gold answer becomes entirely absent from the downstream prediction despite only a minimal transcription difference. Finally, an auxiliary comparison shows that a large audio language model outperforms an ASR-LLM pipeline with a matched language backbone in noisy Korean SQA, indicating the potential of direct audio input to mitigate transcript-induced information loss.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Analyzing Error Propagation in Korean Spoken QA with ASR-LLM Cascades》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our analysis shows that the relative downstream degradation caused by ASR errors is consistent across LLMs with different absolute performance, suggesting that cascade degradation largely tracks ASR-stage information loss. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：automatic speech recognition。 |

---
### 2. Sometin Beta Pass Notin (SBPN): Improving Multilingual ASR for Nigerian Languages via Knowledge Distillation

👤 **作者**: Sewade Ogun
🔗 **来源**: [https://arxiv.org/abs/2605.17710v1](https://arxiv.org/abs/2605.17710v1)

**摘要**
> Although modern multilingual Automatic Speech Recognition (ASR) systems support several Nigerian languages, their performance consistently lags behind high-resource languages like English and French. Nigerian languages present unique modelling hurdles, including acute data scarcity, inconsistent orthography, tonal diacritics, diverse accents, frequent code-switching, and localized named entities. To address these challenges, we developed a multilingual ASR framework utilizing a two-stage distillation process. First, we employ student-teacher knowledge distillation from existing monolingual models, conditioned on robust language-specific N-gram language models. Second, we perform iterative self improvement using pseudo-labelled data to further refine accuracy. Our method significantly bridges the performance gap, achieving on average a relative Word Error Rate (WER) reduction of 29 % over monolingual baselines. Our models also outperform state-of-the-art multilingual models across major benchmarks, including Common Voice and Fleurs. We introduce Sometin Beta Pass Notin (SBPN), a foundational multilingual ASR model covering Yorùbá, Hausa, Igbo, Nigerian Pidgin, and Nigerian English. SBPN is released in two sizes: SBPN-Base (120 M parameters) and SBPN-Large (600 M parameters). By releasing these as open foundation models, we aim to provide ASR resources for further research into the rich phonetic and cultural landscape of the region.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Sometin Beta Pass Notin (SBPN): Improving Multilingual ASR for Nigerian Languages via Knowledge Distillation》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Second, we perform iterative self improvement using pseudo-labelled data to further refine accuracy. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

---
### 3. Contextual Biasing for Streaming ASR via CTC-based Word Spotting

👤 **作者**: Kai-Chen Tsai, Tien-Hong Lo, Yun-Ting Sun, Berlin Chen
🔗 **来源**: [https://arxiv.org/abs/2605.18222v2](https://arxiv.org/abs/2605.18222v2)

**摘要**
> Contextual biasing is essential to improving the recognition of rare and domain-specific words in an automatic speech recognition (ASR) system. While numerous methods have been proposed in recent years, most of them focus on offline settings and do not explicitly address the challenges of streaming ASR. For example, CTC-based word spotting (CTC-WS) have demonstrated strong performance by directly detecting keywords from CTC log-probabilities, but they are limited to offline processing and require access to the full utterance. In This work, we present a streaming extension of CTC-WS for real-time contextual biasing. Our method maintains active keyword paths across audio chunks using a stateful token passing algorithm, enabling the detection of keywords that span multiple chunks. To ensure low latency and stable output, we introduce an incremental commitment mechanism that only emits segments guaranteed not to be affected by future audio, while deferring uncertain regions. This method naturally integrates with streaming ASR pipelines and does not require modifications to the underlying acoustic model or additional training, making it practical for real-world deployment. Experimental results show that our method reduces overall WER and effectively improves keyword F-score, demonstrating its effectiveness for real-time ASR applications.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Contextual Biasing for Streaming ASR via CTC-based Word Spotting》所界定。 从摘要看，作者主要围绕 automatic speech recognition、acoustic model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Contextual biasing is essential to improving the recognition of rare and domain-specific words in an automatic speech recognition (ASR) system. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, acoustic model。 |

---
### 4. Mega-ASR: Towards In-the-wild^2 Speech Recognition via Scaling up Real-world Acoustic Simulation

👤 **作者**: Zhifei Xie, Kaiyu Pang, Haobin Zhang, Deheng Ye, Xiaobin Hu, Shuicheng Yan, Chunyan Miao
🔗 **来源**: [https://arxiv.org/abs/2605.19833v1](https://arxiv.org/abs/2605.19833v1)

**摘要**
> Despite rapid advances in automatic speech recognition (ASR) and large audio-language models, robust recognition in real-world environments remains limited by an "acoustic robustness bottleneck": models often lose acoustic grounding and produce omissions or hallucinations under severe, compositional distortions. We propose Mega-ASR, a unified ASR-in-the-wild framework that combines scalable compound-data construction with progressive acoustic-to-semantic optimization. We introduce Voices-in-the-Wild-2M, covering 7 classic acoustic phenomena and 54 physically plausible compound scenarios, and train Mega-ASR with Acoustic-to-Semantic Progressive Supervised Fine-Tuning and Dual-Granularity WER-Gated Policy Optimization. Extensive experiments demonstrate that Mega-ASR achieves significant advantages over prior state-of-the-art systems on adverse-condition ASR benchmarks (45.69% vs. 54.01% on VOiCES R4-B-F, and 21.49% vs. 29.34% on NOIZEUS Sta-0). On complex compositional acoustic scenarios, Mega-ASR further delivers over 30% relative WER reduction against strong open- and closed-source baselines, establishing a scalable paradigm for robust ASR in-the-wild.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Mega-ASR: Towards In-the-wild^2 Speech Recognition via Scaling up Real-world Acoustic Simulation》所界定。 从摘要看，作者主要围绕 audio-language model、automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experiments demonstrate that Mega-ASR achieves significant advantages over prior state-of-the-art systems on adverse-condition ASR benchmarks (45.69% vs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model, automatic speech recognition。 |

---
## 🏷️ TTS

### 1. Raon-OpenTTS: Open Models and Data for Robust Text-to-Speech

👤 **作者**: Semin Kim, Seungjun Chung, Taehong Moon, Sangheon Lee, Minyoung Ahn, Keon Lee, Nam Soo Kim, Jaewoong Cho, Ludwig Schmidt, Kangwook Lee, Dongmin Park
🔗 **来源**: [https://arxiv.org/abs/2605.20830v1](https://arxiv.org/abs/2605.20830v1)

**摘要**
> Recent advances in text-to-speech (TTS) models show impressive speech naturalness and quality, yet the role of large-scale open data in driving this progress remains underexplored. In this work, we introduce Raon-OpenTTS, an open TTS model that performs competitively with state-of-the-art closed-data TTS models, and Raon-OpenTTS-Pool, a large-scale open dataset for reproducible TTS training. Raon-OpenTTS-Pool consists of 615K hours of 240M speech segments aggregated from publicly available English speech corpora and web-sourced recordings. With a model-based filtering pipeline applied to Raon-OpenTTS-Pool, we derive Raon-OpenTTS-Core, a curated, high-quality subset of 510K hours and 194M speech segments. Using Raon-OpenTTS-Core, we train Raon-OpenTTS, a series of diffusion transformer (DiT)-based TTS models from 0.3B to 1B parameters. On multiple benchmarks, Raon-OpenTTS-1B shows comparable performance to state-of-the-art models such as Qwen3-TTS and CosyVoice 3, which are trained on several million hours of proprietary speech data. Notably, on Seed-TTS-Eval, Raon-OpenTTS-1B achieves a word error rate (WER) of 1.78% and a speaker similarity (SIM) of 0.749, ranking second on WER and first on SIM among recent open-weight TTS baselines. On CV3-Hard-EN, Raon-OpenTTS-1B achieves a WER of 6.15% and a SIM of 0.775, ranking first on both metrics. Furthermore, to support robust evaluation, we introduce Raon-OpenTTS-Eval, a structured benchmark for assessing TTS robustness across diverse acoustic conditions including clean, noisy, in-the-wild, and expressive speech. On Raon-OpenTTS-Eval, Raon-OpenTTS-1B achieves the best average WER and SIM among all evaluated models, and the second-best human preference, as measured by comparative mean opinion score (CMOS). Our data pool, filtering pipeline, training code, and checkpoints are publicly available at https://github.com/krafton-ai/RAON-OpenTTS.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Raon-OpenTTS: Open Models and Data for Robust Text-to-Speech》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Recent advances in text-to-speech (TTS) models show impressive speech naturalness and quality, yet the role of large-scale open data in driving this progress remains underexplored. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech。 |

---
### 2. Evaluating Speech Articulation Synthesis with Articulatory Phoneme Recognition

👤 **作者**: Vinicius Ribeiro, Yves Laprie
🔗 **来源**: [https://arxiv.org/abs/2605.20920v1](https://arxiv.org/abs/2605.20920v1)

**摘要**
> Recent advances in machine learning and the availability of articulatory datasets allow vocal tract synthesis to be conditioned on phonetic sequences, a primary task of articulatory speech synthesis. However, quality assessment needs a better definition. Generally, ranking generative models is tricky due to subjectivity. However, articulatory synthesis has the additional difficulty of requiring specialized knowledge in vocal tract anatomy and acoustics. To address this problem, this paper proposes to evaluate speech articulation synthesis using phoneme recognition as a proxy. Our hypothesis is that phoneme recognition using articulatory features better captures nuances in phoneme production, such as correct places of articulation, which traditional metrics (e.g., point-wise distance metrics) do not. We train a neural network with acoustic and articulatory features extracted from a single-speaker RT-MRI dataset. Then, we compare the recognition performance when testing the model with different synthetic articulatory features. Our results show that our articulatory feature set is phonetically rich and helps exploring additional dimensions on speech articulation synthesis.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Evaluating Speech Articulation Synthesis with Articulatory Phoneme Recognition》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that our articulatory feature set is phonetically rich and helps exploring additional dimensions on speech articulation synthesis. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech synthesis。 |

---
### 3. RobustSpeechFlow: Learning Robust Text-to-Speech Trajectories via Augmentation-based Contrastive Flow Matching

👤 **作者**: Jinhyeok Yang, Hyeongju Kim, Yechan Yu, Joon Byun, Frederik Bous, Juheon Lee
🔗 **来源**: [https://arxiv.org/abs/2605.22083v1](https://arxiv.org/abs/2605.22083v1)

**摘要**
> While flow-matching text-to-speech (TTS) achieves strong zero-shot speaker similarity and naturalness, it remains susceptible to content fidelity issues, particularly skip and repeat errors from imperfect alignment. We propose RobustSpeechFlow, a training strategy that improves alignment robustness by extending contrastive flow matching with length-preserving repeat and skip latent augmentations. Requiring no external aligners or preference data, our method directly penalizes realistic failure modes and readily integrates into existing pipelines. On Seed-TTS-eval, it reduces the word error rate (WER) from 1.44 to 1.38 using only 0.06B parameters. On our ZERO500 benchmark, it delivers consistent intelligibility improvements across diverse speaker and prosody conditions; at NFE=24, it reduces English character error rate (CER) from 0.48\% to 0.35\% and Korean CER from 0.81\% to 0.57\%. Audio samples: https://robustspeechflow.github.io/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《RobustSpeechFlow: Learning Robust Text-to-Speech Trajectories via Augmentation-based Contrastive Flow Matching》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While flow-matching text-to-speech (TTS) achieves strong zero-shot speaker similarity and naturalness, it remains susceptible to content fidelity issues, particularly skip and repeat errors from imperfect alignment. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech。 |

---
### 4. Beyond Acoustic Emotion Recognition: Multimodal Pathos Analysis in Political Speech Using LLM-Based and Acoustic Emotion Models

👤 **作者**: Juergen Dietrich
🔗 **来源**: [https://arxiv.org/abs/2605.22732v1](https://arxiv.org/abs/2605.22732v1)

**摘要**
> We investigate whether acoustic emotion recognition models can serve as proxies for the Pathos dimension in political speech analysis, as operationalised by the TRUST multi-agent large language model (LLM) pipeline. Using a Bundestag plenary speech by Felix Banaszak (51 segments, 245 s) as a case study, we compare three analysis modalities: (1) emotion2vec_plus_large, an acoustic speech emotion recognition (SER) model whose continuous Arousal and Valence values are derived via post-hoc Russell Circumplex projection; (2) Gemini 2.5 Flash, an LLM analysing the full speech audio together with its transcript in an open-ended, context-aware fashion; and (3) TRUST-Pathos scores from a three-advocate LLM supervisor ensemble. Spearman rank correlations reveal that Gemini Valence correlates strongly with TRUST-Pathos (rho = +0.664, p < 0.001), whereas emotion2vec Valence does not (rho = +0.097, p = 0.499). We further demonstrate, via a systematic quality evaluation of the Berlin Database of Emotional Speech (EMO-DB) using Gemini in an open-ended annotation paradigm, that standard SER benchmark corpora suffer from acted speech, cultural bias, and category incompatibility. Our results suggest that LLM-based multimodal analysis captures semantically defined political emotion substantially better than acoustic models alone, while acoustic features remain informative for low-level Arousal estimation. Future work will extend this approach to video-based analysis incorporating facial expression and gaze.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Beyond Acoustic Emotion Recognition: Multimodal Pathos Analysis in Political Speech Using LLM-Based and Acoustic Emotion Models》所界定。 从摘要看，作者主要围绕 acoustic model、emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We further demonstrate, via a systematic quality evaluation of the Berlin Database of Emotional Speech (EMO-DB) using Gemini in an open-ended annotation paradigm, that standard SER benchmark corpora suffer from acted speech, cultural bias, and category incompatibility. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic model, emotion recognition。 |

---
## 🏷️ Enhancement

### 1. Fractional-Order Subband p-Norm Adaptive Filter via Transformation Nearest Kronecker Product Decomposition for Active Noise Control

👤 **作者**: Jianhong Ye, Haiquan Zhao, Shaohui Lv, Yang Zhou
🔗 **来源**: [https://arxiv.org/abs/2605.17964v1](https://arxiv.org/abs/2605.17964v1)

**摘要**
> The conventional normalized subband p-norm (NSPN) algorithm achieves robustness in $α$-stable noise ($1<α\leq 2$) by utilizing low-order error moments. However, its performance degrades significantly under three scenarios: (1) non-Gaussian inputs, (2) $α$-stable noise with $0<α\leq 1$, and (3) sparse system identification. To address these limitations, this paper proposes a fractional-order NSPN algorithm based on the nearest Kronecker product (NKP) decomposition and fractional-order stochastic gradient descent, termed NKP-FoNSPN. Theoretical bounds for the fractional-order parameter $β$ are also derived. Notably, when $β=1$, the NKP-FoNSPN reduces to a new NKP-NSPN algorithm, while its non-NKP decomposition variant becomes the fractional-order NSPN (FoNSPN) algorithm. Furthermore, a novel transformation-based NKP (TNKP) decomposition technique is designed, which exhibits lower computational complexity than conventional NKP for specific filter structures. The resulting TNKP-based FoNSPN (TNKP-FoNSPN) achieves lower steady-state misadjustment and multiplication cost compared with the NKP-FoNSPN algorithm. Additionally, complete computational complexity analyses are provided. For active noise control (ANC) scenarios, we develop filtered-x variants: NKP-FxFoNSPN and TNKP-FxFoNSPN. From the former, two additional variants are derived: NKP-FxNSPN and FxFoNSPN. Simulations using diverse noise sources (pink, helicopter, gunshot, pile driver, and traction substation noise) demonstrate the superiority of the proposed algorithms. Finally, we validate their noise reduction performance in a real constructed single-channel duct ANC and a simulated multi-channel ANC systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Fractional-Order Subband p-Norm Adaptive Filter via Transformation Nearest Kronecker Product Decomposition for Active Noise Control》所界定。 从摘要看，作者主要围绕 noise reduction 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The conventional normalized subband p-norm (NSPN) algorithm achieves robustness in $α$-stable noise ($1<α\leq 2$) by utilizing low-order error moments. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：noise reduction。 |

---
### 2. Fast Multichannel NMF with Block-Diagonal Spatial Covariance Matrices for Efficient Blind Source Separation Using Distributed Microphone Arrays

👤 **作者**: Hirotaka Nishikori, Nobutaka Ito, Kouei Yamaoka, Norihiro Takamune, Hiroshi Saruwatari
🔗 **来源**: [https://arxiv.org/abs/2605.19388v1](https://arxiv.org/abs/2605.19388v1)

**摘要**
> Distributed microphone arrays composed of multiple subarrays enable blind source separation over a wide spatial area. Directly applying fast multichannel nonnegative matrix factorization (FastMNMF) to all subarrays can exploit observations from all subarrays, but it requires repeated inversions of large matrices spanning all microphones, causing the computational cost to increase rapidly as the number of microphones grows. In contrast, applying FastMNMF to one subarray reduces the matrix size but cannot exploit observations from other subarrays. We propose distributed FastMNMF, which imposes a block-diagonal structure on the source spatial covariance matrices, so that matrix inversions are performed within subarrays. The NMF-based source spectrogram model is shared across subarrays, allowing the method to aggregate source activity information while discarding inter-subarray covariance. In synchronized, noiseless simulations with fixed room and array/source geometry, the method required less computation time than conventional FastMNMF using all subarrays, achieved a higher average source-to-distortion ratio than conventional FastMNMF using one subarray, and was applicable in the tested five-source condition, where each four-microphone subarray was locally underdetermined.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Fast Multichannel NMF with Block-Diagonal Spatial Covariance Matrices for Efficient Blind Source Separation Using Distributed Microphone Arrays》所界定。 从摘要看，作者主要围绕 source separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In synchronized, noiseless simulations with fixed room and array/source geometry, the method required less computation time than conventional FastMNMF using all subarrays, achieved a higher average source-to-distortion ratio than conventional FastMNMF using one subarray, and was applicable in the tested five-source condition, where each four-microphone subarray was locally underdetermined. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation。 |

---
### 3. Cross-Talk Speech Reduction, by Separation, for Separation

👤 **作者**: Zhong-Qiu Wang, Samuele Cornell
🔗 **来源**: [https://arxiv.org/abs/2605.19695v1](https://arxiv.org/abs/2605.19695v1)

**摘要**
> In conversational speech separation and recognition tasks, close-talk microphones are typically attached to each speaker during training data collection to capture near-field, close-talk mixture signals, in addition to using far-field microphones to record far-field mixture signals. Each such close-talk mixture exhibits a reasonably high energy level for the wearer and could intuitively serve as weak supervision for training far-field speech separation models directly on real-recorded far-field signals. However, they are not sufficiently clean for this purpose, as they often contain strong cross-talk speech from other speakers in addition to background noise. To address this, we propose cross-talk reduction (CTR), a task aiming to isolate the wearer's speech from each close-talk mixture, and a novel method called CTRnet, which can be trained directly on real-recorded pairs of close-talk and far-field mixtures to accomplish CTR. Building on CTRnet, we further propose pseudo-label based far-field speech separation (PuLSS), which uses CTRnet's estimated clean speech as pseudo-labels to train models for separating far-field mixtures. A key advantage of the proposed framework is that both CTRnet and PuLSS can be trained on real-recorded data from the target domain, addressing the generalization gap commonly observed when models are trained exclusively on simulated data. On the CHiME-6 dataset, our framework achieves state-of-the-art ASR performance under both oracle and estimated speaker diarization, surpassing all CHiME-{7,8} challenge submissions. To our knowledge, it is the first neural speech separation method that substantially outperforms guided source separation on real conversational "speech-in-the-wild" data.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Cross-Talk Speech Reduction, by Separation, for Separation》所界定。 从摘要看，作者主要围绕 source separation、speech separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On the CHiME-6 dataset, our framework achieves state-of-the-art ASR performance under both oracle and estimated speaker diarization, surpassing all CHiME-{7,8} challenge submissions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation, speech separation。 |

---
### 4. Linearly Constrained Deep Beamformer for Multi-Speaker Scenarios

👤 **作者**: Ilai Zaidel, Ori Engel, Bar Engel, Sharon Gannot
🔗 **来源**: [https://arxiv.org/abs/2605.21141v1](https://arxiv.org/abs/2605.21141v1)

**摘要**
> We propose a deep beamforming framework for enhancing target speaker(s) in multi-speaker environments. A deep neural network (DNN) is trained to estimate beamforming weights directly from noisy multichannel inputs while satisfying linear spatial constraints through an adaptive multi-term loss inspired by the augmented Lagrangian framework. The loss combines signal reconstruction with penalties that enforce a distortionless response toward the target and suppress the interference subspace. The model is further guided by the target relative transfer function (RTF) and the estimated interference subspace. The proposed model can direct a beam toward the target speaker while directing nulls toward the interfering sources, achieving superior overall enhancement performance compared with the classical LCMV beamformer constructed by the same estimated spatial signatures. Furthermore, compared with the LCMV beamformer, the proposed model produces more controlled sidelobes and improved background-noise attenuation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Linearly Constrained Deep Beamformer for Multi-Speaker Scenarios》所界定。 从摘要看，作者主要围绕 beamforming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The proposed model can direct a beam toward the target speaker while directing nulls toward the interfering sources, achieving superior overall enhancement performance compared with the classical LCMV beamformer constructed by the same estimated spatial signatures. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beamforming。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Omni-Customizer: End-to-End MultiModal Customization for Joint Audio-Video Generation

👤 **作者**: Yuheng Chen, Qingdong He, Teng Hu, Yuji Wang, Yabiao Wang, Lizhuang Ma, Jiangning Zhang
🔗 **来源**: [https://arxiv.org/abs/2605.17488v1](https://arxiv.org/abs/2605.17488v1)

**摘要**
> The landscape of joint audio and video generation has been fundamentally transformed by the advent of powerful foundation models. Despite these strides, achieving cohesive multimodal customization for the simultaneous preservation of visual identities and vocal timbres across multiple interacting subjects remains largely underexplored. To bridge this gap, we present Omni-Customizer, an end-to-end framework targeted at the precise binding and seamless fusion of multimodal identity information. Specifically, we introduce an Omni-Context Fusion (OCF) module that effectively enriches the base textual prompt with dense, multimodal identity cues, along with a Masked TTS Cross-Attention (MTP-CA) mechanism explicitly designed to prevent the severe "speech leakage" problem. Within this architecture, we propose Semantic-Anchored Multimodal RoPE (SA-MRoPE) to anchor visual and audio reference tokens, along with TTS embeddings, to their corresponding semantic descriptions, enabling structured multimodal fusion and robust identity binding. Furthermore, we devise a comprehensive training strategy that incorporates interleaved audio-video scheduling to rapidly adapt the audio branch to multilingual scenarios without degrading foundational priors, and a progressive in-pair to cross-pair curriculum to facilitate the learning of high-level and robust identity features. Extensive experiments demonstrate that Omni-Customizer achieves state-of-the-art performance in dual-modal customized generation, excelling across visual identity similarity, timbre consistency, precise audio-video synchronization, and overall video-audio fidelity.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Omni-Customizer: End-to-End MultiModal Customization for Joint Audio-Video Generation》所界定。 从摘要看，作者主要围绕 omni-customizer、end-to-end、multimodal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Despite these strides, achieving cohesive multimodal customization for the simultaneous preservation of visual identities and vocal timbres across multiple interacting subjects remains largely underexplored. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：omni-customizer, end-to-end, multimodal。 |

---
### 2. Audio-Image Cross-Modal Retrieval with Onomatopoeic Images

👤 **作者**: Keisuke Imoto, Yamato Kojima, Takao Tsuchiya
🔗 **来源**: [https://arxiv.org/abs/2605.17509v1](https://arxiv.org/abs/2605.17509v1)

**摘要**
> Finding sound effects or environmental sounds that match a creator's intended impression remains a largely manual process in multimedia production. This is especially relevant for comics and other visual media, where visually stylized onomatopoeic expressions convey auditory impressions through letter shapes, strokes, layouts, and decorative patterns. However, cross-modal retrieval between onomatopoeic images and general sounds has been largely unexplored. This paper thus introduces a bidirectional retrieval framework between onomatopoeic images and the corresponding sound clips. Instead of directly comparing embeddings extracted from pretrained image and audio encoder, we train modality-specific projection heads that re-align the embeddings for visual onomatopoeia and corresponding sounds. We then construct the Multimodal Image-Audio Onomatopoeia dataset (MIAO), which contains paired onomatopoeic images and sound clips across 50 sound event classes. Experimental results show that the proposed method substantially outperforms a zero-shot baseline using pretrained CLIP and CLAP embeddings. These results demonstrate that adapting pretrained representations enables effective retrieval in both directions: from onomatopoeic images to sounds and from sounds to onomatopoeic images.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Audio-Image Cross-Modal Retrieval with Onomatopoeic Images》所界定。 从摘要看，作者主要围绕 audio-image、cross-modal、retrieval 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results show that the proposed method substantially outperforms a zero-shot baseline using pretrained CLIP and CLAP embeddings. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio-image, cross-modal, retrieval。 |

---
### 3. Robust Audio Tagging under Class-wise Supervision Unreliability

👤 **作者**: Yuanbo Hou, Zhaoyi Liu, Tong Ye, Qiaoqiao Ren, Jian Guan, Wenwu Wang, Stephen Roberts
🔗 **来源**: [https://arxiv.org/abs/2605.17512v1](https://arxiv.org/abs/2605.17512v1)

**摘要**
> Weakly labeled datasets such as AudioSet have driven recent progress in audio tagging. However, annotation quality varies across sound classes. Labels may be incomplete, ambiguous, or unreliable, which introduces class-dependent supervision bias during optimisation. The issue becomes harder as real and generated audio are increasingly mixed in training, and generated samples do not always match their intended semantic labels. Prior work mainly addressed unreliable supervision from missing-positive labels, while this paper targets three other sources of unreliable supervision: spurious additions, misassignments between similar classes, and weakened label evidence. These effects introduce class-dependent optimisation bias that is not explicitly modeled by most existing methods. To bridge this gap, the paper proposes a Class-wise Supervision Unreliability (CSU) framework that controls supervision strength at the class level during training. CSU learns a separate unreliability parameter for each class and down-weights less reliable supervision without changing the model architecture or inference process. To support evaluations, this paper also introduces ESC-FreeGen50, a manually verified benchmark of 50 sound classes that combines real and generated audio. Experiments on controlled benchmarks and AudioSet show that CSU improves robustness across different architectures and different sources of supervision unreliability. The results indicate that explicit class-wise modeling of supervision unreliability is an effective and practical strategy for robust audio tagging under large-scale weakly labeled training. Code and data are available at: https://github.com/Yuanbo2020/CSU

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Robust Audio Tagging under Class-wise Supervision Unreliability》所界定。 从摘要看，作者主要围绕 audio tagging 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on controlled benchmarks and AudioSet show that CSU improves robustness across different architectures and different sources of supervision unreliability. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio tagging。 |

---
### 4. Profiling the Voice: Speaker-Specific Phoneme Fingerprinting for Speech Deepfake Detection

👤 **作者**: Jun Xue, Tong Zhang, Zhuolin Yi, Yihuan Huang, Yi Chai, Yiyang Zhang, Yanzhen Ren
🔗 **来源**: [https://arxiv.org/abs/2605.17737v1](https://arxiv.org/abs/2605.17737v1)

**摘要**
> The rapid advancement of generative AI has made audio deepfakes increasingly indistinguishable from authentic human vocals, posing significant threats to persons-of-interest (POI) such as public figures. Current detection systems primarily rely on generic, black-box models that fail to capture speaker-specific idiosyncratic traits and lack interpretability. In this paper, we propose Phoneme-based Voice Profiling (PVP), a novel personalized defense framework. By shifting the detection paradigm from macro-utterance analysis to micro-phonetic modeling, PVP captures the unique acoustic distributions underlying a POI's habitual articulatory patterns. Specifically, our framework models speaker-specific phonetic realizations using lightweight Gaussian Mixture Models (GMMs) estimated solely from bona fide reference speech. This design enables data-efficient profiling and robust generalization to previously unseen spoofing attacks without requiring heavy spoof-specific training. Furthermore, we introduce the first large-scale Chinese POI deepfake dataset to benchmark speaker-specific detection. Experimental results demonstrate that PVP significantly outperforms state-of-the-art generic detectors in POI spoofing scenarios, achieving substantial EER reductions while providing fine-grained, phoneme-level interpretability for forensic analysis. Code and data are available at: https://github.com/JunXue-tech/PVP

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Profiling the Voice: Speaker-Specific Phoneme Fingerprinting for Speech Deepfake Detection》所界定。 从摘要看，作者主要围绕 profiling、voice、speaker-specific 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results demonstrate that PVP significantly outperforms state-of-the-art generic detectors in POI spoofing scenarios, achieving substantial EER reductions while providing fine-grained, phoneme-level interpretability for forensic analysis. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：profiling, voice, speaker-specific。 |

---
### 5. UrduSpeech: A 156-Hour Urdu Speech Corpus with 12-Dimension Paralinguistic Annotations

👤 **作者**: Attia Nafees ul Haq, Zeyu Zhu, Jingbin Hu, ChunJiang He, Lei Xie
🔗 **来源**: [https://arxiv.org/abs/2605.17846v1](https://arxiv.org/abs/2605.17846v1)

**摘要**
> Despite 230 million speakers, Urdu remains critically under-resourced in speech technology. We introduce UrduSpeech: a large high-fidelity Urdu corpus comprising 156 hours of audio with 12-dimension paralinguistic metadata, encompassing US-Std, US-CS, US-EngPk. To address Right-to-Left script constraints and frequent code-switching, we developed UrduSpeech, a LLM-driven pipeline to curate data across 12 diverse categories, including news, drama, and rare literary forms like Bait-Bazi. We also release a 9-hour US-Benchmark set, manually corrected by native annotators to serve as a standard. Human quality assessment of the primary 156-hour corpus yielded a Mean Opinion Score (MOS) of 4.6 (std = 0.7) with inter-rater reliability confirmed by a 0.68 Cohen's Kappa, validating our curation pipeline's 97.6% confidence score. The corpus maintains a 60-40 gender balance across 71,792 utterances. Our work represents a significant leap toward linguistic inclusivity in global AI. The corpus and code are open-sourced, and a demo page is available.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《UrduSpeech: A 156-Hour Urdu Speech Corpus with 12-Dimension Paralinguistic Annotations》所界定。 从摘要看，作者主要围绕 urduspeech、hour、urdu 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We introduce UrduSpeech: a large high-fidelity Urdu corpus comprising 156 hours of audio with 12-dimension paralinguistic metadata, encompassing US-Std, US-CS, US-EngPk. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：urduspeech, hour, urdu。 |

---
### 6. CounterFlow: A Two-Phase Inference-Time Sampling for Counterfactual Video Foley Generation

👤 **作者**: Gyubin Lee, Junwon Lee, Juhan Nam
🔗 **来源**: [https://arxiv.org/abs/2605.18916v1](https://arxiv.org/abs/2605.18916v1)

**摘要**
> We investigate Counterfactual Video Foley Generation, which aims to adopt a sound-source identity that contradicts the visual evidence while remaining temporally synchronized to a silent video. Existing Video&Text-to-Audio (VT2A) models struggle with this, often remaining anchored to the visually implied sound source when video and text contents disagree. We present ConterFlow, an inference-time dual-phase sampling scheme for pretrained flow-matching VT2A models. Phase 1 builds a video-derived temporal structure while suppressing the visually implied source; Phase 2 drops video conditioning to focus entirely on shaping audio timbre toward the target prompt. ConterFlow substantially improves counterfactual Video Foley generation compared to naive negative prompting and state-of-the-art baselines. To evaluate replacement quality, we propose a metric leveraging a text-audio co-embedding space to measure both target-prompt evidence and residual visually implied source leakage. Video demonstrations and code are available at https://gyubin-lee.github.io/counterflow-demo/

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CounterFlow: A Two-Phase Inference-Time Sampling for Counterfactual Video Foley Generation》所界定。 从摘要看，作者主要围绕 counterflow、two-phase、inference-time 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：ConterFlow substantially improves counterfactual Video Foley generation compared to naive negative prompting and state-of-the-art baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：counterflow, two-phase, inference-time。 |

---
### 7. Stable Audio 3

👤 **作者**: Zach Evans, Julian D. Parker, Matthew Rice, CJ Carr, Zack Zukowski, Josiah Taylor, Jordi Pons
🔗 **来源**: [https://arxiv.org/abs/2605.17991v1](https://arxiv.org/abs/2605.17991v1)

**摘要**
> Stable Audio 3 is a family of fast latent diffusion models (small, medium, large) for variable-length audio generation and editing. Since our models can generate several minutes of audio, variable-length generations are key to avoid the cost of producing full-length generations for short sounds. We also support inpainting, enabling targeted audio editing and the continuation of short recordings. Our latent diffusion models operate on top of a novel semantic-acoustic autoencoder that projects audio into a compact latent space, enabling efficient diffusion-based generation while preserving audio fidelity and encouraging semantic structure in the latent. Finally, we run adversarial post-training to both accelerate inference and improve generation quality, reducing the number of inference steps while improving fidelity and prompt adherence. Stable Audio 3 models are trained on licensed and Creative Commons data to generate music and sounds in less than a 2s on an H200 GPU and less than a few seconds on a MacBook Pro M4. We release the weights of small and medium, that can run on consumer-grade hardware, together with their training and inference pipeline.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Stable Audio 3》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Finally, we run adversarial post-training to both accelerate inference and improve generation quality, reducing the number of inference steps while improving fidelity and prompt adherence. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---
### 8. MusicDET: Zero-Shot AI-Generated Music Detection

👤 **作者**: Chaolei Han, Hongsong Wang, Jie Gui
🔗 **来源**: [https://arxiv.org/abs/2605.18072v1](https://arxiv.org/abs/2605.18072v1)

**摘要**
> Detecting AI-generated music is crucial for preserving artistic authenticity and preventing the misuse of generative music technologies. However, existing discriminative detectors typically rely on generated samples during training and often suffer from severe performance degradation when confronted with music produced by unseen generators, which limits their real-world applicability. To address this issue, we formulate a zero-shot setting for AI-generated music detection, where the detector is trained exclusively on real music without access to any generated samples. Under this setting, we propose MusicDET, a generator-agnostic detection framework based on frequency-guided normalizing flows that probabilistically models the distribution of real music features. By evaluating the likelihood of an input sample under the learned real-music distribution, MusicDET enables effective detection of out-of-distribution music signals. Experiments on the FakeMusicCaps and SONICS datasets show that MusicDET consistently outperforms conventional discriminative detectors, particularly when detecting music generated by previously unseen models.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MusicDET: Zero-Shot AI-Generated Music Detection》所界定。 从摘要看，作者主要围绕 musicdet、zero-shot、ai-generated 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the FakeMusicCaps and SONICS datasets show that MusicDET consistently outperforms conventional discriminative detectors, particularly when detecting music generated by previously unseen models. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：musicdet, zero-shot, ai-generated。 |

---
### 9. Acoustic Interference: A New Paradigm Weaponizing Acoustic Latent Semantic for Universal Jailbreak against Large Audio Language Models

👤 **作者**: Yanyun Wang, Yu Huang, Zi Liang, Xixin Wu, Li Liu
🔗 **来源**: [https://arxiv.org/abs/2605.18168v1](https://arxiv.org/abs/2605.18168v1)

**摘要**
> The integration of audio modality into Large Audio Language Models (LALMs) significantly expands their attack surface. Existing jailbreak paradigms predominantly treat audio as a carrier for malicious payloads, relying on semantic optimization, acoustic parameter control, or additive perturbation to embed harmful content into the audio signal. In this work, we challenge this necessity and propose a new paradigm in which the role of audio shifts from content injection to safety alignment interference. We reveal that LALM safety alignment can be compromised solely by specific Acoustic Latent Semantics (ALS), the underlying paralinguistic features intrinsic to the priors of audio generative models. Distinct from previous works that leverage explicit acoustic parameters to merely style malicious audio, we demonstrate that interference audio, benign in content but infused with specific ALS, can serve as a universal jailbreak trigger. Leveraging this insight, we propose the Acoustic Interference Attack (AIA), which decouples the attack payload from the audio. Specifically, AIA employs a set of universal, instruction-neutral interference audio, enabling standard malicious text queries to bypass safety alignment without instance-specific optimization. Extensive experiments on 10 LALMs across five datasets demonstrate that AIA achieves the state-of-the-art attack success rate. Furthermore, our interpretability analysis uncovers the inference path drift induced by AIA and identifies the inherent effective patterns within ALS, revealing the fundamental vulnerability of cross-modal alignment in LALMs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Acoustic Interference: A New Paradigm Weaponizing Acoustic Latent Semantic for Universal Jailbreak against Large Audio Language Models》所界定。 从摘要看，作者主要围绕 acoustic、interference、paradigm 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Distinct from previous works that leverage explicit acoustic parameters to merely style malicious audio, we demonstrate that interference audio, benign in content but infused with specific ALS, can serve as a universal jailbreak trigger. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic, interference, paradigm。 |

---
### 10. Sonalyzer-Moz: A Framework for Analyzing the Structure of Mozart's Sonata Form

👤 **作者**: Jing Zhao, KokSheik Wong, Vishnu Monn Baskaran, Kiki Adhinugraha, David Taniar
🔗 **来源**: [https://arxiv.org/abs/2605.18175v1](https://arxiv.org/abs/2605.18175v1)

**摘要**
> The sonata form is a musically rich and hierarchically structured form that poses significant challenges for automatic analysis. While music structure analysis has seen strides of progress in recent years, sonata form analysis remains in its early stages. This is largely due to the time-consuming and high barrier of the music background requirement for annotating classical music structures. To advance research in this area, we curated SoSA-Moz, the first large-scale dataset featuring comprehensive hierarchical structure annotations. This work establishes a foundation for systematic sonata form analysis. Leveraging this newly contributed resource, we further propose Sonalyzer-Moz, a baseline model specifically designed for investigating complex sonata structures. This framework integrates feature aggregation with sequential modeling, enabling it to capture both local feature and upper-level structural dependencies. Experiment results show that Sonalyzer-Moz is capable of identifying the components' boundaries of the upper-level structure that are critical to understanding sonata form. Therefore, this method demonstrates, for the first time, the effectiveness of automatic upper-level analysis of sonata form, and provides a robust baseline for future research in the automatic understanding of sonata form while advancing the study of classical music structure analysis.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Sonalyzer-Moz: A Framework for Analyzing the Structure of Mozart's Sonata Form》所界定。 从摘要看，作者主要围绕 sonalyzer-moz、framework、analyzing 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiment results show that Sonalyzer-Moz is capable of identifying the components' boundaries of the upper-level structure that are critical to understanding sonata form. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sonalyzer-moz, framework, analyzing。 |

---
### 11. SIREM: Speech-Informed MRI Reconstruction with Learned Sampling

👤 **作者**: Md Hasan, Nyvenn Castro, Daiqi Liu, Lukas Mulzer, Jana Hutter, Jonghye Woo, Moritz Zaiss, Andreas Maier, Paula A. Perez-Toro
🔗 **来源**: [https://arxiv.org/abs/2605.18221v1](https://arxiv.org/abs/2605.18221v1)

**摘要**
> Real-time magnetic resonance imaging (rtMRI) of speech production enables non-invasive visualization of dynamic vocal-tract motion and is valuable for speech science and clinical assessment. However, rtMRI is fundamentally constrained by trade-offs among spatial resolution, temporal resolution, and acquisition speed, often leading to undersampled k-space measurements and degraded reconstructions. We propose SIREM, a speech-informed MRI reconstruction framework that uses synchronized speech as a cross-modal prior. The central idea is that vocal-tract configurations during speech are correlated with the produced acoustics, making part of the image content predictable from audio. SIREM models each frame as a fusion of an audio-driven component and an MRI-driven component through a spatial weighting map. The audio branch predicts articulator-related structure from speech, while the MRI branch reconstructs complementary content from measured k-space data. We further introduce a learnable soft weighting profile over spiral arms, enabling a differentiable study of how k-space arm usage interacts with speech-informed fusion. This yields a unified multimodal formulation that combines audio-driven prediction, MRI reconstruction, and sampling adaptation. We evaluate SIREM on the USC speech rtMRI benchmark against standard baselines, including gridding, wavelet-based compressed sensing, and total variation. SIREM introduces a speech-informed reconstruction paradigm that operates in a substantially higher-throughput regime than iterative methods while preserving anatomically plausible vocal-tract structure. These results establish an initial benchmark for multimodal speech-informed rtMRI reconstruction and highlight the potential of synchronized speech as an auxiliary prior for fast reconstruction. The source code is available at https://github.com/mdhasanai/SIREM

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SIREM: Speech-Informed MRI Reconstruction with Learned Sampling》所界定。 从摘要看，作者主要围绕 sirem、speech-informed、reconstruction 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, rtMRI is fundamentally constrained by trade-offs among spatial resolution, temporal resolution, and acquisition speed, often leading to undersampled k-space measurements and degraded reconstructions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sirem, speech-informed, reconstruction。 |

---
### 12. EnvTriCascade: An Environment-Aware Tri-Stage Cascaded Framework for ESDD2 2026 Challenge

👤 **作者**: Hengyan Huang, Xiaoxuan Guo, Jiayi Zhou, Yuankun Xie, Jian Liu, Haonan Cheng, Long Ye, Qin Zhang
🔗 **来源**: [https://arxiv.org/abs/2605.18409v1](https://arxiv.org/abs/2605.18409v1)

**摘要**
> ADD in real-world scenarios has evolved from speech-only spoofing to more challenging component-level settings, where speech and environmental sounds may be independently manipulated. To tackle this, we propose EnvTriCascade, an Environment-Aware Tri-Stage Cascaded framework for the ESDD2 Challenge. First, a mix-consistency detector provides a binary prior to distinguish original recordings from manipulated mixtures, which calibrates the final decisions. Next, two complementary five-class detectors, leveraging SSLAM+XLS-R and EAT-large+XLS-R representations, extract robust multi-branch features integrated via a cross-branch attention-gated classifier. To enhance robustness against diverse mixing conditions, we incorporate RawBoost augmentation. Trained exclusively on the official CompSpoofV2 dataset, our system achieves a Macro-F1 score of 0.8266 on the test set, significantly outperforming the official baseline and ranking second in the challenge.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《EnvTriCascade: An Environment-Aware Tri-Stage Cascaded Framework for ESDD2 2026 Challenge》所界定。 从摘要看，作者主要围绕 envtricascade、environment-aware、tri-stage 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Trained exclusively on the official CompSpoofV2 dataset, our system achieves a Macro-F1 score of 0.8266 on the test set, significantly outperforming the official baseline and ranking second in the challenge. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：envtricascade, environment-aware, tri-stage。 |

---
### 13. Flexible Multi-Channel Target Speaker Extraction Using Geometry-Conditioned Spatially Selective Non-linear Filters

👤 **作者**: Jiatong Li, Wiebke Middelberg, Simon Doclo
🔗 **来源**: [https://arxiv.org/abs/2605.18442v1](https://arxiv.org/abs/2605.18442v1)

**摘要**
> Recently, a spatially selective non-linear filter (SSF) has been proposed for target speaker extraction, using the target direction-of-arrival (DOA) as a spatial cue. Since learned intermediate features are tied to the microphone geometry, the performance of the SSF degrades significantly when evaluated on mismatched array geometries. In this paper, we propose a geometry-conditioned SSF (GC-SSF), which incorporates a geometry-conditioning branch based on FiLM layers. Furthermore, we propose a feature that jointly encodes the DOA and the microphone positions (DOA-MPE). The conditioning branch modulates the intermediate feature maps of the SSF using the DOA-MPE feature to capture the spatial relationship between the microphone positions and the target speaker. Experimental results across circular, uniform linear, and random microphone arrays show that the proposed GC-SSF generalizes better to mismatched geometries while maintaining high spatial selectivity, demonstrating its ability to effectively adapt the filtering process to different array geometries

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Flexible Multi-Channel Target Speaker Extraction Using Geometry-Conditioned Spatially Selective Non-linear Filters》所界定。 从摘要看，作者主要围绕 flexible、multi-channel、target 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results across circular, uniform linear, and random microphone arrays show that the proposed GC-SSF generalizes better to mismatched geometries while maintaining high spatial selectivity, demonstrating its ability to effectively adapt the filtering process to different array geometries 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：flexible, multi-channel, target。 |

---
### 14. SAME: A Semantically-Aligned Music Autoencoder

👤 **作者**: Julian D. Parker, Zach Evans, CJ Carr, Zachary Zukowski, Josiah Taylor, Matthew Rice, Jordi Pons
🔗 **来源**: [https://arxiv.org/abs/2605.18613v1](https://arxiv.org/abs/2605.18613v1)

**摘要**
> Latent representations are at the heart of the majority of modern generative models. In the audio domain they are typically produced by a neural-audio-codec autoencoder. In this work we introduce SAME (Semantically-Aligned Music autoEncoder), an autoencoder for stereo music and general audio that reaches a 4096$\times$ temporal compression ratio while maintaining reconstruction quality and downstream generative performance. We achieve this by combining a tranformer-based backbone with set of semantic regularisation approaches, phase-aware reconstruction losses and improved discriminator designs. The architecture delivers substantial computational cost benefits, through both its high compression ratio and its reliance on well-optimised transformer primitives. Two variants (a large SAME-L and a CPU-deployable SAME-S) are released in open-weights form.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SAME: A Semantically-Aligned Music Autoencoder》所界定。 从摘要看，作者主要围绕 same、semantically-aligned、music 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We achieve this by combining a tranformer-based backbone with set of semantic regularisation approaches, phase-aware reconstruction losses and improved discriminator designs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：same, semantically-aligned, music。 |

---
### 15. WavFlow: Audio Generation in Waveform Space

👤 **作者**: Feiyan Zhou, Luyuan Wang, Shoufa Chen, Zhe Wang, Zhiheng Liu, Yuren Cong, Xiaohui Zhang, Fanny Yang, Belinda Zeng
🔗 **来源**: [https://arxiv.org/abs/2605.18749v1](https://arxiv.org/abs/2605.18749v1)

**摘要**
> Modern audio generation predominantly relies on latent-space compression, introducing additional complexity and potential information loss. In this work, we challenge this paradigm with WavFlow, a framework that generates high-fidelity audio directly in raw waveform space without intermediate representations. To overcome the inherent difficulties of modeling high-dimensional and low-energy signals, we reshape audio into 2D token grids through waveform patchify and introduce amplitude lifting to align signal scales, enabling stable optimization via direct x-prediction in flow matching. To capture complex semantic alignment and temporal synchronization, we leverage an automated data pipeline to curate 5 million high-quality video-text-audio triplets, allowing the model to learn fine-grained acoustic patterns from scratch. Experimental results show that WavFlow achieves competitive performance on the video-to-audio benchmark VGGSound (FD_PaSST: 59.98, IS_PANNs: 17.40, DeSync: 0.44) and the text-to-audio benchmark AudioCaps (FD_PANNs: 10.63, IS_PANNs: 12.62), matching or exceeding the performance of established latent-based methods. Our work demonstrates that intermediate compression is not a prerequisite for high-quality synthesis, offering a simpler and more scalable alternative for multimodal audio generation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《WavFlow: Audio Generation in Waveform Space》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results show that WavFlow achieves competitive performance on the video-to-audio benchmark VGGSound (FD_PaSST: 59.98, IS_PANNs: 17.40, DeSync: 0.44) and the text-to-audio benchmark AudioCaps (FD_PANNs: 10.63, IS_PANNs: 12.62), matching or exceeding the performance of established latent-based methods. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---
### 16. A Survey of Large Audio Language Models: Generalization, Trustworthiness, and Outlook

👤 **作者**: Kaiwen Luo, Zhenhong Zhou, Leo Wang, Liang Lin, Yang Xiao, Tianyu Shao, Yuanhe Zhang, Yuxuan Li, Miao Yu, Kailin Lyu, Jiaming Zhang, Dongrui Liu, Li Sun, Yueming Wu, Kai Li, Ting Dang, Xiaojun Jia, Rohan Kumar Das, Xinfeng Li, Siyuan Liang, Qiufeng Wang, Xingjun Ma, Jing Chen, Kun Wang, Junhao Dong, Deqing Zou, Yu Cheng, Xia Hu, Zhigang Zeng, Sen Su, Yang Liu, Yu-Gang Jiang, Philip S. Yu, Yew-Soon Ong
🔗 **来源**: [https://arxiv.org/abs/2605.20266v1](https://arxiv.org/abs/2605.20266v1)

**摘要**
> The foundational capabilities established by Large Language Models (LLMs) have paved the way for Multimodal Large Language Models (MLLMs), within which Large Audio Language Models (LALMs) are essential for realizing universal auditory intelligence. Despite their remarkable performance, the escalation of LALMs' capabilities has significantly outpaced the development of systemic frameworks to ensure their trustworthiness. This survey provides a comprehensive investigation into the endogenous mechanisms of LALMs, detailing the architectural innovations and alignment algorithms that facilitate emergent reasoning. Specifically, we analyze how the transition to unified end-to-end frameworks and the integration of continuous acoustic signals inherently expand the attack surface. To rigorously evaluate the risks within these paradigms, we establish a comprehensive taxonomy of trustworthiness, categorizing critical vulnerabilities such as cross-modal jailbreaking, latent acoustic backdoors, and biometric privacy leakage. We review the state-of-the-art through six analytical pillars: hallucination, robustness, safety, privacy, fairness, and authentication. The profound imbalance between a mature offensive landscape and underdeveloped defenses further validates the critical trustworthiness gaps and multidimensional risks facing audio-centric intelligence. Finally, we propose a strategic roadmap advocating for "Defense-in-Depth" architectures, causal auditory world modeling, and intrinsic representation engineering to bridge the gap between empirical performance and intrinsically trustworthy audio intelligence. Our project has been uploaded to GitHub https://github.com/Kwwwww74/Awesome-Trustworthy-AudioLLMs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Survey of Large Audio Language Models: Generalization, Trustworthiness, and Outlook》所界定。 从摘要看，作者主要围绕 survey、large、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We review the state-of-the-art through six analytical pillars: hallucination, robustness, safety, privacy, fairness, and authentication. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：survey, large, audio。 |

---
### 17. Heterogeneity-Aware Dataset Scheduling for Efficient Audio Large Language Model Training

👤 **作者**: Yanru Wu, Jianning Wang, Chongxin Gan, Yang Li
🔗 **来源**: [https://arxiv.org/abs/2605.19101v1](https://arxiv.org/abs/2605.19101v1)

**摘要**
> Training general-purpose Audio Large Language Models (ALLMs) across diverse datasets is essential for holistic audio understanding, yet it faces significant challenges due to dataset heterogeneity, which often leads to conflicting gradients and slow convergence. Despite its impact, how to explicitly manage this heterogeneity during training remains underexplored, with current practices relying primarily on uniform mixture. In this work, we analyze multi-dataset AudioQA training from a convergence perspective and propose Grouped Sequential Training (GST). GST strategically organizes datasets into affinity-aware groups and introduces them via a progressive scheduling protocol, effectively balancing the stability of parallel training with the efficiency of sequential optimization. To ensure scalability, we develop gradient-based affinity metrics that capture inter-dataset relationships without the prohibitive cost of empirical transferability estimation. Extensive evaluations on 14 AudioQA datasets spanning speech, music, and environmental sounds demonstrate that GST achieves 30--40\% faster convergence than standard parallel training while maintaining or even surpassing the performance of mix-all training. Our results provide both theoretical insights and a practical, model-agnostic framework for efficient large-scale ALLM optimization.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Heterogeneity-Aware Dataset Scheduling for Efficient Audio Large Language Model Training》所界定。 从摘要看，作者主要围绕 heterogeneity-aware、dataset、scheduling 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive evaluations on 14 AudioQA datasets spanning speech, music, and environmental sounds demonstrate that GST achieves 30--40\% faster convergence than standard parallel training while maintaining or even surpassing the performance of mix-all training. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：heterogeneity-aware, dataset, scheduling。 |

---
### 18. Optimising Neural Speech Codecs for 300bps Communication using Reinforcement Learning

👤 **作者**: Junyi Wang, Chi Zhang, Jing Qian, Haifeng Luo, Hao Wang, Zengrui Jin, Chao Zhang
🔗 **来源**: [https://arxiv.org/abs/2605.19541v1](https://arxiv.org/abs/2605.19541v1)

**摘要**
> In bandwidth-constrained communication such as satellite and underwater channels, speech must often be transmitted at ultra-low bitrates where intelligibility is the primary objective. At such extreme compression levels, codecs trained with acoustic reconstruction losses tend to allocate bits to perceptual detail, leading to substantial degradation in word error rate (WER). This paper proposes ClariCodec, a neural speech codec operating at 300 bit per second (bps) that reformulates quantisation as a stochastic policy, enabling reinforcement learning (RL)-based optimisation of intelligibility. Specifically, the encoder is fine-tuned using WER-driven rewards while the acoustic reconstruction pipeline remains frozen. Even without RL, ClariCodec achieves 4.64% WER on the LibriSpeech test-clean set at 300 bps, already competitive with codecs operating at higher bitrates. Further RL fine-tuning reduces WER to 3.55% on test-clean and 10.4% on test-other, corresponding to a 23% relative reduction while preserving perceptual quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Optimising Neural Speech Codecs for 300bps Communication using Reinforcement Learning》所界定。 从摘要看，作者主要围绕 optimising、neural、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Even without RL, ClariCodec achieves 4.64% WER on the LibriSpeech test-clean set at 300 bps, already competitive with codecs operating at higher bitrates. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：optimising, neural, speech。 |

---
### 19. Executable Boundary Contracts for Sound Event Traces

👤 **作者**: Faruk Alpay, Hamdi Alakkad
🔗 **来源**: [https://arxiv.org/abs/2605.19632v1](https://arxiv.org/abs/2605.19632v1)

**摘要**
> Sound event reports often compress timed boundary behavior into frame, segment, or event scores. This paper defines executable boundary contracts for finite sound event traces. The frame fragment is a bounded Boolean fragment embeddable in STL after grid projection. The event layer adds declared interval matching, duration clauses, fragmentation clauses, and obligation restricted vector scoring. The aim is measurement, not a new general temporal logic and not a challenge leaderboard. The artifact evaluates controlled Mini LibriSpeech seeded scenes, MAESTRO Real soundscapes, frozen pretrained timing probes, and an official DCASE 2024 Task 4 baseline track. Across these tracks, standard scores and contract coordinates disagree in interpretable ways. The strongest real corpus finding is that union activity can hide typed boundary failure, while external DCASE outputs provide a class indexed challenge level reference. Code, generated tables, manifests, and Lean checks for the finite frame core are supplied as ancillary material.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Executable Boundary Contracts for Sound Event Traces》所界定。 从摘要看，作者主要围绕 executable、boundary、contracts 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper defines executable boundary contracts for finite sound event traces. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：executable, boundary, contracts。 |

---
### 20. DASM: Domain-Aware Sharpness Minimization for Multi-Domain Voice Stream Steganalysis

👤 **作者**: Pengcheng Zhou, Pianran Guo, Shuhua Chen, Mengqin Zhao, Zhongliang Yang, Linna Zhou
🔗 **来源**: [https://arxiv.org/abs/2605.19955v2](https://arxiv.org/abs/2605.19955v2)

**摘要**
> The growing use of information hiding in network streaming media for covert communication poses a significant security threat, necessitating the development of robust detection technologies. However, existing steganalysis methods for network voice streams mostly rely on data distributions in specific scenarios, making it difficult to adapt to the practical detection needs of non-homologous data distributions. Through Hessian analysis, we find that the loss landscapes of mainstream models are dominated by numerous saddle points and sharp local minima, rendering them highly sensitive to data distribution shifts and fundamentally limiting generalization. Therefore, we propose a new optimizer, Domain-Aware Sharpness Minimization (DASM). The core mechanisms of DASM consist of two aspects: first, it integrates domain-supervised contrastive learning with sharpness-aware optimization, explicitly preserving inter-domain feature separation while seeking flat minima; second, we design an adaptive domain gap modulation strategy that dynamically calibrates the optimization loss weights by sensing the real-time feature separability of different domains. Extensive experimental results demonstrate that our method outperforms the state-of-the-art methods by a large margin and achieves excellent generalization and robustness.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《DASM: Domain-Aware Sharpness Minimization for Multi-Domain Voice Stream Steganalysis》所界定。 从摘要看，作者主要围绕 dasm、domain-aware、sharpness 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Extensive experimental results demonstrate that our method outperforms the state-of-the-art methods by a large margin and achieves excellent generalization and robustness. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dasm, domain-aware, sharpness。 |

---
### 21. A conceptual framework for learning to listen by reward: Curiosity-driven search for novel sources

👤 **作者**: Andreas Triantafyllopoulos, Jakub Šťastný, Alexios Terpinas, Tianyi Liu, Yuanqi Wang, Björn W. Schuller
🔗 **来源**: [https://arxiv.org/abs/2605.19984v1](https://arxiv.org/abs/2605.19984v1)

**摘要**
> Reinforcement learning is a powerful learning paradigm that has spearheaded progress in numerous domains. Its core promise lies in learning through high-level goals without the need for granular labels. However, it still remains elusive in the realm of audio, where it has received substantially less attention than in computer vision or other domains. The key question remains: how can agents learn to listen purely via reward-driven exploration? In this contribution, we present an overview of previous attempts and a new conceptual framework for learning to listen by reward. Our approach depends on the continuous search for novel sound sources. We formulate our framework, discuss open technical challenges, and present a first proof-of-concept implementation that showcases the feasibility of our approach.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A conceptual framework for learning to listen by reward: Curiosity-driven search for novel sources》所界定。 从摘要看，作者主要围绕 conceptual、framework、learning 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We formulate our framework, discuss open technical challenges, and present a first proof-of-concept implementation that showcases the feasibility of our approach. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：conceptual, framework, learning。 |

---
### 22. Precise and Simple Audio-to-Score Alignment

👤 **作者**: Silvan Peter, Patricia Hu, Gerhard Widmer
🔗 **来源**: [https://arxiv.org/abs/2605.20014v1](https://arxiv.org/abs/2605.20014v1)

**摘要**
> Audio-to-score alignment is a long-standing challenge in music information retrieval and arguably the most widely applicable alignment task for music research. Alignment algorithms match two versions of a piece of music, and for this to work these versions need to be in comparable formats. Audio-to-audio alignment matches audio features; when matching audio files to scores, they must either synthesize the score or derive audio-like features by means of piano rolls or similar feature sequences. Symbolic alignment, by contrast, matches symbolically encoded notes; in an audio-to-score scenario these would be obtained by a transcription of the audio file. In this article, we present an algorithm that bridges audio-like and symbol-level features directly. Sequential audio features encoding onset and spectral activation are matched to score positions by a bespoke dynamic programming-based matching algorithm derived from symbolic alignment methods. The resulting method is both precise - surpassing widely used audio-to-audio approaches based on synthesized scores -, and remains flexible in its digital signal processing components, i.e., the method is adaptable to diverse timbral characteristics without requiring a separate transcription model. Furthermore it inherits some of the symbolic alignment runtime advantages with an algorithmic complexity that is at worst linear in the length of the (typically short) symbolic score and (typically long) audio feature sequence. In the following sections, we provide a detailed algorithm description and evaluate its alignment quality on a large-scale dataset of solo piano recordings.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Precise and Simple Audio-to-Score Alignment》所界定。 从摘要看，作者主要围绕 music information retrieval 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Alignment algorithms match two versions of a piece of music, and for this to work these versions need to be in comparable formats. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：music information retrieval。 |

---
### 23. Music of Changing Lines: Toward a Culturally Situated Approach to the I-Ching

👤 **作者**: Ling Qi, Aleksandra Teng Ma, Alexandria Smith
🔗 **来源**: [https://arxiv.org/abs/2605.20386v1](https://arxiv.org/abs/2605.20386v1)

**摘要**
> The I-Ching is one of the most influential texts in Chinese intellectual history, integrating divination, cosmology, and ethical reflection. While Western experimental music, most notably John Cage, has drawn on the I-Ching as a source of chance operation, such appropriations have often detached its formal mechanisms from the interpretive and philosophical processes that give the text meaning. This work, Music of Changing Lines, presents an interactive system that re-centers the I-Ching as a meaning-bearing framework rather than a neutral randomizer. Users perform Wen Wang Fa coin casting, which is accompanied in real time through probabilistic musical processes. The resulting hexagrams and changing lines are interpreted by a large language model, Gemini, in relation to the user's inquiry. This textual interpretation is then translated into a prompt for a generative music model, Lyria, producing a responsive musical realization. By situating AI as an interpretive intermediary rather than a compositional authority, the system foregrounds the I-Ching's ritual, interpretation, and participation as the primary sonic materials. Music of Changing Lines extends process-driven traditions in computer music by demonstrating how generative AI can support participatory, meaning-driven musical processes without prescribing musical structure or replacing human agency.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Music of Changing Lines: Toward a Culturally Situated Approach to the I-Ching》所界定。 从摘要看，作者主要围绕 music、changing、lines 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Music of Changing Lines extends process-driven traditions in computer music by demonstrating how generative AI can support participatory, meaning-driven musical processes without prescribing musical structure or replacing human agency. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：music, changing, lines。 |

---
### 24. Causal Spatio-Temporal Sound Field Reconstruction

👤 **作者**: David Sundström, Filip Tronarp, Johan Lindström, Andreas Jakobsson
🔗 **来源**: [https://arxiv.org/abs/2605.20403v1](https://arxiv.org/abs/2605.20403v1)

**摘要**
> In sound field control applications, it is commonly assumed that one has access to an accurate representation of the sound field in the region of interest. This is a problematic assumption since the reconstruction of a sound field from available microphone measurements is especially challenging in real-time applications where only causal measurements are available. Notably, causal time-windowed observations introduce correlation between frequency components, making sound field reconstruction methods that process each frequency band independently sub-optimal. In this work, we formulate a causal finite-window spatio-temporal linear minimum mean-square error estimator for sound field reconstruction. The sound field is modeled as the solution to the wave equation driven by a stationary stochastic spatio-temporal source distribution, which induces a physically interpretable covariance function. It is shown that this covariance function is closely related to the classical diffuse-field coherence model. Since the computational complexity grows rapidly with the number of spatio-temporal observations, we formulate a budget-constrained spatio-temporal sample selection approach to minimize the posterior reconstruction variance. The proposed estimator and sampling strategy are evaluated using both simulated and measured sound fields, demonstrating improved short-window reconstruction compared to frequency domain finite-window baselines.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Causal Spatio-Temporal Sound Field Reconstruction》所界定。 从摘要看，作者主要围绕 causal、spatio-temporal、sound 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：It is shown that this covariance function is closely related to the classical diffuse-field coherence model. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：causal, spatio-temporal, sound。 |

---
### 25. PlanRAG-Audio: Planning and Retrieval Augmented Generation for Long-form Audio Understanding

👤 **作者**: Masao, Someki, Chien-yu, Huang, Siddhant, Arora, Samuele, Cornell, Markus, Müller, Nathan, Susanj, Rupak V, Swaminathan, Grant P, Strimel, Jing, Liu, Shinji, Watanabe
🔗 **来源**: [https://arxiv.org/abs/2605.20414v1](https://arxiv.org/abs/2605.20414v1)

**摘要**
> Long-form audio understanding poses significant challenges for large audio language models (LALMs) due to the extreme length of audio sequences and the need to reason over heterogeneous acoustic cues distributed over time, such as speech content, speaker identity, emotion, and sound events. To address these challenges, we propose \textbf{PlanRAG-Audio}, a planning-based retrieval-augmented generation framework for scalable long-form audio understanding. Rather than having audio LALMs process entire recordings directly, PlanRAG-Audio explicitly plans which modalities and temporal spans are required for a given query, and retrieves only query-relevant information from a structured text and audio database. This retrieval planning enables effective reasoning over complex, cross-domain audio queries while substantially reducing the input length passed to the large language models. Experiments across a wide range of speech/audio retrieval demonstrate that PlanRAG-Audio improves reasoning accuracy and stabilizes performance as audio duration increases by decoupling inference cost from raw audio length.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《PlanRAG-Audio: Planning and Retrieval Augmented Generation for Long-form Audio Understanding》所界定。 从摘要看，作者主要围绕 planrag-audio、planning、retrieval 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments across a wide range of speech/audio retrieval demonstrate that PlanRAG-Audio improves reasoning accuracy and stabilizes performance as audio duration increases by decoupling inference cost from raw audio length. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：planrag-audio, planning, retrieval。 |

---
### 26. A strongly annotated passive acoustic dataset for tropical bird monitoring

👤 **作者**: Daniela Ruiz, Juan Sebastián Ulloa, Zhongqi Miao, Nicolás Betancourt, Maria Paula Toro-Gómez, Andrés Hernández, Bruno Demuro, Eliana Barona-Cortés, Angela Mendoza-Henao, Andrés Sierra-Ricaurte, Sebastián Pérez-Peña, Rahul Dodhia, Pablo Arbeláez, Juan M. Lavista Ferres
🔗 **来源**: [https://arxiv.org/abs/2605.20578v2](https://arxiv.org/abs/2605.20578v2)

**摘要**
> Passive acoustic monitoring enables continuous, non-invasive biodiversity assessment across diverse ecosystems. The scale of these datasets has driven the adoption of machine learning, with supervised approaches showing strong performance. However, supervised methods require time-resolved annotated datasets, which remain scarce, especially in complex tropical soundscapes. We present PteroSet, a curated dataset of strongly annotated Neotropical bird vocalizations recorded in Puerto Asis (Putumayo) and Pivijay (Magdalena), Colombia, between 2023 and 2025. The dataset comprises 563 recordings (73.62 h) and 15,372 time-frequency annotations, including 6,702 events identified to the species level across 168 species. We release the annotations in a COCO-inspired JSON schema that unifies audio files, taxonomic categories, and labels for machine learning workflows. Beyond providing annotated data, PteroSet serves as a realistic benchmark that highlights key characteristics of tropical soundscapes, including acoustic co-occurrence and domain shift across recording sites. We provide a deep learning baseline for binary bird detection, demonstrating PteroSet's usability and the challenges it presents.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A strongly annotated passive acoustic dataset for tropical bird monitoring》所界定。 从摘要看，作者主要围绕 strongly、annotated、passive 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The scale of these datasets has driven the adoption of machine learning, with supervised approaches showing strong performance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：strongly, annotated, passive。 |

---
### 27. Academic Text-to-Music Grand Challenge: Datasets, Baselines, and Evaluation Methods

👤 **作者**: Fang-Chih Hsieh, Wei-Jaw Lee, Chun-Ping Wang, Hung-yi Lee, Hao-Wen Dong, Yi-Hsuan Yang
🔗 **来源**: [https://arxiv.org/abs/2605.21538v1](https://arxiv.org/abs/2605.21538v1)

**摘要**
> This paper presents an overview and the technical framework of the ICME 2026 Grand Challenge on Academic Text-to-Music Generation (ATTM). Despite the rapid progress in text-to-music generation (TTM) systems, the field is currently dominated by models trained on massive proprietary datasets with industrial-scale computational resources, creating a significant barrier for academic research. To address this, the ATTM Challenge establishes a fair-play benchmark that requires participants to train generative models strictly from scratch using a standardized, CC-licensed subset of the MTG-Jamendo dataset containing only instrumental music. The challenge is divided into two tracks: the Efficiency Track (limited to 500M parameters) and the Performance Track (no parameter limit). Submissions are evaluated through a multi-stage process involving objective metrics, including Frechet Audio Distance, CLAP score, and a novel Concept Coverage Score (CCS), followed by a subjective listening test. By providing open-source baselines, preprocessing pipelines, reference captions, and public evaluation code for computing FAD and CLAP, this challenge aims to facilitate and promote TTM research in academic contexts.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Academic Text-to-Music Grand Challenge: Datasets, Baselines, and Evaluation Methods》所界定。 从摘要看，作者主要围绕 academic、text-to-music、grand 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Despite the rapid progress in text-to-music generation (TTM) systems, the field is currently dominated by models trained on massive proprietary datasets with industrial-scale computational resources, creating a significant barrier for academic research. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：academic, text-to-music, grand。 |

---
### 28. SEABAD: A Tropical Bird Activity Detection Dataset for Passive Acoustic Monitoring

👤 **作者**: Muhammad Mun'im Ahmad Zabidi, Mohd Yamani Idna Idris, Norisma Idris
🔗 **来源**: [https://arxiv.org/abs/2605.20853v1](https://arxiv.org/abs/2605.20853v1)

**摘要**
> Passive acoustic monitoring (PAM) enables large-scale biodiversity assessment, but continuous recording generates large amounts of non-informative audio, creating challenges for storage, power consumption, and long-term edge deployment. Bird audio detection (BAD), which identifies bird vocalizations, can reduce this burden by filtering irrelevant recordings before downstream analysis. However, most BAD systems are trained on temperate datasets despite tropical soundscapes being denser, more species-rich, and acoustically unpredictable. To address this gap, we introduce SEABAD (Southeast Asian Bird Activity Detection), a dataset of 50,000 curated three-second clips from Southeast Asian soundscapes, evenly balanced between bird-present and bird-absent samples. The dataset spans 1,677 bird species and is standardized to 16 kHz mono audio for embedded and low-power inference. We developed a dual-branch curation pipeline: a six-stage positive-label workflow applied to Xeno-Canto recordings, alongside six source-specific negative-label extractions from environmental datasets. These procedures reduced class imbalance by 13.7% (Gini coefficient: 0.601 to 0.519). A manual audit of 1,000 positive clips confirmed 97.8% +/- 0.9% labeling accuracy. Baseline experiments using MobileNetV3-Small achieved 99.57% +/- 0.25% accuracy and 0.9985 +/- 0.0002 AUC across three random seeds. SEABAD and the full curation pipeline are publicly released to support tropical BAD research and energy-efficient acoustic monitoring.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SEABAD: A Tropical Bird Activity Detection Dataset for Passive Acoustic Monitoring》所界定。 从摘要看，作者主要围绕 seabad、tropical、bird 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Baseline experiments using MobileNetV3-Small achieved 99.57% +/- 0.25% accuracy and 0.9985 +/- 0.0002 AUC across three random seeds. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：seabad, tropical, bird。 |

---
### 29. From Numbers to Perception, Energy Decay Curves Prediction

👤 **作者**: Imran Muhammad, Gerald Schuller
🔗 **来源**: [https://arxiv.org/abs/2605.20968v1](https://arxiv.org/abs/2605.20968v1)

**摘要**
> Predicting Room Impulse Responses (RIRs) remains a challenge due to the high dimensionality of audio signals and the need for perceptual accuracy. This paper introduces a neural network framework that predicts multi-band Energy Decay Curves (EDCs) directly from room geometry and material properties. Unlike standard models, our framework employs a custom composite loss function that optimizes for both energy levels and decay slopes in the log-domain. This ensures the predicted curves adhere to physical decay principles while maintaining high sensitivity to reverberation time and early reflections. Results demonstrate that the model successfully approximates ground-truth acoustics with minimal error in T30 and clarity indices. The approach offers a computationally efficient alternative to traditional simulations, facilitating realistic audio rendering for interactive virtual environments.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《From Numbers to Perception, Energy Decay Curves Prediction》所界定。 从摘要看，作者主要围绕 from、numbers、perception 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results demonstrate that the model successfully approximates ground-truth acoustics with minimal error in T30 and clarity indices. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：from, numbers, perception。 |

---
### 30. A Survey of Audio Reasoning in Multimodal Foundation Models

👤 **作者**: Zhihan Guo, Wenqian Cui, Guan-Ting Lin, Daxin Tan, Jingyao Li, Qiyong Zheng, Dingdong Wang, Jing Xiong, Han Shi, Jiaya Jia, Irwin King
🔗 **来源**: [https://arxiv.org/abs/2605.21008v1](https://arxiv.org/abs/2605.21008v1)

**摘要**
> Reasoning has become a defining capability of modern foundation models, yet its development in the audio modality remains limited. Audio poses challenges that are distinct from those of text and vision. It is continuous, temporally dense, and contains linguistic, paralinguistic, and environmental information at multiple time scales. As a result, audio reasoning models must align acoustic signals with the discrete semantic space of large language models, while still preserving fine-grained information needed for reliable inference. Progress is also limited by three major obstacles: the scarcity of genuinely audio-grounded reasoning data, shortcut learning and modality hallucination, and the tension between reasoning depth and real-time latency in spoken interaction. In this paper, we present the first dedicated survey of audio reasoning. We provide a unified formulation that distinguishes direct predictive modeling from reasoning-augmented generation, review the architectural and training foundations of audio reasoning models, and systematically organize recent advances in Audio-to-Text, Audio-to-Speech, Audio-Visual Reasoning and Agentic Audio Reasoning. We further examine emerging paradigms such as Chain-of-Thought prompting, supervised fine-tuning, reinforcement learning, and latency-aware spoken interaction, and discuss evaluation practices, open challenges, and future directions. Our goal is to offer a coherent roadmap for developing robust, efficient, and natively grounded audio reasoning systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Survey of Audio Reasoning in Multimodal Foundation Models》所界定。 从摘要看，作者主要围绕 survey、audio、reasoning 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Audio poses challenges that are distinct from those of text and vision. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：survey, audio, reasoning。 |

---
### 31. Musical Attention Transformer: Music Generation Using a Music-Specific Attention Model

👤 **作者**: Shinnosuke Taksuka, Hideo Mukai
🔗 **来源**: [https://arxiv.org/abs/2605.21081v1](https://arxiv.org/abs/2605.21081v1)

**摘要**
> This study aims to enhance the quality of music generation using Transformers by incorporating meta-information. While Transformer-based approaches are effective at capturing long-term dependencies in musical compositions, the music they generate often suffers from issues such as excessive repetition or duplication of notes, leading to unnatural melodies. To address these limitations, we propose Musical Attention, a mechanism that incorporates meta-information such as bar numbers, key, signatures, and tempos into the attention process. Musical Attention explicitly leverages both the structural properties of music and its associated metadata, enabling the Transformer's attention mechanism to operate more effectively and thereby improving the quality of the generated output. In our framework, each musical note is represented as a combination of five events-pitch, bar number, onset, duration, and velocity in addition to the three metadata elements. The attention mechanism is then modified to reflect the correlations among these eight features, allowing the model to better capture the inherent characteristics of musical composition. Experimental results demonstrate that the model incorporating Musical Attention outperforms prior methods, such as Full Attention and Strided Attention, in terms of musical coherence, variation, and overall quality. Notably, it significantly reduces repetition and enhances the model's ability to generate diverse, harmonically consistent melodies. Musical Attention thus represents a meaningful advancement in AI-driven music generation, facilitating the creation of more natural and expressive compositions.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Musical Attention Transformer: Music Generation Using a Music-Specific Attention Model》所界定。 从摘要看，作者主要围绕 musical、attention、transformer 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Musical Attention explicitly leverages both the structural properties of music and its associated metadata, enabling the Transformer's attention mechanism to operate more effectively and thereby improving the quality of the generated output. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：musical, attention, transformer。 |

---
### 32. CoarseSoundNet: Building a reliable model for ecological soundscape analysis

👤 **作者**: Alexander Gebhard, Andreas Triantafyllopoulos, Dominik Arend, Sandra Müller, Svenja Schmidt, Michael Scherer-Lorenzen, Björn W. Schuller
🔗 **来源**: [https://arxiv.org/abs/2605.21143v2](https://arxiv.org/abs/2605.21143v2)

**摘要**
> A soundscape is composed of three types of sound: biophony (sounds made by animals), geophony (natural abiotic sounds) and anthropophony (sounds made by humans). A key research question in the field of soundscape ecology is how these components interact with each other, specifically how biophony responds to geophony and anthropophony. Nevertheless, as of today, there are not many analytical instruments that enable the distinct quantification of these elements. Recent machine learning (ML) approaches aim to support automated analysis but often rely on task-specific or clean data, limiting generalisation to noisy passive acoustic monitoring (PAM) recordings. This study presents a clear and reproducible structure to build ML models for coarse soundscape classification and introduces CoarseSoundNet, a deep learning model trained to distinguish biophony, geophony, and anthropophony under realistic PAM conditions. We systematically investigate model architectures, the influence of an additional training class, data composition, and evaluation strategies. Our findings suggest that model performance improves with additional PAM data, especially when similar to the target domain, and by introducing an explicit silence class during training. Class-specific decision thresholds and duration-based constraints further enhance performance, particularly for anthropophony and geophony. Error analyses exhibit challenges for anthropophony due to masking effects and confusions for silence and insect sounds for geophony and biophony. Finally, we conduct an ecological case study which shows that pre-filtering recordings with CoarseSoundNet yields acoustic index trends comparable to ground-truth filtering, supporting its use as an effective preprocessing tool for ecoacoustic analyses.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CoarseSoundNet: Building a reliable model for ecological soundscape analysis》所界定。 从摘要看，作者主要围绕 coarsesoundnet、building、reliable 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our findings suggest that model performance improves with additional PAM data, especially when similar to the target domain, and by introducing an explicit silence class during training. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：coarsesoundnet, building, reliable。 |

---
### 33. Speech Quality Embeddings for Improved Detection and Classification of Degradations in Speech Signals

👤 **作者**: Michael Kuhlmann, Tobias Cord-Landwehr, Reinhold Haeb-Umbach
🔗 **来源**: [https://arxiv.org/abs/2605.21332v1](https://arxiv.org/abs/2605.21332v1)

**摘要**
> Automatic subjective speech quality assessment (SSQA) traditionally estimates speech quality on an utterance or system level. While this resolution was adequate for older transmission or synthesis systems that produced speech signals of mediocre quality, modern systems generate high-quality speech with degradations that may occur only locally. With suitable model architectures and regularization losses, SSQA models trained with utterance-level targets can also yield useful local predictions of speech quality. In this work, we extend such models to produce frame-level embeddings that cluster by degradation type. Specifically, we employ a partial mix-up strategy on a parallel corpus of clean and degraded utterances and apply a contrastive loss to distinguish between degradation types. Through experiments on both in- and out-of-domain data, we demonstrate that our approach improves degradation detection and enables the identification of degradation types by analyzing embedding clusters.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Speech Quality Embeddings for Improved Detection and Classification of Degradations in Speech Signals》所界定。 从摘要看，作者主要围绕 speech、quality、embeddings 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Through experiments on both in- and out-of-domain data, we demonstrate that our approach improves degradation detection and enables the identification of degradation types by analyzing embedding clusters. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech, quality, embeddings。 |

---
### 34. Instrumental Text-to-Music Generation with Auxiliary Conditioning Branches

👤 **作者**: Junyoung Koh
🔗 **来源**: [https://arxiv.org/abs/2605.21433v1](https://arxiv.org/abs/2605.21433v1)

**摘要**
> Text-to-music generation has advanced rapidly, with modern autoregressive and diffusion-based models producing convincing music from natural-language prompts. However, much of this progress relies on large-scale training data and external pretraining, making it difficult to isolate which design choices remain effective when data and pretraining are controlled. We study this setting using a Diffusion Transformer backbone with lyric and timbre conditioning, adapted to an instrumental-only text-to-music task in which the auxiliary lyric and timbre branches receive only degenerate conditioning signals. Through controlled ablations, we find that models retrained without these branches score lower across AudioBox aesthetics, LLM-as-judge, and human MOS, and that reinvesting the saved parameters as additional DiT depth recovers only marginally. This suggests the auxiliary branches may act as training-time architectural anchors whose contribution goes beyond their explicit conditioning content. We validate the same model through comparisons with external instrumental baselines and through our submission to the ICME 2026 Academic Text-to-Music (ATTM) Grand Challenge, where our Performance submission ranked first under both the objective metrics and the subsequent organizer-administered MOS over 35 raters, attaining the highest overall MOS across all challenge submissions, while our Efficiency submission was a finalist that tied for second under the objective metrics.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Instrumental Text-to-Music Generation with Auxiliary Conditioning Branches》所界定。 从摘要看，作者主要围绕 instrumental、text-to-music、generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, much of this progress relies on large-scale training data and external pretraining, making it difficult to isolate which design choices remain effective when data and pretraining are controlled. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：instrumental, text-to-music, generation。 |

---
### 35. Real-time, EDM-inspired sonfication of the activity of a supercomputer

👤 **作者**: Marco Alunno, Paolo Bientinesi
🔗 **来源**: [https://arxiv.org/abs/2605.21874v1](https://arxiv.org/abs/2605.21874v1)

**摘要**
> The project described in this paper explores the informative sonification of data received in real time from a supercomputer. These data capture the current activities in all the nodes of the computer, therefore, their sonification functions as a form of continuous monitoring of the nodes' behavior and, by extension, of the system as a whole. Because such monitoring is theoretically unending, the resulting sonification must be musically capable of conveying information through sound in a way that remains both intelligible and engaging over long durations. Rather than imposing a predefined musical style onto the data, we sought to identify one which the data themselves could plausibly support. From a small set of candidates, we selected EDM because it is a family of genres whose structural and temporal characteristics align well with continuous, data-driven processes and long-term listening. Through this style-based approach, this research builds on the long tradition of computer data sonification while uniquely combining three elements rarely addressed together: monitoring (rather than debugging) as the primary goal, real-time (rather than post-mortem) data interpretation, and generation of virtually infinite and stylistically coherent (rather than incongruous) music.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Real-time, EDM-inspired sonfication of the activity of a supercomputer》所界定。 从摘要看，作者主要围绕 real-time、edm-inspired、sonfication 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These data capture the current activities in all the nodes of the computer, therefore, their sonification functions as a form of continuous monitoring of the nodes' behavior and, by extension, of the system as a whole. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：real-time, edm-inspired, sonfication。 |

---
### 36. Neighbor-Consistent Neural Filters for Robust Personal Sound Zones Under Localization Uncertainty

👤 **作者**: Hao Jiang, Edgar Choueiri
🔗 **来源**: [https://arxiv.org/abs/2605.21891v1](https://arxiv.org/abs/2605.21891v1)

**摘要**
> Coordinate-conditioned neural networks can generate head-tracked personal sound zone (PSZ) loudspeaker filters in real time, but they are sensitive to localization uncertainty. Small fluctuations in estimated listener coordinates, caused by optical distortion, temporary occlusions, or tracking jitter, may produce large filter changes even when listeners are physically stationary. This paper proposes neighbor-consistent neural filters that regularize the coordinate-to-filter mapping by penalizing filter differences at randomly perturbed neighboring coordinates during training. To evaluate robustness against tracking noise, we introduce a decoupled protocol that fixes the acoustic transfer functions at a physical anchor while perturbing only the coordinate inputs used for filter generation. Isolation quality and local stability are evaluated using neighborhood median and lower-tail statistics of inter-zone and inter-program isolation, together with spatial variation rates that quantify metric sensitivity within a coordinate neighborhood. In simulation with a split-band woofer-tweeter system and 25 randomly sampled anchor positions, neighbor consistency reduces the root-mean-square (RMS) variation rate by up to 55.9% in the woofer band and 30.3% in the tweeter band while largely preserving isolation quality and improving lower-tail robustness. In in-situ measurements using a 24-driver array and two stationary head-and-torso simulators, the proposed regularization improves worst-case neighborhood isolation by up to 16.9% and reduces spatial variation rates by up to 61.8%. These results demonstrate that neighbor-consistency regularization effectively stabilizes PSZ rendering under localization uncertainty.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Neighbor-Consistent Neural Filters for Robust Personal Sound Zones Under Localization Uncertainty》所界定。 从摘要看，作者主要围绕 neighbor-consistent、neural、filters 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In simulation with a split-band woofer-tweeter system and 25 randomly sampled anchor positions, neighbor consistency reduces the root-mean-square (RMS) variation rate by up to 55.9% in the woofer band and 30.3% in the tweeter band while largely preserving isolation quality and improving lower-tail robustness. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：neighbor-consistent, neural, filters。 |

---
### 37. Effective User-defined Keyword Spotting with Dual-stage Matching, Multi-modal Enrollment, and Continual Adaptation

👤 **作者**: Zhiqi Ai, Han Cheng, Shiyi Mu, Xinnuo Li, Yongjin Zhou, Shugong Xu
🔗 **来源**: [https://arxiv.org/abs/2605.22120v1](https://arxiv.org/abs/2605.22120v1)

**摘要**
> User-defined keyword spotting (KWS) is crucial for personalized voice interaction, yet existing methods face several challenges: (1) insufficient discriminability among confusable words, (2) performance inconsistency across speakers with varying pronunciations, and (3) high data cost to ensure reliable wake-word performance. In this paper, we introduce DMA-KWS, an efficient and robust framework for user-defined keyword spotting. First, it adopts a dual-stage matching pipeline: CTC decoding with streaming phoneme search to locate candidate segments, followed by QbyT with a phoneme matcher for fine-grained verification, enabling it to better distinguish confusable words. Next, multi-modal enrollment fuses user-specific speech with text embeddings to further improve accuracy for registered users. Finally, a parameter-efficient continual adaptation mechanism performs lightweight updates using synthetic and real data. Extensive experiments demonstrate the superior performance of DMA-KWS. On the LibriPhrase Hard subset, it achieves 97.85% AUC and 6.13% EER, reaching state-of-the-art performance. In speaker-dependent settings, DMA-KWS consistently outperforms text-only enrollment, demonstrating significant performance gains. Moreover, the proposed parameter-efficient fine-tuning mechanism adapts DMA-KWS with only 187k updated parameters, further enhancing KWS performance while ensuring suitability for on-device deployment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Effective User-defined Keyword Spotting with Dual-stage Matching, Multi-modal Enrollment, and Continual Adaptation》所界定。 从摘要看，作者主要围绕 effective、user-defined、keyword 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Next, multi-modal enrollment fuses user-specific speech with text embeddings to further improve accuracy for registered users. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：effective, user-defined, keyword。 |

---
### 38. Automatic Contextual Audio Denoising

👤 **作者**: Diep Luong, Konstantinos Drossos, Mikko Heikkinen, Tuomas Virtanen
🔗 **来源**: [https://arxiv.org/abs/2605.22262v1](https://arxiv.org/abs/2605.22262v1)

**摘要**
> Audio context determines which sound components and sources are relevant and which can be perceived as irrelevant (noise) by listeners. For example, traffic noise is informative in urban surveillance but noise for a phone call at the same location. Most current audio denoising systems apply fixed target-noise definitions, often removing useful components in one context while failing to suppress irrelevant components. To address this, we introduce the concept automatic contextual audio denoising (ACAD) which defines target and noise based on the inferred context. In this work, we restrict context to be associated with an acoustic scene class. We label sound events outside the event distribution of a scene class (noise) as out-of-context (OC) and events typical for that scene as in-context (IC). We implement a deep learning method that automatically infers the context of the audio signal and removes OC components, and benchmark it against variants: without context inference, with oracle context, and with separately provided uninformative context. On paired clean/noisy data across diverse contexts, where OC components in one context may be IC in another, our proposed method outperforms other approaches across standard objective metrics, indicating that the model can infer context and context-dependent processing can enhance denoising.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Automatic Contextual Audio Denoising》所界定。 从摘要看，作者主要围绕 acoustic scene 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On paired clean/noisy data across diverse contexts, where OC components in one context may be IC in another, our proposed method outperforms other approaches across standard objective metrics, indicating that the model can infer context and context-dependent processing can enhance denoising. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：acoustic scene。 |

---
### 39. Live Music Diffusion Models: Efficient Fine-Tuning and Post-Training of Interactive Diffusion Music Generators

👤 **作者**: Zachary Novack, Stephen Brade, Haven Kim, Hugo Flores García, Nithya Shikarpur, Chinmay Talegaonkar, Suwan Kim, Valerie K. Chen, Julian McAuley, Taylor Berg-Kirkpatrick, Cheng-Zhi Anna Huang
🔗 **来源**: [https://arxiv.org/abs/2605.22717v1](https://arxiv.org/abs/2605.22717v1)

**摘要**
> Interactive streaming music generation promises the use of generative models for live performance and co-creation that is impossible with offline models. However, SOTA models exist in the discrete-AR regime, requiring industrial levels of compute for both training and inference. In this work, we investigate whether audio diffusion models, with their wide support in the open-source community but non-streaming bidirectional nature, can be repurposed efficiently into interactive models accessible on consumer hardware. By taking a critical look at the modern pipeline for block-wise outpainting diffusion, we identify critical inefficiencies during inference that result in strictly worse computational efficiency than their discrete-AR counterparts. We propose Live Music Diffusion Models (LMDMs), a simple modification of the generative diffusion process that recovers, and then outperforms, the inference complexity of the discrete Live Music Models (LMMs) through block-wise KV Caching. Unlike LMMs, LMDMs further enable stable post-training alignment through our novel ARC-Forcing paradigm, reducing error accumulation without any explicit RL or reward models. We demonstrate the application of LMDMs in a number of creative domains, including text-conditioned generation, sketch-based music synthesis, and jamming. We finally show how LMDMs can be used as a generative instrument in a real artist-AI collaboration, utilizing LMDMs as a "generative delay" to transform musicians' improvisation live for variable timbral effects while running locally on a consumer gaming laptop.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Live Music Diffusion Models: Efficient Fine-Tuning and Post-Training of Interactive Diffusion Music Generators》所界定。 从摘要看，作者主要围绕 live、music、diffusion 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We propose Live Music Diffusion Models (LMDMs), a simple modification of the generative diffusion process that recovers, and then outperforms, the inference complexity of the discrete Live Music Models (LMMs) through block-wise KV Caching. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：live, music, diffusion。 |

---
### 40. Plug-in Losses for Evidential Deep Learning: A Simplified Framework for Uncertainty Estimation that Includes the Softmax Classifier

👤 **作者**: Berk Hayta, Hannah Laus, Simon Mittermaier, Felix Krahmer
🔗 **来源**: [https://arxiv.org/abs/2605.22746v1](https://arxiv.org/abs/2605.22746v1)

**摘要**
> Real-world sensor-based learning systems require uncertainty estimation that is both reliable and computationally efficient. Evidential Deep Learning (EDL) provides single-pass uncertainty estimation by modeling the class probabilities via Dirichlet distributions, where the Dirichlet parameters are predicted by a learned neural network mapping. However, this approach can lead to computational challenges, as Dirichlet expected objectives are more complex than standard supervised learning losses, complicating their analysis and implementation. We address this issue by approximating the objective of the first-order empirical risk minimization problem induced by EDL with a plug-in loss evaluated at the Dirichlet mean and show that, under mild assumptions, the approximation error decays with growing evidence for a broad class of loss functions, including mean-squared error and cross-entropy loss. As a special case, our analysis provides justification for the use of softmax in the context of uncertainty estimation, since under a particular evidence-to-Dirichlet mapping, our framework includes the standard softmax classifier. We validate the proposed simplified objectives on the Google Speech Commands dataset and show that they achieve predictive accuracy and selective prediction performance comparable to classical EDL, while being simpler to implement using standard deep learning losses and training pipelines. To the best of our knowledge, this empirical analysis is the first to obtain coverage-accuracy trade-offs for speech recognition tasks through EDL.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Plug-in Losses for Evidential Deep Learning: A Simplified Framework for Uncertainty Estimation that Includes the Softmax Classifier》所界定。 从摘要看，作者主要围绕 plug-in、losses、evidential 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We address this issue by approximating the objective of the first-order empirical risk minimization problem induced by EDL with a plug-in loss evaluated at the Dirichlet mean and show that, under mild assumptions, the approximation error decays with growing evidence for a broad class of loss functions, including mean-squared error and cross-entropy loss. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：plug-in, losses, evidential。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
