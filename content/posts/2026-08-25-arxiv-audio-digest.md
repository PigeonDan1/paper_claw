<div align="center">

# 📰 Paper Claw

**2026-08-25**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-24 10:13:41 CST → 2026-08-25 10:09:40 CST |
| 📄 论文总数 | **2** 篇 |

### 分类统计

- **Speech LLM**: 1 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 1 篇

> 💡 今日共收录 2 篇新论文，主要分布在 Speech LLM 1, Audio 1。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Reasoning-Oriented Post-Training and Inference-Time LoRA Rescaling for Audio-Dependent Question Answering

👤 **作者**: Weiteng Hu, Yin Cao, Jun Yang
🔗 **来源**: [https://arxiv.org/abs/2608.23092v1](https://arxiv.org/abs/2608.23092v1)

**摘要**
> Audio-Dependent Question Answering (ADQA) requires Large Audio-Language Models (LALMs) to answer questions whose correct answers depend on the given audio content. Successful ADQA requires accurate audio perception, identification of question-relevant evidence, and cross-modal reasoning. Using the official ADQA dataset of DCASE 2026 Task 5, we investigate reasoning-oriented post-training with Low-Rank Adaptation (LoRA) and inference-time LoRA rescaling for both Qwen2.5-Omni and MOSS-Audio-8B-Thinking. We introduce a structured Chain-of-Thought (CoT) framework that decomposes the reasoning process into question analysis, question type, audio evidence, and reasoning. We then analyze how task-specific LoRA adaptation affects the two backbones and further explore inference-time rescaling of trained LoRA adapters. Experiments on the development set reveal markedly backbone-dependent behavior: post-training improves the Qwen-based systems but substantially degrades MOSS-Audio under our supervised fine-tuning configuration. Moderate LoRA rescaling further improves the best Qwen system's top-1 accuracy from 58.93% to 61.05% and partially restores the performance of the fine-tuned MOSS-Audio models, while the best MOSS-Audio system achieves 67.70% top-1 accuracy. Our submitted systems ranked third overall and second among lightweight systems under 10B parameters in the challenge.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Reasoning-Oriented Post-Training and Inference-Time LoRA Rescaling for Audio-Dependent Question Answering》所界定。 从摘要看，作者主要围绕 audio-language model 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments on the development set reveal markedly backbone-dependent behavior: post-training improves the Qwen-based systems but substantially degrades MOSS-Audio under our supervised fine-tuning configuration. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio-language model。 |

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

### 1. AT-ADD: A Benchmark and Challenge for Robust and All-Type Audio Deepfake Detection

👤 **作者**: Yuankun Xie, Haonan Cheng, Jiayi Zhou, Xiaoxuan Guo, Tao Wang, Changhao Zhang, Jian Liu, Weiqiang Wang, Ruibo Fu, Xiaopeng Wang, Hengyan Huang, Xiaoying Huang, Long Ye, Guangtao Zhai
🔗 **来源**: [https://arxiv.org/abs/2608.23437v1](https://arxiv.org/abs/2608.23437v1)

**摘要**
> Recent audio generation models can synthesize high-fidelity speech, environmental sound, singing voice, and music, creating new risks for multimedia trust. Existing audio deepfake detection (ADD) benchmarks remain predominantly speech-centric and often underrepresent realistic channel variation and diverse audio types. This paper presents AT-ADD, a large-scale benchmark and challenge designed to evaluate both robust speech deepfake detection and all-type audio deepfake detection. Track 1 evaluates binary speech detection under unseen generators, diverse recording conditions, signal perturbations, and replay effects. Track 2 evaluates type-agnostic real/fake detection over speech, sound, singing, and music when the audio type is unknown at test time. We detail the dataset construction, evaluation protocol, and reproducible baselines, and analyze the final systems submitted to the ACM Multimedia 2026 Grand Challenge. The strongest official baseline obtains 76.73% and 79.47% Macro-F1 on the Track 1 and Track 2 evaluation sets, respectively, whereas the winning challenge systems reach 90.71% and 96.10%. Beyond aggregate rankings, sample-level analysis of the top five submissions examines generator- and type-level difficulty, cross-system error complementarity, and ranking stability. The results show that large-scale self-supervised representations, condition-aware augmentation, multi-crop inference, and structured fusion or routing are central to generalization, while generator-specific robustness and consistent performance across diverse audio types remain unresolved.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《AT-ADD: A Benchmark and Challenge for Robust and All-Type Audio Deepfake Detection》所界定。 从摘要看，作者主要围绕 audio generation 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The results show that large-scale self-supervised representations, condition-aware augmentation, multi-crop inference, and structured fusion or routing are central to generalization, while generator-specific robustness and consistent performance across diverse audio types remain unresolved. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：audio generation。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
