# 材料科学

<p align="right"><strong>Language:</strong> <a href="materials-science_en.md">English</a> | 中文</p>

> 覆盖通用原子模型、原子级力场、晶体与材料生成、催化、电池、合金、聚合物等材料科学基础模型。
> [总览](../README.zh.md)

## 目录
- [原子级力场](#materials-science-section-01)
- [晶体与材料性质](#materials-science-section-02)
- [通用原子模型](#materials-science-section-03)
- [晶体生成与逆向设计](#materials-science-section-04)
- [催化剂与表面](#materials-science-section-05)
- [电子结构预测](#materials-science-section-06)
- [聚合物与软物质](#materials-science-section-07)
- [电池与能源材料](#materials-science-section-08)
- [基础GNN架构](#materials-science-section-09)
- [超材料](#materials-science-section-10)
- [超导体](#materials-science-section-11)


<a id="materials-science-section-01"></a>
## 原子级力场

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MACE | MACE: Higher Order Equivariant Message Passing Neural Networks for Fast and Accurate Force Fields | Ilyes Batatia | 2022 | arXiv:2206.07697 | NeurIPS 2022 | 高阶等变消息传递神经网络框架，通过多层原子团簇展开(ACE)实现高精度和高效率的力场计算。 |
| MACE-MP-0 | A Foundation Model for Atomistic Materials Chemistry | Ilyes Batatia | 2023 | arXiv:2401.00096 | J. Chem. Phys. 2025 | MACE框架的预训练基础力场模型，覆盖89种元素，在Materials Project数据上训练，用于通用材料化学模拟。 |
| CHGNet | CHGNet as a pretrained universal neural network potential for charge-informed atomistic modelling | Bowen Deng | 2023 | 10.1038/s42256-023-00716-3 | Nature Machine Intelligence | 预训练通用图神经网络势，包含电荷信息，在Materials Project DFT数据上训练。roject DFT data. |
| M3GNet | A universal graph deep learning interatomic potential for the periodic table | Chi Chen | 2022 | 10.1038/s43588-022-00349-3 | Nature Computational Science | 通用图深度学习原子间势，在Materials Project弛豫数据上训练，覆盖所有周期表元素。vering all periodic table elements. |
| SevenNet | SevenNet: Scalable Graph Neural Network Interatomic Potential | Yutack Park | 2024 | doi:10.1021/acs.jctc.4c00190 | J. Chem. Theory Comput. | 基于NequIP架构的可扩展GNN原子间势，支持LAMMPS并行分子动力学模拟，提供预训练模型。 |
| Orb | Orb: A Fast, Scalable Neural Network Potential | Mark Neumann | 2024 | arXiv:2410.22570 | arXiv | Orbital Materials开发的快速可扩展神经网络势，比现有通用势快3-6倍，同时保持SOTA精度。 potentials while maintaining SOTA accuracy. |
| NequIP | E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials | Simon Batzner | 2022 | 10.1038/s41467-022-29939-5 | Nature Communications | E(3)等变GNN，使用等变卷积代替不变描述符，以最少训练数据实现高精度。 accuracy with minimal training data. |
| Allegro | Learning local equivariant representations for large-scale atomistic dynamics | Albert Musaelian | 2023 | 10.1038/s41467-023-36329-y | Nature Communications | 高可扩展E(3)等变架构，使用局部等变表示支持大规模分子动力学。ge-scale molecular dynamics. |
| Allegro-FM | Allegro-FM: Toward an Equivariant Foundation Model for Exascale Molecular Dynamics Simulations | - | 2025 | arXiv:2502.06073 | J. Phys. Chem. Lett. 2025 | 面向Exascale分子动力学模拟的等变基础模型，基于Allegro架构，覆盖广泛化学空间。 |
| DPA-2 | DPA-2: a large atomic model as a multi-task learner | Duo Zhang | 2024 | 10.1038/s41524-024-01493-2 | npj Computational Materials | 大规模Deep Potential多任务原子模型，跨多种化学和材料系统预训练，支持微调。 systems with fine-tuning support. |
| ANI-1 | ANI-1: an extensible neural network potential with DFT accuracy at force field computational cost | J. S. Smith | 2017 | 10.1039/c6sc05720a | Chemical Science | 开创性可扩展神经网络势，以力场计算成本实现DFT精度，适用于H/C/N/O有机分子。ost for H/C/N/O organic molecules. |
| ANI-2x | Extending the Applicability of the ANI Deep Learning Molecular Potential to Sulfur and Halogens | Christian Devereux | 2020 | doi:10.1021/acs.jctc.0c00121 | J. Chem. Theory Comput. | ANI系列扩展版本，将覆盖元素扩展到S和卤素（F/Cl），支持更广泛有机分子空间。 |
| AIMNet2 | AIMNet2: A Neural Network Potential to Meet Your Neutral, Charged, Organic, and Elemental-Organic Needs | Dylan Anstine | 2024 | doi:10.1039/D4SC08572H | Chemical Science 2025 | 高可迁移性神经网络势，支持中性和带电有机/元素有机分子，覆盖14种元素。 |
| GRACE | Graph Atomic Cluster Expansion for Semilocal Interactions beyond Equivariant Message Passing | — | 2024 | 10.1103/PhysRevX.14.021036 | Phys. Rev. X | 图原子团簇展开通用MLIP框架，覆盖97种元素 |
| Orb-v3 | Orb-v3: atomistic simulation at scale | Benjamin Rhodes | 2025 | arXiv:2504.06231 | arXiv | Orb重大升级版，提升大规模原子模拟的精度和效率。 |
| PET-MAD | PET-MAD as a lightweight universal interatomic potential for advanced materials modeling | — | 2025 | 10.1038/s41467-025-65662-7 | Nature Communications | 轻量级通用原子间势，覆盖全周期表 |
| Grappa | Grappa – a machine learned molecular mechanics force field | — | 2025 | 10.1039/D4SC05465B | Chemical Science | E(3)等变分子力学力场 |

<a id="materials-science-section-02"></a>
## 晶体与材料性质

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CGCNN | Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties | Tian Xie | 2018 | 10.1103/physrevlett.120.145301 | Physical Review Letters | 开创性晶体图卷积神经网络，直接从晶体结构进行可解释的材料属性预测。al properties from crystal structures. |
| MEGNet | Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals | Chi Chen | 2019 | 10.1021/acs.chemmater.9b01294 | Chemistry of Materials | 通用材料图网络，通过全局状态特征支持分子和晶体的属性预测。h global state features. |
| ALIGNN | Atomistic Line Graph Neural Network for improved materials property predictions | Kamal Choudhary | 2021 | 10.1038/s41524-021-00650-1 | npj Computational Materials | NIST原子线图神经网络，显式建模键角，性能超越CGCNN和MEGNet。 MEGNet. |
| MultiMat | Multimodal foundation models for material property prediction and discovery | Viggo Moro | 2025 | 10.1016/j.newton.2025.100016 | Newton | 多模态基础模型，整合晶体结构、态密度、电荷密度和文本，用于全面的材料属性预测。xt for comprehensive materials property prediction. |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | - | 2025 | IBM Research | ICLR 2025 Workshop | IBM大规模SMILES编码器-解码器模型，在PubChem 9100万SMILES上预训练，面向材料和化学应用。 |
| DARWIN 1.5 | DARWIN 1.5: Large Language Models as Materials Science Adapted Learners | Tong Xie | 2024 | arXiv:2412.11970 | arXiv | 开源材料科学LLM，从自然语言输入预测材料属性并促进发现。atural language input. |
| MatBERT | Quantifying the Advantage of Domain-Specific Pre-training on Named Entity Recognition Tasks in Materials Science | Trewartha | 2022 | doi:10.1016/j.patter.2022.100488 | Patterns (Cell Press) | 在材料科学文献上预训练的BERT模型（LBNL），在材料NLP任务（命名实体识别等）上优于通用模型。 |
| MatSciBERT | MatSciBERT: A materials domain language model for text mining and information extraction | Tanishq Gupta | 2022 | 10.1038/s41524-022-00784-w | npj Computational Materials | 在材料科学文献上训练的领域专用BERT，增强文本挖掘和信息抽取。n extraction. |
| MOFTransformer | A multi-modal pre-training transformer for universal transfer learning in metal–organic frameworks | Yeonghun Kang | 2023 | 10.1038/s42256-023-00628-2 | Nature Machine Intelligence | 多模态预训练Transformer，在100万假想MOF上训练，使用原子图和能量网格嵌入进行MOF属性预测。h atomic graph and energy grid embeddings. |
| CrystalFormer | Space group informed transformer for crystalline materials generation | Zhendong Cao | 2025 | 10.1016/j.scib.2025.09.035 | Science Bulletin | 受空间群对称性和Wyckoff位置引导的自回归Transformer，用于晶体材料生成。rials generation. |
| MatInFormer | Materials Informatics Transformer: A Language Model for Interpretable Materials Properties Prediction | Hongshuo Huang | 2023 | arXiv:2308.16259 | arXiv | 利用LLM技术的材料信息学Transformer，用于可解释的材料属性预测。diction. |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | - | 2023 | doi:10.1038/s41467-023-43214-1 | Nature Communications | 知识引导的图Transformer预训练框架，利用化学知识提升分子/材料表示学习质量。 |
| Matformer | Periodic Graph Transformers for Crystal Material Property Prediction | Keqiang Yan | 2022 | arXiv:2209.11807 | NeurIPS 2022 | 周期图Transformer，利用周期性感知的多图注意力机制预测晶体材料性质。 |
| PotNet | Complete and Efficient Graph Transformers for Crystal Material Property Prediction | Keqiang Yan | 2023 | arXiv:2306.10045 | ICLR 2024 | 完备高效的晶体图Transformer，通过原子间势信息实现完备图表示，提升晶体性质预测。 |
| LLM-Prop | LLM-Prop: Predicting Physical And Electronic Properties Of Crystalline Solids From Their Text Descriptions | Andre Niyongabo Rubungo | 2023 | arXiv:2310.14029 | arXiv | 使用大语言模型从文本描述预测晶体的物理和电子属性。iptions. |
| EScAIP | EScAIP: Efficiently Scaled Attention Interatomic Potential | Claudio Zeni | 2025 | arXiv:2411.15019 | ICLR 2025 | 高效缩放注意力原子间势，通过注意力机制实现高精度且可扩展的材料性质预测。 |
| AlloyGPT | End-to-end prediction and design of additively manufacturable alloys | Bo Ni | 2025 | doi:10.1038/s41524-025-01768-2 | npj Computational Materials | 合金设计自回归语言模型 |
| aLLoyM | aLLoyM: a large language model for alloy phase diagram prediction | Yuna Oikawa | 2026 | 10.1038/s41524-026-01966-6 | npj Computational Materials | 用于预测合金相图的大语言模型。 |
| MaskTerial | MaskTerial: a foundation model for automated 2D material flake detection | Jan-Lucas Uslu | 2025 | 10.1039/d5dd00156k | Digital Discovery | 用于自动检测二维材料薄片的基础模型。 |
| CLOUD | CLOUD: A Scalable and Physics-Informed Foundation Model for Crystal Representation Learning | — | 2026 | 10.5281/zenodo.17666827 | Zenodo | 可扩展物理信息晶体表示基础模型，600万+晶体结构训练 |
| LLaMat | A family of large language models for materials research with insights into model adaptability in continued pretraining | — | 2026 | 10.1038/s42256-026-01199-8 | Nature Machine Intelligence | 材料科学大语言模型家族 |

<a id="materials-science-section-03"></a>
## 通用原子模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| UMA | UMA: A Family of Universal Models for Atoms | Brandon M. Wood | 2025 | arXiv:2506.23971 | NeurIPS 2025 | Meta FAIR开发的通用原子模型家族，在超过5亿3D原子结构上训练，覆盖分子、材料、催化剂等多化学领域。 |
| Zatom-1 | Zatom-1: A Multimodal Flow Foundation Model for 3D Molecules and Materials | Alex Morehead | 2026 | arXiv:2602.22251 | arXiv | 开源多模态流基础模型，统一3D分子和材料的生成与预测。 materials. |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Alexius Wadell | 2025 | arXiv:2510.18900 | arXiv | 大规模分子基础模型家族（分子洞察SMILES Transformer），预测400+结构-属性关系。+ structure-property relationships. |
| MatterSim | MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures | Han Yang | 2024 | arXiv:2405.04967 | arXiv | 微软深度学习原子模型，覆盖所有元素，温度0-5000K，压力0-1000GPa。 |
| GNoME | Scaling deep learning for materials discovery | Amil Merchant | 2023 | 10.1038/s41586-023-06735-9 | Nature | Google DeepMind GNN材料探索器，发现220万种新稳定无机晶体结构。 |
| JMP | From Molecules to Materials: Pre-training Large Generalizable Models for Atomic Property Prediction | Nima Shoghi | 2024 | arXiv:2310.16802 | ICLR 2024 | Meta FAIR的联合多域预训练策略，在约1.2亿原子系统上监督预训练，跨越分子、材料等多化学域。 |
| ATOMICA | Learning Universal Representations of Intermolecular Interactions with ATOMICA | — | 2025 | doi:10.1101/2025.04.02.646906 | bioRxiv Preprint | Zitnik Lab开发的几何深度学习模型，学习分子间相互作用的通用原子级表示 |
| eSEN | Efficient Scalable Equivariant Networks | Meta FAIR | 2025 | arXiv:2501.02063 | arXiv | 可扩展等变架构，UMA的基础，在分子/材料基准上达到SOTA |

<a id="materials-science-section-04"></a>
## 晶体生成与逆向设计

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CDVAE | Crystal Diffusion Variational Autoencoder for Periodic Material Generation | Tian Xie | 2022 | arXiv:2110.06197 | ICLR 2022 | 晶体扩散变分自编码器，结合扩散过程和VAE生成周期性晶体结构，首个端到端稳定晶体生成模型。 |
| DiffCSP | Crystal Structure Prediction by Joint Equivariant Diffusion | Rui Jiao | 2023 | arXiv:2309.04475 | NeurIPS 2023 | 联合等变扩散模型用于晶体结构预测，同时扩散原子坐标和晶格参数，实现高精度CSP。 |
| SyMat | Towards Symmetry-Aware Generation of Periodic Materials | Youzhi Luo | 2023 | arXiv:2307.02554 | NeurIPS 2023 | 对称性感知的周期性材料生成模型，显式利用空间群对称性约束生成过程。 |
| MatterGen | MatterGen: A Generative Model for Inorganic Materials Design | Claudio Zeni | 2024 | arXiv:2312.03687 | Nature 2025 | 微软开发的扩散生成模型，可按化学、对称性和性质约束逆向设计无机晶体材料。 |
| Crystal-GFN | Crystal-GFN: sampling crystals with desirable properties and constraints | Mila AI4Science | 2023 | arXiv:2310.04925 | arXiv | 基于GFlowNet的晶体采样框架，在属性和成分约束下高效探索晶体空间。 composition constraints. |
| FlowMM | FlowMM: Generating Materials with Riemannian Flow Matching | Benjamin Kurt Miller | 2024 | arXiv:2406.04713 | ICML 2024 | 利用黎曼流匹配在晶体流形上生成材料结构，实现几何感知的高效晶体生成。 |
| FlowLLM | FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions | Pauli Virtanen | 2024 | arXiv:2410.23405 | NeurIPS 2024 | 将LLM作为基分布与流匹配结合，利用LLM的化学先验知识提升晶体生成质量。 |
| CrystalFlow | CrystalFlow: A Flow-Based Generative Model for Crystalline Materials | Tai D. Nguyen | 2024 | arXiv:2412.12345 | Nature Communications 2025 | 基于流的晶体材料生成模型，通过归一化流实现高保真度的晶体结构生成。 |
| WyckoffDiff | WyckoffDiff: Diffusion in the Wyckoff Space for Crystal Structure Generation | Filip Ekström Kelvinius | 2025 | arXiv:2502.xxxxx | ICML 2025 | 在Wyckoff位置空间进行扩散的晶体生成模型，通过对称性感知表示提升结构有效性。 |
| MatterGPT | MatterGPT: A Generative Transformer for Multi-Property Inverse Design of Solid-State Materials | Yan Chen | 2024 | arXiv:2408.07608 | arXiv | 自回归Transformer，支持固态材料的多属性条件逆向设计。ials. |
| CrystaLLM | CrystaLLM: Large Language Model for Crystallography | - | 2024 | doi:10.1038/s41467-024-54639-7 | Nature Communications 2024 | 利用大语言模型直接从CIF文本生成晶体结构，无需显式几何编码。 |
| UniMat | Scalable Diffusion for Materials Generation | Sherry Yang | 2024 | arXiv:2311.09235 | ICLR 2024 | 可扩展的晶体材料扩散生成模型，通过统一表示支持不同规模的晶体结构生成。 |
| DAO-G / DAO-P | Siamese Foundation Models for Crystal Structure Prediction | Liming Wu | 2025 | arXiv:2503.10471 | arXiv | 孪生预训练框架：DAO-G用于晶体生成，DAO-P用于属性预测。 |
| MOFGPT | Transformer-based generative model for de novo MOF design | — | 2025 | arXiv:2506.00198 | arXiv | 金属有机框架从头设计Transformer生成模型 |
| Matra-Genoa | Autoregressive generative material Transformer | — | 2025 | 10.1038/s41524-025-01940-8 | npj Computational Materials | 自回归材料生成Transformer |

<a id="materials-science-section-05"></a>
## 催化剂与表面

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AdsorbML | AdsorbML: A Leap in Efficiency for Adsorption Energy Calculations using Generalizable Machine Learning Potentials | Janice Lan | 2023 | doi:10.1038/s41524-023-01121-5 | npj Computational Materials | 通用ML势用于吸附能高效计算，结合OC20预训练模型显著加速催化剂筛选流程。 |
| CatBERTa | CatBERTa: A RoBERTa-based Catalyst Property Prediction Model | - | 2023 | arXiv:2305.08628 | arXiv preprint | 基于RoBERTa的催化剂性质预测模型，从催化剂文本描述进行吸附能和活性预测。 |
| eSCN | Reducing SO(3) Convolutions to SO(2) for Efficient Equivariant GNNs | Larry Zitnick | 2023 | arXiv:2302.03655 | ICML 2023 | 高效等变球面通道网络，将SO(3)卷积降维为SO(2)操作，大幅提升计算效率同时保持精度。 |
| SCN | Spherical Channels for Modeling Atomic Interactions | Larry Zitnick | 2022 | arXiv:2206.14331 | NeurIPS 2022 | 球面通道网络，使用球谐函数通道建模原子相互作用，在OC20催化任务上取得优异表现。 |
| EquiformerV2 | EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations | Yi-Lun Liao | 2023 | arXiv:2306.12059 | ICLR 2024 | 改进的等变Transformer架构，支持更高阶表示，在OC20/OC22催化基准上达到SOTA。 |
| eqV2 | Improved EquiformerV2 for OC20/OC22 | Meta FAIR | 2024 | arXiv:2401.13013 | arXiv | 改进的EquiformerV2，用于Open Catalyst数据集的通用原子性质预测 |
| CatDRX | Reaction-conditioned generative model for catalyst design and optimization with CatDRX | — | 2025 | 10.1038/s42004-025-01732-7 | Communications Chemistry | 反应条件化催化剂设计生成模型 |

<a id="materials-science-section-06"></a>
## 电子结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DeepH | Deep-learning density functional theory Hamiltonian for efficient ab initio electronic-structure calculation | He Li | 2022 | 10.1038/s43588-022-00265-6 | Nature Computational Science | 深度学习模型，直接预测DFT哈密顿矩阵，加速从头算电子结构计算。ic structure calculations. |
| DeepH-E3 | DeepH-E3: E(3)-Equivariant Deep Learning for Efficient ab initio Electronic Structure | Xiaoxun Gong | 2023 | doi:10.1038/s41467-023-38468-8 | Nature Communications | DeepH的E(3)-等变版本，利用等变神经网络更准确高效地预测哈密顿量矩阵元素。 |
| HamGNN | HamGNN: Graph Neural Networks for Predicting Hamiltonian Matrix | Zijie Yang | 2023 | arXiv:2305.10844 | arXiv preprint | 用于哈密顿矩阵预测的图神经网络，通过等变消息传递直接预测DFT精度的电子结构。 |
| NextHAM | NextHAM: Next-Generation Hamiltonian Prediction with Equivariant Graph Neural Networks | - | 2024 | arXiv:2405.xxxxx | arXiv preprint | 新一代哈密顿量预测模型，改进等变GNN架构实现更大规模材料体系的电子结构预测。 |
| MACE-H | Equivariant electronic Hamiltonian prediction with many-body message passing | — | 2026 | 10.1038/s41524-026-02020-1 | npj Computational Materials | 基于MACE的等变电子哈密顿量预测 |

<a id="materials-science-section-07"></a>
## 聚合物与软物质

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| polyBERT | polyBERT: a chemical language model to enable fully machine-driven ultrafast polymer informatics | Christopher Kuenneth | 2023 | 10.1038/s41467-023-39868-6 | Nature Communications | 基于BERT的化学语言模型，在聚合物SMILES上训练，用于超快速聚合物属性预测。on. |
| polyGNN | polyGNN: Multitask Graph Neural Networks for Polymer Informatics | Rishi Gurnani | 2023 | doi:10.1021/acs.chemmater.2c02991 | Chemistry of Materials | 多任务图神经网络用于聚合物信息学，支持多性质同时预测和聚合物结构-性质关系学习。 |
| polyBART | polyBART: A Generative Transformer for Polymer Design | - | 2024 | arXiv:2404.xxxxx | arXiv preprint | 基于BART的聚合物生成Transformer，支持条件生成和性质导向的聚合物逆向设计。 |
| POLYT5 | POLYT5: an encoder-decoder foundation chemical language model for generative polymer design | — | 2026 | 10.1038/s44387-026-00087-1 | npj Artificial Intelligence | T5编码器-解码器聚合物设计基础语言模型 |

<a id="materials-science-section-08"></a>
## 电池与能源材料

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BatteryBERT | BatteryBERT: A Pretrained Language Model for Battery Research | Shu Huang | 2022 | doi:10.1021/acs.jcim.2c00035 | J. Chem. Inf. Model. | 电池研究领域预训练语言模型，在电池文献语料上微调BERT，支持电池文本挖掘和信息提取。 |
| BatteryFormer | BatteryFormer: Graph Transformer for Battery Material Property Prediction | - | 2024 | arXiv:2404.xxxxx | arXiv preprint | 面向电池材料的图Transformer模型，预测电极材料容量、电压和循环寿命等关键性质。 |

<a id="materials-science-section-09"></a>
## 基础GNN架构

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SchNet | SchNet: A Continuous-Filter Convolutional Neural Network for Modeling Quantum Interactions | Kristof Schütt | 2017 | arXiv:1706.08566 | NeurIPS 2017 | 连续滤波卷积神经网络，开创性地将原子间距离编码为连续表示，建模量子相互作用。 |

<a id="materials-science-section-10"></a>
## 超材料

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MetaFO | Toward a robust and generalizable metamaterial foundation model | Namjung Kim | 2025 | 10.1038/s41524-025-01925-7 | npj Computational Materials | 贝叶斯Transformer超材料基础模型，用于零样本结构-属性预测。 |

<a id="materials-science-section-11"></a>
## 超导体

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BEE-NET | Developing a complete AI-accelerated workflow for superconductor discovery | Jason B. Gibson | 2026 | 10.1038/s41524-026-01964-8 | npj Computational Materials | 等变GNN，预测Eliashberg谱函数和临界温度，用于超导体发现。r discovery. |
| DeeperBand | A deep learning approach to search for superconductors from electronic bands | — | 2025 | doi:10.1088/3050-287X/adf6cb | IOPscience | 对称感知3D Vision Transformer，从电子能带结构预测超导性 |
