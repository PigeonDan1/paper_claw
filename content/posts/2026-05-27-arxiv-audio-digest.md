<div align="center">

# 📰 Paper Claw

**2026-05-27**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-05-26 12:54:23 CST → 2026-05-27 13:05:43 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 1 篇
- **TTS**: 1 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 1, ASR 1, TTS 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Learning When to Think While Listening in Large Audio-Language Models

👤 **作者**: Zhiyuan Song, Weici Zhao, Yang Xiao, Suhao Yu, Cheng Zhu, Jiatao Gu
🔗 **来源**: [https://arxiv.org/abs/2605.27190v1](https://arxiv.org/abs/2605.27190v1)

**摘要**
> Recent advances in Large Audio-Language Models (LALMs) have made real-time, streaming spoken interaction increasingly practical. In this setting, reasoning quality and responsiveness are tightly coupled: delaying reasoning until the speech endpoint can improve answer quality but moves deliberation into user-visible response delay, while answering too early risks committing before decisive evidence arrives. We introduce a learnable wait-think-answer control formulation for LALMs. Motivated by the incremental nature of human conversation, the controller decides under partial audio evidence when to wait, when to externalize a compact reasoning update, and when to answer. Using Qwen2.5-Omni-7B as the base model, we construct aligned wait-think-answer traces from spoken reasoning data, train the controller with supervised fine-tuning (SFT), and then apply Decoupled Clip and Dynamic Sampling Policy Optimization (DAPO). The reward combines answer correctness, action validity, update timing, latency synchronization, reasoning quality, and chain consistency, optimizing the complete wait-think-answer trajectory and not the final answer alone. On a six-task synthetic spoken reasoning question answering (SRQA) benchmark, the six-reward DAPO controller improves the row-weighted accuracy from 67.6% to 70.3% while reducing post-endpoint final-think length by 14% under the same Qwen deployment harness. On a 186-item human-recorded Real Audio Bench, a transfer check beyond text-to-speech (TTS)-rendered speech, the controller family remains functional: SFT achieves the strongest accuracy, while the six-reward DAPO controller is the only learned variant whose final-think length falls below the base. These results suggest that a streaming model should learn when to make intermediate reasoning explicit during the audio stream.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Learning When to Think While Listening in Large Audio-Language Models》所界定。 从摘要看，作者主要围绕 audio-language model、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In this setting, reasoning quality and responsiveness are tightly coupled: delaying reasoning until the speech endpoint can improve answer quality but moves deliberation into user-visible response delay, while answering too early risks committing before decisive evidence arrives. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model, text-to-speech。 |

---
## 🏷️ ASR

### 1. PashtoTTS-Bench: automated screening for low-resource non-Latin-script text-to-speech

👤 **作者**: Hanif Rahman
🔗 **来源**: [https://arxiv.org/abs/2605.26978v1](https://arxiv.org/abs/2605.26978v1)

**摘要**
> Text-to-speech (TTS) evaluation for low-resource non-Latin-script languages can fail when it relies on a single ASR round-trip word error rate (WER). A system may produce no audio, speak a neighbouring language, preserve target script text only in an ASR transcript, or sound unnatural to native listeners. We introduce INSV (Intelligibility, Naturalness, Script fidelity, and Verification), a reporting framework that separates these cases. This paper reports INSV-A, the automated screening subset: synthesis completion, ASR WER/CER, transcript Script Fidelity Rate, and audio language identification. Native MOS and phonetic annotation are specified but not claimed in this release. We instantiate INSV-A as PashtoTTS-Bench, a dated benchmark for Pashto TTS. The April-May 2026 run evaluates Edge GulNawaz, Edge Latifa, OmniVoice clone, OmniVoice auto, and an Urdu negative control on 200 FLEURS and 200 filtered Common Voice 24 prompts. Under the independent omniASR_CTC_300M_v2, OmniVoice auto has the lowest WER (24.1% FLEURS, 27.4% CV24), followed by Edge GulNawaz (32.8%, 39.5%), Edge Latifa (35.6%, 47.7%), and OmniVoice clone (45.4%, 34.8%). WER below the natural-speech baseline reflects clean synthetic audio and should not be read as better than native speech. Whisper Large V3 returns 0.0% Pashto labels on checked Pashto TTS audio, while MMS-LID-4017 and SpeechBrain VoxLingua107 separate Pashto outputs from the Urdu control. The release provides provider metadata, per-sentence scores, LID audits, failure logs, and scripts for adding systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音识别」方向，核心任务由题目《PashtoTTS-Bench: automated screening for low-resource non-Latin-script text-to-speech》所界定。 从摘要看，作者主要围绕 whisper、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：A system may produce no audio, speak a neighbouring language, preserve target script text only in an ASR transcript, or sound unnatural to native listeners. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：whisper, text-to-speech。 |

---
## 🏷️ TTS

### 1. PilotTTS: A Disciplined Modular Recipe for Competitive Speech Synthesis

👤 **作者**: Bowen Li, Shaotong Guo, Zhen Wang, Yang Xiang, Mingli Jin, Yihang Lin, Jiahui Zhao, Weibo Xiong, Dongrui Li, Keming Chen, Yunze Gao, Yuze Zhou, Zeyang Lin, Yue Liu
🔗 **来源**: [https://arxiv.org/abs/2605.27258v1](https://arxiv.org/abs/2605.27258v1)

**摘要**
> Building state-of-the-art text-to-speech (TTS) systems typically demands millions of hours of proprietary data and complex multi-stage architectures, creating substantial barriers for resource-constrained research teams. In this report, we present PilotTTS, a lightweight autoregressive TTS system that achieves competitive performance through minimalist architecture and rigorous data engineering. PilotTTS is trained on only 200K hours of data processed entirely with open-source tools. Specifically, our contributions are: (1) a reproducible multi-stage data processing pipeline covering quality assessment, label annotation, and filtering, and (2) a compact model architecture that employs Q-Former-based conditioning to decouple speaker identity from speaking style via cross-sample paired training. Within a unified framework, PilotTTS supports zero-shot voice cloning, emotion synthesis (11 categories), paralinguistic synthesis (4 categories), and Chinese dialect synthesis (14 dialects). On the Seed-TTS Eval benchmark, PilotTTS achieves the lowest WER of 1.50% on test-en, a CER of 0.87% on test-zh, and the highest speaker similarity on both test sets (0.862 and 0.815), outperforming systems trained on significantly larger datasets. We release the complete data pipeline recipe, pretrained weights, and code at https://github.com/AMAPVOICE/PilotTTS.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音合成」方向，核心任务由题目《PilotTTS: A Disciplined Modular Recipe for Competitive Speech Synthesis》所界定。 从摘要看，作者主要围绕 text-to-speech、tts system、speech synthesis 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Building state-of-the-art text-to-speech (TTS) systems typically demands millions of hours of proprietary data and complex multi-stage architectures, creating substantial barriers for resource-constrained research teams. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：text-to-speech, tts system, speech synthesis。 |

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

### 1. Why Can't They Remember? Uncovering Representation and Retrieval Bottlenecks in Multi-Turn Acoustic Memory

👤 **作者**: Yang Xiao, Siyi Wang, Han Yin, Hong Jia, Vidhyasaharan Sethu, Eun-Jung Holden, Ting Dang
🔗 **来源**: [https://arxiv.org/abs/2605.27039v1](https://arxiv.org/abs/2605.27039v1)

**摘要**
> Large audio language models (LALMs) process both speech and environmental acoustic cues, yet struggle to retain non-speech information across multi-turn interactions. The performance gap between semantic (speech) and acoustic (non-speech) understanding remains poorly understood, and the underlying mechanisms of representation and retrieval are still unclear. This work introduces EnvMem, a controlled multi-turn benchmark designed to study this gap and identify the root causes of failures at the representation (i.e., latent embeddings) and retrieval levels (i.e., attention allocation). We further conduct post-hoc interventions to probe representational structure and attention dynamics. Our results reveal representational trajectory drift as the key failure mode, while showing that attention allocation plays a limited role in explaining the observed degradation. Overall, we provide a systematic framework for analyzing and improving non-linguistic memory in long-context LALMs, shedding light on future data and training design for robust acoustic memory modeling.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Why Can't They Remember? Uncovering Representation and Retrieval Bottlenecks in Multi-Turn Acoustic Memory》所界定。 从摘要看，作者主要围绕 they、remember、uncovering 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our results reveal representational trajectory drift as the key failure mode, while showing that attention allocation plays a limited role in explaining the observed degradation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：they, remember, uncovering。 |

---
### 2. An investigation of AI integration in sound designer workflows and experiences

👤 **作者**: Nelly Garcia, Joshua Reiss
🔗 **来源**: [https://arxiv.org/abs/2605.27174v1](https://arxiv.org/abs/2605.27174v1)

**摘要**
> Artificial intelligence is increasingly being integrated into professional audio production workflows, yet a gap persists between the tools developers produce and the requirements of practising sound designers. This paper investigates this gap through a mixed-methods study comprising a survey of 76 practitioners and follow-up semi-structured interviews with 20 industry professionals. Results were analysed using descriptive statistical analysis and thematic analysis to identify patterns across both datasets. Five themes emerged from our analysis: Context, Workflow, Potential, Risks, and Right Use. Our work indicates that current AI tools perform adequately in fast-consumption media contexts but lack the narrative sophistication required for high-end sound design (films, immersive experiences etc). Practitioners demonstrate a preference for assistive, task-specific applications, particularly in audio restoration and library management, over end-to-end generative systems. This work contributes to the on-going discussion on the use of AI and AI-enhanced tools in the creative industries. We report on the current status of the field from the point of view of sound designers and creative audio practitioners, and offer a set of recommendation for sound technologist and developers based on our findings to guide the development of more informed AI tools for sound design.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《An investigation of AI integration in sound designer workflows and experiences》所界定。 从摘要看，作者主要围绕 investigation、integration、sound 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Practitioners demonstrate a preference for assistive, task-specific applications, particularly in audio restoration and library management, over end-to-end generative systems. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：investigation, integration, sound。 |

---
### 3. Beyond Binary: Speech Representations Across the Cognitive Score Hierarchy

👤 **作者**: Serli Kopar, Roshan Prakash Rane, Christian Mychajliw, Lydia Federmann, Gerhard Eschweiler, Daniela Berg, Sam Gijsen, Paula Andrea Perez-Toro, Kerstin Ritter
🔗 **来源**: [https://arxiv.org/abs/2605.27189v1](https://arxiv.org/abs/2605.27189v1)

**摘要**
> This study examines the relationship between speech representations and the hierarchical structure of cognitive assessment in mild cognitive impairment. Utilizing 5,754 German neuropsychological assessment recordings, we evaluate six cognitive tasks across three score levels: task, domain, and global levels. We compare hand-crafted acoustic features with self-supervised learning (SSL) embeddings. Results show that although SSL representations generally outperform hand-crafted features at lower levels, this trend reverses for MCI classification. Furthermore, task-specific constraints influence performance: tasks with greater response freedom exhibit performance dilution as hierarchical levels increase, suggesting ``specialist'' representations, whereas the performance of highly structured tasks increases toward higher levels, suggesting ``generalist'' representations. These findings show links between task constraints and assessment hierarchy in automated clinical speech analysis.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Beyond Binary: Speech Representations Across the Cognitive Score Hierarchy》所界定。 从摘要看，作者主要围绕 beyond、binary、speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Results show that although SSL representations generally outperform hand-crafted features at lower levels, this trend reverses for MCI classification. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beyond, binary, speech。 |

---
### 4. MERIT: Learning Disentangled Music Representations for Audio Similarity

👤 **作者**: Abhinaba Roy, Junyi Liang, Dorien Herremans
🔗 **来源**: [https://arxiv.org/abs/2605.27346v1](https://arxiv.org/abs/2605.27346v1)

**摘要**
> Current music similarity models typically compute a single, monolithic score, entangling distinct musical dimensions like melody, rhythm, and timbre. This limits user control and interpretability, making it impossible to execute nuanced queries. We introduce MERIT, a framework for learning disentangled, factor-specific music representations tailored to these three core dimensions. To overcome the lack of isolated musical variations in real-world audio, we use a novel training strategy that uses conditional audio generation and source-separated stems to strongly encourage single-factor variation in training data. Our evaluations demonstrate strong factor-wise disentanglement. Each head responds strongly to its intended perceptual dimension while remaining near chance on the others, a representational property that holds across both the synthetic training domain and independent real-world audio.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MERIT: Learning Disentangled Music Representations for Audio Similarity》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our evaluations demonstrate strong factor-wise disentanglement. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
