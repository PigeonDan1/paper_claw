<div align="center">

# 📰 Paper Claw

**2026-10-09**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-08 14:43:25 CST → 2026-10-09 14:50:53 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Enhancement 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. EgoVoice: Proactive Spoken Assistance from Egocentric Multimodal Streams

👤 **作者**: Heeseung Kim
🔗 **来源**: [https://arxiv.org/abs/2610.12248v1](https://arxiv.org/abs/2610.12248v1)

**摘要**
> Wearable augmented reality (AR) assistants are moving toward continuous real-world interaction, where they perceive the user's activity through first-person video and audio and provide timely spoken guidance without being explicitly asked. While proactive video assistants, spoken dialog systems, and egocentric task understanding have each advanced rapidly, existing systems do not address the joint problem of deciding when to speak and what to say from continuous first-person streams. We introduce EgoVoice, a framework for training and evaluating proactive egocentric spoken assistants. From HoloAssist video recordings of real human instructors, we construct clean audio streams through source separation and speech resynthesis, and convert each video session into a format where the model must decide at each moment whether to remain silent or provide spoken guidance. We fine-tune an omni-modal LLM with our data, and further improve its proactive intervention behavior with direct preference optimization. Experiments across closed and open-source models show that existing systems rarely produce well-timed, meaningful proactive interventions, while EgoVoice yields clear improvements in intervention timing, content relevance, and human preference over the zero-shot backbone.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《EgoVoice: Proactive Spoken Assistance from Egocentric Multimodal Streams》所界定。 从摘要看，作者主要围绕 source separation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We fine-tune an omni-modal LLM with our data, and further improve its proactive intervention behavior with direct preference optimization. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：source separation。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. SteerablePlex: Can We Steer Full-Duplex Models?

👤 **作者**: Haolong Zheng, Maike Züfle, Dominik Macháček, Peter Polák, Xulin Fan, Xavier Sumba, Siyin Wang, Ondřej Klejch, Mark Hasegawa-Johnson
🔗 **来源**: [https://arxiv.org/abs/2610.12201v1](https://arxiv.org/abs/2610.12201v1)

**摘要**
> Full-duplex speech models can listen and speak simultaneously, enabling natural interaction, but become increasingly difficult to control as the conversation history grows. When used as user simulators, this lack of control can cause them to deviate from prescribed scenarios and produce unreliable evaluation outcomes. We introduce SimIF-Bench (Simulator Instruction-Following Benchmark), which evaluates whether a conversational model stays within a prescribed scenario and completes multiple goals in the required order. The benchmark reveals that current open-source full-duplex models struggle to follow such constraints. We then introduce a Group Reward-Decoupled Normalization Policy Optimization (GDPO)-based training recipe that enables a full-duplex model to follow textual instructions during an ongoing conversation while maintaining its turn-taking ability. By connecting the resulting SteerablePlex to an asynchronous backend language model that monitors the conversation and provides instructions when needed, we build a more controllable full-duplex user simulator that follows multi-stage constraints more reliably than existing open-source models and GPT-Realtime.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SteerablePlex: Can We Steer Full-Duplex Models?》所界定。 从摘要看，作者主要围绕 steerableplex、steer、full-duplex 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：When used as user simulators, this lack of control can cause them to deviate from prescribed scenarios and produce unreliable evaluation outcomes. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：steerableplex, steer, full-duplex。 |

---
### 2. DiffuPlex: Accelerating Full-Duplex Spoken Dialog Models via Rolling Masked Diffusion

👤 **作者**: Heeseung Kim
🔗 **来源**: [https://arxiv.org/abs/2610.12214v1](https://arxiv.org/abs/2610.12214v1)

**摘要**
> Recent full-duplex spoken dialog models enable simultaneous listening and speaking, but fine-grained models still advance their backbone autoregressively at every interaction frame. We introduce DiffuPlex, a rolling masked diffusion framework that reduces this sequential computation by predicting multiple future user and assistant frames in a single backbone wake. DiffuPlex consumes only a confident prefix of each predicted future while interaction continues at the original frame rate. As user speech arrives, it checks the corresponding user predictions and, when the interaction diverges, preserves already played assistant content while revising only the unplayed future. We consider two inference policies over the same predictor: DiffuPlex-LISTEN consumes multiple future frames when they predict assistant silence, whereas DiffuPlex-SPEAK can also consume predicted assistant speech. Across full-duplex interaction and spoken-language evaluations, DiffuPlex substantially reduces sequential backbone computation while largely preserving interaction behavior and general capability. DiffuPlex-LISTEN and DiffuPlex-SPEAK achieve $1.46\times$ and $1.59\times$ deployment-path wall-clock speedups and $1.61\times$ and $1.80\times$ Core LM speedups, with all measured backbone invocations completing within the 80ms interaction interval. Human evaluation shows that LISTEN preserves speech naturalness and conversational quality, while SPEAK retains conversational quality with some degradation in speech naturalness.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《DiffuPlex: Accelerating Full-Duplex Spoken Dialog Models via Rolling Masked Diffusion》所界定。 从摘要看，作者主要围绕 diffuplex、accelerating、full-duplex 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：DiffuPlex-LISTEN and DiffuPlex-SPEAK achieve $1.46\times$ and $1.59\times$ deployment-path wall-clock speedups and $1.61\times$ and $1.80\times$ Core LM speedups, with all measured backbone invocations completing within the 80ms interaction interval. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：diffuplex, accelerating, full-duplex。 |

---
### 3. How Much Audio Is Left In An Embedding? An Inversion Audit Of Audio Encoders

👤 **作者**: Marios Glytsos, Brian McFee
🔗 **来源**: [https://arxiv.org/abs/2610.12250v1](https://arxiv.org/abs/2610.12250v1)

**摘要**
> Pretrained audio encoders are reused for downstream tasks that are often unknown when the encoder is trained, so their usefulness depends partly on which signal properties survive the pretext objective. We study this retained information through paired source reconstruction. Using a shared Stable Audio Open latent diffusion decoder, we reconstruct five-second, 44.1-kHz stereo music from frozen representations produced by supervised classifiers (VGGish, ConvNeXt), an audio-text contrastive model (CLAP), and a waveform-reconstruction model (EnCodec). These objectives impose different pressures to preserve source detail, while their exposed interfaces vary substantially in temporal and spectral resolution. Evaluating on the Million Song Dataset (MSD), we find clear differences in reconstructability across encoder families, while within encoder comparisons show improved recovery when finer temporal or spectral structure is exposed. Even compressed task oriented embeddings support reconstructions that preserve measurable source specificity and high level musical content.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《How Much Audio Is Left In An Embedding? An Inversion Audit Of Audio Encoders》所界定。 从摘要看，作者主要围绕 much、audio、left 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluating on the Million Song Dataset (MSD), we find clear differences in reconstructability across encoder families, while within encoder comparisons show improved recovery when finer temporal or spectral structure is exposed. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：much, audio, left。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
