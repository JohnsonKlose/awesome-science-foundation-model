# 医学与生物医学

<p align="right"><strong>Language:</strong> <a href="medicine_en.md">English</a> | 中文</p>

> 覆盖医学影像、病理、放射学、临床语言模型、手术 AI、数字健康、药物发现等医学与生物医学基础模型。
> [总览](../README.zh.md)
> 说明：本页已剔除纯数据集、基准、挑战赛、库与仅有产品发布页的条目；为避免误译，少量新增条目暂沿用英文版简述。

## 目录
- [医学影像](#medicine-section-01)
- [神经影像](#medicine-section-02)
- [病理学](#medicine-section-03)
- [内窥镜与手术](#medicine-section-04)
- [超声](#medicine-section-05)
- [心电与生理信号](#medicine-section-06)
- [口腔影像](#medicine-section-07)
- [眼科](#medicine-section-08)
- [医学文本与NLP](#medicine-section-09)
- [医学多模态](#medicine-section-10)
- [电子健康记录](#medicine-section-11)
- [核医学](#medicine-section-12)
- [乳腺影像](#medicine-section-13)
- [肌骨影像](#medicine-section-14)
- [可穿戴与数字健康](#medicine-section-15)
- [放射治疗](#medicine-section-16)
- [显微镜](#medicine-section-17)
- [睡眠医学](#medicine-section-18)
- [兽医学](#medicine-section-19)
- [法医学](#medicine-section-20)

<a id="medicine-section-01"></a>
## 医学影像

### 综述 Overview

医学影像基础模型涵盖CT、MRI、X-ray等多种模态的大规模预训练模型，用于分割、分类、检测及报告生成等临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MRI-CORE | MRI-CORE: A Foundation Model for Magnetic Resonance Imaging | Haoyu Dong | 2025 | arXiv:2506.12186 | arXiv | 在110,000+ MRI体数据（600万+切片）上预训练的基础模型，覆盖18个身体部位，支持分割、分类和零样本分析。 |
| Pillar-0 | Pillar-0: A New Frontier for Radiology Foundation Models | Kumar Krishna Agrawal | 2025 | arXiv:2511.17803 | arXiv | UC Berkeley/UCSF开发的放射学基础模型，在腹盆CT、胸部CT、头部CT和乳腺MRI上预训练，用于解读3D体积数据。 |
| CineMA | CineMA: A Foundation Model for Cine Cardiac MRI | (多作者) | 2025 | arXiv:2506.00679 | arXiv Preprint | 在1500万张心脏磁共振图像（~75,000受试者）上训练的心脏MRI基础模型，支持心室分割、射血分数计算和疾病检测。 |
| OmniMRI | OmniMRI: A Unified Vision-Language Foundation Model for MRI | (多作者) | 2025 | arXiv:2508.17524 | arXiv Preprint | 统一的MRI全流程基础模型，覆盖采集、重建、分割、检测、诊断和报告生成。 |
| BiomedCLIP | BiomedCLIP: A Multimodal Biomedical Foundation Model Pretrained from Fifteen Million Scientific Image-Text Pairs | Sheng Zhang | 2023 | arXiv:2303.00915 | arXiv | 微软开发的生物医学视觉-语言基础模型，在PMC-15M（1500万图文对）上预训练，支持跨模态检索和零样本分类。 |
| SAM-Med2D | SAM-Med2D | Junlong Cheng | 2023 | arXiv:2308.16184 | arXiv | Segment Anything Model (SAM) 的2D医学图像分割适配版本，在460万图像和1970万mask上微调。 |
| SAM-Med3D | SAM-Med3D: Towards General-purpose Segmentation Models for Volumetric Medical Images | Haoyu Wang | 2023 | arXiv:2310.15161 | arXiv | 通用3D医学图像分割模型，支持多种解剖结构和病灶的交互式分割，仅需最少标注。 |
| MedSAM | Segment Anything in Medical Images | Jun Ma | 2023 | arXiv:2304.12306 | Nature Communications 2024 | 首个通用医学图像分割基础模型，在超过157万图像-mask对、10种成像模态上训练。 |
| MedSAM2 | MedSAM2: Segment Anything in 3D Medical Images and Videos | Jun Ma | 2025 | arXiv:2504.03600 | arXiv | 基于SAM 2的3D医学图像和视频分割模型，在455,000+ 3D图像-mask对上微调。 |
| CT-CLIP | A Foundation Model Utilizing Chest CT Volumes and Radiology Reports for Supervised-Level Zero-Shot Detection of Abnormalities | Ibrahim Ethem Hamamci | 2024 | arXiv:2403.17834 | arXiv | 基于CT-RATE数据集的3D胸部CT基础模型，通过对比语言-图像预训练实现零样本异常检测。 |
| CheXzero | Expert-Level Detection of Pathologies from Unannotated Chest X-ray Images via Self-Supervised Learning | Ekin Tiu | 2022 | DOI:10.1038/s41551-022-00936-9 | Nature Biomedical Engineering 2022 | 基于自监督对比学习的零样本胸部X光分析模型，无需标注即可达到专家级病理检测水平。 |
| BioViL | Making the Most of Text Semantics to Improve Biomedical Vision-Language Processing | Benedikt Boecking | 2022 | arXiv:2204.09817 | ECCV 2022 | 微软开发的生物医学视觉-语言模型，结合领域特定语言模型CXR-BERT，增强胸部X光分析。 |
| BioViL-T | Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing | Shruthi Bannur | 2023 | arXiv:2301.04558 | CVPR 2023 | 微软开发的时序视觉-语言模型，用于放射学中胸部X光的纵向分析和短语定位。 |
| LVM-Med | LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-Order Graph Matching | Duy M.H. Nguyen | 2023 | arXiv:2306.11925 | NeurIPS 2023 | 大规模自监督医学影像视觉模型，在约130万张多模态图像（CT/MRI/X-ray/超声等）上训练。 |
| STU-Net | STU-Net: Scalable and Transferable Medical Image Segmentation Models Empowered by Large-Scale Supervised Pre-training | Ziyan Huang | 2023 | arXiv:2304.06716 | arXiv | 可扩展至14亿参数的医学图像分割模型，通过大规模监督预训练实现强迁移性。 |
| UniverSeg | UniverSeg: Universal Medical Image Segmentation | Victor Ion Butoi | 2023 | arXiv:2304.06131 | ICCV 2023 | 无需额外训练即可泛化到未见任务的医学图像分割模型，使用in-context学习范式。 |
| RETFound | A Foundation Model for Generalizable Disease Detection from Retinal Images | Yukun Zhou | 2023 | DOI:10.1038/s41586-023-06555-x | Nature 2023 | 在160万张未标注视网膜图像上自监督预训练的眼科基础模型，支持多种眼病和全身疾病检测。 |
| SkinGPT-4 | Pre-trained Multimodal Large Language Model Enhances Dermatological Diagnosis Using SkinGPT-4 | Juexiao Zhou | 2023 | arXiv:2304.10691 | Nature Communications 2024 | 交互式皮肤病诊断系统，集成视觉变换器和Llama-2-13b-chat，在52,000+皮肤病图像上训练。 |
| PanDerm | A Multimodal Vision Foundation Model for Clinical Dermatology | (多作者) | 2024 | arXiv:2410.15038 | Nature Medicine 2025 | 在200万+皮肤病图像（11个机构、4种成像模态）上预训练的多模态皮肤科基础模型。 |
| RadFM | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data | Chaoyi Wu | 2023 | arXiv:2308.02463 | Nature Communications 2025 | 通用放射学基础模型，利用1300万2D图像和61.5万3D扫描进行多模态训练。 |
| CheXFound | Chest X-ray Foundation Model with Global and Local Self-supervised Learning | (多作者) | 2025 | arXiv:2502.05142 | arXiv Preprint | 在约100万张胸部X光上自监督预训练的基础模型，结合全局和局部学习策略，提升多种临床任务的泛化能力。 |
| REMEDIS | Robust and Data-Efficient Generalization of Self-Supervised Machine Learning for Diagnostic Imaging | Shekoofeh Azizi | 2022 | arXiv:2205.09723 | Nature Biomedical Engineering 2023 | Google开发的医学影像表示学习框架，结合大规模自监督预训练和任务特定微调，提升鲁棒性和数据效率。 |
| Medical SAM Adapter | Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation | Junde Wu | 2023 | arXiv:2304.12620 | MIA 2025 | 通过适配器将SAM适配于医学图像分割的方法，保持SAM原有能力同时增强医学域表现。 |
| MedicoSAM | MedicoSAM: Towards Foundation Models for Medical Image Segmentation | (多作者) | 2025 | arXiv:2501.11734 | arXiv Preprint | 探索将SAM适配为医学图像分割基础模型的系统研究。 |
| BiomedParse | BiomedParse: Biomedical Foundation Model for Image Parsing | Microsoft | 2024 | arXiv:2405.12971 | Nature Methods 2024 | 微软统一生物医学图像解析基础模型，支持分割、检测和识别 |
| TotalSegmentator | TotalSegmentator: Robust Segmentation of 104 Anatomic Structures in CT Images | Jakob Wasserthal | 2023 | DOI:10.1148/ryai.230024 | Radiology: AI 2023 | 104种解剖结构CT自动分割，1228例训练集 |
| SegVol | SegVol: Universal and Interactive Volumetric Medical Image Segmentation | Yuxin Du | 2023 | arXiv:2311.13385 | arXiv | 通用交互式3D医学图像分割模型，支持语义和空间提示。 |
| SuPreM | SuPreM: Label-Efficient 3D Medical Image Segmentation via Supervised Pre-training | — | 2024 | arXiv:2410.06667 | IEEE TMI 2025 | 监督预训练的3D分割基础模型，2100+CT |
| VISTA3D | VISTA3D: Versatile Imaging Segmentation and Annotation Model for 3D | NVIDIA | 2024 | — | MICCAI 2024 | NVIDIA通用3D医学图像分割注释模型 |
| CT-FM | CT Foundation Model for Body Composition Analysis | — | 2024 | — | arXiv | CT身体成分分析基础模型 |
| LCTfound | Learning CT Foundation Representations | — | 2025 | — | arXiv | CT基础表征学习 |
| EVA-X | EVA-X: A Foundation Model for General Chest X-ray Analysis | — | 2024 | arXiv:2405.05237 | arXiv | 通用胸部X光分析基础模型 |
| vesselFM | vesselFM: A Foundation Model for Universal 3D Blood Vessel Segmentation | Bastian Wittmann | 2025 | 10.1109/cvpr52734.2025.01944 | CVPR 2025 | 通用3D血管分割基础模型。 |
| Rad-DINO | RAD-DINO: Exploring Scalable Medical Image Encoders Beyond Text Supervision | — | 2024 | arXiv:2401.10815 | arXiv | 超越文本监督的可扩展医学图像编码器 |
| MAIRA-2 | MAIRA-2: Grounded Radiology Report Generation | Shruthi Bannur | 2024 | arXiv:2406.04449 | arXiv | 微软开发的定位感知放射报告生成模型，结合病灶定位和文本生成。 |
| MedCLIP | MedCLIP: Contrastive Learning from Unpaired Medical Images and Text | Zifeng Wang | 2022 | arXiv:2210.10163 | EMNLP 2022 | 去耦合对比学习医学视觉-语言模型 |
| PMC-CLIP | PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents | Weixiong Lin | 2023 | arXiv:2303.07240 | MICCAI 2023 | PubMed Central文献预训练的生物医学CLIP |
| M3D | M3D: Advancing 3D Medical Image Analysis with Multi-Modal Large Language Models | Fan Bai | 2024 | arXiv:2404.00578 | arXiv | 3D医学影像多模态大语言模型。 |
| Merlin | Merlin: A Vision Language Foundation Model for 3D Computed Tomography | Louis Blankemeier | 2024 | arXiv:2406.06512 | arXiv | 3D CT视觉-语言基础模型，15,000+ CT |
| ELIXR | ELIXR: Towards a General-Purpose X-Ray Artificial Intelligence System Through Alignment of Large Language Models and Radiology Vision Encoders | Google | 2023 | arXiv:2308.01317 | Google Research / arXiv | Google大语言模型对齐放射学视觉编码器 |
| CXR-LLaVA | CXR-LLaVA: Multimodal Large Language Model for Interpreting Chest X-ray | — | 2024 | — | arXiv | 胸部X光解读多模态大语言模型 |
| 3DINO | 3DINO: Self-supervised 3D Anatomical Representation Learning | — | 2025 | — | arXiv | 3D解剖自监督表征学习 |
| DeepMedix-R1 | DeepMedix-R1: Reasoning-Based Medical Imaging Foundation Model | — | 2025 | — | arXiv | 推理增强医学影像基础模型 |
| MedImageInsight | MedImageInsight: An Open-Source Embedding Model for General Domain Medical Imaging | Noel C. F. Codella | 2024 | arXiv:2410.06542 | arXiv | 微软开源医学影像嵌入基础模型，覆盖14种成像模态，支持多种下游任务。 |
| Curia | Curia: A Multi-Modal Foundation Model for Radiology | Corentin Dancette | 2025 | arXiv:2509.06830 | arXiv | 大规模放射学多模态基础模型，在150,000 CT/MRI检查（130TB数据）上训练，支持报告生成和图像理解。 |
| Medical SAM3 | Medical SAM3: A Foundation Model for Universal Prompt-Driven Medical Image Segmentation | Chongcong Jiang | 2026 | arXiv:2601.10880 | arXiv | 基于SAM3的通用提示驱动医学图像分割基础模型，同时支持2D和3D医学数据。 |
| OmniRad | OmniRad: A self-supervised radiological foundation model | — | 2026 | arXiv:2602.04547 | arXiv Preprint | 自监督放射学基础模型，训练于120万张医学影像，强调跨任务迁移能力 |
| MedVAR | MedVAR: Towards Scalable and Efficient Medical Image Generation via Next-scale Autoregressive Prediction | Zhicheng He | 2026 | arXiv:2602.14512 | arXiv | 可扩展高效的医学图像生成基础模型，使用下一尺度自回归预测。 |
| FMIR | FMIR, a foundation model-based Image Registration Framework for Robust Image Registration | Fengting Zhang | 2026 | arXiv:2601.17529 | arXiv | 基于基础模型的医学图像配准框架，实现鲁棒图像配准。 |
| Citrus-V | Citrus-V: Advancing Medical Foundation Models with Unified Medical Image Grounding for Clinical Reasoning | Guoxin Wang | 2025 | arXiv:2509.19090 | arXiv | 统一医学图像定位和临床推理多模态基础模型，整合检测、分割和结构化推理。 |
| DermFM-Zero | DermFM-Zero: A Vision-Language Foundation Model for Zero-shot Clinical Dermatology | — | 2026 | arXiv:2602.10624 | arXiv Preprint | 皮肤病学视觉-语言基础模型，400万+多模态数据训练，零样本诊断 |
| SkinCLIP-VL | SkinCLIP-VL: Consistency-Aware Vision-Language Learning for Multimodal Skin Cancer Diagnosis | Zhixiang Lu | 2026 | arXiv:2603.21010 | arXiv | 一致性感知的视觉-语言学习模型，用于多模态皮肤癌诊断。 |
| PRISM-MRI | Large-scale Multi-sequence Pretraining for Generalizable MRI Analysis in Versatile Clinical Applications | Zelin Qiu | 2025 | arXiv:2508.07165 | arXiv | PRISM多序列MRI基础模型，在336,476个体积MRI扫描上预训练，覆盖诊断、分割、配准、进展预测和报告生成等任务。 |
| LLaVA-NeXT-Med | LLaVA-NeXT-Med: Medical Multimodal Large Language Model | Yunfei Guo | 2025 | DOI:10.1109/CITSC64390.2025.00092 | CITSC 2025 | 结合LLaVA-NeXT与LLaVA-Med数据预训练和微调的医学多模态大模型，用于医学影像分析与视觉问答。 |
| ChexGen | A Generative Foundation Model for Chest Radiography | Yuanfeng Ji | 2025 | arXiv:2509.03903 | arXiv | 胸部X光合成生成基础模型。 |
| CheXficient | A data- and compute-efficient chest X-ray foundation model | Chong Wang | 2026 | arXiv:2602.22843 | arXiv | 数据高效胸部X光基础模型 |
| Ark+ | A fully open AI foundation model applied to chest radiography | — | 2025 | 10.1038/s41586-025-09079-8 | Nature | 全开放胸部X光AI基础模型(Nature发表) |

---

<a id="medicine-section-02"></a>
## 神经影像

### 综述 Overview

神经影像基础模型专注于脑部MRI和fMRI数据分析，用于脑疾病检测、脑区分割、认知状态解码等神经科学与临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BrainIAC | A Generalizable Foundation Model for Analysis of Human Brain MRI | Noel Vouitsis | 2024 | DOI:10.1038/s41593-026-02202-6 | Nature Neuroscience 2026 | 在近49,000张未标注脑部MRI上自监督预训练的基础模型，学习通用脑表征，支持多种下游临床任务。 |
| GenBrain | GenBrain: A Generative Foundation Model of Multimodal Brain Imaging | Weikang Gong | 2026 | 10.21203/rs.3.rs-8404638/v1 | Research Square | 大规模多模态脑影像生成基础模型，在约120万3D MRI扫描（44,000+个体、34种成像模态）上预训练。 |
| Prima | Learning Neuroimaging Models from Health System-Scale Data | (多作者) | 2026 | DOI:10.1038/s41551-025-01608-0 | Nature Biomedical Engineering 2026 | 密歇根大学开发的大规模AI神经影像基础模型，基于220,000+健康系统MRI研究训练，可在数秒内读取脑部MRI并诊断。 |
| BrainSymphony | BrainSymphony: A Parameter-Efficient Multimodal Foundation Model for Neuroimaging | (多作者) | 2025 | arXiv:2506.18314 | arXiv Preprint | 轻量级、参数高效的多模态神经影像基础模型，整合fMRI时间序列和扩散MRI导出的结构连接。 |
| CytoNet | CytoNet: A Foundation Model for the Human Cerebral Cortex | (多作者) | 2025 | arXiv:2511.01870 | arXiv Preprint | 用于分析人类大脑皮层细胞分辨率的基础模型，在超过100万张未标记组织学图像patch上训练。 |
| BrainLM | BrainLM: A Foundation Model for Brain Activity Recordings | Josue Ortega Caro | 2023 | arXiv:2311.00768 | ICLR 2024 | 在6,700小时fMRI数据上训练的脑活动基础模型，采用自监督掩码预测方法预测年龄、性别等临床变量。 |
| BrainFM | BrainFM: A Modality-Agnostic Multi-task Foundation Model for Human Brain Imaging | (多作者) | 2025 | arXiv:2509.00549 | arXiv Preprint | 模态无关的多任务脑成像基础模型，能跨MRI/fMRI/EEG等多种神经影像模态泛化。 |
| BrainGFM | A Brain Graph Foundation Model: Pre-Training and Prompt-Tuning across Broad Atlases and Disorders | (多作者) | 2026 | OpenReview:PeGHkAaRxs | ICLR 2026 | 利用图对比学习和掩码自编码器处理fMRI数据的脑图基础模型。 |
| BrainFounder | BrainFounder: Towards 3D Foundation Models for Neuroimage Segmentation | Joseph Cox | 2024 | arXiv:2406.10395 | MICCAI 2024 | 在41,400名参与者多模态MRI上预训练的大规模神经影像分割基础模型，采用两阶段预训练策略。 |
| Brain Harmony | Brain Harmony: A Multimodal Foundation Model Unifying Brain Structural Morphology and Functional Dynamics | (多作者) | 2025 | arXiv:2509.24693 | arXiv Preprint | 首个统一脑结构形态（T1-MRI）和功能动态（fMRI）的多模态脑基础模型。 |
| Brain-OF | Brain-OF: An Omnifunctional Foundation Model for fMRI, EEG and MEG | Hanning Guo | 2026 | arXiv:2602.23410 | arXiv | 跨fMRI、EEG和MEG神经影像模态的全功能基础模型。 |
| SAM-Brain3D | Brain Foundation Models with Hypergraph Dynamic Adapter for Brain Disease Analysis | Zhongying Deng | 2025 | arXiv:2505.00627 | arXiv | 在66,000+ MRI图像-标签对（14种子模态）上训练的脑影像基础模型，用于脑疾病分析。 |
| MindLLM | MindLLM: A Subject-Agnostic and Versatile Model for fMRI-to-Text Decoding | Weikang Qiu | 2025 | ICML 2025 Poster #45933 | ICML 2025 | 主体无关的fMRI到文本解码模型，推进脑-计算机接口研究。 |
| Decipher-MR | Decipher-MR: A Vision-Language Foundation Model for 3D MRI Representations | — | 2025 | arXiv:2509.21249 | npj Digital Medicine 2026 | 3D MRI视觉-语言基础模型，训练于>200,000个MRI序列，支持脑部多种疾病分析（含精神疾病） |
| SLIM-Brain | Data-efficient FM for fMRI analysis | — | 2026 | arXiv:2512.21881 | arXiv | 数据高效fMRI分析基础模型 |

---

<a id="medicine-section-03"></a>
## 病理学

### 综述 Overview

病理学基础模型专注于组织病理学全切片图像（WSI）分析，用于癌症检测、生物标志物预测、疾病分类等计算病理学任务。这是SFM最活跃的领域之一。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Virchow | Virchow: A Million-Slide Digital Pathology Foundation Model | Eugene Vorontsov | 2023 | arXiv:2309.07778 | Nature Medicine 2024 | Paige/微软开发的百万切片数字病理基础模型，在150万H&E染色WSI上自监督训练，支持癌症检测和罕见癌识别。 |
| Virchow2 | Virchow2: Scaling Self-Supervised Mixed Magnification Models in Pathology | Eric Zimmermann | 2024 | arXiv:2408.00738 | arXiv | Virchow第二代，包含Virchow2（6.32亿参数）和Virchow2G（18.5亿参数），在混合放大倍率下训练。 |
| UNI | Towards a General-Purpose Foundation Model for Computational Pathology | Richard J. Chen | 2024 | DOI:10.1038/s41591-024-02857-3 | Nature Medicine 2024 | Mahmood Lab开发的通用计算病理基础模型，在10万+WSI上自监督训练，支持20+主要组织类型分析。 |
| UNI2 | UNI2: A Universal Foundation Model for Computational Pathology | Richard J. Chen | 2025 | (更新版) | arXiv Preprint | UNI的升级版，在2亿+病理图像（350,000+切片）上预训练，2025年1月发布。 |
| CONCH | A Visual-Language Foundation Model for Computational Pathology | Ming Y. Lu | 2024 | DOI:10.1038/s41591-024-02856-4 | Nature Medicine 2024 | 首个病理学视觉-语言基础模型(CONtrastive learning from Captions for Histopathology)，在117万+图文对上训练。 |
| TITAN | A Multimodal Whole-Slide Foundation Model for Pathology | (Mahmood Lab) | 2025 | DOI:10.1038/s41591-025-03982-3 | Nature Medicine 2025 | 多模态全切片基础模型，结合335,000+ WSI的视觉自监督学习和病理报告的视觉-语言对齐。 |
| Prov-GigaPath | A Whole-Slide Foundation Model for Digital Pathology from Real-World Data | Hanwen Xu | 2024 | DOI:10.1038/s41586-024-07441-w | Nature 2024 | 微软开发的全切片基础模型，在13亿图像tile（171,000+真实世界切片）上预训练，开源权重。 |
| PLIP | A Visual-Language Foundation Model for Pathology Image Analysis Using Medical Twitter | Zhi Huang | 2023 | DOI:10.1038/s41591-023-02504-3 | Nature Medicine 2023 | 基于CLIP的病理学视觉-语言基础模型，利用医学社交媒体数据（OpenPath数据集）训练。 |
| PathChat | A Foundational Multimodal Vision Language AI Assistant for Human Pathology | Ming Y. Lu | 2023 | arXiv:2312.07814 | Nature 2024 | 多模态病理AI助手，集成1亿张组织学图像训练的视觉编码器和LLM，支持交互式病理分析。 |
| CTransPath | Transformer-Based Unsupervised Contrastive Learning for Histopathological Image Classification | Xiyue Wang | 2022 | DOI:10.1016/j.media.2022.102559 | Medical Image Analysis 2022 | 基于CNN-Swin Transformer混合架构的组织病理学特征提取器，采用自监督对比学习训练。 |
| Hibou | Hibou: A Family of Foundational Vision Transformers for Pathology | Dmitry Nechaev | 2024 | arXiv:2406.05074 | arXiv | HistAI病理学视觉Transformer系列（Hibou-B和Hibou-L），用于细胞检测、组织分类等任务。 |
| Phikon | Scaling Self-Supervised Learning for Histopathology with Masked Image Modeling | Alexandre Filiot | 2023 | 10.1101/2023.07.21.23292757 | medRxiv | Owkin开发的组织病理学自监督基础模型，使用iBOT框架在大规模病理数据上训练。 |
| Phikon-v2 | Phikon-v2, A large and public feature extractor for biomarker prediction | Alexandre Filiot | 2024 | arXiv:2409.09173 | arXiv | Phikon升级版，在4.6亿+病理图像块（55,000+切片、30+癌症类型）上训练，作为大规模公开特征提取器。 |
| H-optimus-0 | H-optimus-0: An Open-Source AI Foundation Model for Pathology | (Bioptimus) | 2024 | (Bioptimus发布) | 商业发布 | 全球最大的开源病理AI基础模型(11亿参数)，在500,000+WSI上训练，由法国初创公司Bioptimus开发。 |
| PathChat+ | A Clinical-Grade Agentic and Generative AI-Driven Copilot for Pathology | (Mahmood Lab) | 2025 | arXiv:2506.20964 | arXiv Preprint | PathChat的临床级升级版，在100万+病理特异性指令样本和550万QA对上训练。 |
| UniBiomed | UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation | Linshan Wu | 2025 | arXiv:2504.21336 | arXiv | 统一生物医学图像解读基础模型，整合多模态LLM和分割模型，支持同时对话和分割。 |
| CHIEF | A pathology foundation model for cancer diagnosis and prognosis prediction | Xiyue Wang | 2024 | DOI:10.1038/s41586-024-07894-z | Nature 2024 | 通用临床组织病理学AI系统，在60,000+WSI（19种解剖部位）上预训练，支持癌症检测、分级和分子标志物预测。 |
| Atlas | Atlas: A Whole-Slide Foundation Model for Computational Pathology | — | 2024 | — | arXiv | 全切片级病理基础模型 |
| MUSK | A Vision-Language Foundation Model for Precision Oncology | Jinxi Xiang | 2024 | DOI:10.1038/s41586-025-08780-8 | Nature 2025 | 精准肿瘤学视觉-语言基础模型，支持多模态癌症诊断和预后预测。 |
| PRISM | Predicting Regulatory Interactions from Single Morphology | — | 2024 | — | Nature Medicine 2024 | 病理学多模态基础模型，整合视觉和分子信息 |
| PathOrchestra | PathOrchestra: A Comprehensive Foundation Model for Computational Pathology | — | 2025 | arXiv:2503.00203 | arXiv | 全面的计算病理基础模型，覆盖多种病理任务 |
| kaiko.ai | Towards Training Large-Scale Pathology Foundation Models | — | 2024 | — | arXiv | 大规模病理基础模型训练，提供多尺度ViT变体 |
| RudolfV | A Foundation Model Connecting Pathology Images and Genomic Sequences | — | 2024 | arXiv:2401.09027 | arXiv | 连接病理图像和基因组序列的基础模型 |
| BEPH | A foundation model for generalizable cancer diagnosis and survival prediction from histopathological images | Zhaochang Yang | 2025 | DOI:10.1038/s41467-025-57587-y | Nature Communications 2025 | 基于BEiT的组织病理基础模型，在1100万未标注病理图像patch上预训练，用于癌症诊断与生存预测。 |
| GPFM | A Generalizable Pathology Foundation Model | — | 2024 | arXiv:2407.18807 | arXiv | 通用病理基础模型，在19万+WSI上训练 |
| mSTAR | Multi-Scale Tissue-Aware Representation | — | 2024 | arXiv:2407.15362 | arXiv | 多尺度组织感知表征学习 |
| HIPT | Hierarchical Image Pyramid Transformer for Whole-Slide Image Analysis | Richard J. Chen | 2022 | arXiv:2206.02647 | CVPR 2022 | 分层图像金字塔Transformer，用于WSI的自监督学习 |
| RetCCL | Retention-based Contrastive Learning for Histopathology | Xiyue Wang | 2022 | DOI:10.1016/j.media.2022.102645 | Medical Image Analysis 2023 | 基于保留的对比学习病理特征提取器 |
| PathoDuet | Foundation Models for Pathological Image Analysis via Self-Supervised Learning | — | 2023 | arXiv:2312.09849 | arXiv | 双尺度自监督病理基础模型 |
| COBRA | Unsupervised Foundation Model-Agnostic Slide-Level Representation Learning | Tim Lenz | 2025 | arXiv:2411.13623 | CVPR 2025 | 利用多个基础模型的tile嵌入进行对比预训练的切片级病理表征学习方法，可生成任务无关的slide表示。 |
| THREADS | Molecular-driven Foundation Model for Oncologic Pathology | Anurag Vaidya | 2025 | arXiv:2501.16652 | arXiv | 多模态肿瘤病理切片级基础模型，在47,171张与基因组/转录组配对的H&E切片上预训练。 |
| MADELEINE | Multimodal ADaptive LEarning with INtegrated Embeddings | — | 2024 | — | arXiv | 多模态自适应病理学习 |
| Lunit-DINO | Benchmarking Self-Supervised Learning on Diverse Pathology Datasets | Mingu Kang | 2023 | 10.1109/cvpr52729.2023.00326 | CVPR 2023 | Lunit基于DINOv2的大规模病理预训练模型。 |
| QuiltNet | Quilt-1M: One Million Image-Text Pairs for Histopathology | Wisdom Ikezogwo | 2023 | arXiv:2306.11207 | NeurIPS 2023 | 100万+病理图文对预训练的视觉-语言模型 |
| Quilt-LLaVA | Visual Instruction Tuning for Histopathology | — | 2024 | arXiv:2312.04746 | arXiv | 病理学视觉指令微调多模态模型 |
| PathGen | PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation | — | 2024 | arXiv:2407.00203 | arXiv | 160万病理图文对生成与预训练 |
| Path Foundation | Domain-specific optimization and diverse evaluation of self-supervised models for histopathology | — | 2023 | arXiv:2310.13259 | Google Research / arXiv | Google开发的病理基础模型 |
| CONCH 1.5 | Task-Agnostic Vision-Language Foundation Model for Pathology | — | 2025 | — | arXiv | CONCH升级版，增强视觉-语言对齐 |
| GigaSSL | Giga-SSL: Self-Supervised Learning for Gigapixel Images | Tristan Lazard | 2023 | — | CVPR Workshops 2023 | 面向病理全切片图像的自监督切片级表示学习方法，从未标注WSI中学习任务无关的gigapixel嵌入。 |
| MUPAD | MUPAD: A Generative Foundation Model for Multimodal Histopathology | — | 2026 | arXiv:2604.03635 | arXiv Preprint | 多模态组织病理学生成基础模型，整合组织学图像、RNA分子谱和临床文本 |
| VISTA-PATH | VISTA-PATH: An interactive foundation model for pathology image segmentation and quantitative analysis | — | 2026 | arXiv:2601.16451 | arXiv Preprint | 交互式病理图像分割与定量分析基础模型，增强临床相关性和准确性 |
| CARE | CARE: A Molecular-Guided Foundation Model with Adaptive Region Modeling for WSI Analysis | — | 2026 | arXiv:2602.21637 | arXiv Preprint | 分子引导的自适应区域建模全切片图像分析基础模型 |
| BRIGHT | BRIGHT: A Collaborative Generalist-Specialist Foundation Model for Breast Pathology | Xiaojing Guo | 2026 | arXiv:2603.03030 | arXiv | 协作式通才-专家乳腺癌理基础模型。 |
| GenBio-PathFM | GenBio-PathFM: A State-of-the-Art Foundation Model for Histopathology | Saarthak Kapse | 2026 | 10.64898/2026.03.17.712534 | bioRxiv | 11亿参数的SOTA组织病理学基础模型，完全基于公开数据训练。 |
| Atlas 2 | State-of-the-art pathology FM trained on 5.5M WSIs | Aignostics/Mayo | 2026 | arXiv:2601.05148 | arXiv | 550万全切片训练的病理学基础模型 |
| LongViT | LongViT: Long-Context Vision Transformer for Pathology | — | 2024 | arXiv:2403.14576 | arXiv Preprint | 长上下文视觉Transformer，直接处理超大尺寸病理全切片图像 |
| Pixel-Mamba | Pixel-Mamba: Efficient Mamba-Based Foundation Model for Computational Pathology | — | 2025 | arXiv | arXiv Preprint | 基于Mamba架构的高效计算病理基础模型，像素级处理 |
| Virchow 2G | Virchow 2G: Scaling Self-Supervised Models to 1.9B Parameters for Pathology | — (Paige/Microsoft) | 2024 | arXiv:2408.00738 | arXiv Preprint | ViT-G架构1.9B参数病理基础模型，在310万WSI上训练（Virchow2系列最大版本） |
| UNI 2-g-preview | UNI 2-g-preview: ViT-G Version of Universal Foundation Model for Computational Pathology | Richard J. Chen (Mahmood Lab) | 2025 | — | Preview Release | UNI2的ViT-G大规模版本预览，进一步扩展计算病理基础模型参数规模 |
| Campanella DINO | Campanella et al. (DINO): Self-Supervised ViT-S for Digital Pathology | — (Thomas Fuchs Lab) | 2024 | — | arXiv Preprint | ViT-S架构，DINOv1自监督训练于42万WSI的病理基础模型 |
| Campanella MAE | Campanella et al. (MAE): Masked Autoencoder ViT-L for Digital Pathology | — (Thomas Fuchs Lab) | 2024 | — | arXiv Preprint | ViT-L架构，MAE自监督训练于42万WSI的病理基础模型 |

---

---

<a id="medicine-section-04"></a>
## 内窥镜与手术

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Endo-FM | Foundation Model for Endoscopy Video Analysis | Zhao Wang | 2023 | arXiv:2306.16741 | MICCAI 2023 | 首个内窥镜视频基础模型，33000+视频自监督预训练 |
| EndoDINO | A Foundation Model for GI Endoscopy | Patrick Dermyer | 2025 | arXiv:2501.05488 | arXiv | 胃肠内窥镜DINOv2基础模型，175万+图像 |
| EndoMamba | Efficient Foundation Model for Endoscopic Videos | Qingyao Tian | 2025 | arXiv:2502.19090 | MICCAI 2025 | Mamba架构高效内窥镜视频基础模型 |
| SurgVISTA | Large-scale self-supervised video foundation model for intelligent surgery | — | 2025 | — | npj Digital Medicine | 大规模手术视频基础模型，3650视频/355万帧 |
| SurgVLP | Learning multi-modal representations for surgical video | — | 2023 | — | MedIA 2025 | 手术视频-语言预训练 |
| SurgLLM | A Versatile Large Multimodal Model for Surgical Video Understanding | — | 2025 | arXiv:2509.00357 | arXiv | 大型多模态手术视频理解 |
| SurgFM / Surg-3M | A Dataset and Foundation Model for Perception in Surgical Settings | — | 2025 | arXiv:2503.19740 | arXiv | 4000+手术视频数据集与基础模型 |
| LEMON | Large-scale Endoscopic Surgical Dataset and Foundation Model | — | 2025 | — | CVPR 2025 | 大规模内窥镜手术基础模型 |
| GSViT | General Surgery Vision Transformer | — | 2024 | arXiv:2403.05949 | arXiv | 通用外科视觉Transformer |
| HecVL | Hierarchical Video-Language Pretraining for Zero-shot Surgical Phase Recognition | Kun Yuan | 2024 | — | MICCAI 2024 | 零样本手术阶段识别 |
| PeskaVLP | Procedure-Aware Surgical Video-language Pretraining | — | 2024 | — | NeurIPS 2024 | 过程感知手术视频-语言预训练 |
| SurgiSAM 2 | A fine-tuned SAM2 for surgical video segmentation | — | 2025 | — | Scientific Reports | SAM2手术场景分割 |
| ZEN | ZEN: A generalizable foundation model for intraoperative understanding across surgical procedures | — | 2026 | arXiv:2602.13633 | arXiv Preprint | 通用术中理解基础模型，实时手术视频分析，跨手术类型泛化 |
| SurgMotion | SurgMotion: A Video-Native Foundation Model for Universal Understanding of Surgical Videos | Jinlin Wu | 2026 | arXiv:2602.05638 | arXiv | 原生视频手术基础模型，直接从视频而非帧级特征学习，用于通用手术视频理解。 |
| Surg-R1 | Surg-R1: A Hierarchical Reasoning Foundation Model for Scalable and Interpretable Surgical Decision Support | — | 2026 | arXiv:2603.12430 | arXiv Preprint | 层次推理手术基础模型，三级推理架构，多中心临床验证 |
| Cosmos-H-Surgical | Cosmos-H-Surgical: NVIDIA Physical AI for Surgical Robotics | (NVIDIA) | 2025 | arXiv:2512.23162 | arXiv | NVIDIA开发的手术机器人物理AI基础模型，基于Cosmos世界模型架构，用于手术场景理解和机器人操作规划。 |
| SurgRec | SurgRec: Surgical Foundation Model via Large-Scale Self-Supervised Video Pretraining | (多作者) | 2025 | — | arXiv Preprint | 大规模自监督手术视频预训练基础模型，在数千小时手术视频上训练，支持多种手术视觉理解任务。 |

---

<a id="medicine-section-05"></a>
## 超声

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| USFM | A universal ultrasound foundation model | Jing Jiao | 2024 | — | MedIA 2024 | 通用超声基础模型，多器官多任务 |
| UltraFedFM | Federated Ultrasound Foundation Model | — | 2024 | arXiv:2411.16380 | npj Digital Medicine | 联邦学习超声基础模型，16机构100万+图像 |
| UltraDINO | Domain-specific Foundation Model for fetal ultrasound | Jakob Ambsdorf | 2025 | — | MICCAI 2025 | 200万胎儿超声DINOv2基础模型 |
| EchoCare | Fully Open Foundation Model for Ultrasound | Hongyuan Zhang | 2025 | arXiv:2509.11752 | arXiv | 全开放超声基础模型，450万图像 |
| OpenUS | Open-Source Foundation Model for Ultrasound | Xiaoyu Zheng | 2025 | arXiv:2511.11510 | arXiv | 全开源超声基础模型，308K+图像 |
| EchoFM | Foundation Model for Echocardiography | — | 2025 | arXiv:2410.23413 | arXiv | 心超基础模型，2000万+图像 |
| EchoApex | General-Purpose Vision Foundation Model for Echocardiography | — | 2024 | arXiv:2410.11092 | arXiv | 通用心超视觉基础模型 |
| EchoCLIP | Vision-language foundation model for echocardiogram | — | 2024 | — | Nature Medicine | 心超视觉-语言基础模型 |
| EchoPrime | Comprehensive echocardiogram evaluation with AI | — | 2025 | — | Nature | 最大心超AI，1200万视频 |
| FetalCLIP | Visual-Language Foundation Model for Fetal Ultrasound | Fadillah Maani | 2025 | arXiv:2502.14807 | arXiv | 胎儿超声视觉-语言基础模型 |
| UltraSam | Foundation Model for Ultrasound Segmentation | Adrien Meyer | 2024 | arXiv:2411.16222 | arXiv | SAM超声分割基础模型 |
| Sonomate | Sonomate: A Fetal Ultrasound Vision-Language Model for Clinical Decision Support | (多作者) | 2025 | — | arXiv Preprint | 胎儿超声视觉-语言模型，整合超声影像和临床文本支持产科决策。 |

---

<a id="medicine-section-06"></a>
## 心电与生理信号

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ECG-FM | Open Electrocardiogram Foundation Model | Kaden McKeen | 2024 | arXiv:2408.05178 | npj Digital Medicine | 开放ECG基础模型，150万ECG |
| ECGFounder | Electrocardiogram Foundation Model on 10M Recordings | — | 2024 | — | NEJM AI | 1070万ECG/150诊断类别 |
| AnyECG | Evolved ECG Foundation Model for Health Profiling | — | 2025 | arXiv:2601.10748 | arXiv | 全面健康画像ECG，1330万ECG |
| MIRA | Medical Time Series Foundation Model | Microsoft | 2025 | arXiv:2506.07584 | NeurIPS 2025 | 医学时间序列基础模型，4540亿token |
| REVE | A Foundation Model for EEG | Yassine El Ouahidi | 2025 | arXiv:2510.21585 | NeurIPS 2025 | EEG基础模型，60000小时/25000受试者 |
| EEGPT | EEG Generalist Foundation Model | — | 2024 | arXiv:2410.19779 | arXiv | EEG自回归预训练基础模型 |
| FoME | A Foundation Model for EEG | — | 2024 | arXiv:2510.21585 | arXiv | EEG基础模型，具有自适应时间-侧向注意力缩放功能，支持头皮和颅内EEG分析。 |
| TinyMyo | Tiny Foundation Model for EMG | — | 2025 | arXiv:2512.15729 | arXiv | 轻量级EMG边缘基础模型 |
| ECG-MoE | ECG-MoE: Mixture-of-Expert Electrocardiogram Foundation Model | Yuhao Xu | 2026 | arXiv:2603.04589 | arXiv | 混合专家ECG基础模型，同时捕获周期性和形态特征以增强心脏诊断。 |
| LAMAE | LAMAE: Foundation Model for Cardiac Time Series via Masked Latent Attention | — | 2026 | arXiv:2603.26475 | arXiv Preprint | 心脏时间序列基础模型，利用ECG结构先验的潜隐注意力掩码自编码器 |
| ECG-Soup | ECG-Soup: Harnessing Multi-Layer Synergy for ECG Foundation Models | Phu X. Nguyen | 2025 | arXiv:2509.00102 | arXiv | 利用多层Transformer协同的ECG基础模型，改善心脏信号表征。 |
| BIOT | BIOT: Biosignal Transformer for Cross-data Learning in the Wild | — | 2024 | NeurIPS 2024 | NeurIPS 2024 | 跨数据集生物信号Transformer，统一处理EEG/ECG/EMG等多种生理信号 |
| LaBraM | LaBraM: Large Brain Model for Learning Generic Representations with Tremendous EEG Data | — | 2024 | ICLR 2024 | ICLR 2024 | 大规模脑电模型，在海量EEG数据上预训练的通用EEG表征学习基础模型 |
| CBraMod | CBraMod: Cross-Brain-Modal Learning for EEG Foundation Models | — | 2025 | arXiv | arXiv Preprint | 跨脑模态学习的EEG基础模型，整合多种EEG范式 |
| NeuroGPT | Neuro-GPT: Towards A Foundation Model for EEG | Wenhui Cui | 2023 | arXiv:2311.03764 | arXiv | 结合EEG编码器和GPT架构的EEG基础模型，用于脑信号理解和生成。 |
| BrainWave | BrainWave: A Brain Signal Foundation Model for Clinical Applications | Zhizhang Yuan | 2024 | arXiv:2402.10251 | arXiv | 脑信号基础模型，在40,000+小时侵入式和非侵入式神经记录上预训练，用于临床应用。 |
| Brant-2 | Brant-2: Foundation Model for Brain Signals | — | 2024 | arXiv | arXiv Preprint | 脑信号基础模型第二代，大规模EEG/iEEG预训练，支持多种脑科学下游任务 |
| S-JEPA | S-JEPA: Self-supervised Joint Embedding Predictive Architecture for EEG | — | 2024 | arXiv | arXiv Preprint | 基于联合嵌入预测架构的自监督EEG表征学习 |
| EEG2Rep | EEG2Rep: Enhancing Self-supervised EEG Representation Through Informative Masking | — | 2024 | arXiv | arXiv Preprint | 信息掩码增强的自监督EEG表征学习方法 |
| MaEEG | MAEEG: Masked Auto-encoder for EEG Representation Learning | Hsiang-Yun Sherry Chien | 2022 | arXiv:2211.02625 | arXiv | EEG数据掩码自编码器，通过重建掩码EEG特征进行自监督脑信号表示学习。 |

---

<a id="medicine-section-07"></a>
## 口腔影像

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DentVFM | Vision Foundation Models for Oral Radiology | — | 2025 | arXiv:2510.14532 | arXiv | 口腔颌面放射学视觉基础模型 |
| DentVLM | Multimodal Vision-Language Model for Dental Diagnosis | — | 2025 | arXiv:2509.23344 | arXiv | 牙科多模态视觉-语言模型 |
| DVCTNet | Adapting Foundation Model for Dental Caries Detection | — | 2025 | arXiv:2508.20813 | arXiv | 双视角龋齿检测 |
| OralGPT-Omni | Versatile dental multimodal large language model | — | 2025 | arXiv:2511.22055 | arXiv | 通用牙科多模态大语言模型 |

---

<a id="medicine-section-08"></a>
## 眼科

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OCTCube | 3D Foundation Model for Optical Coherence Tomography | Zixuan Liu | 2024 | arXiv:2408.11227 | arXiv | 3D OCT基础模型 |
| MIRAGE | Multimodal Foundation Model for Retinal OCT | José Morano | 2025 | arXiv:2506.08900 | npj Digital Medicine | 多模态视网膜OCT基础模型 |
| VisionFM | Multimodal Ophthalmic Vision Foundation Model | Fei Li | 2024 | — | NEJM AI | 340万眼科图像多模态基础模型 |
| EyeFound | Multimodal Generalist Foundation Model for Ophthalmic Imaging | Danli Shi | 2024 | arXiv:2405.11338 | arXiv | 11种模态278万视网膜图像 |
| FLAIR | Foundation Language-Image Model of the Retina | Julio Silva-Rodríguez | 2024 | — | MedIA 2025 | 视网膜视觉-语言基础模型 |
| RET-CLIP | Retinal Image Foundation Model with Clinical Reports | Jiawei Du | 2024 | — | MICCAI 2024 | 临床报告预训练视网膜基础模型 |
| VOLMO | VOLMO: Versatile and Open Large Models for Ophthalmology | Zhenyue Qin | 2026 | arXiv:2603.23953 | arXiv | 开放大规模多功能眼科基础模型，三阶段训练覆盖多种眼科任务。 |
| Dual-IFM | Dual-IFM: Towards Interpretable Foundation Models for Retinal Fundus Images | — | 2026 | arXiv:2603.18846 | arXiv Preprint | 可解释视网膜眼底图像基础模型，局部到全局的可解释性 |
| OCTCube-M | OCTCube-M: A 3D Multimodal OCT Foundation Model for Ophthalmic Disease Diagnosis | (多作者) | 2025 | — | arXiv Preprint | 3D多模态OCT基础模型，OCTCube的升级版，整合多模态眼科数据用于疾病诊断。 |
| EyeFM | EyeFM: A Universal Eyecare Foundation Model | (多作者) | 2025 | — | Nature Medicine | 发表于Nature Medicine的通用眼科基础模型，在大规模多模态眼科数据上预训练，支持多种眼病筛查和诊断。 |
| OVFM | Ophthalmic video foundation model for surgical recognition | — | 2026 | Nature Biomedical Engineering | Nature BME | 眼科视频基础模型用于手术识别导航 |

---

<a id="medicine-section-09"></a>
## 医学文本与NLP

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Med-PaLM | Large Language Models Encode Clinical Knowledge | Karan Singhal | 2023 | 10.1038/s41586-023-06291-2 | Nature | Google首个医学LLM。 |
| Med-PaLM 2 | Towards Expert-Level Medical Question Answering with Large Language Models | Karan Singhal | 2023 | arXiv:2305.09617 | arXiv | 专家级医学问答。 |
| Med-Gemini | Advancing Multimodal Medical Capabilities of Gemini | Lin Yang | 2024 | arXiv:2405.03162 | arXiv | Google多模态医学AI，将Gemini能力扩展到文本、图像和基因组学的临床推理。 |
| PubMedBERT | Domain-specific language model pretraining for biomedical NLP | Yu Gu | 2021 | — | ACL 2021 | PubMed全文预训练的生物医学BERT |
| GatorTron | A large language model for electronic health records | Xi Yang | 2022 | 10.1038/s41746-022-00742-2 | npj Digital Medicine | 90B token临床文本预训练的大规模临床语言模型。 |
| BioGPT | BioGPT: generative pre-trained transformer for biomedical text generation and mining | Renqian Luo | 2022 | 10.1093/bib/bbac409 | Briefings in Bioinformatics | 生物医学文本生成与挖掘GPT模型。 |
| PMC-LLaMA | PMC-LLaMA: toward building open-source language models for medicine | Chaoyi Wu | 2024 | 10.1093/jamia/ocae045 | JAMIA | 在PubMed Central论文与医学教材上适配的开源医学大语言模型。 |
| MedAlpaca | An Open-Source Collection of Medical Conversational AI Models | Tianyu Han | 2023 | arXiv:2304.08247 | arXiv | 开源医学对话AI |
| Meditron | Open medical LLMs adapted from Llama2 | EPFL | 2023 | arXiv:2311.16079 | arXiv | 48B医学文献微调LLaMA2 |
| ClinicalBERT | ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission | Kexin Huang | 2019 | arXiv:1904.05342 | arXiv | 临床笔记BERT。 |
| HuatuoGPT | HuatuoGPT, Towards Taming Language Model to Be a Doctor | — (FreedomIntelligence) | 2023 | arXiv:2305.15075 | EMNLP 2023 Findings | 中文医疗大语言模型，结合ChatGPT蒸馏数据和真实医生数据进行监督微调和RLHF |
| HuatuoGPT-o1 | HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs | Junying Chen | 2024 | arXiv:2412.18925 | ACL 2025 Findings | 医疗复杂推理LLM，通过验证器引导搜索和强化学习提升医学诊断推理能力 |
| ChatDoctor | ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model | — | 2023 | arXiv:2303.14070 | arXiv / PMC | 基于LLaMA微调的医疗对话模型，使用10万条匿名患者-医生对话数据训练 |
| DoctorGLM | DoctorGLM: Fine-tuning your Chinese Doctor is not a Herculean Task | Honglin Xiong | 2023 | arXiv:2304.01097 | arXiv | 基于ChatGLM-6B的中文医疗LLM，使用中文医疗对话数据微调，提供可访问的中文医疗咨询。 |
| BioMistral | BioMistral: A Collection of Open-Source Pretrained Large Language Models for the Medical Domain | — | 2024 | arXiv:2402.10373 | ACL 2024 | 基于Mistral的开源生物医学LLM，在PubMed Central数据上继续预训练 |
| Me-LLaMA | Me-LLaMA: Foundation Large Language Models for Medical Applications | Qianqian Xie (Yale) | 2024 | arXiv:2402.12749 | npj Digital Medicine | 基于LLaMA2的医疗基础LLM（13B/70B），在大规模生物医学和临床数据上继续预训练和指令微调 |
| MMedLM | Towards Building Multilingual Language Model for Medicine | — (MAGIC-AI4Med) | 2024 | arXiv:2402.13963 | Nature Communications | 多语言医疗语言模型，基于MMedC多语言医疗语料库训练，支持跨语言医疗问答 |
| RadEx | RadEx: A Framework for Structured Information Extraction from Radiology Reports | Daniel Reichenpfader | 2024 | arXiv:2406.15465 | arXiv Preprint | 基于LLM的放射报告结构化信息抽取端到端框架 |
| ClinicalMamba | ClinicalMamba: A Generative Clinical Language Model on Longitudinal Clinical Notes | Zhichao Yang | 2024 | arXiv:2403.05795 | arXiv | 基于Mamba架构的生成式临床语言模型，设计用于高效序列建模处理纵向临床笔记。 |
| ChiMed-GPT | ChiMed-GPT: A Chinese Medical Large Language Model with Full Training Regime | — | 2023 | arXiv | arXiv Preprint | 全训练流程的中文医学大语言模型 |
| BioBART | BioBART: Pretraining and Evaluation of A Biomedical Generative Language Model | — | 2022 | arXiv:2204.03905 | BioNLP@ACL 2022 | 生物医学生成语言模型，基于BART架构在PubMed摘要上预训练 |
| ClinicalT5 | ClinicalT5: A Generative Language Model for Clinical Text | — | 2023 | arXiv | EMNLP 2023 Findings | 临床文本生成语言模型，基于T5架构在临床笔记上预训练 |
| KeBioLM | KeBioLM: Improving Biomedical Pretrained Language Models with Knowledge | — | 2021 | arXiv:2104.10344 | BioNLP@ACL 2021 | 知识增强的生物医学预训练语言模型，整合UMLS知识图谱 |
| BioELMo | BioELMo: Probing Biomedical Embeddings from Language Models | — | 2019 | arXiv:1904.02181 | BioNLP@ACL 2019 | 生物医学嵌入探测模型，基于ELMo在PubMed文本上预训练 |
| RadBERT | RadBERT: Adapting Transformer-based Language Models to Radiology | — | 2022 | arXiv:2201.06125 | Radiology: AI 2022 | 放射学领域适配的BERT语言模型 |
| BioBERT | BioBERT: A Pre-trained Biomedical Language Representation Model for Biomedical Text Mining | Jinhyuk Lee | 2020 | arXiv:1901.08746 | Bioinformatics 2020 | 首个生物医学领域BERT，在PubMed和PMC上预训练，广泛用于生物医学文本挖掘 |
| SciBERT | SciBERT: A Pretrained Language Model for Scientific Text | Iz Beltagy | 2019 | arXiv:1903.10676 | EMNLP 2019 | 在114万篇科学论文上预训练的BERT模型，生物医学NLP基础模型 |
| BioLinkBERT | LinkBERT: Pretraining Language Models with Document Links | Yasaman Bahri | 2022 | arXiv:2203.15827 | ACL 2022 | 利用生物医学文献间超链接预训练的BERT，增强知识捕获 |
| MetaReact | MetaReact: A Reaction-Aware Transformer for End-to-End Prediction of Drug Metabolism | — | 2026 | 10.64898/2026.03.14.711529 | bioRxiv | 反应感知Transformer，预测药物代谢途径，将化学反应知识整合到药物代谢建模中。 |

---

<a id="medicine-section-10"></a>
## 医学多模态

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| LLaVA-Med | Large Language-and-Vision Assistant for Biomedicine | Chunyuan Li | 2023 | arXiv:2306.00890 | NeurIPS 2023 | Microsoft生物医学多模态LLM |
| BiomedGPT | Generalist vision-language foundation model for biomedical tasks | Kai Zhang | 2024 | — | Nature Medicine | 通用生物医学VL基础模型，16种任务 |
| XrayGPT | Chest Radiographs Summarization using VL Models | Omkar Thawkar | 2023 | arXiv:2306.07971 | arXiv | 胸片摘要生成 |
| ChatCAD | Interactive Computer-Aided Diagnosis using LLMs | Sheng Wang | 2023 | arXiv:2302.07257 | arXiv | 交互式医学CAD |
| Med-Flamingo | Multimodal Medical Few-shot Learner | Michael Moor | 2023 | arXiv:2307.15189 | ML4H 2023 | 多模态医学少样本学习 |
| PVLens | PVLens: Enhancing Pharmacovigilance Through Automated Label Extraction | Jeffery L Painter | 2025 | arXiv:2503.20639 | arXiv | GSK开发的自动化管线，从FDA药品标签中提取药物不良反应并映射到MedDRA术语。 |
| MedMO | MedMO: Grounding and Understanding Multimodal Large Language Model for Medical Images | Ankan Deria | 2026 | arXiv:2602.06965 | arXiv | 在2600万+多样化医学样本上训练的医学多模态LLM，支持医学图像的定位和理解。 |
| UNIMEDVL | UNIMEDVL: A unified medical multimodal foundation model for clinical diagnosis | — | 2025 | OpenReview | OpenReview | 统一医学多模态基础模型，支持跨模态理解和生成的临床诊断 |
| MeDiM | MeDiM: A medical discrete diffusion model for unified multimodal medical generation | — | 2026 | OpenReview | OpenReview | 医学离散扩散模型，统一多模态医学生成（图像+文本双向翻译） |
| Lingshu | Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning | LASA Team | 2025 | arXiv:2506.07044 | arXiv | 通用多模态医学LLM，支持跨多种医学数据模态的统一理解和推理。 |
| CLEAR | CLEAR: An Auditable Foundation Model for Radiology Grounded in Clinical Concepts | Tianyu Han | 2026 | 10.64898/2026.01.15.26344222 | medRxiv | 可审计放射学基础模型，在约87万胸片-报告对上训练，将预测基于显式临床概念以增强透明度。 |
| GreenRFM | GreenRFM: Toward a resource-efficient radiology foundation model | Yingtai Li | 2026 | arXiv:2603.06467 | arXiv | 资源高效的放射学基础模型，以大幅降低的计算和内存需求达到SOTA性能。 |
| Curia-2 | Curia-2: An advanced radiology foundation model | Raidium | 2026 | arXiv:2604.01987 | arXiv Preprint | 进阶放射学基础模型，增强CT/MRI自监督学习 |
| MediVLM | MediVLM: A Vision Language Model for Radiology Report Generation | Ronast Subedi | 2025 | — | EMNLP 2025 | 放射报告自动生成VLM |
| InfiMed-Foundation | Compute-efficient medical multimodal FM | — | 2025 | arXiv:2509.22261 | arXiv | 计算高效医学多模态基础模型 |

---

<a id="medicine-section-11"></a>
## 电子健康记录

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BEHRT | Transformer for Electronic Health Records | Yikuan Li | 2020 | — | Scientific Reports | BERT用于EHR疾病预测 |
| Med-BERT | Structured EHR Pre-training for Diverse Downstream Tasks | Laila Rasmy | 2021 | — | JAMIA | 结构化EHR预训练 |
| CLMBR | Modeling EHR with Self-Supervised Learning | Ethan Steinberg | 2021 | — | NeurIPS 2021 | 自监督EHR建模 |
| CEHR-BERT | Temporal Patient Representations from EHR | Chao Pang | 2021 | — | ML4H 2021 | 临床事件时序BERT |
| EHRMamba | Foundation Model Integrating Mamba for Clinical | — | 2025 | arXiv:2505.01425 | arXiv | Mamba架构EHR基础模型 |
| MOTOR | Multi-Omics Transformer for EHR | — | 2023 | — | NeurIPS 2023 | 多组学EHR Transformer |
| CEHR-GPT | CEHR-GPT: Generating Electronic Health Records with Chronological Patient Timelines | Chao Pang | 2024 | arXiv:2402.04400 | arXiv | 基于GPT的合成EHR数据生成模型，生成按时间顺序排列的患者时间线，支持隐私保护的数据增强。 |
| Foresight | Foresight: Generative Pretraining on Patient Timelines for Clinical Prediction | (多作者) | 2025 | — | Lancet Digital Health | 发表于Lancet Digital Health的患者时间线生成预训练模型，用于临床事件预测和早期预警。 |
| Panacea | Panacea: A Foundation Model for Clinical Trial Outcome Prediction | (多作者) | 2025 | — | arXiv Preprint | 临床试验结果预测基础模型，整合患者数据和试验设计信息预测临床试验终点。 |
| GENIE-EHR | GENIE: Generative Note Information Extraction for EHR | — | 2025 | arXiv:2501.18435 | arXiv | 临床笔记结构化抽取模型 |

---

<a id="medicine-section-12"></a>
## 核医学

### 综述 Overview

核医学基础模型专注于PET/CT等功能成像数据，用于全身代谢分析、肿瘤检测、器官/病灶分割和报告生成。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SDF-HOLO | A Generalist Foundation Model for Total-body PET/CT Enables Diagnostic Reporting and System-wide Metabolic Profiling | Wei Chen | 2026 | arXiv:2601.12820 | arXiv | 在10,000+患者全身PET/CT数据上训练的多模态基础模型，采用双流架构支持诊断报告和全身代谢分析。 |
| FratMAE | Developing a PET/CT Foundation Model for Cross-Modal Anatomical and Functional Imaging | Yujin Oh | 2025 | arXiv:2503.02824 | arXiv | 双ViT编码器PET/CT跨模态基础模型，用于肿瘤学应用中的功能-解剖联合分析。 |
| SegAnyPET | Developing Foundation Models for Universal Segmentation from 3D Whole-Body Positron Emission Tomography | Yichi Zhang | 2025 | arXiv:2603.11627 | ICCV 2025 | 首个PET图像通用分割基础模型，基于>11,000例PET扫描和60万标注，支持器官和病灶分割 |

---

<a id="medicine-section-13"></a>
## 乳腺影像

### 综述 Overview

乳腺影像基础模型专注于乳腺X线（钼靶）等影像分析，用于乳腺癌筛查、诊断、预后预测和报告生成。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Mammo-CLIP | Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography | Shantanu Ghosh | 2024 | MICCAI 2024 | MICCAI 2024 | 视觉-语言乳腺X线基础模型，基于大规模乳腺X线-报告对训练，提升乳腺癌检测数据效率和鲁棒性 |
| MammoDINO | MammoDINO: Foundation Model for Mammography AI | — (GE HealthCare) | 2026 | GE HealthCare Research | Industry | 基于>140万张乳腺X线图像训练的自监督基础模型，支持乳腺癌筛查和诊断多任务 |
| VersaMammo | A Versatile Foundation Model for AI-enabled Mammogram Interpretation | Fuxiang Huang | 2025 | arXiv:2509.20271 | arXiv | 多功能基础模型，在70万+多机构乳腺X线上训练，支持多种乳腺癌检测和诊断任务。 |
| Mammo-FM | Mammo-FM: Breast-specific foundational model for Integrated Mammographic Diagnosis, Prognosis, and Reporting | Shantanu Ghosh | 2025 | arXiv:2512.00198 | arXiv | 乳腺专用基础模型，在14万+患者和82万图像上训练，统一乳腺X线诊断、预后预测和报告生成。 |
| OMAFound | A Foundation Model for Breast and Lung Cancer Screening Using Non-contrast CT | — | 2026 | Nature Health | Nature Health | 基于>209,000例非增强CT扫描的多癌筛查基础模型，同时检测乳腺癌和肺癌 |

---

<a id="medicine-section-14"></a>
## 肌骨影像

### 综述 Overview

肌骨影像基础模型专注于骨骼、关节等肌肉骨骼系统的X线和MRI分析，用于骨科疾病诊断、关节损伤检测等任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OrthoFoundation | A multimodal vision foundation model for generalizable knee pathology | Kang Yu | 2026 | arXiv:2601.18250 | arXiv | 多模态骨科视觉基础模型，通过自监督对比学习在120万未标注膝部X光和MRI图像上训练，用于可泛化的膝关节病理评估。 |
| OrthoDiffusion | OrthoDiffusion: A Generalizable Multi-Task Diffusion Foundation Model for Musculoskeletal MRI Interpretation | Tian Lan | 2026 | arXiv:2602.20752 | arXiv | 基于扩散的多任务肌骨MRI基础模型，在约16,000未标注膝部MRI上训练，支持分割和分类。 |
| XR-0 | Multi Anatomy X-Ray Foundation Model | Nishank Singla | 2025 | arXiv:2509.12146 | arXiv | 自监督多解剖部位X光基础模型，在115万X光图像上训练，覆盖包括肌骨结构在内的多个解剖区域。 |

---

<a id="medicine-section-15"></a>
## 可穿戴与数字健康

### 综述 Overview

可穿戴与数字健康基础模型专注于可穿戴传感器（加速度计、PPG、ECG等）的多模态生理信号分析，用于健康监测、活动识别和临床预测。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| LSM | Scaling Wearable Foundation Models | — (Google) | 2025 | arXiv:2410.13638 | ICLR 2025 | 大规模可穿戴传感器基础模型，训练于>4000万小时数据（165,000+人），支持多模态生理信号分析 |
| LSM-2 | LSM-2: Learning from Incomplete Wearable Sensor Data | — (Google) | 2025 | arXiv:2506.05321 | ICLR 2025 | LSM升级版，使用自适应和继承掩码（AIM）直接从不完整可穿戴传感器数据学习 |
| NormWear | Toward Foundation Model for Multivariate Wearable Sensing of Physiological Signals | Asif Salekin | 2025 | arXiv:2412.09758 | ICML 2025 | 多模态可穿戴生理信号基础模型（PPG/ECG/EEG/GSR/IMU），通道感知注意力机制 |
| SensorLM | SensorLM: Learning the Language of Wearable Sensors | — (Google) | 2025 | arXiv:2506.09108 | NeurIPS 2025 | 传感器-语言基础模型，训练于约6000万小时可穿戴数据（103,000+人），用自然语言理解传感器数据 |
| WAX-FM | Wearable Accelerometer Foundation Models for Health via Knowledge Distillation | Salar Abbaspourazad | 2024 | arXiv:2412.11276 | arXiv | Apple开发的可穿戴加速度计基础模型，使用PPG到加速度计的知识蒸馏，在2000万分钟未标注数据上训练。 |

---

<a id="medicine-section-16"></a>
## 放射治疗

### 综述 Overview

放射治疗基础模型专注于放疗计划自动化，包括靶区勾画、剂量预测、计划优化等，旨在提升放疗效率和质量。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AIRT | AI End-to-End Radiation Treatment Planning Under One Second | Simon Arberet | 2026 | arXiv:2603.06338 | arXiv | 端到端深度学习框架，在不到1秒内从CT图像生成可交付的前列腺VMAT治疗计划。 |
| DOLA | Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent | Humza Nusrat | 2025 | arXiv:2503.17553 | arXiv | 基于LLaMA 3.1构建的隐私保护LLM智能体，用于无云依赖的自主本地放疗计划优化。 |
| GPT-RadPlan | Automated radiotherapy treatment planning guided by GPT-4Vision | Sheng Liu | 2024 | arXiv:2406.15609 | arXiv | 利用GPT-4Vision多模态推理的全自动放疗计划系统，模拟人类计划员的临床决策过程。 |
| AIRTP | Automating RT Planning at Scale: High Quality Data For AI Training | — | 2025 | arXiv:2501.11803 | Nature Communications | 可扩展的自动化放疗计划管线，自动完成靶区勾画、剂量预测和计划优化全流程 |

---

<a id="medicine-section-17"></a>
## 显微镜

### 综述 Overview

显微镜基础模型涵盖荧光显微镜、电子显微镜和冷冻电镜等非病理学显微成像，用于图像恢复、增强、分割和生物分子结构分析。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FluoResFM | A foundation model for multi-task cross-distribution restoration of fluorescence microscopy images | Qiqi Lu | 2026 | 10.1038/s41467-026-70307-4 | Nature Communications | 多任务荧光显微镜图像恢复基础模型，利用文本先验实现跨分布去噪、反卷积和超分辨率。 |
| FluoGen | FluoGen: An Open-Source Generative Foundation Model for Fluorescence Microscopy Image Enhancement | — | 2026 | Research Square | Preprint | 开源扩散式荧光显微镜基础模型，训练于350万张荧光图像，支持图像增强和分析 |
| MorphGen | MorphGen: Controllable and Morphologically Plausible Generative Cell-Imaging | Berker Demirel | 2025 | arXiv:2510.01298 | arXiv | CZI AI的扩散生成模型，用于多种细胞类型和扰动条件下的可控荧光显微镜细胞成像。 |
| META-SiM | Foundation model for efficient biological discovery in single-molecule time traces | Jieming Li | 2025 | 10.1038/s41592-025-02839-4 | Nature Methods | 基于Transformer的单分子荧光显微镜基础模型，加速时间轨迹的分类、计数和动力学分析。 |
| DF5T | A foundation AI model enhances electron microscopy image analysis | Mengze Du | 2026 | 10.64898/2026.02.28.708664 | bioRxiv | 无监督电子显微镜基础模型，支持五种任务：去噪、去模糊、超分辨率、2D修复和3D各向同性恢复。 |

---

---

<a id="medicine-section-18"></a>
## 睡眠医学

### 综述 Overview

睡眠医学基础模型专注于多导睡眠图（PSG）和可穿戴设备的睡眠数据分析，用于睡眠分期、睡眠障碍诊断等临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SleepFM | SleepFM: A Multi-Modal Foundation Model for Sleep Medicine | (多作者) | 2025 | 10.1038/s41591-025-04133-4 | Nature Medicine | 多模态睡眠基础模型，在大规模PSG数据上预训练，整合EEG、ECG和呼吸信号用于睡眠分期和疾病预测。 |

---

---

<a id="medicine-section-19"></a>
## 兽医学

### 综述 Overview

兽医学基础模型专注于动物医学影像和临床数据分析，用于动物疾病诊断、解剖结构分割等兽医临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| VET-DINO | VET-DINO: Learning Anatomical Understanding in Veterinary Imaging | Andre Dourson | 2025 | arXiv:2505.15248 | arXiv | 自监督兽医影像FM，使用多视图知识蒸馏(Mars Petcare) |

---

<a id="medicine-section-20"></a>
## 法医学

### 综述 Overview

法医学基础模型专注于法医病理学和法医鉴定数据分析，支持死因鉴定、损伤分类等法医学任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SongCi | Large-vocabulary forensic pathological analyses via prototypical cross-modal contrastive learning | Chen Shen | 2025 | 10.1038/s41467-025-62060-x | Nature Communications | 面向法医病理学的视觉-语言基础模型，使用原型跨模态对比学习处理大体发现和全切片图像。 |

---
