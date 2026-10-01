<div align="center">

# 📰 Paper Claw

**2026-10-01**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-09-30 14:03:50 CST → 2026-10-01 14:37:47 CST |
| 📄 论文总数 | **4** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 4 篇

> 💡 今日共收录 4 篇新论文，主要分布在 Audio 4。
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

### 1. SEAR: Spoofing Evidence-Grounded Audio Reasoning Benchmark for Audio Language Models

👤 **作者**: Rong Wan, Suliu Qin, Jiaxi Li, Wei Xie, Wenwu Wang, Xiaolong Han, Lu Yin, Xilu Wang
🔗 **来源**: [https://arxiv.org/abs/2609.39847v1](https://arxiv.org/abs/2609.39847v1)

**摘要**
> Audio language models (ALMs) are increasingly used for audio deepfake detection (ADD), yet existing benchmarks assess their verdicts or rationale plausibility without verifying the underlying acoustic evidence. To address this issue, we first introduce spoofing evidence-grounded audio reasoning (SEAR), a four-task AQA benchmark to evaluate ALM-based ADD through acoustic evidence identification and quantification, deepfake detection, and forensic rationale generation. We further propose a bona-fide-based acoustic evidence agent (BAEA), which equips a frozen ALM with controlled acoustic tools under \textsc{fixed} or \textsc{adaptive} evidence-acquisition policies. Experiments with six ALMs reveal a clear gap between plausible rationales and verifiable acoustic evidence reasoning, while BAEA-\textsc{Fixed} improves final verdicts and forensic rationales on both evaluation partitions. Controlled interventions further show that misleading evidence degrades both detection and grounding performance.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SEAR: Spoofing Evidence-Grounded Audio Reasoning Benchmark for Audio Language Models》所界定。 从摘要看，作者主要围绕 sear、spoofing、evidence-grounded 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments with six ALMs reveal a clear gap between plausible rationales and verifiable acoustic evidence reasoning, while BAEA-\textsc{Fixed} improves final verdicts and forensic rationales on both evaluation partitions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：sear, spoofing, evidence-grounded。 |

---
### 2. Pitch Smoothing Using Relative Interval Networks

👤 **作者**: Chin-Yun Yu, Chi-Jen Peng, Li Su, György Fazekas
🔗 **来源**: [https://arxiv.org/abs/2609.39852v1](https://arxiv.org/abs/2609.39852v1)

**摘要**
> Pitch tracking systems typically couple a per-frame fundamental frequency ($F_0$) estimator with a temporal smoothing stage to obtain continuous trajectories. Conventional Viterbi smoothers enforce first-order continuity but lack long-term temporal awareness and could lock into octave errors across corrupted frames. We propose Relative Interval Networks (RIN), a trajectory smoothing framework that reconciles per-frame pitch estimates with data-driven multi-hop pitch differences. We extract robust relative pitch intervals across arbitrary frame offsets using Variable-Q Transform cross-correlation. We formulate pitch smoothing as an $L_1$-norm optimization problem and prove its equivalence to a minimum cost circulation problem, solved efficiently via linear programming. Evaluations across speech, singing, and instrumental datasets show that RIN substantially improves weak estimators, matches or outperforms Viterbi decoding at a comparable computational cost, and provides superior robustness under certain acoustic degradation.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Pitch Smoothing Using Relative Interval Networks》所界定。 从摘要看，作者主要围绕 pitch、smoothing、using 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Evaluations across speech, singing, and instrumental datasets show that RIN substantially improves weak estimators, matches or outperforms Viterbi decoding at a comparable computational cost, and provides superior robustness under certain acoustic degradation. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：pitch, smoothing, using。 |

---
### 3. MeanVoiceFlow2: Joint Optimization of Mean Flow and Content Encoder for Fast One-Step Zero-Shot Voice Conversion

👤 **作者**: Takuhiro Kaneko, Hirokazu Kameoka, Kou Tanaka, Yuto Kondo
🔗 **来源**: [https://arxiv.org/abs/2609.40087v1](https://arxiv.org/abs/2609.40087v1)

**摘要**
> Flow-matching approaches to voice conversion (VC) have gained attention owing to their high speech quality and strong speaker similarity. Among them, one-step models such as MeanVoiceFlow are particularly attractive because they enable efficient inference; however, their reliance on a computationally intensive content encoder remains a bottleneck. We therefore propose MeanVoiceFlow2, a framework that jointly optimizes a flow-based conversion module and a computationally efficient content encoder. The model is trained through conversion distillation using MeanVoiceFlow and the reconstruction of real data. We further incorporate diffusion-GAN training with sample mixing and teacher-guided conditioning augmentation to enhance realism and disentanglement. Experiments on zero-shot VC showed that MeanVoiceFlow2 achieved higher perceptual quality and approximately $9\times$ faster inference than MeanVoiceFlow while maintaining comparable speaker similarity. Audio samples are available at https://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/meanvoiceflow2/.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MeanVoiceFlow2: Joint Optimization of Mean Flow and Content Encoder for Fast One-Step Zero-Shot Voice Conversion》所界定。 从摘要看，作者主要围绕 meanvoiceflow、joint、optimization 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on zero-shot VC showed that MeanVoiceFlow2 achieved higher perceptual quality and approximately $9\times$ faster inference than MeanVoiceFlow while maintaining comparable speaker similarity. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：meanvoiceflow, joint, optimization。 |

---
### 4. SCB: SpeechConversationBench for Evaluating Multi-Turn Reasoning in Speech-to-Speech Models

👤 **作者**: Kanpat Vesessook, Saksorn Ruangtanusak
🔗 **来源**: [https://arxiv.org/abs/2609.40198v1](https://arxiv.org/abs/2609.40198v1)

**摘要**
> Speech-to-speech systems must solve tasks whose requirements emerge across conversational turns. We introduce SpeechConversationBench (SCB), a focused evaluation of spoken mathematical reasoning using 103 sharded GSM8K problems. The framework compares the original problem delivered in one turn (full), its concatenated information shards delivered together (concat), and incremental spoken disclosure across turns (sharded). We report final-answer accuracy for four commercial speech systems and LEGO, a proprietary speech pipeline developed internally by the SCBX Innovation Lab team with explicit conversational context management. Relative to concat, sharded accuracy decreases by 5.0-25.3 percentage points across the four commercial systems. LEGO achieves 77.5 percent accuracy in all three conditions, compared with 76.6 percent sharded accuracy for GPT-4o Realtime. The two single-turn baselines distinguish sensitivity to problem reformulation from the additional challenges introduced by incremental spoken interaction.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《SCB: SpeechConversationBench for Evaluating Multi-Turn Reasoning in Speech-to-Speech Models》所界定。 从摘要看，作者主要围绕 speechconversationbench、evaluating、multi-turn 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：LEGO achieves 77.5 percent accuracy in all three conditions, compared with 76.6 percent sharded accuracy for GPT-4o Realtime. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speechconversationbench, evaluating, multi-turn。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
