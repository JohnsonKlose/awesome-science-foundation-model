# 地球科学

<p align="right"><strong>Language:</strong> <a href="earth-sciences_en.md">English</a> | 中文</p>

> 覆盖天气与气候、遥感、水文学、野火、地震学、海洋科学、空气质量等地球科学基础模型。
> [总览](../README.zh.md)

## 目录
- [天气与气候](#earth-sciences-section-01)
- [遥感](#earth-sciences-section-02)
- [海洋学](#earth-sciences-section-03)
- [地震学](#earth-sciences-section-04)
- [水文学](#earth-sciences-section-05)
- [野火预测](#earth-sciences-section-06)
- [空气质量](#earth-sciences-section-07)
- [冰冻圈](#earth-sciences-section-08)
- [地球科学语言模型](#earth-sciences-section-09)
- [地下与勘探地球物理](#earth-sciences-section-10)
- [SAR专用模型](#earth-sciences-section-11)
- [土地利用](#earth-sciences-section-12)
- [气候降尺度](#earth-sciences-section-13)
- [参考资源](#earth-sciences-section-14)

<a id="earth-sciences-section-01"></a>
## 天气与气候

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Aurora | A foundation model for the Earth system | Cristian Bodnar | 2025 | DOI:10.1038/s41586-025-09005-y | Nature 2025 | 微软开发的大规模地球系统基础模型，在超过100万小时的多源地球物理数据上训练，支持大气、海洋和空气质量预测 |
| Pangu-Weather | Accurate Medium-range Global Weather Forecasting with 3D Neural Networks | Kaifeng Bi | 2022 | 2211.02556 | Nature (2023) | 华为开发的3D高分辨率AI天气预报模型，使用43年ERA5再分析数据训练，可在秒级生成10天全球预报 |
| GraphCast | Learning skillful medium-range global weather forecasting | Remi Lam | 2023 | DOI:10.1126/science.adi2336 | Science 2023 | Google DeepMind基于图神经网络的全球中期天气预报模型，0.25°分辨率，10天预报优于ECMWF HRES |
| GenCast | Probabilistic weather forecasting with machine learning | Ilan Price | 2025 | DOI:10.1038/s41586-024-08252-9 | Nature 2025 | Google DeepMind基于扩散模型的集合天气预报系统，生成概率性15天预报，超越ECMWF ENS |
| ClimaX | ClimaX: A foundation model for weather and climate | Tung Nguyen | 2023 | PMLR v202 | ICML 2023 | 首个天气和气候基础模型，基于Transformer架构，支持多种下游气象任务的灵活微调 |
| FengWu | FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead | Kang Chen | 2023 | arXiv:2304.02948 | arXiv preprint | 上海人工智能实验室开发的多模态多任务天气预报系统，将确定性预报技能推至10.75天 |
| FuXi | FuXi: a cascade machine learning forecasting system for 15-day global weather forecast | Lei Chen | 2023 | DOI:10.1038/s41612-023-00512-1 | npj Climate and Atmospheric Science 2023 | 级联机器学习天气预报系统，使用39年ERA5数据训练，15天预报性能媲美ECMWF集合平均 |
| NeuralGCM | Neural General Circulation Models for Weather and Climate | Dmitrii Kochkov | 2023 | 2311.07222 | Nature (2024) | Google Research开发的神经GCM，将可微大气动力学求解器与机器学习结合，支持天气到气候时间尺度预测 |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Forecasting System | Jaideep Pathak | 2022 | 2202.11214 | arXiv preprint | NVIDIA开发的高分辨率全球天气预报模型，使用自适应傅里叶神经算子(AFNO)，0.25°分辨率 |
| ECMWF AIFS | AIFS -- ECMWF's Data-driven Forecasting System | Simon Lang | 2024 | 2406.01465 | arXiv preprint | ECMWF开发的AI预报系统，结合图神经网络和Transformer，已投入业务运行 |
| Stormer | Scaling Transformer Neural Networks for Skillful and Reliable Medium-range Weather Forecasting | Tung Nguyen | 2023 | 2312.03876 | arXiv preprint | 简洁高效的Transformer天气预报模型，以更少训练数据达到SOTA性能 |
| AtmoRep | AtmoRep: A Stochastic Model of Atmosphere Dynamics Using Large Scale Representation Learning | Christian Lessig | 2023 | 2308.13280 | arXiv preprint | 基于大规模表征学习的随机大气动力学模型，任务无关的大气基础模型 |
| WeatherGFT | WeatherGFT: Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling | Xinyi Li | 2024 | 2405.13796 | NeurIPS 2024 | 混合物理-AI天气预报模型，将预报推广到更细时间分辨率（30分钟间隔） |
| WeatherGFM | WeatherGFM: Learning A Weather Generalist Foundation Model via In-context Learning | Xiangyu Zhao | 2024 | 2411.05420 | ICLR 2025 | 天气通用基础模型，统一天气预报、超分辨率、图像翻译和天气后处理多种任务 |
| Prithvi WxC | Prithvi WxC: Foundation Model for Weather and Climate | Johannes Schmude | 2024 | 2409.13598 | arXiv preprint | IBM和NASA联合开发的23亿参数天气与气候基础模型，使用MERRA-2数据160个变量训练 |
| FuXi-2.0 | FuXi-2.0: Advancing Machine Learning Weather Forecasting Model for Practical Applications | Xiaohui Zhong | 2024 | 2409.07188 | arXiv preprint | FuXi的升级版，提供1小时全球预报，包含更全面的气象变量集 |
| ArchesWeather | ArchesWeather: An Efficient AI Weather Forecasting Model at 1.5° Resolution | Guillaume Couairon | 2024 | 2405.14527 | arXiv preprint | 高效轻量级AI天气预报模型，1.5°分辨率，使用2D注意力和列级注意力组合 |
| W-MAE | W-MAE: Pre-trained Weather Model with Masked Autoencoder | — | 2023 | arXiv:2304.08754 | arXiv | 基于掩码自编码器的预训练天气模型，任务无关的大气基础模型 |
| Omni-Weather | Unified multimodal foundation model for weather | — | 2025 | arXiv:2512.21643 | arXiv | 统一多模态天气生成与理解基础模型 |

---

<a id="earth-sciences-section-02"></a>
## 遥感

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Prithvi-EO-2.0 | Prithvi-EO-2.0: A Versatile Multi-Temporal Foundation Model for Earth Observation Applications | Daniela Szwarcman | 2024 | arXiv:2412.02732 | arXiv | NASA/IBM多时相地球观测基础模型，在420万全球时间序列样本上训练，支持Landsat和Sentinel-2。ting Landsat and Sentinel-2. |
| SpectralGPT | SpectralGPT: Spectral Remote Sensing Foundation Model | Danfeng Hong | 2023 | 2311.07113 | IEEE TPAMI (2024) | 首个光谱遥感基础模型，采用3D生成式预训练Transformer，专为多光谱/高光谱卫星影像设计 |
| SatMAE | SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery | Yezhen Cong | 2022 | NeurIPS 2022 proceedings | NeurIPS 2022 | 针对时序和多光谱卫星影像的掩码自编码器预训练框架 |
| SeaMo | SeaMo: A Multi-Seasonal and Multimodal Remote Sensing Foundation Model | Xuyang Li | 2024 | 2412.19237 | arXiv preprint | 多季节多模态遥感基础模型，融合光学、SAR和气象数据 |
| TerraMind | TerraMind: Large-Scale Generative Multimodality for Earth Observation | Johannes Jakubik | 2025 | ICCV 2025 proceedings | ICCV 2025 | IBM/ESA/DLR联合开发的大规模多模态地球观测生成基础模型，在5000亿token上训练 |
| RingMo | RingMo: A Remote Sensing Foundation Model with Masked Image Modeling | Xian Sun | 2022 | DOI:10.1109/TGRS.2022.3194732 | IEEE TGRS (2023) | 中国科学院开发的遥感基础模型，使用掩码图像建模进行大规模预训练 |
| SatCLIP | SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery | Konstantin Klemmer | 2023 | 2311.17179 | AAAI 2025 | 微软开发的全球通用地理位置编码器，使用Sentinel-2对比学习生成位置嵌入 |
| SkySense | SkySense: A Multi-Modal Remote Sensing Foundation Model Towards Universal Interpretation for Earth Observation Imagery | Xin Guo | 2023 | 2312.10115 | CVPR 2024 | 大规模多模态遥感基础模型，在2150万时序光学+SAR数据集上预训练 |
| Scale-MAE | Scale-MAE: A Scale-Aware Masked Autoencoder for Multiscale Geospatial Representation Learning | Colorado J. Reed | 2022 | 2212.14532 | ICCV 2023 | 尺度感知的掩码自编码器，为多尺度地理空间表征学习显式建模不同空间分辨率关系 |
| DOFA | Neural Plasticity-Inspired Multimodal Foundation Model for Earth Observation | Zhitong Xiong | 2024 | 2403.15356 | arXiv preprint | 受神经可塑性启发的多模态EO基础模型，使用动态波长自适应超网络处理多种传感器数据 |
| GFM (Prithvi-EO-1.0) | Foundation Models for Generalist Geospatial Artificial Intelligence | Johannes Jakubik | 2023 | 2310.18660 | arXiv preprint | NASA/IBM首代地球科学基础模型，基于HLS数据的自监督视觉Transformer |
| S2MAE | S2MAE: A Spatial-Spectral Pretraining Foundation Model for Spectral Remote Sensing Image | Boheng Li | 2024 | — | CVPR 2024 | 空间-光谱掩码自编码器，为光谱遥感影像提供联合空间-光谱预训练 |
| RingMoE | RingMoE: Mixture-of-Modality-Experts Multi-Modal Foundation Models for Universal Remote Sensing Image Interpretation | — | 2024 | 2504.03166 | arXiv preprint | 混合模态专家(MoE)遥感基础模型，147亿参数，在4亿+样本上预训练 |
| WaveMAE | WaveMAE: Wavelet-decomposition Masked Autoencoder for Multispectral Satellite Imagery | — | 2024 | 2510.22697 | arXiv preprint | 结合小波分解和地理空间先验的多光谱卫星影像自监督基础模型 |
| RoMA | RoMA: Scaling up Mamba-based Foundation Models for Remote Sensing | Fengxiang Wang | 2025 | arXiv:2503.10392 | NeurIPS 2025 | 可扩展的Mamba架构遥感基础模型，解决ViT在大规模遥感预训练中的局限 |
| CROMA | CROMA: Contrastive Radar-Optical Masked Autoencoders for Remote Sensing | — | 2024 | NeurIPS 2024 | NeurIPS 2024 | 对比雷达-光学掩码自编码器，用于多模态遥感表示学习 |
| AnySat | One EO model for many resolutions, scales, and modalities | — | 2025 | CVPR 2025 | CVPR 2025 | 统一多分辨率多模态地球观测模型，JEPA架构 |
| TerraFM | Scalable foundation model for unified multisensor EO | — | 2025 | — | ICLR 2026 | 可扩展多传感器统一地球观测基础模型 |

---

<a id="earth-sciences-section-03"></a>
## 海洋学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OceanGPT | OceanGPT: A Large Language Model for Ocean Science Tasks | Zhen Bi | 2024 | DOI:10.18653/v1/2024.acl-long.184 | ACL 2024 | 浙江大学开发的海洋科学专用大语言模型，基于DoInstruct框架生成海洋领域指令数据 |
| XiHe | XiHe: A Data-Driven Model for Global Ocean Eddy-Resolving Forecasting | Xiang Wang | 2024 | arXiv:2402.02995 | arXiv | 数据驱动全球海洋涡旋分辨预报模型，1/12°分辨率，在25年再分析数据上训练。 |
| WV-Net | WV-Net: A Foundation Model for SAR WV-mode Satellite Imagery Trained Using Contrastive Self-supervised Learning | Yannik Glaser | 2025 | — | 期刊论文 | 首个基于SAR海洋卫星影像的基础模型，使用自监督对比学习在合成孔径雷达数据上训练 |
| GLONET | GLONET: Mercator's End-to-End Neural Forecasting System | — | 2024 | 2412.05454 | arXiv preprint | Mercator Ocean开发的端到端神经网络全球海洋预报系统，基于GLORYS12再分析数据训练 |
| WenHai | Forecasting the Eddying Ocean with a Deep Neural Network | — | 2025 | DOI:10.1038/s41467-025-57389-2 | Nature Communications (2025) | 深度神经网络海洋预报系统，擅长中尺度涡旋动力学预测 |
| FuXi-Ocean | FuXi-Ocean: A Global Ocean Forecasting System with Sub-Daily Resolution | — | 2025 | — | NeurIPS 2025 | 数据驱动全球海洋预报系统，6小时时间分辨率，1/12°空间分辨率，深度达1500米 |
| ORCA-DL | Data-driven Global Ocean Modeling for Seasonal to Decadal Prediction | — | 2025 | — | 期刊论文 | 数据驱动全球海洋模型，支持从季节到年代际尺度的三维海洋预测 |
| FuXi-ONS | ML-based ensemble forecasting for global ocean | — | 2026 | arXiv:2603.19591 | arXiv | ML集合全球海洋预报(5-365天) |
| PhaseNet | PhaseNet: A Deep-Neural-Network-Based Seismic Arrival Time Picking Method | Weiqiang Zhu | 2019 | 10.1093/gji/ggy423 | Geophysical Journal International | 最广泛使用的地震到时拾取深度学习模型之一，支持P波和S波到时自动识别 |
| EQTransformer | EQTransformer: An Attentive Deep-Learning Model for Simultaneous Earthquake Detection and Phase Picking | S. Mostafa Mousavi | 2020 | 10.1038/s41467-020-17591-w | Nature Communications | 基于注意力机制的地震检测与震相拾取深度学习模型，已成为地震学标准工具 |

---

<a id="earth-sciences-section-04"></a>
## 地震学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SeisT | SeisT: A Foundational Deep Learning Model for Earthquake Monitoring Tasks | Sen Li | 2023 | 2310.01037 | IEEE TGRS (2024) | 基于Transformer的地震监测基础模型，支持多种地震任务（检测、震相拾取、震级估计等） |
| SeisLM | SeisLM: a Foundation Model for Seismic Waveforms | Tianlin Liu | 2024 | arXiv:2410.15765 | arXiv | 大规模自监督地震波形基础模型，通过对比学习在海量开源地震数据上预训练。rce seismic data. |
| SeisMoLLM | SeisMoLLM: Advancing Seismic Monitoring via Cross-modal Transfer with Pre-trained Large Language Model | Xinghao Wang | 2025 | arXiv:2502.19960 | arXiv | 地震监测基础模型，利用GPT-2架构的跨模态迁移进行地震分析。 |
| SeismicXM | SeismicXM: A Cross-Task Foundation Model for Single-Station Seismic Waveform Processing | — | 2026 | DOI:10.1785/0220250290 | SRL (2026) | 中国地震局开发的跨任务地震波形处理基础模型，支持单台站多种处理任务 |
| U-Trans | U-Trans: A Foundation Model for Seismic Waveform Representation and Enhanced Downstream Earthquake Tasks | — | 2026 | DOI:10.1038/s41598-026-41454-x | Scientific Reports (2026) | U-Net编码器-解码器架构的地震波形表征基础模型，在200万+三分量波形上训练 |
| PhaseNet+ | PhaseNet+: Towards End-to-End Earthquake Monitoring Using a Multitask Deep Learning Model | Weiqiang Zhu | 2024 | 2506.06939 | arXiv preprint | PhaseNet的多任务扩展版本，实现端到端地震监测 |
| SeisCLIP | Contrastive multimodal seismology FM | — | 2023 | arXiv:2309.02320 | arXiv | 对比多模态地震学基础模型 |

---

<a id="earth-sciences-section-05"></a>
## 水文学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| HydroGAT | HydroGAT: A Graph Attention Foundation Model for Hydrological Prediction | — | 2025 | — | arXiv preprint | 基于图注意力网络的水文预测基础模型，建模流域间空间依赖关系 |
| ZeroFlood | ZeroFlood: A Geospatial Foundation Model for Data-Efficient Flood Susceptibility Mapping | — | 2025 | arXiv:2510.23364 | arXiv | 地理空间洪水易感性制图基础模型 |
| GraphRiverCast | Topology-informed AI FM for global river forecasting | — | 2026 | arXiv:2602.22293 | arXiv | 拓扑信息全球河流水动力预报AI基础模型 |

---

<a id="earth-sciences-section-06"></a>
## 野火预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FireCastNet | FireCastNet: A Deep Learning Model for Global Wildfire Danger Forecasting | — | 2025 | — | Scientific Reports (2025) | 深度学习全球野火危险预报模型，融合气象、植被和地形数据实现多时间尺度预测 |
| FireScope | FireScope: A Foundation Model for Wildfire Spread Prediction | — | 2025 | — | arXiv preprint | 野火蔓延预测基础模型，利用多源遥感和气象数据预测火灾传播路径 |

---

<a id="earth-sciences-section-07"></a>
## 空气质量

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AirCast | AirCast: A Data-Driven Foundation Model for Air Quality Forecasting | — | 2024 | — | arXiv preprint | 数据驱动的空气质量预报基础模型，支持多种大气污染物浓度预测 |
| FuXi-Air | FuXi-Air: Global Air Quality Forecasting with a Foundation Model Approach | — | 2025 | — | arXiv preprint | FuXi系列空气质量预报扩展，将天气预报基础模型范式应用于全球空气质量预测 |

---

<a id="earth-sciences-section-08"></a>
## 冰冻圈

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SIFM | SIFM: Sea Ice Foundation Model for Arctic Monitoring | — | 2024 | — | arXiv preprint | 海冰基础模型，用于北极海冰监测，基于多源卫星遥感数据预训练 |
| IceNet | IceNet: Seasonal Arctic Sea Ice Forecasting with Probabilistic Deep Learning | Tom Andersson | 2021 | DOI:10.1038/s41467-021-25257-4 | Nature Communications (2021) | 概率深度学习北极海冰季节预报模型，预报技能显著超越物理动力学模型 |
| IceMamba | IceMamba: A Mamba-based Foundation Model for Sea Ice Forecasting | — | 2025 | — | arXiv preprint | 基于Mamba状态空间模型架构的海冰预报基础模型，高效处理极区时空序列数据 |

---

<a id="earth-sciences-section-09"></a>
## 地球科学语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| K2 | K2: A Foundation Language Model for Geoscience Knowledge Understanding and Utilization | Cheng Deng | 2024 | 10.1145/3616855.3635772 | WSDM 2024 / ACM | 首个基于LLaMA的70亿参数地球科学LLM，在地球科学文献上继续预训练和指令微调。literature. |
| JiuZhou | JiuZhou: open foundation language models and effective pre-training framework for geoscience | Zhou Chen | 2025 | 10.1080/17538947.2025.2449708 | International Journal of Digital Earth | 清华大学提出的地球科学开放基础语言模型及高效预训练框架，支持中英文地学知识问答与推理。 |
| GeoGPT | GeoGPT: An assistant for understanding and processing geospatial tasks | Yifan Zhang | 2024 | 10.1016/j.jag.2024.103976 | International Journal of Applied Earth Observation and Geoinformation | 面向地理空间任务理解与处理的助手模型，结合GIS工具调用能力完成地理空间分析与推理。 |
| GeoGalactica | GeoGalactica: A Scientific LLM for Geoscience | — | 2024 | arXiv:2401.00434 | arXiv | 300亿参数地球科学大语言模型，基于Galactica架构在地学语料上预训练 |

---

<a id="earth-sciences-section-10"></a>
## 地下与勘探地球物理

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Transparent Earth | Transparent Earth: A Foundation Model for Subsurface Characterization | — | 2025 | — | arXiv Preprint | 洛斯阿拉莫斯国家实验室开发的地下特征化基础模型，用于地下结构成像与反演 |
| GEM 3D | GEM 3D: A Generative Earth Model for 3D Subsurface Modeling | — | 2025 | — | arXiv preprint | 生成式三维地球模型，用于地下结构建模与地质属性预测 |
| SFM-Exploration | SFM-Exploration: A Seismic Foundation Model for Exploration Geophysics | — | 2023 | — | Geophysics (2025) | 面向勘探地球物理的地震基础模型，在大规模合成与实际地震数据上预训练，支持多种勘探下游任务 |
| WLFM | WLFM: Well Log Foundation Model for Subsurface Analysis | — | 2025 | — | arXiv preprint | 测井基础模型，在大规模测井数据上自监督预训练，支持岩性识别、储层预测等下游任务 |

---

<a id="earth-sciences-section-11"></a>
## SAR专用模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SARATR-X | SARATR-X: Towards Building A Foundation Model for SAR Target Recognition | — | 2024 | — | IEEE TGRS (2024) | SAR目标识别基础模型，在大规模SAR图像上预训练，支持多种SAR目标识别下游任务 |
| SUMMIT | SUMMIT: A SAR Universal Multi-task Foundation Model for Intelligent Interpretation | — | 2025 | — | arXiv preprint | SAR通用多任务基础模型，统一检测、分割、分类等多种SAR解译任务 |
| SAR-W-MixMAE | SAR-W-MixMAE: A Mixed Masked Autoencoder for SAR-Wide Image Pre-training | — | 2025 | — | arXiv preprint | 混合掩码自编码器SAR宽幅图像预训练模型，优化SAR特有的斑点噪声和几何特征学习 |
| CrossEarth-SAR | Billion-scale SAR FM for domain-generalizable segmentation | — | 2026 | arXiv:2603.12008 | arXiv | 十亿级SAR基础模型，域泛化语义分割 |

---

<a id="earth-sciences-section-12"></a>
## 土地利用

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| LandSegmenter | LandSegmenter: A Foundation Model for Land Use and Land Cover Segmentation | — | 2025 | — | arXiv preprint | 土地利用/土地覆盖分割基础模型，大规模多源遥感数据预训练，支持全球LULC制图 |

---

<a id="earth-sciences-section-13"></a>
## 气候降尺度

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ORBIT-2 | ORBIT-2: A Foundation Model for Climate Downscaling | — | 2025 | — | ORNL | 气候降尺度基础模型，在超级计算环境中训练，实现高效气候降尺度推理 |

---

<a id="earth-sciences-section-14"></a>
## 参考资源

- [DL-Foundation-Models-for-Weather-Prediction (GitHub)](https://github.com/jimengshi/dl-foundation-models-weather)
- [Awesome-Remote-Sensing-Foundation-Models (GitHub)](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models)
- [Foundation Models for Remote Sensing and Earth Observation — Survey](https://arxiv.org/abs/2410.16602)
