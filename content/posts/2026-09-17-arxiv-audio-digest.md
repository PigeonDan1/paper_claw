<div align="center">

# 📰 Paper Claw

**2026-09-17**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-16 13:23:17 CST → 2026-09-17 13:32:15 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 1 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 3 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, ASR 1, TTS 1, Enhancement 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. FRAUDSkill: Structured Frozen-Weight Skill Optimization for Audio Anti-Fraud Detection

👤 **作者**: Chengxian Hu, Zhiming Ma, Mingjun Pan, Yifan Wang, Shun Zhang, Qifan Wang, Zhilei Zhao, Yijin Zhou, Yuxi Zhao, Huiyuan Liu, Peidong Wang, Peng Chen
🔗 **来源**: [https://arxiv.org/abs/2609.18766v1](https://arxiv.org/abs/2609.18766v1)

**摘要**
> Large audio-language models have shown promise for anti-fraud detection by directly processing speech and reasoning over fraud-related evidence. Their deployment, however, requires predictions to follow a predefined label space and a structured decision protocol consisting of service-scenario identification, fraud detection, and conditional fraud-type classification. Existing fine-tuning and prompt-based approaches typically encode task knowledge, constraints, and decision rules into model parameters or manually maintained prompts, making them difficult to adapt as fraud patterns and labeling policies evolve. To this end, we propose FRAUDSkill, a structured frozen-weight adaptation framework that leaves the underlying audio-language model unchanged while optimizing an external layer of skill programs, route-specific policies, and decision rules. We further combine structured output control with validation-guided multi-path inference to ensure protocol-compliant predictions. On the TeleAntiFraud benchmark, FRAUDSkill achieves 73.50% Macro-F1, outperforming the shared frozen-model baseline by 31.96% while reducing invalid outputs to 1.94%. Extensive experiments demonstrate that external skill optimization provides an effective and adaptable solution for structured audio anti-fraud detection without modifying the underlying model. The source code is available at https://anonymous.4open.science/r/FRAUDSKILL-114514.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《FRAUDSkill: Structured Frozen-Weight Skill Optimization for Audio Anti-Fraud Detection》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Large audio-language models have shown promise for anti-fraud detection by directly processing speech and reasoning over fraud-related evidence. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model。 |

---
## 🏷️ ASR

### 1. Multi-Teacher Distillation for Cross-Domain Streaming Electrolaryngeal Speech Encoding

👤 **作者**: Benedikt Mayrhofer, Enrique Orozco Olivares, Franz Pernkopf, Philipp Aichinger, Martin Hagmüller
🔗 **来源**: [https://arxiv.org/abs/2609.18686v1](https://arxiv.org/abs/2609.18686v1)

**摘要**
> Self-supervised learning (SSL) has improved speech representations, yet performance degrades in pathological domains such as electrolaryngeal (EL) speech, and the computational footprint of SSL models limits their applicability in real-time, on-device deployment. We propose a multi-teacher knowledge distillation framework to train a lightweight, streaming content encoder that generalizes across healthy (HE) and EL speech. Two teachers are distilled progressively: a frozen SSL model providing discrete phonetic cluster targets from HE speech, and an EL-fine-tuned speech recognition model supplying continuous bottleneck feature targets. Evaluated via downstream speech recognition, our approach reduces the EL word error rate to 21.2%, compared to 39.3% for the strongest zero-shot SSL baseline. Among causal convolutional, Transformer, Conformer, and Mamba-based student architectures, a Mel-Conformer achieves the best combination of EL accuracy and computational efficiency. The final encoder contains 21.9,M parameters and runs at a real-time factor of 0.30 under ONNX Runtime on a single CPU core.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Multi-Teacher Distillation for Cross-Domain Streaming Electrolaryngeal Speech Encoding》所界定。 从摘要看，作者主要围绕 conformer 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Self-supervised learning (SSL) has improved speech representations, yet performance degrades in pathological domains such as electrolaryngeal (EL) speech, and the computational footprint of SSL models limits their applicability in real-time, on-device deployment. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：conformer。 |

---
## 🏷️ TTS

### 1. GrainSpeech: Less Context, More Detail for Compact Speech Synthesis

👤 **作者**: Zitao Liang, Chang Gao
🔗 **来源**: [https://arxiv.org/abs/2609.18856v1](https://arxiv.org/abs/2609.18856v1)

**摘要**
> Compact acoustic models face a challenging quality-capacity trade-off. We investigate two factors in this regime: encoder context and Mel-spectrogram supervision. A receptive-field-scaling study shows that expanding self-attention beyond 15 phonemes provides no consistent gains in pitch, energy, or duration prediction. Guided by this finding, we introduce a fixed-receptive-field convolutional encoder that reduces the respective prediction errors by 36.0%, 17.3%, and 3.4%. We further show that directly transferring image-domain gradient-variance supervision restores fine-scale variation but degrades predicted quality, motivating a Mel-specific formulation with axis-specific gradients, overlapping local statistics, and log-domain variance matching. GrainSpeech contains only 264.8K parameters and achieves 17.9x real-time Mel generation on a microcontroller (MCU), while attaining UTMOS scores comparable to substantially larger models with less than 1.5% of their parameters. Source code and demos are available at https://github.com/lab-emi/GrainSpeech.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《GrainSpeech: Less Context, More Detail for Compact Speech Synthesis》所界定。 从摘要看，作者主要围绕 speech synthesis、acoustic model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：A receptive-field-scaling study shows that expanding self-attention beyond 15 phonemes provides no consistent gains in pitch, energy, or duration prediction. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech synthesis, acoustic model。 |

---
## 🏷️ Enhancement

### 1. Absolute Quality Ratings of Speech Enhancement Systems by Listeners of Different Ages and Degrees of Hearing Loss

👤 **作者**: Matteo Torcoli, Chih-Wei Wu, Andrea Esposito, Phillip A. Williams, Katrien Cambier, William Wolcott, Antonio Curci, Nicholas S. Reed, Mark Laureyns
🔗 **来源**: [https://arxiv.org/abs/2609.18714v1](https://arxiv.org/abs/2609.18714v1)

**摘要**
> Speech Enhancement (SE) supports listening, particularly for older adults with age-related hearing loss. Yet, enhanced Speech Quality (SQ) is commonly evaluated by young normal-hearing listeners, and how their ratings translate to older adults remains under-explored. We compared absolute SQ ratings from 40 younger normal-hearing listeners (20-30 years) and 67 older listeners (60-95 years) with diverse audiometric profiles, after screening. Test materials comprised natural dialogues with realistic backgrounds. SQ differences between SE systems that were clear for younger listeners were smaller or inseparable in older groups, regardless of hearing status. Hearing loss severity was associated with lower absolute ratings, but did not strongly modulate the contraction in separable SQ differences. A small, audiometrically mixed subgroup of older listeners showed younger-like rating patterns, suggesting that peripheral audiology alone cannot explain the contraction.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音增强」方向，核心任务由题目《Absolute Quality Ratings of Speech Enhancement Systems by Listeners of Different Ages and Degrees of Hearing Loss》所界定。 从摘要看，作者主要围绕 speech enhancement 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：A small, audiometrically mixed subgroup of older listeners showed younger-like rating patterns, suggesting that peripheral audiology alone cannot explain the contraction. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech enhancement。 |

---
## 🏷️ SLU

> 📭 今日该分类暂无新论文。

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Beyond EER: Multi-Dimensional Evaluation of Information Leakage in Speaker De-Identification

👤 **作者**: Seungmin Seo, Oleg Aulov, P. Jonathon Phillips, Kevin Mangold, Jonathan Eskin
🔗 **来源**: [https://arxiv.org/abs/2609.18673v1](https://arxiv.org/abs/2609.18673v1)

**摘要**
> Speaker de-identification (SDID) aims to preserve privacy by concealing speaker identity while maintaining speech utility. However, current evaluations often reduce privacy to a single dimension - biometric verification performance - typically measured by Equal Error Rate (EER). This narrow focus ignores critical leakage channels, such as soft biometric inference, embedding-level re-identification, and structural template similarity, which threaten the unlinkability and irreversibility of biometric references. We propose a holistic evaluation framework across five complementary metrics: (i) EER, (ii) soft biometric leakage score , (iii) cumulative match characteristic re-identification analysis, (iv) canonical correlation analysis and Procrustes embedding alignment, and (v) intelligibility via word error rate and semantic similarity. Evaluating five SDID systems from the IARPA ARTS program, we demonstrate that these metrics capture independent dimensions of information leakage. Our results indicate that reliance on a single metric can misrepresent the privacy properties of an SDID system.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond EER: Multi-Dimensional Evaluation of Information Leakage in Speaker De-Identification》所界定。 从摘要看，作者主要围绕 beyond、multi-dimensional、evaluation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluating five SDID systems from the IARPA ARTS program, we demonstrate that these metrics capture independent dimensions of information leakage. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：beyond, multi-dimensional, evaluation。 |

---
### 2. HearInContext: A Benchmark for Implicit Context in Speech Recognition

👤 **作者**: Yifan Gao, Yao Tian, Hongbin Suo
🔗 **来源**: [https://arxiv.org/abs/2609.18680v1](https://arxiv.org/abs/2609.18680v1)

**摘要**
> Contextual ASR can benefit from semantic cues or from target words explicitly provided in the context. We introduce HearInContext, a Mandarin--English benchmark that pairs shared synthetic speech with assistant replies supporting different interpretations. The benchmark comprises 3,764 semantic test cases built around homophones. Implicit contexts exclude candidate words; explicit contexts name the target. No-context and unrelated-context controls measure the benefit of relevant history and sensitivity to irrelevant history. Context-capable models benefit from implicit cues but achieve higher target recall with explicit hints. Fine-tuning Qwen3-ASR-1.7B improves implicit-context target recall by 11.0 and 11.5 percentage points in Mandarin and English, respectively, while absolute CER/WER changes on AISHELL-1 and LibriSpeech remain below 0.1 percentage points. Gains extend to explicit conditions excluded from fine-tuning and to Mandarin hotword recognition on real recordings.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《HearInContext: A Benchmark for Implicit Context in Speech Recognition》所界定。 从摘要看，作者主要围绕 hearincontext、benchmark、implicit 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Context-capable models benefit from implicit cues but achieve higher target recall with explicit hints. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：hearincontext, benchmark, implicit。 |

---
### 3. TeleAntiFraud 2.0: A Refreshable, Profile-Grounded, and Audio-Based Benchmark for Telecom Fraud Detection

👤 **作者**: Huiyuan Liu, Zhiming Ma, Yanxing Liu, Shun Zhang, Qifan Wang, Di Liu, Yifan Wang, Yuyang Deng, Haoyang Meng, Yijin Zhou, Yuxi Zhao, Chengxian Hu, Peidong Wang, Peng Chen
🔗 **来源**: [https://arxiv.org/abs/2609.18748v1](https://arxiv.org/abs/2609.18748v1)

**摘要**
> Telecom fraud scripts evolve rapidly and are often designed to resemble routine service conversations, creating two key requirements for audio-based telecom-fraud evaluation. First, benchmarks must incorporate newly observed scam patterns without overwriting previously established test sets. Second, they must distinguish fraud from lawful, near-domain calls rather than relying on topic-separated negative examples. We present TeleAntiFraud 2.0, constructed with our Mixed-Tree Anti-Fraud Generation Pipeline and evaluated under a monthly frozen evaluation protocol. The pipeline transforms online fraud-case abstracts into profile-grounded scenarios, expands them through mixed-tree generation, realizes fraud and non-fraud dialogue paths under shared contexts, renders validated dialogues as role-matched speech, and freezes the resulting audio, labels, prompts, manifests, and provenance records for each monthly evaluation set. Each frozen set contains 900 Chinese calls, comprising 600 fraud and 300 near-domain non-fraud cases. Controlled text experiments show that three classifiers achieve perfect macro-averaged F1 (Macro-F1) when evaluated against unrelated or ordinary negatives, but drop to 0.65-0.68 with near-domain sibling negatives. Full-set audio and automatic-speech-recognition plus large-language-model (ASR+LLM) evaluations further reveal class-prior shortcuts, prediction collapse, and snapshot sensitivity. Together, these findings establish near-domain construction and collapse-aware reporting as core requirements for evaluating audio-based telecom-fraud models under realistic confusable conditions. The accompanying research artifact includes the construction code, evaluation scripts, manifests, and documentation. Our dataset and code are available at https://anonymous.4open.science/r/TeleAntiFraud-2_0-EEB2/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《TeleAntiFraud 2.0: A Refreshable, Profile-Grounded, and Audio-Based Benchmark for Telecom Fraud Detection》所界定。 从摘要看，作者主要围绕 teleantifraud、refreshable、profile-grounded 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Controlled text experiments show that three classifiers achieve perfect macro-averaged F1 (Macro-F1) when evaluated against unrelated or ordinary negatives, but drop to 0.65-0.68 with near-domain sibling negatives. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：teleantifraud, refreshable, profile-grounded。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
