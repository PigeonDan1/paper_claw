<div align="center">

# 📰 Paper Claw

**2026-10-02**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-01 14:37:47 CST → 2026-10-02 14:21:13 CST |
| 📄 论文总数 | **6** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 6 篇新论文，主要分布在 TTS 1, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

> 📭 今日该分类暂无新论文。

---
## 🏷️ ASR

> 📭 今日该分类暂无新论文。

---
## 🏷️ TTS

### 1. Multi-sample Synthetic Supervision for Accent Conversion

👤 **作者**: Yangyang Qu, Michele Panariello, Massimiliano Todisco, Nicholas Evans
🔗 **来源**: [https://arxiv.org/abs/2610.01961v1](https://arxiv.org/abs/2610.01961v1)

**摘要**
> Accent conversion (AC) requires changing accent while preserving speaker identity and linguistic content, yet parallel recordings are scarce. Speech synthesis provides an alternative source of supervision, but generated targets vary in accent realization and source preservation. We propose a multi-sample synthetic supervision framework that constructs conversion targets by jointly assessing these properties across candidate waveforms for each source--accent condition. Selected candidates provide associated discrete speech codes, representing linguistic content, prosody, and speaking style, as targets for accent-conditioned autoregressive adaptation. Compared with using one generated target per training example, our method improves target-accent classification accuracy by 2.49 percentage points, while speaker similarity remains nearly unchanged, and word error rate increases by 0.29 percentage points. Across six target accents, our method achieves 7.81% WER and the highest mean listening ratings among evaluated systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《Multi-sample Synthetic Supervision for Accent Conversion》所界定。 从摘要看，作者主要围绕 speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Compared with using one generated target per training example, our method improves target-accent classification accuracy by 2.49 percentage points, while speaker similarity remains nearly unchanged, and word error rate increases by 0.29 percentage points. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech synthesis。 |

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

### 1. Beyond Decodability: Do Acoustic Factors Drive Predictions in Speech-Based Alzheimer's Assessment?

👤 **作者**: Serli Kopar, Alkis Koudounas, Roshan P. Rane, Sam Gijsen, Paula A. Perez-Toro, Kerstin Ritter
🔗 **来源**: [https://arxiv.org/abs/2610.01846v1](https://arxiv.org/abs/2610.01846v1)

**摘要**
> Speech-based Alzheimer's disease (AD) assessments increasingly rely on pretrained self-supervised learning (SSL) models that learn acoustic representations directly from raw audio, exposing the model to recording factors. We ask whether such factors are merely encoded in SSL representations or can systematically alter predictions. Using ADReSSo and three large SSL backbones, we apply controlled noise and reverberation interventions to participant-speech-only, non-speech, and full-recording audio. We combine layer-wise linear decoding, input- and representation-space interventions, and geometric alignment analysis to distinguish acoustic decodability from influence on AD prediction. Our results show that controlled acoustic interventions alter AD predictions across all three SSL backbones. Noise, despite showing no significant diagnostic-group difference in the original data, produces the strongest intervention effects. Importantly, these effects are systematically structured relative to the classifier's decision direction, replicate on the held-out test set and reverse when the representation-space intervention direction is reversed. Together, these findings show that high predictive performance and the absence of a significant diagnostic-group difference in a measured acoustic factor are not sufficient for robustness. We argue that intervention-based robustness tests should become standard for trustworthy clinical speech models.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond Decodability: Do Acoustic Factors Drive Predictions in Speech-Based Alzheimer's Assessment?》所界定。 从摘要看，作者主要围绕 beyond、decodability、acoustic 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results show that controlled acoustic interventions alter AD predictions across all three SSL backbones. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beyond, decodability, acoustic。 |

---
### 2. AVSD-Scenes: A Dataset for Audio-Visual Description of Urban Scenes

👤 **作者**: Dhanunjaya Varma Devalraju, Arshdeep Singh, Mark D. Plumbley
🔗 **来源**: [https://arxiv.org/abs/2610.01861v1](https://arxiv.org/abs/2610.01861v1)

**摘要**
> Natural language descriptions can provide rich semantic representations of audio-visual urban scenes, yet datasets that jointly describe both auditory and visual information remain limited. In this paper, we introduce AVSD-Scenes, a paired audio-visual scene description dataset for urban environments. The dataset contains 12,291 audio-visual scene descriptions generated from the TAU Urban Audio-Visual Scenes dataset. To construct the dataset, we first generate audio- and visual-based descriptions using Qwen2-Audio-7B and Qwen2.5-VL-7B, respectively. These modality-specific descriptions are then combined using large language models, namely Qwen3-14B, Mistral-Small-3.2-24B-Instruct-2506, and Gemma-3-27B-it, to produce multimodal descriptions that capture complementary information from both modalities. We benchmark AVSD-Scenes using semantic alignment, cross-modal retrieval, scene classification, LLM-as-a-judge evaluation, and human subjective assessment. Results show that multimodal descriptions improve semantic alignment and cross-modal retrieval performance compared with modality-specific descriptions while preserving strong scene-discriminative information. The generated descriptions achieve up to 94.5% accuracy in urban scene classification, while combining audio, visual, and description embeddings further improves accuracy to 95.4%. Furthermore, the descriptions remain highly scene-discriminative even when scene labels are removed from the prompting instructions, indicating that they capture semantic information derived from the audio-visual content rather than merely reflecting label information.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AVSD-Scenes: A Dataset for Audio-Visual Description of Urban Scenes》所界定。 从摘要看，作者主要围绕 avsd-scenes、dataset、audio-visual 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that multimodal descriptions improve semantic alignment and cross-modal retrieval performance compared with modality-specific descriptions while preserving strong scene-discriminative information. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：avsd-scenes, dataset, audio-visual。 |

---
### 3. From Isolated Feature to Orbits: Discovering Music Concepts via Multi-SAE Alignment

👤 **作者**: Liwei Lin, Gus Xia
🔗 **来源**: [https://arxiv.org/abs/2610.01864v1](https://arxiv.org/abs/2610.01864v1)

**摘要**
> How can we understand what a music foundation model has learned \textit{internally}? Most interpretability approaches, such as probing and Sparse Autoencoders (SAEs), focus on identifying individual features with minimal structural assumptions. We argue that many concepts are better understood as \textit{structured relations} rather than isolated features. This is especially prominent in music, where tonal structures are organized in the space of pitch and time. For example, concepts such as chords or keys are naturally expressed as structured sets (e.g., the 12 transpositions of a chord or the diatonic system within a key), rather than isolated features. In this study, \textbf{we shift from feature identification to structure-based analysis}, asking whether the learned inner representations of music foundation model emerge as organized structures over features. To this end, we introduce a framework that uses pitch transposition as an inductive bias to induce ordered orbits via multi-view SAE alignment. Concretely, we generate pitch-shifted input pairs and align their SAE representations to discover structured groups of pitch-related features. Experimental results show that this approach recovers orbit structures corresponding to chords, keys, and melodic patterns across two state-of-the-art music foundation models, while requiring only minimal grounding (e.g., a few anchor examples) to interpret entire concept families.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《From Isolated Feature to Orbits: Discovering Music Concepts via Multi-SAE Alignment》所界定。 从摘要看，作者主要围绕 from、isolated、feature 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experimental results show that this approach recovers orbit structures corresponding to chords, keys, and melodic patterns across two state-of-the-art music foundation models, while requiring only minimal grounding (e.g., a few anchor examples) to interpret entire concept families. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：from, isolated, feature。 |

---
### 4. LAST: Looped Audio Spectrogram Transformer

👤 **作者**: Haider Al-Tahan, Sean O'Brien, Anastasia Razdaibiedina, N. Apurva Ratan Murty
🔗 **来源**: [https://arxiv.org/abs/2610.01926v1](https://arxiv.org/abs/2610.01926v1)

**摘要**
> Increasing depth of transformer models improves recognition, but it comes at a substantial cost. Each additional layer requires more parameters, which makes the process computationally inefficient. We ask whether additional processing can focus on integrating features already computed. Looped Audio Spectrogram Transformer (LAST) first processes all tokens, then reuses the same blocks to refine only the class token over fixed audio features, thereby making later passes inexpensive. On AudioSet, ten-pass LAST achieves 0.345 mean average precision, exceeding a twelve-layer sequential transformer by 2.1% relative with 49.4% fewer parameters, 42% fewer multiply-accumulate operations, and 9.8% higher measured throughput. Across separately trained models, increasing the pass count from two to ten improves accuracy while adding only 1.2% computation. Further evaluations show improved robustness to temporal masking and various other auditory augmentations, with better generalization on classification tasks with music, environmental, and event sounds.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《LAST: Looped Audio Spectrogram Transformer》所界定。 从摘要看，作者主要围绕 last、looped、audio 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Increasing depth of transformer models improves recognition, but it comes at a substantial cost. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：last, looped, audio。 |

---
### 5. Shared-State Local Translations for Training-Free Voice Conversion

👤 **作者**: Yangyang Qu, Michele Panariello, Massimiliano Todisco, Nicholas Evans
🔗 **来源**: [https://arxiv.org/abs/2610.01952v1](https://arxiv.org/abs/2610.01952v1)

**摘要**
> In one-shot training-free voice conversion (VC), the source and reference utterances may contain different linguistic content, so reliable frame-level correspondence between them cannot be assumed. We propose StateVC, which jointly defines a common set of local regions from pooled frame-level WavLM representations of the source and reference utterances; we refer to these regions as states. These shared states are obtained by fitting a pair-specific Gaussian mixture model to the pooled representations, without explicit source--reference frame matching. Within each state, StateVC estimates a source-to-reference mean shift in the original WavLM space. Source-frame posterior probabilities then combine the state-specific shifts so that different frames can receive different local updates. For the LibriSpeech one-shot protocol, StateVC achieves the lowest word error rate (WER) and character error rate (CER) among the evaluated systems, at 8.01% and 3.22%, respectively, with a speaker similarity (SIM) of 0.9512. It also achieves the highest mean perceived speaker similarity among the evaluated systems and the highest mean naturalness among the evaluated training-free systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Shared-State Local Translations for Training-Free Voice Conversion》所界定。 从摘要看，作者主要围绕 shared-state、local、translations 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：For the LibriSpeech one-shot protocol, StateVC achieves the lowest word error rate (WER) and character error rate (CER) among the evaluated systems, at 8.01% and 3.22%, respectively, with a speaker similarity (SIM) of 0.9512. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：shared-state, local, translations。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
