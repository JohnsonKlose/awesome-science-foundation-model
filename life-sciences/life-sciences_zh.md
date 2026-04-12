# 生命科学

<p align="right"><strong>Language:</strong> <a href="life-sciences_en.md">English</a> | 中文</p>

> 覆盖蛋白质、RNA、DNA与基因组、单细胞、空间转录组、抗体与免疫、冷冻电镜、宏基因组等生命科学基础模型。
> [总览](../README.zh.md)

## 目录
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
## 蛋白质

### 蛋白质语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ESM-1b | Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences | Alexander Rives | 2021 | 10.1073/pnas.2016239118 | PNAS | 大规模无监督蛋白质语言模型，在2.5亿蛋白质序列上训练，捕获进化多样性和生物学特性 |
| ESM-2 | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 150亿参数的蛋白质语言模型，支持从单序列直接预测原子级蛋白质结构(ESMFold) |
| ESM3 | Simulating 500 million years of evolution with a language model | Alexander Rives | 2025 | 10.1126/science.ads0018 | Science | 多模态蛋白质生成模型，可同时处理序列、结构和功能，模拟5亿年进化 |
| ESMFold | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 基于ESM-2的单序列蛋白质结构预测方法，速度比AlphaFold2快约60倍 |
| ESM Cambrian (ESMC) | ESM Cambrian: Revealing the mysteries of proteins with unsupervised learning | EvolutionaryScale | 2024 | — | EvolutionaryScale Blog | ESM系列新一代蛋白质语言模型，通过无监督学习揭示蛋白质内在生物学规律 |
| ProtTrans | ProtTrans: Toward understanding the language of life through self-supervised learning | Ahmed Elnaggar | 2021 | 10.1109/TPAMI.2021.3095381 | IEEE TPAMI | 大规模蛋白质预训练模型套件(含ProtBERT、ProtXLNet、ProtT5等)，在3930亿氨基酸上训练 |
| ProteinBERT | ProteinBERT: A universal deep-learning model of protein sequence and function | Nadav Brandes | 2022 | 10.1093/bioinformatics/btac020 | Bioinformatics | 通用蛋白质深度学习模型，同时预训练序列和GO注释，适用于多种蛋白质属性预测 |
| ProtGPT2 | ProtGPT2 is a deep unsupervised language model for protein design | Noelia Ferruz | 2022 | 10.1038/s41467-022-32007-7 | Nature Communications | 基于GPT-2的蛋白质序列生成模型，可生成与天然蛋白类似的新序列 |
| ProGen | Large language models generate functional protein sequences across diverse families | Ali Madani | 2023 | 10.1038/s41587-022-01618-2 | Nature Biotechnology | Salesforce开发的大规模蛋白质语言模型，在2.8亿序列上训练，生成功能性人工蛋白 |
| ProGen2 | ProGen2: Exploring the boundaries of protein language models | Erik Nijkamp | 2023 | 10.1016/j.cels.2023.10.002 | Cell Systems | 64亿参数的蛋白质语言模型，在基因组、元基因组和蛋白质家族数据上训练 |
| ProGen3 | Scaling unlocks broader generation and deeper functional understanding of proteins | EvolutionaryScale | 2025 | bioRxiv:2025.04.15.649055 | bioRxiv | 稀疏混合专家蛋白质生成模型，在1.5万亿token上训练，增强蛋白质设计能力 |
| SaProt | SaProt: Protein language modeling with structure-aware vocabulary | Jingjing Gong | 2024 | ICLR 2024 | ICLR 2024 (Spotlight) | 结构感知蛋白质语言模型，利用Foldseek将3D结构编码为离散token与序列联合训练 |
| xTrimoPGLM | xTrimoPGLM: Unified 100B-scale pre-trained transformer for deciphering the language of protein | Bo Chen | 2025 | 10.1038/s41592-025-02636-z | Nature Methods | 1000亿参数统一蛋白质语言模型，同时支持蛋白质理解和生成任务 |
| Ankh | Ankh: Optimized protein language model unlocks general-purpose modelling | Ahmed Elnaggar | 2023 | arXiv:2301.06568 | arXiv Preprint | 优化的蛋白质语言模型，强调训练效率，以更少资源达到竞争性能 |
| ProCyon | ProCyon: A multimodal foundation model for protein phenotypes | — | 2024 | bioRxiv:2024.12.10.627665 | bioRxiv | 多模态蛋白质基础模型，整合序列、结构和自然语言数据预测蛋白质表型 |
| ProSST | ProSST: Protein language modeling with quantized structure and disentangled attention | — | 2024 | doi:10.52202/079017-1126 | NeurIPS 2024 | 结合氨基酸序列与量化3D结构信息的蛋白质语言模型 |
| InstructPLM | InstructPLM: Aligning protein language models to follow protein design instructions | — | 2024 | arXiv:2510.03370 | arXiv | 通过指令微调ESM2，在蛋白质设计任务上超越ESM3 |
| UniRep | Unified rational protein engineering with sequence-based deep representation learning | Alley et al. | 2019 | doi:10.1038/s41592-019-0598-1 | Nature Methods | 基于RNN的蛋白质语言模型，用于统一表征学习和理性蛋白质工程。 |
| MSA Transformer | MSA Transformer | Rao et al. | 2021 | doi:10.1101/2021.02.12.430858 | ICML 2021 | 在多序列比对上运行的Transformer模型，用于改进蛋白质建模。 |
| EVE | Disease variant prediction with deep generative models of evolutionary data | Frazer et al. | 2021 | doi:10.1038/s41586-021-04043-8 | Nature | 进化变分自编码器，用于从蛋白质家族数据预测致病遗传变异。 |
| Tranception | Protein fitness prediction with autoregressive transformers and inference-time retrieval | Notin et al. | 2022 | arXiv:2205.13760 | ICML 2022 | 带检索时比对上下文的自回归语言模型，用于蛋白质适应性预测。 |
| RITA | RITA: a Study on Scaling Up Generative Protein Sequence Models | Hesslow et al. | 2022 | arXiv:2205.05789 | Preprint | 自回归蛋白质生成模型的缩放研究，参数量达12亿。 |
| ProtSSN | Semantical and Geometrical Protein Encoding for Zero-Shot Engineering | — | 2024 | eLife 2024 | eLife | 结构加序列去噪预训练框架，用于零样本蛋白质工程。 |
| ProLLaMA | ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing | Lv et al. | 2024 | arXiv:doi:10.1109/tai.2025.3564914 | IEEE 2025 | 基于LLaMA架构的多任务蛋白质大语言模型，用于多种蛋白质语言处理任务。 |
| ProTrek | ProTrek: Navigating the Protein Universe through Tri-Modal Contrastive Learning | Su et al. | 2024 | doi:10.1038/s41587-025-02836-0 | Nature Biotechnology | 通过对比学习联合建模序列、结构和功能的三模态蛋白质模型。 |
| ProtWord | ProtWord: A Discrete Protein Language Model for Functional Discovery and De Novo Design | — | 2026 | github | Preprint | 1.5亿参数的离散蛋白质语言模型，将序列翻译为8,192词元词汇表用于功能发现。 |
| ProtLLM | ProtLLM: An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training | — | 2024 | arXiv | Preprint | 具有动态蛋白质挂载机制的交错蛋白质-语言大语言模型。 |
| ProtHyena | Hyena architecture enables fast and efficient protein language modeling | — | 2024 | doi:10.1002/imo2.45 | iMetaOmics | 基于Hyena隐式卷积的快速蛋白质语言模型，用于高效序列处理。 |
| DPLM | Diffusion Language Models Are Versatile Protein Learners | Wang et al. | 2024 | arXiv:2402.18567 | ICML 2024 | 基于扩散的语言模型，用于多功能蛋白质序列生成和理解。 |
| PTM-Mamba | PTM-Mamba: a PTM-aware protein language model with bidirectional gated Mamba blocks | — | 2025 | doi:10.1038/s41592-025-02656-9 | Nature Methods | 具有双向门控Mamba模块的状态空间模型，用于翻译后修饰感知蛋白质表征。 |
| DeepSequence | Deep generative models of genetic variation capture the effects of mutations | Riesselman et al. | 2018 | doi:10.1038/s41592-018-0138-4 | Nature Methods | 在比对的蛋白质家族上的变分自编码器，用于预测突变效应。 |
| PoET | PoET: A generative model of protein families as sequences-of-sequences | Truong et al. | 2024 | arXiv:2306.06156 | NeurIPS 2024 | 具有检索功能的序列的序列家族建模框架，用于蛋白质适应性预测。 |
| Prot2Text | Prot2Text: Multimodal Protein's Function Generation with GNNs and Transformers | — | 2024 | doi:10.1609/aaai.v38i10.28948 | AAAI 2024 | 从结构和序列生成蛋白质功能自然语言描述的多模态模型。 |
| PAIR | Boosting the predictive power of protein representations with a corpus of text annotations | — | 2025 | doi:10.1038/s42256-025-01088-6 | Nature Machine Intelligence | 通过整合文本标注语料库来增强蛋白质表征的方法。 |
| MULAN | MULAN: Multimodal protein language model for sequence and structure encoding | — | 2024 | doi:10.1093/bioadv/vbaf117 | Bioinformatics Advances | 联合建模序列和结构信息的多模态蛋白质编码器。 |
| ProteinSage | ProteinSage: From implicit learning to explicit structural constraints for efficient protein language modeling | — | 2026 | bioRxiv:2026.03.17.712034 | bioRxiv | 新型蛋白质语言模型，将隐式学习与显式结构约束结合，提升效率和表征质量 |
| OneProt | OneProt: Towards Multi-Modal Protein Foundation Models | — | 2024/2025 | arXiv:2411.04863 | arXiv | 多模态蛋白质基础模型，整合结构、序列、文本和结合位点数据 |
| ECNet | ECNet: Evolutionary context-integrated neural network for protein engineering | — | 2022 | doi:10.1038/s41467-022-29076-z | Nature Communications | 进化上下文整合的深度学习框架，用于蛋白质工程和适应性预测 |
| PoET-2 | PoET-2: Next-generation Protein Family Modeling with Sequences-of-Sequences | (OpenProtein.AI) | 2025 | — | Preprint | PoET的升级版，增强蛋白质家族建模能力，改进序列-序列架构的蛋白质适应性预测。 |
| FlexRibbon | FlexRibbon: Foundation Model for Flexible Protein Representation | — | 2025 | — | Preprint | 灵活蛋白质表示基础模型，支持多种蛋白质分析和设计下游任务。 |
| ProteinAligner | ProteinAligner: Cross-Modal Alignment for Protein Sequence and Structure | — | 2025 | — | Preprint | 蛋白质序列-结构跨模态对齐基础模型，增强蛋白质理解和功能预测。 |
| ProteinTalks | ProteinTalks: Multi-Modal Protein Language Model with Natural Language Interaction | — | 2025 | — | Preprint | 支持自然语言交互的多模态蛋白质语言模型，将蛋白质知识与自然语言理解结合。 |
| GearNet | Protein Representation Learning by Geometric Structure Pretraining | Zuobai Zhang | 2023 | arXiv:2203.06125 | ICLR 2023 | 关系图神经网络，通过几何结构预训练和多视图对比学习学习蛋白质结构表示 |
| MIF | Masked Inverse Folding with Sequence Transfer for Protein Representation Learning | Kevin Yang | 2022 | arXiv:2209.07203 | bioRxiv | 通过掩码逆折叠自监督预训练学习蛋白质表示 |
| PPLM | A paired sequence language model for protein-protein interaction | Jun Liu | 2026 | doi:10.1038/s41467-026-70457-5 | Nature Communications | 成对序列语言模型，预测蛋白质-蛋白质相互作用 |

