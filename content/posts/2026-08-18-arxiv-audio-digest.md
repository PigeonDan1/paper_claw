<div align="center">

# 📰 Paper Claw

**2026-08-18**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-17 10:10:26 CST → 2026-08-18 10:06:44 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 6 篇

> 💡 今日共收录 6 篇新论文，主要分布在 Audio 6。
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

### 1. Contrastive Learning with Variational Regularization for Multi-Session EEG-to-Speech Decoding

👤 **作者**: Tomoaki Mizuno, Toru Nakashika
🔗 **来源**: [https://arxiv.org/abs/2608.16360v1](https://arxiv.org/abs/2608.16360v1)

**摘要**
> Reconstructing heard speech from non-invasive electroencephalography (EEG) is challenging due to a low signal-to-noise ratio (SNR) and inter-session variability. While trial averaging improves the SNR, it is difficult to apply to continuous speech. We instead use repeated EEG responses to the same stimulus across different sessions as positive pairs for contrastive learning, and introduce variational regularization that, combined with this contrastive objective, keeps the encoder representation space broad. Experiments on a Japanese EEG dataset show that combining the session-invariant strategy with variational regularization improves the character error rate (CER) while maintaining mel-spectrogram reconstruction fidelity. Session probing confirms that the encoder representations achieve session-invariance.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Contrastive Learning with Variational Regularization for Multi-Session EEG-to-Speech Decoding》所界定。 从摘要看，作者主要围绕 contrastive、learning、with 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：While trial averaging improves the SNR, it is difficult to apply to continuous speech. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：contrastive, learning, with。 |

---
### 2. Unadapted Multilingual ASR on a Garrusi Kurdish Evaluation Set: A Common-Reference Staged Normalization Analysis

👤 **作者**: Hiwa Asadpour
🔗 **来源**: [https://arxiv.org/abs/2608.16379v1](https://arxiv.org/abs/2608.16379v1)

**摘要**
> Evaluating speech recognition for a Kurdish variety written in a Latin field orthography, using a model that outputs Arabic script, creates a measurement problem before a modelling one: direct scoring treats writing-system differences as recognition errors. Jointly normalizing reference and hypothesis avoids this, but also changes reference tokenization, mixing agreement gains with a change in the scoring denominator. I evaluate MMS-1B-all with the Central Kurdish (ckb) adapter, used as released without adaptation, on 1,722 Garrusi questionnaire segments from five speakers (9,763 reference word tokens; 117.9 minutes). I use a common-reference design: the reference is folded once and fixed at 9,763 tokens, while only the hypothesis representation varies. The raw Arabic-script hypothesis scores 111.70% WER and 100.92% CER, with zero exact word matches. Latin transliteration gives 102.36% WER and 57.89% CER; folding it into the reference's reduced orthography gives 97.85% and 51.20%. Thus RAW-to-FOLDED reduces measured WER by 13.85 points and CER by 49.72 points; folding alone accounts for 4.51 and 6.69 points. Substantial error remains: 14.53% of reference tokens are exact matches, edits are substitution-dominated, and per-segment WER is higher for shorter segments. A Southern Kurdish fine-tuned system (aranemini/southern-kurdish-asr), scored under the same design, performs worse on every speaker (1,703 segments), with 109.56% WER and 55.85% CER. However, 12,330 output characters fall outside the folding table, so these rates must be recomputed against the corrected fixed reference. The MMS output also contains 613 unconverted or unmapped characters, showing that part of the residual error reflects scoring-pipeline limits rather than recognition alone. I will release the fixed reference and segment-level results, subject to source-corpus sharing terms, to support independent checking.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Unadapted Multilingual ASR on a Garrusi Kurdish Evaluation Set: A Common-Reference Staged Normalization Analysis》所界定。 从摘要看，作者主要围绕 unadapted、multilingual、garrusi 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The MMS output also contains 613 unconverted or unmapped characters, showing that part of the residual error reflects scoring-pipeline limits rather than recognition alone. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：unadapted, multilingual, garrusi。 |

---
### 3. Sonifying I2S Transport Signals to Detect Transmission Faults

👤 **作者**: Stephen Roddy
🔗 **来源**: [https://arxiv.org/abs/2608.16498v1](https://arxiv.org/abs/2608.16498v1)

**摘要**
> This paper outlines a sonification design to support fault detection in the transmission of I2S transport signals. I2S is a protocol for communicating real-time digital audio between integrated circuits that, while in wide and general use, does not include built-in error detection. Moreover, given the nature of the protocol transmission faults affecting timing, framing and alignment can be difficult to identify using conventional visual methods. The proposed design addresses this with an approach informed by Audification, wherein oversampling controls temporal rescaling to render protocol structure (SCK and WS) and payload data (SD) across separate stereo channels. A preliminary computational feasibility study was carried out to measure feature-space separability of I2S faults in the generated auditory representations as opposed to listener performance. It evaluates the design across several payload types and error conditions including jitter, bit-slip, and word-length errors. Class separability was assessed through clustering analyses of extracted features. The evaluation results show that while oversampling produces systematic changes in feature values, it does not meaningfully improve separability between error classes. However, a modest but consistent improvement in separability is observed as a function of the joint representation of structural and payload information across channels. The findings suggest that feature-space separability in sonified communication protocol data may be dependent on the integration of complementary information streams, rather than on signal scaling alone.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Sonifying I2S Transport Signals to Detect Transmission Faults》所界定。 从摘要看，作者主要围绕 sonifying、transport、signals 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The evaluation results show that while oversampling produces systematic changes in feature values, it does not meaningfully improve separability between error classes. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sonifying, transport, signals。 |

---
### 4. Listen, Reason, and Segment: Aligning LALMs with Editorial Judgment for Media Chapterization

👤 **作者**: Tony Alex, Wish Suharitdamrong, Sara Atito, Armin Mustafa, Muhammad Awais, Philip J. B. Jackson, Jiankang Deng, Ismail Elezi
🔗 **来源**: [https://arxiv.org/abs/2608.16539v1](https://arxiv.org/abs/2608.16539v1)

**摘要**
> Large Audio Language Models (LALMs) have made rapid progress on standardized benchmarks, yet their deployment in practical media workflows, curation, archival indexing, and content distribution remains largely unrealized. We identify automated audio chapterization, the task of segmenting continuous audio streams into thematically coherent chapters, as a demanding and commercially consequential setting that exposes this gap. Chapterization is challenging because boundaries are defined less by objective acoustic events than by subjective editorial judgment, requiring models to reason sequentially over long acoustic contexts and approximate creator-authored boundary decisions. We present AudioChaps, a post-training framework for aligning end-to-end LALMs for this task via Group Relative Policy Optimization (GRPO) guided by Chain-of-Thought (CoT) reasoning. To support training and evaluation, we curate three datasets: AudioChaps-Alignment, derived from creator-annotated chapter boundaries on YouTube; AudioChaps-CoT, which provides structured supervision for well-formatted, high-quality, and evidence-grounded boundary reasoning; and AudioChaps-Eval, a held-out benchmark for audio chapterization. Applying GRPO directly without a Supervised Fine-Tuning (SFT) cold start, AudioChaps-R1-Zero already improves average F1 by 33 points over the state-of-the-art LALM Audio-Flamingo-3-Think. The AudioChaps framework produces our final aligned LALM, AudioChaps-R1, which improves average F1 by 49 points. These results demonstrate that GRPO-trained LALMs can reliably transform unstructured auditory streams into navigable, structured media. Our code, models, and dataset resources will be released upon acceptance at https://github.com/ta012/AudioChaps.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Listen, Reason, and Segment: Aligning LALMs with Editorial Judgment for Media Chapterization》所界定。 从摘要看，作者主要围绕 listen、reason、segment 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Applying GRPO directly without a Supervised Fine-Tuning (SFT) cold start, AudioChaps-R1-Zero already improves average F1 by 33 points over the state-of-the-art LALM Audio-Flamingo-3-Think. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：listen, reason, segment。 |

---
### 5. How Fragile Is Your Watermark? Training-Free Structural Removal of Neural Audio Watermarks

👤 **作者**: Likhith Kumara
🔗 **来源**: [https://arxiv.org/abs/2608.16566v1](https://arxiv.org/abs/2608.16566v1)

**摘要**
> Neural audio watermarks are increasingly used to attribute and detect AI-generated speech, so their practical value rests on how cheaply an adversary can remove them. Robustness is usually measured by running a fixed battery of distortions blindly against every scheme. We instead make removal diagnostic: from a few clean/watermarked pairs we compute cheap structural probes that reveal where a watermark sits in the signal (its embedding domain), then apply a single domain-matched attack rather than a blind sweep. We further summarize each scheme with one threshold-free fragility score, the area under its accuracy-versus-quality trade-off, which an accuracy-only benchmark cannot provide. Across ten watermarking schemes the probes separate fragile from robust marks: for magnitude and carrier-domain watermarks a single matched attack erases the payload (WavMark, SilentCipher, audiowmark) or removes the detection flag (AudioSeal) at high objective quality (PESQ >= 3.6), whereas latent-domain marks (VoiceMark, WMCodec, AlignMark, AWARE) resist every training-free attack we apply. The same pair-only probe signatures also identify which watermarking scheme is present (84% over ten schemes).

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《How Fragile Is Your Watermark? Training-Free Structural Removal of Neural Audio Watermarks》所界定。 从摘要看，作者主要围绕 fragile、your、watermark 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Robustness is usually measured by running a fixed battery of distortions blindly against every scheme. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：fragile, your, watermark。 |

---
### 6. Numerical and perceptual validity of synthetic Head-Related Transfer Functions at scale

👤 **作者**: Katarina C. Poole, Lorenzo Picinali
🔗 **来源**: [https://arxiv.org/abs/2608.16722v1](https://arxiv.org/abs/2608.16722v1)

**摘要**
> Individually measuring head-related transfer functions (HRTFs) at scale remains a central challenge for personalised spatial audio, motivating growing interest in synthetic HRTFs. We evaluated the numerical, computational, and behavioural validity of synthetic HRTFs, generated through the boundary element method simulation using Mesh2HRTF, against measured and KEMAR HRTFs using the Extended SONICOM dataset. Across 200 subjects, synthetic HRTFs deviated less from measured than KEMAR in interaural time and level differences, but residual errors, together with elevated spectral distortion, concentrated at low, rear elevations. This is consistent with the omission of torso geometry from the synthesis pipeline. Two computational models revealed a corresponding pattern of predicted localisation errors, with synthetic HRTFs positioned between measured and KEMAR. In a virtual reality localisation task (N = 20), synthetic HRTFs matched measured on every polar metric, while KEMAR was significantly worse. However, behavioural error clustered around the front-back midline regardless of condition, not at the low elevations implicated numerically or by the models. A separate spatial release from masking task (N = 18) showed no effect of HRTF type. Together, these results indicate that high-resolution synthetic HRTFs preserve behavioural localisation performance, despite discrepancies between the numerical/model-predicted bias and the spatial pattern of behavioural error.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Numerical and perceptual validity of synthetic Head-Related Transfer Functions at scale》所界定。 从摘要看，作者主要围绕 numerical、perceptual、validity 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：A separate spatial release from masking task (N = 18) showed no effect of HRTF type. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：numerical, perceptual, validity。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
