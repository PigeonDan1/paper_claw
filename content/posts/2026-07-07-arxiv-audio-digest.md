<div align="center">

# 📰 Paper Claw

**2026-07-07**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-06 13:01:04 CST → 2026-07-07 12:39:15 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 2 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, ASR 2, TTS 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. SPEARBench: A Benchmark for Naturalness Evaluation in Streaming Speech-to-Speech Language Models

👤 **作者**: Thomas Thebaud, Yuzhe Wang, Hao Zhang, Sathvik Manikantan Napa Ugandhar, Ashish Hallur, Georgi Tinchev, Venkatesh Ravichandran, Laureano Moro-Velazquez
🔗 **来源**: [https://arxiv.org/abs/2607.05365v1](https://arxiv.org/abs/2607.05365v1)

**摘要**
> Streaming speech-to-speech language models aim to answer spoken queries directly with synthetic speech. However, standard speech and text benchmarks do not capture whether these systems behave naturally in conversations, where timing, turn-taking, prosody, interpersonal stance, language and dialect consistency, and relationship-aware appropriateness jointly shape perceived quality. We introduce SPEARBench, a benchmark for evaluating naturalness in speech-to-speech language models from question-answer interactions. SPEARBench constructs controlled dialogue prompts from the Seamless Interaction corpus, runs inference across multiple models, and evaluates generated answers using a multidimensional protocol that covers response latency, interruptions, speech quality, ASR robustness, language and dialect consistency, emotional naturalness, interpersonal stance, and explainable distributional baselines. The benchmark includes original human answers as a reference condition and reports results for several contemporary models. Results show that current models can achieve high signal-level quality and low ASR error while still differing from human conversational behavior in latency, overlap, dialect preservation, emotional adaptation, and interpersonal stance dynamics.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《SPEARBench: A Benchmark for Naturalness Evaluation in Streaming Speech-to-Speech Language Models》所界定。 从摘要看，作者主要围绕 speech language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that current models can achieve high signal-level quality and low ASR error while still differing from human conversational behavior in latency, overlap, dialect preservation, emotional adaptation, and interpersonal stance dynamics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model。 |

---
## 🏷️ ASR

### 1. Listen, Think, Transcribe: Continuous Latent Test-Time Scaling for ASR

👤 **作者**: Ho Lam Chung, Yiming Chen, Dau-Cheng Lyu, Hsiao-Tsung Hung, Hung-yi Lee
🔗 **来源**: [https://arxiv.org/abs/2607.05051v1](https://arxiv.org/abs/2607.05051v1)

**摘要**
> End-to-end ASR models transcribe in a single pass, leaving no room for the decoder to revisit hard inputs. We propose LatentASR, a parameter-efficient method that adds continuous latent test-time scaling to a frozen ASR backbone. Two small trainable modules drive it: a Latent Adapter that iteratively refines a few latent prefix positions through bounded, stabilized updates, and a Value Head that predicts whether extra computation will help and halts the loop early. The Qwen3-ASR-0.6B backbone stays fully frozen, and we train only ~4M extra parameters. We activate this loop with a deliberately small, diverse 500-utterance training set. Under this minimal-data regime, standard adaptation methods all regress: full fine-tuning, LoRA, and prompt tuning each increase WER. LatentASR is the only tested method that reduces WER on both clean benchmarks (FLEURS -2.54% and VoxPopuli -0.47% relative). The reductions are concentrated on intrinsically hard inputs. On accented and code-switched speech (ASCEND), LatentASR achieves a 16.0% relative CER reduction. Across 30 FLEURS languages (23,049 utterances), the multilingual WER decreases uniformly across resource tiers, confirming that the adapter generalizes without overfitting. Dynamic halting preserves most of the clean-set reduction at a fraction of the compute, skipping roughly half of all utterances at the entry gate. Our results show that a small, carefully chosen activation set can switch on test-time scaling inside a frozen ASR model without corrupting the model itself, converting fixed per-utterance compute into input-dependent compute where it is most needed.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Listen, Think, Transcribe: Continuous Latent Test-Time Scaling for ASR》所界定。 从摘要看，作者主要围绕 end-to-end asr 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On accented and code-switched speech (ASCEND), LatentASR achieves a 16.0% relative CER reduction. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：end-to-end asr。 |

---
### 2. REDDIT: Correcting Model-Generated Timestamp Drift in ASR without Forgetting via Replay-Based Distribution Editing

👤 **作者**: Cheng-Kang Chou, Ming-To Chuang, Ke-Han Lu, Chan-Jan Hsu, Hung-yi Lee
🔗 **来源**: [https://arxiv.org/abs/2607.05364v1](https://arxiv.org/abs/2607.05364v1)

**摘要**
> Modern autoregressive ASR systems can emit timestamps as decoded tokens, enabling timestamped transcription without frame-level aligners or inference-time post-processing. We show that these generated timestamps can drift across long non-speech spans: the transcript may remain plausible, but the decoded time axis drifts away from the audio. We study this non-speech-induced timestamp drift with self-built gap and long-gap benchmarks across 15 evaluated timestamp-producing ASR and audio-language systems. Naive timestamp-corrected fine-tuning improves alignment but can severely degrade non-target ASR behavior, exposing a forgetting problem. We propose REDDIT(REplay-based Distribution eDITing), a lightweight two-stage post-training framework that corrects timestamps while avoiding this catastrophic forgetting: it first edits timestamp targets under the model's own replayed decoder context while matching the frozen base distribution on non-timestamp tokens, then applies a short edited-prefix refinement stage. In this framework, we construct correction supervision without human transcripts or human timestamp annotations by combining VAD-trimmed speech spans with inserted non-speech gaps and known concatenation offsets. On Whisper-tiny, 34.9 hours of targeted correction audio used and only 1.6% of model parameters updated, raising long-gap mIoU from 38.7% to 95.0% and reducing mixed-gap out-of-domain AAS from 2752 ms to 223 ms while preserving CV-en MER at 41.3% (versus 524.2% for ordinary SFT decoder tuning).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《REDDIT: Correcting Model-Generated Timestamp Drift in ASR without Forgetting via Replay-Based Distribution Editing》所界定。 从摘要看，作者主要围绕 asr system、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that these generated timestamps can drift across long non-speech spans: the transcript may remain plausible, but the decoded time axis drifts away from the audio. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：asr system, whisper。 |

---
## 🏷️ TTS

### 1. ProPS: Prompted Profile Synthesis for Natural Language-Conditioned Speaker Embedding Distributions

👤 **作者**: Thomas Thebaud, Junhyeok Lee, Laureano Moro-Velazquez, Jesus Villalba Lopez, Najim Dehak
🔗 **来源**: [https://arxiv.org/abs/2607.05276v1](https://arxiv.org/abs/2607.05276v1)

**摘要**
> Speaker embeddings, or x-vectors, are widely used to represent speaker identity and speaker-related attributes, but existing embedding extractors are typically descriptive rather than generative: they map an observed speech segment to an x-vector, which is then used for downstream applications. We introduce ProPS, Prompted Profile Synthesis, a framework for generating distributions of speaker embeddings conditioned on natural language prompts such as "a thirties male speaker with an Indian accent". ProPS converts human-written profile descriptions into sentence embeddings and uses a mixture density network trained on a large-scale dataset to predict a Gaussian mixture model in the x-vector space. The model is trained by maximizing the likelihood that real speaker embeddings match the requested profile, and its generated distributions are evaluated by negative log-likelihood on held-out x-vectors and by attribute classification accuracies on sampled synthetic x-vectors. Experiments show that ProPS produces profile-conditioned distributions and generates x-vectors that preserve requested speaker attributes such as age, gender, accent, and prosodic characteristics. This design enables controllable speaker-profile synthesis for speech generation systems like Text-To-Speech (TTS) or Voice Conversion (VC) while anchoring generated distributions in observed speaker-embedding structure.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《ProPS: Prompted Profile Synthesis for Natural Language-Conditioned Speaker Embedding Distributions》所界定。 从摘要看，作者主要围绕 text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that ProPS produces profile-conditioned distributions and generates x-vectors that preserve requested speaker attributes such as age, gender, accent, and prosodic characteristics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
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

### 1. Context-Aware ASR for Mandarin Technical Lectures

👤 **作者**: Ho-Lam Chung, Yiming Chen, Hung-yi Lee
🔗 **来源**: [https://arxiv.org/abs/2607.05058v1](https://arxiv.org/abs/2607.05058v1)

**摘要**
> Technical lectures mix Mandarin speech with English technical terms. These terms carry the core meaning of the lecture, yet they occupy few characters. Character error rate (CER) therefore hides their recognition failures. We study whether lecture context helps recognize these terms. We build a term-rich Mandarin AI/ML lecture benchmark, and we define term-centric metrics that measure technical-term recognition directly. We then propose a two-pass, reference-free decoding method. The first pass runs segment-only ASR. We extract the most frequent technical terms from the first-pass hypotheses, and we prompt the recognizer with this self-built glossary in the second pass. Across five ASR backbones, the first-pass glossary raises term recall for every model and holds or lowers CER on all five. On Breeze-ASR-25 it lifts term recall from 52.50% to 60.13% while lowering CER, and a hybrid that adds a small external term list reaches 62.05% recall and 82.73% term precision. Lecture context, recovered from the model's own output, is a practical signal for technical-term recognition. Term-centric evaluation exposes errors that CER misses.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Context-Aware ASR for Mandarin Technical Lectures》所界定。 从摘要看，作者主要围绕 context-aware、mandarin、technical 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：These terms carry the core meaning of the lecture, yet they occupy few characters. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：context-aware, mandarin, technical。 |

---
### 2. Towards Language-Agnostic Speech Inversion

👤 **作者**: Saba Tabatabaee, Mark Tiede, Suzanne Boyce, Liran Oren, Carol Espy-Wilson
🔗 **来源**: [https://arxiv.org/abs/2607.05060v1](https://arxiv.org/abs/2607.05060v1)

**摘要**
> Characteristic timing patterns are reflected in the acoustic speech signal, encompassing both vocal tract configuration and acoustic excitation. Previous studies have demonstrated that speech inversion (SI) systems can recover these timing patterns from speech, including oral tract variables (tongue and lip constrictions) and source information such as periodic and aperiodic energies and fundamental frequency. In this study, we develop an SI system that simultaneously estimates oral tract variables and three source information parameters trained on co-recorded American English speech audio and articulatory kinematics and investigate cross-linguistic generalizability by evaluating performance on previously unseen languages. Pearson product-moment correlation scores of 0.83 and 0.74 were achieved on untrained French and Russian respectively, across oral tract variables and source information when comparing estimated data with ground-truth measurements.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Towards Language-Agnostic Speech Inversion》所界定。 从摘要看，作者主要围绕 towards、language-agnostic、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Previous studies have demonstrated that speech inversion (SI) systems can recover these timing patterns from speech, including oral tract variables (tongue and lip constrictions) and source information such as periodic and aperiodic energies and fundamental frequency. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：towards, language-agnostic, speech。 |

---
### 3. Unified Audio Intelligence Without Regressing on Text Intelligence

👤 **作者**: Zhifeng Kong, Sang-gil Lee, Jaehyeon Kim, Boxin Wang, Zihan Liu, Sungwon Kim, Yang Chen, Arushi Goel, Rajarshi Roy, Wenliang Dai, Zhuolin Yang, Yangyi Chen, Dongfu Jiang, Sreyan Ghosh, Tuomas Rintamaki, Andrew Tao, Jonathan Raiman, Mohammad Shoeybi, Bryan Catanzaro, Wei Ping
🔗 **来源**: [https://arxiv.org/abs/2607.05196v1](https://arxiv.org/abs/2607.05196v1)

**摘要**
> Audio intelligence involves understanding, reasoning about, and generating both audio and speech. In this work, we introduce Nemotron-Labs-Audex-30B-A3B (Audex), a unified audio-text LLM built on Nemotron-Cascade-2-30B-A3B, a strong text-only MoE LLM. Audex adopts a simple unified design with a single Transformer decoder: audio inputs are encoded and projected into the text embedding space, while text tokens and quantized audio output tokens are treated uniformly during generation. This architecture enables strong audio-text fusion, seamless multimodal generation, and compatibility with standard LLM training and inference infrastructure. For training, we meticulously curate audio-text datasets comprising 157.4B audio tokens and 320.5B text tokens. We apply multi-stage supervised training on these datasets, followed by text-only Cascade RL and multi-domain on-policy distillation. Audex delivers state-of-the-art audio understanding, speech recognition and translation, text-to-speech, audio generation, and speech-to-speech generation, while preserving very compelling reasoning, alignment, knowledge, long-context, and agentic capabilities of its text-only LLM backbone with marginal or no regression. We release the model checkpoints to facilitate open research.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Unified Audio Intelligence Without Regressing on Text Intelligence》所界定。 从摘要看，作者主要围绕 text-to-speech、audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Audex delivers state-of-the-art audio understanding, speech recognition and translation, text-to-speech, audio generation, and speech-to-speech generation, while preserving very compelling reasoning, alignment, knowledge, long-context, and agentic capabilities of its text-only LLM backbone with marginal or no regression. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