### 蛋白质结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaFold2 | Highly accurate protein structure prediction with AlphaFold | John Jumper | 2021 | 10.1038/s41586-021-03819-2 | Nature | DeepMind开发的革命性蛋白质结构预测模型，在CASP14中达到原子级精度 |
| AlphaFold3 | Accurate structure prediction of biomolecular interactions with AlphaFold 3 | Josh Abramson | 2024 | 10.1038/s41586-024-07487-w | Nature | 基于扩散模型的生物分子相互作用结构预测，支持蛋白质、核酸、小分子、离子等 |
| RoseTTAFold | Accurate prediction of protein structures and interactions using a three-track neural network | Minkyung Baek | 2021 | 10.1126/science.abj8754 | Science | 三轨道神经网络蛋白质结构预测模型，开源替代AlphaFold2 |
| RoseTTAFold2 | Efficient and accurate prediction of protein structure using RoseTTAFold2 | — | 2023 | bioRxiv:2023.05.24.542179 | bioRxiv | RoseTTAFold升级版，结合AlphaFold2和RoseTTAFold的关键特征 |
| RoseTTAFold All-Atom | Generalized biomolecular modeling and design with RoseTTAFold All-Atom | Rohith Krishna | 2024 | 10.1126/science.adl2528 | Science | 全原子生物分子建模框架，支持蛋白质、核酸、小分子、金属离子的复合物预测 |
| OmegaFold | High-resolution de novo structure prediction from primary sequence | Ruidong Wu | 2022 | bioRxiv:2022.07.21.500999 | bioRxiv | 无需MSA的单序列蛋白质结构预测方法，利用预训练蛋白质语言模型 |

### 蛋白质设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProteinMPNN | Robust deep learning-based protein sequence design using ProteinMPNN | Justas Dauparas | 2022 | 10.1126/science.add2187 | Science | 基于消息传递神经网络的蛋白质序列设计方法，实验验证成功率极高 |
| RFdiffusion | De novo design of protein structure and function with RFdiffusion | Joseph Watson | 2023 | 10.1038/s41586-023-06415-8 | Nature | 基于RoseTTAFold的扩散模型，实现从头设计蛋白质骨架 |
| RFdiffusion3 | RFdiffusion3: All-atom biomolecular design | Baker Lab | 2025 | — | IPD Release | RFdiffusion升级版，支持全原子级蛋白质与生物分子设计 |
| Chroma | Illuminating protein space with a programmable generative model | John Ingraham | 2023 | 10.1038/s41586-023-06728-8 | Nature | Generate:Biomedicines开发的可编程蛋白质扩散生成模型 |
| FrameDiff | SE(3) diffusion model with application to protein backbone generation | Jason Yim | 2023 | arXiv:2302.02277 | ICLR 2024 | SE(3)等变扩散模型，用于蛋白质骨架生成，无需预训练结构预测网络 |
| FrameFlow | SE(3) stochastic flow matching for protein backbone generation | Jason Yim | 2024 | arXiv:2310.02391 | ICLR 2024 | 基于SE(3)流匹配的蛋白质骨架生成模型 |
| FoldingDiff | Protein structure generation via folding diffusion | Kevin Wu | 2024 | 10.1038/s41467-024-45051-2 | Nature Communications | 基于蛋白质折叠角度表示的扩散模型，模拟自然折叠过程 |
| Genie | Genie: SE(3)-equivariant generative model for protein backbone design | Yeqing Lin | 2023 | arXiv:2301.12485 | ICML 2023 (Workshop) | SE(3)等变DDPM蛋白质骨架设计模型 |
| Genie 2 | Out of many, one: Designing and scaffolding proteins at the scale of the structural universe with Genie 2 | Yeqing Lin | 2024 | arXiv:2405.15489 | arXiv | Genie升级版，捕获更广泛多样的蛋白质结构空间 |
| Proteus | Proteus: Exploring protein structure generation for enhanced designability and efficiency | Chentong Wang | 2024 | bioRxiv:2024.02.10.579791 | bioRxiv | 高效蛋白质骨架生成模型，无需预训练结构预测网络 |
| FoldFlow | FoldFlow: SE(3) stochastic flow matching for protein backbone generation | — | 2024 | arXiv:2310.02391 | ICLR 2024 | 基于随机流匹配的蛋白质骨架生成模型族 |
| ProteinGenerator (PG) | Multistate and functional protein design using RoseTTAFold | Sidney Lyayber | 2024 | 10.1038/s41587-024-02395-w | Nature Biotechnology | 基于RoseTTAFold的扩散模型，同时生成蛋白质序列和结构 |
| SeedProteo | SeedProteo: All-atom protein design | — | 2024 | arXiv:2512.24192 | arXiv | 基于扩散的全原子蛋白质设计模型，整合结构和序列信息 |
| ESM-IF (ESM-IF1) | Language models generalize beyond natural proteins | Hsu et al. | 2022 | doi:10.1101/2022.12.21.521521 | bioRxiv | 基于骨架结构条件化的逆折叠模型，用于生成蛋白质序列。 |
| EvoDiff | Protein generation with evolutionary diffusion | Alamdari et al. | 2023 | doi:10.1101/2023.09.11.556673 | bioRxiv/Nature Biotechnology | 利用进化数据的基于序列的扩散模型，用于蛋白质生成。 |
| ZymCTRL | ZymCTRL: a conditional language model for the generation of artificial enzymes | Munsamy et al. | 2022 | doi:10.1101/2024.05.03.592223 | bioRxiv | 在3700万BRENDA酶序列上训练的条件酶语言模型。 |
| PiFold | PiFold: Toward effective and efficient protein inverse folding | Gao et al. | 2023 | doi:10.48550/arXiv.2209.12643 | ICLR 2023 | 具有新型PiGNN架构的高效逆折叠模型。 |
| LM-Design | Structure-informed language models are protein designers | Zheng et al. | 2023 | doi:10.1101/2023.02.03.526917 | ICML 2023 | 结合蛋白质语言模型和结构上下文的结构信息引导蛋白质设计语言模型。 |
| ProteinDT | A text-guided protein design framework | Liu et al. | 2025 | doi:10.1038/s42256-025-01011-z | Nature Machine Intelligence | 使用多模态学习的文本引导蛋白质生成框架。 |
| Protpardelle | An all-atom protein generative model | Chu et al. | 2024 | doi:10.1073/pnas.2311500121 | PNAS | 全原子生成模型，用于生成包含侧链的完整蛋白质结构。 |
| Multiflow | Generative Flows on Discrete State-Spaces for Protein Co-Design | Campbell et al. | 2024 | arXiv:2402.04997 | ICML 2024 | 离散流匹配框架，用于序列-结构联合蛋白质协同设计。 |
| La-Proteina | La-Proteina: Atomistic Protein Generation via Partially Latent Flow Matching | — | 2025 | arXiv:2507.09466 | Preprint | 通过部分潜在流匹配的原子级蛋白质生成方法。 |
| EvoFlows | Evolutionary Edit-Based Flow-Matching for Protein Engineering | — | 2026 | arXiv:2603.11703 | Preprint | 基于进化编辑的流匹配方法，用于定向蛋白质工程。 |
| Fold2Seq | Fold2Seq: A joint sequence(1D)-fold(3D) embedding-based generative model for protein design | — | 2021 | arXiv:2106.13058 | ICML 2021 | 联合序列-折叠嵌入的蛋白质设计生成模型，从3D结构和1D序列联合学习 |
| TERMinator | TERMinator: A neural framework for structure-based protein design using tertiary repeating motifs | — | 2022 | doi:10.1038/s41467-022-37051-7 | Nature Communications | 基于三级重复基序的蛋白质设计神经网络框架 |
| AlphaDesign | AlphaDesign: A graph protein design method and benchmark on AlphaFoldDB | — | 2022 | arXiv:2202.01079 | arXiv | 基于AlphaFoldDB的图蛋白质设计方法和基准测试 |
| Latent-X | Latent-X: Atom-level frontier model for de novo protein binder design | Latent Labs | 2025 | — | arXiv Preprint | 原子级前沿模型，用于从头蛋白质结合物设计 |
| Latent-X2 | Latent-X2: Drug-like antibodies with low immunogenicity | Latent Labs | 2025 | — | Latent Labs | 低免疫原性的药物级抗体设计模型 |
| ProDiT | Generating functional proteins with a multimodal diffusion transformer | — | 2025 | bioRxiv:2025.09.03.672144 | bioRxiv | 多模态扩散Transformer蛋白质设计模型，在2.14亿蛋白上训练 |
| SimpleDesign | SimpleDesign: Joint Model for Protein Sequence and Structure Codesign | — | 2025 | OpenReview | ICLR 2025 | 端到端蛋白质序列-结构联合设计模型 |
| PXDesign | PXDesign: Fast De Novo Design of Protein Binders | Protenix (ByteDance) | 2025 | bioRxiv:2025.08.15.670450 | bioRxiv | 字节跳动Protenix快速蛋白质结合物从头设计 |

