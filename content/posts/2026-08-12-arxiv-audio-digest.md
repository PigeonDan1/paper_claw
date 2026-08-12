<div align="center">

# 📰 Paper Claw

**2026-08-12**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-11 10:55:56 CST → 2026-08-12 11:14:50 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, ASR 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. X2-Turn: Frame-Synchronous Dual-Head Modeling for Joint Streaming ASR and Turn State Prediction

👤 **作者**: Kaiqi Fu, Rime Wen, Altman Lin, Shawn Qin, Roy Gan, Hao Wang, Qian Wang
🔗 **来源**: [https://arxiv.org/abs/2608.10878v1](https://arxiv.org/abs/2608.10878v1)

**摘要**
> Accurate and responsive turn-taking is essential for spoken dialogue systems, which must distinguish in real time between user interruptions, backchannels that should be ignored, and the completion of an utterance. Prior modular approaches typically optimize turn state prediction at the utterance or fixed-chunk level, creating a mismatch with the continuous turn state estimate, and often depend on an auxiliary ASR model, which limits responsiveness and increases overall system complexity. Therefore, we present X2-Turn, a frame-synchronous turn state prediction method via delayed-stream modeling. Specifically, building on the pretrained Voxtral Realtime model, we introduce a frame-synchronous turn state head that operates in parallel with the ASR head on shared streaming representations, jointly predicting ASR tokens and fine-grained turn states at the frame level. We evaluate our method on the bilingual Chinese-English Easy-Turn test sets, and the results demonstrate its effectiveness in achieving accurate turn-taking detection while maintaining low latency.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《X2-Turn: Frame-Synchronous Dual-Head Modeling for Joint Streaming ASR and Turn State Prediction》所界定。 从摘要看，作者主要围绕 spoken dialogue、dialogue system 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We evaluate our method on the bilingual Chinese-English Easy-Turn test sets, and the results demonstrate its effectiveness in achieving accurate turn-taking detection while maintaining low latency. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：spoken dialogue, dialogue system。 |

---
## 🏷️ ASR

### 1. Whisper-Aware LLM: Self-Supervised Uncertainty Learning for Robust Whispered Speech Recognition

👤 **作者**: Gaopeng Xu, Zhenyu Wang, Zheng Xue, Yinfeng Xia, Haitao Yao
🔗 **来源**: [https://arxiv.org/abs/2608.10836v1](https://arxiv.org/abs/2608.10836v1)

**摘要**
> The signal ambiguity of whispered speech drives ASR systems toward two opposing failure modes: failing to capture whispered speech or hallucinatory transcription of noise. This paper introduces the Whisper-Aware LLM, a framework that teaches an Audio-LLM to perceive and react to this uncertainty. Our model develops an intrinsic self-awareness by learning to quantify the physical deficiencies of acoustic signals through targeted self-supervised tasks. This learned uncertainty is then operationalized via a novel Confidence-Fused Decoding mechanism, which provides both high-level instructions and frame-level attention modulation to the LLM decoder. Our experiments confirm the effectiveness of this approach. The model sets a new state-of-the-art on whispered speech with a 17% relative CER reduction on AISHELL6-Whisper. At the same time, it directly addresses the reliability trade-off, with hallucination rates dropping from over 25% to 4.5%.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《Whisper-Aware LLM: Self-Supervised Uncertainty Learning for Robust Whispered Speech Recognition》所界定。 从摘要看，作者主要围绕 asr system、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The model sets a new state-of-the-art on whispered speech with a 17% relative CER reduction on AISHELL6-Whisper. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：asr system, whisper。 |

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

### 1. The GENEA Challenge 2026: A Large-Scale Disentangled Evaluation of Speech-Driven Gesture Generation on the Seamless Interaction Dataset

👤 **作者**: Rajmund Nagy, Silvia Arellano García, Hendric Voss, Mihail Tsakov, Taras Kucherenko, Youngwoo Yoon, Gustav Eje Henter
🔗 **来源**: [https://arxiv.org/abs/2608.10839v1](https://arxiv.org/abs/2608.10839v1)

**摘要**
> This preprint presents the results of the fourth GENEA Challenge, a large-scale human evaluation of five speech-driven gesture-generation systems trained by participating teams on the Seamless Interaction dataset of dyadic conversations. As in the 2023 GENEA Challenge, we used a disentangled evaluation methodology to assess motion quality and speech alignment without confounding between the two, and performed a dyadic mismatching study to isolate the effect of listening and reacting to the interlocutor. We additionally introduce a new semantic gesture-generation task and a text-mismatching evaluation methodology using the Grounded Gestures subset of the data. In total, we ran four large-scale user studies, collecting over 23,000 votes from 869 test-takers. In the motion-realism study, the dataset's filtered segments had substantially higher motion quality than all challenge submissions (68-95% pairwise winrate). In the speech-alignment study, the motion-capture segments provided a conceptual ceiling at 62% alignment score, with the top submission significantly behind at 32% and the rest only slightly above the 0% expected of an input-independent system. In the dyadic study, motion capture again set the ceiling at 65% appropriateness score, but no submission scored substantially above chance, indicating that the systems could not yet respond to the interlocutor. Finally, the semantic mismatching evaluation found highly expressive gestures in the dataset (test-takers identified the matching transcript 79% of the time), yet almost all submissions failed to generate semantically expressive motion, with the best achieving only an 8% appropriateness score. The collected votes and outputs will be made publicly available at https://genea-workshop.github.io/2026/challenge/ to facilitate reproducibility and further research.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《The GENEA Challenge 2026: A Large-Scale Disentangled Evaluation of Speech-Driven Gesture Generation on the Seamless Interaction Dataset》所界定。 从摘要看，作者主要围绕 genea、challenge、large-scale 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Finally, the semantic mismatching evaluation found highly expressive gestures in the dataset (test-takers identified the matching transcript 79% of the time), yet almost all submissions failed to generate semantically expressive motion, with the best achieving only an 8% appropriateness score. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：genea, challenge, large-scale。 |

---
### 2. A Dataset and Benchmark for Optical Music Recognition of String Quartet Scores

👤 **作者**: Dongmin Kim, Brian Liu, Jose J. Valero-Mas, Dasaem Jeong
🔗 **来源**: [https://arxiv.org/abs/2608.10978v1](https://arxiv.org/abs/2608.10978v1)

**摘要**
> Optical music recognition (OMR) transcribes music scores into digital formats. While the field has advanced significantly on monophonic and piano-form scores, multi-part score transcription remains underexplored, largely due to the absence of a suitable dataset. We introduce OpenScore String Quartet for Optical Music Recognition (OSSQ-OMR), the first dataset dedicated to multi-part OMR. Built on the OpenScore String Quartet corpus, OSSQ-OMR pairs digitally encoded scores with their original scanned editions from IMSLP, with all images visually aligned to their transcriptions. The dataset is released with score images at system and staff levels, and paired transcriptions in three encoding formats: Extended Linearized MusicXML (LMXE), **kern, and ABC. In total, OSSQ-OMR contains 24,544 system images and 98,172 staff images drawn from 116 string quartet scores. We accompany the dataset with a benchmark protocol and baseline results from two representative OMR models, evaluated across four random score-level splits with mutually exclusive test sets. Baselines reach OMR-NED as low as 3.6% on synthetic and 5.9% on scanned inputs; results reveal substantial effects of encoding and segmentation choices, with the LSTM-based baseline degrading on scanned inputs roughly 2.6 times less than the Transformer-based baseline.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A Dataset and Benchmark for Optical Music Recognition of String Quartet Scores》所界定。 从摘要看，作者主要围绕 dataset、benchmark、optical 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While the field has advanced significantly on monophonic and piano-form scores, multi-part score transcription remains underexplored, largely due to the absence of a suitable dataset. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：dataset, benchmark, optical。 |

---
### 3. Pitch Contour Tokenization using VQ-VAE and Its Application on Korean Traditional Music Analysis

👤 **作者**: Seonguk Ju, Seola Cho, Sooin Chung, Danbinaerin Han, Dasaem Jeong
🔗 **来源**: [https://arxiv.org/abs/2608.10979v1](https://arxiv.org/abs/2608.10979v1)

**摘要**
> Computational analysis of music often relies on discrete representations, yet many musical traditions are organized around continuous pitch movement that resists segmentation into note-like units. For such traditions, the discrete units that analysis would build on are not given in advance. We address this gap by learning a vocabulary of local pitch-contour patterns directly from unlabeled audio, using a VQ-VAE that quantizes fixed-length contour segments into a finite codebook. To make the learned tokens stable across segmentation positions and small variations in timing and pitch range, we train the model with a reconstruction objective evaluated under the best alignment among a set of candidate temporal and pitch-domain transformations. Applied to Korean traditional music, the learned tokens recover information about expert-defined sigimsae categories without supervision, and in pansori individual tokens align with the two principal modes, Gyemyeonjo and Ujo, supporting their use as units for corpus-level analysis of contour-centric traditions.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Pitch Contour Tokenization using VQ-VAE and Its Application on Korean Traditional Music Analysis》所界定。 从摘要看，作者主要围绕 pitch、contour、tokenization 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：For such traditions, the discrete units that analysis would build on are not given in advance. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：pitch, contour, tokenization。 |

---
### 4. Measuring Cross-Cultural Style Diffusion Through Era Classification: US and Korean Popular Music

👤 **作者**: Dasol Lee, Minhee Lee, Seonguk Ju, Daewoong Kim, Harin Lee, Dasaem Jeong
🔗 **来源**: [https://arxiv.org/abs/2608.10980v1](https://arxiv.org/abs/2608.10980v1)

**摘要**
> Popular music circulates globally while being locally reinterpreted, yet this process of cross-cultural style diffusion has rarely been quantified. We propose an era-classification framework for measuring temporal alignment between chart cultures. CNN classifiers trained from scratch on Billboard Hot 100 audio are applied to Korean Melon chart songs. Korean chart songs from the 1960s through the 1980s are consistently inferred as belonging to earlier Billboard eras, by a median of about four to five years, while the same models remain unbiased on held-out Billboard audio. The offset then halves at the 1990s, to roughly two to three years, and holds there through the 2000s. Reverse inference shows a complementary narrowing, and the pattern holds across architectures and seeds. We interpret these results as reflecting how globally circulating pop styles were locally adopted and progressively synchronized. The framework can be applied to other pairs of chart cultures beyond the US-Korea case examined here.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Measuring Cross-Cultural Style Diffusion Through Era Classification: US and Korean Popular Music》所界定。 从摘要看，作者主要围绕 measuring、cross-cultural、style 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Reverse inference shows a complementary narrowing, and the pattern holds across architectures and seeds. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：measuring, cross-cultural, style。 |

---
### 5. MAJEPPA: Morphing and Assessing in a Unified Piano Performance Space

👤 **作者**: Jinwen Zhou, Huan Zhang, Weixi Zhai, Jinhua Liang, Aidan O. T. Hogg, Simon Dixon
🔗 **来源**: [https://arxiv.org/abs/2608.11026v1](https://arxiv.org/abs/2608.11026v1)

**摘要**
> We present MAJEPPA, a self-supervised framework to learn piano performance representations that span the full skill spectrum, from beginner practice sessions to virtuoso concert recordings. We curate the MAJEPPA dataset, comprising ~4,000 annotated recordings across six expertise levels and six recording contexts. We adapt a single pre-trained MIDI autoregressive model with a joint objective: next-token prediction learns score-conditioned performance generation at various skill levels, while InfoNCE and supervised contrastive losses align abstract score and performance representations in a joint embedding space. The proposed model both generates and understands performances in a unified framework. By introducing the EVPMR benchmark, a suite of downstream tasks spanning quality assessment, competition ranking, mistake and technique classification, we evaluate the learnt representations, demonstrating progress towards a real-world model for the piano performance space.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MAJEPPA: Morphing and Assessing in a Unified Piano Performance Space》所界定。 从摘要看，作者主要围绕 majeppa、morphing、assessing 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：By introducing the EVPMR benchmark, a suite of downstream tasks spanning quality assessment, competition ranking, mistake and technique classification, we evaluate the learnt representations, demonstrating progress towards a real-world model for the piano performance space. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：majeppa, morphing, assessing。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
