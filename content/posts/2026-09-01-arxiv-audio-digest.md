<div align="center">

# 📰 Paper Claw

**2026-09-01**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-08-31 14:18:36 CST → 2026-09-01 13:46:49 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 2 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 5 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Speech LLM 2, Audio 5。
> 📈 整体上以方法改进、跨模态建模和系统化评测为主，适合按分类快速筛选当天值得细读的论文。

---

## 🏷️ Speech LLM

### 1. Stride-k Subsampling: Train-Free Audio Token Reduction for Whisper

👤 **作者**: Chanhee Cho, Junhyuk Choi, Bugeun Kim
🔗 **来源**: [https://arxiv.org/abs/2608.30927v1](https://arxiv.org/abs/2608.30927v1)

**摘要**
> Whisper exposes speech through a fixed 1500-token encoder interface, now a default representation for ASR decoders and Whisper-based speech language models (SpeechLMs), yet its redundancy remains largely unexamined. We propose stride-k subsampling, a deterministic indexing operation that retains every k-th token after the convolutional stem or encoder transformer. Across five Whisper scales, k=2 preserves baseline WER at both positions, with CKA attributing this stability to acoustic overlap at the stem and attention-induced redistribution at the encoder output. Applying stride-2 at both positions cuts audio tokens by 75% and total GFLOPs by 52-58%, with small WER costs on most ASR benchmarks and larger costs on harder ones. The same configuration extends to three Whisper-based SpeechLMs, yielding modest accuracy drops on stronger baselines and larger drops on weaker ones, while reducing end-to-end latency by 19.6-27.4%. Requiring no training or auxiliary computation, stride-k subsampling exploits Whisper's preprocessing redundancy, indicating that its audio-token interface carries more capacity than downstream tasks require.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《Stride-k Subsampling: Train-Free Audio Token Reduction for Whisper》所界定。 从摘要看，作者主要围绕 speech language model、whisper 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We propose stride-k subsampling, a deterministic indexing operation that retains every k-th token after the convolutional stem or encoder transformer. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：speech language model, whisper。 |

---
### 2. When Does Predictor-Based RL Align with Human Perception? A Study of Subjective Rewards in Codec-Based Speech Language Models

👤 **作者**: Joonyong Park, Jerry Li
🔗 **来源**: [https://arxiv.org/abs/2608.31035v1](https://arxiv.org/abs/2608.31035v1)

**摘要**
> Codec-based text-to-speech (TTS) models make language-model post-training applicable to speech generation, but it remains unclear when learned perceptual predictors can serve as reinforcement learning rewards without losing alignment with human listeners. We study this question with Group Relative Policy Optimization (GRPO) using learned rewards for anime-like speaking style, naturalness, likability, and arousal. To prevent perceptual rewards from being optimized through transcript drift, we introduce a character error rate (CER) zone constraint and compare policy optimization with Best-of-$N$ reranking under the same reward gate. Across single-reward runs, each reward primarily improves its own target metric, showing that subjective predictors are not interchangeable quality surrogates. Multi-rater A/B tests further show uneven human transfer, while a reward-gap analysis separates average transfer from within-axis calibration: signed reward gaps significantly predict listener choices in the pooled analysis, whereas residual CER gaps do not, but per-axis calibration remains heterogeneous. Best-of-8 is a strong human-level baseline and is not clearly worse than GRPO perceptually, suggesting that GRPO should be viewed as amortizing reward-selected behavior into the policy rather than uniformly outperforming reranking. These results support analyzing subjective speech rewards as predictor-axis-base tuples and provide practical diagnostics for selecting rewards before multi-reward speech post-training.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「语音大模型」方向，核心任务由题目《When Does Predictor-Based RL Align with Human Perception? A Study of Subjective Rewards in Codec-Based Speech Language Models》所界定。 从摘要看，作者主要围绕 speech language model、text-to-speech 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Across single-reward runs, each reward primarily improves its own target metric, showing that subjective predictors are not interchangeable quality surrogates. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：speech language model, text-to-speech。 |

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

### 1. Decoupled Latent Flow Matching for Few-Step Joint Vocal-Accompaniment Separation

👤 **作者**: Lishi Zuo, Youzhi Tu, Lu Yi, Zezhong Jin, Chongxin Gan, Man-Wai Mak, KongAik Lee
🔗 **来源**: [https://arxiv.org/abs/2608.30913v1](https://arxiv.org/abs/2608.30913v1)

**摘要**
> Generative modeling provides a flexible way to model mixture-conditioned source distributions, but iterative diffusion and flow matching models are costly for long music signals. This paper studies joint vocal-accompaniment separation through latent flow matching, where a pretrained variational autoencoder (VAE) maps mixtures and sources into a compact latent space and a flow matching model generates vocal and accompaniment latents jointly. The proposed framework decouples semantic separation from acoustic velocity prediction through a Separation Encoder and a Velocity Decoder. To reduce sampling cost, we further apply latent adversarial post-training inspired by Flow2GAN for few-step generation. Experiments show that latent adversarial refinement can improve perceptual and separation metrics under a reduced sampling budget.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Decoupled Latent Flow Matching for Few-Step Joint Vocal-Accompaniment Separation》所界定。 从摘要看，作者主要围绕 decoupled、latent、flow 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Experiments show that latent adversarial refinement can improve perceptual and separation metrics under a reduced sampling budget. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性高。摘要结构较直白，问题、方法和结果都比较容易定位。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：decoupled, latent, flow。 |

---
### 2. MusGU+: Toward a Musician-Centered Evaluation Framework and Discovery Tool for Generative Music AI

👤 **作者**: Laura Ibáñez-Martínez, Roser Batlle-Roca, Xavier Serra, Martín Rocamora
🔗 **来源**: [https://arxiv.org/abs/2608.30940v1](https://arxiv.org/abs/2608.30940v1)

**摘要**
> Generative music systems are increasingly presented as tools that democratize music creation, yet their practical suitability for musicians remains underexplored. Prior work includes openness-focused evaluation frameworks, such as MusGO (Music-Generative Open AI), as well as qualitative studies of musicians' experiences with generative systems. However, these approaches do not support systematic comparison or early-stage discovery of models for creative use. Motivated by such limitations, we introduce MusGU+, a musician-centered evaluation framework organized around three dimensions: Adaptability, Usability, and Controllability. Together, these capture whether a model can be feasibly trained or fine-tuned on personal data, integrated into real-world music workflows, and controlled in musically meaningful ways. We evaluate 10 representative generative music systems and present an interactive discovery tool that enables musicians to explore and filter models according to these criteria. While MusGO remains valuable for promoting responsible research practices, MusGU+ supports informed selection and practical adoption of generative systems by musicians.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MusGU+: Toward a Musician-Centered Evaluation Framework and Discovery Tool for Generative Music AI》所界定。 从摘要看，作者主要围绕 musgu、toward、musician-centered 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Prior work includes openness-focused evaluation frameworks, such as MusGO (Music-Generative Open AI), as well as qualitative studies of musicians' experiences with generative systems. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：musgu, toward, musician-centered。 |

---
### 3. CoJEPA: Combining Contrastive Learning and JEPA for Global-Local Music Representations

👤 **作者**: Gabriel Meseguer-Brocal, Yuexuan Kong, Romain Hennequin
🔗 **来源**: [https://arxiv.org/abs/2608.30974v1](https://arxiv.org/abs/2608.30974v1)

**摘要**
> Joint-Embedding Predictive Architecture (JEPA) has shown strong performance in learning rich representations through self-supervised prediction in latent space. However, it typically relies on teacher--student architecture with an EMA to stabilise training, and can tend to yield uninformative representations. Contrastive learning is stable to train and produces strong global representations, but remains limited on local tasks by the global nature of its objective. In this work, we combine both into CoJEPA: a single shared backbone jointly trained with a JEPA objective on masked sequence tokens and a contrastive objective on the class token. The contrastive gradient provides stability, removing the need for an EMA teacher entirely, while JEPA enriches the sequence tokens via local predictions that contrastive learning alone cannot provide. Crucially, no extra parameters are added to the backbone: the same model is guided towards richer representations purely through the design of its training signal. CoJEPA takes the best of both worlds, outperforming or matching both individual methods across global and local MIR tasks, with a particularly strong advantage on tonal and harmonic understanding, and without any task-specific architectural changes. CoJEPA shows that combining objectives with complementary inductive biases can substitute for scale, encouraging future work to invest in smarter training objectives over ever-larger models.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《CoJEPA: Combining Contrastive Learning and JEPA for Global-Local Music Representations》所界定。 从摘要看，作者主要围绕 cojepa、combining、contrastive 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Joint-Embedding Predictive Architecture (JEPA) has shown strong performance in learning rich representations through self-supervised prediction in latent space. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：cojepa, combining, contrastive。 |

---
### 4. Language-Statistical Analysis of Neural Audio Codec Tokens Across Architectures, Corpora, and Noise Conditions

👤 **作者**: Joonyong Park, Shinnosuke Takamichi, David M. Chan, Shunsuke Kando, Yuki Saito, Hiroshi Saruwatari
🔗 **来源**: [https://arxiv.org/abs/2608.31037v1](https://arxiv.org/abs/2608.31037v1)

**摘要**
> Neural audio codecs (NACs) convert speech into discrete token sequences, and prior work has reported that these sequences follow language-like statistical laws. This paper analyzes the token statistics of 13 NACs spanning multi-codebook residual vector quantization (RVQ), single-codebook VQ, and non-VQ designs, evaluated on three corpora under clean, white-noise, and real-world DEMAND-noise conditions. Zipf and Heaps parameters, unigram entropy, codebook occupancy, and Jensen-Shannon divergence (JSD) are estimated from matched token samples with explicit fit-validity safeguards and family-conditional $n$-gram orders. Corpus identity explains little variance in any metric, whereas acoustic condition and quantizer meta-category dominate in a metric-dependent way, and unigram entropy is the metric most strongly associated with meta-category. Clean-to-noise JSD computed at a common unigram order is associated with mel-cepstral distortion most clearly under DEMAND noise. The collapse and explosion degradation signatures previously reported for RVQ codecs concentrate in RVQ cells under white and DEMAND noise, respectively; explosion also occurs in non-VQ codecs, and single-codebook VQ codecs shift in occupancy and distribution shape without either signature. These results provide architecture-conditioned conventions for applying language-statistical analysis to NAC tokens.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Language-Statistical Analysis of Neural Audio Codec Tokens Across Architectures, Corpora, and Noise Conditions》所界定。 从摘要看，作者主要围绕 language-statistical、analysis、neural 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This paper analyzes the token statistics of 13 NACs spanning multi-codebook residual vector quantization (RVQ), single-codebook VQ, and non-VQ designs, evaluated on three corpora under clean, white-noise, and real-world DEMAND-noise conditions. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：language-statistical, analysis, neural。 |

---
### 5. DreamX-Creator: Democratizing Native Audio-Video Generation at 2K Resolution

👤 **作者**: Jiashu Zhu, Yanhao Zheng, Ruitian Tian, Rujing Dang, Shen Zhang, Bingze Song, Jiachen Lei, Ruimin Lin, Jiahong Wu, Xiangxiang Chu
🔗 **来源**: [https://arxiv.org/abs/2608.31106v1](https://arxiv.org/abs/2608.31106v1)

**摘要**
> Recent video generators often omit audio or synthesize it in a separate stage, limiting reciprocal modeling of visual dynamics and acoustic events. We present DreamX-Creator 1.0, a compact native joint audio-video generation system centered on a 7B generator. Conditioned on a first frame and a text prompt, the generator jointly denoises modality-specialized audio and video streams. The streams are processed independently in the first half of the network and coupled in the latter half through Gated Cross-Modal Attention, whose token- and head-wise output gates modulate each active cross-modal attention-head output. A unified Audio-Video Data System constructs and filters temporally coherent clips, produces structured multimodal annotations, and organizes clips into capability-oriented data pools. Progressive Joint Training comprises two audio-video pre-training stages followed by High-Quality Finetuning. Audio-Video Reinforcement Learning further post-trains the generator with Modality-Aware Multimodal Feedback that routes video-, audio-, and cross-modal feedback to the corresponding streams. For high-resolution output, our Autoregressive 1-Step 2K Refinement pipeline adapts a bidirectional multi-step teacher into an autoregressive multi-step refiner and distills it into a student requiring one denoising evaluation per temporal chunk. Overall, DreamX-Creator 1.0 achieves native, synchronized audio-video generation with performance competitive with state-of-the-art open-source systems. By releasing our compact 7B generator and 2K Refiner, we seek to democratize native audio-video generation and provide an accessible foundation for future research in unified audio-video generative modeling.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《DreamX-Creator: Democratizing Native Audio-Video Generation at 2K Resolution》所界定。 从摘要看，作者主要围绕 dreamx-creator、democratizing、native 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Overall, DreamX-Creator 1.0 achieves native, synchronized audio-video generation with performance competitive with state-of-the-art open-source systems. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：dreamx-creator, democratizing, native。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
