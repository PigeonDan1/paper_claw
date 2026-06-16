<div align="center">

# 📰 Paper Claw

**2026-06-16**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-15 14:11:41 CST → 2026-06-16 14:19:18 CST |
| 📄 论文总数 | **3** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 2 篇

> 💡 今日共收录 3 篇新论文，主要分布在 TTS 1, Audio 2。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

### 1. Probing Low Frame Rate Degradation in Neural Audio Codecs

👤 **作者**: Alex Gichamba, Moise Busogi
🔗 **来源**: [https://arxiv.org/abs/2606.16969v1](https://arxiv.org/abs/2606.16969v1)

**摘要**
> Low frame rates in neural audio codecs are attractive for autoregressive speech synthesis, where the generation cost scales linearly with the sequence length. Recent work has demonstrated that codecs can operate at 12.5 Hz and below, but the mechanisms underlying low frame rate degradation remain insufficiently understood. We investigate these mechanisms through a controlled frame rate ablation. We reproduce a quality cliff at 6.25 Hz reported in previous works and evaluate candidate explanations: phonemic collisions and codebook saturation, neither of which shows evidence of a fundamental barrier. The cliff is instead caused by suboptimal training configuration: fixed clip duration during training yields too few tokens at low frame rates, starving the decoder of inter-token context. Once corrected, WER degrades smoothly with phonemic load down to 3.1 Hz and 1.6 Hz, suggesting the inference-time efficiency gains of low frame rate codecs are more accessible than previously assumed.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Probing Low Frame Rate Degradation in Neural Audio Codecs》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Recent work has demonstrated that codecs can operate at 12.5 Hz and below, but the mechanisms underlying low frame rate degradation remain insufficiently understood. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech synthesis。 |

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

### 1. Robust Spoofed Speech Detection via Temporal Pyramid Modeling

👤 **作者**: Mahtab Masoudi Nezhad, Nima Karimian
🔗 **来源**: [https://arxiv.org/abs/2606.16837v1](https://arxiv.org/abs/2606.16837v1)

**摘要**
> Spoofed speech detection is increasingly challenged by realistic synthesis, voice conversion, and replay attacks, with cross-dataset generalization remaining a major limitation. This work we propose a Temporal Pyramid Adapter that utilize parallel temporal convolutions with varying receptive fields to capture multi-scale spoofing cues, ranging from local artifacts to global prosodic irregularities. We also integrated self-supervised XLS-R representations combined with front-end adapters, including Mel, Sinc, and a Temporal Pyramid design for multi-scale temporal modeling. The proposed model is evaluated cross multiple benchmark including ASVspoof 2017, ASVspoof 2021 (DF/LA), PartialSpoof, DiffSSD, and multilingual HQ-MPSD datasets. Experimental results demonstrate that Temporal Pyramid model obtained AUC of 99.24% and a EER of 3.87% on the PartialSpoof database, which is significantly outperforming the base model and several SOTA baseline such as LCNN-BLSTM (9.87% EER) and TRACE (8.08% EER). Additionally, multilingual evaluations confirm that while spoofing artifact are independent from language. While self-supervised representations improve robustness, performance degrades under domain and language shifts, highlighting the need for better adaptation and calibration strategies.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Robust Spoofed Speech Detection via Temporal Pyramid Modeling》所界定。 从摘要看，作者主要围绕 robust、spoofed、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results demonstrate that Temporal Pyramid model obtained AUC of 99.24% and a EER of 3.87% on the PartialSpoof database, which is significantly outperforming the base model and several SOTA baseline such as LCNN-BLSTM (9.87% EER) and TRACE (8.08% EER). 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：robust, spoofed, speech。 |

---
### 2. TuneJury: An Open Metric for Improving Music Generation Preference Alignment

👤 **作者**: Yonghyun Kim, Junwon Lee, Haiwen Xia, Yinghao Ma, Junghyun Koo, Koichi Saito, Yuki Mitsufuji, Chris Donahue
🔗 **来源**: [https://arxiv.org/abs/2606.17006v1](https://arxiv.org/abs/2606.17006v1)

**摘要**
> We introduce TuneJury, an open, instance-level pairwise reward model for text-to-music that predicts a music preference score from a text prompt and an audio clip. The released checkpoint is trained on publicly available human-preference labels covering arena-style (A vs. B) votes, metric-alignment preference pairs, crowdsourced pairwise comparisons, and expert aesthetic ratings. The predicted score margin between two clips is well calibrated on our held-out test split, supporting data filtering via a simple score threshold. TuneJury generalizes to both held-out test pairs and out-of-distribution benchmarks, remaining competitive with prior baselines on the latter. For generators released after training, we introduce anchor calibration, a post-hoc, per-system Bradley-Terry calibration that recovers agreement at substantially better data efficiency than from-scratch retraining. The same frozen reward drives consistent reward-axis gains across three downstream applications: inference-time best-of-N selection, DITTO-style latent optimization, and expert-iteration post-training. TuneJury is available at https://github.com/yonghyunk1m/TuneJury.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《TuneJury: An Open Metric for Improving Music Generation Preference Alignment》所界定。 从摘要看，作者主要围绕 tunejury、open、metric 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The released checkpoint is trained on publicly available human-preference labels covering arena-style (A vs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：tunejury, open, metric。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
