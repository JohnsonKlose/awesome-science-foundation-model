# 物理学

<p align="right"><strong>Language:</strong> <a href="physics_en.md">English</a> | 中文</p>

> 覆盖 PDE 求解、流体力学、量子系统、粒子物理、等离子体、光学与科学模拟等物理学基础模型。
> [总览](../README.zh.md)

## 目录
- [粒子物理](#physics-section-01)
- [流体动力学与PDE求解](#physics-section-02)
- [通用物理仿真](#physics-section-03)
- [物理世界模型](#physics-section-04)
- [量子物理与多体系统](#physics-section-05)
- [等离子体物理与聚变](#physics-section-06)
- [光学与光子学](#physics-section-07)
- [结构保持与几何物理ML](#physics-section-08)
- [量子化学与电子结构](#physics-section-09)
- [燃烧模拟](#physics-section-10)
- [核工程](#physics-section-11)
- [参考说明 / Notes](#physics-section-12)

<a id="physics-section-01"></a>
## 粒子物理

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FM4NPP | A Scaling Foundation Model for Nuclear and Particle Physics | Yihui Ren | 2025 | 2508.14087 | ICLR 2026 | 大规模自监督基础模型，针对核物理与粒子物理稀疏探测器数据，训练于1100万+碰撞事件，在sPHENIX等实验中取得SOTA |
| OmniLearn | OmniLearn: A Method to Simultaneously Facilitate All Jet Physics Tasks | Vinicius Mikuni | 2024 | 2404.16091 | arXiv preprint | 多任务喷注物理基础模型，通过多类分类预训练学习通用表征，可同时服务于喷注标记、生成等多个任务 |
| OmniLearned | Foundation Model Framework for All Tasks Involving Jet Physics | Wahid Bhimji | 2025 | 2510.24066 | arXiv preprint | OmniLearn的升级版框架，训练于10亿+喷注事件，引入transformer架构，显著提升喷注分类、回归和生成性能 |
| OmniJet-α | OmniJet-α: The first cross-task foundation model for particle physics | Joschka Birk | 2024 | 2403.05618 | arXiv preprint | 首个跨任务粒子物理基础模型，基于transformer的预训练模型，支持喷注生成和喷注标记多任务 |
| Bumblebee | Bumblebee: Foundation Model for Particle Physics Discovery | Andrew J. Wildridge | 2024 | 2412.07867 | NeurIPS 2024 Workshop | 受BERT启发的粒子物理基础模型，嵌入粒子四动量向量，去除位置编码，捕获生成级和重建级信息 |
| EveNet | EveNet: A Foundation Model for Particle Collision Data Analysis | Ting-Hsiang Hsu | 2026 | 2601.17126 | arXiv preprint | 事件级碰撞数据基础模型，预训练于5亿模拟碰撞事件，采用混合自监督学习，支持多任务分析与生成 |
| HEP-JEPA | HEP-JEPA: A foundation model for collider physics using joint embedding predictive architecture | Jai Bardhan | 2025 | 2502.03933 | arXiv preprint | 基于联合嵌入预测架构(JEPA)的对撞机物理基础模型，用于喷注标记等下游任务，自监督预训练 |
| Particle Transformer (ParT) | Particle Transformer for Jet Tagging | Huilin Qu | 2022 | 2202.03772 | ICML 2022 | 基于transformer的喷注标记架构，引入pairwise粒子相互作用特征，在JetClass大规模数据集上表现优异 |
| PELICAN | Explainable Equivariant Neural Networks for Particle Physics: PELICAN | Alexander Bogatskiy | 2023 | 2307.16506 | JHEP 2024 | 排列等变且Lorentz不变/协变的聚合网络，直接处理四动量向量，可解释性强，用于喷注标记和重建 |
| LorentzNet | An Efficient Lorentz Equivariant Graph Neural Network for Jet Tagging | Shiqi Gong | 2022 | 2201.08187 | JHEP 2022 | 高效Lorentz等变图神经网络，在喷注标记中显式尊重时空对称性，性能优异且计算高效 |
| ParticleNet | ParticleNet: Jet Tagging via Particle Clouds | Huilin Qu | 2019 | 1902.08570 | Phys. Rev. D 2020 | 将喷注视为"粒子云"的图神经网络架构，借鉴点云处理技术(EdgeConv)，用于喷注分类，影响深远 |
| JetCLR | Symmetries, Safety, and Self-Supervision | Barry M. Dillon | 2021 | 2108.04253 | SciPost Phys. 2022 | 基于对比学习的自监督喷注表征框架，利用排列不变transformer编码器和对称性增强，学习物理感知表征 |
| ABCNet | ABCNet: An attention-based method for particle tagging | Vinicius Mikuni | 2020 | 2001.05311 | EPJ Plus 2020 | 注意力增强的图神经网络，将对撞机数据作为点云处理，用于夸克/胶子判别等粒子标记任务 |
| JEDI-net | JEDI-net: a jet identification algorithm based on interaction networks | Eric A. Moreno | 2019 | 1908.05318 | EPJ C 2020 | 基于交互网络的喷注识别深度学习算法，通过粒子对之间的相互作用建模来区分重粒子衰变产生的喷注 |
| CaloFM | Foundation Model for Calorimetry via MoE | — | 2026 | arXiv:2603.28804 | arXiv | MoE量热器模拟基础模型 |
| CaloDREAM | Detector Response Emulation via Attentive Flow Matching | Luigi Favaro | 2024 | arXiv:2405.09629 | SciPost Phys. 2025 | 流匹配高保真量热器快速模拟 |
| JetFormer | Scalable Transformer for Jet Tagging | — | 2026 | arXiv:2601.17215 | arXiv | 可扩展Transformer喷注标记 |
| PanopTag | PanopTag: Simultaneously Tagging All Jets in a Particle Collision Event | Umar Sohail Qureshi | 2026 | 2601.16417 | arXiv preprint | 首个同时标记碰撞事件中所有喷注的方法，采用编码器-解码器transformer架构，利用事件级上下文 |
| GN2 | Transforming jet flavour tagging at ATLAS | ATLAS Collaboration | 2025 | 2505.19689 | Nature Comm. 2026 | ATLAS合作组开发的transformer图神经网络喷注味标记算法，处理底层径迹数据，大幅提升b-jet识别 |
| TrackingBERT | A Language Model for Particle Tracking | Andris Huang | 2024 | 2402.10239 | arXiv preprint | 基于BERT的粒子径迹重建基础模型，将探测器数据标记化处理，用于LHC中的粒子径迹寻找 |

---

<a id="physics-section-02"></a>
## 流体动力学与PDE求解

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Fourier Neural Operator (FNO) | Fourier Neural Operator for Parametric Partial Differential Equations | Zongyi Li | 2020 | 2010.08895 | ICLR 2021 | 开创性的神经算子架构，在傅里叶空间中学习函数映射，分辨率无关，高效求解参数化PDE |
| DeepONet | Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators | Lu Lu | 2021 | DOI:10.1038/s42256-021-00302-5 | Nature Machine Intelligence 2021 | 基于算子万能逼近定理的深度算子网络，通过branch/trunk网络学习连续非线性算子，广泛应用于PDE求解 |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators | Jaideep Pathak | 2022 | 2202.11214 | arXiv preprint | NVIDIA开发的高分辨率全球天气预报模型，基于自适应傅里叶神经算子，0.25°分辨率，可快速生成集合预报 |
| Poseidon | Poseidon: Efficient Foundation Models for PDEs | Maximilian Herde | 2024 | 2405.19101 | NeurIPS 2024 | 高效PDE基础模型，采用多尺度算子transformer与时间条件层归一化，在多物理场流体动力学数据上预训练 |
| MPP | Multiple Physics Pretraining for Physical Surrogate Models | Michael McCabe | 2023 | 2310.02994 | NeurIPS 2024 | 多物理预训练方法，task-agnostic的transformer架构，在多种时空物理系统上自回归预训练，增强泛化能力 |
| ICON / ICON-LM | In-context operator learning with data prompts for differential equation problems | Liu Yang | 2023 | DOI:10.1073/pnas.2310142120 | PNAS 2023 | 上下文算子学习网络，单一模型通过数据提示学习多种PDE的求解算子，无需重新训练，ICON-LM扩展至语言模型微调 |
| VICON | VICON: Vision In-Context Operator Networks for Multi-Physics Fluid Dynamics | Yuxuan Cao | 2024 | 2411.16063 | arXiv preprint | 视觉上下文算子网络，将vision transformer引入多物理场流体动力学预测，处理不可压/可压Navier-Stokes等方程 |
| DPOT | DPOT: Auto-Regressive Denoising Operator Transformer for Large-Scale PDE Pre-Training | Zhongkai Hao | 2024 | 2403.03542 | ICML 2024 | 大规模PDE预训练的自回归去噪算子transformer，基于Fourier attention，处理复杂长程PDE动力学 |
| PROSE-PDE | Towards a Foundation Model for Partial Differential Equations: Multi-Operator Learning and Extrapolation | Jingmin Sun | 2024 | 2404.12355 | Phys. Rev. E 2025 | 多模态PDE基础模型，支持多算子学习与外推，同时预测系统演化和识别底层方程 |
| PROSE-FD | PROSE-FD: A Multimodal PDE Foundation Model for Learning Fluid Dynamics | Jingmin Sun | 2024 | 2409.09811 | arXiv preprint | 面向流体动力学的多模态零样本PDE基础模型，支持浅水方程和Navier-Stokes方程在多种几何条件下的预测 |
| OmniArch | OmniArch: Building Foundation Model for Scientific Computing | Tianyu Chen | 2024 | 2402.16014 | ICML 2025 | 多尺度多物理科学计算基础模型，整合Fourier编解码器架构，支持1D/2D/3D PDE模拟 |
| Unisolver | Unisolver: PDE-Conditional Transformers Are Universal PDE Solvers | Minkai Xu | 2024 | 2405.17527 | NeurIPS 2024 | 通用PDE求解器，基于PDE条件化的Transformer，在多种PDE数据上预训练，利用方程/系数/边界条件信息 |
| PINO | Physics-Informed Neural Operator for Learning Partial Differential Equations | Zongyi Li | 2021 | 2111.03794 | ACM/JCP 2024 | 物理信息神经算子，结合数据驱动与物理约束损失，无需大量标注数据即可学习PDE族的求解算子 |
| PI-MFM | PI-MFM: Physics-informed multimodal foundation model for solving partial differential equations | — | 2024 | 2512.23056 | arXiv preprint | 物理信息多模态基础模型，将物理先验嵌入PDE基础模型，减少对数据的依赖 |
| Walrus | Walrus: A Cross-Domain Foundation Model for Continuum Dynamics | Polymathic AI | 2025 | 2511.15684 | arXiv preprint | 1.3B参数连续介质动力学跨域基础模型，在19个物理系统上预训练，支持流体、固体等多种连续介质仿真 |
| DISCO | DISCO: Distributional Synthesis of Compositional Operators | — | 2025 | — | ICML 2025 | 分布式组合算子合成方法，用于高效PDE求解与泛化 |
| LFNO | Latent Fourier Neural Operator | — | 2024 | — | arXiv preprint | 潜空间傅里叶神经算子，在低维潜空间中执行傅里叶变换，提高计算效率 |
| RNO | Recurrent Neural Operator | — | 2024 | — | arXiv preprint | 递归神经算子，结合递归结构处理时间序列PDE动力学 |
| MINO | Masked Implicit Neural Operator | — | 2024 | — | arXiv preprint | 掩码隐式神经算子，通过掩码策略增强算子学习的泛化能力 |
| TNO | Transolver / Transformer Neural Operator | — | 2024 | — | arXiv preprint | 基于Transformer的神经算子，处理复杂几何和非规则网格上的PDE |
| HyPINO | Hybrid Physics-Informed Neural Operator | — | 2024 | — | arXiv preprint | 混合物理信息神经算子，结合物理约束与数据驱动学习，增强PDE求解精度 |
| PI-Latent-NO | Physics-Informed Latent Neural Operator | — | 2024 | — | arXiv preprint | 物理信息潜空间神经算子，在潜空间中融合物理方程约束进行PDE求解 |
| Transolver | Transolver: A Fast Transformer Solver for PDEs on General Geometries | Wu et al. | 2024 | arXiv:2402.02366 | ICML 2024 | 基于Physics-Attention的Transformer PDE求解器，支持任意几何，多基准SOTA |
| SFNO | Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere | Boris Bonev (NVIDIA) | 2023 | arXiv:2306.03838 | ICML 2023 | 球面傅里叶神经算子，FourCastNet V2的基础架构，用于全球天气预测 |
| WIND | WIND: Weather Inverse Diffusion for Zero-Shot Atmospheric Modeling | — | 2026 | arXiv:2602.03924 | arXiv | 零样本大气建模基础模型 |
| STAR-MD | Scalable Spatio-Temporal SE(3) Diffusion for Long-Horizon Protein Dynamics | Nima Shoghi | 2026 | arXiv:2602.02128 | arXiv | 可扩展SE(3)等变扩散模型模拟蛋白质动力学 |
| MORPH | Shape-agnostic PDE Foundation Models | — | 2025 | arXiv:2509.21670 | ICLR 2026 | 形状无关自回归PDE基础模型 |
| PDEformer-2 | Versatile Foundation Model for 2D PDEs | — | 2025 | arXiv:2507.15409 | arXiv | 通用2D PDE基础模型，编码方程结构为计算图 |
| NESTOR | Nested MOE Neural Operator for Large-Scale PDE Pre-Training | — | 2026 | arXiv:2602.22059 | arXiv | 嵌套MoE神经算子大规模PDE预训练 |

---

<a id="physics-section-03"></a>
## 通用物理仿真

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GPhyT | Towards a Physics Foundation Model | Florian Wiesner | 2025 | 2509.13805 | arXiv preprint | 通用物理transformer，训练于1.8TB多样化仿真数据，可零样本泛化到新物理场景，涵盖流动、对流、冲击波等 |
| PhysiX | PhysiX: A Foundation Model for Physics Simulations | Tung Nguyen | 2025 | 2506.17774 | NeurIPS 2025 | 45亿参数的物理仿真基础模型，采用离散tokenizer编码多尺度物理过程，自回归生成，克服物理数据稀缺 |
| PhysicsNeMo (formerly Modulus) | PhysicsNeMo: An Open-Source Framework for Physics-AI | NVIDIA | 2023– | GitHub: NVIDIA/physicsnemo | NVIDIA (open-source) | NVIDIA开源深度学习框架，用于构建、训练和部署物理信息AI模型，支持GNN/FNO等多种架构，广泛用于工程仿真 |
| PDE-Transformer | PDE-Transformer: Efficient and Versatile Transformers for Physics Simulations | — | 2025 | OpenReview | NeurIPS 2025 | 面向多种PDE类型的可扩展transformer架构，增强正则网格上的代理建模效率 |
| M2PDE | M2PDE: Compositional Generative Multiphysics and Multi-component PDE Simulation | — | 2024 | 2412.04134 | arXiv preprint | 组合生成式多物理/多组分PDE仿真框架，基于扩散模型，处理复杂耦合物理系统 |
| UPS | Unified PDE Solvers | — | 2024 | 2403.07187 | arXiv preprint | 统一PDE求解器基础模型，高效解决跨域、跨维度、跨分辨率的时空PDE，支持多种物理场景 |
| CompNO | CompNO: A Novel Foundation Model approach for solving Partial Differential Equations | Hamda Hmida | 2025 | 2601.07384 | arXiv preprint | 组合式神经算子框架，将单片模型拆分为可组合模块，高效求解参数化PDE |
| GNS | Learning to Simulate Complex Physics with Graph Networks | Alvaro Sanchez-Gonzalez | 2020 | 2002.09405 | ICML 2020 | DeepMind提出的图网络模拟器(GNS)，学习粒子交互规则，可泛化模拟流体、刚体、可变形物体等复杂物理系统 |
| MeshGraphNets | Learning Mesh-Based Simulation with Graph Networks | Tobias Pfaff | 2021 | 2010.03409 | ICLR 2021 | 基于网格的图网络仿真方法，在非结构化网格上学习物理动力学，支持空气动力学和结构力学等 |
| X-MeshGraphNet | X-MeshGraphNet: Scalable Multi-Scale Graph Neural Networks for Physics Simulation | — | 2024 | — | NVIDIA 2024 | NVIDIA提出的多尺度网格图网络，扩展MeshGraphNets至大规模工业物理仿真场景 |
| DHN | Deep Hamiltonian Networks | — | 2025 | — | NeurIPS 2025 | 深度哈密顿网络，在保持能量守恒的结构中学习物理动力学 |
| AI-HAMILTON | AI-HAMILTON: Learning Hamiltonians from Data | — | 2025 | — | NeurIPS 2025 | 从数据中学习哈密顿量的AI框架，结合对称性先验实现物理一致性的动力学建模 |
| GeoPT | Scaling Physics Simulation via Lifted Geometric Pre-Training | Haixu Wu | 2026 | arXiv:2602.20399 | arXiv | 几何预训练物理模拟基础模型 |

---

<a id="physics-section-04"></a>
## 物理世界模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Cosmos | Cosmos World Foundation Model Platform for Physical AI | NVIDIA | 2025 | 2501.03575 | arXiv / NVIDIA | NVIDIA开源世界基础模型平台，生成物理感知视频/世界状态，服务于机器人和自动驾驶等物理AI |
| Genie | Genie: Generative Interactive Environments | Jake Bruce | 2024 | 2402.15391 | ICML 2024 | DeepMind开发的110亿参数无监督世界模型，从未标注视频中学习，可从单张图片生成可交互的虚拟世界 |
| Genie 2 | Genie 2: A large-scale foundation world model | Jack Parker-Holder | 2024 | DeepMind Blog | DeepMind 2024 | Genie的升级版，可从单张图片生成多样化、可操控的交互式3D环境，用于训练和评估具身AI智能体 |
| Genie 3 | Genie 3: A new frontier for world models | Jack Parker-Holder | 2025 | DeepMind Blog | DeepMind 2025 | 通用世界模型，可从文本/图片实时生成一致的交互式3D世界，支持物理一致性和长时间推演 |
| DIAMOND | Diffusion for World Modeling: Visual Details Matter in Atari | Eloi Alonso | 2024 | 2405.12399 | NeurIPS 2024 (Spotlight) | 基于扩散模型的世界建模方法，在Atari环境中实现高视觉保真度的RL智能体训练，保留细节信息 |
| WorldDreamer | WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens | Xiaofeng Wang | 2024 | 2401.09985 | arXiv preprint | 通用世界模型，通过预测掩码token捕获多种环境的物理动力学，支持自然场景和驾驶场景视频生成 |
| GameNGen | Diffusion Models Are Real-Time Game Engines | Dani Valevski | 2024 | 2408.14837 | arXiv preprint (Google) | Google Research开发的神经游戏引擎，利用扩散模型实时模拟复杂游戏环境(DOOM)，20+ fps交互 |
| OASIS | Oasis: A Universe in a Transformer | Decart AI | 2024 | oasis-model.github.io | Decart AI 2024 | 基于transformer和扩散架构的实时开放世界AI模型，在Minecraft类环境中以20fps生成交互式游戏画面 |
| Pandora | Pandora: Towards General World Model with Natural Language Actions and Video States | Jiannan Xiang | 2024 | 2406.09455 | arXiv preprint | 混合自回归-扩散世界模型，通过自然语言动作控制视频状态生成，模拟物理世界的未来状态 |
| UniSim | Learning Interactive Real-World Simulators | Mengjiao Yang | 2023 | 2310.06114 | ICLR 2024 | 通用世界模拟器，学习模拟人与世界的多样交互，可从文本/动作/图像输入生成真实世界仿真 |
| PAN | PAN: A World Model for General, Interactable, and Long-Horizon World Simulation | — | 2025 | 2511.09057 | arXiv preprint | 面向通用、可交互、长时间世界模拟的模型，基于动作条件的高质量视频预测，保持环境动态一致性 |
| PhysDreamer | PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation | Tianyuan Zhang | 2024 | 2404.13026 | ECCV 2024 | 基于物理的3D对象交互生成模型，通过视频生成实现物理一致性的物体交互仿真 |
| PhyRecon | PhyRecon: Physically Plausible Neural Scene Reconstruction | — | 2024 | — | arXiv preprint | 物理合理的神经场景重建方法，结合物理约束实现三维场景的物理一致性重建 |
| Astra | General Interactive World Model with Autoregressive Denoising | — | 2024 | arXiv:2512.08931 | ICLR 2026 | 自回归去噪通用交互世界模型 |

---

<a id="physics-section-05"></a>
## 量子物理与多体系统

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FNQS | Foundation Model for Quantum Many-Body States via Transformers | — | 2025 | — | Nature Communications 2025 | 基于Transformer的量子多体系统基础模型，预训练于大量量子态数据，可泛化到不同哈密顿量和晶格结构 |
| Attention-Based FM for Quantum States | Attention-Based Foundation Model for Quantum States | — | 2025 | — | arXiv preprint | 基于注意力机制的量子态基础模型，利用self-attention捕获量子关联，实现跨体系量子态表征 |
| NOQS | Neural Operator for Quantum States | — | 2026 | — | arXiv preprint | 量子态神经算子，学习量子态空间上的连续映射，用于高效量子模拟和量子态预测 |
| Large Electron Model | Large Electron Model: A Foundation Model for Electron Systems | — | 2026 | — | arXiv preprint | 大电子模型，面向电子系统的基础模型，预训练于大规模电子结构数据，支持多种量子化学和材料物理任务 |
| DysonNet | Constant-Time Local Updates for Neural Quantum States | — | 2026 | arXiv:2603.11189 | arXiv | O(1)局部更新效率的神经量子态 |

---

<a id="physics-section-06"></a>
## 等离子体物理与聚变

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| TokaMind | TokaMind: A Multi-Modal Transformer Foundation Model for Tokamak Plasma | — | 2026 | — | arXiv preprint | 面向托卡马克等离子体的多模态Transformer基础模型，融合多种诊断数据模态，用于等离子体行为预测和聚变控制 |

---

<a id="physics-section-07"></a>
## 光学与光子学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OptoGPT | OptoGPT: A Foundation Model for Inverse Design in Optical Multilayer Thin Film Structures | — | 2023 | — | Opto-Electronic Advances 2024 | 基于GPT架构的光学薄膜逆向设计基础模型，可自动设计光学多层薄膜结构满足目标光谱特性 |
| MOCLIP | MOCLIP: Multi-modal Optical Contrastive Learning for Inverse Photonic Design | — | 2025 | — | arXiv preprint | 多模态光学对比学习模型，结合CLIP框架实现光子结构逆向设计，跨模态关联光学特性与结构参数 |

---

<a id="physics-section-08"></a>
## 结构保持与几何物理ML

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| HNN | Hamiltonian Neural Networks | Sam Greydanus | 2019 | 1906.01563 | NeurIPS 2019 | 开创性的哈密顿神经网络，学习保持哈密顿结构的动力学系统，确保能量守恒 |
| LNN | Lagrangian Neural Networks | Miles Cranmer | 2020 | 2003.04630 | ICLR 2020 Workshop | 拉格朗日神经网络，直接在广义坐标中学习拉格朗日量，自动满足Euler-Lagrange方程 |
| GeoHNNs | Geometric Hamiltonian Neural Networks | — | 2025 | — | arXiv preprint | 几何哈密顿神经网络，将黎曼几何与辛结构融入神经网络，保持物理系统的几何对称性 |
| CGENN | Clifford Group Equivariant Neural Networks | David Ruhe | 2023 | 2305.11141 | NeurIPS 2023 | 基于Clifford代数的群等变神经网络，统一处理旋转、反射和平移对称性，用于物理系统建模 |
| Multivector Neurons | Multivector Neurons: Better and Faster O(n)-Equivariant Clifford Graph Neural Networks | — | 2024 | — | NeurIPS 2024 | 多向量神经元，基于Clifford代数实现更高效的O(n)等变图神经网络，加速几何物理ML |

---

<a id="physics-section-09"></a>
## 量子化学与电子结构

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Skala | Skala: A Foundation Model for Quantum Chemistry | Microsoft Research | 2025 | — | Microsoft 2025 | 微软开发的量子化学基础模型，用于电子结构计算和分子性质预测，支持跨体系泛化 |
| Orbformer | Orbformer: Orbital Transformer for Electronic Structure Prediction | — | 2025 | — | arXiv preprint | 轨道Transformer，基于分子轨道表征预测电子结构，融合物理对称性先验实现高精度预测 |
| OrbEvo | Orbital Transformers for Predicting Wavefunctions in TD-DFT | Chengdong He | 2025 | arXiv:2603.03511 | arXiv | 等变图Transformer预测TD-DFT波函数实时演化 |

---

<a id="physics-section-10"></a>
## 燃烧模拟

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DeepFlame | Deep Learning-Enabled Supercritical Flame Simulation | — | 2025 | arXiv:2508.18969 | arXiv | 开源深度学习燃烧CFD平台，集成ML代理模型进行反应流模拟 |

---

<a id="physics-section-11"></a>
## 核工程

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| NucReactor-FM | Agentic Physical AI toward a Domain-Specific FM for Nuclear Reactor Control | — | 2025 | arXiv:2512.23292 | arXiv | 核反应堆控制领域专用FM，结合物理模拟与强化学习 |

---

<a id="physics-section-12"></a>
## 参考说明 / Notes

- **ArXiv ID** 格式为纯数字编号（如 `2202.03772`），可通过 `https://arxiv.org/abs/<ID>` 访问
- 部分模型为框架/平台（如 PhysicsNeMo、Cosmos），并非单一论文，已标注相应来源
- 世界模型(World Model)类别包含面向物理感知的视频生成和交互式环境模型
- 年份以论文首次公开发表（preprint或正式发表）为准
- 本目录持续更新中，欢迎补充
