<div align="center">

# 📰 Paper Claw

**2026-06-18**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-17 13:54:42 CST → 2026-06-18 13:25:53 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 1 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 7 篇新论文，主要分布在 ASR 1, TTS 1, SLU 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. DASH: Dual-View Self-Distillation with Multi-Layer Hidden Representations for Robust Speech Recognition

👤 **作者**: Jaeeun Baik, Ui-Hyeop Shin, Jiwoon Lee, Woocheol Jeong, Hyung-Min Park
🔗 **来源**: [https://arxiv.org/abs/2606.19203v1](https://arxiv.org/abs/2606.19203v1)

**摘要**
> Automatic Speech Recognition (ASR) often degrades in real-world noisy environments, making noise robustness essential for deployment. Supervised noise-augmented fine-tuning is a common remedy, but it can introduce a robustness-clean trade-off and overfit to specific corruptions, degrading recognition in clean conditions. We propose DASH, a self-distillation framework that improves robustness by learning clean--noisy consistency from paired views. DASH distills hidden representations from multiple encoder layers to capture features from low-level acoustics to high-level semantics, and stabilizes training by minimizing KL divergence between prototype assignment distributions of clean and noisy views. Experiments on LibriSpeech show that DASH consistently improves recognition under diverse noisy conditions while preserving clean accuracy, achieved by a label-free pre-training stage with minimal additional overhead (about 4% of fine-tuning time) beyond standard fine-tuning.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《DASH: Dual-View Self-Distillation with Multi-Layer Hidden Representations for Robust Speech Recognition》所界定。 从摘要看，作者主要围绕 automatic speech recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We propose DASH, a self-distillation framework that improves robustness by learning clean--noisy consistency from paired views. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：automatic speech recognition。 |

---
## 🏷️ TTS

### 1. FineCombo-TTS: Collaborative and Precise Controllable Speech Synthesis Using Text Descriptions and Reference Speech

👤 **作者**: Shuoyi Zhou, Yixuan Zhou, Peiji Yang, Yifan Hu, Yicheng Zhong, Zhisheng Wang, Zhiyong Wu
🔗 **来源**: [https://arxiv.org/abs/2606.19209v1](https://arxiv.org/abs/2606.19209v1)

**摘要**
> Controllable text-to-speech (TTS) has become a key research focus. However, methods based on either reference speech or text descriptions lack flexibility and precise control, and recent joint approaches remain loosely coupled, with speech modeling timbre and text controlling global style. We propose FineCombo-TTS, a unified framework for speech synthesis grounded in reference speech and guided by text descriptions, enabling flexible and precise control over acoustic attributes. Instead of explicit attribute disentanglement, we learn a unified acoustic representation and introduce a Conditional Flow Matching (CFM)-based Speech Variance Predictor to model fine-grained reference-to-target transformations guided by text descriptions. To support relative attribute control, we construct FineEdit, a structured paired dataset that explicitly encodes source-to-target attribute variations. Experiments demonstrate that our approach achieves flexible, precise, and expressive controllable TTS.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《FineCombo-TTS: Collaborative and Precise Controllable Speech Synthesis Using Text Descriptions and Reference Speech》所界定。 从摘要看，作者主要围绕 text-to-speech、speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments demonstrate that our approach achieves flexible, precise, and expressive controllable TTS. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：text-to-speech, speech synthesis。 |

---
## 🏷️ Enhancement

> 📭 今日该分类暂无新论文。

---
## 🏷️ SLU

### 1. Reference-Driven Multi-Speaker Audio Scene Generation from In-the-Wild Priors

👤 **作者**: Michael Finkelson, Daniel Segal, Eitan Richardson, Shahar Armon, Nani Goldring, Poriya Panet, Nir Zabari, Benjamin Brazowski, Or Patashnik, Yoav HaCohen
🔗 **来源**: [https://arxiv.org/abs/2606.19325v1](https://arxiv.org/abs/2606.19325v1)

**摘要**
> Existing multi-speaker dialogue systems bind speakers to utterances through structured supervision: per-turn tags, multi-stream transcriptions, or learnable speaker embeddings. These systems operate within speech-only pipelines that produce clean vocal sequences without the ambient texture of real conversations. We take a different approach. Our method, ScenA, conditions a text-to-audio flow-matching foundation model, pretrained on large-scale in-the-wild data, directly on multiple reference voices and a free-form natural language prompt that describes an entire multi-speaker audio scene. Leveraging such a foundational model allows us to inherit its capacity for natural, non-studio audio: background noise, room acoustics, overlapping dialogue, and spontaneous paralinguistic events, while adding multi-speaker control without any per-turn structure. Concretely, reference latents are concatenated into the model's token sequence and distinguished by lightweight identity-aware positional encodings. However, we identify a critical obstacle to this approach: the \textit{Reference Shortcut}. During training under standard noise schedules, the model can identify the matching reference by acoustic similarity to the noisy target, bypassing the text prompt entirely. We address this with a high-noise-biased timestep distribution that forces the model to rely on the text prompt for speaker assignment. We evaluate ScenA on the CoVoMix2-Dialogue benchmark, showing that it outperforms existing multi-speaker systems on speaker-binding metrics while generating rich conversational audio with overlapping speech, emotional vocalizations, and ambient sound. Our results demonstrate the advantage of using a general-purpose audio model conditioned on a free-form scene description, rather than passing structured dialog scripts through a speech-only pipeline.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「口语理解」方向，核心任务由题目《Reference-Driven Multi-Speaker Audio Scene Generation from In-the-Wild Priors》所界定。 从摘要看，作者主要围绕 dialogue system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We evaluate ScenA on the CoVoMix2-Dialogue benchmark, showing that it outperforms existing multi-speaker systems on speaker-binding metrics while generating rich conversational audio with overlapping speech, emotional vocalizations, and ambient sound. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dialogue system。 |

---
## 🏷️ Paralinguistics

> 📭 今日该分类暂无新论文。

---
## 🏷️ Audio

### 1. Continuous-Speech Parkinson's Disease Detection Using Acoustic and Inharmonicity Features

👤 **作者**: Rujia Li, Niloofar Momeni, Susanna Whitling, Andreas Jakobsson
🔗 **来源**: [https://arxiv.org/abs/2606.19125v1](https://arxiv.org/abs/2606.19125v1)

**摘要**
> Notable efforts have been made to identify Parkinson's disease (PD) from vocal data, primarily using sustained vowel phonations. In this work, we extend on these efforts introducing a PD identification approach for continuous speech, enabling a practical background monitoring of voice data to detect vocal changes indicative of PD. Using two distinct data sets, we compare the best sustained vowel model with that of the proposed continuous speech model, clearly illustrating the preferential performance of the latter. We examine approaches for speaker level evaluation and data leakage preventions, as well as how vowel information may be reliable extracted from continuous speech. The proposed method framework exploits both traditional acoustic representations and a promising novel inharmonicity based framework, showing how the latter provides complementary information improving the performance for one of the data sets; however, for the other data set, this information did not significantly improve (nor reduce) the performance, suggesting that further studies are required before being able to draw firm conclusions in its use. Overall, the work clearly illustrates the benefit of forming PD classification using continuous speech compared to using sustained vowel sounds.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Continuous-Speech Parkinson's Disease Detection Using Acoustic and Inharmonicity Features》所界定。 从摘要看，作者主要围绕 continuous-speech、parkinson、disease 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The proposed method framework exploits both traditional acoustic representations and a promising novel inharmonicity based framework, showing how the latter provides complementary information improving the performance for one of the data sets; however, for the other data set, this information did not significantly improve (nor reduce) the performance, suggesting that further studies are required before being able to draw firm conclusions in its use. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：continuous-speech, parkinson, disease。 |

---
### 2. IndicContextEval: A Benchmark for Evaluating Context Utilisation in Audio Large Language Models Across 8 Indic Languages

👤 **作者**: Sakshi Joshi, Dhruv Subhash Rathi, Sanskar Singh, Eldho Ittan George, R J Hari, Kaushal Bhogale, Mitesh M. Khapra
🔗 **来源**: [https://arxiv.org/abs/2606.19157v1](https://arxiv.org/abs/2606.19157v1)

**摘要**
> AudioLLMs enable speech recognition conditioned on textual prompts such as domain descriptions or entity lists. However, it remains unclear whether these models genuinely utilise such context or rely on parametric knowledge learned during pretraining. Existing benchmarks cannot answer this question because they evaluate transcription under fixed prompting conditions and rarely include explicit contextual inputs. We introduce IndicContextEval, a 56-hour multilingual benchmark of natural speech from 555 speakers across 8 Indian languages and 23 professional domains. We design a 7-level prompting framework that progressively introduces contextual signals, including metadata, natural-language descriptions, entity lists in English and native script, and adversarial prompts with incorrect entities. Evaluating five models reveals substantial differences in context utilisation behaviour, highlighting the need for explicit evaluation of contextual grounding in AudioLLMs.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《IndicContextEval: A Benchmark for Evaluating Context Utilisation in Audio Large Language Models Across 8 Indic Languages》所界定。 从摘要看，作者主要围绕 indiccontexteval、benchmark、evaluating 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：However, it remains unclear whether these models genuinely utilise such context or rely on parametric knowledge learned during pretraining. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：indiccontexteval, benchmark, evaluating。 |

---
### 3. Scoring Backends Matter More Than Pooling: A Systematic Study of Training-Free Anomalous Sound Detection under Domain Shift

👤 **作者**: Jingwen Zhou, Mingzhe Wang
🔗 **来源**: [https://arxiv.org/abs/2606.19269v1](https://arxiv.org/abs/2606.19269v1)

**摘要**
> Training-free anomalous sound detection (ASD) scores a test clip against a memory bank of normal embeddings from a frozen pretrained audio encoder. Recent work attributes domain-shift robustness mainly to how frame-level features are pooled over time; the scoring backend applied on top of the pooled embedding has received far less systematic attention. Using a single frozen BEATs encoder on the DCASE 2023 Task 2 development set (all seven machine types), we cross four classical backends -- nearest-neighbor cosine distance, Mahalanobis distance, locally density-normalized kNN, and PCA-subspace reconstruction residual -- with three temporal poolings (mean, GeM, max). Switching the backend moves target-domain AUC by 13.8 points on average (up to 53.8), whereas switching the pooling moves it by only 3.2 points: in this training-free regime, the backend, not the pooling, dominates domain-shift robustness. No backend wins everywhere, but the machine-dependent pattern reproduces on the DCASE 2025 development data (fan, bearing). Exploiting this, we propose a label-free score fusion that z-normalizes each backend with its training-bank self-scores and takes the minimum; it reaches a harmonic-mean target AUC of 63.3% versus 64.4% for the per-machine oracle, surpassing every fixed single backend while preserving source-domain accuracy. We also report a negative result: selecting a backend by source-domain pseudo-validation with proxy outliers fails, because all backends saturate on the proxy task.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Scoring Backends Matter More Than Pooling: A Systematic Study of Training-Free Anomalous Sound Detection under Domain Shift》所界定。 从摘要看，作者主要围绕 scoring、backends、matter 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Recent work attributes domain-shift robustness mainly to how frame-level features are pooled over time; the scoring backend applied on top of the pooled embedding has received far less systematic attention. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：scoring, backends, matter。 |

---
### 4. Native Active Perception as Reasoning for Omni-Modal Understanding

👤 **作者**: Zhenghao Xing, Ruiyang Xu, Yuxuan Wang, Jinzheng He, Ziyang Ma, Qize Yang, Yunfei Chu, Jin Xu, Junyang Lin, Chi-Wing Fu, Pheng-Ann Heng
🔗 **来源**: [https://arxiv.org/abs/2606.19341v1](https://arxiv.org/abs/2606.19341v1)

**摘要**
> Passive models for long video understanding typically rely on a "watch-it-all" paradigm, processing frames uniformly regardless of query difficulty, causing computational cost to grow with video duration. Although interactive frameworks have emerged, they often rely on global pre-scanning, and their context cost still scales with video length. We propose OmniAgent, the first native omni-modal agent that formulates video understanding as a POMDP-based iterative Observation-Thought-Action cycle. OmniAgent executes on-demand actions to selectively distill audio-visual cues into a persistent textual memory, effectively decoupling reasoning complexity from raw video duration. To operationalize this, we introduce (1) Agentic Supervised Fine-Tuning to bootstrap native active perception via best-of-N trajectory synthesis with dual-stage quality control, and (2) Agentic Reinforcement Learning with TAURA (Turn-aware Adaptive Uncertainty Rescaled Advantage), which leverages turn-level entropy to steer credit assignment toward pivotal discovery turns. Crucially, OmniAgent exhibits positive test-time scaling, where performance improves as the number of reasoning turns increases, validating the efficacy of active perception. Empirical results across ten benchmarks (e.g., VideoMME, LVBench) demonstrate that OmniAgent achieves state-of-the-art performance among open-source models. Notably, on LVBench, our 7B agent outperforms the 10$\times$ larger Qwen2.5-VL-72B (50.5% vs. 47.3%).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Native Active Perception as Reasoning for Omni-Modal Understanding》所界定。 从摘要看，作者主要围绕 native、active、perception 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Crucially, OmniAgent exhibits positive test-time scaling, where performance improves as the number of reasoning turns increases, validating the efficacy of active perception. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：native, active, perception。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
