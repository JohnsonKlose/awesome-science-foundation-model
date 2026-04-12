# 天文学

<p align="right"><strong>Language:</strong> <a href="astronomy_en.md">English</a> | 中文</p>

> 覆盖多模态天文学、系外行星、引力波、宇宙学、射电天文学、太阳物理等天文学基础模型。
> [总览](../README.zh.md)

## 目录
- [多模态天文](#astronomy-section-01)
- [引力波科学](#astronomy-section-02)
- [射电天文](#astronomy-section-03)
- [系外行星探测](#astronomy-section-04)
- [宇宙学模拟](#astronomy-section-05)
- [CMB分析](#astronomy-section-06)
- [巡天分类器](#astronomy-section-07)
- [行星科学](#astronomy-section-08)
- [参考资源](#astronomy-section-09)

<a id="astronomy-section-01"></a>
## 多模态天文

### E1. 多模态/跨模态基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AION-1 | AION-1: Omnimodal Foundation Model for Astronomical Sciences | Liam Parker | 2025 | 2510.17960 | NeurIPS 2025 | 大规模全模态天文基础模型，集成39种数据模态（成像、光谱、标量测量），覆盖2亿+天文目标 |
| AstroCLIP | AstroCLIP: A Cross-Modal Foundation Model for Galaxies | Liam Parker | 2023 | doi:10.1093/mnras/stae1450 | MNRAS (2024) | 跨模态星系基础模型，使用自监督对比学习将星系图像和光谱嵌入共享物理意义的潜在空间 |
| AstroLLaMA | AstroLLaMA: Towards Specialized Foundation Models in Astronomy | Tuan Dung Nguyen | 2023 | 2309.06126 | WIESP@EMNLP 2023 | 天文专用70亿参数大语言模型，基于LLaMA-2在30万+天文摘要上微调 |
| AstroLLaMA-2-70B | AstroMLab 2: AstroLLaMA-2-70B Model and Benchmarking Specialized LLMs for Astronomy | — | 2024 | 2409.19750 | arXiv preprint | AstroLLaMA的大规模升级版（700亿参数），为天文学提供更强大的领域专用LLM |
| AstroPT | AstroPT: Scaling Large Observation Models for Astronomy | Michael J. Smith | 2024 | 2405.14930 | arXiv preprint | 开源自回归预训练Transformer，在860万DESI Legacy Survey星系图像上训练，可扩展的大观测模型 |
| astroBERT | astroBERT: A Language Model for Astronomy | — | 2022 | — | Astronomy & Computing | 在天文学文献上预训练的BERT模型，用于天文文本挖掘NLP任务 |

### E2. 光谱基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OmniSpectra | OmniSpectra: A Unified Foundation Model for Native Resolution Astronomical Spectra | Jeff Shen | 2025 | 2601.15351 | arXiv preprint | 统一天文光谱基础模型，可处理任意长度、任意仪器的原始分辨率光谱，无需重采样或插值 |
| SpectraFM | SpectraFM: Tuning into Stellar Foundation Models | — | 2024 | — | NeurIPS FM4Science Workshop (2024) | 恒星光谱基础模型，在大规模恒星光谱数据上预训练，支持光谱分类与参数估计等下游任务 |

### E3. 时域天文/光变曲线基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FALCO | FALCO: Foundation Model of Astronomical Light Curves for Time Domain Astronomy | Xiaoxiong Zuo | 2025 | 2504.20290 | AJ (2026) | 天文光变曲线基础模型，基于Transformer自监督学习在Kepler数据上训练，支持时域天文多种下游任务 |
| Astromer 2 | Astromer 2: Few-shot Light Curve Classification | Cristobal Donoso-Oliva | 2025 | 2502.02717 | A&A (2026) | 自监督光变曲线基础模型，在150万MACHO巡天光变曲线上预训练，支持少样本分类 |
| ASTROMER | ASTROMER: A Transformer-based Embedding for the Representation of Light Curves | Cristobal Donoso-Oliva | 2022 | DOI:10.1051/0004-6361/202243928 | A&A (2023) | 首个用于天文光变曲线表征的Transformer预训练模型，可迁移到多种巡天数据 |
| AstroCo | ASTROCO: Self-Supervised Conformer-Style Transformers for Light-Curve Embeddings | — | 2025 | 2509.24134 | arXiv preprint | 自监督Conformer风格Transformer编码器，处理不规则恒星光变曲线 |

---

<a id="astronomy-section-02"></a>
## 引力波科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GraviBERT | GraviBERT: A Foundation Model for Gravitational Wave Signal Analysis | — | 2024 | — | arXiv preprint | 引力波信号分析基础模型，基于BERT架构在模拟引力波数据上预训练，支持信号检测与参数估计 |
| Dingo-T1 | Dingo-T1: A Foundation Model for Fast Gravitational-Wave Inference | — | 2025 | — | NeurIPS ML4PS (2025) | 快速引力波推断基础模型，基于深度学习实现近实时引力波参数后验估计 |
| WaveFormer | WaveFormer: Transformer-based Gravitational Wave Detection | — | 2022 | — | arXiv preprint | 基于Transformer架构的引力波检测模型，从原始干涉仪时间序列中检测引力波信号 |

---

<a id="astronomy-section-03"></a>
## 射电天文

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RGZ-FM | RGZ-FM: A First Multipurpose Foundation Model for Radio Galaxy Zoo | — | 2023 | — | arXiv preprint | 首个多用途射电星系基础模型，在Radio Galaxy Zoo数据上预训练，支持射电源分类与形态学分析 |
| STRADAViT | STRADAViT: A Vision Transformer for Radio Astronomy Data | — | 2026 | — | arXiv preprint | 面向射电天文数据的视觉Transformer基础模型，处理射电干涉成像数据的多种下游任务 |
| SKATR | SKATR: A Foundation Model for SKA Radio Continuum Data | — | 2024 | — | SciPost (2025) | 面向SKA射电连续谱数据的基础模型，为下一代射电巡天提供通用特征表示 |

---

<a id="astronomy-section-04"></a>
## 系外行星探测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PANOPTICON | PANOPTICON: A Foundation Model for Exoplanet Transit Detection | — | 2025 | — | A&A (2025) | 系外行星凌星探测基础模型，用于大规模巡天数据中行星凌星信号的自动检测与分类 |

---

<a id="astronomy-section-05"></a>
## 宇宙学模拟

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GOTHAM | GOTHAM: A Generative Foundation Model for Cosmological Simulations | — | 2024 | — | arXiv preprint | 宇宙学模拟生成基础模型，快速生成高保真大尺度结构模拟 |
| CosmosGalaxyFM | Multi-modal Foundation Model for Cosmological Simulation Data | Bin Xia | 2025 | arXiv:2510.07684 | NeurIPS ML4PS 2025 | 多模态宇宙学基础模型 |

---

<a id="astronomy-section-06"></a>
## CMB分析

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

---

<a id="astronomy-section-07"></a>
## 巡天分类器

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ORACLE | ORACLE: A Foundation Model for Astronomical Survey Classification | — | 2025 | — | ApJ (2025) | 天文巡天分类基础模型，支持多波段巡天数据中的天体源自动分类与编目 |

---

<a id="astronomy-section-08"></a>
## 行星科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MOMO | Mars Orbital Model Foundation Model | — | 2026 | arXiv:2604.02719 | arXiv | 火星轨道多传感器遥感基础模型 |

---

<a id="astronomy-section-09"></a>
## 参考资源

- [PolymathicAI / AstroCLIP (GitHub)](https://github.com/PolymathicAI/AstroCLIP)
- [Smith42 / astroPT (GitHub)](https://github.com/smith42/astroPT)
- [Astromer Science (GitHub)](https://github.com/astromer-science/main-code)
- [IAIFI Astrophysics Papers](https://iaifi.github.io/papers-astro.html)
- [Multimessenger Astronomy in the Era of Foundational AI Workshop (2025)](https://www.lisamission.org/multimessenger-astronomy-in-the-era-of-foundational-ai/)