### 肽基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PepMLM | Target Sequence-Conditioned Generation of Therapeutic Peptide Binders via Span Masked Language Modeling | Tianlai Chen | 2023/2025 | arXiv:2310.03842 | Nature Biotechnology / ICLR 2024 | 基于ESM-2微调的span masked LM，根据靶蛋白序列条件生成线性肽结合物 |
| PepBERT | PepBERT: Lightweight language models for peptide representation | Zhenjiao Du | 2025 | bioRxiv:2025.04.08.647838 | bioRxiv | 轻量级专用肽语言模型，用于生物活性肽发现和表示学习 |
| PepDoRA | PepDoRA: A Unified Peptide Language Model via Weight-Decomposed Low-Rank Adaptation | — | 2024 | arXiv:2410.20667 | arXiv | 统一的肽语言模型，通过权重分解低秩适应预测多种肽属性 |
| AMP-Designer | A foundation model approach to guide antimicrobial peptide design in the era of AI-driven scientific discovery | Tingjun Hou | 2024/2025 | arXiv:2407.12296 | Science Advances | 基于LLM的抗菌肽设计基础模型，可从头设计具有显著抗菌活性的新型AMP |
| AMP-Diffusion | AMP-Diffusion: Integrating Latent Diffusion with Protein Language Models for Antimicrobial Peptide Generation | Tianlai Chen | 2024 | bioRxiv:2024.03.03.583201 | bioRxiv | 将潜空间扩散与ESM-2蛋白质语言模型结合，生成新型抗菌肽 |
| deepAMP | A Foundation Model Identifies Broad-Spectrum Antimicrobial Peptides against Drug-Resistant Bacterial Infection | — | 2024 | doi:10.1038/s41467-024-51933-2 | Nature Communications | 基于肽语言模型的深度生成框架，识别广谱抗菌肽对抗耐药菌感染 |
| RFpeptides | Accurate de novo design of high-affinity protein-binding macrocycles | Stephen Rettie | 2024/2025 | doi:10.1038/s41589-025-01929-w | Nature Chemical Biology | 基于RoseTTAFold的去噪扩散模型，用于大环肽从头设计 |
| AfCycDesign | Cyclic peptide structure prediction and design using AlphaFold2 | Stephen Rettie | 2025 | doi:10.1038/s41467-025-59940-7 | Nature Communications | 利用AlphaFold2进行环肽结构预测、重设计和从头生成 |
| CP-Composer | Zero-Shot Cyclic Peptide Design via Composable Geometric Constraints | — | 2025 | arXiv:2507.04225 | ICML 2025 | 基于可组合几何约束的零样本环肽设计框架 |
| CpSDE | Designing Cyclic Peptides via Harmonic SDE with Atom-Bond Modeling | — | 2025 | arXiv:2505.21452 | ICML 2025 | 使用谐波随机微分方程和原子-键建模的环肽设计方法 |
| PDeepPP | A general language model for peptide identification | Jixiu Zhai | 2025 | arXiv:2502.15610 | arXiv | 通用的肽功能预测深度学习框架，结合预训练蛋白质语言模型与Transformer-CNN架构 |

### 蛋白质-蛋白质相互作用

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PLM-interact | PLM-interact: extending protein language models to predict protein-protein interactions | Dan Liu | 2025 | doi:10.1038/s41467-025-64512-w | Nature Communications | 扩展蛋白质语言模型用于PPI预测，联合编码蛋白对，仅需氨基酸序列 |
| IntFold | IntFold: A Controllable Foundation Model for General and Specialized Biomolecular Structure Prediction | IntFold Team | 2025 | arXiv:2507.02025 | arXiv | 可控生物分子结构预测基础模型，精度媲美AlphaFold3，支持PPI复合物预测和变构状态 |

### 蛋白质动力学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProTDyn | ProTDyn: a foundation Protein language model for Thermodynamics and Dynamics | — | 2025 | arXiv:2510.00013 | NeurIPS 2025 | 蛋白质热力学与动力学基础语言模型，统一构象集合生成和多时间尺度动力学建模 |
| SeqDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | bioRxiv Preprint | 结合生物物理动力学的蛋白质语言模型，训练于>64,000个蛋白质的MD模拟和简正模式分析 |
| ESMDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | bioRxiv Preprint | ESM-2微调版本，用于蛋白质构象动力学预测 |
| MD-LLM-1 | MD-LLM-1: A Large Language Model for Molecular Dynamics | Mhd Hussein Murtada | 2025 | arXiv:2508.03709 | arXiv | 首个分子动力学大语言模型，微调Mistral 7B用于蛋白质构象动力学预测 |
| VibeGen | Agentic End-to-End De Novo Protein Design for Tailored Dynamics Using a Language Diffusion Model | Markus Buehler | 2025 | arXiv:2502.10173 | arXiv (MIT) | 基于语言扩散模型的端到端蛋白质动力学设计框架，面向振动模式定制设计 |
| DynamicsPLM | Learning Protein Representations with Conformational Dynamics | Dan Kalifa | 2025 | bioRxiv:2025.10.06.680789 | bioRxiv | 结合构象动力学集合的蛋白质语言模型，从计算生成的结构集合中学习 |
| DPLM-2 | DPLM-2: A Multimodal Diffusion Protein Language Model | Xinyou Wang | 2024/2025 | arXiv:2410.13782 | NeurIPS 2025 (ByteDance) | 多模态离散扩散蛋白质语言模型，联合建模氨基酸序列和3D结构 |
| METL | Biophysics-based protein language models for protein engineering | — | 2025 | doi:10.1038/s41592-025-02776-2 | Nature Methods | 突变效应迁移学习框架，整合生物物理建模和机器学习用于蛋白质工程 |

---

<a id="life-sciences-section-02"></a>
## RNA

### RNA语言模型

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
| OmniGenome | Bridging sequence-structure alignment in RNA foundation models | — | 2024 | arXiv:2407.11242 | arXiv | 将RNA序列与二级结构精确对齐的RNA基础模型 |
| structRFM | A fully open structure-guided RNA foundation model for robust structural and functional inference | — | 2025 | — | Preprint | 完全开源的结构引导RNA基础模型，用于结构和功能推断 |
| SpliceBERT | SpliceBERT: a pre-trained RNA language model for analyzing vertebrate splicing | Chen et al. | 2024 | doi:10.1101/2023.01.31.526427 | Genome Biology | 专门用于脊椎动物剪接分析的预训练RNA语言模型。 |
| PlantRNA-FM | An interpretable RNA foundation model for exploring functional RNA motifs in plants | Yang et al. | 2024 | doi:10.1038/s42256-024-00946-z | Nature Machine Intelligence | 用于植物生物学的可解释RNA基础模型，覆盖1,124+种植物。 |
| AllSplice | Perturbation-aware predictive modeling of RNA splicing using bidirectional transformers | McNally et al. | 2024 | doi:10.1101/2024.03.20.585793 | bioRxiv | 扰动感知双向Transformer，用于RNA剪接预测。 |
| HydraRNA | HydraRNA: A hybrid architecture based full-length RNA language model | — | 2025 | doi:10.1186/s13059-025-03853-7 | Genome Biology | 混合架构全长RNA语言模型，结合多种架构优势处理全长RNA序列 |
| EVA-RNA | EVA-RNA: A Scaling Cross-Species Transcriptomic Foundation Model for Immunology & Inflammation | — | 2026 | OpenReview:VcOvSJNgRf | OpenReview | 跨物种转录组基础模型，训练于50万+人鼠样本，专注免疫与炎症研究 |
| GRNFormer | GRNFormer: A Biologically-Guided Framework for Integrating Gene Regulatory Networks into RNA Foundation Models | — | 2025 | arXiv:2503.01682 | arXiv | 将基因调控网络整合到RNA基础模型的生物学引导框架 |
| BMFM-RNA | BMFM-RNA: Whole-cell expression decoding improves transcriptomic foundation models | — | 2025 | arXiv:2506.14861 | arXiv (IBM) | IBM生物医学基础模型RNA模块，全细胞表达解码增强转录组基础模型 |
| CodonFM | CodonFM: Foundation Models for Codons | NVIDIA/Arc Institute | 2025 | github | Preprint | 密码子基础模型，在1.3亿蛋白质编码序列上训练 |
| Orthrus | Orthrus: Evolutionary and Functional RNA Foundation Models | Bo Wang | 2024 | bioRxiv:2024.10.10.617658 | bioRxiv Preprint | 生物增强对比学习RNA基础模型 |

### RNA结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RhoFold+ | Accurate RNA 3D structure prediction using a language model-based deep learning approach | Tao Shen | 2024 | 10.1038/s41592-024-02487-0 | Nature Methods | 基于预训练RNA语言模型的RNA 3D结构预测，在2370万序列上训练 |
| RhoFold | RhoFold: Fast and accurate RNA 3D structure prediction | — | 2023 | — | CUHK | 基于深度学习的RNA 3D结构预测模型 |
| RNA-FrameFlow | Flow Matching for de novo 3D RNA Backbone Design | — | 2024 | arXiv:2406.13839 | Preprint | SE(3)流匹配方法，用于从头设计3D RNA骨架结构。 |
| DRfold2 | Ab initio RNA structure prediction with composite language model | Zhang et al. | 2025 | doi:10.1101/2025.03.05.641632 | bioRxiv | 使用复合语言模型的从头RNA 3D结构预测深度学习框架。 |
| 3DRNALM | Accurate RNA 3D structure prediction using a language model-based framework | — | 2024 | PMC11621015 | Nature Communications | 基于语言模型的准确RNA 3D结构预测框架。 |
| NuFold | NuFold: end-to-end approach for RNA tertiary structure prediction | Daisuke Kihara | 2025 | doi:10.1038/s41467-025-56261-7 | Nature Communications | 端到端RNA三级结构预测深度学习模型 |

### RNA设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RNAGenesis | RNAGenesis: A Generalist Foundation Model for Functional RNA Therapeutics | Zaixi Zhang | 2024 | bioRxiv:2024.12.30.630826 | bioRxiv | RNA治疗通用基础模型，统一序列表示、结构预测和功能从头设计 |
| GEMORNA | Deep generative models design mRNA sequences with enhanced translational capacity and stability | — | 2024/2025 | doi:10.1126/science.adr8470 | Science | 深度生成模型设计具有增强翻译能力和稳定性的mRNA序列 |
| EVA | A Long-Context Generative Foundation Model Deciphers RNA Design Principles | — | 2026 | bioRxiv:2026.03.17.712398 | bioRxiv (GENTEL-Lab) | 长上下文生成基础模型，14亿参数MoE架构，训练于>1.14亿全长RNA序列 |
| RNACG | RNACG: A Universal RNA Sequence Conditional Generation model based on Flow-Matching | Letian Gao | 2024 | arXiv:2407.19838 | arXiv | 基于流匹配的通用RNA序列条件生成模型 |
| RiboFlow | RiboFlow: Conditional De Novo RNA Co-Design via Synergistic Flow Matching | Runze Ma | 2025 | arXiv:2503.17007 | NeurIPS 2025 | 协同流匹配的RNA序列-结构联合设计框架，面向配体结合 |
| RiboGen | RiboGen: RNA Sequence and Structure Co-Generation with Equivariant MultiFlow | — | 2025 | arXiv:2503.02058 | ICLR 2025 | 等变多流模型同时生成RNA序列和全原子3D结构 |
| SANDSTORM | Generative and predictive neural networks for the design of functional RNA molecules | — | 2025 | doi:10.1038/s41467-025-59389-8 | Nature Communications | RNA功能预测神经网络，整合序列和二级结构数据 |
| GARDN | Generative and predictive neural networks for the design of functional RNA molecules | — | 2025 | doi:10.1038/s41467-025-59389-8 | Nature Communications | RNA功能设计生成网络，与SANDSTORM配对使用 |
| mRNA-GPT | Large generative mRNA language foundation model for efficient coding sequence generation and design | — | 2025 | bioRxiv:2025.12.22.695962 | bioRxiv | 基于GPT-2的大规模mRNA生成语言模型（302M参数），跨三个生物域的mRNA编码序列生成 |
| codonGPT | codonGPT: reinforcement learning on a generative language model enables scalable mRNA design | Lingtao Peng | 2025 | doi:10.1093/nar/gkaf1345 | Nucleic Acids Research | 强化学习+生成语言模型用于可扩展mRNA密码子优化设计 |
| RiboDecode | Deep generative optimization of mRNA codon sequences for enhanced mRNA translation and therapeutic efficacy | — | 2025 | doi:10.1038/s41467-025-64894-x | Nature Communications | mRNA密码子序列深度生成优化框架，增强翻译效率和治疗效果 |

