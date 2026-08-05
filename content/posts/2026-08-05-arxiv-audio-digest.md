<div align="center">

# 📰 Paper Claw

**2026-08-05**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-04 11:55:42 CST → 2026-08-05 11:50:39 CST |
| 📄 论文总数 | **9** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 2 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 1 篇
- **Audio**: 6 篇

> 💡 今日共收录 9 篇新论文，主要分布在 ASR 2, Paralinguistics 1, Audio 6。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

### 1. Language-Specialized Multi-Teacher On-Policy Distillation for Multilingual LLM-Based ASR

👤 **作者**: Yuan Xie, Jiaqi Song, Xianliang Wang, Ming Lei, Jie Gao, Jie Wu
🔗 **来源**: [https://arxiv.org/abs/2608.03610v1](https://arxiv.org/abs/2608.03610v1)

**摘要**
> Modern LLM-based ASR systems have established multilingual capability as a standard feature, leveraging large-scale multilingual corpora and LLMs' cross-lingual knowledge to achieve competitive performance across multilingual benchmarks. However, joint modeling of languages with heterogeneous acoustic, phonological, and lexical characteristics inevitably introduces optimization conflicts, undermining language-wise specialization. To address this challenge, we propose Language-Specialized Multi-Teacher On-Policy Distillation (LS-MOPD), which decouples language-specific knowledge acquisition from multilingual capability integration: language-specialized teachers are independently optimized via reinforcement learning (RL), after which their expertise is integrated into a generalist multilingual student through language routing and token-level multi-teacher distillation, thereby reducing direct cross-lingual optimization conflicts. We further explore two acoustic-prefix configurations, static and dynamic, to examine how teacher--student prefix consistency influences the efficacy of on-policy distillation. Experiments on benchmarks covering Mandarin, Mandarin subdialects, Cantonese, and English demonstrate that LS-MOPD substantially outperforms RL baselines and consistently surpasses the empirical performance envelope defined by best-performing RL teachers, revealing its potential to generalize beyond all teachers in multilingual ASR.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Language-Specialized Multi-Teacher On-Policy Distillation for Multilingual LLM-Based ASR》所界定。 从摘要看，作者主要围绕 asr system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Modern LLM-based ASR systems have established multilingual capability as a standard feature, leveraging large-scale multilingual corpora and LLMs' cross-lingual knowledge to achieve competitive performance across multilingual benchmarks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：asr system。 |

---
### 2. Identity-Faithful Audio-Visual Target Speaker Extraction with QIANGDA and VOXBLINK2-AVSE

👤 **作者**: Peijun Yang, Zhan Jin, Juan Liu, Ming Li
🔗 **来源**: [https://arxiv.org/abs/2608.03964v1](https://arxiv.org/abs/2608.03964v1)

**摘要**
> Audio-visual target speaker extraction should return the speaker indicated by the video, yet a separator can ignore the visual cue and repeatedly output the acoustically dominant voice. We introduce QIANGDA, a Mandarin AV-TSE benchmark of jointly recorded real two-speaker mixtures with synchronized multi-view video. Each scene also contains preceding A-only and B-only stages that provide in-scene speaker references. It contains 77 scenes and 7,598 clips (11.84 hours), including 6,042 dual-annotated mixtures. After processing there leave 6,038 evaluable mixtures and 12,076 target-speaker rows. We additionally curate VOXBLINK2-AVSE from VoxBlink2, comprising 250,828 synchronized audio--lip-ROI pairs from 28,421 identities and 766.17 hours of speech. Our extractor uses frozen, 1,280-dimensional projected AV-HuBERT features, target-conditioned training, and layer-wise feature modulation. We jointly evaluate content with Qwen3-ASR-1.7B CER and target identity with WeSpeaker ResNet34 plus Overlapped Speech Detection (OSD). On the complete manifest, the best archived checkpoint obtains 0.2261 CER, 82.22% strict output correctness, and 69.53% both-output strict success.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Identity-Faithful Audio-Visual Target Speaker Extraction with QIANGDA and VOXBLINK2-AVSE》所界定。 从摘要看，作者主要围绕 hubert 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We introduce QIANGDA, a Mandarin AV-TSE benchmark of jointly recorded real two-speaker mixtures with synchronized multi-view video. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：hubert。 |

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

### 1. Speaker Verification Under Real Classroom Conditions for English Speech

👤 **作者**: Saba Tabatabaee, Jing Liu, Megh Krishnaswamy, Carol Espy-Wilson
🔗 **来源**: [https://arxiv.org/abs/2608.03623v1](https://arxiv.org/abs/2608.03623v1)

**摘要**
> Developing speaker verification (SV) models that are robust to classroom noise and effective across both children and adult speakers is critical for AI tools supporting educational environments. In this study, we use a real-world English-speaking classrooms dataset containing partial speaker identity annotations, with most recordings remaining unlabeled. We adapt the WavLM-TDNN model for classroom SV, achieving average relative reductions in Equal Error Rate (EER) of 23.99% and 6.32% compared to the ECAPA-TDNN baseline and the ECAPA-TDNN model trained on classroom data, respectively. Additionally, we investigate two training strategies for SV in classroom settings: self-supervised learning (SSL) and a two-stage approach that first pre-trains with SSL and then fine-tunes with limited annotated data. Five-fold cross-validation demonstrates that the two-stage strategy consistently outperforms the SSL-only approach, achieving an average relative EER reduction of 13.39%.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「副语言学」方向，核心任务由题目《Speaker Verification Under Real Classroom Conditions for English Speech》所界定。 从摘要看，作者主要围绕 speaker verification 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We adapt the WavLM-TDNN model for classroom SV, achieving average relative reductions in Equal Error Rate (EER) of 23.99% and 6.32% compared to the ECAPA-TDNN baseline and the ECAPA-TDNN model trained on classroom data, respectively. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speaker verification。 |

---
## 🏷️ Audio

### 1. Echo-Aware Modulation for Compact-Latent Frequency-Time Modeling in Lightweight Acoustic Echo Cancellation

👤 **作者**: Ye Ni, Ruiyu Liang, Qingyun Wang, Kai Xie, Cairong Zou, Björn W. Schuller
🔗 **来源**: [https://arxiv.org/abs/2608.03650v1](https://arxiv.org/abs/2608.03650v1)

**摘要**
> Existing lightweight acoustic echo cancellation (AEC) systems often combine linear AEC with Bark-domain DNN-based suppression to lower the computational footprint. In such systems, downsampling layers further compress the input features into a compact bottleneck representation, but this compression weakens frequency-time modeling capacity and degrades performance. To mitigate this limitation, we propose MSA-EchoLite, a lightweight Bark-domain AEC framework with an asymmetric dual-branch encoder and an echo-aware frequency-time modulation (EAM) module. The EAM module enriches the compressed bottleneck representation by modeling discrepancy and correlation cues between the dual-branch microphone and echo-related latent features. Experimental results show that the Bark-domain variant of MSA-EchoLite offers a better performance-complexity trade-off than its frequency-domain counterpart but is more sensitive to feature compression. With only 26.1% additional FLOPs over its non-EAM Bark-domain variant, its EAM-enhanced version achieves 99.1% of the PESQ of the frequency-domain counterpart, which requires nearly twice the FLOPs, and even surpasses it in SDR. Overall, MSA-EchoLite outperforms state-of-the-art lightweight AEC models while using only 0.2 M parameters and 100 M FLOPs/s.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Echo-Aware Modulation for Compact-Latent Frequency-Time Modeling in Lightweight Acoustic Echo Cancellation》所界定。 从摘要看，作者主要围绕 echo-aware、modulation、compact-latent 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results show that the Bark-domain variant of MSA-EchoLite offers a better performance-complexity trade-off than its frequency-domain counterpart but is more sensitive to feature compression. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：echo-aware, modulation, compact-latent。 |

---
### 2. On the Geometry of Music Bandwidth Extension in Latent Spaces of Audio Codecs

👤 **作者**: Hendrik Vincent Koops, Hao Hao Tan, Elio Quinton
🔗 **来源**: [https://arxiv.org/abs/2608.03721v1](https://arxiv.org/abs/2608.03721v1)

**摘要**
> Recent audio restoration increasingly relies on large-scale conditional latent generative modeling, including diffusion, Schrodinger Bridges, and Flow Matching variants, to invert degradations such as bandwidth limitation or noise. We present an analysis of the performance of various state-of-the-art methods compared to simple arithmetic transformations in the latent spaces of multiple neural codecs for musical bandwidth extension. We show that estimating a single transport vector between the clean and degraded latent centroids on a reference set, and adding it to degraded latents, can yield restoration performance competitive with large diffusion models. This suggests, first, that some neural codec latent spaces exhibit structure aligned with audio bandwidth; and second, that in such cases complex conditional models may offer only limited gains over a simple vector addition. We argue that these findings reveal an interesting avenue for future research whereby models could take advantage of the latent space structure in order to offer greater training and parameter efficiency, and overall better performance. Additionally, we propose to consider this simple arithmetic transformation as a baseline for music bandwidth extension research, as it allows an assessment of the contribution of learnable parameters towards restoration performance.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《On the Geometry of Music Bandwidth Extension in Latent Spaces of Audio Codecs》所界定。 从摘要看，作者主要围绕 geometry、music、bandwidth 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We present an analysis of the performance of various state-of-the-art methods compared to simple arithmetic transformations in the latent spaces of multiple neural codecs for musical bandwidth extension. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：geometry, music, bandwidth。 |

---
### 3. AI-Based Sound Effect Generation: A Narrative Review of Generative Models Across Input Modalities

👤 **作者**: Sandy Abdo, Bill Kapralos, Priyamvada Tripathi, KC Collins, Adam Dubrowski
🔗 **来源**: [https://arxiv.org/abs/2608.03742v1](https://arxiv.org/abs/2608.03742v1)

**摘要**
> Sound effects play a crucial role in conveying actions, events, and environmental cues across digital applications, often requiring a high degree of variation and contextual adaptability. Artificial intelligence (AI)-driven audio generative models are rapidly growing in popularity and have the potential to transform the way sound is synthesized and used across various applications. In response to this growing momentum, this chapter reviews and analyzes recent AI-based generative models for sound effect synthesis, with a focus on how different input modalities (text, visual, audio, and multimodal) affect the quality, controllability, and contextual relevance of the generated audio. It examines 30 peer-reviewed articles sourced from Google Scholar, IEEE Xplore, and the ACM Digital Library, exploring the evolution of AI generative models over the past five years. The results show that multiple models achieved state-of-the-art performance, producing high-fidelity, semantically aligned, and increasingly temporally coherent sound effects across tasks. However, despite these advances, the review identifies persistent challenges, including limitations in temporal synchronization for complex multi-event scenarios, gaps between objective metrics and human perception, and trade-offs between controllability and generative diversity. Overall, the chapter highlights that AI-driven sound effect generation is progressing toward more adaptive, scalable, and context-aware systems, offering significant implications for future sound design workflows and interactive media applications.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AI-Based Sound Effect Generation: A Narrative Review of Generative Models Across Input Modalities》所界定。 从摘要看，作者主要围绕 ai-based、sound、effect 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that multiple models achieved state-of-the-art performance, producing high-fidelity, semantically aligned, and increasingly temporally coherent sound effects across tasks. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：ai-based, sound, effect。 |

---
### 4. Equivariant Music Transformer

👤 **作者**: Zixun Guo, Simon Dixon
🔗 **来源**: [https://arxiv.org/abs/2608.03920v1](https://arxiv.org/abs/2608.03920v1)

**摘要**
> Humans recognize a musical passage even when it is shifted in time or transposed in pitch, indicating a notion of equivariance in the representation space. Our analysis, however, shows that standard music transformers map such time-shifted or pitch-transposed inputs onto uncorrelated representations: these models become progressively less equivariant as they scale in size or train longer. This suggests that in standard music transformers, additional model capacity is allocated to memorizing absolute patterns rather than capturing shared musical structures. In this paper, we propose the Equivariant Music Transformer (EMT), which enforces equivariance through self-distillation by jointly optimizing a next-token-prediction and an auxiliary equivariance regularization loss. We find that the additional equivariance loss acts as a beneficial regularizer, simultaneously improving next-token prediction and producing equivariant latent representations. Through both objective and subjective evaluations, EMT demonstrates superior equivariance and generative capability compared to data augmentation, feature engineering, and state-of-the-art (SOTA) baselines. More broadly, our findings reveal that standard language modeling methods alone do not capture music's translational symmetries, and dedicated inductive biases are required to produce better music representations. The code, weights and demos are available online.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Equivariant Music Transformer》所界定。 从摘要看，作者主要围绕 equivariant、music、transformer 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our analysis, however, shows that standard music transformers map such time-shifted or pitch-transposed inputs onto uncorrelated representations: these models become progressively less equivariant as they scale in size or train longer. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：equivariant, music, transformer。 |

---
### 5. Transfer Learning for Avian Bioacoustics under Sparse Positive Labels

👤 **作者**: Dhyey Patel, Yunting Yin
🔗 **来源**: [https://arxiv.org/abs/2608.03977v1](https://arxiv.org/abs/2608.03977v1)

**摘要**
> Passive acoustic monitoring is an important tool for biodiversity assessment and wildlife conservation because it supports continuous and non-invasive monitoring of species across large spatial and temporal scales. Robust monitoring remains challenging because many datasets contain sparse positive labels, where species presences may be confirmed while unannotated species cannot be assumed absent. In this work, we study transfer learning under sparse positive labels using BirdCLEF+ 2026 as a target benchmark and BirdCLEF 2021, iNatSounds, WABAD, and BirdSet as external bioacoustic sources. We introduce a multi-source reliability framework that models heterogeneous bioacoustic datasets as distinct supervision sources with differing reliability. Our approach achieves 0.584 macro average precision and 0.860 macro AUC on public BirdCLEF+ 2026 validation labels while outperforming naive source pooling strategies. The strongest gains arise from passive acoustic monitoring datasets and biologically informed source selection. Our findings suggest that transfer learning in bioacoustics is fundamentally a weak supervision and negative transfer problem.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Transfer Learning for Avian Bioacoustics under Sparse Positive Labels》所界定。 从摘要看，作者主要围绕 transfer、learning、avian 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our approach achieves 0.584 macro average precision and 0.860 macro AUC on public BirdCLEF+ 2026 validation labels while outperforming naive source pooling strategies. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：transfer, learning, avian。 |

---
### 6. Agogic: Performance-Timed Music Tokens for LLM-Native Text-to-Symbolic-Music Generation

👤 **作者**: Junhao Chen, Mingjin Chen, Jingjia Mao, Lin Chen, Saining Zhang, Minglin Chen, Ruocheng Wu, Liaoyuan Fan, Wenyi Li, Mingju Gao, Henghaofan Zhang, Zhihao Li, Hao Zhao, Yufei Wang, Ruqi Huang
🔗 **来源**: [https://arxiv.org/abs/2608.03999v1](https://arxiv.org/abs/2608.03999v1)

**摘要**
> Text-to-music language models begin with a choice usually made by default: how to tokenize music. Normally entangled with backbone, data, and recipe, its effect has never been measured in isolation. We fix pretrained Qwen3.5 (0.8B-27B), data, budget, and decoding, and swap only the representation across seven tokenizations, anchoring texture metrics to each representation's model-free ceiling. The ordering is clean and surprising: representation, not model size, is the binding variable for distributional fidelity. Scaling the backbone 34x barely moves Frechet Music Distance (FMD), whereas switching representation halves it. PMT, a performance-resolution stream we release (10 ms timing, per-note velocity, multi-track texture; 609 symbols), reaches FMD 159 at 0.8B against 272-286 for beat grids (1.7-1.8x lower, up to 2.8x elsewhere; non-overlapping bootstrap CIs), so a 0.8B performance-resolution model beats a 27B beat grid. It reappears on a 26M from-scratch backbone and a second performance-resolution tokenizer: a property of the class, not one lucky vocabulary. Nor is it a finer-lattice artifact: snapping PMT's onsets to the beat grids' resolution still leaves it 67-129 FMD ahead of both (n=500). The effect is distributional; whether it is audible is a separate question, left open by our probe, with a human study pre-registered. Native caption adherence is weak but separable: a lightweight decode-time constraint doubles instrument-F1 (.28 to .60) and Correct-Key (.16 to .35) at no distributional cost. We release the harness, 25+ checkpoints, two corpora (86.6k aligned across caption/MIDI/ABC/audio; 6.25M captioned, the largest for music), and an imprinting diagnostic: published text-to-MIDI systems reproduce their training distribution near-invariant to the caption (72% vs. 71% chord-time on disjoint domains). The field's next representation claim can now be measured, not asserted.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Agogic: Performance-Timed Music Tokens for LLM-Native Text-to-Symbolic-Music Generation》所界定。 从摘要看，作者主要围绕 agogic、performance-timed、music 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Normally entangled with backbone, data, and recipe, its effect has never been measured in isolation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：agogic, performance-timed, music。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
