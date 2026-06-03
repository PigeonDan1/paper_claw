<div align="center">

# 📰 Paper Claw

**2026-06-03**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-02 13:18:51 CST → 2026-06-03 13:52:15 CST |
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

### 1. Efficient ASR Training with Conversations that Never Happened

👤 **作者**: Máté Gedeon, Péter Mihajlik
🔗 **来源**: [https://arxiv.org/abs/2606.03957v1](https://arxiv.org/abs/2606.03957v1)

**摘要**
> Conversational ASR for lower-resource languages and niche domains is limited by the scarcity of domain-matched multi-speaker training data. We propose an augmentation pipeline that generates scenario-level dialogues with participant metadata, maps speaker attributes to TTS voice profiles, and assembles synthesized utterances into speaker-aware simulated conversations. We evaluated five LLM families under single-generator, fixed-budget mixture, and scale-up settings using the same FastConformer-Large training recipe for each one. We ran comprehensive evaluations on the Hungarian BEA-Dialogue benchmark corpus, with the method itself being applicable to any language given the resources for each component. The results show that synthetic conversations consistently improve speech recognition performance, but generator choice and data composition strongly affect the gains. Our largest training configuration, using only 67 hours of real conversations and 636 hours of simulated data, achieves better performance on the evaluation benchmark than a zero-shot model trained on 2700 hours of Hungarian speech. These findings indicate that LLM-generated conversational data synthesized with TTS is a practical complement to real conversational corpora for speech model training.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Efficient ASR Training with Conversations that Never Happened》所界定。 从摘要看，作者主要围绕 conformer 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that synthetic conversations consistently improve speech recognition performance, but generator choice and data composition strongly affect the gains. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：conformer。 |

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

### 1. Foley-Omni: A Unified Multimodal Generation Model from Task-Level Audio Synthesis to Complete Video Soundtrack Generation

👤 **作者**: Ye Tao, Lupeng Liu, Xuenan Xu, Jiasun Feng, Jiarui Wang, Ying Qin, Shuiyang Mao, Wei Liu, Shuai Wang
🔗 **来源**: [https://arxiv.org/abs/2606.03672v1](https://arxiv.org/abs/2606.03672v1)

**摘要**
> Recent unified audio generation models can support diverse tasks across speech, sound effects, and music, but most of them still focus on isolated task-level synthesis. However, real video production often requires multiple components of a complete audio track to be generated jointly and consistently for the same video. We present Foley-Omni, a unified multimodal audio generation model that extends isolated task-level synthesis to complete video soundtrack generation by jointly modeling speech, sound effects, and music within a shared latent generation process. To support training and reproducible evaluation, we develop an audiovisual data curation pipeline and introduce V2ST-Bench, a benchmark for holistic video soundtrack generation evaluation. Experiments show that Foley-Omni achieves competitive performance with expert systems on individual synthesis tasks, while improving speech intelligibility, audiovisual consistency and perceptual quality for mixed soundtrack generation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Foley-Omni: A Unified Multimodal Generation Model from Task-Level Audio Synthesis to Complete Video Soundtrack Generation》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that Foley-Omni achieves competitive performance with expert systems on individual synthesis tasks, while improving speech intelligibility, audiovisual consistency and perceptual quality for mixed soundtrack generation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---
### 2. Stable Hybrid Cross-Attention Fusion for Audio-Visual Event Recognition

👤 **作者**: Parinaz Binandeh Dehaghani, Danilo Pena, A. Pedro Aguiar
🔗 **来源**: [https://arxiv.org/abs/2606.03747v1](https://arxiv.org/abs/2606.03747v1)

**摘要**
> Audio-Visual Event Recognition (AVER) is essential for intelligent urban monitoring systems, where robust multimodal understanding of complex environments is required. This paper proposes a stable hybrid cross-attention fusion framework for audio-visual event recognition in smart urban environments. The proposed architecture combines pretrained Video Masked Autoencoder (VideoMAE) and Audio Spectrogram Transformer (AST) representations with FiLM-based audio conditioning, bidirectional cross-attention fusion, multimodal Transformer encoding, and modality-temporal attention. To improve computational efficiency and training stability, frozen pretrained backbones and cached feature extraction are employed. Extensive experiments on the AVE dataset show that the proposed framework achieves the highest average performance among the evaluated unimodal and multimodal baselines across multiple evaluation metrics, obtaining a best validation accuracy of 91.74% and a test accuracy of 83.85 plus/minus 1.40% over five independent runs. The results indicate that the proposed hybrid fusion strategy effectively captures complementary audio-visual information and provides robust multimodal representation learning for challenging realworld urban monitoring scenarios.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Stable Hybrid Cross-Attention Fusion for Audio-Visual Event Recognition》所界定。 从摘要看，作者主要围绕 stable、hybrid、cross-attention 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：To improve computational efficiency and training stability, frozen pretrained backbones and cached feature extraction are employed. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：stable, hybrid, cross-attention。 |

---
### 3. LiveBand: Live Accompaniment Generation in the Audio Domain

👤 **作者**: Marco Pasini, Javier Nistal, Mathias Rose Bjare, Stefan Lattner, George Fazekas
🔗 **来源**: [https://arxiv.org/abs/2606.03803v1](https://arxiv.org/abs/2606.03803v1)

**摘要**
> We present LiveBand, a real-time system that generates high-fidelity music accompaniments to live audio input, respecting strict causal constraints. Our method trains a causal transformer generator in the continuous latent space of a pre-trained causal audio autoencoder, using adversarial sequence-level supervision from a discriminator. At each timestep, the generator receives only the causally available mix context and Gaussian noise, and predicts accompaniment latents without access to future mix frames or ground-truth target latents. Training is performed in a single parallel forward pass under causal masking, while streaming inference proceeds autoregressively with a rolling attention state. The model's training and inference computations are matched by design, eliminating teacher forcing and the associated exposure bias. On a multi-instrument music accompaniment benchmark, LiveBand improves over prior work on objective measures of audio quality, beat alignment, and mix adherence, while enabling real-time streaming generation without lookahead into the future on consumer hardware.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《LiveBand: Live Accompaniment Generation in the Audio Domain》所界定。 从摘要看，作者主要围绕 liveband、live、accompaniment 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On a multi-instrument music accompaniment benchmark, LiveBand improves over prior work on objective measures of audio quality, beat alignment, and mix adherence, while enabling real-time streaming generation without lookahead into the future on consumer hardware. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：liveband, live, accompaniment。 |

---
### 4. In-the-Loop Training of Deep Feedback Cancellation for Hearing Aids

👤 **作者**: Svantje Voit, Simon Doclo
🔗 **来源**: [https://arxiv.org/abs/2606.03832v1](https://arxiv.org/abs/2606.03832v1)

**摘要**
> Acoustic feedback limits the maximum gain in hearing aids. In addition to several approaches based on adaptive filtering, recently a deep-neural-network-based feedback cancellation (DFC) approach has been proposed, which is trained via an open-loop framework. Since open-loop-trained DFC (DFC-OL) can become unstable during inference at high gains, in this paper we propose an in-the-loop-trained DFC (DFC-IL) that integrates the DFC directly into the optimisation loop. This allows the model to be exposed to unstable conditions during training. A two-stage training strategy involving pre-training on stable systems and fine-tuning on a wider gain range enables DFC-IL to learn robust howling reduction. Experimental results on measured feedback paths demonstrate that in scenarios with small gains, the proposed DFC-IL performs similarly to DFC-OL, and both exceed the performance of adaptive filters. In scenarios with high amplification gains, DFC-IL clearly outperforms DFC-OL by maintaining system stability.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《In-the-Loop Training of Deep Feedback Cancellation for Hearing Aids》所界定。 从摘要看，作者主要围绕 in-the-loop、training、deep 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results on measured feedback paths demonstrate that in scenarios with small gains, the proposed DFC-IL performs similarly to DFC-OL, and both exceed the performance of adaptive filters. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：in-the-loop, training, deep。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
