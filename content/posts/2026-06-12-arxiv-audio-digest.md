<div align="center">

# 📰 Paper Claw

**2026-06-12**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-06-11 13:16:46 CST → 2026-06-12 13:22:49 CST |
| 📄 论文总数 | **5** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 5 篇新论文，主要分布在 Speech LLM 1, Audio 4。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Endpoint Anticipation for Low-Latency Spoken Dialogue

👤 **作者**: Sathvik Udupa, Shinji Watanabe, Petr Schwarz, Jan Cernocky
🔗 **来源**: [https://arxiv.org/abs/2606.13450v1](https://arxiv.org/abs/2606.13450v1)

**摘要**
> While low-latency interaction is critical for spoken dialogue, cascaded architectures are often bottlenecked by reactive turn-completion detection. We propose Endpoint Anticipation, shifting from reactive detection to proactive forecasting of end-of-turn signals. Our speech-based model anticipates endpoints upto 2.56 seconds in advance, enabling speculative execution of LLM and TTS pipelines on partial context. We introduce metrics to quantify the trade-off between realized latency reduction and computational redundancy. Evaluation across conversational and task-oriented datasets shows our model consistently outperforms competitive VAP-based baselines. Integration with the Unmute framework demonstrates a 505 ms average latency reduction with a 28.4% increase in speculative computation, effectively masking sequential bottlenecks to enable complex reasoning in real-time speech-to-speech interaction.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Endpoint Anticipation for Low-Latency Spoken Dialogue》所界定。 从摘要看，作者主要围绕 spoken dialogue 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluation across conversational and task-oriented datasets shows our model consistently outperforms competitive VAP-based baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：spoken dialogue。 |

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

### 1. A beam--membrane biomechanical vocal fold model incorporating posturing and glottal conformation

👤 **作者**: Mohamed A. Serry, Matías Zañartu, Sean D. Peterson
🔗 **来源**: [https://arxiv.org/abs/2606.13480v1](https://arxiv.org/abs/2606.13480v1)

**摘要**
> The posture of the vocal folds produced by laryngeal muscle activation plays a central role in determining the dynamics of voice production. Abnormal vocal fold configurations are frequently associated with inefficient phonation and a variety of voice disorders. Although diverse glottal closure patterns have been observed clinically, the biomechanical mechanisms governing their dynamic behavior and resulting phonatory characteristics remain incompletely understood. Moreover, existing numerical models that incorporate the effects of the intrinsic musculature on posturing and glottal conformation are computationally expensive, which limits their suitability for large-scale parametric investigations. In this work, we introduce a computationally inexpensive vocal fold (VF) model wherein the body and cover VF layers are treated as a composite beam and a coupled membrane, respectively. Intrinsic laryngeal muscle activation, in addition to positioning the arytenoid cartilages and cricothyroid joint, introduces moments at the boundaries of the structure that influence glottal conformation. The model produces phonatory characteristics that are qualitatively consistent with those reported in high-fidelity finite-element models and clinical studies, thereby supporting its predictive capability while offering substantial computational advantage. The proposed framework provides biomechanical insights into the influence of incomplete glottal closure on phonation dynamics and may serve as a computationally tractable tool for investigating mechanisms underlying certain voice disorders.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《A beam--membrane biomechanical vocal fold model incorporating posturing and glottal conformation》所界定。 从摘要看，作者主要围绕 beam--membrane、biomechanical、vocal 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Abnormal vocal fold configurations are frequently associated with inefficient phonation and a variety of voice disorders. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：beam--membrane, biomechanical, vocal。 |

---
### 2. Adaptive Turn-Taking for Real-time Multi-Party Voice Agents

👤 **作者**: Soumyajit Mitra, Prabhat Pandey, Abhinav Jain, Shanmukha Sahith, K V Vijay Girish
🔗 **来源**: [https://arxiv.org/abs/2606.13544v1](https://arxiv.org/abs/2606.13544v1)

**摘要**
> Turn-taking in multi-party spoken conversations remains a fundamental challenge for voice-based agents, particularly under dynamic floor competition and varying user expectations. We propose ModeratorLM, a role-playing voice agent that conditions turn-taking behavior on an explicitly assigned role in multi-party settings. The system is built on a speech large language model operating in chunk-wise streaming manner. We further introduce a reasoning-augmented variant that incorporates chain-of-thought reasoning over conversational context and the assigned role. We construct RolePlayConv, a large-scale synthetic dataset of spoken multi-party conversations with diverse assistant roles. Experiments on real-world meeting data and RolePlayConv show improved turn-taking precision by over 40% and recall by more than 70%, while substantially reducing false-positive interruptions compared to non-role-conditioned baselines.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Adaptive Turn-Taking for Real-time Multi-Party Voice Agents》所界定。 从摘要看，作者主要围绕 adaptive、turn-taking、real-time 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on real-world meeting data and RolePlayConv show improved turn-taking precision by over 40% and recall by more than 70%, while substantially reducing false-positive interruptions compared to non-role-conditioned baselines. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：adaptive, turn-taking, real-time。 |

---
### 3. Generative Modeling of Bach-Style Symbolic Music: A Comparative Study of Autoregressive, Latent-Variable, and Adversarial Approaches

👤 **作者**: Kyuil Lee, Dezhi Yu, Yongkang Huang
🔗 **来源**: [https://arxiv.org/abs/2606.13626v1](https://arxiv.org/abs/2606.13626v1)

**摘要**
> We study generative modeling of Bach-style symbolic piano music using a shared MIDI corpus and three model families: autoregressive LSTMs with attention, latent-variable models including recurrent VAEs and vector-quantized VAEs, and generative adversarial networks. We compare their ability to model polyphonic note sequences, learn useful latent representations, and generate stylistically coherent compositions. Our experiments show that the autoregressive LSTM with attention produces the most musically coherent samples, while vector quantization helps mitigate posterior collapse and yields more structured outputs than conventional recurrent VAEs. The adversarial approach captures local pitch patterns but remains difficult to train and generalizes less reliably to Bach's style. These results highlight the relative strengths and failure modes of autoregressive, latent-variable, and adversarial approaches for symbolic music generation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Generative Modeling of Bach-Style Symbolic Music: A Comparative Study of Autoregressive, Latent-Variable, and Adversarial Approaches》所界定。 从摘要看，作者主要围绕 generative、modeling、bach-style 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Our experiments show that the autoregressive LSTM with attention produces the most musically coherent samples, while vector quantization helps mitigate posterior collapse and yields more structured outputs than conventional recurrent VAEs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：generative, modeling, bach-style。 |

---
### 4. The Moving Drone: Negotiating Agency Between the Voice and the Virtual

👤 **作者**: Nithya Shikarpur, Victor Arul, Anna Huang
🔗 **来源**: [https://arxiv.org/abs/2606.13640v1](https://arxiv.org/abs/2606.13640v1)

**摘要**
> Melodic material in Hindustani music is presented in relation to a tonic, usually sustained by the tanpura, a four-stringed drone instrument. Rooted in Hindustani music, 'The Moving Drone' sets the traditionally static drone into motion that, throughout the performance, gains increasing agency transitioning from reactive to more proactive roles. The work employs four independent loopers in Max/MSP to function as 'virtual' drones. They are populated cyclically in real-time as the vocalist improvises, creating an organic and evolving feedback loop between the voice and the virtual drone. This relationship further evolves melodically by pitch shifting the loops, which introduces a dimension of sudden, explicit movement. Then it changes timbrally, via the integration of GaMaDHaNi, a singer conditioned pitch-to-voice generative AI model to resynthesize looped audio. While current music AI approaches prioritize high-fidelity and realism of generated content which has sparked anxiety over job replacement for the music community, this work intentionally utilizes low-fidelity generative outputs, further necessitating human interpretation and situational context in order to be complete. 'The Moving Drone' positions technology and generative AI within established socio-cultural musical practices, proposing a virtual drone as an active, responsive, and co-creative musical agent.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《The Moving Drone: Negotiating Agency Between the Voice and the Virtual》所界定。 从摘要看，作者主要围绕 moving、drone、negotiating 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：They are populated cyclically in real-time as the vocalist improvises, creating an organic and evolving feedback loop between the voice and the virtual drone. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：moving, drone, negotiating。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
