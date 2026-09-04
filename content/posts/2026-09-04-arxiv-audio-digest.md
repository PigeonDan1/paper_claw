<div align="center">

# 📰 Paper Claw

**2026-09-04**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-03 13:14:26 CST → 2026-09-04 13:10:29 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, Enhancement 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Fairness Evaluation of Edge-AI Implementation for Cleft Lip and Palate Speech ASR

👤 **作者**: Susmita Bhattacharjee, Himashri Deka, H. S. Shekhawat, S. R. M. Prasanna
🔗 **来源**: [https://arxiv.org/abs/2609.03982v1](https://arxiv.org/abs/2609.03982v1)

**摘要**
> Automatic speech recognition (ASR) remains challenging for individuals with cleft lip and palate (CLP) because of limited pathological speech data and large variations in speech characteristics across speakers and severity levels. These recognition difficulties can reduce the accessibility of voice-based human-computer interaction, particularly when cloud-based ASR services are unavailable or unreliable. This work investigates a severity-aware and edge-deployable ASR framework for improving recognition of CLP speech using Whisper-small. The model was fine-tuned using different combinations of normal and CLP speech representing mild, moderate, and severe conditions, together with a CLP-only training configuration, to examine how the inclusion of different severity levels influences recognition performance and fairness across speakers. The pretrained model produced pooled word error rate (WER) and phoneme error rate (PER) values of 62.46% and 52.72%, respectively. Severity-aware fine-tuning substantially improved performance, reducing the best pooled WER to 22.72% and the best pooled PER to 18.44%. Training with a broader representation of CLP severity levels also provided the best overall balance between recognition accuracy and performance consistency across severity groups. Deployment on an NVIDIA Jetson platform demonstrated real-time inference for all fine-tuned models, with real-time factors of 0.167-0.171 and peak GPU memory usage of approximately 566 MB. The results demonstrate that incorporating severity diversity during ASR adaptation can substantially improve recognition of CLP speech while reducing performance disparities across severity groups. The proposed approach further enables low-latency, Internet-independent speech interaction on edge devices, supporting more accessible and inclusive voice-based human-computer interaction for individuals with CLP.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Fairness Evaluation of Edge-AI Implementation for Cleft Lip and Palate Speech ASR》所界定。 从摘要看，作者主要围绕 automatic speech recognition、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This work investigates a severity-aware and edge-deployable ASR framework for improving recognition of CLP speech using Whisper-small. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition, whisper。 |

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

---
## 🏷️ Enhancement

### 1. Masked Autoregressive Speech Enhancement with Continuous Neural Audio Codec Representations

👤 **作者**: Yoto Fujita, Simon Leglaive, Laurent Girin
🔗 **来源**: [https://arxiv.org/abs/2609.03940v1](https://arxiv.org/abs/2609.03940v1)

**摘要**
> Most previous work on speech enhancement (SE) based on masked generative modeling relied on discrete token representations of audio signals, obtained using neural audio codecs (NACs). However, a recent study has shown that continuous latent representations of NACs can be advantageous for SE in terms of speech quality and intelligibility. In this work, we propose masked autoregressive SE (MARSE), a method for SE based on iterative decoding of masked clean speech frames using continuous NAC representations of speech. In particular, we investigate a set of different decoding policies, ceteris paribus, that is, using the same DNN (a Conformer model), the same NAC (the DAC codec) and the same training setup. The results show that MARSE enables a flexible trade-off between SE performance and computational cost. Audio examples and code are available online.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Masked Autoregressive Speech Enhancement with Continuous Neural Audio Codec Representations》所界定。 从摘要看，作者主要围绕 conformer、speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, a recent study has shown that continuous latent representations of NACs can be advantageous for SE in terms of speech quality and intelligibility. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：conformer, speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Alignment-Free Text-Audiobox for Voice Dubbing and Full-Duplex Dialogue Synthesis

👤 **作者**: Sanyuan Chen, Min-Jae Hwang, Sho Inoue, Anna Sun, Bokai Yu, David Kant, Dongmin Hyun, Dorian Desblancs, Gregory Antonovsky, Oleg Repin, Peng-Jen Chen, Xutai Ma, Zehai Tu, Juan Pino, Wei-Ning Hsu
🔗 **来源**: [https://arxiv.org/abs/2609.03992v1](https://arxiv.org/abs/2609.03992v1)

**摘要**
> We present Alignment-Free Text-Audiobox (Text-AB), a unified framework for high-quality voice dubbing and full-duplex dialogue synthesis. Building on a Diffusion Transformer trained with a flow-matching objective, Text-AB departs from the Audiobox system along three dimensions. First, it operates in a latent diffusion framework using DAC-VAE features that encode 48 kHz waveforms into a 25 Hz latent sequence, giving over 10x higher compression than previous EnCodec representations while improving resynthesis quality. Second, Text-AB is alignment-free: it consumes raw text via an off-the-shelf text encoder and learns text-speech alignment through cross-attention, removing the need for forced alignment and explicit duration prediction. Third, we scale model and data substantially, pretraining a 3B-parameter model on 480k hours of monolingual speech, followed by supervised fine-tuning on three downstream tasks: cross-lingual voice dubbing, full-duplex dialogue synthesis, and emotional full-duplex dialogue synthesis. At inference, Text-AB supports one-shot generation for up to ~1 min of speech and arbitrarily long-form generation via a multi-diffusion scheme, plus a multi-stage reranking strategy that enhances quality based on automated metrics. On a real-world dubbing benchmark, Text-AB delivers a step-change improvement over the latest internal dubbing system, with large gains in prosody similarity, voice similarity, naturalness, and shareability. For full-duplex dialogue synthesis, it approaches human recordings on short-form conversations and substantially outperforms the latest internal model on long-form human-likeness and expressivity, while natively modeling turn-taking, back-channeling, and emotional dynamics. For emotional dialogue synthesis, emotion conditioning significantly improves emotion alignment and emotional interaction quality over the unconditioned baseline.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Alignment-Free Text-Audiobox for Voice Dubbing and Full-Duplex Dialogue Synthesis》所界定。 从摘要看，作者主要围绕 alignment-free、text-audiobox、voice 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：First, it operates in a latent diffusion framework using DAC-VAE features that encode 48 kHz waveforms into a 25 Hz latent sequence, giving over 10x higher compression than previous EnCodec representations while improving resynthesis quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：alignment-free, text-audiobox, voice。 |

---
### 2. Deep Neural Compression for RIR-Characterized Acoustic Environments with Structure-Aware Constraints

👤 **作者**: Chen-Yuan Ning, Yang Ai, Hui-Peng Du, Xiao-Hang Jiang, Zhen-Hua Ling
🔗 **来源**: [https://arxiv.org/abs/2609.04085v1](https://arxiv.org/abs/2609.04085v1)

**摘要**
> Room impulse responses (RIRs) characterize the acoustic environment of a room by capturing how sound propagates and decays within an enclosed space. In applications such as immersive audio rendering, accurate acoustic reconstruction often relies on spatially densely sampled RIRs. This consequently gives rise to a large volume of RIR data, imposing a substantial burden on storage. Although recent neural audio codecs provide an effective framework for low-bitrate compression, their training objectives are mainly tailored to speech and general audio, and are therefore not well aligned with the acoustic characteristics of RIRs. Therefore, we propose an EnCodec-based neural RIR compression method, which incorporates RIR structure-aware constraints at two levels. Specifically, at the RIR level, structure-aware constraints are imposed on the global decay behavior and local energy distribution of RIRs through energy decay curve (EDC) regularization and a short-time window energy constraint, while at the reverberant-speech level, reverberant-speech supervision is further introduced to constrain the consistency of the reverberant speech generated by the reconstructed RIRs. Experimental results show that, at a low bitrate of 375 bps, the proposed method achieves lower RIR reconstruction error and better reverberant-speech perceptual consistency than audio-oriented codecs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Deep Neural Compression for RIR-Characterized Acoustic Environments with Structure-Aware Constraints》所界定。 从摘要看，作者主要围绕 deep、neural、compression 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results show that, at a low bitrate of 375 bps, the proposed method achieves lower RIR reconstruction error and better reverberant-speech perceptual consistency than audio-oriented codecs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：deep, neural, compression。 |

---
### 3. Compressing Streaming Neural Audio Encoders via Latent-Space Distillation

👤 **作者**: Prasanth Yadla, Mohammad Samragh, Dongseong Hwang, Mingbin Xu, Yuanyuan Zhang, Chung-Cheng Chiu, Yongqiang Wang, Yuan Liu, Zhen Huang, Xiaodan Zhuang
🔗 **来源**: [https://arxiv.org/abs/2609.04102v1](https://arxiv.org/abs/2609.04102v1)

**摘要**
> System-wide Dictation on Apple devices runs entirely on-device, and the speech it transcribes reaches the foundation model through a tokenizer: an encoder that maps short windows of waveform onto the representation the language model reads. Because that model is sparsely activated under Instruction-Following Pruning, only a small subset of its experts occupies DRAM at any time, so the always-on tokenizer competes for the same memory, and its parameter count bears directly on power and latency. In this work we study how to compress such a tokenizer by distillation, taking as the supervision target neither the discrete token nor the output distribution but the pre-quantizer latent the model actually consumes - the last representation the two token interfaces share. We train only the student encoder to regress the teacher's per-frame latent under a squared-error objective, with a single affine layer absorbing the teacher-student width mismatch. Because the target precedes both the quantizer and the language-model bridge, one recipe covers both token interfaces we support, and applies both to a tokenizer pretrained alone and to one jointly trained with a language model. At 2.8x compression the distilled student stays within 1.9% relative WER of its teacher on five of six teacher-student pairs without any fine-tuning, and improves on an independently trained tokenizer of identical capacity by 3.9% relative.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Compressing Streaming Neural Audio Encoders via Latent-Space Distillation》所界定。 从摘要看，作者主要围绕 compressing、streaming、neural 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：At 2.8x compression the distilled student stays within 1.9% relative WER of its teacher on five of six teacher-student pairs without any fine-tuning, and improves on an independently trained tokenizer of identical capacity by 3.9% relative. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：compressing, streaming, neural。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