---

<a id="life-sciences-section-03"></a>
## DNA与基因组

### DNA/基因组语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Evo | Sequence modeling and design from molecular to genome scale with Evo | Eric Nguyen | 2024 | 10.1126/science.ado9336 | Science | Arc Institute开发的DNA基础模型，处理分子到基因组尺度(>650K token)的序列 |
| Evo 2 | Genome modelling and design across all domains of life with Evo 2 | Eric Nguyen | 2025 | 10.1038/s41586-026-10176-5 | Nature | 在9万亿碱基对上训练的DNA基础模型，覆盖所有生命域，100万token上下文窗口 |
| DNABERT | DNABERT: Pre-trained bidirectional encoder representations from transformers model for DNA-language in genome | Yanrong Ji | 2021 | 10.1093/bioinformatics/btab083 | Bioinformatics | 首个将BERT架构应用于基因组DNA序列的预训练模型，使用k-mer分词 |
| DNABERT-2 | DNABERT-2: Efficient foundation model and benchmark for multi-species genome | Zhihan Zhou | 2024 | ICLR 2024 | ICLR 2024 | DNABERT升级版，采用BPE分词替代k-mer，支持多物种基因组分析 |
| Nucleotide Transformer | Nucleotide Transformer: Building and evaluating robust foundation models for human genomics | Hugo Dalla-Torre | 2024 | 10.1038/s41592-024-02523-z | Nature Methods | InstaDeep开发的大规模基因组基础模型(50M-2.5B参数)，在3200+人类基因组上训练 |
| HyenaDNA | HyenaDNA: Long-range genomic sequence modeling at single nucleotide resolution | Eric Nguyen | 2023 | NeurIPS 2023 | NeurIPS 2023 | 基于Hyena隐式卷积架构的基因组模型，单核苷酸分辨率长程建模(100万bp) |
| Enformer | Effective gene expression prediction from sequence by integrating long-range interactions | Žiga Avsec | 2021 | 10.1038/s41592-021-01252-x | Nature Methods | DeepMind/Calico开发的Transformer模型，从DNA序列预测基因表达和染色质状态 |
| Caduceus | Caduceus: Bi-directional equivariant long-range DNA sequence modeling | Yair Schiff | 2024 | arXiv:2403.03234 | ICML 2024 | 基于Mamba架构的双向DNA语言模型，支持反向互补等变性 |
| GenSLMs | GenSLMs: Genome-scale language models reveal SARS-CoV-2 evolutionary dynamics | Maxim Zvyagin | 2023 | 10.1177/10943420231210152 | IJHPCA (Gordon Bell Prize) | 基因组尺度语言模型，在1.1亿原核基因序列上预训练，分析SARS-CoV-2进化动态 |
| GROVER | DNA language model GROVER learns sequence context in the human genome | Melissa Sanabria | 2024 | 10.1038/s42256-024-00872-0 | Nature Machine Intelligence | 在人类基因组上训练的DNA语言模型，使用BPE定义DNA"词汇"，捕获CpG甲基化等特征 |
| Sei | A sequence-based global map of regulatory activity for deciphering human genetics | Kathleen M. Chen | 2022 | 10.1038/s41588-022-01102-2 | Nature Genetics | 深度学习框架，预测21,900+染色质特征，将序列映射到40个调控活性类别 |
| GPN (Genomic Pre-trained Network) | DNA language models are powerful predictors of genome-wide variant effects | Gonzalo Benegas | 2024 | — | Preprint | 无监督DNA语言模型，预测全基因组变异效应 |
| Borzoi | Borzoi decodes the complex DNA signals governing gene regulation | — | 2025 | 10.1038/s41588-025-02154-w | Nature Genetics | 从DNA序列预测RNA-seq覆盖度的深度学习模型，解析基因调控信号 |
| PlantCaduceus | Cross-species modeling of plant genomes at single-nucleotide resolution using a pretrained DNA language model | — | 2025 | 10.1073/pnas.2421738122 | PNAS | 植物特异性DNA语言模型，在16种被子植物基因组上训练，支持跨物种分析 |
| HybriDNA | HybriDNA: A hybrid Transformer-Mamba2 DNA language model | — | 2025 | arXiv:2502.10807 | arXiv | 结合Transformer和Mamba2架构的DNA语言模型，支持超长序列(131kb)单核苷酸分辨率 |
| Nucleotide Transformer v3 (NTv3) | A foundational model for joint sequence-function multi-species prediction | — | 2025 | bioRxiv | bioRxiv | 多物种长程基因组预测与功能注释基础模型 |
| Basenji | Sequential regulatory activity prediction across chromosomes with convolutional neural networks | Kelley et al. | 2018 | doi:10.1101/gr.227819.117 | Genome Research | 从DNA序列预测基因表达和调控活性的卷积神经网络。 |
| Basenji2 | Cross-species regulatory sequence activity prediction | Kelley | 2020 | doi:10.1371/journal.pcbi.1008050 | PLoS Computational Biology | 跨物种DNA调控活性预测模型。 |
| ChromBPNet | ChromBPNet: bias factorized, base-resolution deep learning models of chromatin accessibility | Pampari et al. | 2025 | doi:10.1101/2024.12.25.630221 | bioRxiv | 具有偏差分解的碱基分辨率染色质可及性预测深度学习模型。 |
| scBasset | scBasset: Sequence-based modeling of single-cell ATAC-seq using convolutional neural networks | Yuan et al. | 2022 | doi:10.1038/s41592-022-01562-8 | Nature Methods | 从DNA序列建模单细胞ATAC-seq染色质可及性的卷积神经网络。 |
| EpiGePT | EpiGePT: a Pretrained Transformer model for epigenomics | Gao et al. | 2023 | doi:10.1101/2023.07.15.549134 | bioRxiv | 用于表观基因组数据分析和预测的预训练Transformer模型。 |
| AgroNT | AgroNT: A crop genomics foundation model | Mendoza-Revilla et al. | 2024 | doi:10.1038/s41586-024-07969-x | Nature | 专用于植物基因组学和育种应用的作物基因组基础模型。 |
| AlphaGenome | Advancing regulatory variant effect prediction with AlphaGenome | Google DeepMind | 2026 | doi:10.1038/s41586-025-10014-0 | Nature | Google DeepMind的兆碱基级DNA模型，预测基因表达和染色质信号用于变异效应分析。 |
| GENA-LM | GENA-LM: A Family of Open-Source Foundational DNA Language Models for Long Sequences | — | 2023 | doi:10.1101/2023.06.12.544594 | bioRxiv/Bioinformatics | 支持最长36k bp序列的开源Transformer DNA语言模型家族。 |
| DNAGPT | DNAGPT: A Generalized Pre-trained Tool for Multiple DNA Sequence Analysis Tasks | — | 2023 | doi:10.1101/2023.07.11.548628 | bioRxiv/PLoS ONE | 用于多种DNA分析任务的生成式预训练模型。 |
| MoDNA | MoDNA: Motif-Oriented Pre-training For DNA Language Model | — | 2022 | doi:10.1145/3535508.3545512 | ACM BCB | 面向基序的预训练DNA语言模型，捕获调控基序模式。 |
| GPN-MSA | GPN-MSA: An alignment-based DNA language model for genome-wide variant effect prediction | Benegas et al. | 2023 | doi:10.1038/s41587-024-02511-w | Nature Biotechnology | 使用多物种比对的DNA语言模型，用于全基因组变异效应预测。 |
| MergeDNA | MergeDNA: Context-aware Genome Modeling with Dynamic Tokenization through Token Merging | — | 2025 | AAAI 2025 | AAAI | 分层动态词元化方法，用于上下文感知基因组建模。 |
| BMFM-DNA | BMFM-DNA: A SNP-aware DNA foundation model to capture variant effects | — | 2025 | arXiv:2507.05265 | Preprint | IBM的SNP感知DNA基础模型，用于捕获基因组序列中的变异效应。 |
| EpiAgent | EpiAgent: foundation model for single-cell epigenomics | — | 2025 | doi:10.1038/s41592-025-02822-z | Nature Methods | 用于单细胞ATAC-seq表观基因组数据分析的基础模型。 |
| Gene42 | Gene42: Long-Range Genomic Foundation Model With Dense Attention | — | 2026 | arXiv:2503.16565 | arXiv | 长程基因组基础模型，decoder-only架构，处理高达192,000碱基对的单核苷酸分辨率DNA序列 |
| dnaHNet | dnaHNet: A Scalable and Hierarchical Foundation Model for Genomic Sequence Learning | — | 2026 | arXiv:2602.10603 | arXiv | 可扩展层次化基因组序列学习基础模型 |
| JEPA-DNA | JEPA-DNA: Grounding Genomic Foundation Models through Joint-Embedding Predictive Architectures | — | 2026 | arXiv:2602.17162 | arXiv | 基于联合嵌入预测架构(JEPA)的基因组基础模型，结合生成和判别目标 |
| GeneZip | GeneZip: Region-Aware Compression for Long Context DNA Modeling | — | 2026 | arXiv:2602.17739 | arXiv | 区域感知压缩的长上下文DNA建模方法 |
| ModernGENA | ModernGENA: A modernized BERT-style DNA foundation model | — | 2025/2026 | OpenReview:U98HvYaBDE | OpenReview | 现代化BERT架构的DNA基础模型(ModernBERT适配基因组) |
| OpticalDNA | OpticalDNA: Reimagining DNA sequence analysis as an OCR task | — | 2026 | arXiv:2602.02014 | arXiv | 将DNA序列分析重构为光学字符识别(OCR)任务的新框架 |
| OmniReg-GPT | OmniReg-GPT: A Generative Pre-trained Model for Universal Gene Regulation Prediction | — | 2025 | — | Preprint | 通用基因调控预测的生成式预训练模型，跨物种跨组织的基因表达调控建模。 |
| BOTANIC-0 | BOTANIC-0: A Plant Genomic Foundation Model | — | 2025 | — | Preprint | 植物基因组基础模型，在大规模植物DNA序列上预训练，支持作物育种和功能基因组学。 |
| Species-aware DNA LM | Species-aware DNA Language Modeling | Dennis Gankin | 2023 | bioRxiv:2023.01.26.525670 | bioRxiv | 在预训练中融入物种特异性信息的DNA语言模型 |
| Genos | Genos: A Large Human-Centric Genomic Foundation Model | — (BGI / Zhejiang Lab) | 2025 | BGI-HangzhouAI/Genos | ICG-20 Conference | 全球首个100亿参数人类基因组基础模型，MoE-Transformer架构，支持百万碱基对上下文分析 |
| GENERator | GENERator: A Long-Context Generative Genomic Foundation Model | Wei Wu | 2025 | arXiv:2502.07272 | arXiv | 长上下文生成式基因组基础模型 |

---

