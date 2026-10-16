<div align="center">

# 📰 Paper Claw

**2026-10-16**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-15 13:20:35 CST → 2026-10-16 13:11:35 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Audio 4。
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

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Frame-Wise Streaming for Efficient Learned Speech Compression

👤 **作者**: Yuhan Liu, Jun Xu, Fengxi Zhang, Zhengxue Cheng, Li Song
🔗 **来源**: [https://arxiv.org/abs/2610.21998v1](https://arxiv.org/abs/2610.21998v1)

**摘要**
> Speech compression is increasingly important in scenarios such as real-time and satellite communication. Neural codecs have shown superior Rate-Distortion (RD) performance over traditional signal-processing codecs. Models with long-range dependency encoders/decoders and entropy models outperform convolution-based structures, but they still lack streaming support since they rely on sequence-level correlations. In this paper, we propose StreamLSC, a frame-level streaming learned speech compression model built on three fundamental components of streaming networks, i.e. Boundary-Cached Causal Convolution, Intra-Frame Layer Normalization, and RNN-mode RWKV. Our model incorporates a streamable entropy quantizer module, ensuring efficient context model while preserving causal constraints. Experiments show that the streaming model achieves performance comparable to its offline counterpart, attaining state-of-the-art rate-distortion results, significant gains in subjective evaluations, -51.37% (ViSQOL) and -53.99% (PESQ) BD-RATE savings on average, and improvements of 0.2154 and 0.5156 in BD-ViSQOL and BD-PESQ.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Frame-Wise Streaming for Efficient Learned Speech Compression》所界定。 从摘要看，作者主要围绕 frame-wise、streaming、efficient 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Neural codecs have shown superior Rate-Distortion (RD) performance over traditional signal-processing codecs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：frame-wise, streaming, efficient。 |

---
### 2. From Signals to Evidence: Interpretable Underwater Acoustic Target Sensing with Large Language Models - Part I: Framework and Recognition

👤 **作者**: Yuge Zhang, Jie Chen, Zhengqiao Zhao, Xiling Yao, Lingji Xu, Jingdong Chen, Yixin Yang
🔗 **来源**: [https://arxiv.org/abs/2610.22064v1](https://arxiv.org/abs/2610.22064v1)

**摘要**
> Underwater acoustic target detection and recognition are essential to marine surveillance and intelligent ocean sensing. Despite substantial advances in deep learning, existing systems typically produce binary detection decisions, categorical labels, or scalar confidence scores, offering limited insight into the physical evidence underlying their outputs. Large language models (LLMs) offer an opportunity to move underwater acoustic sensing toward interpretable, evidence-grounded understanding; however, generic audio encoders struggle to capture the distinctive physical characteristics of underwater acoustics, and physically annotated data are scarce. In this paper, the first of a two-part series, we propose a from-signals-to-evidence framework that integrates physics-aware acoustic encoding with a pretrained LLM, organized around a unified feature-evidence-decision chain with a shared reasoning core. An open input layer accommodates heterogeneous information-raw waveforms, time-frequency representations, environmental and geographic data, and textual physical priors-unifying detection and recognition within a common formulation. In Part I, we instantiate this framework for target recognition through an Underwater Acoustic Physics-aware Transformer (UPT), which tokenizes complementary acoustic representations and learns task-disentangled physical representations through four physics-oriented learning tasks. We develop a physics-parameterized data engine that provides traceable supervision at two levels of granularity and introduce an attribute-level evaluation protocol to assess the physical fidelity of generated descriptions. Experiments on simulated recordings of four vessels demonstrate accurate vessel recognition and reliable estimation of shaft frequency, blade-passing frequency, and machinery-related attributes.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《From Signals to Evidence: Interpretable Underwater Acoustic Target Sensing with Large Language Models - Part I: Framework and Recognition》所界定。 从摘要看，作者主要围绕 from、signals、evidence 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on simulated recordings of four vessels demonstrate accurate vessel recognition and reliable estimation of shaft frequency, blade-passing frequency, and machinery-related attributes. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：from, signals, evidence。 |

---
### 3. How Much Physics Can Vision Learn from Audio? Probing and Distilling Damping Structure

👤 **作者**: Zainab Afolabi, Vadim Selyutin, Zhao Gao, Babs Khalidson, Mohamed Ghoneim
🔗 **来源**: [https://arxiv.org/abs/2610.22221v1](https://arxiv.org/abs/2610.22221v1)

**摘要**
> Physical understanding is crucial for decision making, yet vision models struggle to infer properties such as damping that govern how materials behave. Audio encodes such properties directly, because an object's acoustic response to impact reveals its damping through measurable decay. We probe frozen encoders for the quality factor $Q$, a dimensionless measure of how many oscillations an object completes before its ring dies away, and report how well each embedding orders impacts by $Q$ using the Spearman rank correlation $ρ$, for which $ρ=1$ is a perfect ordering and $ρ=0$ an unrelated one. Audio embeddings reach $ρ=0.73$ and retain most of that advantage on materials withheld from training, while a single video frame taken at the moment of impact, encoded by CLIP, supports only $ρ=0.28$. Having established where the signal lives, we ask how much of that gap vision can recover. We distill a frozen audio teacher into a frozen CLIP backbone through a trained projection head and find that this recovers a useful fraction of the audio advantage. Because pooled correlations on this task are dominated in practice by category identity, we also evaluate under a leave-one-material-out protocol in which the held-out material is withheld from the projection head as well as the probe. Distillation with a four-frame input improves the correlation there from 0.234 to 0.338 (+0.053 over the matched four-frame baseline, 14 of 17 materials), a gain that no category-level strategy can produce. Widening the visual input to four frames spanning the impact supplies half of that improvement at no acoustic cost, which indicates that part of what a single frame misses is visible dynamics.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《How Much Physics Can Vision Learn from Audio? Probing and Distilling Damping Structure》所界定。 从摘要看，作者主要围绕 much、physics、vision 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Distillation with a four-frame input improves the correlation there from 0.234 to 0.338 (+0.053 over the matched four-frame baseline, 14 of 17 materials), a gain that no category-level strategy can produce. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：much, physics, vision。 |

---
### 4. Backward Compatibility in Zero-Bit Neural Audio Watermarking

👤 **作者**: Admir Krnić, Kosta Pavlović, Petar Nedić, Željko Bolević, Slavko Kovačević, Igor Djurović
🔗 **来源**: [https://arxiv.org/abs/2610.22296v1](https://arxiv.org/abs/2610.22296v1)

**摘要**
> Neural watermarking systems are typically trained as tightly coupled embedder-detector pairs and implicitly assume static deployment. In real-world deployments, embedders and detectors are frequently updated and selectively decoupled for security and versioning purposes, which can break detection in previously embedded content and, more critically, increase false-positive rates on embedders that a given detector is intentionally not intended to recognize. In this paper the concept of backward compatibility in zero-bit audio watermarking is formalized. A training framework is proposed that pairs a new detector with a sequence of frozen legacy embedders (its legacy chain), using a performance-weighted sampling strategy so that the detector retains accuracy across all earlier versions. This coupling, while necessary for backward compatibility, is shown to induce an embedder-collapse effect that catastrophically degrades the true negative rate (TNR) against out-of-chain embedders. To counteract this, a Angular Diversity Loss (ADL) is introduced that explicitly forces each new embedder to occupy a distinct region of the output space. The combined approach restores near-perfect TNR with no measurable cost to detection accuracy or perceptual audio quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Backward Compatibility in Zero-Bit Neural Audio Watermarking》所界定。 从摘要看，作者主要围绕 backward、compatibility、zero-bit 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This coupling, while necessary for backward compatibility, is shown to induce an embedder-collapse effect that catastrophically degrades the true negative rate (TNR) against out-of-chain embedders. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：backward, compatibility, zero-bit。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
