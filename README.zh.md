# Awesome 科学基础模型 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="right"><strong>Language:</strong> <a href="README.md">English</a> | 中文</p>

一份全面的中英双语指南，收录驱动下一轮科学突破的 **1,000+ 基础模型**——横跨九大学科领域，从蛋白质设计到天气预测。跨学科模型在所有相关领域均有收录。

## 目录

- [生命科学](#生命科学)
- [化学](#化学)
- [材料科学](#材料科学)
- [物理学](#物理学)
- [地球科学](#地球科学)
- [天文学](#天文学)
- [医学与生物医学](#医学与生物医学)
- [数学与科学推理](#数学与科学推理)
- [农业与生态](#农业与生态)

## 生命科学

> [英文](life-sciences/life-sciences_en.md) | [中文](life-sciences/life-sciences_zh.md)

### 目录
- [蛋白质](#life-sciences-section-01)
- [RNA](#life-sciences-section-02)
- [DNA与基因组](#life-sciences-section-03)
- [单细胞](#life-sciences-section-04)
- [多尺度生物学](#life-sciences-section-05)
- [抗体与免疫](#life-sciences-section-06)
- [酶工程](#life-sciences-section-07)
- [空间转录组](#life-sciences-section-08)
- [糖链](#life-sciences-section-09)
- [代谢组学](#life-sciences-section-10)
- [冷冻电镜](#life-sciences-section-11)
- [宏基因组](#life-sciences-section-12)
- [系统发育](#life-sciences-section-13)
- [多组学整合](#life-sciences-section-14)
- [表观基因组](#life-sciences-section-15)
- [质谱](#life-sciences-section-16)
- [神经科学](#life-sciences-section-17)
- [合成生物学](#life-sciences-section-18)

<a id="life-sciences-section-01"></a>
### 蛋白质

#### 蛋白质语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ESM-1b | Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences | Alexander Rives | 2021 | 10.1073/pnas.2016239118 | PNAS | 大规模无监督蛋白质语言模型，在2.5亿蛋白质序列上训练，捕获进化多样性和生物学特性 |
| ESM-2 | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 150亿参数蛋白质语言模型，支持从单序列进行原子级结构预测（ESMFold）。 |
| ESM3 | Simulating 500 million years of evolution with a language model | Thomas Hayes | 2025 | 10.1126/science.ads0018 | Science | 多模态蛋白质生成模型，联合处理序列、结构和功能信息，模拟5亿年进化过程。 |
| ESMFold | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 基于ESM-2的单序列蛋白质结构预测方法，比AlphaFold2快约60倍。 |
| ESM Cambrian (ESMC) | ESM Cambrian: Revealing the mysteries of proteins with unsupervised learning | — | 2024 | — | EvolutionaryScale | 新一代ESM蛋白质语言模型，在多种蛋白质理解和生成任务上显著超越ESM-2 |
| ProtTrans | ProtTrans: Toward understanding the language of life through self-supervised learning | Ahmed Elnaggar | 2021 | 10.1109/TPAMI.2021.3095381 | IEEE TPAMI | 大规模蛋白质预训练模型套件(含ProtBERT、ProtXLNet、ProtT5等)，在3930亿氨基酸上训练 |
| ProteinBERT | ProteinBERT: a universal deep-learning model of protein sequence and function | Nadav Brandes | 2022 | 10.1093/bioinformatics/btac020 | Bioinformatics | 通用蛋白质模型，在序列和GO注释上联合预训练，支持多种蛋白质属性预测。 |
| ProtGPT2 | ProtGPT2 is a deep unsupervised language model for protein design | Noelia Ferruz | 2022 | 10.1038/s41467-022-32007-7 | Nature Communications | 基于GPT-2的蛋白质序列生成模型，生成类似于天然蛋白质的新序列。 |
| ProGen | Large language models generate functional protein sequences across diverse families | Ali Madani | 2023 | 10.1038/s41587-022-01618-2 | Nature Biotechnology | Salesforce开发的大规模蛋白质语言模型，在2.8亿序列上训练，生成功能性人工蛋白质。 |
| ProGen2 | ProGen2: Exploring the boundaries of protein language models | Erik Nijkamp | 2023 | 10.1016/j.cels.2023.10.002 | Cell Systems | 64亿参数蛋白质语言模型，在基因组、宏基因组和蛋白质家族数据上训练。 |
| ProGen3 | Scaling Unlocks Broader Generation and Deeper Functional Understanding of Proteins | Aadyot Bhatnagar | 2025 | 10.1101/2025.04.15.649055 | bioRxiv | 稀疏混合专家蛋白质生成模型，在1.5万亿token上训练，用于增强蛋白质设计。 |
| SaProt | SaProt: Protein language modeling with structure-aware vocabulary | Jingjing Gong | 2024 | ICLR 2024 | ICLR 2024 (Spotlight) | 结构感知蛋白质语言模型，利用Foldseek将3D结构编码为离散token与序列联合训练 |
| xTrimoPGLM | xTrimoPGLM: Unified 100B-scale pre-trained transformer for deciphering the language of protein | Bo Chen | 2025 | 10.1038/s41592-025-02636-z | Nature Methods | 1000亿参数统一蛋白质语言模型，同时支持蛋白质理解和生成任务 |
| Ankh | Ankh: Optimized protein language model unlocks general-purpose modelling | Ahmed Elnaggar | 2023 | arXiv:2301.06568 | arXiv Preprint | 优化的蛋白质语言模型，强调训练效率，以更少资源达到竞争性能 |
| ProCyon | ProCyon: A multimodal foundation model for protein phenotypes | — | 2024 | bioRxiv:2024.12.10.627665 | bioRxiv | 多模态蛋白质基础模型，整合序列、结构和自然语言数据预测蛋白质表型 |
| ProSST | ProSST: Protein language modeling with quantized structure and disentangled attention | — | 2024 | doi:10.52202/079017-1126 | NeurIPS 2024 | 结合氨基酸序列与量化3D结构信息的蛋白质语言模型 |
| InstructPLM | InstructPLM: Aligning protein language models to follow protein design instructions | — | 2024 | arXiv:2510.03370 | arXiv | 通过指令微调ESM2，在蛋白质设计任务上超越ESM3 |
| UniRep | Unified rational protein engineering with sequence-based deep representation learning | Alley et al. | 2019 | doi:10.1038/s41592-019-0598-1 | Nature Methods | 基于RNN的蛋白质语言模型，用于统一表征学习和理性蛋白质工程。 |
| MSA Transformer | MSA Transformer | Rao et al. | 2021 | doi:10.1101/2021.02.12.430858 | ICML 2021 | 在多序列比对上运行的Transformer模型，用于改进蛋白质建模。 |
| EVE | Disease variant prediction with deep generative models of evolutionary data | Jonathan Frazer | 2021 | 10.1038/s41586-021-04043-8 | Nature | 进化变分自编码器，从蛋白质家族数据预测致病遗传变异。 |
| Tranception | Protein fitness prediction with autoregressive transformers and inference-time retrieval | Notin et al. | 2022 | arXiv:2205.13760 | ICML 2022 | 带检索时比对上下文的自回归语言模型，用于蛋白质适应性预测。 |
| RITA | RITA: a Study on Scaling Up Generative Protein Sequence Models | Hesslow et al. | 2022 | arXiv:2205.05789 | Preprint | 自回归蛋白质生成模型的缩放研究，参数量达12亿。 |
| ProtSSN | Semantical and Geometrical Protein Encoding for Zero-Shot Engineering | — | 2024 | eLife 2024 | eLife | 结构加序列去噪预训练框架，用于零样本蛋白质工程。 |
| ProLLaMA | ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing | Lv et al. | 2024 | arXiv:2402.16445 | IEEE 2025 | 基于LLaMA架构的多任务蛋白质大语言模型，用于多种蛋白质语言处理任务。 |
| ProTrek | ProTrek: Navigating the Protein Universe through Tri-Modal Contrastive Learning | Su et al. | 2024 | doi:10.1038/s41587-025-02836-0 | Nature Biotechnology | 通过对比学习联合建模序列、结构和功能的三模态蛋白质模型。 |
| ProtWord | ProtWord: A Discrete Protein Language Model for Functional Discovery and De Novo Design | — | 2026 | github | Preprint | 1.5亿参数的离散蛋白质语言模型，将序列翻译为8,192词元词汇表用于功能发现。 |
| ProtLLM | ProtLLM: An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training | Le Zhuo | 2024 | 10.18653/v1/2024.acl-long.484 | ACL 2024 | 交错蛋白质-语言大模型，具有动态蛋白质挂载机制。 |
| ProtHyena | Hyena architecture enables fast and efficient protein language modeling | Yiming Zhang | 2025 | 10.1002/imo2.45 | iMetaOmics | 快速Hyena架构蛋白质语言模型，利用隐式卷积实现高效序列处理。 |
| DPLM | Diffusion Language Models Are Versatile Protein Learners | Wang et al. | 2024 | arXiv:2402.18567 | ICML 2024 | 基于扩散的语言模型，用于多功能蛋白质序列生成和理解。 |
| PTM-Mamba | PTM-Mamba: a PTM-aware protein language model with bidirectional gated Mamba blocks | Fred Zhangzhi Peng | 2025 | 10.1038/s41592-025-02656-9 | Nature Methods | 具有双向门控Mamba块的状态空间模型，用于翻译后修饰感知的蛋白质表示。 |
| DeepSequence | Deep generative models of genetic variation capture the effects of mutations | Adam J. Riesselman | 2018 | 10.1038/s41592-018-0138-4 | Nature Methods | 对齐蛋白质家族上的变分自编码器，用于预测突变效应。 |
| PoET | PoET: A generative model of protein families as sequences-of-sequences | Timothy F. Truong Jr | 2023 | arXiv:2306.06156 | NeurIPS 2023 | 具有检索功能的序列的序列家族建模框架，用于蛋白质适应性预测。 |
| Prot2Text | Prot2Text: Multimodal Protein's Function Generation with GNNs and Transformers | — | 2024 | doi:10.1609/aaai.v38i10.28948 | AAAI 2024 | 从结构和序列生成蛋白质功能自然语言描述的多模态模型。 |
| PAIR | Boosting the predictive power of protein representations with a corpus of text annotations | Haonan Duan | 2025 | 10.1038/s42256-025-01088-6 | Nature Machine Intelligence | 通过整合文本注释语料库增强蛋白质表示的方法。 |
| MULAN | MULAN: multimodal protein language model for sequence and structure encoding | Daria Frolova | 2024 | 10.1093/bioadv/vbaf117 | Bioinformatics Advances | 多模态蛋白质编码器，联合建模序列和结构信息。 |
| ProteinSage | ProteinSage: From implicit learning to explicit structural constraints for efficient protein language modeling | Lingdong Shen | 2026 | 10.64898/2026.03.17.712034 | bioRxiv | 蛋白质语言模型，结合隐式学习和显式结构约束以提升效率。 |
| OneProt | OneProt: Towards Multi-Modal Protein Foundation Models | Klemens Flöge | 2024 | arXiv:2411.04863 | arXiv | 多模态蛋白质基础模型，整合结构、序列、文本和结合位点数据。 |
| ECNet | ECNet: Evolutionary context-integrated neural network for protein engineering | — | 2022 | 10.1038/s41467-022-29076-z | Nature Communications | 整合进化上下文的深度学习框架，用于蛋白质工程和适应性预测。 |
| PoET-2 | Understanding protein function with a multimodal retrieval-augmented foundation model | (OpenProtein.AI) | 2025 | arXiv:2508.04724 | arXiv | 下一代检索增强多模态蛋白质家族模型，相比PoET改善适应性预测。 |
| FlexRibbon | FlexRibbon: Foundation Model for Flexible Protein Representation | — | 2025 | — | Preprint | 灵活蛋白质表示基础模型，支持多种蛋白质分析和设计下游任务。 |
| ProteinAligner | ProteinAligner: Cross-Modal Alignment for Protein Sequence and Structure | — | 2025 | — | Preprint | 蛋白质序列-结构跨模态对齐基础模型，增强蛋白质理解和功能预测。 |
| ProteinTalks | ProteinTalks: Multi-Modal Protein Language Model with Natural Language Interaction | — | 2025 | 10.1101/2025.02.07.637070 | bioRxiv | 多模态蛋白质语言模型，支持自然语言交互进行蛋白质分析和设计 |
| GearNet | Protein Representation Learning by Geometric Structure Pretraining | Zuobai Zhang | 2023 | arXiv:2203.06125 | ICLR 2023 | 关系图神经网络，通过几何结构预训练和多视图对比学习学习蛋白质结构表示 |
| MIF | Masked inverse folding with sequence transfer for protein representation learning | Kevin Yang | 2022 | 10.1093/protein/gzad015 | Protein Engineering Design and Selection | 自监督掩码逆折叠预训练，从结构学习蛋白质表示。 |
| PPLM | A paired sequence language model for protein-protein interaction | Jun Liu | 2026 | doi:10.1038/s41467-026-70457-5 | Nature Communications | 成对序列语言模型，预测蛋白质-蛋白质相互作用 |
| AIDO.Protein | Mixture of experts enable efficient and effective protein understanding and design | — | 2024 | bioRxiv:2024.11.29.625425 | bioRxiv Preprint | AIDO体系中的蛋白质模块，160亿参数MoE架构，在1.2万亿氨基酸上训练 |
| BioReason-Pro | BioReason-Pro: Advancing Protein Function Prediction with Multimodal Biological Reasoning | Adibvafa Fallahpour | 2026 | doi:10.64898/2026.03.19.712954 | bioRxiv Preprint | 首个蛋白质功能预测多模态推理LLM，整合ESM3嵌入与GO-GPT本体建模；GO术语预测F_max 73.6%，人类专家79%偏好其注释超过UniProt |

#### 蛋白质结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaFold2 | Highly accurate protein structure prediction with AlphaFold | John Jumper | 2021 | 10.1038/s41586-021-03819-2 | Nature | DeepMind开发的革命性蛋白质结构预测模型，在CASP14中达到原子级精度 |
| AlphaFold3 | Accurate structure prediction of biomolecular interactions with AlphaFold 3 | Josh Abramson | 2024 | 10.1038/s41586-024-07487-w | Nature | 基于扩散模型的生物分子相互作用结构预测，支持蛋白质、核酸、小分子、离子等 |
| RoseTTAFold | Accurate prediction of protein structures and interactions using a three-track neural network | Minkyung Baek | 2021 | 10.1126/science.abj8754 | Science | 三轨道神经网络蛋白质结构预测模型，开源替代AlphaFold2 |
| RoseTTAFold2 | Efficient and accurate prediction of protein structure using RoseTTAFold2 | — | 2023 | bioRxiv:2023.05.24.542179 | bioRxiv | RoseTTAFold升级版，结合AlphaFold2和RoseTTAFold的关键特征 |
| RoseTTAFold All-Atom | Generalized biomolecular modeling and design with RoseTTAFold All-Atom | Rohith Krishna | 2024 | 10.1126/science.adl2528 | Science | 全原子生物分子建模框架，支持蛋白质、核酸、小分子、金属离子的复合物预测 |
| OmegaFold | High-resolution de novo structure prediction from primary sequence | Ruidong Wu | 2022 | bioRxiv:2022.07.21.500999 | bioRxiv | 无需MSA的单序列蛋白质结构预测方法，利用预训练蛋白质语言模型 |

#### 蛋白质设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProteinMPNN | Robust deep learning–based protein sequence design using ProteinMPNN | J. Dauparas | 2022 | 10.1126/science.add2187 | Science | 消息传递神经网络用于蛋白质序列设计，具有实验验证的高成功率。 |
| RFdiffusion | De novo design of protein structure and function with RFdiffusion | Joseph L. Watson | 2023 | 10.1038/s41586-023-06415-8 | Nature | 基于RoseTTAFold的扩散模型，用于从头蛋白质骨架设计。 |
| RFdiffusion3 | RFdiffusion3: All-atom biomolecular design | — | 2025 | 10.1101/2025.09.18.676967 | bioRxiv | 升级版RFdiffusion，支持全原子级蛋白质和生物分子设计 |
| Chroma | Illuminating protein space with a programmable generative model | John B. Ingraham | 2023 | 10.1038/s41586-023-06728-8 | Nature | Generate:Biomedicines开发的可编程蛋白质扩散生成模型。 |
| FrameDiff | SE(3) diffusion model with application to protein backbone generation | Jason Yim | 2023 | arXiv:2302.02277 | ICLR 2024 | SE(3)等变扩散模型，用于蛋白质骨架生成，无需预训练结构预测网络 |
| FrameFlow | SE(3) stochastic flow matching for protein backbone generation | Jason Yim | 2024 | arXiv:2310.02391 | ICLR 2024 | 基于SE(3)流匹配的蛋白质骨架生成模型 |
| FoldingDiff | Protein structure generation via folding diffusion | Kevin E. Wu | 2024 | 10.1038/s41467-024-45051-2 | Nature Communications | 基于蛋白质折叠角表示的扩散模型，模拟自然折叠过程。 |
| Genie | Genie: SE(3)-equivariant generative model for protein backbone design | Yeqing Lin | 2023 | arXiv:2301.12485 | ICML 2023 (Workshop) | SE(3)等变DDPM蛋白质骨架设计模型 |
| Genie 2 | Out of Many, One: Designing and Scaffolding Proteins at the Scale of the Structural Universe with Genie 2 | Yeqing Lin | 2024 | arXiv:2405.15489 | arXiv | Genie升级版，捕获更广泛、更多样化的蛋白质结构空间。 |
| Proteus | Proteus: Exploring Protein Structure Generation for Enhanced Designability and Efficiency | Chentong Wang | 2024 | 10.1101/2024.02.10.579791 | bioRxiv | 高效蛋白质骨架生成模型，无需预训练结构预测网络。 |
| FoldFlow | FoldFlow: SE(3) stochastic flow matching for protein backbone generation | — | 2024 | arXiv:2310.02391 | ICLR 2024 | 基于随机流匹配的蛋白质骨架生成模型族 |
| ProteinGenerator (PG) | Multistate and functional protein design using RoseTTAFold | Sidney Lyayber | 2024 | 10.1038/s41587-024-02395-w | Nature Biotechnology | 基于RoseTTAFold的扩散模型，同时生成蛋白质序列和结构 |
| SeedProteo | SeedProteo: All-atom protein design | — | 2024 | arXiv:2512.24192 | arXiv | 基于扩散的全原子蛋白质设计模型，整合结构和序列信息 |
| ESM-IF (ESM-IF1) | Language models generalize beyond natural proteins | Robert Verkuil | 2022 | 10.1101/2022.12.21.521521 | bioRxiv | 以骨架结构为条件的逆折叠模型，用于生成蛋白质序列。 |
| EvoDiff | Protein generation with evolutionary diffusion | Alamdari et al. | 2023 | doi:10.1101/2023.09.11.556673 | bioRxiv/Nature Biotechnology | 利用进化数据的基于序列的扩散模型，用于蛋白质生成。 |
| ZymCTRL | Conditional language models enable the efficient design of proficient enzymes | Munsamy et al. | 2024 | 10.1101/2024.05.03.592223 | bioRxiv | 条件酶语言模型，在3700万BRENDA酶序列上训练。 |
| PiFold | PiFold: Toward effective and efficient protein inverse folding | Gao et al. | 2023 | doi:10.48550/arXiv.2209.12643 | ICLR 2023 | 具有新型PiGNN架构的高效逆折叠模型。 |
| LM-Design | Structure-informed language models are protein designers | Zheng et al. | 2023 | doi:10.1101/2023.02.03.526917 | ICML 2023 | 结合蛋白质语言模型和结构上下文的结构信息引导蛋白质设计语言模型。 |
| ProteinDT | A text-guided protein design framework | Shengchao Liu | 2025 | 10.1038/s42256-025-01011-z | Nature Machine Intelligence | 使用多模态学习的文本引导蛋白质生成框架。 |
| Protpardelle | An all-atom protein generative model | Chu et al. | 2024 | doi:10.1073/pnas.2311500121 | PNAS | 全原子生成模型，用于生成包含侧链的完整蛋白质结构。 |
| Multiflow | Generative Flows on Discrete State-Spaces for Protein Co-Design | Campbell et al. | 2024 | arXiv:2402.04997 | ICML 2024 | 离散流匹配框架，用于序列-结构联合蛋白质协同设计。 |
| La-Proteina | La-Proteina: Atomistic Protein Generation via Partially Latent Flow Matching | Tomas Geffner | 2025 | arXiv:2507.09466 | arXiv | 通过部分潜在流匹配的原子级蛋白质生成方法。 |
| EvoFlows | Evolutionary Edit-Based Flow-Matching for Protein Engineering | — | 2026 | arXiv:2603.11703 | Preprint | 基于进化编辑的流匹配方法，用于定向蛋白质工程。 |
| Fold2Seq | Fold2Seq: A joint sequence(1D)-fold(3D) embedding-based generative model for protein design | — | 2021 | arXiv:2106.13058 | ICML 2021 | 联合序列-折叠嵌入的蛋白质设计生成模型，从3D结构和1D序列联合学习 |
| TERMinator | TERMinator: A neural framework for structure-based protein design using tertiary repeating motifs | — | 2022 | doi:10.1038/s41467-022-37051-7 | Nature Communications | 基于三级重复基序的蛋白质设计神经网络框架 |
| AlphaDesign | AlphaDesign: A graph protein design method and benchmark on AlphaFoldDB | — | 2022 | arXiv:2202.01079 | arXiv | 基于AlphaFoldDB的图蛋白质设计方法和基准测试 |
| Latent-X | Latent-X: Atom-level frontier model for de novo protein binder design | Latent Labs | 2025 | — | arXiv Preprint | 原子级前沿模型，用于从头蛋白质结合物设计 |
| Latent-X2 | Latent-X2: Drug-like antibodies with low immunogenicity | Latent Labs | 2025 | arXiv:2512.20263 | arXiv | 低免疫原性的药物级抗体设计模型 |
| ProDiT | Generating functional proteins with a multimodal diffusion transformer | — | 2025 | bioRxiv:2025.09.03.672144 | bioRxiv | 多模态扩散Transformer蛋白质设计模型，在2.14亿蛋白上训练 |
| SimpleDesign | SimpleDesign: Joint Model for Protein Sequence and Structure Codesign | — | 2025 | OpenReview | ICLR 2025 | 端到端蛋白质序列-结构联合设计模型 |
| PXDesign | PXDesign: Fast De Novo Design of Protein Binders | Protenix (ByteDance) | 2025 | bioRxiv:2025.08.15.670450 | bioRxiv | 字节跳动Protenix快速蛋白质结合物从头设计 |

#### 肽基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PepMLM | Target Sequence-Conditioned Generation of Therapeutic Peptide Binders via Span Masked Language Modeling | Tianlai Chen | 2023/2025 | arXiv:2310.03842 | Nature Biotechnology / ICLR 2024 | 基于ESM-2微调的span masked LM，根据靶蛋白序列条件生成线性肽结合物 |
| PepBERT | PepBERT: Lightweight language models for peptide representation | Zhenjiao Du | 2025 | bioRxiv:2025.04.08.647838 | bioRxiv | 轻量级专用肽语言模型，用于生物活性肽发现和表示学习 |
| PepDoRA | PepDoRA: A Unified Peptide Language Model via Weight-Decomposed Low-Rank Adaptation | Leyao Wang | 2024 | arXiv:2410.20667 | arXiv | 统一肽语言模型，通过权重分解低秩适应预测多种肽属性。 |
| AMP-Designer | A foundation model approach to guide antimicrobial peptide design in the era of AI-driven scientific discovery | Tingjun Hou | 2024/2025 | arXiv:2407.12296 | Science Advances | 基于LLM的抗菌肽设计基础模型，可从头设计具有显著抗菌活性的新型AMP |
| AMP-Diffusion | AMP-Diffusion: Integrating Latent Diffusion with Protein Language Models for Antimicrobial Peptide Generation | Tianlai Chen | 2024 | 10.1101/2024.03.03.583201 | bioRxiv | 整合ESM-2的潜在扩散模型，用于生成新型抗菌肽。 |
| deepAMP | A Foundation Model Identifies Broad-Spectrum Antimicrobial Peptides against Drug-Resistant Bacterial Infection | Tingting Li | 2024 | 10.1038/s41467-024-51933-2 | Nature Communications | 基于肽语言模型的深度生成框架，识别广谱抗菌肽。 |
| RFpeptides | Accurate de novo design of high-affinity protein-binding macrocycles | Stephen Rettie | 2024/2025 | doi:10.1038/s41589-025-01929-w | Nature Chemical Biology | 基于RoseTTAFold的去噪扩散模型，用于大环肽从头设计 |
| AfCycDesign | Cyclic peptide structure prediction and design using AlphaFold2 | Stephen A. Rettie | 2025 | 10.1038/s41467-025-59940-7 | Nature Communications | 基于AlphaFold2的环肽结构预测、重设计和从头生成方法。 |
| CP-Composer | Zero-Shot Cyclic Peptide Design via Composable Geometric Constraints | — | 2025 | arXiv:2507.04225 | ICML 2025 | 基于可组合几何约束的零样本环肽设计框架 |
| CpSDE | Designing Cyclic Peptides via Harmonic SDE with Atom-Bond Modeling | — | 2025 | arXiv:2505.21452 | ICML 2025 | 使用谐波随机微分方程和原子-键建模的环肽设计方法 |
| PDeepPP | A general language model for peptide identification | Jixiu Zhai | 2025 | arXiv:2502.15610 | arXiv | 通用的肽功能预测深度学习框架，结合预训练蛋白质语言模型与Transformer-CNN架构 |

#### 蛋白质-蛋白质相互作用

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PLM-interact | PLM-interact: extending protein language models to predict protein-protein interactions | Dan Liu | 2025 | 10.1038/s41467-025-64512-w | Nature Communications | 蛋白质语言模型的PPI预测扩展，仅从序列联合编码蛋白质对。 |
| IntFold | IntFold: A Controllable Foundation Model for General and Specialized Biomolecular Structure Prediction | The IntFold Team | 2025 | arXiv:2507.02025 | arXiv | 可控生物分子结构预测基础模型，精度匹配AlphaFold3，支持PPI复合物和变构状态。 |

#### 蛋白质动力学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProTDyn | ProTDyn: a foundation Protein language model for Thermodynamics and Dynamics | — | 2025 | arXiv:2510.00013 | NeurIPS 2025 | 蛋白质热力学与动力学基础语言模型，统一构象集合生成和多时间尺度动力学建模 |
| SeqDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | bioRxiv Preprint | 结合生物物理动力学的蛋白质语言模型，训练于>64,000个蛋白质的MD模拟和简正模式分析 |
| ESMDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | bioRxiv Preprint | ESM-2微调版本，用于蛋白质构象动力学预测 |
| MD-LLM-1 | MD-LLM-1: A Large Language Model for Molecular Dynamics | Mhd Hussein Murtada | 2025 | arXiv:2508.03709 | arXiv | 首个分子动力学大语言模型，微调Mistral 7B用于蛋白质构象动力学预测 |
| VibeGen | Agentic End-to-End De Novo Protein Design for Tailored Dynamics Using a Language Diffusion Model | Markus Buehler | 2025 | arXiv:2502.10173 | arXiv (MIT) | 基于语言扩散模型的端到端蛋白质动力学设计框架，面向振动模式定制设计 |
| DynamicsPLM | Learning Protein Representations with Conformational Dynamics | Dan Kalifa | 2025 | bioRxiv:2025.10.06.680789 | bioRxiv | 结合构象动力学集合的蛋白质语言模型，从计算生成的结构集合中学习 |
| DPLM-2 | DPLM-2: A Multimodal Diffusion Protein Language Model | Xinyou Wang | 2024/2025 | arXiv:2410.13782 | NeurIPS 2025 (ByteDance) | 多模态离散扩散蛋白质语言模型，联合建模氨基酸序列和3D结构 |
| METL | Biophysics-based protein language models for protein engineering | Sam Gelman | 2025 | 10.1038/s41592-025-02776-2 | Nature Methods | 突变效应迁移学习框架，整合生物物理建模和机器学习用于蛋白质工程。 |

---

<a id="life-sciences-section-02"></a>
### RNA

#### RNA语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RNA-FM | Interpretable RNA foundation model from unannotated data for highly accurate RNA structure and function predictions | Jiayang Chen | 2022 | 10.1038/s41592-024-02243-4 | Nature Methods | RNA基础模型，在2300万非编码RNA序列上预训练，用于RNA结构和功能预测 |
| RiNALMo | RiNALMo: General-purpose RNA language models can generalize well on structure prediction tasks | Rafael Josip Penić | 2024 | 10.1038/s41467-025-5671 | Nature Communications | 6.5亿参数通用RNA语言模型，在3600万非编码RNA序列上训练，结构预测泛化能力强 |
| ERNIE-RNA | ERNIE-RNA: An RNA language model with structure-enhanced representations | Weijie Yin | 2025 | 10.1038/s41467-025-64972-0 | Nature Communications | 基于修改BERT架构的RNA语言模型，融合碱基配对结构信息增强表示 |
| RNA-MSM | Multiple sequence alignment-based RNA language model and its application to structural inference | Yikun Zhang | 2024 | 10.1093/nar/gkad1031 | Nucleic Acids Research | 基于多序列比对的RNA语言模型，利用同源RNA的共进化信息进行结构推断 |
| UNI-RNA | UNI-RNA: Universal pre-trained models revolutionize RNA research | Han Wen | 2023 | bioRxiv:2023.07.11.548588 | bioRxiv | 在最大RNA序列数据集上训练的通用预训练RNA模型，支持多种下游任务 |
| RNAErnie | Multi-purpose RNA language modelling with motif-aware pretraining and type-guided fine-tuning | Weijie Yin | 2024 | 10.1038/s42256-024-00836-4 | Nature Machine Intelligence | 多功能RNA语言模型，结合motif感知预训练和RNA类型引导微调 |
| AIDO.RNA | A large-scale foundation model for RNA function and structure prediction | — | 2024 | bioRxiv:2024.11.28.625345 | bioRxiv Preprint | 16亿参数RNA基础模型，在4200万非编码RNA序列上训练，单核苷酸分辨率 |
| BiRNA-BERT | BiRNA-BERT allows efficient RNA language modeling with adaptive tokenization | — | 2025 | 10.1038/s42003-025-08982-0 | Communications Biology | 自适应分词RNA语言模型，克服传统模型在序列长度和多样性上的限制 |
| mRNABERT | mRNABERT: advancing mRNA sequence design with a universal language model and comprehensive dataset | — | 2025 | 10.1038/s41467-025-65340-8 | Nature Communications | 专为mRNA序列工程设计的语言模型，采用双分词方案 |
| CodonBERT | CodonBERT: Large language models for mRNA design and optimization | — | 2024 | — | arXiv Preprint | 基于密码子级分词的mRNA语言模型 |
| NucleicBERT | NucleicBERT: A large language model for RNA structure prediction | — | 2025 | — | GitHub/KIT-MBS | RNA序列分析的Transformer语言模型，在大规模RNA数据集上预训练 |
| MP-RNA | MP-RNA: Unleashing multi-species RNA foundation model via calibrated secondary structure prediction | — | 2024 | ACL Anthology | EMNLP 2024 Findings | 多物种RNA基础模型，强调二级结构预测在RNA建模中的重要性 |
| OmniGenome | Bridging Sequence-Structure Alignment in RNA Foundation Models | Heng Yang | 2024 | arXiv:2407.11242 | arXiv | RNA基础模型，精确对齐RNA序列与二级结构，实现双向映射。 |
| structRFM | A fully-open structure-guided RNA foundation model for robust structural and functional inference | Heqin Zhu | 2025 | 10.1101/2025.08.06.668731 | bioRxiv | 完全开源的结构引导RNA基础模型，整合序列和二级结构实现鲁棒推断。 |
| SpliceBERT | SpliceBERT: a pre-trained RNA language model for analyzing vertebrate splicing | Chen et al. | 2024 | doi:10.1101/2023.01.31.526427 | Genome Biology | 专门用于脊椎动物剪接分析的预训练RNA语言模型。 |
| PlantRNA-FM | An interpretable RNA foundation model for exploring functional RNA motifs in plants | Yang et al. | 2024 | doi:10.1038/s42256-024-00946-z | Nature Machine Intelligence | 用于植物生物学的可解释RNA基础模型，覆盖1,124+种植物。 |
| AllSplice | Perturbation-aware predictive modeling of RNA splicing using bidirectional transformers | McNally et al. | 2024 | doi:10.1101/2024.03.20.585793 | bioRxiv | 扰动感知双向Transformer，用于RNA剪接预测。 |
| HydraRNA | HydraRNA: A hybrid architecture based full-length RNA language model | — | 2025 | doi:10.1186/s13059-025-03853-7 | Genome Biology | 混合架构全长RNA语言模型，结合多种架构优势处理全长RNA序列 |
| EVA-RNA | EVA-RNA: A Scaling Cross-Species Transcriptomic Foundation Model for Immunology & Inflammation | — | 2026 | OpenReview:VcOvSJNgRf | OpenReview | 跨物种转录组基础模型，训练于50万+人鼠样本，专注免疫与炎症研究 |
| GRNFormer | GRNFormer: A Biologically-Guided Framework for Integrating Gene Regulatory Networks into RNA Foundation Models | — | 2025 | arXiv:2503.01682 | arXiv | 将基因调控网络整合到RNA基础模型的生物学引导框架 |
| BMFM-RNA | BMFM-RNA: Whole-cell expression decoding improves transcriptomic foundation models | — | 2025 | arXiv:2506.14861 | arXiv (IBM) | IBM生物医学基础模型RNA模块，全细胞表达解码增强转录组基础模型 |
| CodonFM | CodonFM: Foundation Models for Codons | NVIDIA/Arc Institute | 2025 | github | Preprint | 密码子基础模型，在1.3亿蛋白质编码序列上训练 |
| Orthrus | Orthrus: Evolutionary and Functional RNA Foundation Models | Bo Wang | 2024 | bioRxiv:2024.10.10.617658 | bioRxiv Preprint | 生物增强对比学习RNA基础模型 |

#### RNA结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RhoFold+ | Accurate RNA 3D structure prediction using a language model-based deep learning approach | Tao Shen | 2024 | 10.1038/s41592-024-02487-0 | Nature Methods | 基于预训练RNA语言模型的准确RNA 3D结构预测方法，在2370万序列上训练。 |
| RNA-FrameFlow | Flow Matching for de novo 3D RNA Backbone Design | — | 2024 | arXiv:2406.13839 | Preprint | SE(3)流匹配方法，用于从头设计3D RNA骨架结构。 |
| DRfold2 | Ab initio RNA structure prediction with composite language model and denoised end-to-end learning | Zhang et al. | 2025 | 10.1101/2025.03.05.641632 | bioRxiv | 使用复合语言模型的从头RNA 3D结构预测深度学习框架。 |
| 3DRNALM | Accurate RNA 3D structure prediction using a language model-based framework | — | 2024 | PMC11621015 | Nature Communications | 基于语言模型的准确RNA 3D结构预测框架。 |
| NuFold | NuFold: end-to-end approach for RNA tertiary structure prediction | Daisuke Kihara | 2025 | doi:10.1038/s41467-025-56261-7 | Nature Communications | 端到端RNA三级结构预测深度学习模型 |

#### RNA设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RNAGenesis | RNAGenesis: A Generalist Foundation Model for Functional RNA Therapeutics | Zaixi Zhang | 2024 | 10.1101/2024.12.30.630826 | bioRxiv | 通用RNA治疗基础模型，统一序列表示、结构预测和功能从头设计。 |
| GEMORNA | Deep generative models design mRNA sequences with enhanced translational capacity and stability | He Zhang | 2025 | 10.1126/science.adr8470 | Science | 深度生成模型，设计具有增强翻译能力和稳定性的mRNA序列。 |
| EVA | A Long-Context Generative Foundation Model Deciphers RNA Design Principles | Yanjie Huang | 2026 | 10.64898/2026.03.17.712398 | bioRxiv | 14亿参数MoE生成基础模型，在1.14亿全长RNA序列上训练，用于长上下文RNA设计。 |
| RNACG | RNACG: A Universal RNA Sequence Conditional Generation model based on Flow-Matching | Letian Gao | 2024 | arXiv:2407.19838 | arXiv | 基于流匹配的通用RNA序列条件生成模型。 |
| RiboFlow | RiboFlow: Conditional De Novo RNA Co-Design via Synergistic Flow Matching | Runze Ma | 2025 | arXiv:2503.17007 | NeurIPS 2025 | 协同流匹配的RNA序列-结构联合设计框架，面向配体结合 |
| RiboGen | RiboGen: RNA Sequence and Structure Co-Generation with Equivariant MultiFlow | — | 2025 | arXiv:2503.02058 | ICLR 2025 | 等变多流模型同时生成RNA序列和全原子3D结构 |
| SANDSTORM | Generative and predictive neural networks for the design of functional RNA molecules | Aidan T. Riley | 2025 | 10.1038/s41467-025-59389-8 | Nature Communications | 整合序列和二级结构数据的RNA功能预测神经网络。 |
| GARDN | Generative and predictive neural networks for the design of functional RNA molecules | Aidan T. Riley | 2025 | 10.1038/s41467-025-59389-8 | Nature Communications | 功能性RNA设计的生成神经网络，与SANDSTORM配对用于预测。 |
| mRNA-GPT | Large generative mRNA language foundation model for efficient coding sequence generation and design | — | 2025 | bioRxiv:2025.12.22.695962 | bioRxiv | 基于GPT-2的大规模mRNA生成语言模型（302M参数），跨三个生物域的mRNA编码序列生成 |
| codonGPT | codonGPT: reinforcement learning on a generative language model enables scalable mRNA design | Binita Rajbanshi | 2025 | 10.1093/nar/gkaf1345 | Nucleic Acids Research | 强化学习加生成语言模型，用于可扩展mRNA密码子优化设计。 |
| RiboDecode | Deep generative optimization of mRNA codon sequences for enhanced mRNA translation and therapeutic efficacy | Yupeng Li | 2025 | 10.1038/s41467-025-64894-x | Nature Communications | 深度生成优化框架，增强mRNA密码子序列的翻译效率和治疗效果。 |

---

<a id="life-sciences-section-03"></a>
### DNA与基因组

#### DNA/基因组语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Evo | Sequence modeling and design from molecular to genome scale with Evo | Eric Nguyen | 2024 | 10.1126/science.ado9336 | Science | Arc Institute DNA基础模型，处理从分子到基因组尺度的序列（>650K token）。 |
| Evo 2 | Genome modelling and design across all domains of life with Evo 2 | Garyk Brixi | 2026 | 10.1038/s41586-026-10176-5 | Nature | DNA基础模型，在9万亿碱基对上训练，覆盖所有生命域，具有100万token上下文窗口。 |
| DNABERT | DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome | Yanrong Ji | 2021 | 10.1093/bioinformatics/btab083 | Bioinformatics | 首个基于BERT的基因组DNA序列预训练模型，使用k-mer分词。 |
| DNABERT-2 | DNABERT-2: Efficient foundation model and benchmark for multi-species genome | Zhihan Zhou | 2024 | ICLR 2024 | ICLR 2024 | DNABERT升级版，采用BPE分词替代k-mer，支持多物种基因组分析 |
| Nucleotide Transformer | Nucleotide Transformer: building and evaluating robust foundation models for human genomics | Hugo Dalla-Torre | 2025 | 10.1038/s41592-024-02523-z | Nature Methods | InstaDeep开发的大规模基因组基础模型（5000万-25亿参数），在3,200+人类基因组上训练。 |
| HyenaDNA | HyenaDNA: Long-range genomic sequence modeling at single nucleotide resolution | Eric Nguyen | 2023 | arXiv:2306.15794 | arXiv | 基于Hyena隐式卷积架构的基因组模型，单核苷酸分辨率长程建模(100万bp) |
| Enformer | Effective gene expression prediction from sequence by integrating long-range interactions | Žiga Avsec | 2021 | 10.1038/s41592-021-01252-x | Nature Methods | DeepMind/Calico开发的Transformer模型，从DNA序列预测基因表达和染色质状态。 |
| Caduceus | Caduceus: Bi-directional equivariant long-range DNA sequence modeling | Yair Schiff | 2024 | arXiv:2403.03234 | ICML 2024 | 基于Mamba架构的双向DNA语言模型，支持反向互补等变性 |
| GenSLMs | GenSLMs: Genome-scale language models reveal SARS-CoV-2 evolutionary dynamics | Maxim Zvyagin | 2023 | 10.1177/10943420231201154 | IJHPCA (Gordon Bell Prize) | 基因组尺度语言模型，在1.1亿原核基因序列上预训练，分析SARS-CoV-2进化动态 |
| GROVER | DNA language model GROVER learns sequence context in the human genome | Melissa Sanabria | 2024 | 10.1038/s42256-024-00872-0 | Nature Machine Intelligence | DNA语言模型，使用BPE在人类基因组上训练，定义DNA词汇表并捕获CpG甲基化特征。 |
| Sei | A sequence-based global map of regulatory activity for deciphering human genetics | Kathleen M. Chen | 2022 | 10.1038/s41588-022-01102-2 | Nature Genetics | 深度学习框架，预测21,900+染色质特征并将序列映射到40种调控活性类别。 |
| GPN | DNA language models are powerful predictors of genome-wide variant effects | Gonzalo Benegas | 2023 | 10.1073/pnas.2311219120 | Proceedings of the National Academy of Sciences | 无监督DNA语言模型，从基因组序列预测全基因组变异效应。 |
| Borzoi | Borzoi decodes the complex DNA signals governing gene regulation | Sandra T. Cooper | 2025 | 10.1038/s41588-025-02154-w | Nature Genetics | 深度学习模型，从DNA序列预测RNA-seq覆盖度，解码基因调控信号。 |
| PlantCaduceus | Cross-species modeling of plant genomes at single-nucleotide resolution using a pretrained DNA language model | — | 2025 | 10.1073/pnas.2421738122 | PNAS | 植物特异性DNA语言模型，在16种被子植物基因组上训练，支持跨物种分析 |
| HybriDNA | HybriDNA: A hybrid Transformer-Mamba2 DNA language model | — | 2025 | arXiv:2502.10807 | arXiv | 结合Transformer和Mamba2架构的DNA语言模型，支持超长序列(131kb)单核苷酸分辨率 |
| Nucleotide Transformer v3 (NTv3) | A foundational model for joint sequence-function multi-species prediction | — | 2025 | bioRxiv | bioRxiv | 多物种长程基因组预测与功能注释基础模型 |
| Basenji | Sequential regulatory activity prediction across chromosomes with convolutional neural networks | Kelley et al. | 2018 | doi:10.1101/gr.227819.117 | Genome Research | 从DNA序列预测基因表达和调控活性的卷积神经网络。 |
| Basenji2 | Cross-species regulatory sequence activity prediction | David R. Kelley | 2020 | 10.1371/journal.pcbi.1008050 | PLOS Computational Biology | 跨物种DNA调控活性预测模型。 |
| ChromBPNet | ChromBPNet: bias factorized, base-resolution deep learning models of chromatin accessibility reveal cis-regulatory sequence syntax, transcription factor footprints and regulatory variants | Pampari et al. | 2025 | 10.1101/2024.12.25.630221 | bioRxiv | 碱基分辨率深度学习模型，通过偏差因子分解预测染色质可及性。 |
| scBasset | scBasset: sequence-based modeling of single-cell ATAC-seq using convolutional neural networks | Han Yuan | 2022 | 10.1038/s41592-022-01562-8 | Nature Methods | CNN模型，从DNA序列建模单细胞ATAC-seq染色质可及性。 |
| EpiGePT | EpiGePT: a Pretrained Transformer model for epigenomics | Zijing Gao | 2023 | 10.1101/2023.07.15.549134 | bioRxiv | 用于表观基因组数据分析和预测的预训练Transformer模型。 |
| AgroNT | AgroNT: A crop genomics foundation model | Mendoza-Revilla et al. | 2024 | 10.1038/s41586-024-07969-x | Nature | 作物特异性基因组基础模型，用于植物基因组学和育种应用。 |
| AlphaGenome | Advancing regulatory variant effect prediction with AlphaGenome | Žiga Avsec | 2026 | 10.1038/s41586-025-10014-0 | Nature | Google DeepMind的兆碱基尺度DNA模型，预测基因表达和染色质信号用于变异效应分析。 |
| GENA-LM | GENA-LM: A Family of Open-Source Foundational DNA Language Models for Long Sequences | Veniamin Fishman | 2023 | 10.1101/2023.06.12.544594 | bioRxiv | 开源Transformer DNA语言模型家族，支持最长36k bp序列。 |
| DNAGPT | DNAGPT: A Generalized Pre-trained Tool for Multiple DNA Sequence Analysis Tasks | Daoan Zhang | 2023 | 10.1101/2023.07.11.548628 | bioRxiv | 用于多种DNA分析任务的生成式预训练模型。 |
| MoDNA | MoDNA: Motif-Oriented Pre-training For DNA Language Model | — | 2022 | doi:10.1145/3535508.3545512 | ACM BCB | 面向基序的预训练DNA语言模型，捕获调控基序模式。 |
| GPN-MSA | GPN-MSA: An alignment-based DNA language model for genome-wide variant effect prediction | Benegas et al. | 2023 | doi:10.1038/s41587-024-02511-w | Nature Biotechnology | 使用多物种比对的DNA语言模型，用于全基因组变异效应预测。 |
| MergeDNA | MergeDNA: Context-aware Genome Modeling with Dynamic Tokenization through Token Merging | — | 2025 | AAAI 2025 | AAAI | 分层动态词元化方法，用于上下文感知基因组建模。 |
| BMFM-DNA | BMFM-DNA: A SNP-aware DNA foundation model to capture variant effects | Hongyang Li | 2025 | arXiv:2507.05265 | arXiv | IBM SNP感知DNA基础模型，捕获基因组序列中的变异效应。 |
| EpiAgent | EpiAgent: foundation model for single-cell epigenomics | Xiaoyang Chen | 2025 | 10.1038/s41592-025-02822-z | Nature Methods | 用于单细胞ATAC-seq表观基因组数据分析的基础模型。 |
| Gene42 | Gene42: Long-Range Genomic Foundation Model With Dense Attention | Kirill Vishniakov | 2025 | arXiv:2503.16565 | arXiv | 仅解码器的长程基因组基础模型，以单核苷酸分辨率处理最长192,000 bp。 |
| dnaHNet | dnaHNet: A Scalable and Hierarchical Foundation Model for Genomic Sequence Learning | Arnav Shah | 2026 | arXiv:2602.10603 | arXiv | 用于基因组序列学习的可扩展层次化基础模型。 |
| JEPA-DNA | JEPA-DNA: Grounding Genomic Foundation Models through Joint-Embedding Predictive Architectures | Ariel Larey | 2026 | arXiv:2602.17162 | arXiv | 基于联合嵌入预测架构的基因组基础模型，结合生成和判别目标。 |
| GeneZip | GeneZip: Region-Aware Compression for Long Context DNA Modeling | Jianan Zhao | 2026 | arXiv:2602.17739 | arXiv | 用于长上下文DNA序列建模的区域感知压缩方法。 |
| ModernGENA | ModernGENA: A modernized BERT-style DNA foundation model | — | 2025/2026 | OpenReview:U98HvYaBDE | OpenReview | 现代化BERT架构的DNA基础模型(ModernBERT适配基因组) |
| OpticalDNA | OpticalDNA: Reimagining DNA sequence analysis as an OCR task | — | 2026 | arXiv:2602.02014 | arXiv | 将DNA序列分析重构为光学字符识别(OCR)任务的新框架 |
| OmniReg-GPT | OmniReg-GPT: A Generative Pre-trained Model for Universal Gene Regulation Prediction | — | 2025 | — | Preprint | 通用基因调控预测的生成式预训练模型，跨物种跨组织的基因表达调控建模。 |
| BOTANIC-0 | BOTANIC-0: A Plant Genomic Foundation Model | — | 2025 | — | Preprint | 植物基因组基础模型，在大规模植物DNA序列上预训练，支持作物育种和功能基因组学。 |
| Species-aware DNA LM | Species-aware DNA Language Modeling | Dennis Gankin | 2023 | bioRxiv:2023.01.26.525670 | bioRxiv | 在预训练中融入物种特异性信息的DNA语言模型 |
| Genos | Genos: A Large Human-Centric Genomic Foundation Model | — (BGI / Zhejiang Lab) | 2025 | BGI-HangzhouAI/Genos | ICG-20 Conference | 全球首个100亿参数人类基因组基础模型，MoE-Transformer架构，支持百万碱基对上下文分析 |
| GENERator | GENERator: A Long-Context Generative Genomic Foundation Model | Wei Wu | 2025 | arXiv:2502.07272 | arXiv | 长上下文生成式基因组基础模型 |
| BioReason | BioReason: Incentivizing Multimodal Biological Reasoning within a DNA-LLM Model | Adibvafa Fallahpour | 2025 | arXiv:2505.23579 | NeurIPS 2025 | 首个将DNA基础模型（Nucleotide Transformer/Evo2）与LLM深度整合的多模态生物推理模型；KEGG疾病通路预测从86%提升至98%，生成可解释的推理链 |

---

<a id="life-sciences-section-04"></a>
### 单细胞

#### 单细胞基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| scGPT | scGPT: toward building a foundation model for single-cell multi-omics using generative AI | Haotian Cui | 2024 | 10.1038/s41592-024-02201-0 | Nature Methods | 单细胞多组学生成式预训练Transformer，支持细胞注释、扰动预测和基因网络推断（3,300万+细胞）。 |
| scBERT | scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data | Fan Yang | 2022 | 10.1038/s42256-022-00534-z | Nature Machine Intelligence | 大规模基于BERT的预训练模型，用于scRNA-seq数据的自动细胞类型注释。 |
| Geneformer | Transfer learning enables predictions in network biology | Christina V. Theodoris | 2023 | 10.1038/s41586-023-06139-9 | Nature | 在约3,000万单细胞转录组上预训练的Transformer模型，用于基因网络生物学迁移学习。 |
| scFoundation | Large-scale foundation model on single-cell transcriptomics | Minsheng Hao | 2024 | 10.1038/s41592-024-02305-7 | Nature Methods | 1亿参数单细胞转录组基础模型（xTrimoGene），在5,000万+人类细胞上训练。 |
| UCE | Universal Cell Embeddings: A Foundation Model for Cell Biology | Yanay Rosen | 2023 | 10.1101/2023.11.28.568918 | bioRxiv | 通用细胞嵌入模型，创建跨物种和组织的统一表示空间。 |
| GeneCompass | GeneCompass: deciphering universal gene regulatory mechanisms with a knowledge-informed cross-species foundation model | Xiaodong Yang | 2024 | 10.1038/s41422-024-01034-y | Cell Research | 知识增强的跨物种基础模型，在1亿+人和小鼠细胞上训练，用于解读基因调控机制。 |
| CellPLM | CellPLM: Pre-training of Cell Language Model Beyond Single Cells | Hongzhi Wen | 2024 | OpenReview:BKXvPDekud | ICLR 2024 | 超越单细胞的细胞语言模型预训练，整合基因-基因和细胞-细胞相互作用 |
| tGPT | Generative pretraining from large-scale transcriptomes for single-cell deciphering | Hongru Shen | 2023 | 10.1016/j.isci.2023.106536 | iScience | 在2,230万单细胞转录组上的生成式预训练模型，用于细胞解读和临床转化。 |
| CellFM | CellFM: a large-scale foundation model pre-trained on transcriptomics of 100 million human cells | Yuansong Zeng | 2025 | 10.1038/s41467-025-59926-5 | Nature Communications | 8亿参数基础模型，在1亿人类细胞转录组上预训练。 |
| Nicheformer | Nicheformer: a foundation model for single-cell and spatial omics | Alejandro Tejada-Lapuerta | 2025 | 10.1038/s41592-025-02814-z | Nature Methods | 单细胞和空间组学基础模型，在SpatialCorpus-110M（1.1亿+细胞）上训练，捕获空间微环境。 |
| scMulan | scMulan: A multitask generative pre-trained language model for single-cell analysis | Haiyang Bian | 2024 | RECOMB 2024 | RECOMB 2024 | 多任务生成式预训练单细胞语言模型，将细胞编码为结构化"c-句子" |
| Cell2Sentence | Cell2Sentence: Teaching large language models the language of biology | Daniel Levine | 2024 | ICML 2024 | ICML 2024 | 将基因表达数据转化为自然语言句子，使LLM(如GPT-2)适应单细胞转录组学 |
| GET | GET: A foundation model of transcription across human cell types | Xi Fu | 2025 | 10.1038/s41586-024-08391-z | Nature | 通用表达Transformer，从染色质可及性和序列预测213种人类细胞类型基因表达 |
| GenePT | GenePT: A simple but effective foundation model for genes and cells built from ChatGPT | Yiqun Chen | 2024 | — | bioRxiv | 利用ChatGPT嵌入构建的简单高效基因和细胞基础模型 |
| LangCell | LangCell: Language-cell pre-training for cell identity understanding | Suyuan Zhao | 2024 | arXiv:2405.06708 | arXiv | 自然语言与单细胞转录组联合预训练，增强细胞身份理解 |
| CellVQ | Illuminating cell states by a comprehensive and interpretable single cell foundation model | — | 2026 | 10.1038/s41467-026-70071-5 | Nature Communications | 综合可解释单细胞基础模型，在6800万细胞上训练 |
| scKGBERT | scKGBERT: A knowledge-enhanced foundation model for single-cell transcriptomics | — | 2025 | doi:10.1186/s13059-025-03862-6 | Genome Biology | 知识图谱增强的单细胞转录组基础模型 |
| SATURN | Toward universal cell embeddings: integrating scRNA-seq datasets across species | Rosen et al. | 2024 | doi:10.1038/s41592-024-02191-z | Nature Methods | 跨物种通用细胞嵌入框架，整合不同物种的scRNA-seq数据。 |
| scTab | scTab: Scaling cross-tissue single-cell annotation models | Felix Fischer | 2024 | 10.1038/s41467-024-51059-5 | Nature Communications | 可扩展深度学习模型，在2200万细胞上训练，用于跨组织细胞类型注释。 |
| scPRINT | scPRINT: pre-training on 50 million cells allows robust gene network predictions | Jérémie Kalfon | 2025 | 10.1038/s41467-025-58699-1 | Nature Communications | Transformer基础模型，在5000万细胞上训练，用于鲁棒基因网络推断。 |
| scPRINT-2 | scPRINT-2: Towards the next-generation of cell foundation models | Kalfon et al. | 2025 | doi:10.64898/2025.12.11.693702 | bioRxiv | 下一代细胞基础模型，训练于16个物种的3.5亿细胞。 |
| scELMo | scELMo: Embeddings from Language Models are Good Learners for Single-cell Data Analysis | Tianyu Liu | 2023 | 10.1101/2023.12.07.569910 | bioRxiv | 语言模型嵌入应用于单细胞数据分析。 |
| scVI | scVI: Variational Inference for Single-Cell Gene Expression | Lopez et al. | 2018 | doi:10.1038/s41592-018-0229-2 | Nature Methods | 为单细胞转录组分析提供概率框架的深度生成模型。 |
| scANVI | scANVI: semi-supervised integration of single-cell multi-omic data | Xu et al. | 2021 | doi:10.15252/msb.20209620 | Molecular Systems Biology | 用于整合单细胞多组学数据的半监督深度生成模型。 |
| totalVI | Joint probabilistic modeling of single-cell multi-omic data with totalVI | Gayoso et al. | 2021 | doi:10.1038/s41592-020-01050-x | Nature Methods | 用于同时分析RNA和蛋白质单细胞数据的联合概率模型。 |
| scPoli | Population-level integration of single-cell datasets enables multi-scale analysis | De Donno et al. | 2023 | doi:10.1038/s41592-023-02035-2 | Nature Methods | 群体级单细胞数据集整合，实现多尺度生物学分析。 |
| scHyena | scHyena: Foundation Model for Full-Length Single-Cell RNA-Seq Analysis in Brain | Gyutaek Oh | 2023 | arXiv:2310.02713 | arXiv | 基于Hyena架构的基础模型，用于脑组织全长度scRNA-seq分析。 |
| TOSICA | TOSICA: Transfer of Omics Single-Cell Analysis | — | 2023 | 10.1038/s41467-023-44066-5 | Nature Communications | 跨数据集和模态的单细胞组学分析迁移学习框架。 |
| xTrimoGene | xTrimoGene: An Efficient and Scalable Representation Learner for Single-Cell RNA-Seq Data | — | 2023 | OpenReview:gdwcoBCMVi | NeurIPS 2023 | 使用非对称编码器-解码器架构的高效可扩展scRNA-seq表征学习器。 |
| CancerFoundation | A single-cell RNA sequencing foundation model to decipher drug resistance in cancer | — | 2024 | doi:10.1101/2024.11.01.621087 | bioRxiv | 用于解析药物耐药机制的癌症特异性scRNA-seq基础模型。 |
| Cell-GraphCompass | Cell-GraphCompass: modeling single cells with graph structure foundation model | Chen Fang | 2025 | 10.1093/nsr/nwaf255 | National Science Review | 图结构基础模型，使用基于图的细胞表示进行单细胞分析。 |
| scLong | scLong: A billion-parameter foundation model for capturing long-range gene context | — | 2026 | doi:10.1038/s41467-026-69102-y | Nature Communications | 十亿参数基础模型，同时关注所有28,000个基因以捕获长程上下文。 |
| Tahoe-x1 | Tahoe-x1: Scaling Perturbation-Trained Single-Cell Foundation Models to 3 Billion Parameters | Shreshth Gandhi | 2025 | 10.1101/2025.10.23.683759 | bioRxiv | 30亿参数扰动训练单细胞基础模型，用于预测细胞响应。 |
| PULSAR | PULSAR: a Foundation Model for Multi-scale and Multicellular Biology | Kuan Pang | 2025 | 10.1101/2025.11.24.685470 | bioRxiv | 多尺度基础模型，整合3600万+细胞用于多细胞生物学分析。 |
| TranscriptFormer | A Cross-Species Generative Cell Atlas Across 1.5 Billion Years of Evolution | — | 2025 | doi:10.1101/2025.04.25.650731 | bioRxiv | 跨越15亿年进化的跨物种生成式细胞图谱基础模型。 |
| TCRfoundation | TCRfoundation: A multimodal foundation model for single-cell immune profiling | — | 2025 | — | Preprint | 多模态基础模型，整合基因表达和TCR序列数据用于单细胞免疫分析 |
| CELLama | CELLama: Foundation Model for Single Cell and Spatial Transcriptomics | — | 2024 | doi:10.1101/2024.05.08.593094 | bioRxiv | 利用语言模型能力的细胞嵌入模型，用于单细胞和空间转录组学。 |
| scPROTEIN | scPROTEIN: versatile deep graph contrastive learning framework for single-cell proteomics | — | 2024 | doi:10.1038/s41592-024-02214-9 | Nature Methods | 用于单细胞蛋白质组学嵌入和分析的图对比学习框架。 |
| TEDDY | TEDDY: A Family of Foundation Models for Understanding Single Cell Biology | — | 2025 | arXiv:2503.03485 | ICML Workshop | 面向全面单细胞生物学理解的基础模型家族。 |
| Tabula | Tabula: A Tabular Self-Supervised Foundation Model for Single-Cell Transcriptomics | — | 2025 | NeurIPS 2025 Poster #117659 | NeurIPS 2025 | 面向单细胞转录组学数据的表格自监督基础模型。 |
| ChromFound | ChromFound: Towards A Universal Foundation Model for Single-Cell Chromatin Accessibility Data | — | 2025 | arXiv:2505.12638 | NeurIPS 2025 | 用于单细胞染色质可及性(scATAC-seq)数据分析的通用基础模型。 |
| EpiFoundation | EpiFoundation: A Foundation Model for Single-Cell ATAC-seq via Peak-to-Gene Alignment | — | 2025 | doi:10.1101/2025.02.05.636688 | bioRxiv | 使用峰-基因比对的scATAC-seq表观基因组分析基础模型。 |
| SCARF | SCARF: Single Cell ATAC-seq and RNA-seq Foundation model | — | 2025 | doi:10.1101/2025.04.07.647689 | bioRxiv | 联合建模scATAC-seq和scRNA-seq数据的多模态基础模型。 |
| CAPTAIN | CAPTAIN: A multimodal foundation model pretrained on co-assayed single-cell RNA and protein | — | 2025 | doi:10.1101/2025.07.07.663366 | bioRxiv | 用于共检测scRNA和蛋白质数据整合的多模态基础模型。 |
| OKR-Cell | OKR-Cell: Open world knowledge aided single-cell foundation model with cross-modal pre-training | — | 2025 | arXiv | arXiv | 开放世界知识增强的单细胞基础模型，跨模态预训练 |
| GeneJepa | GeneJepa: A predictive world model of the transcriptome | — | 2025 | arXiv | arXiv | 转录组预测世界模型，基于JEPA架构 |
| VCWorld | VCWorld: Biological world model for virtual cell simulation | — | 2025 | arXiv | arXiv | 虚拟细胞模拟的生物世界模型 |
| CellHermes | CellHermes: Harmonizing multimodal data for omics understanding | — | 2025 | arXiv | arXiv | 多模态数据协调的组学理解模型 |
| CellTok | CellTok: Early-fusion multimodal LLM for single-cell transcriptomics via tokenization | — | 2025 | arXiv | arXiv | 基于token化的早期融合多模态单细胞转录组LLM |
| sciLaMA | sciLaMA: Single-cell representation learning leveraging prior knowledge from LLMs | — | 2025 | arXiv | arXiv | 利用LLM先验知识的单细胞表示学习 |
| scConcept | scConcept: Contrastive pretraining for technology-agnostic single-cell representations | — | 2025 | arXiv | arXiv | 对比预训练的技术无关单细胞表示学习 |
| scLinguist | scLinguist: Hyena-based foundation model for cross-modality translation in single-cell multi-omics | — | 2025 | arXiv | arXiv | 基于Hyena的单细胞多组学跨模态翻译基础模型 |
| scNET | scNET: Context-specific gene and cell embeddings by integrating scRNA with PPI | — | 2025 | arXiv | arXiv | 整合scRNA和PPI的上下文特异性基因和细胞嵌入 |
| scLAMBDA | scLAMBDA: Modeling single-cell multi-gene perturbation responses | — | 2025 | arXiv | arXiv | 单细胞多基因扰动响应建模 |
| GeneMamba | GeneMamba: An Efficient and Effective Foundation Model on Single Cell Data | — | 2025 | arXiv:2504.16956 | arXiv | 基于Mamba架构的高效单细胞基础模型，可扩展且计算高效 |
| Atacformer | Atacformer: Transformer-based foundation model for ATAC-seq data analysis | — | 2025 | arXiv | arXiv | 基于Transformer的ATAC-seq数据分析基础模型，用于表观基因组学 |
| CLM-X | CLM-X: Cross-Modal Language Model for Single-Cell Multi-Omics | — | 2025 | — | Preprint | 跨模态单细胞语言模型，整合多组学数据实现统一的细胞表示学习。 |
| CellOracle | CellOracle: Dissecting cell identity via network inference and in silico gene perturbation | Kenji Kamimoto | 2023 | doi:10.1038/s41586-022-05688-9 | Nature | 基于基因调控网络的计算框架，模拟基因扰动对细胞身份的影响 |
| Stack | Stack: In-Context Learning of Single-Cell Biology | Mingze Dong | 2026 | 10.64898/2026.01.09.698608 | bioRxiv | Arc Institute单细胞基础模型，在1.49亿人类细胞上训练，通过上下文学习实现零样本预测。 |
| Lingshu-Cell | Lingshu-Cell: cellular world model for transcriptome modeling | Alibaba DAMO | 2026 | arXiv:2603.25240 | arXiv | 灵枢-细胞：掩码离散扩散细胞世界模型 |
| OmniCell | OmniCell: Unified Foundation Modeling of Single-Cell and Spatial Transcriptomics | — | 2025 | doi:10.64898/2025.12.29.696804 | bioRxiv | 同时用于单细胞和空间转录组学分析的统一基础模型。 |

#### 虚拟细胞模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaCell | Towards building a World Model to simulate perturbation-induced cellular dynamics | — | 2026 | bioRxiv:2026.03.02.709176 | bioRxiv | 虚拟细胞世界模型，模拟细胞扰动响应动力学 |
| CellFluxV2 | CellFluxV2 : An Image Generative Foundation Model for Virtual Cell Modeling | Yuhui Zhang | 2026 | 10.64898/2026.01.19.696785 | bioRxiv | 基于流匹配的虚拟细胞图像建模生成基础模型。 |
| X-Cell | X-Cell: Scaling Causal Perturbation Prediction Across Diverse Cellular Contexts | Xaira Therapeutics | 2026 | bioRxiv:2026.03.18.712807 | bioRxiv | 大规模扩散语言模型，预测跨细胞环境的基因组级转录响应 |

---

<a id="life-sciences-section-05"></a>
### 多尺度生物学

#### 多尺度生物基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Xpressor | Towards foundation models that learn across biological scales | Jeremie Kalfon | 2025 | bioRxiv:2025.05.16.653447 | bioRxiv Preprint | 跨尺度学习框架，通过交叉注意力机制整合分子、细胞和组织层面的基因表达信息 |
| AIDO | Toward AI-driven digital organism: Multiscale foundation models for predicting, simulating and programming biology at all levels | Le Song | 2024 | arXiv:2412.06993 | arXiv | GenBio AI开发的AI驱动数字生物体系统，整合DNA→RNA→蛋白质→细胞多尺度基础模型 |
| CDT (Central Dogma Transformer) | Central Dogma Transformer: Towards Mechanism-Oriented AI for Cellular Understanding | Nobuyuki Ota | 2026 | arXiv:2601.01089 | arXiv Preprint | 中心法则Transformer，通过方向性交叉注意力整合DNA（Enformer）、RNA（scGPT）和蛋白质（ProteomeLM）预训练模型，模拟DNA→RNA→蛋白质信息流，生成统一的虚拟细胞嵌入 |
| CDT-II | Central Dogma Transformer II: An AI Microscope for Understanding Cellular Regulatory Mechanisms | Nobuyuki Ota | 2026 | arXiv:2602.08751 | arXiv Preprint | AI显微镜架构，通过DNA/RNA自注意力和交叉注意力建模转录调控；在K562 CRISPRi数据上达到基因平均r=0.84，恢复GFI1B调控网络（6.6倍富集），通过梯度归因预测治疗靶点下游效应 |
| CDT-III | Central Dogma Transformer III: Interpretable AI Across DNA, RNA, and Protein | Nobuyuki Ota | 2026 | arXiv:2603.23361 | arXiv Preprint | 两阶段虚拟细胞嵌入器（VCE-N核转录+VCE-C胞质翻译），将CDT扩展至完整中心法则并支持蛋白质预测；RNA r=0.843，蛋白质r=0.969，在无临床数据下重新发现阿仑单抗5/7已知临床副作用 |

---

<a id="life-sciences-section-06"></a>
### 抗体与免疫

#### 抗体语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgBERT | Large scale paired antibody language models | Henry Kenlay | 2024 | 10.1371/journal.pcbi.1012646 | PLOS Computational Biology | 基于BERT的抗体语言模型，在OAS的20亿+未配对和200万配对抗体序列上训练。 |
| IgT5 | Large scale paired antibody language models | Henry Kenlay | 2024 | 10.1371/journal.pcbi.1012646 | PLOS Computational Biology | 基于T5的配对抗体语言模型，与IgBERT配合用于抗体设计和工程。 |
| AntiBERTy | Deciphering antibody affinity maturation with language models and weakly supervised learning | Jeffrey A. Ruffolo | 2021 | arXiv:2112.07782 | arXiv | 基于BERT的模型，在5.58亿抗体序列上训练，用于亲和力成熟分析。 |
| AbLang | AbLang: an antibody language model for completing antibody sequences | Tobias H Olsen | 2022 | 10.1093/bioadv/vbac046 | Bioinformatics Advances | 抗体特异性语言模型，在OAS上训练，用于残基预测和抗体表示。 |
| AbLang2 | Addressing the antibody germline bias and its effect on language models for improved antibody design | Tobias H. Olsen | 2024 | 10.1093/bioinformatics/btae618 | Bioinformatics | 改进的配对重轻链抗体语言模型，针对种系偏差问题优化抗体设计建议。 |
| IGLOO | Tokenizing Loops of Antibodies | — | 2025 | OpenReview:usWILm9KEL | NeurIPS 2025 Workshop | 增强蛋白质语言模型的多模态抗体环区词元化器。 |
| Ab-RoBERTa | Antibody Foundational Model : Ab-RoBERTa | Eunna Huh | 2025 | arXiv:2506.13006 | arXiv | 基于RoBERTa的抗体语言模型，用于抗体位预测和抗体设计。 |
| BALM | Accurate Prediction of Antibody Function and Structure Using Bio-Inspired Antibody Language Model | Hongtai Jing | 2023 | 10.1101/2023.08.30.555473 | bioRxiv | 仿生抗体语言模型，用于预测抗体结构和功能。 |
| DASM | Separating selection from mutation in antibody language models | Frederick A Matsen | 2026 | 10.7554/elife.109644 | eLife | 深度氨基酸选择模型，在抗体序列建模中分离选择和突变。 |
| nanoBERT | nanoBERT: a deep learning model for gene agnostic navigation of the nanobody mutational space | Johannes Thorling Hadsund | 2024 | 10.1093/bioadv/vbae033 | Bioinformatics Advances | 纳米抗体特异性Transformer模型，预测VHH序列中的氨基酸替换。 |
| FAbCon | A generative foundation model for antibody sequence understanding | Justin Barton | 2024 | bioRxiv:2024.05.22.594943 | bioRxiv Preprint | 24亿参数抗体生成基础模型 |
| S2ALM | S2ALM: Sequence-Structure Pre-trained Large Language Model for Antibody | Mingze Yin | 2025 | arXiv:2411.15215 | Nature Methods 2025 | 序列-结构预训练抗体大语言模型 |

#### 抗体结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgFold | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Jeffrey A. Ruffolo | 2023 | 10.1038/s41467-023-38063-x | Nature Communications | 快速抗体结构预测，使用在5.58亿序列上预训练的语言模型和图神经网络。 |
| DeepAb | Antibody structure prediction using interpretable deep learning | Jeffrey A. Ruffolo | 2022 | 10.1016/j.patter.2021.100406 | Patterns (Cell Press) | 可解释深度学习抗体Fv结构预测模型，专注于CDR环建模。 |
| ABlooper | ABlooper: fast accurate antibody CDR loop structure prediction with accuracy estimation | Brennan Abanades | 2022 | 10.1093/bioinformatics/btac016 | Bioinformatics | 快速等变神经网络，用于带精度估计的抗体CDR环结构预测。 |
| AntiFold | AntiFold: Improved structure-based antibody design using inverse folding | Magnus Haraldson Høie | 2025 | 10.1093/bioadv/vbae202 | Bioinformatics Advances | 从ESM-IF1微调的抗体特异性逆折叠模型，从结构生成CDR序列。 |

#### 抗体设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgGM | A Generative Foundation Model for Antibody Design | Rubo Wang | 2025 | 10.1101/2025.09.12.675771 | bioRxiv | 用于全面抗体设计的生成基础模型。 |
| DiffAb | Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models | Shitong Luo | 2022 | 10.1101/2022.07.10.499510 | bioRxiv | 基于扩散的抗原特异性抗体CDR-H3设计生成模型，联合建模序列、结构和取向。 |
| dyMEAN | Full-Atom Antibody Design via dyMEAN | Xiangzhe Kong | 2023 | 10.48550/arXiv.2302.00203 | ICML 2023 | 使用动态多通道等变图网络的端到端全原子抗体设计。 |
| MEAN | Conditional Antibody Design as 3D Equivariant Graph Translation | Xiangzhe Kong | 2023 | ICLR 2023 Oral | ICLR 2023 | 用于条件抗体CDR序列-结构协同设计的3D等变图神经网络。 |
| RefineGNN | Iterative Refinement Graph Neural Network for Antibody Sequence-Structure Co-design | Wengong Jin | 2022 | arXiv:2110.04624 | ICLR 2022 | 通过自回归生成进行抗体CDR序列和3D结构协同设计的迭代细化GNN。 |
| Ophiuchus-Ab | Ophiuchus-Ab: A Versatile Generative Foundation Model for Advanced Antibody-Based Immunotherapy | Yiheng Zhu | 2025 | 10.5281/zenodo.18478480 | Zenodo | 用于抗体免疫治疗和配对抗体库生成的扩散语言模型。 |
| NanoAbLLaMA | NanoAbLLaMA: construction of nanobody libraries with protein large language models | Xin Wang | 2025 | 10.3389/fchem.2025.1545136 | Frontiers in Chemistry | 基于LLaMA2的语言模型，微调用于纳米抗体(VHH)库构建和设计。 |
| CoSiNE | CoSiNE: Conditionally Site-Independent Neural Evolution of Antibody Sequences | — | 2026 | arXiv:2602.18982 | arXiv | 条件位点独立的抗体序列神经进化模型，显式建模抗体亲和力成熟过程 |
| AbBFN2 | AbBFN2: A flexible antibody foundation model based on Bayesian Flow Networks | Bora Guloglu | 2025 | 10.1101/2025.04.29.651170 | bioRxiv | 基于贝叶斯流网络的灵活抗体基础模型，用于多目标统一建模。 |
| AntibodyDesignBFN | AntibodyDesignBFN: High-Fidelity Fixed-Backbone Antibody Design via Discrete Bayesian Flow Networks | Yue Hu | 2026 | arXiv:2601.05605 | arXiv | 使用离散贝叶斯流网络的高保真固定骨架抗体设计。 |
| AbAffinity | AbAffinity: A Large Language Model for Predicting Antibody Binding Affinity | — | 2026 | arXiv:2603.04480 | arXiv | 预测抗体结合亲和力的大语言模型 |
| CALM | CALM: Cross-attention Adaptive Immune Receptor–Antigen Language Model | — | 2026 | bioRxiv:2026.02.25.707916 | bioRxiv | 抗体-抗原特异性预测的跨注意力自适应免疫受体语言模型 |
| JAM-2 | JAM-2: Fully computational design of drug-like antibodies | Nabla Bio | 2025 | — | Technical Report | 全计算设计药物级抗体，Nabla Bio开发 |
| Chai-2 | Chai-2: Zero-shot antibody discovery | Chai Discovery | 2025 | 10.1101/2025.07.05.663018 | bioRxiv | 零样本抗体发现模型，Chai Discovery开发 |

#### TCR与免疫模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| TCR-BERT | TCR-BERT: learning the grammar of T-cell receptors for flexible antigen-binding analyses | Kevin Wu | 2024 | MLCB 2024 proceedings | PMLR v240 | 通过自监督学习在TCR序列上训练的改进BERT，捕获TCR特异性表征。 |
| tcrLM | tcrLM: a lightweight protein language model for predicting T cell receptor and epitope binding specificity | Xing Fang | 2024 | arXiv:2406.16995 | arXiv | 轻量级BERT语言模型，在1亿+ TCR CDR3序列上预训练，用于TCR-表位结合预测。 |
| TCR-GPT | TCR-GPT: Integrating Autoregressive Model and Reinforcement Learning for T-Cell Receptor Repertoires Generation | Yicheng Lin | 2024 | arXiv:2408.01156 | arXiv | 仅解码器Transformer，使用自回归建模和强化学习生成TCR序列。 |
| SCEPTR | Contrastive learning of T cell receptor representations | Yuta Nagano | 2024 | arXiv:2406.06397 | arXiv | 轻量级BERT风格Transformer，使用自对比和掩码语言预训练进行TCR分析。 |
| ERGO-II | Prediction of Specific TCR-Peptide Binding From Large Dictionaries of TCR-Peptide Pairs | Ido Springer | 2020 | 10.3389/fimmu.2020.01803 | Frontiers in Immunology | 深度学习模型(LSTM+自编码器)，使用NLP技术进行TCR-肽结合预测。 |
| mvTCR | Multi-modal generative modeling for joint analysis of single-cell T cell receptor and gene expression data | Felix Drost | 2024 | 10.1038/s41467-024-49806-9 | Nature Communications | 多模态变分自编码器，整合单细胞TCR序列和基因表达数据。 |
| NetTCR-2.0 | NetTCR-2.0 enables accurate prediction of TCR-peptide binding | Alessandro Montemurro | 2021 | 10.1038/s42003-021-02610-3 | Communications Biology | 使用配对TCRα和β序列的TCR-肽-MHC结合预测深度学习模型。 |
| TCR-TRANSLATE | Conditional generation of real antigen-specific T cell receptor sequences | Dhuvarakesh Karthikeyan | 2025 | 10.1038/s42256-025-01096-6 | Nature Machine Intelligence | 用于生成抗原特异性TCR序列的机器学习框架，包括未见过的表位。 |

---

<a id="life-sciences-section-07"></a>
### 酶工程

#### 酶工程基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| EnzyGen | Generative Enzyme Design Guided by Functionally Important Sites and Small-Molecule Substrates | Zhenqiao Song | 2024 | arXiv:2405.08205 | arXiv | 利用功能位点和底物信息的生成酶设计模型。 |
| RFdiffusion2 | Atom-level enzyme active site scaffolding using RFdiffusion2 | Woody Ahern | 2026 | 10.1038/s41592-025-02975-x | Nature Methods | 基于RFdiffusion架构的原子级酶活性位点支架工具。 |
| CLEAN | Enzyme function prediction using contrastive learning | Tianhao Yu | 2023 | 10.1126/science.adf2465 | Science | 酶EC编号预测的对比学习模型，性能超越BLAST和传统方法。 |
| CLEAN-Contact | Improved enzyme functional annotation prediction using contrastive learning with structural inference | Yuxin Yang | 2024 | 10.1038/s42003-024-07359-z | Communications Biology | CLEAN扩展版，整合蛋白质接触图改善酶功能注释。 |
| EnzBERT | Predicting enzymatic function of protein sequences with attention | Nicolas Buton | 2023 | 10.1093/bioinformatics/btad620 | Bioinformatics | 基于BERT的模型，使用注意力机制从蛋白质序列预测酶EC编号。 |
| EnzymeFlow | EnzymeFlow: Generating Reaction-specific Enzyme Catalytic Pockets through Flow Matching and Co-Evolutionary Dynamics | Chao Song | 2024 | arXiv:2410.00327 | NeurIPS 2024 | 使用流匹配设计反应特异性酶催化口袋的生成模型。 |
| EnzymeCAGE | EnzymeCAGE: A Geometric Foundation Model for Enzyme Retrieval with Evolutionary Insights | Yong Liu | 2024 | 10.1101/2024.12.15.628585 | bioRxiv → Nature Catalysis 2026 | 在约100万酶-反应对上训练的几何基础模型，用于酶检索和功能预测。 |
| CatPred | CatPred: a comprehensive framework for deep learning in vitro enzyme kinetic parameters | Veda Sheersh Boorla | 2025 | 10.1038/s41467-025-57215-9 | Nature Communications | 预测酶动力学参数(kcat、Km、Ki)的深度学习框架。 |
| UniKP | UniKP: a unified framework for the prediction of enzyme kinetic parameters | Han Yu | 2023 | 10.1038/s41467-023-44113-1 | Nature Communications | 使用预训练蛋白质语言模型预测kcat、Km和催化效率的统一深度学习框架。 |
| TurNuP | Turnover number predictions for kinetically uncharacterized enzymes using machine and deep learning | Alexander Kroll | 2023 | 10.1038/s41467-023-39840-4 | Nature Communications | 预测动力学未表征酶的转换数(kcat)的深度学习模型。 |
| EnzyControl | EnzyControl: Adding Functional and Substrate-Specific Control for Enzyme Backbone Generation | N/A | 2025 | arXiv:2510.25132 | Preprint | 具有功能控制的底物特异性酶骨架生成框架。 |
| ProtDETR | Interpretable Enzyme Function Prediction via Residue-Level Detection | Yang Zhao | 2025 | arXiv:2501.05644 | arXiv preprint | 受目标检测启发的基于注意力的残基级酶EC编号预测框架。 |
| EZpred | EZpred: improving deep learning-based enzyme function prediction using unlabeled sequence homologs | N/A | 2025 | doi:10.1101/2025.07.09.663945 | bioRxiv | 利用未标记同源序列改进酶EC预测的深度学习框架。 |
| BEC-Pred | A general model for predicting enzyme functions based on enzymatic reactions | N/A | 2024 | 10.1186/s13321-024-00827-y | Journal of Cheminformatics | 基于BERT的模型，从底物和产物的SMILES表征预测酶EC编号。 |
| HIT-EC | HIT-EC: Trustworthy prediction of enzyme commission numbers using a hierarchical interpretable transformer | — | 2026 | doi:10.1038/s41467-026-68727-3 | Nature Communications | 层次可解释Transformer预测酶EC编号，可信赖的酶功能预测 |
| ENZYME-UNIFIED | ENZYME-UNIFIED: Learning Holistic Representations of Enzyme Function with a Hybrid Interaction Model | — | 2025 | OpenReview:oTnFATrtCD | OpenReview | 酶功能全面表示学习基础模型，混合交互模型 |

---

<a id="life-sciences-section-08"></a>
### 空间转录组

#### 空间转录组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Novae | Novae: a graph-based foundation model for spatial transcriptomics data | Quentin Blampey | 2025 | 10.1038/s41592-025-02899-6 | Nature Methods | 基于图的空间转录组基础模型，在3000万细胞上训练。 |
| SpaFoundation | SpaFoundation: a visual foundation model for spatial transcriptomics | — | 2025 | doi:10.1101/2025.08.07.669202 | bioRxiv | 使用184万张组织学图像的空间转录组学视觉基础模型。 |
| STPath | STPath: a generative foundation model for integrating spatial transcriptomics and WSIs | — | 2025 | doi:10.1038/s41746-025-02020-3 | npj Digital Medicine | 整合空间转录组学与全切片组织学图像的生成基础模型。 |
| OmiCLIP | A visual–omics foundation model to bridge histopathology with spatial transcriptomics | Weiqing Chen | 2025 | 10.1038/s41592-025-02707-1 | Nature Methods | 视觉-组学基础模型，连接组织病理学图像和空间转录组学数据。 |
| SpatialFusion | SpatialFusion: a lightweight multimodal foundation model for spatial niche mapping with pathway-informed local to global context | — | 2026 | 10.64898/2026.03.16.712056 | bioRxiv | 轻量级多模态基础模型，整合基因表达、组织病理学和通路数据。 |
| SAGE-FM | SAGE-FM: A lightweight and interpretable foundation model for spatial transcriptomics | — | 2025 | arXiv:2601.15504 | Preprint | 基于GCN的轻量级可解释空间转录组学基础模型。 |
| scGPT-spatial | scGPT-spatial: Continual Pretraining of Single-Cell FM for Spatial Transcriptomics | — | 2025 | doi:10.1101/2025.02.05.636714 | bioRxiv | 通过持续预训练将scGPT扩展到空间转录组学。 |
| SpatialScope | SpatialScope: integrating spatial and single-cell transcriptomics data using deep generative models | — | 2023 | doi:10.1038/s41467-023-43629-w | Nature Communications | 用于空间转录组学与scRNA-seq数据整合的深度生成模型。 |
| stFormer | stFormer: a foundation model for spatial transcriptomics | Shenghao Cao | 2024 | 10.1101/2024.09.27.615337 | bioRxiv | Transformer基础模型，将配体-受体相互作用整合到空间基因表示中。 |
| STAGE | STAGE: A Foundation Model for Spatial Transcriptomics Analysis via Graph Embeddings with Hierarchical Prototypes | N/A | 2026 | OpenReview:ZGzKckA29U | ICLR 2026 Submitted | 使用图嵌入和层次原型的空间转录组学基础模型。 |
| STORM | STORM: A multimodal foundation model of spatial transcriptomics and histology | — | 2026 | arXiv:2604.03630 | arXiv | 空间转录组+组织学多模态基础模型，训练于120万空间分辨谱，覆盖18个器官 |
| SEAL | SEAL: Spatial Expression-Aligned Learning for pathology foundation models | — | 2026 | arXiv:2602.14177 | arXiv | 利用空间转录组数据增强病理基础模型的空间表达对齐学习框架 |
| MINT | MINT: Molecularly Informed Training with Spatial Transcriptomics Supervision for Pathology Foundation Models | Minsoo Lee | 2026 | arXiv:2603.07895 | arXiv | 利用空间转录组学监督的分子信息训练，用于病理基础模型。 |
| HINGE | HINGE: Adapting Pre-trained Single-Cell Foundation Models to Spatial Gene Expression | — | 2026 | arXiv:2603.19766 | arXiv | 将预训练单细胞基础模型适配到空间基因表达谱，基于组织学图像条件生成 |
| HEIST | HEIST: A Graph Foundation Model for Spatial Transcriptomics and Proteomics Data | Hiren Madhu | 2025 | arXiv:2506.11152 | arXiv | 用于空间转录组学和蛋白质组学数据分析的图基础模型。 |
| TISSUENARRATOR | TissueNarrator: Generative Modeling of Spatial Transcriptomics with Large Language Models | — | 2025 | PMID:41394628 | PubMed (bioRxiv) | 基于大语言模型的空间转录组生成建模 |
| SpaTranslator | SpaTranslator: A deep generative framework for universal spatial multi-omics cross-modality translation | — | 2025 | 10.1101/2025.11.15.688644 | bioRxiv | 通用空间多组学跨模态翻译的深度生成框架 |
| SpatialProp | SpatialProp: tissue perturbation modeling with spatially resolved single-cell transcriptomics | Eric Sun | 2025 | 10.64898/2025.11.30.691355 | bioRxiv | 使用空间分辨单细胞转录组学进行组织扰动建模。 |
| SWITCH | Integrative deep learning of spatial multi-omics with SWITCH | — | 2025 | 10.1038/s43588-025-00891-w | Nature Computational Science | 空间多组学整合深度学习框架 |
| CancerSTFormer | CancerSTFormer enables multi-scale analysis of spot-resolution spatial transcriptomes and dissects the gene and immune regulatory responses of targeted therapies | N/A | 2025 | 10.1101/2025.12.22.696102 | bioRxiv | 多尺度空间转录组癌症基础模型，50µm和250µm分辨率。 |
| STAGATE | Deciphering spatial domains from spatially resolved transcriptomics with adaptive graph attention auto-encoder | Kangning Dong | 2022 | 10.1038/s41467-022-29439-6 | Nature Communications | 通过整合基因表达和空间位置进行空间域识别的图注意力自编码器。 |
| CellViT | CellViT: Vision Transformers for precise cell segmentation and classification | Fabian Hörst | 2024 | 10.1016/j.media.2024.103143 | Medical Image Analysis | 用于H&E全切片图像中精确细胞/核分割的视觉Transformer。 |
| STAMP | Interpretable spatially aware dimension reduction of spatial transcriptomics with STAMP | N/A | 2024 | 10.1038/s41592-024-02463-8 | Nature Methods | 用于空间转录组学空间感知可解释降维的深度生成模型。 |
| SpaGT | Spatially informed graph transformers for spatially resolved transcriptomics | N/A | 2025 | 10.1038/s42003-025-08015-w | Communications Biology | 整合空间坐标和基因表达的图Transformer，用于空间域识别。 |
| BrainBeacon | BrainBeacon: A Cross-Species Foundation Model for Single-cell Spatial Transcriptomics of Brain | — | 2025 | bioRxiv:2025.07.08.663729 | bioRxiv | 全球首个跨物种大脑空间转录组基础模型，整合多物种脑空间组学数据用于数字孪生大脑与靶标发现 |
| SToFM | SToFM: A multi-scale foundation model for spatial transcriptomics | — | 2025 | — | ICML 2025 | 空间转录组多尺度基础模型，整合宏观组织形态和微观细胞环境 |
| OmniCell | OmniCell: Unified Foundation Modeling of Single-Cell and Spatial Transcriptomics | — | 2025 | doi:10.64898/2025.12.29.696804 | bioRxiv | 同时用于单细胞和空间转录组学分析的统一基础模型。 |
| PAST | PAST: A multimodal single-cell foundation model for histopathology and spatial transcriptomics in cancer | Changchun Yang | 2025 | arXiv:2507.06418 | arXiv | 多模态单细胞基础模型，整合组织病理学图像和空间转录组数据用于癌症分析 |

---

<a id="life-sciences-section-09"></a>
### 糖链

#### 糖链基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GlycanGT | GlycanGT: A Foundation Model for Glycan Graphs with Pretrained Representation and Generative Learning | Akihiro Kitani | 2025 | 10.64898/2025.12.14.694171 | bioRxiv | 首个糖链图基础模型，使用图Transformer进行糖链表示和生成学习。 |
| SweetBERT | Exploring BERT-based models for IUPAC glycan nomenclature | — | 2025 | OpenReview:BC4vd3oBXs | ICLR 2025 Workshop | 基于BERT的糖链序列语言模型，编码IUPAC糖链命名法及分支结构 |
| GlycanAA | Modeling All-Atom Glycan Structures via Hierarchical Message Passing and Multi-Scale Pre-training | — | 2025 | arXiv:2506.01376 | ICML 2025 | 全原子糖链建模框架，通过层次消息传递和多尺度预训练捕获糖链精细结构 |
| MCNet | Atom-level machine learning of protein-glycan interactions and cross-chiral recognition | — | 2025 | doi:10.1126/sciadv.adx6373 | Science Advances | 原子级蛋白-糖链相互作用预测模型，能预测镜像糖链识别 |
| DeepGlycanSite | Highly accurate carbohydrate-binding site prediction with DeepGlycanSite | Xinheng He | 2024 | 10.1038/s41467-024-49516-2 | Nature Communications | 高精度深度学习模型，预测蛋白质上的碳水化合物结合位点。 |
| SweetNet | Using graph convolutional neural networks to learn a representation for glycans | Rebekka Burkholz | 2021 | 10.1016/j.celrep.2021.109251 | Cell Reports | 图卷积神经网络，用于处理复杂分支结构的糖链表示学习。 |
| GlycoBERT | Transformer-based Deep Learning for Glycan Structure Inference from MS/MS | — | 2025 | bioRxiv:2025.07.02.662857 | bioRxiv | 基于BERT的transformer，从串联质谱数据推断糖链结构 |

---

<a id="life-sciences-section-10"></a>
### 代谢组学

#### 代谢组学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MetaboLM | MetaboLM: a metabolomic language model for multi-disease early prediction and risk stratification | Shizheng Qiu | 2025 | 10.1038/s41467-025-66163-3 | Nature Communications | 基于Transformer的代谢组学语言模型，在~84,000健康血浆代谢组上训练，用于多疾病早期预测。 |
| DSCF | Deep spectral component filtering as a foundation model for spectral analysis demonstrated in metabolic profiling | Bingsen Xue | 2025 | 10.1038/s42256-025-01027-5 | Nature Machine Intelligence | 自监督深度光谱成分过滤基础模型，用于代谢谱分析。 |

---

<a id="life-sciences-section-11"></a>
### 冷冻电镜

#### 冷冻电镜基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CryoFM | CryoFM: A Flow-based Foundation Model for Cryo-EM Densities | Yi Zhou | 2024 | arXiv:2410.08631 | arXiv | 基于流匹配的基础模型，学习高质量生物分子密度图分布。 |
| Cryo-IEF | A comprehensive foundation model for cryo-EM image processing | Yang Yan | 2026 | 10.1038/s41592-025-02916-8 | Nature Methods | 综合冷冻电镜图像处理基础模型，通过对比学习在6500万粒子图像上预训练。 |
| CryoLVM | CryoLVM: Self-supervised Learning from Cryo-EM Density Maps | — | 2025/2026 | arXiv:2602.02620 | arXiv | 使用JEPA架构的自监督冷冻电镜密度图基础模型 |
| CryoNet.Refine | CryoNet.Refine: A One-step Diffusion Model for Rapid Refinement of Structural Models with Cryo-EM Density Map Restraints | Fuyao Huang | 2026 | arXiv:2602.22263 | arXiv | 单步扩散模型，使用冷冻电镜密度图约束快速精修结构模型。 |
| CryoDRGN-AI | CryoDRGN-AI: neural ab initio reconstruction for cryo-EM | — | 2025 | doi:10.1038/s41592-025-02720-4 | Nature Methods | 神经网络从头重建异质性冷冻电镜数据 |

---

<a id="life-sciences-section-12"></a>
### 宏基因组

#### 宏基因组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| METAGENE-1 | Metagenomic Foundation Model for Pandemic Monitoring | Ollie Liu | 2025 | arXiv:2501.02045 | arXiv | 70亿参数自回归Transformer，训练于>1.5万亿碱基对的宏基因组DNA/RNA，用于病原监测 |
| MGM | MGM as a large-scale pretrained foundation model for microbiome analyses in diverse contexts | Haohong Zhang | 2025 | 10.1101/2024.12.30.630825 | bioRxiv | 大规模微生物组基础模型，在>263,000微生物组样本上训练，适用于多种场景。 |
| BiomeGPT | BiomeGPT: A foundation model for the human gut microbiome | Nicholas A. Medearis | 2026 | 10.64898/2026.01.05.697599 | bioRxiv | 基于Transformer的人类肠道微生物组基础模型，在>13,300宏基因组样本上训练。 |
| GenomeOcean | GenomeOcean: Efficiently Training a Foundation Model with Large Scale Metagenomics Data | Zhihan Zhou | 2025 | 10.1101/2025.01.30.635558 | bioRxiv | 高效40亿参数基因组基础模型，在大规模宏基因组组装上训练（>600 Gbp）。 |
| MicroGenomer | MicroGenomer: A Foundation Model for Transferable Microbial Genome Representations | — | 2025 | bioRxiv:2025.12.28.696777 | bioRxiv (BGI Research) | 可迁移微生物基因组表示基础模型，训练于>234.5B碱基对，支持多尺度基因组分析 |
| Generanno | Gener anno : A Genomic Foundation Model for Metagenomic Annotation | Qiuyi Li | 2025 | 10.1101/2025.06.04.656517 | bioRxiv | 基因组基础模型，在7150亿原核生物碱基对上训练，用于宏基因组注释。 |
| FGBERT | FGBERT: Function-Driven Pre-trained Gene Language Model for Metagenomics | ChenRui Duan | 2024 | arXiv:2402.16901 | arXiv | 功能驱动预训练基因语言模型，使用蛋白质级上下文感知分词器用于宏基因组学。 |
| MetagenBERT | MetagenBERT: a Transformer Architecture using Foundational DNA Read Embedding Models for novel Metagenome Representation | Gaspar Roy | 2025 | arXiv:2601.03295 | bioRxiv | 基于Transformer的宏基因组表示框架，利用DNABERT-2/DNABERT-S直接从原始DNA读段进行疾病分类 |
| Darwin-7B | Darwin-7B: A Multi-Omic Foundation Model for the Human Gut Microbiome via Sparsified Quality-Aware Tokenization | (多作者) | 2026 | OpenReview:X5Ii21IdDF | ICLR 2026 Workshop | 70亿参数多组学基础模型，面向人类肠道微生物组，采用稀疏化质量感知tokenization进行训练。 |
| ViraLM | ViraLM: virus discovery through genome foundation model | Cheng Peng | 2024 | 10.1093/bioinformatics/btae704 | Bioinformatics | 病毒基因组基础模型 |

---

<a id="life-sciences-section-13"></a>
### 系统发育

#### 系统发育基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Phyla | Phyla: Towards a Foundation Model for Phylogenetic Inference | Andrew Shen | 2025 | bioRxiv:2025.01.17.633626 | bioRxiv Preprint | 首个系统发育推断基础模型，使用混合状态空间Transformer和树损失函数 |
| PhyloGPN | A Phylogenetic Approach to Genomic Language Modeling | — | 2024/2025 | arXiv:2503.03773 | arXiv | 基于系统发育树的基因组语言模型，利用多物种全基因组比对和进化模型 |

---

<a id="life-sciences-section-14"></a>
### 多组学整合

#### 多组学整合基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OmniBioTE | Large-Scale Multi-omic Biosequence Transformers for Modeling Protein-Nucleic Acid Interactions | — | 2024 | arXiv:2408.16245 | PLOS ONE | 大规模多组学生物序列Transformer，训练于>250B token的蛋白质和核酸序列 |
| Omni-DNA | Omni-DNA: A Unified Genomic Foundation Model for Cross-Modal and Multi-Task Learning | Zehui Li | 2025 | arXiv:2502.03499 | NeurIPS 2025 (Microsoft) | 统一基因组基础模型，支持DNA/RNA/蛋白质跨模态多任务学习 |
| OmniNA | OmniNA: A foundation model for nucleotide sequences | Xilin Shen | 2024 | 10.1101/2024.01.14.575543 | bioRxiv | 核苷酸序列基础模型，在>9170万序列（>1万亿碱基）上预训练，用于跨物种理解。 |
| spEMO | Leveraging multi-modal foundation models for analysing spatial multi-omic and histopathology data | Tianyu Liu | 2026 | 10.1038/s41551-025-01602-6 | Nature Biomedical Engineering | 多模态基础模型框架，整合空间多组学与组织病理学图像数据。 |
| scMamba | scMamba: A Scalable Foundation Model for Single-Cell Multi-Omics Integration Beyond Highly Variable Feature Selection | Zhen Yuan | 2025 | arXiv:2506.20697 | arXiv | 可扩展的基于Mamba的基础模型，无需特征选择即可整合单细胞多组学。 |

---

---

<a id="life-sciences-section-15"></a>
### 表观基因组

#### 表观基因组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CpGPT | CpGPT: a Foundation Model for DNA Methylation | Lucas Paulo de Lima Camillo | 2024 | 10.1101/2024.10.24.619766 | bioRxiv | DNA甲基化基础模型，预测CpG位点甲基化状态，用于衰老和疾病研究。 |
| MethylGPT | MethylGPT: a foundation model for the DNA methylome | Kejun Ying | 2024 | 10.1101/2024.10.30.621013 | bioRxiv | DNA甲基组基础模型，在大规模甲基化数据上预训练，用于表观遗传年龄预测和癌症分类。 |
| scDNAm-GPT | scDNAm-GPT: a foundation model for single-cell DNA methylation analysis | (多作者) | 2025 | 10.1101/2025.02.19.638959 | bioRxiv | 单细胞DNA甲基化分析基础模型，以单细胞分辨率解析表观遗传异质性。 |

---

<a id="life-sciences-section-16"></a>
### 质谱

#### 质谱基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DIA-BERT | DIA-BERT: A Foundation Model for Data-Independent Acquisition Proteomics | (多作者) | 2024 | arXiv:2403.17860 | arXiv | 基于Transformer的DIA蛋白质组学基础模型，改善肽段鉴定和定量。 |
| DreaMS | DreaMS: Deep Representations Empowering the Annotation of Mass Spectra | (多作者) | 2024 | 10.1038/s41587-025-02689-7 | Nature Biotechnology | 深度表示学习基础模型，用于质谱注释和代谢物鉴定。 |
| LSM-MS2 | LSM-MS2: A Foundation Model Bridging Spectral Identification and Biological Interpretation | (多作者) | 2025 | arXiv:2510.26715 | arXiv | 大规模串联质谱基础模型，在数百万MS2谱图上预训练，用于化合物鉴定。 |
| OmniNovo | Accurate de novo sequencing of the modified proteome with OmniNovo | (多作者) | 2025 | arXiv:2512.12272 | arXiv | 通用基础模型，直接从质谱数据进行从头肽段测序。 |
| MS-FM | Foundation model for mass spectrometry proteomics | Justin Sanders | 2025 | arXiv:2505.10848 | arXiv | 统一质谱蛋白质组学基础模型，在从头测序数据上预训练。 |
| InstaNovo | InstaNovo: diffusion-powered de novo peptide sequencing | InstaDeep | 2025 | doi:10.1038/s42256-025-01019-5 | Nature Machine Intelligence | 扩散模型从头肽段测序 |

---

---

<a id="life-sciences-section-17"></a>
### 神经科学

#### 神经科学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| VFAM | Foundation model of neural activity predicts response to new stimulus types | Eric Y. Wang | 2025 | 10.1038/s41586-025-08829-y | Nature | 神经活动基础模型，在大规模小鼠视觉皮层数据上训练，预测对新刺激类型的响应。 |

---

<a id="life-sciences-section-18"></a>
### 合成生物学

#### 合成生物学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DNA-Diffusion | Designing synthetic regulatory elements using DNA-Diffusion | — | 2025 | doi:10.1038/s41588-025-02441-6 | Nature Genetics | 生成式扩散模型设计合成DNA调控元件 |

---

> **总计 / Total: 376 models** — 蛋白质 Protein: 103 | RNA: 40 | DNA与基因组 Genomics: 41 | 单细胞 SingleCell: 63 | 多尺度生物学 MultiScale: 5 | 抗体与免疫 Antibody: 40 | 酶工程 Enzyme: 16 | 空间转录组 SpatialTranscriptomics: 25 | 糖链 Glycan: 7 | 代谢组学 Metabolomics: 2 | 冷冻电镜 CryoEM: 5 | 宏基因组 Metagenomics: 11 | 系统发育 Phylogenetics: 2 | 多组学整合 MultiOmics: 5 | 表观基因组 Epigenomics: 3 | 质谱 MassSpectrometry: 6 | 神经科学: 1 | 合成生物学: 1

## 化学

> [英文](chemistry/chemistry_en.md) | [中文](chemistry/chemistry_zh.md)

### 目录
- [小分子](#chemistry-section-01)
- [化学反应与逆合成](#chemistry-section-02)
- [蛋白质配体](#chemistry-section-03)
- [3D等变分子表示](#chemistry-section-04)
- [分子生成](#chemistry-section-05)
- [光谱与分析化学](#chemistry-section-06)
- [食品科学](#chemistry-section-07)
- [电化学](#chemistry-section-08)



<a id="chemistry-section-01"></a>
### 小分子

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MoLFormer | Large-scale chemical language representations capture molecular structure and properties | Jerret Ross | 2022 | 10.1038/s42256-022-00580-7 | Nature Machine Intelligence | 基于Transformer的化学语言模型，在11亿SMILES上使用线性注意力和旋转位置编码预训练，用于分子属性预测. |
| GP-MoLFormer | GP-MoLFormer: A Foundation Model For Molecular Generation | Jerret Ross | 2024 | arXiv:2405.04912 | Digital Discovery (RSC) | 基于Transformer的大规模分子生成基础模型，在11亿SMILES上训练的4680万参数decoder模型，用于分子生成任务。 |
| ChemBERTa | ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction | Seyone Chithrananda | 2020 | arXiv:2010.09885 | NeurIPS ML4Molecules Workshop | 基于RoBERTa架构的化学语言模型，在1000万PubChem SMILES上预训练，用于分子属性预测。 |
| ChemBERTa-2 | ChemBERTa-2: Towards Chemical Foundation Models | Walid Ahmad | 2022 | arXiv:2209.01712 | arXiv preprint | ChemBERTa的进化版本，在7700万PubChem SMILES上训练，优化了预训练方法（含多任务回归），探索化学基础模型方向。 |
| ChemFM | ChemFM as a Scaling Law Guided Foundation Model Pre-trained on Informative Chemicals | - | 2024 | arXiv:2410.21422 | Communications Chemistry | 30亿参数化学基础模型，在UniChem的1.78亿分子上使用自监督因果语言建模训练，遵循缩放定律指导。 |
| ChemDFM | Developing ChemDFM as a Large Language Foundation Model for Chemistry | - | 2024 | arXiv:2401.14818 | NeurIPS 2024 | 基于LLaMa-13B的化学领域大语言模型，在340亿token化学文献上训练，270万指令对微调。 |
| Uni-Mol | Uni-Mol: A Universal 3D Molecular Representation Learning Framework | Gengmo Zhou | 2022 | arXiv:2204.07599 | ICLR 2023 | 通用3D分子表示学习框架，直接利用分子三维结构信息进行预训练，在分子属性预测等任务达到SOTA。 |
| Uni-Mol2 | Uni-Mol2: Exploring Molecular Pretraining Model at Scale | Xiaohong Ji | 2024 | arXiv:2406.14969 | NeurIPS 2024 | 最大3D分子基础模型（11亿参数），双轨Transformer架构整合原子、图和3D几何特征，在8.84亿分子上训练。 |
| MolBERT | MolBERT: Molecular Representation Learning with Language Models and Domain-Relevant Auxiliary Tasks | Fabian Simm | 2020 | arXiv:2011.13230 | arXiv preprint | 基于BERT的分子表示学习模型（BenevolentAI），使用SMILES表示并结合自监督任务生成有意义的分子嵌入。 |
| GROVER | Self-Supervised Graph Transformer on Large-Scale Molecular Data | Yu Rong | 2020 | arXiv:2007.02835 | NeurIPS 2020 | 自监督图Transformer模型，在大规模分子数据上预训练（Tencent AI Lab），融合GNN消息传递与Transformer注意力。 |
| GEM | Geometry-enhanced molecular representation learning for property prediction | Xiaomin Fang | 2022 | 10.1038/s42256-021-00438-4 | Nature Machine Intelligence | 几何增强分子表示学习框架，利用3D空间结构信息提升属性预测d property prediction. |
| Graphormer | Do Transformers Really Perform Bad for Graph Representation? | Chengxuan Ying | 2021 | arXiv:2106.05234 | NeurIPS 2021 | 微软的图Transformer框架，在OGB-LSC分子任务中获得第一名，引入空间编码和边编码用于图结构建模。 |
| MoleculeSTM | Multi-modal molecule structure–text model for text-based retrieval and editing | Shengchao Liu | 2023 | 10.1038/s42256-023-00759-6 | Nature Machine Intelligence | 多模态模型，联合学习分子结构和文本描述，支持文本驱动的分子检索和编辑iting. |
| 3D-MoLM | Towards 3D Molecule-Text Interpretation in Language Models | Sihang Li | 2024 | arXiv:2401.13923 | ICLR 2024 | 将3D分子编码器与语言模型集成的开创性框架，通过3D分子-文本投影器实现LLM的3D分子理解能力。 |
| MolE | MolE: a foundation model for molecular graphs using disentangled attention | Oscar Méndez-Lucio | 2024 | 10.1038/s41467-024-53751-y | Nature Communications | Recursion开发的分子图基础模型，使用解耦注意力Transformer，两阶段自监督预训练于约8.42亿分子。 |
| MiniMol | MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning | Kerstin Kläser | 2024 | arXiv:2404.14986 | ICML 2024 | 参数高效的分子学习基础模型（仅1000万参数），在600万分子的3300+多样化生物活性数据上预训练。 |
| SMILES-Mamba | SMILES-Mamba: Chemical Mamba Foundation Models for Drug ADMET Prediction | - | 2024 | arXiv:2408.05696 | NeurIPS 2024 Workshop | 基于Mamba架构的化学基础模型，两阶段训练（自监督预训练+监督微调）用于药物ADMET预测。 |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | - | 2025 | IBM Research | ICLR 2025 Workshop | IBM开发的大规模SMILES编码器-解码器基础模型，在PubChem 9100万SMILES上自监督训练，用于化学和材料科学。 |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | - | 2023 | doi:10.1038/s41467-023-43214-1 | Nature Communications | 知识引导的图Transformer预训练框架，整合化学知识增强分子表示学习。 |
| GIN (Pretrained) | Strategies for Pre-Training Graph Neural Networks | Weihua Hu | 2020 | arXiv:1905.12265 | ICLR 2020 | 提出GNN预训练策略（节点级+图级），在200万分子上预训练GIN模型用于分子属性预测，开创性工作。 |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | - | 2025 | arXiv:2510.18900 | arXiv preprint | 大规模分子基础模型家族（Molecular Insight SMILES Transformers），在大量无标注分子上训练，可预测400+结构-性质关系。 |
| M2UMol | Multi-to-Uni Modal Knowledge Transfer Pre-training for Molecular Representation Learning | - | 2026 | doi:10.1038/s41467-026-69302-6 | Nature Communications | 多模态到单模态知识迁移预训练框架，将多种分子模态知识有效转移到2D编码器中。 |
| Omni-Mol | Exploring Universal Convergent Space for Omni-Molecular Tasks | Chengxin Hu | 2025 | arXiv:2502.01074 | NeurIPS 2025 | 统一语言模型，在通用收敛空间中实现任意模态分子任务。 |
| TamGen | TamGen: Drug Design with Target-Aware Molecule Generation through a Chemical Language Model | Microsoft/GHDDI | 2024 | doi:10.1038/s41467-024-53632-4 | Nature Communications | GPT风格化学语言模型，用于靶标感知的分子生成和药物设计 |
| MoleculeGPT | MoleculeGPT: Instruction Following LLMs for Molecular Property Prediction | — | 2024 | arXiv:2306.09048 | NeurIPS 2024 Workshop | 通过分子指令数据微调的LLM，用于自然语言驱动的分子属性预测 |
| SAFE-GPT | SAFE: A Molecular-Centric Foundation Model with SAFE Representation | — | 2024 | 10.1039/D4DD00019F | Digital Discovery | 使用顺序连接片段嵌入(SAFE)分子表示的基础模型，用于生成化学mistry. |
| DrugGPT | DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins | Yuesen Li | 2023 | 10.1101/2023.06.29.543848 | bioRxiv | 基于GPT的药物设计模型，生成靶向特定蛋白结合口袋的类药分子。 |
| MultiPUFFIN | Multimodal domain-constrained foundation model | — | 2026 | arXiv:2603.00857 | arXiv | 多模态域约束基础模型，整合SMILES、分子图和3D几何 |
| FragCLM | Foundation chemical language model for fragment-based drug discovery | — | 2025 | arXiv:2509.19586 | arXiv | 基于片段的药物发现化学语言基础模型 |

<a id="chemistry-section-02"></a>
### 化学反应与逆合成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Molecular Transformer | Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction | Philippe Schwaller | 2019 | doi:10.1021/acscentsci.9b00576 | ACS Central Science | 开创性的seq2seq Transformer模型，将化学反应预测建模为SMILES翻译问题，支持不确定性校准。 |
| Chemformer | Chemformer: A Pre-trained Transformer for Computational Chemistry | Ross Irwin | 2022 | doi:10.1088/2632-2153/ac3ffb | Machine Learning: Science and Technology | 基于BART架构的预训练Transformer，用于分子SMILES的化学反应预测和逆合成等计算化学任务。 |
| RXNFP | Mapping the Space of Chemical Reactions Using Attention-Based Neural Networks | Philippe Schwaller | 2021 | doi:10.1038/s42256-020-00284-w | Nature Machine Intelligence | IBM开发的Transformer模型，学习化学反应指纹（reaction fingerprints），用于反应分类和反应空间映射。 |
| T5Chem | Unified Deep Learning Model for Multitask Reaction Predictions with Explanation | Jieyu Lu | 2022 | doi:10.1021/acs.jcim.1c01467 | Journal of Chemical Information and Modeling | 基于T5的统一Transformer模型，支持多任务化学反应预测（正向预测、逆合成、产率预测等）。 |
| Llamole | Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning | Gang Liu | 2024 | arXiv:2410.04223 | NeurIPS 2024 | 多模态大语言模型，集成图扩散Transformer和GNN，支持逆向分子设计和逆合成路线规划。 |
| RetroSynFormer | Retrosynformer: Planning Multi-step Chemical Synthesis Routes via a Decision Transformer | Emma Granqvist | 2025 | doi:10.1039/D5DD00153F | Digital Discovery (RSC) | 基于决策Transformer的多步逆合成规划模型，将逆合成建模为序列预测问题。 |
| SynLlama | SynLlama: Generating Synthesizable Molecules and Their Analogs with Large Language Models | Kunyang Sun | 2025 | arXiv:2503.12602 | arXiv | 基于Meta Llama 3微调的LLM，生成可合成分子及完整合成路线。 |
| SynFormer | Generative Artificial Intelligence for Navigating Synthesizable Chemical Space | Wenhao Gao | 2024 | arXiv:2410.03494 | PNAS 2025 | 生成模型框架，专注于可合成化学空间的探索，生成分子时同时保证其可合成性。 |
| ReactionT5 | ReactionT5: a pre-trained transformer model for accurate chemical reaction prediction with limited data | Tatsuya Sagawa | 2025 | 10.1186/s13321-025-01075-4 | Journal of Cheminformatics | 基于T5的预训练Transformer，在Open Reaction Database上预训练，在有限数据下表现优异。 |
| DeepRetro | DeepRetro discovers retrosynthetic pathways through iterative large language model reasoning | Shreyas Vinaya Sathyanarayana | 2026 | 10.1038/s41598-026-38821-z | Scientific Reports | 结合LLM推理、反应模板和专家反馈的先进逆合成框架，用于迭代路径发现 discovery. |
| RXNGraphormer | A unified pre-trained deep learning framework for cross-task reaction performance prediction | Li-Cheng Xu | 2025 | doi:10.1038/s42256-025-01098-4 | Nature Machine Intelligence | 统一预训练反应图Transformer，整合GNN和Transformer学习键形成/断裂机制 |
| RSGPT | RSGPT: a generative transformer for retrosynthesis planning pre-trained on ten billion datapoints | Yafeng Deng | 2025 | doi:10.1038/s41467-025-62308-6 | Nature Communications | 在100亿数据点上预训练的逆合成规划生成Transformer |
| Chem-R | Chemical Reasoning Model | — | 2025 | arXiv:2510.16880 | NeurIPS 2025 | 化学推理模型，模拟化学家深思过程 |

<a id="chemistry-section-03"></a>
### 蛋白质配体

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Pearl | Pearl: A Foundation Model for Placing Every Atom in the Right Location | Genesis Research Team | 2025 | arXiv:2510.24670 | NeurIPS 2025 | 蛋白质-配体结构预测基础模型（Genesis Molecular AI），使用大规模合成数据和SO(3)-等变架构，超越AlphaFold 3。 |
| DiffDock | DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking | Gabriele Corso | 2023 | arXiv:2210.01776 | ICLR 2023 | 基于扩散模型的分子对接方法，将蛋白质-配体对接建模为SE(3)上的生成问题，无需先验结合位点信息。 |
| DiffDock-L | Fine-Tuning DiffDock-L for Allosteric Kinase Docking | - | 2026 | doi:10.1021/acs.jcim.5c02846 | J. Chem. Inf. Model. | DiffDock的大规模版本，针对变构激酶结合位点进行微调的扩散对接模型。 |
| NeuralPLexer | State-specific Protein-Ligand Complex Structure Prediction with a Multiscale Deep Generative Model | Zhuoran Qiao | 2024 | doi:10.1038/s42256-024-00792-z | Nature Machine Intelligence | 多尺度深度生成模型，从蛋白质序列和配体分子图直接预测蛋白质-配体复合物3D结构，包括构象变化。 |
| Uni-Mol Docking V2 | Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction | - | 2024 | arXiv:2405.11769 | arXiv preprint | Uni-Mol系列的分子对接方法，使用预训练分子和口袋编码器预测蛋白质-配体结合位姿，>77%成功率。 |
| Umol | Structure Prediction of Protein-Ligand Complexes from Sequence Information with Umol | - | 2024 | doi:10.1038/s41467-024-48837-6 | Nature Communications | 仅从氨基酸序列和SMILES预测全柔性、全原子蛋白质-配体复合物结构的AI系统。 |
| LigUnity | A Foundation Model for Protein-Ligand Affinity Prediction Through Unified Representation | - | 2025 | bioRxiv:2025.02.17.638554 | bioRxiv preprint | 统一表示学习的蛋白质-配体亲和力预测基础模型，同时支持虚拟筛选和先导优化。 |
| PhysDock | Physics-guided all-atom diffusion for protein-ligand prediction | — | 2025 | bioRxiv:2025.04.28.650887 | bioRxiv | 物理引导全原子扩散分子对接 |
| Boltz-2 | Boltz-2: binding affinity prediction of protein-ligand complexes | — | 2025 | bioRxiv:2025.06.14.659707 | bioRxiv | 蛋白质-配体亲和力预测 |

<a id="chemistry-section-04"></a>
### 3D等变分子表示

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SchNet | SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions | Kristof Schütt | 2018 | doi:10.1063/1.5019779 | J. Chem. Phys. | 连续滤波卷积神经网络，学习原子间量子相互作用的旋转不变表示，用于分子能量和力预测。 |
| ViSNet | ViSNet: An Equivariant Geometry-Enhanced Graph Neural Network with Vector-Scalar Interactive Message Passing | Yusong Wang | 2024 | doi:10.1038/s41467-024-50014-6 | Nature Communications | 矢量-标量交互消息传递的等变几何增强GNN，通过运行时几何计算避免昂贵的高阶张量运算。 |
| EPT | Equivariant Pretrained Transformer for unified 3D molecular representation | — | 2026 | Nature Communications | Nature Communications | E(3)等变全原子预训练Transformer |

<a id="chemistry-section-05"></a>
### 分子生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MolGPT | MolGPT: Molecular Generation Using a Transformer-Decoder Model | Viraj Bagal | 2022 | doi:10.1021/acs.jcim.1c00600 | J. Chem. Inf. Model. | 基于GPT的分子生成模型，使用Transformer解码器从SMILES自回归生成满足特定属性约束的分子。 |
| cMolGPT | cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific de novo Molecular Generation | Haiyan Wang | 2023 | doi:10.3390/molecules28114430 | Molecules | 条件分子GPT模型，在MolGPT基础上增加条件控制，针对特定靶点进行从头分子生成。 |
| GenMol | GenMol: A Drug Discovery Generalist with Discrete Diffusion | Seul Lee (NVIDIA) | 2025 | PMLR v267 | ICLR 2025 | 使用SAFE表示的掩码离散扩散通用分子生成模型 |
| NExT-Mol | NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | Zhiyuan Liu | 2025 | OpenReview | ICLR 2025 | 整合1D SELFIES语言建模与3D扩散的分子生成基础模型 |
| DiTMC | Sampling 3D Molecular Conformers with Diffusion Transformers | — | 2025 | arXiv:2506.15378 | NeurIPS 2025 | 基于扩散Transformer的3D分子构象生成 |
| SynCoGen | Synthesizable 3D molecule generation via joint reaction and coordinate modeling | — | 2025 | arXiv:2507.11818 | ICLR 2026 | 可合成3D分子生成 |

<a id="chemistry-section-06"></a>
### 光谱与分析化学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MolSpectLLM | MolSpectLLM: A Large Language Model for Molecular Spectroscopy Interpretation | - | 2025 | arXiv:2502.13094 | arXiv preprint | 大语言模型用于分子光谱解释，将NMR、IR、MS等多种光谱数据与分子结构关联，支持光谱到结构的推理。 |

<a id="chemistry-section-07"></a>
### 食品科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FART | A chemical language model for molecular taste prediction | Yoel Zimmermann | 2025 | 10.1038/s41538-025-00474-z | npj Science of Food | 从SMILES表示预测分子味觉属性的化学语言模型。 |

<a id="chemistry-section-08"></a>
### 电化学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

## 材料科学

> [英文](materials-science/materials-science_en.md) | [中文](materials-science/materials-science_zh.md)

### 目录
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
### 原子级力场

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
### 晶体与材料性质

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
### 通用原子模型

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
### 晶体生成与逆向设计

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
### 催化剂与表面

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
### 电子结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DeepH | Deep-learning density functional theory Hamiltonian for efficient ab initio electronic-structure calculation | He Li | 2022 | 10.1038/s43588-022-00265-6 | Nature Computational Science | 深度学习模型，直接预测DFT哈密顿矩阵，加速从头算电子结构计算。ic structure calculations. |
| DeepH-E3 | DeepH-E3: E(3)-Equivariant Deep Learning for Efficient ab initio Electronic Structure | Xiaoxun Gong | 2023 | doi:10.1038/s41467-023-38468-8 | Nature Communications | DeepH的E(3)-等变版本，利用等变神经网络更准确高效地预测哈密顿量矩阵元素。 |
| HamGNN | HamGNN: Graph Neural Networks for Predicting Hamiltonian Matrix | Zijie Yang | 2023 | arXiv:2305.10844 | arXiv preprint | 用于哈密顿矩阵预测的图神经网络，通过等变消息传递直接预测DFT精度的电子结构。 |
| NextHAM | NextHAM: Next-Generation Hamiltonian Prediction with Equivariant Graph Neural Networks | - | 2024 | arXiv:2405.xxxxx | arXiv preprint | 新一代哈密顿量预测模型，改进等变GNN架构实现更大规模材料体系的电子结构预测。 |
| MACE-H | Equivariant electronic Hamiltonian prediction with many-body message passing | — | 2026 | 10.1038/s41524-026-02020-1 | npj Computational Materials | 基于MACE的等变电子哈密顿量预测 |

<a id="materials-science-section-07"></a>
### 聚合物与软物质

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| polyBERT | polyBERT: a chemical language model to enable fully machine-driven ultrafast polymer informatics | Christopher Kuenneth | 2023 | 10.1038/s41467-023-39868-6 | Nature Communications | 基于BERT的化学语言模型，在聚合物SMILES上训练，用于超快速聚合物属性预测。on. |
| polyGNN | polyGNN: Multitask Graph Neural Networks for Polymer Informatics | Rishi Gurnani | 2023 | doi:10.1021/acs.chemmater.2c02991 | Chemistry of Materials | 多任务图神经网络用于聚合物信息学，支持多性质同时预测和聚合物结构-性质关系学习。 |
| polyBART | polyBART: A Generative Transformer for Polymer Design | - | 2024 | arXiv:2404.xxxxx | arXiv preprint | 基于BART的聚合物生成Transformer，支持条件生成和性质导向的聚合物逆向设计。 |
| POLYT5 | POLYT5: an encoder-decoder foundation chemical language model for generative polymer design | — | 2026 | 10.1038/s44387-026-00087-1 | npj Artificial Intelligence | T5编码器-解码器聚合物设计基础语言模型 |

<a id="materials-science-section-08"></a>
### 电池与能源材料

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BatteryBERT | BatteryBERT: A Pretrained Language Model for Battery Research | Shu Huang | 2022 | doi:10.1021/acs.jcim.2c00035 | J. Chem. Inf. Model. | 电池研究领域预训练语言模型，在电池文献语料上微调BERT，支持电池文本挖掘和信息提取。 |
| BatteryFormer | BatteryFormer: Graph Transformer for Battery Material Property Prediction | - | 2024 | arXiv:2404.xxxxx | arXiv preprint | 面向电池材料的图Transformer模型，预测电极材料容量、电压和循环寿命等关键性质。 |

<a id="materials-science-section-09"></a>
### 基础GNN架构

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SchNet | SchNet: A Continuous-Filter Convolutional Neural Network for Modeling Quantum Interactions | Kristof Schütt | 2017 | arXiv:1706.08566 | NeurIPS 2017 | 连续滤波卷积神经网络，开创性地将原子间距离编码为连续表示，建模量子相互作用。 |

<a id="materials-science-section-10"></a>
### 超材料

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MetaFO | Toward a robust and generalizable metamaterial foundation model | Namjung Kim | 2025 | 10.1038/s41524-025-01925-7 | npj Computational Materials | 贝叶斯Transformer超材料基础模型，用于零样本结构-属性预测。 |

<a id="materials-science-section-11"></a>
### 超导体

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| BEE-NET | Developing a complete AI-accelerated workflow for superconductor discovery | Jason B. Gibson | 2026 | 10.1038/s41524-026-01964-8 | npj Computational Materials | 等变GNN，预测Eliashberg谱函数和临界温度，用于超导体发现。r discovery. |
| DeeperBand | A deep learning approach to search for superconductors from electronic bands | — | 2025 | doi:10.1088/3050-287X/adf6cb | IOPscience | 对称感知3D Vision Transformer，从电子能带结构预测超导性 |

## 物理学

> [英文](physics/physics_en.md) | [中文](physics/physics_zh.md)

### 目录
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
### 粒子物理

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FM4NPP | A Scaling Foundation Model for Nuclear and Particle Physics | Yihui Ren | 2025 | 2508.14087 | ICLR 2026 | 大规模自监督基础模型，针对核物理与粒子物理稀疏探测器数据，训练于1100万+碰撞事件，在sPHENIX等实验中取得SOTA |
| OmniLearn | OmniLearn: A Method to Simultaneously Facilitate All Jet Physics Tasks | Vinicius Mikuni | 2024 | 2404.16091 | arXiv preprint | 多任务喷注物理基础模型，通过多类分类预训练学习通用表征，可同时服务于喷注标记、生成等多个任务 |
| OmniLearned | Foundation model framework for all tasks involving jet physics | Wahid Bhimji | 2026 | 10.1103/knmd-f5jm | Physical Review D | 升级版OmniLearn框架，在10亿+喷注事件上用Transformer架构训练，支持喷注分类、回归等任务。 and generation. |
| OmniJet-α | OmniJet-α: the first cross-task foundation model for particle physics | Joschka Birk | 2024 | 10.1088/2632-2153/ad66ad | Machine Learning: Science and Technology | 首个跨任务粒子物理基础模型，同时支持喷注生成和喷注标记。 |
| Bumblebee | Bumblebee: Foundation Model for Particle Physics Discovery | Andrew J. Wildridge | 2024 | 2412.07867 | NeurIPS 2024 Workshop | 受BERT启发的粒子物理基础模型，嵌入粒子四动量向量，去除位置编码，捕获生成级和重建级信息 |
| EveNet | EveNet: A Foundation Model for Particle Collision Data Analysis | Ting-Hsiang Hsu | 2026 | 2601.17126 | arXiv preprint | 事件级碰撞数据基础模型，预训练于5亿模拟碰撞事件，采用混合自监督学习，支持多任务分析与生成 |
| HEP-JEPA | HEP-JEPA: A foundation model for collider physics using joint embedding predictive architecture | Jai Bardhan | 2025 | 2502.03933 | arXiv preprint | 基于联合嵌入预测架构(JEPA)的对撞机物理基础模型，用于喷注标记等下游任务，自监督预训练 |
| JetCLR | Symmetries, Safety, and Self-Supervision | Barry M. Dillon | 2021 | 2108.04253 | SciPost Phys. 2022 | 基于对比学习的自监督喷注表征框架，利用排列不变transformer编码器和对称性增强，学习物理感知表征 |
| CaloFM | Foundation Model for Calorimetry via MoE | — | 2026 | arXiv:2603.28804 | arXiv | MoE量热器模拟基础模型 |
| JetFormer | Scalable Transformer for Jet Tagging | — | 2026 | arXiv:2601.17215 | arXiv | 可扩展Transformer喷注标记 |
| PanopTag | PanopTag: Simultaneously Tagging All Jets in a Particle Collision Event | Umar Sohail Qureshi | 2026 | 2601.16417 | arXiv preprint | 首个同时标记碰撞事件中所有喷注的方法，采用编码器-解码器transformer架构，利用事件级上下文 |
| TrackingBERT | A Language Model for Particle Tracking | Andris Huang | 2024 | 2402.10239 | arXiv preprint | 基于BERT的粒子径迹重建基础模型，将探测器数据标记化处理，用于LHC中的粒子径迹寻找 |

---

<a id="physics-section-02"></a>
### 流体动力学与PDE求解

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FNO | Fourier Neural Operator for Parametric Partial Differential Equations | Zongyi Li | 2020 | 2010.08895 | ICLR 2021 | 开创性的神经算子架构，在傅里叶空间中学习函数映射，分辨率无关，高效求解参数化PDE |
| DeepONet | Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators | Lu Lu | 2021 | DOI:10.1038/s42256-021-00302-5 | Nature Machine Intelligence 2021 | 基于算子万能逼近定理的深度算子网络，通过branch/trunk网络学习连续非线性算子，广泛应用于PDE求解 |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators | Jaideep Pathak | 2022 | arXiv:2202.11214 | arXiv | NVIDIA高分辨率全球天气预报模型，基于自适应傅里叶神经算子，0.25°分辨率。 |
| Poseidon | Poseidon: Efficient Foundation Models for PDEs | Maximilian Herde | 2024 | 2405.19101 | NeurIPS 2024 | 高效PDE基础模型，采用多尺度算子transformer与时间条件层归一化，在多物理场流体动力学数据上预训练 |
| MPP | Multiple Physics Pretraining for Physical Surrogate Models | Michael McCabe | 2023 | 2310.02994 | NeurIPS 2024 | 多物理预训练方法，task-agnostic的transformer架构，在多种时空物理系统上自回归预训练，增强泛化能力 |
| ICON / ICON-LM | In-context operator learning with data prompts for differential equation problems | Liu Yang | 2023 | DOI:10.1073/pnas.2310142120 | PNAS 2023 | 上下文算子学习网络，单一模型通过数据提示学习多种PDE的求解算子，无需重新训练，ICON-LM扩展至语言模型微调 |
| VICON | VICON: Vision In-Context Operator Networks for Multi-Physics Fluid Dynamics | Yuxuan Cao | 2024 | 2411.16063 | arXiv preprint | 视觉上下文算子网络，将vision transformer引入多物理场流体动力学预测，处理不可压/可压Navier-Stokes等方程 |
| DPOT | DPOT: Auto-Regressive Denoising Operator Transformer for Large-Scale PDE Pre-Training | Zhongkai Hao | 2024 | 2403.03542 | ICML 2024 | 大规模PDE预训练的自回归去噪算子Transformer，基于Fourier attention，处理复杂长程PDE动力学。 |
| PROSE-PDE | Towards a Foundation Model for Partial Differential Equations: Multi-Operator Learning and Extrapolation | Jingmin Sun | 2024 | 2404.12355 | Phys. Rev. E 2025 | 多模态PDE基础模型，支持多算子学习与外推，同时预测系统演化和识别底层方程 |
| PROSE-FD | PROSE-FD: A Multimodal PDE Foundation Model for Learning Fluid Dynamics | Jingmin Sun | 2024 | 2409.09811 | arXiv preprint | 面向流体动力学的多模态零样本PDE基础模型，支持浅水方程和Navier-Stokes方程在多种几何条件下的预测 |
| OmniArch | OmniArch: Building Foundation Model for Scientific Computing | Tianyu Chen | 2024 | 2402.16014 | ICML 2025 | 多尺度多物理科学计算基础模型，整合Fourier编解码器架构，支持1D/2D/3D PDE模拟 |
| Unisolver | Unisolver: PDE-Conditional Transformers Are Universal PDE Solvers | Minkai Xu | 2024 | 2405.17527 | NeurIPS 2024 | 通用PDE求解器，基于PDE条件化的Transformer，在多种PDE数据上预训练，利用方程/系数/边界条件信息 |
| PINO | Physics-Informed Neural Operator for Learning Partial Differential Equations | Zongyi Li | 2021 | 2111.03794 | ACM/JCP 2024 | 物理信息神经算子，结合数据驱动与物理约束损失，无需大量标注数据即可学习PDE族的求解算子 |
| PI-MFM | PI-MFM: Physics-informed multimodal foundation model for solving partial differential equations | — | 2024 | 2512.23056 | arXiv preprint | 物理信息多模态基础模型，将物理先验嵌入PDE基础模型，减少对数据的依赖 |
| Walrus | Walrus: A Cross-Domain Foundation Model for Continuum Dynamics | Polymathic AI | 2025 | 2511.15684 | arXiv preprint | 1.3B参数连续介质动力学跨域基础模型，在19个物理系统上预训练，支持流体、固体等多种连续介质仿真 |
| DISCO | DISCO: Learning to DISCover an Evolution Operator for Multi-Physics-Agnostic Prediction | — | 2025 | arXiv:2504.19496 | arXiv preprint | 多物理场景无关的演化算子发现方法，用于高效PDE求解与泛化 |
| LFNO | Latent Fourier Neural Operator | — | 2024 | — | arXiv preprint | 潜空间傅里叶神经算子，在低维潜空间中执行傅里叶变换，提高计算效率 |
| RNO | Recurrent Neural Operator | — | 2024 | — | arXiv preprint | 递归神经算子，结合递归结构处理时间序列PDE动力学 |
| MINO | Masked Implicit Neural Operator | — | 2024 | — | arXiv preprint | 掩码隐式神经算子，通过掩码策略增强算子学习的泛化能力 |
| TNO | Transolver / Transformer Neural Operator | — | 2024 | — | arXiv preprint | 基于Transformer的神经算子，处理复杂几何和非规则网格上的PDE |
| HyPINO | Hybrid Physics-Informed Neural Operator | — | 2024 | — | arXiv preprint | 混合物理信息神经算子，结合物理约束与数据驱动学习，增强PDE求解精度 |
| PI-Latent-NO | Physics-Informed Latent Neural Operator | — | 2024 | — | arXiv preprint | 物理信息潜空间神经算子，在潜空间中融合物理方程约束进行PDE求解 |
| Transolver | Transolver: A Fast Transformer Solver for PDEs on General Geometries | Wu et al. | 2024 | arXiv:2402.02366 | ICML 2024 | 基于Physics-Attention的Transformer PDE求解器，支持任意几何，多基准SOTA |
| SFNO | Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere | Boris Bonev (NVIDIA) | 2023 | arXiv:2306.03838 | ICML 2023 | 球面傅里叶神经算子，FourCastNet V2的基础架构，用于全球天气预测 |
| WIND | WIND: Weather Inverse Diffusion for Zero-Shot Atmospheric Modeling | Michael Aich | 2026 | arXiv:2602.03924 | arXiv | 基于逆扩散的零样本大气建模基础模型。 |
| STAR-MD | Scalable Spatio-Temporal SE(3) Diffusion for Long-Horizon Protein Dynamics | Nima Shoghi | 2026 | arXiv:2602.02128 | arXiv | 可扩展SE(3)等变扩散模型，用于模拟长时间尺度蛋白质动力学。 |
| MORPH | Shape-agnostic PDE Foundation Models | — | 2025 | arXiv:2509.21670 | ICLR 2026 | 形状无关自回归PDE基础模型 |
| PDEformer-2 | Versatile Foundation Model for 2D PDEs | — | 2025 | arXiv:2507.15409 | arXiv | 通用2D PDE基础模型，编码方程结构为计算图 |
| NESTOR | Nested MOE Neural Operator for Large-Scale PDE Pre-Training | — | 2026 | arXiv:2602.22059 | arXiv | 嵌套MoE神经算子大规模PDE预训练 |

---

<a id="physics-section-03"></a>
### 通用物理仿真

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GPhyT | Towards a Physics Foundation Model | Florian Wiesner | 2025 | arXiv:2509.13805 | arXiv | 通用物理Transformer，在1.8 TB多样化模拟数据上训练，可零样本泛化到未见物理系统。 scenarios. |
| PhysiX | PhysiX: A Foundation Model for Physics Simulations | Tung Nguyen | 2025 | 2506.17774 | NeurIPS 2025 | 45亿参数的物理仿真基础模型，采用离散tokenizer编码多尺度物理过程，自回归生成，克服物理数据稀缺 |
| PDE-Transformer | PDE-Transformer: Efficient and Versatile Transformers for Physics Simulations | — | 2025 | arXiv:2505.24717 | arXiv preprint | 面向多种PDE类型的可扩展transformer架构，增强正则网格上的代理建模效率 |
| M2PDE | M2PDE: Compositional Generative Multiphysics and Multi-component PDE Simulation | — | 2024 | 2412.04134 | arXiv preprint | 组合生成式多物理/多组分PDE仿真框架，基于扩散模型，处理复杂耦合物理系统 |
| UPS | Unified PDE Solvers | — | 2024 | 2403.07187 | arXiv preprint | 统一PDE求解器基础模型，高效解决跨域、跨维度、跨分辨率的时空PDE，支持多种物理场景 |
| CompNO | CompNO: A Novel Foundation Model approach for solving Partial Differential Equations | Hamda Hmida | 2026 | arXiv:2601.07384 | arXiv | 组合神经算子，将单体模型拆分为可组合模块，实现高效参数化PDE求解。 |
| GNS | Learning to Simulate Complex Physics with Graph Networks | Alvaro Sanchez-Gonzalez | 2020 | 2002.09405 | ICML 2020 | DeepMind提出的图网络模拟器(GNS)，学习粒子交互规则，可泛化模拟流体、刚体、可变形物体等复杂物理系统 |
| MeshGraphNets | Learning Mesh-Based Simulation with Graph Networks | Tobias Pfaff | 2021 | 2010.03409 | ICLR 2021 | 基于网格的图网络仿真方法，在非结构化网格上学习物理动力学，支持空气动力学和结构力学等 |
| GeoPT | Scaling Physics Simulation via Lifted Geometric Pre-Training | Haixu Wu | 2026 | arXiv:2602.20399 | arXiv | 几何预训练物理模拟基础模型 |
| Cosmos | Cosmos World Foundation Model Platform for Physical AI | — | 2025 | — | NVIDIA | NVIDIA开源世界基础模型平台，生成物理感知视频和交互式3D环境 |

---

<a id="physics-section-04"></a>
### 物理世界模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Genie | Genie: Generative Interactive Environments | Jake Bruce | 2024 | 2402.15391 | ICML 2024 | DeepMind开发的110亿参数无监督世界模型，从未标注视频中学习，可从单张图片生成可交互的虚拟世界 |
| Genie 2 | Genie 2: A large-scale foundation world model | — | 2024 | — | DeepMind | 升级版Genie，从单张图像生成多样、可控的交互式3D环境 |
| Genie 3 | Genie 3: A new frontier for world models | — | 2025 | — | DeepMind | 通用世界模型，从文本或图像实时生成一致的交互式3D世界 |
| DIAMOND | Diffusion for World Modeling: Visual Details Matter in Atari | Eloi Alonso | 2024 | 2405.12399 | NeurIPS 2024 (Spotlight) | 基于扩散模型的世界建模方法，在Atari环境中实现高视觉保真度的RL智能体训练，保留细节信息 |
| WorldDreamer | WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens | Xiaofeng Wang | 2024 | arXiv:2401.09985 | arXiv | 通用世界模型，通过掩码词元预测捕获多环境物理动力学，用于视频生成。ation. |
| GameNGen | Diffusion Models Are Real-Time Game Engines | Dani Valevski | 2024 | arXiv:2408.14837 | arXiv | Google Research神经游戏引擎，使用扩散模型模拟复杂游戏环境(DOOM)达20+fps。 |
| OASIS | Oasis: A Universe in a Transformer | — | 2024 | — | arXiv | 实时开放世界AI模型，通过Transformer以20fps生成类Minecraft交互式游戏体验 |
| Pandora | Pandora: Towards General World Model with Natural Language Actions and Video States | Jiannan Xiang | 2024 | arXiv:2406.09455 | arXiv | 混合自回归-扩散世界模型，通过自然语言动作控制视频状态生成。 |
| UniSim | Learning Interactive Real-World Simulators | Mengjiao Yang | 2023 | 2310.06114 | ICLR 2024 | 通用世界模拟器，学习模拟人与世界的多样交互，可从文本/动作/图像输入生成真实世界仿真 |
| PAN | PAN: A World Model for General, Interactable, and Long-Horizon World Simulation | PAN Team | 2025 | arXiv:2511.09057 | arXiv | 动作条件化世界模型，支持通用、可交互、长时间尺度的模拟，保持环境动力学一致性。 |
| PhysDreamer | PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation | Tianyuan Zhang | 2024 | 2404.13026 | ECCV 2024 | 基于物理的3D对象交互生成模型，通过视频生成实现物理一致性的物体交互仿真 |
| Astra | General Interactive World Model with Autoregressive Denoising | — | 2024 | arXiv:2512.08931 | ICLR 2026 | 自回归去噪通用交互世界模型 |

---

<a id="physics-section-05"></a>
### 量子物理与多体系统

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FNQS | Foundation Model for Quantum Many-Body States via Transformers | — | 2025 | 10.1038/s41467-025-62098-x | Nature Communications 2025 | 基于Transformer的量子多体系统基础模型，预训练于大量量子态数据，可泛化到不同哈密顿量和晶格结构 |
| Attention-Based FM for Quantum States | Attention-Based Foundation Model for Quantum States | Timothy Zaklama | 2025 | arXiv:2512.11962 | arXiv | 基于注意力机制的基础模型，使用自注意力捕获量子关联，实现跨系统量子态表示。resentation. |
| NOQS | Neural Operator for Quantum States | — | 2026 | — | arXiv preprint | 量子态神经算子，学习量子态空间上的连续映射，用于高效量子模拟和量子态预测 |
| Large Electron Model | Large Electron Model: A Foundation Model for Electron Systems | — | 2026 | — | arXiv preprint | 大电子模型，面向电子系统的基础模型，预训练于大规模电子结构数据，支持多种量子化学和材料物理任务 |
| DysonNet | Constant-Time Local Updates for Neural Quantum States | — | 2026 | arXiv:2603.11189 | arXiv | O(1)局部更新效率的神经量子态 |

---

<a id="physics-section-06"></a>
### 等离子体物理与聚变

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| TokaMind | TokaMind: A Multi-Modal Transformer Foundation Model for Tokamak Plasma | — | 2026 | — | arXiv preprint | 面向托卡马克等离子体的多模态Transformer基础模型，融合多种诊断数据模态，用于等离子体行为预测和聚变控制 |

---

<a id="physics-section-07"></a>
### 光学与光子学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OptoGPT | OptoGPT: A Foundation Model for Inverse Design in Optical Multilayer Thin Film Structures | — | 2023 | — | Opto-Electronic Advances 2024 | 基于GPT架构的光学薄膜逆向设计基础模型，可自动设计光学多层薄膜结构满足目标光谱特性 |
| MOCLIP | MOCLIP: Multi-modal Optical Contrastive Learning for Inverse Photonic Design | — | 2025 | — | arXiv preprint | 多模态光学对比学习模型，结合CLIP框架实现光子结构逆向设计，跨模态关联光学特性与结构参数 |

---

<a id="physics-section-08"></a>
### 结构保持与几何物理ML

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

---

<a id="physics-section-09"></a>
### 量子化学与电子结构

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Skala | Accurate and scalable exchange-correlation with deep learning | Microsoft Research | 2025 | arXiv:2506.14665 | arXiv | 微软开发的量子化学基础模型，用于电子结构计算和分子性质预测，支持跨体系泛化 |
| Orbformer | Orbformer: Orbital Transformer for Electronic Structure Prediction | — | 2025 | — | arXiv preprint | 轨道Transformer，基于分子轨道表征预测电子结构，融合物理对称性先验实现高精度预测 |
| OrbEvo | Orbital Transformers for Predicting Wavefunctions in TD-DFT | Chengdong He | 2025 | arXiv:2603.03511 | arXiv | 等变图Transformer预测TD-DFT波函数实时演化 |

---

<a id="physics-section-10"></a>
### 燃烧模拟

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

---

<a id="physics-section-11"></a>
### 核工程

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| NucReactor-FM | Agentic Physical AI toward a Domain-Specific FM for Nuclear Reactor Control | — | 2025 | arXiv:2512.23292 | arXiv | 核反应堆控制领域专用FM，结合物理模拟与强化学习 |

---

<a id="physics-section-12"></a>
### 参考说明 / Notes

- **ArXiv ID** 格式为纯数字编号（如 `2202.03772`），可通过 `https://arxiv.org/abs/<ID>` 访问
- 世界模型(World Model)类别包含面向物理感知的视频生成和交互式环境模型
- 年份以论文首次公开发表（preprint或正式发表）为准
- 本目录持续更新中，欢迎补充

## 地球科学

> [英文](earth-sciences/earth-sciences_en.md) | [中文](earth-sciences/earth-sciences_zh.md)

### 目录
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
### 天气与气候

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
### 遥感

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
### 海洋学

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
### 地震学

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
### 水文学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| HydroGAT | HydroGAT: A Graph Attention Foundation Model for Hydrological Prediction | — | 2025 | — | arXiv preprint | 基于图注意力网络的水文预测基础模型，建模流域间空间依赖关系 |
| ZeroFlood | ZeroFlood: A Geospatial Foundation Model for Data-Efficient Flood Susceptibility Mapping | — | 2025 | arXiv:2510.23364 | arXiv | 地理空间洪水易感性制图基础模型 |
| GraphRiverCast | Topology-informed AI FM for global river forecasting | — | 2026 | arXiv:2602.22293 | arXiv | 拓扑信息全球河流水动力预报AI基础模型 |

---

<a id="earth-sciences-section-06"></a>
### 野火预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FireCastNet | FireCastNet: A Deep Learning Model for Global Wildfire Danger Forecasting | — | 2025 | — | Scientific Reports (2025) | 深度学习全球野火危险预报模型，融合气象、植被和地形数据实现多时间尺度预测 |
| FireScope | FireScope: A Foundation Model for Wildfire Spread Prediction | — | 2025 | — | arXiv preprint | 野火蔓延预测基础模型，利用多源遥感和气象数据预测火灾传播路径 |

---

<a id="earth-sciences-section-07"></a>
### 空气质量

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AirCast | AirCast: A Data-Driven Foundation Model for Air Quality Forecasting | — | 2024 | — | arXiv preprint | 数据驱动的空气质量预报基础模型，支持多种大气污染物浓度预测 |
| FuXi-Air | FuXi-Air: Global Air Quality Forecasting with a Foundation Model Approach | — | 2025 | — | arXiv preprint | FuXi系列空气质量预报扩展，将天气预报基础模型范式应用于全球空气质量预测 |

---

<a id="earth-sciences-section-08"></a>
### 冰冻圈

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SIFM | SIFM: Sea Ice Foundation Model for Arctic Monitoring | — | 2024 | — | arXiv preprint | 海冰基础模型，用于北极海冰监测，基于多源卫星遥感数据预训练 |
| IceNet | IceNet: Seasonal Arctic Sea Ice Forecasting with Probabilistic Deep Learning | Tom Andersson | 2021 | DOI:10.1038/s41467-021-25257-4 | Nature Communications (2021) | 概率深度学习北极海冰季节预报模型，预报技能显著超越物理动力学模型 |
| IceMamba | IceMamba: A Mamba-based Foundation Model for Sea Ice Forecasting | — | 2025 | — | arXiv preprint | 基于Mamba状态空间模型架构的海冰预报基础模型，高效处理极区时空序列数据 |

---

<a id="earth-sciences-section-09"></a>
### 地球科学语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| K2 | K2: A Foundation Language Model for Geoscience Knowledge Understanding and Utilization | Cheng Deng | 2024 | 10.1145/3616855.3635772 | WSDM 2024 / ACM | 首个基于LLaMA的70亿参数地球科学LLM，在地球科学文献上继续预训练和指令微调。literature. |
| JiuZhou | JiuZhou: open foundation language models and effective pre-training framework for geoscience | Zhou Chen | 2025 | 10.1080/17538947.2025.2449708 | International Journal of Digital Earth | 清华大学提出的地球科学开放基础语言模型及高效预训练框架，支持中英文地学知识问答与推理。 |
| GeoGPT | GeoGPT: An assistant for understanding and processing geospatial tasks | Yifan Zhang | 2024 | 10.1016/j.jag.2024.103976 | International Journal of Applied Earth Observation and Geoinformation | 面向地理空间任务理解与处理的助手模型，结合GIS工具调用能力完成地理空间分析与推理。 |
| GeoGalactica | GeoGalactica: A Scientific LLM for Geoscience | — | 2024 | arXiv:2401.00434 | arXiv | 300亿参数地球科学大语言模型，基于Galactica架构在地学语料上预训练 |

---

<a id="earth-sciences-section-10"></a>
### 地下与勘探地球物理

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Transparent Earth | Transparent Earth: A Foundation Model for Subsurface Characterization | — | 2025 | — | arXiv Preprint | 洛斯阿拉莫斯国家实验室开发的地下特征化基础模型，用于地下结构成像与反演 |
| GEM 3D | GEM 3D: A Generative Earth Model for 3D Subsurface Modeling | — | 2025 | — | arXiv preprint | 生成式三维地球模型，用于地下结构建模与地质属性预测 |
| SFM-Exploration | SFM-Exploration: A Seismic Foundation Model for Exploration Geophysics | — | 2023 | — | Geophysics (2025) | 面向勘探地球物理的地震基础模型，在大规模合成与实际地震数据上预训练，支持多种勘探下游任务 |
| WLFM | WLFM: Well Log Foundation Model for Subsurface Analysis | — | 2025 | — | arXiv preprint | 测井基础模型，在大规模测井数据上自监督预训练，支持岩性识别、储层预测等下游任务 |

---

<a id="earth-sciences-section-11"></a>
### SAR专用模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SARATR-X | SARATR-X: Towards Building A Foundation Model for SAR Target Recognition | — | 2024 | — | IEEE TGRS (2024) | SAR目标识别基础模型，在大规模SAR图像上预训练，支持多种SAR目标识别下游任务 |
| SUMMIT | SUMMIT: A SAR Universal Multi-task Foundation Model for Intelligent Interpretation | — | 2025 | — | arXiv preprint | SAR通用多任务基础模型，统一检测、分割、分类等多种SAR解译任务 |
| SAR-W-MixMAE | SAR-W-MixMAE: A Mixed Masked Autoencoder for SAR-Wide Image Pre-training | — | 2025 | — | arXiv preprint | 混合掩码自编码器SAR宽幅图像预训练模型，优化SAR特有的斑点噪声和几何特征学习 |
| CrossEarth-SAR | Billion-scale SAR FM for domain-generalizable segmentation | — | 2026 | arXiv:2603.12008 | arXiv | 十亿级SAR基础模型，域泛化语义分割 |

---

<a id="earth-sciences-section-12"></a>
### 土地利用

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| LandSegmenter | LandSegmenter: A Foundation Model for Land Use and Land Cover Segmentation | — | 2025 | — | arXiv preprint | 土地利用/土地覆盖分割基础模型，大规模多源遥感数据预训练，支持全球LULC制图 |

---

<a id="earth-sciences-section-13"></a>
### 气候降尺度

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ORBIT-2 | ORBIT-2: A Foundation Model for Climate Downscaling | — | 2025 | — | ORNL | 气候降尺度基础模型，在超级计算环境中训练，实现高效气候降尺度推理 |

---

<a id="earth-sciences-section-14"></a>
### 参考资源

- [DL-Foundation-Models-for-Weather-Prediction (GitHub)](https://github.com/jimengshi/dl-foundation-models-weather)
- [Awesome-Remote-Sensing-Foundation-Models (GitHub)](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models)
- [Foundation Models for Remote Sensing and Earth Observation — Survey](https://arxiv.org/abs/2410.16602)

## 天文学

> [英文](astronomy/astronomy_en.md) | [中文](astronomy/astronomy_zh.md)

### 目录
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
### 多模态天文

#### E1. 多模态/跨模态基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AION-1 | AION-1: Omnimodal Foundation Model for Astronomical Sciences | Liam Parker | 2025 | 2510.17960 | NeurIPS 2025 | 大规模全模态天文基础模型，集成39种数据模态（成像、光谱、标量测量），覆盖2亿+天文目标 |
| AstroCLIP | AstroCLIP: A Cross-Modal Foundation Model for Galaxies | Liam Parker | 2023 | 2310.03024 | MNRAS (2024) | 跨模态星系基础模型，使用自监督对比学习将星系图像和光谱嵌入共享物理意义的潜在空间 |
| AstroLLaMA | AstroLLaMA: Towards Specialized Foundation Models in Astronomy | Tuan Dung Nguyen | 2023 | 2309.06126 | WIESP@EMNLP 2023 | 天文专用70亿参数大语言模型，基于LLaMA-2在30万+天文摘要上微调 |
| AstroLLaMA-2-70B | AstroMLab 2: AstroLLaMA-2-70B Model and Benchmarking Specialized LLMs for Astronomy | — | 2024 | 2409.19750 | arXiv preprint | AstroLLaMA的大规模升级版（700亿参数），为天文学提供更强大的领域专用LLM |
| AstroPT | AstroPT: Scaling Large Observation Models for Astronomy | Michael J. Smith | 2024 | 2405.14930 | arXiv preprint | 开源自回归预训练Transformer，在860万DESI Legacy Survey星系图像上训练，可扩展的大观测模型 |
| astroBERT | astroBERT: A Language Model for Astronomy | — | 2022 | — | Astronomy & Computing | 在天文学文献上预训练的BERT模型，用于天文文本挖掘NLP任务 |

#### E2. 光谱基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OmniSpectra | OmniSpectra: A Unified Foundation Model for Native Resolution Astronomical Spectra | Md Khairul Islam | 2026 | arXiv:2601.15351 | arXiv | 统一天文光谱基础模型，处理任意长度、任意仪器的原始分辨率光谱数据。ra without resampling or interpolation. |
| SpectraFM | SpectraFM: Tuning into Stellar Foundation Models | — | 2024 | — | NeurIPS FM4Science Workshop (2024) | 恒星光谱基础模型，在大规模恒星光谱数据上预训练，支持光谱分类与参数估计等下游任务 |

#### E3. 时域天文/光变曲线基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FALCO | FALCO: Foundation Model of Astronomical Light Curves for Time Domain Astronomy | Xiaoxiong Zuo | 2025 | 2504.20290 | AJ (2026) | 天文光变曲线基础模型，基于Transformer自监督学习在Kepler数据上训练，支持时域天文多种下游任务 |
| Astromer 2 | Astromer 2: Few-shot Light Curve Classification | Cristobal Donoso-Oliva | 2025 | 2502.02717 | A&A (2026) | 自监督光变曲线基础模型，在150万MACHO巡天光变曲线上预训练，支持少样本分类 |
| ASTROMER | ASTROMER: A Transformer-based Embedding for the Representation of Light Curves | Cristobal Donoso-Oliva | 2022 | DOI:10.1051/0004-6361/202243928 | A&A (2023) | 首个用于天文光变曲线表征的Transformer预训练模型，可迁移到多种巡天数据 |
| AstroCo | ASTROCO: Self-Supervised Conformer-Style Transformers for Light-Curve Embeddings | Antony Tan | 2025 | arXiv:2509.24134 | arXiv | 自监督Conformer风格Transformer编码器，用于处理不规则恒星光变曲线。 |

---

<a id="astronomy-section-02"></a>
### 引力波科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GraviBERT | GraviBERT: A Foundation Model for Gravitational Wave Signal Analysis | — | 2024 | — | arXiv preprint | 引力波信号分析基础模型，基于BERT架构在模拟引力波数据上预训练，支持信号检测与参数估计 |
| Dingo-T1 | Dingo-T1: A Foundation Model for Fast Gravitational-Wave Inference | — | 2025 | — | NeurIPS ML4PS (2025) | 快速引力波推断基础模型，基于深度学习实现近实时引力波参数后验估计 |
| WaveFormer | WaveFormer: Transformer-based Gravitational Wave Detection | — | 2022 | — | arXiv preprint | 基于Transformer架构的引力波检测模型，从原始干涉仪时间序列中检测引力波信号 |

---

<a id="astronomy-section-03"></a>
### 射电天文

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RGZ-FM | RGZ-FM: A First Multipurpose Foundation Model for Radio Galaxy Zoo | — | 2023 | — | arXiv preprint | 首个多用途射电星系基础模型，在Radio Galaxy Zoo数据上预训练，支持射电源分类与形态学分析 |
| STRADAViT | STRADAViT: A Vision Transformer for Radio Astronomy Data | — | 2026 | — | arXiv preprint | 面向射电天文数据的视觉Transformer基础模型，处理射电干涉成像数据的多种下游任务 |
| SKATR | SKATR: A Foundation Model for SKA Radio Continuum Data | — | 2024 | — | SciPost (2025) | 面向SKA射电连续谱数据的基础模型，为下一代射电巡天提供通用特征表示 |
| ExoMiner++ | ExoMiner++: Enhanced Transit Classification and a New Vetting Catalog | — | 2025 | — | Preprint | NASA改进版深度学习模型，用于系外行星凌星验证和分类 |

---

<a id="astronomy-section-04"></a>
### 系外行星探测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PANOPTICON | PANOPTICON: A Foundation Model for Exoplanet Transit Detection | — | 2025 | — | A&A (2025) | 系外行星凌星探测基础模型，用于大规模巡天数据中行星凌星信号的自动检测与分类 |

---

<a id="astronomy-section-05"></a>
### 宇宙学模拟

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GOTHAM | GOTHAM: A Generative Foundation Model for Cosmological Simulations | — | 2024 | — | arXiv preprint | 宇宙学模拟生成基础模型，快速生成高保真大尺度结构模拟 |
| CosmosGalaxyFM | Multi-modal Foundation Model for Cosmological Simulation Data | Bin Xia | 2025 | arXiv:2510.07684 | NeurIPS ML4PS 2025 | 多模态宇宙学基础模型 |

---

<a id="astronomy-section-06"></a>
### CMB分析

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

---

<a id="astronomy-section-07"></a>
### 巡天分类器

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ORACLE | ORACLE: A Foundation Model for Astronomical Survey Classification | — | 2025 | — | ApJ (2025) | 天文巡天分类基础模型，支持多波段巡天数据中的天体源自动分类与编目 |

---

<a id="astronomy-section-08"></a>
### 行星科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MOMO | Mars Orbital Model Foundation Model | — | 2026 | arXiv:2604.02719 | arXiv | 火星轨道多传感器遥感基础模型 |

---

<a id="astronomy-section-09"></a>
### 参考资源

- [PolymathicAI / AstroCLIP (GitHub)](https://github.com/PolymathicAI/AstroCLIP)
- [Smith42 / astroPT (GitHub)](https://github.com/smith42/astroPT)
- [Astromer Science (GitHub)](https://github.com/astromer-science/main-code)
- [IAIFI Astrophysics Papers](https://iaifi.org/papers-astro.html)
- [Multimessenger Astronomy in the Era of Foundational AI Workshop (2025)](https://www.lisamission.org/multimessenger-astronomy-in-the-era-of-foundational-ai/)

## 医学与生物医学

> [英文](medicine/medicine_en.md) | [中文](medicine/medicine_zh.md)

### 目录
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
### 医学影像

#### 综述 Overview

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
| LVM-Med | LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-Order Graph Matching | Duy M.H. Nguyen | 2023 | arXiv:2306.11925 | NeurIPS 2024 | 大规模自监督医学影像视觉模型，在约130万张多模态图像（CT/MRI/X-ray/超声等）上训练。 |
| STU-Net | STU-Net: Scalable and Transferable Medical Image Segmentation Models Empowered by Large-Scale Supervised Pre-training | Ziyan Huang | 2023 | arXiv:2304.06716 | arXiv Preprint | 最大可达14亿参数的可扩展医学图像分割模型，通过大规模监督预训练实现强迁移性。 |
| UniverSeg | UniverSeg: Universal Medical Image Segmentation | Victor Ion Butoi | 2023 | arXiv:2304.06131 | ICLR 2023 | 无需额外训练即可泛化到未见任务的医学图像分割模型，使用in-context学习范式。 |
| RETFound | A Foundation Model for Generalizable Disease Detection from Retinal Images | Yukun Zhou | 2023 | DOI:10.1038/s41586-023-06555-x | Nature 2023 | 在160万张未标注视网膜图像上自监督预训练的眼科基础模型，支持多种眼病和全身疾病检测。 |
| SkinGPT-4 | Pre-trained Multimodal Large Language Model Enhances Dermatological Diagnosis Using SkinGPT-4 | Juexiao Zhou | 2023 | arXiv:2304.10691 | Nature Communications 2024 | 交互式皮肤病诊断系统，集成视觉变换器和Llama-2-13b-chat，在52,000+皮肤病图像上训练。 |
| PanDerm | A Multimodal Vision Foundation Model for Clinical Dermatology | (多作者) | 2024 | arXiv:2410.15038 | Nature Medicine 2025 | 在200万+皮肤病图像（11个机构、4种成像模态）上预训练的多模态皮肤科基础模型。 |
| RadFM | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data | Chaoyi Wu | 2023 | arXiv:2308.02463 | Nature Communications 2025 | 通用放射学基础模型，利用1300万2D图像和61.5万3D扫描进行多模态训练。 |
| CheXFound | Chest X-ray Foundation Model with Global and Local Self-supervised Learning | (多作者) | 2025 | arXiv:2502.05142 | arXiv Preprint | 在约100万张胸部X光上自监督预训练的基础模型，结合全局和局部学习策略，提升多种临床任务的泛化能力。 |
| REMEDIS | Robust and Data-Efficient Generalization of Self-Supervised Machine Learning for Diagnostic Imaging | Shekoofeh Azizi | 2022 | arXiv:2205.09723 | Nature Biomedical Engineering 2023 | Google开发的医学影像表示学习框架，结合大规模自监督预训练和任务特定微调，提升鲁棒性和数据效率。 |
| MedicoSAM | MedicoSAM: Towards Foundation Models for Medical Image Segmentation | (多作者) | 2025 | arXiv:2501.11734 | arXiv Preprint | 探索将SAM适配为医学图像分割基础模型的系统研究。 |
| BiomedParse | BiomedParse: Biomedical Foundation Model for Image Parsing | Microsoft | 2024 | arXiv:2405.12971 | Nature Methods 2024 | 微软统一生物医学图像解析基础模型，支持分割、检测和识别 |
| SegVol | SegVol: Universal and Interactive Volumetric Medical Image Segmentation | Yuxin Du | 2024 | arXiv:2311.13385 | arXiv | 通用交互式3D医学图像分割，支持语义和空间提示 |
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
| SkinCLIP-VL | SkinCLIP-VL: Consistency-Aware Vision-Language Learning for Multimodal Skin Cancer Diagnosis | — | 2026 | arXiv:2603.21010 | arXiv Preprint | 一致性感知视觉-语言学习，多模态皮肤癌诊断 |
| BioMedGPT-R1 | BioMedGPT-R1: A 17B Multimodal Biomedical Foundation Model | (清华大学) | 2025 | Hugging Face | Hugging Face | 清华大学开发的170亿参数多模态生物医学基础模型，整合医学影像和文本理解 |
| LLaVA-NeXT-Med | LLaVA-NeXT-Med: Medical Multimodal Large Language Model | Yunfei Guo | 2025 | doi:10.1109/citsc64390.2025.00092 | IEEE CITSC 2025 | LLaVA-NeXT的医学版本，通过医学视觉指令微调增强多模态医学影像理解和推理 |
| ChexGen | A Generative Foundation Model for Chest Radiography | Yuanfeng Ji | 2025 | arXiv:2509.03903 | arXiv | 胸部X光生成基础模型 |
| CheXficient | A data- and compute-efficient chest X-ray foundation model | Chong Wang | 2026 | arXiv:2602.22843 | arXiv | 数据高效胸部X光基础模型 |
| Ark+ | Fully open AI foundation model for chest radiography | — | 2025 | Nature 2025 | Nature | 全开放胸部X光AI基础模型(Nature发表) |
| MedSigLIP | Medical dual-tower vision-language encoder | Google Health | 2025 | Google HADF | Google HADF | Google Health开发的医学专用双塔视觉-语言编码器，Health AI Developer Foundations项目一部分 |
| FM-CT | 3D Foundation Model for Generalizable Disease Detection in Head Computed Tomography | Weicheng Zhu | 2025 | arXiv:2502.02779 | arXiv Preprint | 3D头部CT基础模型，在361,663例非增强头部CT上通过自蒸馏和掩码图像建模进行自监督预训练，用于可泛化的疾病检测 |

---

<a id="medicine-section-02"></a>
### 神经影像

#### 综述 Overview

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
### 病理学

#### 综述 Overview

病理学基础模型专注于组织病理学全切片图像（WSI）分析，用于癌症检测、生物标志物预测、疾病分类等计算病理学任务。这是SFM最活跃的领域之一。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Virchow | Virchow: A Million-Slide Digital Pathology Foundation Model | Eugene Vorontsov | 2023 | arXiv:2309.07778 | Nature Medicine 2024 | Paige/微软开发的百万切片数字病理基础模型，在150万H&E染色WSI上自监督训练，支持癌症检测和罕见癌识别。 |
| Virchow2 | Virchow2: Scaling Self-Supervised Mixed Magnification Models in Pathology | Eric Zimmermann | 2024 | arXiv:2408.00738 | arXiv | Virchow第二代，包含Virchow2（6.32亿参数）和Virchow2G（18.5亿参数），在混合放大倍率下训练。 |
| UNI | Towards a General-Purpose Foundation Model for Computational Pathology | Richard J. Chen | 2024 | DOI:10.1038/s41591-024-02857-3 | Nature Medicine 2024 | Mahmood Lab开发的通用计算病理基础模型，在10万+WSI上自监督训练，支持20+主要组织类型分析。 |
| UNI2 | Towards a General-Purpose Foundation Model for Computational Pathology | Richard J. Chen | 2025 | doi:10.1038/s41591-024-02857-3 | Nature Medicine | UNI的升级版，包含ViT-H (UNI2-h)和ViT-G (UNI2-g-preview)两个变体，在2亿+病理图像（350,000+切片）上预训练，2025年1月发布。 |
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
| PRISM | PRISM: A Multi-Modal Generative Foundation Model for Slide-Level Histopathology | Eugene Vorontsov | 2024 | arXiv:2405.10254 | arXiv preprint | 病理学多模态生成基础模型，整合视觉和分子信息进行切片级分析 |
| PRISM2 | PRISM2: Unlocking Multi-Modal General Pathology AI with Clinical Dialogue | Eugene Vorontsov | 2025 | arXiv:2506.13063 | arXiv preprint | 多模态切片级基础模型，训练于70万诊断标本-报告对（230万WSI、1400万QA对），实现临床对话式通用病理AI |
| PathOrchestra | PathOrchestra: A Comprehensive Foundation Model for Computational Pathology | — | 2025 | arXiv:2503.00203 | arXiv | 全面的计算病理基础模型，覆盖多种病理任务 |
| kaiko.ai | Towards Training Large-Scale Pathology Foundation Models | — | 2024 | — | arXiv | 大规模病理基础模型训练，提供多尺度ViT变体 |
| RudolfV | A Foundation Model Connecting Pathology Images and Genomic Sequences | — | 2024 | arXiv:2401.09027 | arXiv | 连接病理图像和基因组序列的基础模型 |
| BEPH | A foundation model for generalizable cancer diagnosis and survival prediction from histopathological images | Zhaochang Yang | 2025 | doi:10.1038/s41467-025-57587-y | Nature Communications | 可泛化的癌症诊断与生存预测病理基础模型 |
| GPFM | A Generalizable Pathology Foundation Model | — | 2024 | arXiv:2407.18807 | arXiv | 通用病理基础模型，在19万+WSI上训练 |
| mSTAR | Multi-Scale Tissue-Aware Representation | — | 2024 | arXiv:2407.15362 | arXiv | 多尺度组织感知表征学习 |
| HIPT | Hierarchical Image Pyramid Transformer for Whole-Slide Image Analysis | Richard J. Chen | 2022 | arXiv:2206.02647 | CVPR 2022 | 分层图像金字塔Transformer，用于WSI的自监督学习 |
| RetCCL | Retention-based Contrastive Learning for Histopathology | Xiyue Wang | 2022 | DOI:10.1016/j.media.2022.102645 | Medical Image Analysis 2023 | 基于保留的对比学习病理特征提取器 |
| PathoDuet | Foundation Models for Pathological Image Analysis via Self-Supervised Learning | — | 2023 | arXiv:2312.09849 | arXiv | 双尺度自监督病理基础模型 |
| PLUTO | Pathology-Universal Transformer | — | 2023 | — | arXiv | 通用病理学Transformer |
| COBRA | Unsupervised Foundation Model-Agnostic Slide-Level Representation Learning | Tim Lenz | 2025 | doi:10.1109/cvpr52734.2025.02869 | CVPR 2025 | 无监督基础模型无关的切片级表征学习 |
| THREADS | Molecular-driven Foundation Model for Oncologic Pathology | Anurag Vaidya | 2025 | arXiv:2501.16652 | arXiv Preprint | 分子驱动的肿瘤病理基础模型，47K+ H&E切片配对基因组/转录组多模态预训练 |
| MADELEINE | Multimodal ADaptive LEarning with INtegrated Embeddings | — | 2024 | — | arXiv | 多模态自适应病理学习 |
| Lunit-DINO | Benchmarking Self-Supervised Learning on Diverse Pathology Datasets | — | 2024 | — | arXiv | Lunit基于DINOv2的大规模病理预训练 |
| Quilt-LLaVA | Visual Instruction Tuning for Histopathology | — | 2024 | arXiv:2312.04746 | arXiv | 病理学视觉指令微调多模态模型 |
| Path Foundation | Developing and Validating a Foundation Model for Pathology | — | 2024 | Google HADF | Google HADF | Google开发的病理基础模型，Health AI Developer Foundations (HADF) 项目一部分 |
| CONCH 1.5 | A Multimodal Whole-Slide Foundation Model for Pathology | — | 2025 | doi:10.1038/s41591-025-03982-3 | Nature Medicine | CONCH升级版，增强视觉-语言对齐，作为TITAN的视觉-语言骨干 |
| H-optimus-1 | H-optimus-1: Advanced Pathology Foundation Model | (Bioptimus) | 2025 | Hugging Face | Hugging Face | H-optimus-0的升级版，更大规模训练 |
| Giga-SSL | Giga-SSL: Self-Supervised Learning for Gigapixel Images | Tristan Lazard | 2023 | doi:10.1109/cvprw59228.2023.00453 | CVPRW 2023 | 千兆像素病理图像自监督学习方法 |
| MUPAD | MUPAD: A Generative Foundation Model for Multimodal Histopathology | — | 2026 | arXiv:2604.03635 | arXiv Preprint | 多模态组织病理学生成基础模型，整合组织学图像、RNA分子谱和临床文本 |
| VISTA-PATH | VISTA-PATH: An interactive foundation model for pathology image segmentation and quantitative analysis | — | 2026 | arXiv:2601.16451 | arXiv Preprint | 交互式病理图像分割与定量分析基础模型，增强临床相关性和准确性 |
| CARE | CARE: A Molecular-Guided Foundation Model with Adaptive Region Modeling for WSI Analysis | — | 2026 | arXiv:2602.21637 | arXiv Preprint | 分子引导的自适应区域建模全切片图像分析基础模型 |
| BRIGHT | BRIGHT: A Collaborative Generalist-Specialist Foundation Model for Breast Pathology | Xiaojing Guo | 2026 | arXiv:2603.03030 | arXiv | 协作式通才-专家乳腺癌理基础模型。 |
| GenBio-PathFM | GenBio-PathFM: A State-of-the-Art Foundation Model for Histopathology | Saarthak Kapse | 2026 | 10.64898/2026.03.17.712534 | bioRxiv | 11亿参数的SOTA组织病理学基础模型，完全基于公开数据训练。 |
| Atlas 2 | State-of-the-art pathology FM trained on 5.5M WSIs | Aignostics/Mayo | 2026 | arXiv:2601.05148 | arXiv | 550万全切片训练的病理学基础模型 |
| LongViT | LongViT: Long-Context Vision Transformer for Pathology | — | 2024 | arXiv:2403.14576 | arXiv Preprint | 长上下文视觉Transformer，直接处理超大尺寸病理全切片图像 |
| Pixel-Mamba | Pixel-Mamba: Efficient Mamba-Based Foundation Model for Computational Pathology | — | 2025 | arXiv | arXiv Preprint | 基于Mamba架构的高效计算病理基础模型，像素级处理 |
| Virchow 2G | Virchow 2G: Scaling Self-Supervised Models to 1.9B Parameters for Pathology | — (Paige/Microsoft) | 2024 | arXiv:2408.00738 | arXiv Preprint | ViT-G架构1.9B参数病理基础模型，在310万WSI上训练（Virchow2系列最大版本） |
| Campanella DINO | Campanella et al. (DINO): Self-Supervised ViT-S for Digital Pathology | — (Thomas Fuchs Lab) | 2024 | — | arXiv Preprint | ViT-S架构，DINOv1自监督训练于42万WSI的病理基础模型 |
| Campanella MAE | Campanella et al. (MAE): Masked Autoencoder ViT-L for Digital Pathology | — (Thomas Fuchs Lab) | 2024 | — | arXiv Preprint | ViT-L架构，MAE自监督训练于42万WSI的病理基础模型 |
| SP22M | SP22M: Mount Sinai Computational Pathology Foundation Model (22M params) | — (Mount Sinai) | 2024 | Hugging Face | Hugging Face | Mount Sinai开发的2200万参数计算病理基础模型 |
| SP85M | SP85M: Mount Sinai Computational Pathology Foundation Model (85M params) | — (Mount Sinai) | 2024 | Hugging Face | Hugging Face | Mount Sinai开发的8500万参数计算病理基础模型 |
| CHROMA | A comprehensive foundation model for generalizable cytogenetics in precision oncology with CHROMA | Changchun Yang | 2026 | 10.1038/s41698-026-01383-4 | npj Precision Oncology | 面向精准肿瘤学的通用细胞遗传学基础模型，实现自动化染色体分析与核型判读 |

---

---

<a id="medicine-section-04"></a>
### 内窥镜与手术

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Endo-FM | Foundation Model for Endoscopy Video Analysis | Zhao Wang | 2023 | arXiv:2306.16741 | MICCAI 2023 | 首个内窥镜视频基础模型，33000+视频自监督预训练 |
| EndoDINO | A Foundation Model for GI Endoscopy | Patrick Dermyer | 2025 | arXiv:2501.05488 | arXiv | 胃肠内窥镜DINOv2基础模型，175万+图像 |
| EndoMamba | Efficient Foundation Model for Endoscopic Videos | Qingyao Tian | 2025 | arXiv:2502.19090 | MICCAI 2025 | Mamba架构高效内窥镜视频基础模型 |
| SurgVISTA | Large-scale self-supervised video foundation model for intelligent surgery | — | 2025 | — | npj Digital Medicine | 大规模手术视频基础模型，3650视频/355万帧 |
| SurgVLP | Learning multi-modal representations for surgical video | — | 2023 | — | MedIA 2025 | 手术视频-语言预训练 |
| SurgLLM | A Versatile Large Multimodal Model for Surgical Video Understanding | — | 2025 | arXiv:2509.00357 | arXiv | 大型多模态手术视频理解 |
| GSViT | General Surgery Vision Transformer | — | 2024 | arXiv:2403.05949 | arXiv | 通用外科视觉Transformer |
| HecVL | Hierarchical Video-Language Pretraining for Zero-shot Surgical Phase Recognition | Kun Yuan | 2024 | — | MICCAI 2024 | 零样本手术阶段识别 |
| PeskaVLP | Procedure-Aware Surgical Video-language Pretraining | — | 2024 | — | NeurIPS 2024 | 过程感知手术视频-语言预训练 |
| SurgiSAM 2 | A fine-tuned SAM2 for surgical video segmentation | — | 2025 | — | Scientific Reports | SAM2手术场景分割 |
| ZEN | ZEN: A generalizable foundation model for intraoperative understanding across surgical procedures | — | 2026 | arXiv:2602.13633 | arXiv Preprint | 通用术中理解基础模型，实时手术视频分析，跨手术类型泛化 |
| SurgMotion | SurgMotion: A Video-Native Foundation Model for Universal Understanding of Surgical Videos | Jinlin Wu | 2026 | arXiv:2602.05638 | arXiv | 原生视频手术基础模型，直接从视频而非帧级特征学习，用于通用手术视频理解。rgical video understanding. |
| Surg-R1 | Surg-R1: A Hierarchical Reasoning Foundation Model for Scalable and Interpretable Surgical Decision Support | — | 2026 | arXiv:2603.12430 | arXiv Preprint | 层次推理手术基础模型，三级推理架构，多中心临床验证 |
| Cosmos-H-Surgical | Cosmos-H-Surgical: NVIDIA Physical AI for Surgical Robotics | (NVIDIA) | 2025 | — | arXiv Preprint | NVIDIA开发的手术机器人物理AI基础模型，基于Cosmos世界模型架构，用于手术场景理解和机器人操作规划。 |
| SurgRec | SurgRec: Surgical Foundation Model via Large-Scale Self-Supervised Video Pretraining | (多作者) | 2025 | — | arXiv Preprint | 大规模自监督手术视频预训练基础模型，在数千小时手术视频上训练，支持多种手术视觉理解任务。 |

---

<a id="medicine-section-05"></a>
### 超声

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
| EchoJEPA | EchoJEPA: A Latent Predictive Foundation Model for Echocardiography | Alif Munim | 2026 | arXiv:2602.02603 | arXiv Preprint | 潜在预测式心超基础模型，在30万患者1800万张心超图像上基于V-JEPA 2架构预训练；LVEF估计优于基线约20%，零样本泛化至儿科患者 |
| BUSGen | A foundation generative model for breast ultrasound image analysis | Haojun Yu | 2025 | doi:10.1038/s41551-026-01639-1 | Nature Biomedical Engineering | 乳腺超声生成基础模型，在350万+乳腺超声图像上预训练；少样本合成数据用于癌症筛查、诊断和预后，超越全部9位放射科医师，灵敏度提升16.5% |

---

<a id="medicine-section-06"></a>
### 心电与生理信号

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
| MaEEG | MaEEG: Masked Auto-Encoder for EEG Representation Learning | — | 2024 | arXiv | arXiv Preprint | EEG掩码自编码器，用于EEG数据的自监督表征学习 |

---

<a id="medicine-section-07"></a>
### 口腔影像

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DentVFM | Vision Foundation Models for Oral Radiology | — | 2025 | arXiv:2510.14532 | arXiv | 口腔颌面放射学视觉基础模型 |
| DentVLM | Multimodal Vision-Language Model for Dental Diagnosis | — | 2025 | arXiv:2509.23344 | arXiv | 牙科多模态视觉-语言模型 |
| DVCTNet | Adapting Foundation Model for Dental Caries Detection | — | 2025 | arXiv:2508.20813 | arXiv | 双视角龋齿检测 |
| OralGPT-Omni | Versatile dental multimodal large language model | — | 2025 | arXiv:2511.22055 | arXiv | 通用牙科多模态大语言模型 |

---

<a id="medicine-section-08"></a>
### 眼科

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
### 医学文本与NLP

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Med-PaLM | Large Language Models Encode Clinical Knowledge | Karan Singhal | 2023 | 10.1038/s41586-023-06291-2 | Nature | Google首个医学LLM。 |
| Med-PaLM 2 | Towards Expert-Level Medical Question Answering with Large Language Models | Karan Singhal | 2023 | arXiv:2305.09617 | arXiv | 专家级医学问答。 |
| Med-Gemini | Advancing Multimodal Medical Capabilities of Gemini | Lin Yang | 2024 | arXiv:2405.03162 | arXiv | Google多模态医学AI，将Gemini能力扩展到文本、图像和基因组学的临床推理。 |
| MedGemma | Open Models for Health AI | — | 2025 | arXiv:2507.05201 | arXiv | Google开源Gemma医学变体集合，为医学文本和图像理解提供专门优化的模型 |
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
| OpenBioLLM | OpenBioLLM-70B: Advancing Open-Source Large Language Models in Medical Domain | — | 2024 | — | Saama AI Labs | 700亿参数开源生物医学大语言模型，基于Llama微调，面向医学领域应用 |
| MMedLM | Towards Building Multilingual Language Model for Medicine | — (MAGIC-AI4Med) | 2024 | arXiv:2402.13963 | Nature Communications | 多语言医疗语言模型，基于MMedC多语言医疗语料库训练，支持跨语言医疗问答 |
| ClinicalMamba | ClinicalMamba: A Generative Clinical Language Model on Longitudinal Clinical Notes | — | 2024 | arXiv | arXiv Preprint | 基于Mamba架构的临床语言生成模型，处理纵向临床笔记 |
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
### 医学多模态

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| LLaVA-Med | Large Language-and-Vision Assistant for Biomedicine | Chunyuan Li | 2023 | arXiv:2306.00890 | NeurIPS 2023 | Microsoft生物医学多模态LLM |
| BiomedGPT | Generalist vision-language foundation model for biomedical tasks | Kai Zhang | 2024 | — | Nature Medicine | 通用生物医学VL基础模型，16种任务 |
| XrayGPT | Chest Radiographs Summarization using VL Models | Omkar Thawkar | 2023 | arXiv:2306.07971 | arXiv | 胸片摘要生成 |
| Med-Flamingo | Multimodal Medical Few-shot Learner | Michael Moor | 2023 | arXiv:2307.15189 | ML4H 2023 | 多模态医学少样本学习 |
| MedASR | MedASR: A Conformer-Based Medical Speech Recognition Model | — (Google Health) | 2025 | Google Health AI | Google HADF | 医疗语音识别基础模型，Conformer架构，105M参数，训练于5000小时去标识化医疗语音数据 |
| MedGemma 1.5 | MedGemma 1.5 Technical Report | Google/DeepMind | 2026 | arXiv:2604.05081 | arXiv Preprint | Google最新医学基础模型，显著提升多模态医学影像分析能力（CT/MRI/高维影像） |
| MedMO | MedMO: Grounding and Understanding Multimodal Large Language Model for Medical Images | — | 2026 | arXiv:2602.06965 | arXiv Preprint | 医学影像多模态大语言模型，训练于2600万+多样医学样本，支持定位和理解 |
| UNIMEDVL | UNIMEDVL: A unified medical multimodal foundation model for clinical diagnosis | — | 2025 | OpenReview | arXiv Preprint | 统一医学多模态基础模型，支持跨模态理解和生成的临床诊断 |
| MeDiM | MeDiM: A medical discrete diffusion model for unified multimodal medical generation | — | 2026 | OpenReview | OpenReview | 医学离散扩散模型，统一多模态医学生成（图像+文本双向翻译） |
| Lingshu | Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning | LASA Team | 2025 | arXiv:2506.07044 | arXiv | 通用多模态医学LLM，支持跨多种医学数据模态的统一理解和推理。 |
| CLEAR | CLEAR: An Auditable Foundation Model for Radiology Grounded in Clinical Concepts | Tianyu Han | 2026 | 10.64898/2026.01.15.26344222 | medRxiv | 可审计放射学基础模型，在约87万胸片-报告对上训练，将预测基于显式临床概念以增强透明度。 |
| GreenRFM | GreenRFM: Toward a resource-efficient radiology foundation model | Yingtai Li | 2026 | arXiv:2603.06467 | arXiv | 资源高效的放射学基础模型，以大幅降低的计算和内存需求达到SOTA性能。 |
| Curia-2 | Curia-2: An advanced radiology foundation model | Raidium | 2026 | arXiv:2604.01987 | arXiv Preprint | 进阶放射学基础模型，增强CT/MRI自监督学习 |
| MediVLM | MediVLM: A Vision Language Model for Radiology Report Generation | Ronast Subedi | 2025 | — | EMNLP 2025 | 放射报告自动生成VLM |
| InfiMed-Foundation | Compute-efficient medical multimodal FM | — | 2025 | arXiv:2509.22261 | arXiv | 计算高效医学多模态基础模型 |

---

<a id="medicine-section-11"></a>
### 电子健康记录

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

---

<a id="medicine-section-12"></a>
### 核医学

#### 综述 Overview

核医学基础模型专注于PET/CT等功能成像数据，用于全身代谢分析、肿瘤检测、器官/病灶分割和报告生成。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SDF-HOLO | A Generalist Foundation Model for Total-body PET/CT Enables Diagnostic Reporting and System-wide Metabolic Profiling | Wei Chen | 2026 | arXiv:2601.12820 | arXiv | 在10,000+患者全身PET/CT数据上训练的多模态基础模型，采用双流架构支持诊断报告和全身代谢分析。 |
| FratMAE | Developing a PET/CT Foundation Model for Cross-Modal Anatomical and Functional Imaging | Yujin Oh | 2025 | arXiv:2503.02824 | arXiv | 双ViT编码器PET/CT跨模态基础模型，用于肿瘤学应用中的功能-解剖联合分析。 |
| SegAnyPET | Developing Foundation Models for Universal Segmentation from 3D Whole-Body Positron Emission Tomography | Yichi Zhang | 2025 | arXiv:2603.11627 | ICCV 2025 | 首个PET图像通用分割基础模型，基于>11,000例PET扫描和60万标注，支持器官和病灶分割 |

---

<a id="medicine-section-13"></a>
### 乳腺影像

#### 综述 Overview

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
### 肌骨影像

#### 综述 Overview

肌骨影像基础模型专注于骨骼、关节等肌肉骨骼系统的X线和MRI分析，用于骨科疾病诊断、关节损伤检测等任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OrthoFoundation | A multimodal vision foundation model for generalizable knee pathology | Kang Yu | 2026 | arXiv:2601.18250 | arXiv | 多模态骨科视觉基础模型，通过自监督对比学习在120万未标注膝部X光和MRI图像上训练，用于可泛化的膝关节病理评估。 |
| OrthoDiffusion | OrthoDiffusion: A Generalizable Multi-Task Diffusion Foundation Model for Musculoskeletal MRI Interpretation | Tian Lan | 2026 | arXiv:2602.20752 | arXiv | 基于扩散的多任务肌骨MRI基础模型，在约16,000未标注膝部MRI上训练，支持分割和分类。 |
| XR-0 | Multi Anatomy X-Ray Foundation Model | Nishank Singla | 2025 | arXiv:2509.12146 | arXiv | 自监督多解剖部位X光基础模型，在115万X光图像上训练，覆盖包括肌骨结构在内的多个解剖区域。 |

---

<a id="medicine-section-15"></a>
### 可穿戴与数字健康

#### 综述 Overview

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
### 放射治疗

#### 综述 Overview

放射治疗基础模型专注于放疗计划自动化，包括靶区勾画、剂量预测、计划优化等，旨在提升放疗效率和质量。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|

---

<a id="medicine-section-17"></a>
### 显微镜

#### 综述 Overview

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
### 睡眠医学

#### 综述 Overview

睡眠医学基础模型专注于多导睡眠图（PSG）和可穿戴设备的睡眠数据分析，用于睡眠分期、睡眠障碍诊断等临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SleepFM | SleepFM: A Multi-Modal Foundation Model for Sleep Medicine | (多作者) | 2025 | 10.1038/s41591-025-04133-4 | Nature Medicine | 多模态睡眠基础模型，在大规模PSG数据上预训练，整合EEG、ECG和呼吸信号用于睡眠分期和疾病预测。 |

---

---

<a id="medicine-section-19"></a>
### 兽医学

#### 综述 Overview

兽医学基础模型专注于动物医学影像和临床数据分析，用于动物疾病诊断、解剖结构分割等兽医临床任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| VET-DINO | VET-DINO: Learning Anatomical Understanding in Veterinary Imaging | Andre Dourson | 2025 | arXiv:2505.15248 | arXiv | 自监督兽医影像FM，使用多视图知识蒸馏(Mars Petcare) |

---

<a id="medicine-section-20"></a>
### 法医学

#### 综述 Overview

法医学基础模型专注于法医病理学和法医鉴定数据分析，支持死因鉴定、损伤分类等法医学任务。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SongCi | Large-vocabulary forensic pathological analyses via prototypical cross-modal contrastive learning | Chen Shen | 2025 | 10.1038/s41467-025-62060-x | Nature Communications | 面向法医病理学的视觉-语言基础模型，使用原型跨模态对比学习处理大体发现和全切片图像。 |

---

> **总计 / Total: 265 models**

## 数学与科学推理

> [英文](mathematics/mathematics_en.md) | [中文](mathematics/mathematics_zh.md)

### 目录
- [定理证明](#mathematics-section-01)
- [科学多模态推理](#mathematics-section-02)
- [数学推理LLM](#mathematics-section-03)

<a id="mathematics-section-01"></a>
### 定理证明

#### 综述 Overview

定理证明基础模型专注于形式化数学推理，结合大语言模型与证明辅助系统（如Lean），用于自动化定理证明、数学竞赛问题求解等。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaProof | Olympiad-Level Formal Mathematical Reasoning with AlphaProof | (DeepMind团队) | 2024 | DOI:10.1038/s41586-025-09833-y | Nature 2025 | DeepMind开发的形式化数学推理系统，结合强化学习和Lean证明助手，在2024年IMO中解出4/6题达到银牌水平。 |
| LLEMMA | Llemma: An Open Language Model for Mathematics | Zhangir Azerbayev | 2023 | arXiv:2310.10631 | ICLR 2024 | EleutherAI开发的开源数学语言模型，在Proof-Pile-2数据集上继续预训练Code Llama，支持数学推理和工具使用。 |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | (DeepSeek-AI) | 2024 | arXiv:2405.14333 | arXiv Preprint | 通过大规模合成数据增强Lean形式化定理证明能力的LLM。 |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | (DeepSeek-AI) | 2024 | arXiv:2408.08152 | arXiv Preprint | 利用证明助手反馈进行强化学习和蒙特卡洛树搜索优化的Lean 4定理证明模型。 |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | (DeepSeek-AI) | 2025 | arXiv:2504.21801 | arXiv Preprint | 最新的开源形式化定理证明模型，利用递归定理证明管线和DeepSeek-V3进行子目标分解。 |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | Huaiyuan Ying | 2024 | arXiv:2402.06332 | arXiv Preprint | 上海AI Lab开发的开源双语数学推理模型，集成链式思考推理、Lean 4证明和MATH求解。 |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | Ke Wang | 2023 | arXiv:2310.03731 | ICLR 2024 | 通过无缝代码集成增强LLM数学推理能力的模型系列，使用MathCodeInstruct数据集微调。 |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | Aitor Lewkowycz | 2022 | arXiv:2206.14858 | NeurIPS 2022 | Google开发的大语言模型，通过在科学和数学论文上训练增强定量推理能力，支持数学、物理和工程问题求解。 |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | (Goedel Lab) | 2025 | arXiv:2502.07640 | arXiv Preprint | 开源Lean形式化定理证明模型，基于大规模合成数据训练，推进自动定理证明前沿。 |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | (Goedel Lab) | 2025 | arXiv:2508.03613 | arXiv Preprint | Goedel-Prover的扩展版本，引入强化学习进一步提升定理证明能力。 |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | (Moonshot AI) | 2025 | arXiv:2504.11354 | arXiv Preprint | 720亿参数Lean定理证明模型，在miniF2F基准上达到80.7%通过率。 |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | (ByteDance) | 2025 | arXiv:2507.23726 | arXiv Preprint | 字节跳动开发的形式化数学推理模型，在2025年IMO中解出5/6题。 |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | (ByteDance) | 2025 | arXiv:2512.17260 | arXiv Preprint | Seed-Prover升级版，采用大规模强化学习训练，进一步提升形式化证明能力。 |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | (Shanghai AI Lab) | 2024 | arXiv:2410.15700 | arXiv Preprint | 上海AI Lab开发的基于专家迭代的Lean定理证明模型，结合批评引导搜索策略。 |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | — | 2025 | — | ICLR 2025 | 自提升LLM生成形式化验证代码 |
| Leanstral | First open-source AI agent for formal verification in Lean 4 | Mistral AI | 2026 | HuggingFace | Mistral AI | Mistral AI首个开源Lean 4形式验证AI |
| STP | Self-play Theorem Prover in Lean | Kefan Dong (Stanford) | 2025 | arXiv:2502.00212 | ICML 2025 | 自我对弈LLM在Lean中交替猜想和证明 |

---

<a id="mathematics-section-02"></a>
### 科学多模态推理

#### 综述 Overview

科学多模态推理基础模型涵盖跨学科科学知识理解与推理的大规模模型，支持文本、图像、分子等多模态科学数据的处理和推理。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | Lei Bai | 2025 | arXiv:2508.15763 | arXiv | 上海AI Lab的2410亿参数MoE科学多模态基础模型，在万亿级科学数据上训练。, supporting text/image/video scientific reasoning. |
| Galactica | Galactica: A Large Language Model for Science | Ross Taylor | 2022 | arXiv:2211.09085 | arXiv | Meta AI开发的科学语言模型（1.25亿-1200亿参数），在1060亿token科学文献上训练。pporting paper summarization, math reasoning, and molecular understanding. |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | Dan Zhang | 2024 | arXiv:2401.07950 | ACL 2024 | 基于自反射指令标注和调优的科学语言模型，增强LLM在物理、化学、数学和形式证明等领域的推理能力。 |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | Liangtai Sun | 2024 | arXiv:2409.18412 | NeurIPS 2024 | 从零训练的182亿参数（56亿活跃）MoE科学基础模型，支持分子、氨基酸序列等领域特异性知识理解。 |
| Intern-S1-Pro | Scientific Multimodal Foundation Model at Trillion Scale | Shanghai AI Lab | 2026 | arXiv:2603.25040 | arXiv | 万亿参数MoE科学多模态FM，覆盖化学、物理、生命科学、地球科学 |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal FM for Cross-Disciplinary Scientific Research | — | 2025 | arXiv:2601.01363 | arXiv | 统一多模态FM用于跨学科科学研究 |

---

---

<a id="mathematics-section-03"></a>
### 数学推理LLM

#### 综述 Overview

数学推理LLM专注于通过预训练和微调提升大语言模型在数学问题求解（算术、代数、竞赛数学等）中的推理能力，通常在大规模数学语料或合成数据上训练。

---

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Qwen2.5-Math | Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement | (Alibaba Qwen Team) | 2024 | — | 技术报告 | 阿里巴巴开发的双语（中英）数学LLM系列，1.5B-72B参数，在数学推理基准上达到领先水平。 |
| DeepSeekMath | DeepSeek-Math: Pushing the Limits of Mathematical Reasoning in Open Language Models | (DeepSeek-AI) | 2024 | arXiv:2402.03300 | arXiv Preprint | 7B参数数学推理模型，在1200亿数学token上继续预训练，推进开源数学推理极限。 |
| Mathstral | Mathstral: Mathematics-Specialized 7B Model | (Mistral AI) | 2024 | — | Mistral AI发布 | Mistral AI开发的7B参数数学专用模型，针对数学推理和问题求解优化。 |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | Haipeng Luo | 2023 | arXiv:2308.09583 | arXiv Preprint | 通过强化进化指令方法增强LLM数学推理能力。 |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | Xiang Yue | 2023 | arXiv:2309.05653 | ICLR 2024 | 通过混合指令微调（CoT + PoT）构建的数学通用模型，使用MathInstruct数据集。 |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | Xiang Yue | 2024 | arXiv:2405.03548 | arXiv Preprint | MAmmoTH升级版，利用网络规模数据扩展数学指令训练。 |

---

> **总计 / Total: 29 models** — 定理证明 TheoremProving: 17 | 科学多模态推理 ScientificReasoning: 6 | 数学推理LLM MathReasoning: 6

## 农业与生态

> [英文](agriculture-ecology/agriculture-ecology_en.md) | [中文](agriculture-ecology/agriculture-ecology_zh.md)

### 目录
- [作物与生态遥感](#agriculture-ecology-section-01)

<a id="agriculture-ecology-section-01"></a>
### 作物与生态遥感

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
