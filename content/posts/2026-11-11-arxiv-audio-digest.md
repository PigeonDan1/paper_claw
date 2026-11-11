<div align="center">

# 📰 Paper Claw

**2026-11-11**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-11-10 15:49:22 CST → 2026-11-11 15:17:12 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 3 篇新论文，主要分布在 Audio 3。
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

### 1. Exploring Post-Hoc Disentanglement of Audio Foundation Models for Music Similarity

👤 **作者**: Lucas de Souza Brandão, Gabriel da Costa Merlin, Diego Furtado Silva
🔗 **来源**: [https://arxiv.org/abs/2611.14415v1](https://arxiv.org/abs/2611.14415v1)

**摘要**
> Audio foundation models like CLAP, MuQ, and MERT excel at capturing general musical similarity. On the other hand, their entangled latent spaces limit interpretability and fine-grained attribute control. Conditional Similarity Networks (CSN) address this by pairing a backbone representation model with learned masks that gate the embedding space into attribute-specific subspaces. However, existing methods train the backbone from scratch, rather than leveraging pretrained foundation models. We instead present a systematic study of post-hoc disentanglement, adapting CSN to gate frozen pretrained embeddings. We evaluate adding trainable parameters to adapt the embedding under different masking and pooling regimes across two datasets. Our findings show that minimal adaptation capacity is sufficient for post-hoc gating to improve both attribute-specific disentanglement and overall retrieval performance, while pooling, masking, and depth choices yield limited additional gains.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Exploring Post-Hoc Disentanglement of Audio Foundation Models for Music Similarity》所界定。 从摘要看，作者主要围绕 exploring、post-hoc、disentanglement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our findings show that minimal adaptation capacity is sufficient for post-hoc gating to improve both attribute-specific disentanglement and overall retrieval performance, while pooling, masking, and depth choices yield limited additional gains. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：exploring, post-hoc, disentanglement。 |

---
### 2. Earlybird: Predictive Streaming Speech Recognition in 29M Parameters

👤 **作者**: Sahil Mahendrakar
🔗 **来源**: [https://arxiv.org/abs/2611.14421v1](https://arxiv.org/abs/2611.14421v1)

**摘要**
> Streaming speech recognizers output a word only after the speaker has finished it, typically 90-400 ms later. For a voice agent every millisecond counts: the sooner the words are outputted, the sooner the agent can start a search or plan its reply. We present Earlybird, a 29M-parameter streaming recognizer (16.8 MB at 4 bits). Earlybird learns from audio cut off at random points, including partway through a word, and is asked to predict every word that is due by then in full, plus a guess of the next two words. Its raw token probabilities give a confidence for every word including the one still being spoken. On clean audiobook speech (LibriSpeech test-clean), the median word is predicted correctly 90 ms before the speaker finishes it, while released streaming models get it 90 to 400 ms after it ends. Earlybird is the earliest on all six test sets we time, covering audiobooks, TED talks, public speech, earnings calls, and synthetic speech. On the same audiobooks, 69% of words are predicted correctly before they end, against 3-25% for the other models. For words still being spoken, confidence is calibrated, with an expected calibration error (ECE) of 3.7 to 5.5. On the eight English Open ASR Leaderboard sets, it is more accurate than Moonshine Tiny on every set and roughly ties Whistle, a model of the same size.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Earlybird: Predictive Streaming Speech Recognition in 29M Parameters》所界定。 从摘要看，作者主要围绕 earlybird、predictive、streaming 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：For a voice agent every millisecond counts: the sooner the words are outputted, the sooner the agent can start a search or plan its reply. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：earlybird, predictive, streaming。 |

---
### 3. Assessing Alignment in Automatic Piano Transcription Datasets: A Benchmark for Scoring Methods

👤 **作者**: Lucas de Souza Brandão, Lucas Gris, Joaquim Cavalcante, Chukwuemeka Nkama, Andrea Poltronieri
🔗 **来源**: [https://arxiv.org/abs/2611.14443v1](https://arxiv.org/abs/2611.14443v1)

**摘要**
> Automatic Music Transcription (AMT) relies on paired audio--MIDI datasets, implicitly assuming near-perfect temporal alignment. However, widely used piano datasets have been shown to contain alignment errors that may bias model evaluation and training. We propose a framework for evaluating audio--MIDI alignment scoring methods through controlled temporal, pitch, and structural MIDI corruptions. We also introduce STI, a scoring method built on AMT models, and benchmark it against existing alignment scoring approaches. Our results show that STI, together with methods based on CENS and spectrograms, achieves the strongest overall performance, with STI exhibiting the highest sensitivity to fine-grained temporal misalignments, the main alignment error in AMT datasets. We then apply the best-performing methods to widely used piano AMT datasets and identify trends in their relative alignment quality. These results support more informed dataset curation, model training, and AMT evaluation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Assessing Alignment in Automatic Piano Transcription Datasets: A Benchmark for Scoring Methods》所界定。 从摘要看，作者主要围绕 assessing、alignment、automatic 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, widely used piano datasets have been shown to contain alignment errors that may bias model evaluation and training. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：assessing, alignment, automatic。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
