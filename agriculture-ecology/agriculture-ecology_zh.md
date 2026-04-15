# 农业与生态

<p align="right"><strong>Language:</strong> <a href="agriculture-ecology_en.md">English</a> | 中文</p>

> 覆盖作物科学、植物表型、农业遥感、生物多样性、野生动物等农业与生态基础模型。
> [总览](../README.zh.md)

## 目录
- [作物与生态遥感](#agriculture-ecology-section-01)

<a id="agriculture-ecology-section-01"></a>
## 作物与生态遥感

#### 综述 Overview

农业与生态基础模型涵盖作物检测、植物病害识别、生物多样性监测、物种识别和农业遥感等方面的AI模型。

---

#### A1. 农业AI基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AgriGPT | AgriGPT: A Strong Plant Disease Detection Model via Visual Instruction Tuning | (西交利物浦大学) | 2024 | 10.1007/978-981-96-9921-6_20 | Springer | 多模态AI模型，集成视觉和文本数据用于精准植物病害检测和作物健康评估。 |
| AgroGPT | AgroGPT: Efficient Agricultural Vision-Language Model with Expert Tuning | Muhammad Awais | 2024 | arXiv:2410.08405 | WACV 2025 | 农业专用视觉-语言模型，基于70,000张图像的AgroInstruct数据集通过专家调优训练，支持作物病害对话。 |
| IPM-AgriGPT | IPM-AgriGPT: A Large Language Model for Pest and Disease Management with a G-EA Framework | Leifeng Guo | 2025 | DOI:10.3390/math13040566 | Mathematics 2025 | 利用G-EA框架和农业上下文推理的害虫病害管理大语言模型。 |
| AgriGPT-Omni | AgriGPT-Omni: A Unified Speech-Vision-Text Framework for Multilingual Agricultural Intelligence | Bo Yang | 2025 | arXiv:2512.10624 | arXiv | 浙江大学开发的统一语音-视觉-文本多语言农业AI框架。 |
| AgriFM | AgriFM: A Multi-source Temporal Remote Sensing Foundation Model for Crop Mapping | Wenyuan Li | 2025 | arXiv:2505.21357 | arXiv Preprint | 多源时序遥感基础模型，集成MODIS/Landsat-8/9/Sentinel-2卫星数据，使用改进的Video Swin Transformer进行作物制图。 |
| CropSTS | CropSTS: A Remote Sensing Foundation Model for Cropland Classification with Decoupled Spatiotemporal Attention | Yuxing Chen | 2025 | DOI:10.3390/rs17142481 | Remote Sensing 2025 | 利用解耦时空注意力机制的作物分类遥感基础模型，解决模糊田块边界和有限时序建模问题。 |
| AlphaEarth Foundation | Evaluating Geospatial Foundation Models for Agricultural Applications | — | 2025 | arXiv:2601.00857 | arXiv | 基于多源地球观测数据训练的地理空间基础模型，用于农业应用评估（含作物产量预测等） |
| VITA | VITA: Variational Transformer for Crop Yield Prediction | (多作者) | 2025 | — | arXiv Preprint | 基于变分Transformer的作物产量预测模型，结合时序遥感和环境数据。 |
| AQUA | AQUA: The First Large Language Model for Aquaculture and Fisheries | (多作者) | 2025 | — | arXiv Preprint | 首个水产养殖和渔业专用大语言模型，涵盖养殖管理、病害诊断等领域知识。 |
| FoMo4Wheat | FoMo4Wheat: Toward reliable crop vision foundation models | PheniX-Lab | 2025 | arXiv:2509.06907 | arXiv | 小麦表型分析专用基础模型 |
| SPROUT | Scalable Diffusion Foundation Model for Agricultural Vision | UTokyo | 2026 | arXiv:2603.27519 | arXiv | 扩散预训练农业视觉基础模型 |
| SpeciesNet | SpeciesNet: Open-Source AI Model for Wildlife Species Identification | — | 2025 | — | Google GitHub | Google开源AI模型，在6500万张相机陷阱图像上训练，识别近2500种野生动物 |

#### A2. 生态与生物多样性AI基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BioAnalyst | BioAnalyst: A Foundation Model for Biodiversity | Athanasios Trantas | 2025 | arXiv:2507.09080 | NeurIPS 2025 | 首个多模态生物多样性基础模型，基于Transformer架构，集成物种记录、遥感、气候等生态数据用于欧洲保护规划。 |
| NatureLM-audio | NatureLM-audio: An Audio-Language Foundation Model for Bioacoustics | (Earth Species Project) | 2024 | arXiv:2411.07186 | arXiv Preprint | 首个大规模生物声学音频-语言基础模型，支持零样本物种分类和声音描述，用于生态监测。 |
| Tighnari | Tighnari: Multi-modal Plant Species Prediction Based on Hierarchical Cross-Attention | (多作者) | 2025 | arXiv:2501.02649 | arXiv Preprint | 多模态植物物种预测AI模型，整合卫星图像、气候时序、土地覆盖和土壤变量进行时空物种分布预测。 |
| Tighnari v2 | Tighnari v2: Mitigating Label Noise and Distribution Shift in Multi-modal Plant Species Prediction | (多作者) | 2026 | arXiv:2602.08282 | arXiv Preprint | Tighnari升级版，解决噪声标签和分布偏移问题，增强植物物种分布预测的鲁棒性。 |
| BirdNET | BirdNET: A Deep Learning Solution for Avian Diversity Monitoring | Stefan Kahl | 2021 | — | Cornell Lab | 康奈尔大学鸟类学实验室开发的深度学习鸟类声音识别模型，V1.0支持6500+物种，V3.0扩展到11000+物种，广泛用于生态声学监测。 |
| NicheFlow | NicheFlow: A Generative Foundation Model for Species Distribution Modeling | (多作者) | 2024 | bioRxiv | bioRxiv Preprint | 首个基于生成式流匹配的物种分布建模基础模型，学习环境-物种关系的连续分布。 |
| EcoCast | EcoCast: Biodiversity Risk Forecasting Foundation Model | (多作者) | 2025 | — | NeurIPS Workshop 2025 | 生物多样性风险预测基础模型，用于生态系统健康评估和保护规划。 |
| MiTREE | MiTREE: Multi-Input Transformer for Species Distribution Estimation | (多作者) | 2024 | — | arXiv Preprint | 多输入Transformer模型用于物种分布估计，整合多源环境和遥感数据。 |
| Granite-Geospatial-Ocean | Granite Geospatial Ocean: IBM Foundation Model for Ocean Monitoring | (IBM Research) | 2025 | — | arXiv Preprint | IBM开发的海洋监测地理空间基础模型，基于Granite系列，用于海洋环境变化检测和预测。 |
| OceanSAR | OceanSAR: SAR Ocean Observation Foundation Model | (多作者) | 2025 | — | arXiv Preprint | SAR海洋观测基础模型，专注于海洋表面监测、船舶检测和海洋环境分析。 |
| SatBird | SatBird: Bird Species Distribution Modeling with Remote Sensing and Citizen Science Data | — | 2023 | doi:10.52202/075280-3317 | NeurIPS | 鸟类物种分布模型，结合卫星影像和eBird公民科学数据用于鸟类生态研究 |
| Insect-Foundation | Insect-Foundation: A Foundation Model for Visual Insect Understanding | Hoang-Quan Nguyen | 2024 | arXiv:2311.15206 | CVPR 2024 | 昆虫视觉理解基础模型，100万张昆虫图像 |
| Atlantes | Atlantes: GPS transformers for global-scale maritime intelligence | Allen AI | 2025 | arXiv:2504.19036 | arXiv | GPS Transformer全球海洋船舶行为分析 |

#### A3. 相关遥感基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SkySense++ | A Semantic-Enhanced Multi-Modal Remote Sensing Foundation Model for Earth Observation | Kang Wu | 2025 | DOI:10.1038/s42256-025-01078-8 | Nature Machine Intelligence 2025 | 语义增强的多模态遥感基础模型，在2700万遥感数据上训练，支持农业制图在内的多种地球观测任务。 |
| SkySense V2 | SkySense V2: A Unified Foundation Model for Multi-modal Remote Sensing | (多作者) | 2025 | arXiv:2507.13812 | ICCV 2025 | 统一的多模态遥感基础模型，单一Transformer主干处理多种遥感模态数据。 |

---

> **总计 / Total: 27 models** — 农业AI: 11 | 生态与生物多样性: 14 | 相关遥感: 2