<a id="life-sciences-section-04"></a>
## 单细胞

### 单细胞基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| scGPT | scGPT: Toward building a foundation model for single-cell multi-omics using generative AI | Haotian Cui | 2024 | 10.1038/s41592-024-02201-0 | Nature Methods | 基于生成式预训练Transformer的单细胞多组学基础模型，在3300万+细胞上训练 |
| scBERT | scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data | Fan Yang | 2022 | 10.1038/s42256-022-00534-z | Nature Machine Intelligence | 大规模BERT预训练模型，用于scRNA-seq细胞类型注释 |
| Geneformer | Transfer learning enables predictions in network biology | Christina Theodoris | 2023 | 10.1038/s41586-023-06139-9 | Nature | 在约3000万单细胞转录组上预训练的Transformer模型，通过迁移学习预测基因网络动态 |
| scFoundation | Large-scale foundation model on single-cell transcriptomics | Minsheng Hao | 2024 | 10.1038/s41592-024-02305-7 | Nature Methods | 1亿参数大规模单细胞转录组基础模型(xTrimoGene)，在5000万+人类单细胞上训练 |
| UCE (Universal Cell Embedding) | Universal Cell Embeddings: A foundation model for cell biology | Yanay Rosen | 2023 | bioRxiv:2023.11.28.568918 | bioRxiv | 通用细胞嵌入基础模型，跨物种和组织创建统一的细胞表示空间 |
| GeneCompass | GeneCompass: Deciphering universal gene regulatory mechanisms with a knowledge-informed cross-species foundation model | Xiaodong Yang | 2024 | 10.1038/s41422-024-01034-y | Cell Research | 知识增强的跨物种基础模型，在1亿+人类和小鼠细胞上训练，解析通用基因调控机制 |
| CellPLM | CellPLM: Pre-training of cell language model beyond single cells | Hongzhi Wen | 2024 | ICLR 2024 | ICLR 2024 | 超越单细胞的细胞语言模型预训练，整合基因-基因和细胞-细胞相互作用 |
| tGPT | Generative pretraining from large-scale transcriptomes for single-cell deciphering | Hongwei Li | 2023 | 10.1016/j.isci.2023.106536 | iScience | 在2230万单细胞转录组上生成式预训练，用于单细胞解析和临床翻译 |
| CellFM | CellFM: A large-scale foundation model pre-trained on transcriptomics of 100 million human cells | — | 2025 | 10.1038/s41467-025-59926-5 | Nature Communications | 8亿参数大规模基础模型，在1亿人类细胞转录组上预训练 |
| Nicheformer | Nicheformer: A foundation model for single-cell and spatial omics | — | 2025 | 10.1038/s41592-025-02814-z | Nature Methods | 单细胞和空间组学基础模型，在SpatialCorpus-110M(1.1亿+细胞)上训练，捕获空间微环境 |
| scMulan | scMulan: A multitask generative pre-trained language model for single-cell analysis | Haiyang Bian | 2024 | RECOMB 2024 | RECOMB 2024 | 多任务生成式预训练单细胞语言模型，将细胞编码为结构化"c-句子" |
| Cell2Sentence | Cell2Sentence: Teaching large language models the language of biology | Daniel Levine | 2024 | ICML 2024 | ICML 2024 | 将基因表达数据转化为自然语言句子，使LLM(如GPT-2)适应单细胞转录组学 |
| GET | GET: A foundation model of transcription across human cell types | Xi Fu | 2025 | 10.1038/s41586-024-08391-z | Nature | 通用表达Transformer，从染色质可及性和序列预测213种人类细胞类型基因表达 |
| GenePT | GenePT: A simple but effective foundation model for genes and cells built from ChatGPT | Yiqun Chen | 2024 | — | bioRxiv | 利用ChatGPT嵌入构建的简单高效基因和细胞基础模型 |
| LangCell | LangCell: Language-cell pre-training for cell identity understanding | Suyuan Zhao | 2024 | arXiv:2405.06708 | arXiv | 自然语言与单细胞转录组联合预训练，增强细胞身份理解 |
| CellVQ | Illuminating cell states by a comprehensive and interpretable single cell foundation model | — | 2026 | 10.1038/s41467-026-70071-5 | Nature Communications | 综合可解释单细胞基础模型，在6800万细胞上训练 |
| scKGBERT | scKGBERT: A knowledge-enhanced foundation model for single-cell transcriptomics | — | 2025 | doi:10.1186/s13059-025-03862-6 | Genome Biology | 知识图谱增强的单细胞转录组基础模型 |
| SATURN | Toward universal cell embeddings: integrating scRNA-seq datasets across species | Rosen et al. | 2024 | doi:10.1038/s41592-024-02191-z | Nature Methods | 跨物种通用细胞嵌入框架，整合不同物种的scRNA-seq数据。 |
| scTab | scTab: Scaling cross-tissue single-cell annotation models | Theis et al. | 2024 | doi:10.1038/s41467-024-51059-5 | Nature Communications | 可扩展的跨组织细胞类型注释深度学习模型，训练于2200万细胞。 |
| scPRINT | scPRINT: pre-training on 50 million cells allows robust gene network predictions | Kalfon et al. | 2025 | doi:10.1038/s41467-025-58699-1 | Nature Communications | 训练于5000万细胞的Transformer基础模型，用于鲁棒基因网络推断。 |
| scPRINT-2 | scPRINT-2: Towards the next-generation of cell foundation models | Kalfon et al. | 2025 | doi:10.64898/2025.12.11.693702 | bioRxiv | 下一代细胞基础模型，训练于16个物种的3.5亿细胞。 |
| scELMo | scELMo: Embeddings from Language Models are Good Learners for Single-cell Data Analysis | — | 2023 | doi:10.1101/2023.12.07.569910 | bioRxiv | 将语言模型嵌入应用于单细胞数据分析。 |
| scVI | scVI: Variational Inference for Single-Cell Gene Expression | Lopez et al. | 2018 | doi:10.1038/s41592-018-0229-2 | Nature Methods | 为单细胞转录组分析提供概率框架的深度生成模型。 |
| scANVI | scANVI: semi-supervised integration of single-cell multi-omic data | Xu et al. | 2021 | doi:10.15252/msb.20209620 | Molecular Systems Biology | 用于整合单细胞多组学数据的半监督深度生成模型。 |
| totalVI | Joint probabilistic modeling of single-cell multi-omic data with totalVI | Gayoso et al. | 2021 | doi:10.1038/s41592-020-01050-x | Nature Methods | 用于同时分析RNA和蛋白质单细胞数据的联合概率模型。 |
| scPoli | Population-level integration of single-cell datasets enables multi-scale analysis | De Donno et al. | 2023 | doi:10.1038/s41592-023-02035-2 | Nature Methods | 群体级单细胞数据集整合，实现多尺度生物学分析。 |
| scHyena | scHyena: Foundation Model for Full-Length Single-Cell RNA-Seq Analysis in Brain | — | 2023 | arXiv:2310.02713 | Preprint | 基于Hyena架构的全长scRNA-seq分析基础模型，专注于脑组织。 |
| TOSICA | TOSICA: Transfer of Omics Single-Cell Analysis | — | 2023 | Nature Communications | Nature Communications | 用于跨数据集和模态的单细胞组学分析迁移学习框架。 |
| xTrimoGene | xTrimoGene: An Efficient and Scalable Representation Learner for Single-Cell RNA-Seq Data | — | 2023 | OpenReview | NeurIPS 2023 | 使用非对称编码器-解码器架构的高效可扩展scRNA-seq表征学习器。 |
| CancerFoundation | A single-cell RNA sequencing foundation model to decipher drug resistance in cancer | — | 2024 | doi:10.1101/2024.11.01.621087 | bioRxiv | 用于解析药物耐药机制的癌症特异性scRNA-seq基础模型。 |
| Cell-GraphCompass | Cell-GraphCompass: Modeling Single Cells with Graph Structure Foundation Model | — | 2024 | doi:10.1093/nsr/nwaf255 | National Science Review | 使用基于图的细胞表征的图结构单细胞分析基础模型。 |
| scLong | scLong: A billion-parameter foundation model for capturing long-range gene context | — | 2026 | doi:10.1038/s41467-026-69102-y | Nature Communications | 十亿参数基础模型，同时关注所有28,000个基因以捕获长程上下文。 |
| Tahoe-x1 | Tahoe-x1: Scaling Perturbation-Trained Single-Cell Foundation Models to 3 Billion Parameters | — | 2025 | doi:10.1101/2025.10.23.683759 | bioRxiv | 30亿参数扰动训练单细胞基础模型，用于预测细胞响应。 |
| PULSAR | PULSAR: a Foundation Model for Multi-scale and Multicellular Biology | — | 2025 | doi:10.1101/2025.11.24.685470 | bioRxiv | 整合3600万+细胞的多尺度基础模型，用于多细胞生物学分析。 |
| TranscriptFormer | A Cross-Species Generative Cell Atlas Across 1.5 Billion Years of Evolution | — | 2025 | doi:10.1101/2025.04.25.650731 | bioRxiv | 跨越15亿年进化的跨物种生成式细胞图谱基础模型。 |
| TCRfoundation | TCRfoundation: A multimodal foundation model for single-cell immune profiling | Liao et al. | 2025 | github | bioRxiv | 整合基因表达与TCR序列的多模态免疫分析基础模型。 |
| CELLama | CELLama: Foundation Model for Single Cell and Spatial Transcriptomics | — | 2024 | doi:10.1101/2024.05.08.593094 | bioRxiv | 利用语言模型能力的细胞嵌入模型，用于单细胞和空间转录组学。 |
| scPROTEIN | scPROTEIN: versatile deep graph contrastive learning framework for single-cell proteomics | — | 2024 | doi:10.1038/s41592-024-02214-9 | Nature Methods | 用于单细胞蛋白质组学嵌入和分析的图对比学习框架。 |
| TEDDY | TEDDY: A Family of Foundation Models for Understanding Single Cell Biology | — | 2025 | arXiv:2503.03485 | ICML Workshop | 面向全面单细胞生物学理解的基础模型家族。 |
| Tabula | Tabula: A Tabular Self-Supervised Foundation Model for Single-Cell Transcriptomics | — | 2025 | NeurIPS 2025 | NeurIPS | 面向单细胞转录组学数据的表格自监督基础模型。 |
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
| Stack | Stack: In-Context Learning of Single-Cell Biology | Arc Institute | 2026 | bioRxiv:2026.01.09.698608 | bioRxiv | Arc Institute单细胞FM，1.49亿人类细胞训练，零样本预测 |
| Lingshu-Cell | Lingshu-Cell: cellular world model for transcriptome modeling | Alibaba DAMO | 2026 | arXiv:2603.25240 | arXiv | 灵枢-细胞：掩码离散扩散细胞世界模型 |

