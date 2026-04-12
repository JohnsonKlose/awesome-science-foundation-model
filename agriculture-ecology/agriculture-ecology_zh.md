# 农业与生态

<p align="right"><strong>Language:</strong> <a href="agriculture-ecology_en.md">English</a> | 中文</p>

> 覆盖作物科学、植物表型、农业遥感、生物多样性、野生动物等农业与生态基础模型。
> [总览](../README.zh.md)
> 说明：本页已剔除纯数据集、基准、挑战赛、库与仅有产品发布页的条目；为避免误译，少量新增条目暂沿用英文版简述。

## 目录
- [作物与生态遥感](#agriculture-ecology-section-01)

<a id="agriculture-ecology-section-01"></a>
## 作物与生态遥感

### 综述 Overview

农业与生态基础模型涵盖作物检测、植物病害识别、生物多样性监测、物种识别和农业遥感等方面的AI模型。

---

### A1. 农业AI基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AgriGPT | AgriGPT: A Strong Plant Disease Detection Model via Visual-Language Model | (西交利物浦大学) | 2024 | 10.1007/978-981-96-9921-6_20 | Lecture Notes in Computer Science | 多模态AI模型，集成视觉和文本数据用于精准植物病害检测和作物健康评估。 |
| AgriGPT (Ecosystem) | AgriGPT: a Large Language Model Ecosystem for Agriculture | Bo Yang | 2025 | arXiv:2508.08632 | arXiv | 农业专用LLM生态系统，配备多智能体数据引擎，编译高质量农业领域数据 |
| AgroGPT | AgroGPT: Efficient Agricultural Vision-Language Model with Expert Tuning | Muhammad Awais | 2024 | arXiv:2410.08405 | WACV 2025 | 农业专用视觉-语言模型，基于70,000张图像的AgroInstruct数据集通过专家调优训练，支持作物病害对话。 |
| IPM-AgriGPT | IPM-AgriGPT: A Large Language Model for Pest and Disease Management with a G-EA Framework | Leifeng Guo | 2025 | DOI:10.3390/math13040566 | Mathematics 2025 | 利用G-EA框架和农业上下文推理的害虫病害管理大语言模型。 |
| AgriGPT-Omni | AgriGPT-Omni: A Unified Speech-Vision-Text Framework for Multilingual Agricultural Intelligence | Bo Yang | 2025 | arXiv:2512.10624 | arXiv | 浙江大学开发的统一语音-视觉-文本多语言农业AI框架 |
| AgriFM | AgriFM: A Multi-source Temporal Remote Sensing Foundation Model for Crop Mapping | Wenyuan Li | 2025 | arXiv:2505.21357 | arXiv Preprint | 多源时序遥感基础模型，集成MODIS/Landsat-8/9/Sentinel-2卫星数据，使用改进的Video Swin Transformer进行作物制图。 |
| CropSTS | CropSTS: A Remote Sensing Foundation Model for Cropland Classification with Decoupled Spatiotemporal Attention | Yuxing Chen | 2025 | DOI:10.3390/rs17142481 | Remote Sensing 2025 | 利用解耦时空注意力机制的作物分类遥感基础模型，解决模糊田块边界和有限时序建模问题。 |
| SoilNet | SoilNet: Multimodal Soil Horizon Classification | (多作者) | 2025 | — | arXiv Preprint | 多模态土壤层位分类基础模型，整合土壤图像、化学和物理属性数据。 |
| AQUA | AQUA: The First Large Language Model for Aquaculture and Fisheries | (多作者) | 2025 | — | arXiv Preprint | 首个水产养殖和渔业专用大语言模型，涵盖养殖管理、病害诊断等领域知识。 |
| FoMo4Wheat | FoMo4Wheat: Toward reliable crop vision foundation models | PheniX-Lab | 2025 | arXiv:2509.06907 | arXiv | 小麦表型分析专用基础模型 |
| SPROUT | Scalable Diffusion Foundation Model for Agricultural Vision | UTokyo | 2026 | arXiv:2603.27519 | arXiv | 扩散预训练农业视觉基础模型 |

### A2. 生态与生物多样性AI基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BioAnalyst | BioAnalyst: A Foundation Model for Biodiversity | Athanasios Trantas | 2025 | arXiv:2507.09080 | NeurIPS 2025 | 首个多模态生物多样性基础模型，基于Transformer架构，集成物种记录、遥感、气候等生态数据用于欧洲保护规划。 |
| NatureLM-audio | NatureLM-audio: an Audio-Language Foundation Model for Bioacoustics | David Robinson | 2024 | arXiv:2411.07186 | arXiv | 首个大规模生物声学音频-语言基础模型，支持零样本物种分类和声音描述，用于生态监测 |
| OpenWildlife | OpenWildlife: Open-Vocabulary Multi-Species Wildlife Detector for Geographically-Diverse Aerial Imagery | Muhammed Patel | 2025 | arXiv:2506.19204 | arXiv | 开放词汇多物种野生动物检测器，使用语言-视觉基础模型处理陆地和海洋航空影像 |
| NicheFlow | NicheFlow: A Generative Foundation Model for Species Distribution Modeling | (多作者) | 2024 | bioRxiv | bioRxiv Preprint | 首个基于生成式流匹配的物种分布建模基础模型，学习环境-物种关系的连续分布。 |
| Granite-Geospatial-Ocean | A Sentinel-3 foundation model for ocean colour | Geoffrey Dawson | 2025 | arXiv:2509.21273 | arXiv | Granite地理空间系列中的Sentinel-3海洋颜色基础模型，用于海洋监测及下游海洋任务。 |
| OceanSAR | OceanSAR: SAR Ocean Observation Foundation Model | (多作者) | 2025 | — | arXiv Preprint | SAR海洋观测基础模型，专注于海洋表面监测、船舶检测和海洋环境分析。 |
| Insect-Foundation | Insect-Foundation: A Foundation Model for Visual Insect Understanding | Hoang-Quan Nguyen | 2024 | arXiv:2311.15206 | CVPR 2024 | 昆虫视觉理解基础模型，100万张昆虫图像 |
| FMRAG | FMRAG: Retrieval-Augmented Multimodal Large Language Models for Fisheries Intelligence | — | 2026 | 10.3389/fmars.2026.1801835 | Frontiers in Marine Science | 渔业智能检索增强多模态大语言模型 |

### A3. 相关遥感基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SkySense++ | A Semantic-Enhanced Multi-Modal Remote Sensing Foundation Model for Earth Observation | Kang Wu | 2025 | DOI:10.1038/s42256-025-01078-8 | Nature Machine Intelligence 2025 | 语义增强的多模态遥感基础模型，在2700万遥感数据上训练，支持农业制图在内的多种地球观测任务。 |
| SkySense V2 | SkySense V2: A Unified Foundation Model for Multi-modal Remote Sensing | (多作者) | 2025 | arXiv:2507.13812 | ICCV 2025 | 统一的多模态遥感基础模型，单一Transformer主干处理多种遥感模态数据。 |

---

