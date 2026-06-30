<div align="center">

# 📰 Paper Claw

**2026-06-30**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-29 13:20:26 CST → 2026-06-30 12:55:31 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 3 篇

> 💡 今日共收录 5 篇新论文，主要分布在 ASR 1, Paralinguistics 1, Audio 3。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. MeloDISinger: Melody-Aware & Duration-Preserving Singing Voice Editing with Audio Infilling

👤 **作者**: Yoonjeong Park, Jaekwon Im, Juhan Nam
🔗 **来源**: [https://arxiv.org/abs/2606.30580v1](https://arxiv.org/abs/2606.30580v1)

**摘要**
> Text-based singing voice editing (SVE) aims to revise sung lyrics while preserving the original melody, total duration, and non-edited regions. In this paper, we propose MeloDISinger, a flow-matching-based SVE model for melody-aware and duration-preserving editing. Its core module, MeloDRP, predicts fixed-budget duration ratios, enabling explicit span-wise duration control. For melody-aware duration allocation, MeloDRP fuses phonetic cues with pseudo-MIDI melodic context through cross-attention, while temporal-overlap supervision encourages soft phoneme--note correspondences. We further use a flow-matching mel decoder for audio infilling to synthesize edited regions while preserving surrounding context. In addition, we introduce a duration-aware edited-lyric generation pipeline using WhisperX and an LLM to construct feasible evaluation scenarios. Experiments demonstrate state-of-the-art performance in both objective and subjective evaluations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《MeloDISinger: Melody-Aware & Duration-Preserving Singing Voice Editing with Audio Infilling》所界定。 从摘要看，作者主要围绕 whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments demonstrate state-of-the-art performance in both objective and subjective evaluations. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：whisper。 |

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

### 1. SIGMA: Saliency-Guided Sparse Mask Attacks for Speech Emotion Recognition

👤 **作者**: Qiyang Sun, Yi Chang, Zixing Zhang, Björn W. Schuller
🔗 **来源**: [https://arxiv.org/abs/2606.30550v1](https://arxiv.org/abs/2606.30550v1)

**摘要**
> Speech conveys rich emotional information. As Speech Emotion Recognition (SER) is usually deployed in privacy-sensitive and reliability-critical environments, adversarial attacks on SER have attracted increasing attention. Existing sparse attacks control the number of perturbed elements, yet, they often lack explainability guidance and explicit measures of explanation consistency. A unified treatment of sparsity and magnitude constraints is also uncommon. In addition, transferability across attack families and target models remains limited. Hence, we propose a SalIency-Guided sparse Mask Attack (SIGMA). On self-supervised speech features, we use post-hoc explainable artificial intelligence (XAI) techniques to produce saliency maps and identify the scope of the mask, and then restrict magnitude-bounded updates to this mask. The mask is computed once and can be reused across models and different sparsity attacks to amortise cost. We evaluate on the IEMOCAP and TESS datasets. Under matched budgets and across multiple sparse-attack settings, SIGMA maintains competitive attack success rates, navigating a conscious trade-off between attack efficacy and explanation consistency. SIGMA therefore provides an efficient and interpretable framework for analysing the vulnerability and explanation behaviour of SER models under structured perturbations.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《SIGMA: Saliency-Guided Sparse Mask Attacks for Speech Emotion Recognition》所界定。 从摘要看，作者主要围绕 emotion recognition 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：As Speech Emotion Recognition (SER) is usually deployed in privacy-sensitive and reliability-critical environments, adversarial attacks on SER have attracted increasing attention. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：emotion recognition。 |

---
## 🏷️ Audio

### 1. OLIVE: View-Augmented Latent Prediction with Waveform Reconstruction for Speech SSL

👤 **作者**: Karl El Hajal, Mathew Magimai. -Doss
🔗 **来源**: [https://arxiv.org/abs/2606.30356v1](https://arxiv.org/abs/2606.30356v1)

**摘要**
> We propose Online Latent prediction with Invariant Views and rEconstruction (OLIVE), a self-supervised speech representation learning framework that jointly optimizes analysis and synthesis objectives. OLIVE combines view-augmented masked latent prediction with waveform reconstruction under a unified objective. Reconstruction constrains early encoder features to retain signal-level information, while masked latent prediction shapes later contextual representations toward invariance for robust downstream performance. We show that these objectives enable representations that support a broad range of tasks. In particular, OLIVE improves results on generation and speaker tasks, maintains competitive performance on recognition and semantic tasks, and improves waveform reconstruction.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《OLIVE: View-Augmented Latent Prediction with Waveform Reconstruction for Speech SSL》所界定。 从摘要看，作者主要围绕 olive、view-augmented、latent 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We show that these objectives enable representations that support a broad range of tasks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：olive, view-augmented, latent。 |

---
### 2. Predicting Timbre Traits for Interpretable Assessment of Musical Sound Synthesizers

👤 **作者**: Théo Chasle Cauchy, Modan Tailleur, Lindsey Reymore, Fanny Roche, Mathieu Lagrange
🔗 **来源**: [https://arxiv.org/abs/2606.30369v1](https://arxiv.org/abs/2606.30369v1)

**摘要**
> Measuring neural audio synthesizers' performance is now routinely conducted using distribution based metrics such as the Fréchet Audio Distance (FAD). Although this metric can be correlated with human perception, it offers limited interpretability beyond ranking different approaches. In this paper, we introduce a deep neural timbre trait predictor composed of a pretrained audio neural embedding (CLAP), and a shallow learnable component. The latter is trained using the RWC musical instrument database and human judgments of 20 timbre descriptions (e.g., woody, percussive, rumbling, etc.) for 31 instruments. The resulting model shows strong correlation with average human ratings (r = 0.66, p < 0.001). We then demonstrate the benefit of this predictor for evaluating the performance of TokenSynth, a neural sound synthesizer. First, the Mean Absolute Error (MAE) computed over the set of generated sounds under different conditioning modalities of the model provides the same ranking as a FAD computed with the RWC database as a reference, suggesting that the proposed predictors are able to provide equivalent information on a distributional basis. Second, because the model is able to qualitatively analyze isolated sounds, we can determine which generated sounds could be improved and identify specific timbral dimensions that need adjustment.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Predicting Timbre Traits for Interpretable Assessment of Musical Sound Synthesizers》所界定。 从摘要看，作者主要围绕 predicting、timbre、traits 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The resulting model shows strong correlation with average human ratings (r = 0.66, p < 0.001). 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：predicting, timbre, traits。 |

---
### 3. LeVo 2: Stable and Melodious Song Generation via Hierarchical Representation Modeling and Progressive Post-Training

👤 **作者**: Shun Lei, Huaicheng Zhang, Dapeng Wu, Yaoxun Xu, Lishi Zuo, Wei Tan, Hangting Chen, Guangzheng Li, Jianwei Yu, Zhiyong Wu, Dong Yu
🔗 **来源**: [https://arxiv.org/abs/2606.30642v1](https://arxiv.org/abs/2606.30642v1)

**摘要**
> Full-length song generation must preserve coherence and musicality, render detailed vocal and accompaniment acoustics, and follow lyrics and prompts. Existing language model-based systems face a structural trade-off: mixed-token modeling preserves vocal-instrument coordination but obscures track-specific details, whereas dual-track prediction improves acoustics but requires longer sequences and weakens global planning. We present LeVo 2, a hybrid LLM-Diffusion framework for controllable full-length song generation. LeVo 2 formulates this trade-off as hierarchical modeling: LeLM first predicts mixed tokens for semantic planning, then predicts vocal and accompaniment tokens in parallel for track-specific refinement, while a diffusion-based Music Codec reconstructs full-length waveforms. A central contribution of this extended version is an aesthetics-guided training schedule for alignment. During pre-training, an automated music aesthetic evaluation framework assigns musicality-tier conditions to large-scale data, providing musicality priors before preference alignment. Progressive post-training applies SFT, large-scale offline DPO, and closed-loop semi-online DPO to separately improve generation quality, controllability, and musicality. Modular extension then trains the Track-Specific LM for acoustic refinement while preserving the aligned semantic planner. This schedule separates musicality learning, controllability alignment, and acoustic refinement, mitigating optimization conflict and the limitations of static offline preference pairs. Expert listening tests and objective evaluations show that LeVo 2 outperforms open-source baselines across six subjective dimensions, and approaches leading commercial systems on several listening metrics. Ablations validate the effects of the training strategy, aesthetics guidance, scaling, and hierarchical architecture.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《LeVo 2: Stable and Melodious Song Generation via Hierarchical Representation Modeling and Progressive Post-Training》所界定。 从摘要看，作者主要围绕 levo、stable、melodious 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Existing language model-based systems face a structural trade-off: mixed-token modeling preserves vocal-instrument coordination but obscures track-specific details, whereas dual-track prediction improves acoustics but requires longer sequences and weakens global planning. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：levo, stable, melodious。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
