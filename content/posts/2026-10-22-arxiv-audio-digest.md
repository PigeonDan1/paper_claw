<div align="center">

# 📰 Paper Claw

**2026-10-22**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-21 13:25:44 CST → 2026-10-22 13:31:21 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Bio-Inspired Auditory Processing: Coupling Parallel Resonate-and-Fire Dynamics with Ternary Recurrent Networks for Speech Recognition

👤 **作者**: Pavlos Poulos, Katelyn Sadorf, Themos Stafylakis, Costas A. Anastassiou
🔗 **来源**: [https://arxiv.org/abs/2610.29720v1](https://arxiv.org/abs/2610.29720v1)

**摘要**
> Spiking Neural Networks (SNNs) promise energy-efficient inference through sparse, event-driven computation, yet remain constrained on continuous, context-dependent tasks such as automatic speech recognition (ASR). A key bottleneck is the Leaky Integrate-and-Fire (LIF) neuron, whose membrane decay erases information across pauses and phonetic boundaries while it must both extract features and retain long-range context. Inspired by cortical separation of nonlinear filtering and somatic integration, we introduce the Spiking Ternary GRU (stGRU): a ternary-weight gated recurrent unit performs temporal filtering, while downstream Resonate-and-Fire (RF) neurons generate the binary spike stream driving the next block's event pathway. This makes binary event transmission a native training constraint rather than a separate deployment-time activation quantization step; together with ternary weights, learned projections avoid dense floating-point matrix MACs. Trained end-to-end on LibriSpeech-960, Small, Medium, and Large stGRUs reach 8.09%, 7.04%, and $6.44 \pm 0.17\%$ WER on test-clean without an external language model. To our knowledge, these are the first matrix-MAC-free spiking networks without a learned ANN sequence decoder to achieve single-digit WER on LibriSpeech. The architecture also achieves 10.88% test CER on Aishell-1 (9.28% on dev) when trained from scratch. Internally, trained networks develop a depth-graded hierarchy: shallow layers act as fast acoustic filters, while deep layers form slower semantic integrators whose latent representations segregate into part-of-speech manifolds and word-level spike events. Deep-layer firing rates follow lognormal distributions with a sparsity gradient, mirroring hierarchical processing observed in human cortex in vivo. Our biologically grounded architecture combines competitive ASR with favorable modeled compute and memory cost.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Bio-Inspired Auditory Processing: Coupling Parallel Resonate-and-Fire Dynamics with Ternary Recurrent Networks for Speech Recognition》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To our knowledge, these are the first matrix-MAC-free spiking networks without a learned ANN sequence decoder to achieve single-digit WER on LibriSpeech. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

---
## 🏷️ TTS

> 📭 今日该分类暂无新论文。

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

### 1. Geometry-Conditioned Target Speaker Extraction based on spatial features incorporating acoustic propagation principles

👤 **作者**: Jiatong Li, Simon Doclo
🔗 **来源**: [https://arxiv.org/abs/2610.29778v1](https://arxiv.org/abs/2610.29778v1)

**摘要**
> Recently, spatially selective non-linear filter (SSF) was proposed for target speaker extraction, utilizing the direction-of-arrival (DOA) of the target speaker as a spatial cue. To overcome its dependency on a fixed microphone array geometry, geometry-conditioned SSF (GCSSF) was proposed, which maps the target DOA and the microphone positions into abstract high-dimensional embeddings using positional encoding. As an alternative to these high-dimensional embeddings, in this paper we propose utilizing two spatial features incorporating acoustic propagation principles for geometry conditioning: 1) the steering vector of the target speaker, which captures inter-microphone phase differences, and 2) a spatial mask based on GCC-PHAT, which quantifies presence of the target speaker per time-frequency bin. These features are used as input to a geometry-conditioning encoder and integrated via a FiLM layer into the GCSSF system. Experimental results on circular and random arrays demonstrate that conditioning with spatial features improves target extraction performance compared to abstract high-dimensional embeddings, maintaining a clear performance advantage across a wide range of target DOA errors.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Geometry-Conditioned Target Speaker Extraction based on spatial features incorporating acoustic propagation principles》所界定。 从摘要看，作者主要围绕 geometry-conditioned、target、speaker 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results on circular and random arrays demonstrate that conditioning with spatial features improves target extraction performance compared to abstract high-dimensional embeddings, maintaining a clear performance advantage across a wide range of target DOA errors. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：geometry-conditioned, target, speaker。 |

---
### 2. NeuroCodec: EEG-Guided Latent-Domain Generative Model for High-Fidelity Target Speaker Extraction