### 虚拟细胞模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaCell | Towards building a World Model to simulate perturbation-induced cellular dynamics | — | 2026 | bioRxiv:2026.03.02.709176 | bioRxiv | 虚拟细胞世界模型，模拟细胞扰动响应动力学 |
| CellFluxV2 | CellFluxV2: An Image Generative Foundation Model for Virtual Cell Modeling | Yuhui Zhang | 2026 | bioRxiv:2026.01.19.696785 | bioRxiv | 基于流匹配的虚拟细胞图像生成基础模型 |
| X-Cell | X-Cell: Scaling Causal Perturbation Prediction Across Diverse Cellular Contexts | Xaira Therapeutics | 2026 | bioRxiv:2026.03.18.712807 | bioRxiv | 大规模扩散语言模型，预测跨细胞环境的基因组级转录响应 |

---

<a id="life-sciences-section-05"></a>
## 多尺度生物学

### 多尺度生物基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Xpressor | Towards foundation models that learn across biological scales | Jeremie Kalfon | 2025 | bioRxiv:2025.05.16.653447 | bioRxiv Preprint | 跨尺度学习框架，通过交叉注意力机制整合分子、细胞和组织层面的基因表达信息 |
| AIDO | Toward AI-driven digital organism: Multiscale foundation models for predicting, simulating and programming biology at all levels | Le Song | 2024 | arXiv:2412.06993 | arXiv | GenBio AI开发的AI驱动数字生物体系统，整合DNA→RNA→蛋白质→细胞多尺度基础模型 |
| AIDO.Protein | Mixture of experts enable efficient and effective protein understanding and design | — | 2024 | bioRxiv:2024.11.29 | bioRxiv Preprint | AIDO体系中的蛋白质模块，160亿参数MoE架构，在1.2万亿氨基酸上训练 |
| SToFM | SToFM: A multi-scale foundation model for spatial transcriptomics | — | 2025 | — | ICML 2025 | 空间转录组多尺度基础模型，整合宏观组织形态和微观细胞环境 |
| OmniCell | OmniCell: Unified Foundation Modeling of Single-Cell and Spatial Transcriptomics | — | 2025 | doi:10.64898/2025.12.29.696804 | bioRxiv | 同时用于单细胞和空间转录组学分析的统一基础模型。 |

---

<a id="life-sciences-section-06"></a>
## 抗体与免疫

### 抗体语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgBERT | Large scale paired antibody language models | Henry Kenlay | 2024 | 10.1371/journal.pcbi.1012646 | PLOS Computational Biology | 在20亿+非配对和200万配对OAS抗体序列上训练的BERT抗体语言模型。 |
| IgT5 | Large scale paired antibody language models | Henry Kenlay | 2024 | 10.1371/journal.pcbi.1012646 | PLOS Computational Biology | 基于T5的配对抗体语言模型，为IgBERT的姊妹模型，用于抗体设计和工程。 |
| AntiBERTy | Deciphering antibody affinity maturation with language models and weakly supervised learning | Jeffrey A. Ruffolo | 2021 | arXiv:2112.07782 | Preprint | 在5.58亿抗体序列上训练的BERT模型，用于亲和力成熟分析。 |
| AbLang | AbLang: An antibody language model for completing antibody sequences | Tobias H. Olsen | 2022 | 10.1093/bioadv/vbac046 | Bioinformatics Advances | 在OAS上训练的抗体特异性语言模型，用于残基预测和抗体表征。 |
| AbLang2 | AbLang2: Addressing the Antibody Germline Bias | Tobias H. Olsen | 2024 | N/A | BioLM/Preprint | 改进的配对重轻链抗体语言模型，降低种系偏差。 |
| IGLOO | Multimodal antibody loop tokenizer for protein language models | — | 2025 | OpenReview | NeurIPS 2025 Workshop | 增强蛋白质语言模型的多模态抗体环区词元化器。 |
| Ab-RoBERTa | Antibody Foundational Model: Ab-RoBERTa | Eunna Huh | 2025 | arXiv:2506.13006 | arXiv preprint | 基于RoBERTa的抗体语言模型，用于互补位预测和抗体设计。 |
| BALM | Accurate Prediction of Antibody Function and Structure Using Bio-Inspired Antibody Language Model | N/A (BEAM-Labs) | 2023 | 10.1101/2023.08.30.555473 | bioRxiv | 生物启发的抗体语言模型，用于预测抗体结构和功能。 |
| Sapiens (BioPhi) | BioPhi: A platform for antibody design, humanization and humanness evaluation | David Prihoda | 2022 | 10.1126/sciadv.abj6587 | Science Advances | BioPhi平台中基于BERT的人源抗体语言模型，用于人源化和人源性评估。 |
| DASM | Separating selection from mutation in antibody language models | N/A (Matsen group) | 2025 | eLife:109644 | eLife | 深度氨基酸选择模型，在抗体序列建模中分离选择和突变过程。 |
| nanoBERT | nanoBERT: a deep learning model for gene agnostic navigation of the nanobody mutational space | Johannes Thorling Hadsund | 2024 | 10.1093/bioadv/vbae033 | Bioinformatics Advances | 纳米抗体特异性Transformer模型，预测VHH序列中的氨基酸替换。 |
| FAbCon | A generative foundation model for antibody sequence understanding | Justin Barton | 2024 | bioRxiv:2024.05.22.594943 | bioRxiv Preprint | 24亿参数抗体生成基础模型 |
| S2ALM | S2ALM: Sequence-Structure Pre-trained Large Language Model for Antibody | Mingze Yin | 2025 | arXiv:2411.15215 | Nature Methods 2025 | 序列-结构预训练抗体大语言模型 |

### 抗体结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgFold | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Jeffrey A. Ruffolo | 2023 | 10.1038/s41467-023-38063-x | Nature Communications | 使用在5.58亿序列上预训练的语言模型和图神经网络的快速抗体结构预测。 |
| DeepAb | Antibody structure prediction using interpretable deep learning | Jeffrey A. Ruffolo | 2022 | 10.1016/j.patter.2021.100406 | Patterns (Cell Press) | 可解释深度学习抗体Fv结构预测模型，专注于CDR环建模。 |
| ABodyBuilder2 | ABodyBuilder2: Antibody Structure Prediction with Updated Datasets and Confidence Estimation | Brennan Abanades | 2023 | N/A | Oxford Protein Informatics Group | 快速全原子3D结构预测模型，用于配对抗体可变区域。 |
| ABlooper | ABlooper: Fast accurate antibody CDR loop structure prediction with accuracy estimation | Brennan Abanades | 2022 | 10.1093/bioinformatics/btac016 | Bioinformatics | 快速等变神经网络，用于抗体CDR环结构预测及精度估计。 |
| AntiFold | AntiFold: Improved structure-based antibody design using inverse folding | Magnus Haraldson Høie | 2024 | arXiv:doi:10.1093/bioadv/vbae202 | Digital Discovery (RSC) | 从ESM-IF1微调的抗体特异性逆折叠模型，从结构生成CDR序列。 |

### 抗体设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgGM | A generative foundation model for antibody design | — | 2025 | doi:10.1101/2025.09.12.675771 | bioRxiv | 用于全面抗体设计的生成基础模型。 |
| DiffAb | Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models | Shitong Luo | 2022 | NeurIPS 2022 proceedings | NeurIPS 2022 | 基于扩散的抗原特异性抗体CDR-H3设计生成模型，联合建模序列、结构和取向。 |
| dyMEAN | Full-Atom Antibody Design via dyMEAN | Xiangzhe Kong | 2023 | 10.48550/arXiv.2302.00203 | ICML 2023 | 使用动态多通道等变图网络的端到端全原子抗体设计。 |
| MEAN | Conditional Antibody Design as 3D Equivariant Graph Translation | Xiangzhe Kong | 2023 | N/A | ICLR 2023 | 用于条件抗体CDR序列-结构协同设计的3D等变图神经网络。 |
| RefineGNN | Iterative Refinement Graph Neural Network for Antibody Sequence-Structure Co-design | Wengong Jin | 2022 | arXiv:2110.04624 | ICLR 2022 | 通过自回归生成进行抗体CDR序列和3D结构协同设计的迭代细化GNN。 |
| Ophiuchus-Ab | Ophiuchus-Ab: A Versatile Generative Foundation Model for Advanced Antibody-Based Immunotherapy | Yiheng Zhu | 2026 | 10.1101/2026.02.02.703197 | bioRxiv | 用于抗体免疫治疗和配对抗体库生成的扩散语言模型。 |
| NanoAbLLaMA | NanoAbLLaMA: construction of nanobody libraries with protein large language models | N/A | 2025 | 10.3389/fchem.2025.1534XXX | Frontiers in Chemistry | 基于LLaMA2微调的语言模型，用于纳米抗体(VHH)文库构建和设计。 |
| CoSiNE | CoSiNE: Conditionally Site-Independent Neural Evolution of Antibody Sequences | — | 2026 | arXiv:2602.18982 | arXiv | 条件位点独立的抗体序列神经进化模型，显式建模抗体亲和力成熟过程 |
| AbBFN2 | AbBFN2: A flexible antibody foundation model based on Bayesian Flow Networks | — | 2025 | bioRxiv:2025.04.29.651170 | bioRxiv | 基于贝叶斯流网络的灵活抗体基础模型，多目标统一建模 |
| AntibodyDesignBFN | AntibodyDesignBFN: High-Fidelity Fixed-Backbone Antibody Design via Discrete Bayesian Flow Networks | — | 2026 | arXiv:2601.05605 | arXiv | 基于离散贝叶斯流网络的高保真固定骨架抗体设计 |
| AbAffinity | AbAffinity: A Large Language Model for Predicting Antibody Binding Affinity | — | 2026 | arXiv:2603.04480 | arXiv | 预测抗体结合亲和力的大语言模型 |
| CALM | CALM: Cross-attention Adaptive Immune Receptor–Antigen Language Model | — | 2026 | bioRxiv:2026.02.25.707916 | bioRxiv | 抗体-抗原特异性预测的跨注意力自适应免疫受体语言模型 |
| JAM-2 | JAM-2: Fully computational design of drug-like antibodies | Nabla Bio | 2025 | — | Nabla Bio | 全计算设计药物级抗体，Nabla Bio开发 |
| Chai-2 | Chai-2: Zero-shot antibody discovery | Chai Discovery | 2025 | — | Chai Discovery | 零样本抗体发现模型，Chai Discovery开发 |

