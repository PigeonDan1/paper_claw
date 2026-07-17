<div align="center">

# 📰 Paper Claw

**2026-07-17**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-07-16 11:53:04 CST → 2026-07-17 11:53:11 CST |
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

### 1. SLT 2026 REAL-TSE Challenge: Real-world Target Speaker Extraction from Conversational Recordings

👤 **作者**: Shuai Wang, Zihan Qian, Ke Zhang, Jiangyu Han, Zikai Liu, Xiaoyang Yu, Haoyu Li, Marc Delcroix, Kai Yu, Lei Xie, Ming Li, Haizhou Li
🔗 **来源**: [https://arxiv.org/abs/2607.15198v1](https://arxiv.org/abs/2607.15198v1)

**摘要**
> We introduce the REAL-TSE Challenge, an IEEE SLT 2026 satellite challenge on target speaker extraction~(TSE) from real conversational recordings. Given a multi-speaker mixture and one or more enrollment utterances from a target speaker, participating systems must recover only the target speech. Unlike simulated read-speech benchmarks, REAL-TSE evaluates Mandarin and English recordings that contain natural overlap, reverberation, noise, channel mismatch, and conversational dynamics. The challenge defines two complementary tracks: an Online track for low-latency streaming extraction and an Offline track for full-context processing. Systems are evaluated with Token Error Rate (TER), Speaker Similarity (SpkSim), DNSMOS, and target-speaker activity F1. This overview paper describes the task definition, datasets, baselines, evaluation protocol, submitted systems, condition-wise findings, and lessons for future real-world TSE benchmarks.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SLT 2026 REAL-TSE Challenge: Real-world Target Speaker Extraction from Conversational Recordings》所界定。 从摘要看，作者主要围绕 real-tse、challenge、real-world 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Given a multi-speaker mixture and one or more enrollment utterances from a target speaker, participating systems must recover only the target speech. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：real-tse, challenge, real-world。 |

---
### 2. What does the model actually see? Evaluation protocols and input availability in data-driven prediction of room acoustic parameters

👤 **作者**: Akın Oktav
🔗 **来源**: [https://arxiv.org/abs/2607.15243v1](https://arxiv.org/abs/2607.15243v1)

**摘要**
> Machine-learnt models are increasingly used to predict ISO 3382-1 room acoustic parameters from sparse measurements, with reported coefficients of determination frequently above 0.85. This paper shows that such figures are often determined by the evaluation protocol rather than by the model. Using a multi-condition measurement campaign in a 264-seat conference hall and a 180-seat concert hall, three model families were evaluated under a factorial protocol ablation: validation splits either row-based or grouped by receiver position, and input features either including measured-at-test quantities or restricted to source-receiver geometry and environmental state. Row-based splits with measured-at-test inputs reproduce the high reported accuracies (mean $R^2$ 0.81 for the core parameters); grouping the splits by position and restricting inputs to information available at an unmeasured position reduces these to 0.09-0.57, reordering the apparent difficulty of parameter classes. A hybrid CNN evaluated with the target's own impulse response as input is shown to exploit it as a position fingerprint rather than as transferable acoustic information; training-only signal access yields no gain for any parameter tested, including reverberation time. Under the deployment-consistent protocol, the spread between Random Forest, the hybrid CNN, and inverse-distance weighting is an order of magnitude smaller than the spread between protocols for a fixed model; the learnt models retain a genuine advantage for sound strength and reverberation time, and the high accuracy of the original pipelines re-emerges as condition interpolation at measured positions (band means 0.80-0.88), a distinct and operationally useful task.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《What does the model actually see? Evaluation protocols and input availability in data-driven prediction of room acoustic parameters》所界定。 从摘要看，作者主要围绕 what、does、model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper shows that such figures are often determined by the evaluation protocol rather than by the model. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：what, does, model。 |

---
### 3. SceneBind: Binding What and Where Across Vision, Audio and Language

👤 **作者**: Mingfei Chen, Zijun Cui, Ruoke Zhang, Hyeonggon Ryu, Eli Shlizerman
🔗 **来源**: [https://arxiv.org/abs/2607.15265v1](https://arxiv.org/abs/2607.15265v1)

**摘要**
> We present SceneBind, an omni-modal representation of realistic scenes with joint semantic and 3D spatial understanding across vision, audio and language. Existing omni-modal encoders excel at instance-level semantics (i.e., what is present), but often lack explicit spatial structure (i.e., where it is). SceneBind addresses this gap by representing each scene as a semantic-spatial entity, combining a global semantic embedding with object-centric semantic-spatial slots. This representation explicitly captures object-level semantics, spatial attributes, and uncertainty. We further propose SceneBind Matching, a semantic-spatial matching scheme that integrates global scene similarity with object alignment, supporting cross-modal scene retrieval and object grounding. To train and evaluate SceneBind, we curate a novel real-world binaural audio-visual dataset with structured semantic and spatial annotations, and propose a training protocol for aligning semantic and spatial signals across modalities. SceneBind is compatible with large-scale pretrained semantic encoders, adds lightweight spatial modeling with only a few additional tokens. It achieves state-of-the-art scene and spatial retrieval while enabling strong zero-shot transfer to downstream tasks such as audio-visual localization.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SceneBind: Binding What and Where Across Vision, Audio and Language》所界定。 从摘要看，作者主要围绕 scenebind、binding、what 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：It achieves state-of-the-art scene and spatial retrieval while enabling strong zero-shot transfer to downstream tasks such as audio-visual localization. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：scenebind, binding, what。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