👤 **作者**: Julian Silva, Jaliya Kodithuwakku, Navindu Sirimanna, Shaveen Herath, Wageesha N. Manamperi, Joshua P. Kulasingham
🔗 **来源**: [https://arxiv.org/abs/2610.29815v1](https://arxiv.org/abs/2610.29815v1)

**摘要**
> Driven by recent advancements in hearing assistive devices, target speaker extraction (TSE) in multi-talker environments has drawn significant attention. To address this, hearing technologies identify attention using neural signals recorded via electroencephalography (EEG) to guide TSE, enabling neuro-steered auditory attention decoding. However, most existing techniques rely on time-frequency masking, which suffers from low fidelity in spectro-temporally overlapping regions and is often restricted to narrowband audio. In contrast, we introduce NeuroCodec, which, to the best of our knowledge, is the first generative EEG-guided TSE framework operating in the latent space of a neural audio codec. Specifically, NeuroCodec models spatial EEG dependencies via graph convolutions and fuses cross-modal EEG and speech representations through attention mechanisms and Mamba-based temporal modeling. We further introduce a six-phase training curriculum that progressively incorporates latent reconstruction, multi-scale spectral, and adversarial objectives to ensure stable, high-fidelity speech generation. Experiments on the public Cocktail Party and KUL datasets show NeuroCodec outperforms baselines, across several perceptual metrics. A listening experiment with 20 participants validated that NeuroCodec offers greater perceptual accuracy, achieving a mean score of 82.24 compared with 49.63 for M3ANet. Additionally, the proposed method is seen to enable 44.1 kHz reconstruction with spectral content extending up to 20 kHz, further supporting the perceptual results. Finally, we extend NeuroCodec with a causal streaming formulation suited for real-time processing, providing a basis for hearing assistive devices.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《NeuroCodec: EEG-Guided Latent-Domain Generative Model for High-Fidelity Target Speaker Extraction》所界定。 从摘要看，作者主要围绕 neurocodec、eeg-guided、latent-domain 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the public Cocktail Party and KUL datasets show NeuroCodec outperforms baselines, across several perceptual metrics. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：neurocodec, eeg-guided, latent-domain。 |

---
### 3. AT-Differ: Dataset for Audio-Text Difference Captioning

👤 **作者**: Akihiro Fujii, Yuki Okamoto, Yuki Saito, Hiroshi Saruwatari
🔗 **来源**: [https://arxiv.org/abs/2610.29836v1](https://arxiv.org/abs/2610.29836v1)

**摘要**
> Evaluating audio-text semantic alignment is important in various audio-language tasks. Existing methods mainly quantify audio-text semantic alignment using a single score and cannot explicitly describe how audio and text differ. In this paper, we propose audio-text difference captioning, a task that generates textual descriptions of differences between audio and text. We also construct a new dataset AT-DIFFER containing audio-text pairs with systematically simulated differences and corresponding difference captions. Using AT-DIFFER, we fine-tune an existing multimodal large language model to describe differences between audio and text. The experimental results show that the original model has limited ability to describe such differences, whereas fine-tuning on AT-DIFFER substantially improves this ability.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AT-Differ: Dataset for Audio-Text Difference Captioning》所界定。 从摘要看，作者主要围绕 at-differ、dataset、audio-text 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The experimental results show that the original model has limited ability to describe such differences, whereas fine-tuning on AT-DIFFER substantially improves this ability. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：at-differ, dataset, audio-text。 |

---
### 4. A Learned Musical-Time Coordinate for Piano Audio-to-Score Transcription

👤 **作者**: Min-Hsing Wang, Tsung-Ren Huang
🔗 **来源**: [https://arxiv.org/abs/2610.29928v1](https://arxiv.org/abs/2610.29928v1)

**摘要**
> End-to-end piano audio-to-score (A2S) transcription is the task of reconstructing a notated score from an audio recording in a single system. Existing A2S approaches usually rely on pre-segmented excerpts, and few handle whole pieces without external segmentation. This raises the question of whether a musical-time coordinate can guide score transcription while also helping the system segment whole pieces. Previous work on jazz saxophone A2S uses an external beat tracker to obtain such a coordinate for score prediction. We introduce downbeat phase, a musical-time coordinate learned jointly with score transcription that represents each audio frame's relative position within a notated bar. With this coordinate, our system can not only condition its score decoder on downbeat phase but also self-segment at bar boundaries and stitch the segments into a whole piece. Evaluation suggests that the coordinate improves metrical structure and supports whole-piece transcription with comparable notation quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Learned Musical-Time Coordinate for Piano Audio-to-Score Transcription》所界定。 从摘要看，作者主要围绕 learned、musical-time、coordinate 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluation suggests that the coordinate improves metrical structure and supports whole-piece transcription with comparable notation quality. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：learned, musical-time, coordinate。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