### TCR与免疫模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| TCR-BERT | TCR-BERT: learning the grammar of T-cell receptors for flexible antigen-binding analyses | Kevin Wu | 2024 | MLCB 2024 proceedings | PMLR v240 | 通过自监督学习在TCR序列上训练的改进BERT，捕获TCR特异性表征。 |
| tcrLM | tcrLM: a lightweight protein language model for predicting T cell receptor and epitope binding specificity | Xing Fang | 2024 | arXiv:2406.16995 | arXiv preprint | 在1亿+ TCR CDR3序列上预训练的轻量级BERT语言模型，用于TCR-表位结合预测。 |
| TCR-GPT | TCR-GPT: Integrating Autoregressive Model and Reinforcement Learning for T-Cell Receptor Repertoires Generation | N/A | 2024 | arXiv:2408.01156 | arXiv preprint | 用于TCR序列生成的解码器Transformer，结合自回归建模和强化学习。 |
| SCEPTR | Contrastive learning of T cell receptor representations | Yuta Nagano | 2024 | doi:10.1016/j.cels.2024.09.006 | arXiv preprint | 使用自对比和掩码语言预训练的轻量级类BERT TCR分析Transformer。 |
| ERGO-II | Prediction of Specific TCR-Peptide Binding From Large Dictionaries of TCR-Peptide Pairs | Ido Springer | 2020 | 10.3389/fimmu.2020.01803 | Frontiers in Immunology | 基于LSTM+自编码器的TCR-肽结合预测深度学习模型。 |
| mvTCR | Multi-modal generative modeling for joint analysis of single-cell T cell receptor and gene expression data | Felix Drost | 2024 | 10.1038/s41467-024-49806-9 | Nature Communications | 整合单细胞TCR序列和基因表达数据的多模态变分自编码器。 |
| NetTCR-2.0 | NetTCR-2.0 enables accurate prediction of TCR-peptide binding | Alessandro Montemurro | 2021 | 10.1038/s42003-021-02610-3 | Communications Biology | 使用配对TCRα和β序列的TCR-肽-MHC结合预测深度学习模型。 |
| TCR-TRANSLATE | Conditional generation of real antigen-specific T cell receptor sequences | N/A | 2025 | 10.1038/s42256-025-01096-6 | Nature Machine Intelligence | 生成抗原特异性TCR序列的机器学习框架，包括对未见表位的预测。 |

---

<a id="life-sciences-section-07"></a>
## 酶工程

### 酶工程基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| EnzyGen | Generative Enzyme Design Guided by Functionally Important Sites and Small-Molecule Substrates | Song et al. | 2024 | arXiv:2405.08205 | Preprint | 利用功能位点和底物信息的生成式酶设计模型。 |
| RFdiffusion2 | Atom-level enzyme active site scaffolding using RFdiffusion2 | — | 2025 | doi:10.1038/s41592-025-02975-x | Nature Methods | 基于RFdiffusion架构的原子级酶活性位点支架设计工具。 |
| CLEAN | Enzyme function prediction using contrastive learning | Tianhao Yu | 2023 | 10.1126/science.adf2465 | Science | 用于酶EC编号预测的对比学习模型，超越BLAST和传统方法。 |
| CLEAN-Contact | Improved enzyme functional annotation prediction using contrastive learning with structural inference | N/A (PNNL) | 2024 | 10.1038/s42003-024-07359-z | Communications Biology | CLEAN的扩展版，整合蛋白质接触图以改进酶功能注释。 |
| EnzBERT | Predicting enzymatic function of protein sequences with attention | N/A | 2023 | 10.1093/bioinformatics/btad698 | Bioinformatics | 基于BERT的模型，使用注意力机制从蛋白质序列预测酶EC编号。 |
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
## 空间转录组

### 空间转录组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Novae | Novae: a graph-based foundation model for spatial transcriptomics data | Blampey et al. | 2025 | doi:10.1038/s41592-025-02899-6 | Nature Methods | 在3000万细胞上训练的基于图的空间转录组学基础模型。 |
| SpaFoundation | SpaFoundation: a visual foundation model for spatial transcriptomics | — | 2025 | doi:10.1101/2025.08.07.669202 | bioRxiv | 使用184万张组织学图像的空间转录组学视觉基础模型。 |
| STPath | STPath: a generative foundation model for integrating spatial transcriptomics and WSIs | — | 2025 | doi:10.1038/s41746-025-02020-3 | npj Digital Medicine | 整合空间转录组学与全切片组织学图像的生成基础模型。 |
| OmiCLIP | A visual-omics foundation model to bridge histopathology with spatial transcriptomics | — | 2025 | doi:10.1038/s41592-025-02707-1 | Nature Methods | 连接组织病理学图像和空间转录组学数据的视觉-组学基础模型。 |
| SpatialFusion | SpatialFusion: A lightweight multimodal foundation model for spatial transcriptomics | — | 2026 | doi:10.64898/2026.03.16.712056 | bioRxiv | 整合基因表达、组织病理学和通路数据的轻量级多模态基础模型。 |
| SAGE-FM | SAGE-FM: A lightweight and interpretable foundation model for spatial transcriptomics | — | 2025 | arXiv:2601.15504 | Preprint | 基于GCN的轻量级可解释空间转录组学基础模型。 |
| scGPT-spatial | scGPT-spatial: Continual Pretraining of Single-Cell FM for Spatial Transcriptomics | — | 2025 | doi:10.1101/2025.02.05.636714 | bioRxiv | 通过持续预训练将scGPT扩展到空间转录组学。 |
| SpatialScope | SpatialScope: integrating spatial and single-cell transcriptomics data using deep generative models | — | 2023 | doi:10.1038/s41467-023-43629-w | Nature Communications | 用于空间转录组学与scRNA-seq数据整合的深度生成模型。 |
| stFormer | stFormer: a foundation model for spatial transcriptomics | N/A (csh3) | 2024 | 10.1101/2024.09.27.615337 | bioRxiv | 将配体-受体互作整合到空间基因表征中的Transformer基础模型。 |
| STAGE | STAGE: A Foundation Model for Spatial Transcriptomics Analysis via Graph Embeddings | N/A | 2025 | OpenReview | NeurIPS 2025 (submitted) | 使用图嵌入和层次原型的空间转录组学基础模型。 |
| STORM | STORM: A multimodal foundation model of spatial transcriptomics and histology | — | 2026 | arXiv:2604.03630 | arXiv | 空间转录组+组织学多模态基础模型，训练于120万空间分辨谱，覆盖18个器官 |
| SEAL | SEAL: Spatial Expression-Aligned Learning for pathology foundation models | — | 2026 | arXiv:2602.14177 | arXiv | 利用空间转录组数据增强病理基础模型的空间表达对齐学习框架 |
| MINT | MINT: Molecularly Informed Training with Spatial Transcriptomics Supervision for Pathology Foundation Models | — | 2026 | arXiv:2603.07895 | arXiv | 分子信息训练+空间转录组监督的病理基础模型 |
| HINGE | HINGE: Adapting Pre-trained Single-Cell Foundation Models to Spatial Gene Expression | — | 2026 | arXiv:2603.19766 | arXiv | 将预训练单细胞基础模型适配到空间基因表达谱，基于组织学图像条件生成 |
| HEIST | HEIST: A Graph Foundation Model for Spatial Transcriptomics and Proteomics Data | — | 2025 | arXiv:2506.11152 | arXiv | 空间转录组和蛋白质组学数据的图基础模型 |
| TISSUENARRATOR | TISSUENARRATOR: Generative modeling of spatial transcriptomics with LLMs | — | 2025 | arXiv | arXiv | 基于大语言模型的空间转录组生成建模 |
| SpaTranslator | SpaTranslator: Deep generative framework for universal spatial multi-omics cross-modality translation | — | 2025 | arXiv | arXiv | 通用空间多组学跨模态翻译的深度生成框架 |
| SpatialProp | SpatialProp: Tissue perturbation modeling with spatially resolved single-cell transcriptomics | — | 2025 | arXiv | arXiv | 基于空间分辨单细胞转录组的组织扰动建模 |
| SWITCH | SWITCH: Integrative deep learning of spatial multi-omics | — | 2025 | arXiv | arXiv | 空间多组学整合深度学习框架 |
| CancerSTFormer | CancerSTFormer enables multi-scale analysis of spot-resolution spatial transcriptomes | N/A | 2025 | 10.1101/2025.12.22.696102 | bioRxiv | 在50µm和250µm分辨率下的癌症多尺度空间转录组学基础模型。 |
| STAGATE | Deciphering spatial domains from spatially resolved transcriptomics with adaptive graph attention auto-encoder | Kangning Dong | 2022 | 10.1038/s41467-022-29439-6 | Nature Communications | 通过整合基因表达和空间位置进行空间域识别的图注意力自编码器。 |
| CellViT | CellViT: Vision Transformers for precise cell segmentation and classification | Fabian Hörst | 2024 | 10.1016/j.media.2024.103143 | Medical Image Analysis | 用于H&E全切片图像中精确细胞/核分割的视觉Transformer。 |
| STAMP | Interpretable spatially aware dimension reduction of spatial transcriptomics with STAMP | N/A | 2024 | 10.1038/s41592-024-02463-8 | Nature Methods | 用于空间转录组学空间感知可解释降维的深度生成模型。 |
| SpaGT | Spatially informed graph transformers for spatially resolved transcriptomics | N/A | 2025 | 10.1038/s42003-025-08015-w | Communications Biology | 整合空间坐标和基因表达的图Transformer，用于空间域识别。 |
| BrainBeacon | BrainBeacon: A Cross-Species Foundation Model for Single-cell Spatial Transcriptomics of Brain | — | 2025 | bioRxiv:2025.07.08.663729 | bioRxiv | 全球首个跨物种大脑空间转录组基础模型，整合多物种脑空间组学数据用于数字孪生大脑与靶标发现 |

---

<a id="life-sciences-section-09"></a>
## 糖链

### 糖链基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| GlycanGT | GlycanGT: A Foundation Model for Glycan Graphs with Pretrained Representation and Generative Learning | — | 2025 | bioRxiv:2025.12.14.694171 | bioRxiv | 首个糖链图基础模型，使用图transformer架构进行糖链表示和生成学习 |
| SweetBERT | Exploring BERT-based models for IUPAC glycan nomenclature | — | 2025 | OpenReview:BC4vd3oBXs | ICLR 2025 Workshop | 基于BERT的糖链序列语言模型，编码IUPAC糖链命名法及分支结构 |
| GlycanAA | Modeling All-Atom Glycan Structures via Hierarchical Message Passing and Multi-Scale Pre-training | — | 2025 | arXiv:2506.01376 | ICML 2025 | 全原子糖链建模框架，通过层次消息传递和多尺度预训练捕获糖链精细结构 |
| MCNet | Atom-level machine learning of protein-glycan interactions and cross-chiral recognition | — | 2025 | doi:10.1126/sciadv.adx6373 | Science Advances | 原子级蛋白-糖链相互作用预测模型，能预测镜像糖链识别 |
| DeepGlycanSite | Highly accurate carbohydrate-binding site prediction with DeepGlycanSite | — | 2024 | doi:10.1038/s41467-024-49516-2 | Nature Communications | 高精度碳水化合物结合位点预测深度学习模型 |
| SweetNet | Using graph convolutional neural networks to learn a representation for glycans | Daniel Bojar | 2022 | doi:10.1016/j.celrep.2022.110842 | Cell Reports | 图卷积神经网络用于糖链表示学习，处理复杂分支结构 |
| GlycoBERT | Transformer-based Deep Learning for Glycan Structure Inference from MS/MS | — | 2025 | bioRxiv:2025.07.02.662857 | bioRxiv | 基于BERT的transformer，从串联质谱数据推断糖链结构 |

---

<a id="life-sciences-section-10"></a>
## 代谢组学

