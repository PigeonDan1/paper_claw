<div align="center">

# 📰 Paper Claw

**2026-10-15**

</div>

---

## 📊 今日速览

| 指标 | 数值 |
|:---|:---|
| ⏰ 时间窗口 | 2026-10-14 13:32:15 CST → 2026-10-15 13:20:35 CST |
| 📄 论文总数 | **7** 篇 |

### 分类统计

- **Speech LLM**: 0 篇
- **ASR**: 0 篇
- **TTS**: 0 篇
- **Enhancement**: 0 篇
- **SLU**: 0 篇
- **Paralinguistics**: 0 篇
- **Audio**: 7 篇

> 💡 今日共收录 7 篇新论文，主要分布在 Audio 7。
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

### 1. Evaluating perceptual transparency of lossy music audio compression with Opus codec

👤 **作者**: Benjamin Martin, Romain Hennequin
🔗 **来源**: [https://arxiv.org/abs/2610.20246v1](https://arxiv.org/abs/2610.20246v1)

**摘要**
> Although the open-source Opus audio codec is widely used for digital audio streaming, its perceptual transparency threshold for high-bitrate music compression remains insufficiently evaluated. To establish this threshold, this study evaluates Opus across a two-phase ITU-R BS.1116-3 double-blind framework, analyzing Difference Grades using a Linear Mixed-Effects Model (LMM) and Two One-Sided Tests (TOST) for statistical equivalence. In a first phase with 21 qualified listeners and 23 music excerpts, 128 kbps achieves statistical in-distinguishability ($p = 0.456$) but narrowly fails strict equivalence to the uncompressed reference ($p = 0.064$). In Phase 2, Best Linear Unbiased Predictors (BLUPs) isolate the 10 most critical listeners and 8 most challenging samples for a stress-test. Under these worst-case conditions, 128 kbps is conclusively detected as degraded ($p = 0.030$), whereas 160 kbps successfully reaches perceptual transparency ($p = 0.747$) and strict statistical equivalence ($p = 0.024$). The study concludes that 160 kbps demonstrates perceptual transparency to uncompressed CD quality in critical listening environments. For reproducibility, we publicly release results for both phases, anonymized subject background info and sample characteristics.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Evaluating perceptual transparency of lossy music audio compression with Opus codec》所界定。 从摘要看，作者主要围绕 evaluating、perceptual、transparency 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：In a first phase with 21 qualified listeners and 23 music excerpts, 128 kbps achieves statistical in-distinguishability ($p = 0.456$) but narrowly fails strict equivalence to the uncompressed reference ($p = 0.064$). 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：evaluating, perceptual, transparency。 |

---
### 2. Repairing Speech Access After Text Updates with Frozen Affine Fields

👤 **作者**: Ming-Hao Hsu, Yuxiang Wang, Yingda Shen, Zhizheng Wu
🔗 **来源**: [https://arxiv.org/abs/2610.20253v1](https://arxiv.org/abs/2610.20253v1)

**摘要**
> Speech-capable language models inherit most of their knowledge from text-rich language backbones, and continued model maintenance is likewise dominated by text updates. Knowledge acquired through a text update can nevertheless remain difficult to access when the same query is spoken. We formulate this mismatch as post-update speech access repair, where the knowledge-bearing checkpoint stays frozen and a detachable operator repairs speech-only access in one model pass. We introduce Affine Fields for Interface Repair across Modalities (AFFIRM), which first learns and freezes a base correction for speech hidden states, then adds query-specific corrections with zero mean over the operator-training queries. Paired speech and text states provide the coordinates that condition these corrections on each query. On balanced synthetic-speech PopQA, paired comparisons do not establish a clear advantage for AFFIRM over global SALSA steering or low-rank ReFT interventions under the same frozen single-state constraint. On recorded SLUE-SQA-5 questions with text passages, a full-scale PopQA-fitted AFFIRM operator transfers without refitting and improves ROUGE-L by 0.0941 over its paired No Repair baseline. Low-rank ReFT interventions also transfer positively, whereas the matched SALSA variant falls 0.0707 below its paired baseline. These results show that text acquisition and speech access can diverge after an update and should be verified and repaired separately.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Repairing Speech Access After Text Updates with Frozen Affine Fields》所界定。 从摘要看，作者主要围绕 repairing、speech、access 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：On recorded SLUE-SQA-5 questions with text passages, a full-scale PopQA-fitted AFFIRM operator transfers without refitting and improves ROUGE-L by 0.0941 over its paired No Repair baseline. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：repairing, speech, access。 |

---
### 3. MUSEBENCH: A Benchmark for AI-Generated Music Detection and Artifact Analysis

👤 **作者**: Yi Chen Liu, Syed Irfan Ali Meerza, Jiawei Yu, Xi Guo, Samuel Bright, Jian Liu
🔗 **来源**: [https://arxiv.org/abs/2610.20310v1](https://arxiv.org/abs/2610.20310v1)

**摘要**
> Advances in generative AI have made it possible to produce music that is nearly indistinguishable from human compositions, raising the question of whether such works can be reliably distinguished from human compositions. We present MUSEBENCH, a large-scale benchmark for AI-generated music detection and artifact analysis, comprising over 361K tracks. The dataset includes human compositions, stylistically matched music generated by ten state-of-the-art open-source and commercial models, such as Suno and Udio, as well as human-AI co-creations and variants processed with adversarial perturbations, compression, and acoustic post-processing. Using MUSEBENCH, we benchmark 11 automated detectors and evaluate their accuracy, generalization, and robustness, under default, out-of-domain, and transformed-variant experiment settings. We further conduct a comprehensive artifact analysis through acoustic feature inspection, identifying recurring signatures such as non-idiomatic harmonic progressions, upsampling induced spectral periodicities, and violations of physical performance constraints. Our findings reveal key strengths and vulnerabilities of existing detectors and provide practical insights for building more reliable AI music detection systems.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《MUSEBENCH: A Benchmark for AI-Generated Music Detection and Artifact Analysis》所界定。 从摘要看，作者主要围绕 musebench、benchmark、ai-generated 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：The dataset includes human compositions, stylistically matched music generated by ten state-of-the-art open-source and commercial models, such as Suno and Udio, as well as human-AI co-creations and variants processed with adversarial perturbations, compression, and acoustic post-processing. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：musebench, benchmark, ai-generated。 |

---
### 4. Continued fractions and passive ladder networks for acoustic impedances: the baffled piston and the horn

👤 **作者**: Ronald M. Aarts
🔗 **来源**: [https://arxiv.org/abs/2610.20371v1](https://arxiv.org/abs/2610.20371v1)

**摘要**
> Lumped-element networks give transparent, passive models of acoustic impedances whose low- and high-frequency limits can be read from the circuit, but a systematic, arbitrarily accurate construction for non-rational impedances is lacking. Continued fractions, one- and two-point Padé approximants and their identity with ladder networks and Cauer synthesis are introduced in tutorial form and applied to two examples: the radiation impedance of a baffled circular piston and the throat impedance of a horn with a piston mouth. The even contraction of the piston's continued fraction has positive coefficients, certified by interval arithmetic for the first 100 pairs, and yields a ladder of positive resistances, masses and compliances; with 14 elements the error is 4e-4 up to ka = 5. Beranek's four-element network is, to about 2%, the order-two two-point Padé approximant. A horn modelled as a cascade of waveguide sections is a continued fraction whose tail is the mouth impedance; the infinite exponential horn is a periodic continued fraction, an exact high-pass ladder. The piston networks are passive at every certified order (up to 202 elements) and are extended without changing existing elements; for a finite horn the error of the mouth network passes one to one to the throat impedance.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Continued fractions and passive ladder networks for acoustic impedances: the baffled piston and the horn》所界定。 从摘要看，作者主要围绕 continued、fractions、passive 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：Continued fractions, one- and two-point Padé approximants and their identity with ladder networks and Cauer synthesis are introduced in tutorial form and applied to two examples: the radiation impedance of a baffled circular piston and the throat impedance of a horn with a piston mouth. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：continued, fractions, passive。 |

---
### 5. HRTF Upsampling and Personalization via Neural Operators

👤 **作者**: Meenakshi Krishnan, You Zhang, Ramani Duraiswami, C. Phillip Brown
🔗 **来源**: [https://arxiv.org/abs/2610.20400v1](https://arxiv.org/abs/2610.20400v1)

**摘要**
> Head-related transfer function (HRTF) spatial upsampling from sparse measurements is a fundamental challenge in personalized binaural audio. We formulate HRTF upsampling as an operator learning problem and introduce SPARO, a neural operator that maps sparse measurements at a set of spatial directions to the HRTF field, a continuous representation that can be queried at arbitrary positions. SPARO projects the measurements onto a learned set of spherical latent modes, processes the latent modes with Transformer blocks, and decodes the resulting representations at query directions. On SONICOM, using the LAP24 measurement configuration, SPARO attains the best log-spectral distortion (LSD) and interaural level difference (ILD) error at every sparsity level from 3 to 100 measurements (18% lower LSD and 43% lower ILD error than the strongest baseline at 100 measurements) while remaining competitive in interaural time difference (ITD) error. It reconstructs a dense HRTF 15 to 373 times faster than the leading neural-field method RANF. We further validate the approach on HUTUBS, demonstrating its effectiveness across HRTF datasets.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《HRTF Upsampling and Personalization via Neural Operators》所界定。 从摘要看，作者主要围绕 hrtf、upsampling、personalization 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：We further validate the approach on HUTUBS, demonstrating its effectiveness across HRTF datasets. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性偏低。缩写、设定或实验细节较多，首次浏览成本偏高。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：hrtf, upsampling, personalization。 |

---
### 6. vst-bench-ml: Auditable Dataset Generation for Audio Plugins

👤 **作者**: Youssef Hemimy
🔗 **来源**: [https://arxiv.org/abs/2610.20465v1](https://arxiv.org/abs/2610.20465v1)

**摘要**
> Generating datasets with audio plugins requires preserving how each audio observation was produced. vst-bench-ml is a Python package that samples plugin parameters, coordinates rendering through a separately installed host, and records software identities, rendering settings, and output hashes for later verification. A sealed manifest binds this evidence and supports offline integrity checks without loading the plugin. A companion repository provides a sample-free VST3 test plugin, a deterministic offline host, and additional checks linking rendering attempts to recorded outputs. On a pinned macOS arm64 and Python 3.12 stack, functional validation of the pre-release versions reproduced package and host tests. Two runs in fresh processes reproduced the same render-plan hash and all eight expected output hashes, covering four sampled parameter configurations and two fixed MIDI signals; 12 negative cases also passed. Later licensed 0.1.0 release candidates passed producer-run continuous integration and local validation. Version 0.1.1 adds public Git source repositories, package-index installation, and user documentation; a separate release check reproduced the expected plan and output hashes. These checks establish integrity and repeatability within the tested setup; they do not establish portability, scientific suitability, or perceptual quality.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《vst-bench-ml: Auditable Dataset Generation for Audio Plugins》所界定。 从摘要看，作者主要围绕 vst-bench-ml、auditable、dataset 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：vst-bench-ml is a Python package that samples plugin parameters, coordinates rendering through a separately installed host, and records software identities, rendering settings, and output hashes for later verification. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要更偏方法描述，建议点开原文确认实验细节。 优先看这些信号词：vst-bench-ml, auditable, dataset。 |

---
### 7. Quantizer Redundancy and Exact Index Recoding in a Frozen Neural Audio Codec

👤 **作者**: Youssef Hemimy
🔗 **来源**: [https://arxiv.org/abs/2610.20471v1](https://arxiv.org/abs/2610.20471v1)

**摘要**
> Residual scalar quantization can produce highly dependent indices when successive stages reuse identical, unscaled grids. This case study examines that behavior in a frozen neural audio codec and develops an exact recoding procedure that reduces storage while preserving its decoder inputs. Analysis of the repeated-grid recurrence identifies predictable stage sequences; finite-precision checks motivate preserving every original index through explicit exception records. The model weights and reconstruction graph remain fixed. On the studied 62- and 512-file cohorts, a predictor, adaptive coding and explicit file selection reduce complete stored bytes. The final 512-file rate is 129.591 kbps including headers, 25.943% below an original-index XZ control. Original recorded CPU runs establish bitwise latent and waveform preservation; independent readers verify exact index and metadata recovery in subsequent saved-stream experiments. Later coding choices use previously studied cohorts, and fresh encoding requires generating three alternatives. The engineering result is implementation-specific storage reduction with exact index recovery; the underlying lossy reconstruction quality remains unchanged.

**综合评价**
| 项目 | 内容 |
|:---|:---|
| 📝 总结 | 这篇工作归入「通用音频」方向，核心任务由题目《Quantizer Redundancy and Exact Index Recoding in a Frozen Neural Audio Codec》所界定。 从摘要看，作者主要围绕 quantizer、redundancy、exact 展开方法设计、训练策略或系统建模。 结果部分最值得注意的是：This case study examines that behavior in a frozen neural audio codec and develops an exact recoding procedure that reduces storage while preserving its decoder inputs. 如果你想快速判断这篇论文是否值得细读，这份摘要已经能帮助你抓住问题、方法和结果主线。 |
| 📖 可读性 | 可读性中。需要一定领域背景，但主线仍然清楚。 摘要中给出了明确指标，适合快速判断效果。 优先看这些信号词：quantizer, redundancy, exact。 |

---

<div align="center">

*Generated by [Paper Claw](https://github.com/yourusername/paper_claw)*

</div>