### 代谢组学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MetaboLM | MetaboLM: a metabolomic language model for multi-disease early prediction and risk stratification | Qiu Shizheng | 2025 | doi:10.1038/s41467-025-66163-3 | Nature Communications | 基于Transformer的代谢组学语言模型，训练于~84,000个健康个体的血浆代谢组数据，用于多疾病早期预测 |
| DSCF | Deep spectral component filtering as a foundation model for spectral analysis demonstrated in metabolic profiling | Bingsen Xue | 2025 | doi:10.1038/s42256-025-01027-5 | Nature Machine Intelligence | 深度光谱组分过滤基础模型，自监督学习用于代谢谱分析 |

---

<a id="life-sciences-section-11"></a>
## 冷冻电镜

### 冷冻电镜基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CryoFM | CryoFM: A Flow-based Foundation Model for Cryo-EM Densities | — | 2024/2025 | arXiv:2410.08631 | NeurIPS 2024 / bioRxiv | 基于流匹配的冷冻电镜密度图基础模型，学习高质量生物分子密度图分布 |
| Cryo-IEF | A comprehensive foundation model for cryo-EM image processing | — | 2024/2025 | doi:10.1038/s41592-025-02916-8 | Nature Methods | 综合冷冻电镜图像处理基础模型，基于6500万粒子图像对比学习预训练 |
| CryoLVM | CryoLVM: Self-supervised Learning from Cryo-EM Density Maps | — | 2025/2026 | arXiv:2602.02620 | arXiv | 使用JEPA架构的自监督冷冻电镜密度图基础模型 |
| CryoNet.Refine | CryoNet.Refine: A One-step Diffusion Model for Rapid Refinement of Structural Models with Cryo-EM Density Map Restraints | — | 2026 | arXiv:2602.22263 | arXiv | 单步扩散模型，快速精修冷冻电镜结构模型 |
| CryoDRGN-AI | CryoDRGN-AI: neural ab initio reconstruction for cryo-EM | — | 2025 | doi:10.1038/s41592-025-02720-4 | Nature Methods | 神经网络从头重建异质性冷冻电镜数据 |

---

<a id="life-sciences-section-12"></a>
## 宏基因组

### 宏基因组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| METAGENE-1 | Metagenomic Foundation Model for Pandemic Monitoring | Ollie Liu | 2025 | arXiv:2501.02045 | arXiv | 70亿参数自回归Transformer，训练于>1.5万亿碱基对的宏基因组DNA/RNA，用于病原监测 |
| MGM | MGM as a large-scale pretrained foundation model for microbiome analyses in diverse contexts | Haohong Zhang | 2024/2025 | bioRxiv:2024.12.30.630825 | bioRxiv | 大规模微生物组基础模型，训练于>263,000个微生物组样本 |
| BiomeGPT | BiomeGPT: A foundation model for the human gut microbiome | — | 2026 | bioRxiv:2026.01.05.697599 | bioRxiv | 基于Transformer的人体肠道微生物组基础模型，训练于>13,300个宏基因组样本 |
| GenomeOcean | GenomeOcean: An Efficient Genome Foundation Model Trained on Large-Scale Metagenomic Assemblies | Zhihan Zhou | 2025 | bioRxiv:2025.01.30.635558 | bioRxiv | 高效基因组基础模型，训练于大规模宏基因组组装数据（40亿参数，>600Gbp） |
| MicroGenomer | MicroGenomer: A Foundation Model for Transferable Microbial Genome Representations | — | 2025 | bioRxiv:2025.12.28.696777 | bioRxiv (BGI Research) | 可迁移微生物基因组表示基础模型，训练于>234.5B碱基对，支持多尺度基因组分析 |
| Generanno | Generanno: A Genomic Foundation Model for Metagenomic Annotation | Zheng Wang | 2025 | bioRxiv:2025.06.04.656517 | bioRxiv | 宏基因组注释基因组基础模型，训练于715B原核碱基对 |
| FGBERT | FGBERT: Function-Driven Pre-trained Gene Language Model for Metagenomics | — | 2024 | arXiv:2402.16901 | arXiv | 功能驱动的宏基因组预训练基因语言模型，使用蛋白质级上下文感知分词器 |
| MetagenBERT | MetagenBERT: a Transformer Architecture using Foundational DNA Read Embedding Models for novel Metagenome Representation | Gaspar Roy | 2025 | arXiv:2601.03295 | bioRxiv | 基于Transformer的宏基因组表示框架，利用DNABERT-2/DNABERT-S直接从原始DNA读段进行疾病分类 |
| Darwin-7B | Darwin-7B: A Large Language Model for Metagenomics and Microbial Ecology | (多作者) | 2025 | — | Preprint | 70亿参数宏基因组大语言模型，在微生物基因组和宏基因组数据上训练，支持微生物物种分类和功能注释。 |
| EDEN | EDEN: 28 Billion Parameters for Programming Biology | Basecamp Research | 2026 | — | ICG-20 | 280亿参数FM，在9.7万亿核苷酸token上训练，用于生物工程 |
| ViraLM | ViraLM: virus discovery through genome foundation model | Cheng Peng | 2024 | bioRxiv:2024.01.30.577935 | Bioinformatics | 病毒基因组基础模型 |

---

<a id="life-sciences-section-13"></a>
## 系统发育

### 系统发育基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Phyla | Phyla: Towards a Foundation Model for Phylogenetic Inference | Andrew Shen | 2025 | bioRxiv:2025.01.17.633626 | bioRxiv Preprint | 首个系统发育推断基础模型，使用混合状态空间Transformer和树损失函数 |
| PhyloGPN | A Phylogenetic Approach to Genomic Language Modeling | — | 2024/2025 | arXiv:2503.03773 | arXiv | 基于系统发育树的基因组语言模型，利用多物种全基因组比对和进化模型 |

---

<a id="life-sciences-section-14"></a>
## 多组学整合

### 多组学整合基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OmniBioTE | Large-Scale Multi-omic Biosequence Transformers for Modeling Protein-Nucleic Acid Interactions | — | 2024 | arXiv:2408.16245 | PLOS ONE | 大规模多组学生物序列Transformer，训练于>250B token的蛋白质和核酸序列 |
| Omni-DNA | Omni-DNA: A Unified Genomic Foundation Model for Cross-Modal and Multi-Task Learning | Zehui Li | 2025 | arXiv:2502.03499 | NeurIPS 2025 (Microsoft) | 统一基因组基础模型，支持DNA/RNA/蛋白质跨模态多任务学习 |
| OmniNA | OmniNA: A foundation model for nucleotide sequences | — | 2024 | bioRxiv:2024.01.14.575543 | bioRxiv | 核苷酸序列基础模型，预训练于>9170万序列（>1万亿碱基），跨物种理解 |
| spEMO | Leveraging multi-modal foundation models for analysing spatial multi-omic and histopathology data | — | 2025/2026 | doi:10.1038/s41551-025-01602-6 | Nature Biomedical Engineering | 多模态基础模型框架，整合空间多组学与病理学图像数据 |
| scMamba | scMamba: A Scalable Foundation Model for Single-Cell Multi-Omics Integration Beyond Highly Variable Feature Selection | — | 2025 | arXiv:2506.20697 | arXiv | 可扩展的单细胞多组学整合基础模型，基于Mamba架构不依赖特征选择 |

---

---

<a id="life-sciences-section-15"></a>
## 表观基因组

### 表观基因组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CpGPT | CpGPT: A Foundation Model for DNA Methylation | (多作者) | 2025 | — | Preprint | DNA甲基化基础模型，预测CpG位点甲基化状态和表观遗传调控，支持衰老和疾病研究。 |
| MethylGPT | MethylGPT: A Foundation Model for the DNA Methylome | (多作者) | 2025 | — | Preprint | DNA甲基组基础模型，在大规模甲基化数据上预训练，支持表观遗传年龄预测和癌症分类。 |
| scDNAm-GPT | scDNAm-GPT: A Foundation Model for Single-Cell DNA Methylation Analysis | (多作者) | 2025 | — | Preprint | 单细胞DNA甲基化分析基础模型，用于单细胞分辨率的表观遗传异质性解析。 |

---

<a id="life-sciences-section-16"></a>
## 质谱

### 质谱基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DIA-BERT | DIA-BERT: A Foundation Model for Data-Independent Acquisition Proteomics | (多作者) | 2025 | — | Preprint | 数据非依赖采集蛋白质组学基础模型，通过Transformer架构处理DIA质谱数据，提升肽段鉴定和定量精度。 |
| DreaMS | DreaMS: Deep Representations Empowering the Annotation of Mass Spectra | (多作者) | 2024 | — | Preprint | 质谱深度表示学习基础模型，用于代谢物注释和化学结构鉴定。 |
| LSM-MS2 | LSM-MS2: Large-Scale Mass Spectrometry Foundation Model | (多作者) | 2025 | — | Preprint | 大规模串联质谱基础模型，在数百万MS2谱图上预训练，支持化合物鉴定和结构预测。 |
| OmniNovo | OmniNovo: A Universal Foundation Model for De Novo Peptide Sequencing | (多作者) | 2025 | — | Preprint | 通用的从头肽段测序基础模型，利用Transformer直接从质谱数据预测肽段序列。 |
| MS-FM | Foundation model for mass spectrometry proteomics | Justin Sanders | 2025 | arXiv:2505.10848 | arXiv | 统一质谱蛋白质组学FM，在从头测序数据上预训练 |
| InstaNovo | InstaNovo: diffusion-powered de novo peptide sequencing | InstaDeep | 2025 | doi:10.1038/s42256-025-01019-5 | Nature Machine Intelligence | 扩散模型从头肽段测序 |

---

---

<a id="life-sciences-section-17"></a>
## 神经科学

### 神经科学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| VFAM | Foundation model of neural activity predicts response to new stimulus types | — | 2025 | doi:10.1038/s41586-025-08829-y | Nature | 神经活动基础模型，在小鼠视觉皮层大规模数据上训练，可预测对新刺激类型的响应 |

---

<a id="life-sciences-section-18"></a>
## 合成生物学

### 合成生物学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DNA-Diffusion | Designing synthetic regulatory elements using DNA-Diffusion | — | 2025 | doi:10.1038/s41588-025-02441-6 | Nature Genetics | 生成式扩散模型设计合成DNA调控元件 |

---

> **总计 / Total: 376 models** — 蛋白质 Protein: 103 | RNA: 40 | DNA与基因组 Genomics: 41 | 单细胞 SingleCell: 63 | 多尺度生物学 MultiScale: 5 | 抗体与免疫 Antibody: 40 | 酶工程 Enzyme: 16 | 空间转录组 SpatialTranscriptomics: 25 | 糖链 Glycan: 7 | 代谢组学 Metabolomics: 2 | 冷冻电镜 CryoEM: 5 | 宏基因组 Metagenomics: 11 | 系统发育 Phylogenetics: 2 | 多组学整合 MultiOmics: 5 | 表观基因组 Epigenomics: 3 | 质谱 MassSpectrometry: 6 | 神经科学: 1 | 合成生物学: 1
