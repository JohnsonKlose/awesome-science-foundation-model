# 生命科学

<p align="right"><strong>Language:</strong> <a href="life-sciences_en.md">English</a> | 中文</p>

> 覆盖蛋白质、RNA、DNA与基因组、单细胞、空间转录组、抗体与免疫、冷冻电镜、宏基因组等生命科学基础模型。
> [总览](../README.zh.md)
> 说明：本页已剔除纯数据集、基准、挑战赛、库与仅有产品发布页的条目；为避免误译，少量新增条目暂沿用英文版简述。

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
| ESM-2 | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 150亿参数蛋白质语言模型，支持从单序列进行原子级结构预测（ESMFold）。 |
| ESM3 | Simulating 500 million years of evolution with a language model | Thomas Hayes | 2025 | 10.1126/science.ads0018 | Science | 多模态蛋白质生成模型，联合处理序列、结构和功能信息，模拟5亿年进化过程。 |
| ESMFold | Evolutionary-scale prediction of atomic-level protein structure with a language model | Zeming Lin | 2023 | 10.1126/science.ade2574 | Science | 基于ESM-2的单序列蛋白质结构预测方法，比AlphaFold2快约60倍。 |
| ProtTrans | ProtTrans: Toward understanding the language of life through self-supervised learning | Ahmed Elnaggar | 2021 | 10.1109/TPAMI.2021.3095381 | IEEE TPAMI | 大规模蛋白质预训练模型套件(含ProtBERT、ProtXLNet、ProtT5等)，在3930亿氨基酸上训练 |
| ProteinBERT | ProteinBERT: a universal deep-learning model of protein sequence and function | Nadav Brandes | 2022 | 10.1093/bioinformatics/btac020 | Bioinformatics | 通用蛋白质模型，在序列和GO注释上联合预训练，支持多种蛋白质属性预测。 |
| ProtGPT2 | ProtGPT2 is a deep unsupervised language model for protein design | Noelia Ferruz | 2022 | 10.1038/s41467-022-32007-7 | Nature Communications | 基于GPT-2的蛋白质序列生成模型，生成类似于天然蛋白质的新序列。 |
| ProGen | Large language models generate functional protein sequences across diverse families | Ali Madani | 2023 | 10.1038/s41587-022-01618-2 | Nature Biotechnology | Salesforce开发的大规模蛋白质语言模型，在2.8亿序列上训练，生成功能性人工蛋白质。 |
| ProGen2 | ProGen2: Exploring the boundaries of protein language models | Erik Nijkamp | 2023 | 10.1016/j.cels.2023.10.002 | Cell Systems | 64亿参数蛋白质语言模型，在基因组、宏基因组和蛋白质家族数据上训练。 |
| ProGen3 | Scaling Unlocks Broader Generation and Deeper Functional Understanding of Proteins | Aadyot Bhatnagar | 2025 | 10.1101/2025.04.15.649055 | bioRxiv | 稀疏混合专家蛋白质生成模型，在1.5万亿token上训练，用于增强蛋白质设计。 |
| SaProt | SaProt: Protein language modeling with structure-aware vocabulary | Jingjing Gong | 2024 | ICLR 2024 | ICLR 2024 (Spotlight) | 结构感知蛋白质语言模型，利用Foldseek将3D结构编码为离散token与序列联合训练 |
| xTrimoPGLM | xTrimoPGLM: Unified 100B-scale pre-trained transformer for deciphering the language of protein | Bo Chen | 2025 | 10.1038/s41592-025-02636-z | Nature Methods | 1000亿参数统一蛋白质语言模型，同时支持蛋白质理解和生成任务 |
| Ankh | Ankh: Optimized Protein Language Model Unlocks General-Purpose Modelling | Ahmed Elnaggar | 2023 | arXiv:2301.06568 | arXiv | 优化蛋白质语言模型，强调训练效率，以更少资源实现竞争力性能。 |
| ProCyon | ProCyon: A multimodal foundation model for protein phenotypes | Owen Queen | 2024 | 10.1101/2024.12.10.627665 | bioRxiv | 多模态蛋白质基础模型，整合序列、结构和自然语言数据预测蛋白质表型。 |
| ProSST | ProSST: Protein Language Modeling with Quantized Structure and Disentangled Attention | Mingchen Li | 2024 | 10.1101/2024.04.15.589672 | bioRxiv | 蛋白质语言模型，将氨基酸序列与量化3D结构信息结合。 |
| InstructPLM | InstructPLM: Aligning protein language models to follow protein design instructions | — | 2024 | arXiv:2510.03370 | arXiv | 通过指令微调ESM2，在蛋白质设计任务上超越ESM3 |
| UniRep | Unified rational protein engineering with sequence-based deep representation learning | Ethan C. Alley | 2019 | 10.1038/s41592-019-0598-1 | Nature Methods | 基于RNN的蛋白质语言模型，用于统一表示学习和理性蛋白质工程。 |
| MSA Transformer | MSA Transformer | Rao et al. | 2021 | doi:10.1101/2021.02.12.430858 | ICML 2021 | 在多序列比对上运行的Transformer模型，用于改进蛋白质建模。 |
| EVE | Disease variant prediction with deep generative models of evolutionary data | Jonathan Frazer | 2021 | 10.1038/s41586-021-04043-8 | Nature | 进化变分自编码器，从蛋白质家族数据预测致病遗传变异。 |
| Tranception | Protein fitness prediction with autoregressive transformers and inference-time retrieval | Notin et al. | 2022 | arXiv:2205.13760 | ICML 2022 | 带检索时比对上下文的自回归语言模型，用于蛋白质适应性预测。 |
| RITA | RITA: a Study on Scaling Up Generative Protein Sequence Models | Daniel Hesslow | 2022 | arXiv:2205.05789 | arXiv | 自回归蛋白质生成模型的缩放研究，最高达12亿参数。 |
| ProtSSN | Semantical and Geometrical Protein Encoding for Zero-Shot Engineering | — | 2024 | 10.7554/eLife.98033 | eLife | 结构加序列去噪预训练框架，用于零样本蛋白质工程。 |
| ProLLaMA | ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing | Liuzhenghao Lv | 2025 | 10.1109/TAI.2025.3564914 | IEEE Transactions on Artificial Intelligence | 基于LLaMA架构的多任务蛋白质大语言模型，用于多种蛋白质语言处理任务。 |
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
| GearNet | Protein Representation Learning by Geometric Structure Pretraining | Zuobai Zhang | 2023 | arXiv:2203.06125 | ICLR 2023 | 关系图神经网络，通过几何结构预训练和多视图对比学习学习蛋白质结构表示 |
| MIF | Masked inverse folding with sequence transfer for protein representation learning | Kevin Yang | 2022 | 10.1093/protein/gzad015 | Protein Engineering Design and Selection | 自监督掩码逆折叠预训练，从结构学习蛋白质表示。 |
| PPLM | A paired sequence language model for protein-protein interaction | Jun Liu | 2026 | doi:10.1038/s41467-026-70457-5 | Nature Communications | 成对序列语言模型，预测蛋白质-蛋白质相互作用 |

### 蛋白质结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaFold2 | Highly accurate protein structure prediction with AlphaFold | John Jumper | 2021 | 10.1038/s41586-021-03819-2 | Nature | 革命性蛋白质结构预测模型，在CASP14中达到原子级精度。 |
| AlphaFold3 | Accurate structure prediction of biomolecular interactions with AlphaFold 3 | Josh Abramson | 2024 | 10.1038/s41586-024-07487-w | Nature | 基于扩散的模型，预测蛋白质、核酸、小分子和离子的生物分子相互作用结构。 |
| RoseTTAFold | Accurate prediction of protein structures and interactions using a three-track neural network | Minkyung Baek | 2021 | 10.1126/science.abj8754 | Science | 三轨神经网络蛋白质结构预测模型，作为AlphaFold2的开源替代方案。 |
| RoseTTAFold2 | Efficient and accurate prediction of protein structure using RoseTTAFold2 | Minkyung Baek | 2023 | 10.1101/2023.05.24.542179 | bioRxiv | RoseTTAFold升级版，结合AlphaFold2和原始RoseTTAFold的关键特性。 |
| RoseTTAFold All-Atom | Generalized biomolecular modeling and design with RoseTTAFold All-Atom | Rohith Krishna | 2024 | 10.1126/science.adl2528 | Science | 全原子生物分子建模框架，支持蛋白质、核酸、小分子和金属离子的复合物预测。 |
| OpenFold | OpenFold: retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization | Gustaf Ahdritz | 2024 | 10.1038/s41592-024-02272-z | Nature Methods | AlphaFold2的开源可训练实现，为蛋白质折叠机制提供新见解。 |
| OmegaFold | High-resolution de novo structure prediction from primary sequence | Ruidong Wu | 2022 | 10.1101/2022.07.21.500999 | bioRxiv | 无需MSA的单序列蛋白质结构预测方法，利用预训练蛋白质语言模型。 |
| HelixFold | HelixFold: An Efficient Implementation of AlphaFold2 using PaddlePaddle | Guoxia Wang | 2022 | arXiv:2207.05477 | arXiv | 基于PaddlePaddle的高效AlphaFold2实现，减少训练时间和资源消耗。 |

### 蛋白质设计与生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProteinMPNN | Robust deep learning–based protein sequence design using ProteinMPNN | J. Dauparas | 2022 | 10.1126/science.add2187 | Science | 消息传递神经网络用于蛋白质序列设计，具有实验验证的高成功率。 |
| RFdiffusion | De novo design of protein structure and function with RFdiffusion | Joseph L. Watson | 2023 | 10.1038/s41586-023-06415-8 | Nature | 基于RoseTTAFold的扩散模型，用于从头蛋白质骨架设计。 |
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
| Protpardelle | An all-atom protein generative model | Chu et al. | 2024 | doi:10.1073/pnas.2311500121 | PNAS | 全原子蛋白质生成模型，生成包含侧链的完整蛋白质结构。 |
| Multiflow | Generative Flows on Discrete State-Spaces for Protein Co-Design | Campbell et al. | 2024 | arXiv:2402.04997 | ICML 2024 | 离散流匹配框架，用于序列-结构联合蛋白质协同设计。 |
| La-Proteina | La-Proteina: Atomistic Protein Generation via Partially Latent Flow Matching | Tomas Geffner | 2025 | arXiv:2507.09466 | arXiv | 通过部分潜在流匹配的原子级蛋白质生成方法。 |
| EvoFlows | Evolutionary Edit-Based Flow-Matching for Protein Engineering | — | 2026 | arXiv:2603.11703 | Preprint | 基于进化编辑的流匹配方法，用于定向蛋白质工程。 |
| Fold2Seq | Fold2Seq: A joint sequence(1D)-fold(3D) embedding-based generative model for protein design | — | 2021 | arXiv:2106.13058 | ICML 2021 | 联合序列-折叠嵌入的蛋白质设计生成模型，从3D结构和1D序列联合学习 |
| TERMinator | TERMinator: A neural framework for structure-based protein design using tertiary repeating motifs | — | 2022 | arXiv:2204.13048 | arXiv | 基于三级重复基序的蛋白质设计神经网络框架 |
| ProteinMCP | ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering | Xiaopeng Xu | 2026 | 10.64898/2026.03.11.711149 | bioRxiv | 集成38个专业工具的智能体AI框架（通过MCP），用于自主蛋白质工程。 |
| Latent-X | Latent-X: Atom-level frontier model for de novo protein binder design | Latent Labs | 2025 | arXiv:2507.19375 | arXiv | 原子级前沿模型，用于从头蛋白质结合物设计 |
| Latent-Y | Latent-Y: Lab-validated autonomous agent for de novo drug design | Latent Labs | 2026 | arXiv:2603.29727 | arXiv | 实验验证的自主从头药物设计智能体 |
| ProDiT | Generating functional proteins with a multimodal diffusion transformer | — | 2025 | bioRxiv:2025.09.03.672144 | bioRxiv | 多模态扩散Transformer蛋白质设计模型，在2.14亿蛋白上训练 |
| SimpleDesign | SimpleDesign: Joint Model for Protein Sequence and Structure Codesign | — | 2025 | OpenReview | ICLR 2025 | 端到端蛋白质序列-结构联合设计模型 |
| PXDesign | PXDesign: Fast De Novo Design of Protein Binders | Protenix (ByteDance) | 2025 | bioRxiv:2025.08.15.670450 | bioRxiv | 字节跳动Protenix快速蛋白质结合物从头设计 |

### 肽基础模型

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

### 蛋白质-蛋白质相互作用

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| PLM-interact | PLM-interact: extending protein language models to predict protein-protein interactions | Dan Liu | 2025 | 10.1038/s41467-025-64512-w | Nature Communications | 蛋白质语言模型的PPI预测扩展，仅从序列联合编码蛋白质对。 |
| IntFold | IntFold: A Controllable Foundation Model for General and Specialized Biomolecular Structure Prediction | The IntFold Team | 2025 | arXiv:2507.02025 | arXiv | 可控生物分子结构预测基础模型，精度匹配AlphaFold3，支持PPI复合物和变构状态。 |

### 蛋白质动力学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| ProTDyn | ProTDyn: a foundation Protein language model for Thermodynamics and Dynamics | — | 2025 | arXiv:2510.00013 | NeurIPS 2025 | 蛋白质热力学与动力学基础语言模型，统一构象集合生成和多时间尺度动力学建模 |
| SeqDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | PNAS | 结合生物物理动力学的蛋白质语言模型，训练于>64,000个蛋白质的MD模拟和简正模式分析 |
| ESMDance | Learning Biophysical Dynamics with Protein Language Models (SeqDance & ESMDance) | — | 2024/2025 | bioRxiv:2024.10.11.617911 | PNAS | ESM-2微调版本，用于蛋白质构象动力学预测 |
| MD-LLM-1 | MD-LLM-1: A Large Language Model for Molecular Dynamics | Mhd Hussein Murtada | 2025 | arXiv:2508.03709 | arXiv | 首个分子动力学LLM，微调Mistral 7B用于蛋白质构象动力学预测。 |
| VibeGen | Agentic End-to-End De Novo Protein Design for Tailored Dynamics Using a Language Diffusion Model | Bo Ni | 2025 | arXiv:2502.10173 | arXiv | 语言扩散模型框架，用于靶向特定振动动力学的端到端蛋白质设计。 |
| DynamicsPLM | Learning Protein Representations with Conformational Dynamics | Dan Kalifa | 2025 | 10.1101/2025.10.06.680789 | bioRxiv | 从计算生成的构象动力学集合中学习的蛋白质语言模型。 |
| DPLM-2 | DPLM-2: A Multimodal Diffusion Protein Language Model | Xinyou Wang | 2024/2025 | arXiv:2410.13782 | NeurIPS 2025 (ByteDance) | 多模态离散扩散蛋白质语言模型，联合建模氨基酸序列和3D结构 |
| METL | Biophysics-based protein language models for protein engineering | Sam Gelman | 2025 | 10.1038/s41592-025-02776-2 | Nature Methods | 突变效应迁移学习框架，整合生物物理建模和机器学习用于蛋白质工程。 |

---

<a id="life-sciences-section-02"></a>
## RNA

### RNA语言模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RNA-FM | Interpretable RNA foundation model from unannotated data for highly accurate RNA structure and function predictions | Jiayang Chen | 2022 | 10.1038/s41592-024-02243-4 | Nature Methods | RNA基础模型，在2300万非编码RNA序列上预训练，用于RNA结构和功能预测 |
| RiNALMo | RiNALMo: general-purpose RNA language models can generalize well on structure prediction tasks | Rafael Josip Penić | 2025 | 10.1038/s41467-025-60872-5 | Nature Communications | 6.5亿参数通用RNA语言模型，在3600万非编码RNA序列上训练，具有强结构预测泛化能力。 |
| ERNIE-RNA | ERNIE-RNA: an RNA language model with structure-enhanced representations | Weijie Yin | 2025 | 10.1038/s41467-025-64972-0 | Nature Communications | 改进的BERT架构RNA语言模型，融入碱基配对结构信息以增强表示。 |
| RNA-MSM | Multiple sequence alignment-based RNA language model and its application to structural inference | Yikun Zhang | 2024 | 10.1093/nar/gkad1031 | Nucleic Acids Research | 基于MSA的RNA语言模型，利用同源RNA的共进化信息进行结构推断。 |
| UNI-RNA | UNI-RNA: UNIVERSAL PRE-TRAINED MODELS REVOLUTIONIZE RNA RESEARCH | Xi Wang | 2023 | 10.1101/2023.07.11.548588 | bioRxiv | 通用预训练RNA模型，在最大RNA序列数据集上训练，支持多种下游任务。 |
| RNAErnie | Multi-purpose RNA language modelling with motif-aware pretraining and type-guided fine-tuning | Ning Wang | 2024 | 10.1038/s42256-024-00836-4 | Nature Machine Intelligence | 多用途RNA语言模型，结合基序感知预训练和RNA类型引导微调。 |
| AIDO.RNA | A large-scale foundation model for RNA function and structure prediction | — | 2024 | bioRxiv:2024.11.28.625345 | NeurIPS 2024 | 16亿参数RNA基础模型，在4200万非编码RNA序列上训练，单核苷酸分辨率 |
| BiRNA-BERT | BiRNA-BERT allows efficient RNA language modeling with adaptive tokenization | Md Toki Tahmid | 2025 | 10.1038/s42003-025-08982-0 | Communications Biology | 自适应分词RNA语言模型，克服序列长度和多样性限制。 |
| mRNABERT | mRNABERT: advancing mRNA sequence design with a universal language model and comprehensive dataset | Ying Xiong | 2025 | 10.1038/s41467-025-65340-8 | Nature Communications | 专为mRNA序列工程设计的语言模型，采用双分词方案。 |
| CodonBERT | CodonBERT: Large language models for mRNA design and optimization | — | 2024 | 10.1101/2023.09.09.556981 | bioRxiv | 基于密码子级分词的mRNA语言模型 |
| NucleicBERT | NucleicBERT: A large language model for RNA structure prediction | — | 2025 | 10.1101/2025.09.02.673754 | bioRxiv | RNA序列分析的Transformer语言模型，在大规模RNA数据集上预训练 |
| MP-RNA | MP-RNA: Unleashing multi-species RNA foundation model via calibrated secondary structure prediction | — | 2024 | ACL Anthology | EMNLP 2024 Findings | 多物种RNA基础模型，强调二级结构预测在RNA建模中的重要性 |
| OmniGenome | Bridging Sequence-Structure Alignment in RNA Foundation Models | Heng Yang | 2024 | arXiv:2407.11242 | arXiv | RNA基础模型，精确对齐RNA序列与二级结构，实现双向映射。 |
| structRFM | A fully-open structure-guided RNA foundation model for robust structural and functional inference | Heqin Zhu | 2025 | 10.1101/2025.08.06.668731 | bioRxiv | 完全开源的结构引导RNA基础模型，整合序列和二级结构实现鲁棒推断。 |
| SpliceBERT | SpliceBERT: a pre-trained RNA language model for analyzing vertebrate splicing | Chen et al. | 2024 | doi:10.1101/2023.01.31.526427 | Genome Biology | 专门用于脊椎动物剪接分析的预训练RNA语言模型。 |
| PlantRNA-FM | An interpretable RNA foundation model for exploring functional RNA motifs in plants | Haopeng Yu | 2024 | 10.1038/s42256-024-00946-z | Nature Machine Intelligence | 可解释的植物RNA基础模型，在1,124+植物物种上训练。 |
| AllSplice | Perturbation-aware predictive modeling of RNA splicing using bidirectional transformers | Colin P McNally | 2024 | 10.1101/2024.03.20.585793 | bioRxiv | 扰动感知双向Transformer，用于RNA剪接预测。 |
| HydraRNA | HydraRNA: a hybrid architecture based full-length RNA language model | Guipeng Li | 2025 | 10.1186/s13059-025-03853-7 | Genome Biology | 混合架构全长RNA语言模型，结合多种架构优势处理长RNA序列。 |
| EVA-RNA | EVA-RNA: A Scaling Cross-Species Transcriptomic Foundation Model for Immunology & Inflammation | — | 2026 | OpenReview:VcOvSJNgRf | OpenReview | 跨物种转录组基础模型，训练于50万+人鼠样本，专注免疫与炎症研究 |
| GRNFormer | GRNFormer: A Biologically-Guided Framework for Integrating Gene Regulatory Networks into RNA Foundation Models | Mufan Qiu | 2025 | arXiv:2503.01682 | arXiv | 生物学引导框架，将基因调控网络整合到RNA基础模型训练中。 |
| BMFM-RNA | BMFM-RNA: whole-cell expression decoding improves transcriptomic foundation models | Michael M. Danziger | 2025 | arXiv:2506.14861 | arXiv | IBM生物医学基础模型RNA模块，使用全细胞表达解码增强转录组模型。 |
| CodonFM | Codon FM: Foundation Models for Codon Sequences | NVIDIA/Arc Institute | 2025 | — | NVIDIA Research preprint | NVIDIA和Arc Institute开发的密码子基础模型，在2万+物种的1.3亿蛋白编码序列上训练。 |
| Orthrus | Orthrus: Evolutionary and Functional RNA Foundation Models | Bo Wang | 2024 | bioRxiv:2024.10.10.617658 | NeurIPS 2024 | 生物增强对比学习RNA基础模型 |

### RNA结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| RhoFold+ | Accurate RNA 3D structure prediction using a language model-based deep learning approach | Tao Shen | 2024 | 10.1038/s41592-024-02487-0 | Nature Methods | 基于预训练RNA语言模型的准确RNA 3D结构预测方法，在2370万序列上训练。 |
| RNA-FrameFlow | Flow Matching for de novo 3D RNA Backbone Design | — | 2024 | arXiv:2406.13839 | Preprint | SE(3)流匹配方法，用于从头设计3D RNA骨架结构。 |
| DRfold2 | Ab initio RNA structure prediction with composite language model and denoised end-to-end learning | Zhang et al. | 2025 | 10.1101/2025.03.05.641632 | bioRxiv | 使用复合语言模型的从头RNA 3D结构预测深度学习框架。 |
| 3DRNALM | Accurate RNA 3D structure prediction using a language model-based framework | — | 2024 | PMC11621015 | Nature Communications | 基于语言模型的准确RNA 3D结构预测框架。 |
| NuFold | NuFold: end-to-end approach for RNA tertiary structure prediction | Daisuke Kihara | 2025 | doi:10.1038/s41467-025-56261-7 | Nature Communications | 端到端RNA三级结构预测深度学习模型 |

### RNA设计与生成

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
## DNA与基因组

### DNA/基因组语言模型

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
| GROVER | DNA language model GROVER learns sequence context in the human genome | Melissa Sanabria | 2024 | 10.1038/s42256-024-00872-0 | Nature Machine Intelligence | 在人类基因组上训练的DNA语言模型，使用BPE定义DNA词汇表并捕获CpG甲基化特征。 |
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
| OmniReg-GPT | OmniReg-GPT: A Generative Pre-trained Model for Universal Gene Regulation Prediction | — | 2025 | 10.1038/s41467-025-65066-7 | Nature Communications | 跨物种和组织的通用基因调控预测生成式预训练模型。 |
| BOTANIC-0 | BOTANIC-0: a series of foundation models for plant genomic data | — | 2026 | 10.64898/2026.02.23.706817 | bioRxiv | 植物基因组基础模型家族（1亿-10亿参数），在1,600+精选植物基因组上预训练。 |
| PlantCAD2 / GeneCAD | PlantCAD2/GeneCAD: Computational Aided Design for Synthetic Plant Genomes | — | 2025 | — | Preprint | 植物基因组合成设计的计算辅助工具，利用深度学习优化合成DNA序列设计。 |
| GeneGPT | GeneGPT: Augmenting LLMs with Domain Tools for Improved Access to Biomedical Information | Qiao Jin | 2024 | doi:10.1093/bioinformatics/btae075 | Bioinformatics | 结合NCBI API工具增强的LLM，用于基因组和生物医学信息访问 |
| Species-aware DNA LM | Species-aware DNA Language Modeling | Dennis Gankin | 2023 | bioRxiv:2023.01.26.525670 | bioRxiv | 在预训练中融入物种特异性信息的DNA语言模型 |
| Genos | Genos: a human-centric genomic foundation model | — (BGI / Zhejiang Lab) | 2025 | 10.1093/gigascience/giaf132 | GigaScience | 全球首个100亿参数人类基因组基础模型，MoE-Transformer架构，支持百万碱基对上下文分析 |
| GENERator | GENERator: A Long-Context Generative Genomic Foundation Model | Wei Wu | 2025 | arXiv:2502.07272 | arXiv | 长上下文生成式基因组基础模型，在3860亿核苷酸上预训练，98k上下文长度。 |

---

<a id="life-sciences-section-04"></a>
## 单细胞

### 单细胞基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| scGPT | scGPT: toward building a foundation model for single-cell multi-omics using generative AI | Haotian Cui | 2024 | 10.1038/s41592-024-02201-0 | Nature Methods | 单细胞多组学生成式预训练Transformer，支持从3300万+细胞进行细胞注释、扰动预测和基因网络推断。 |
| scBERT | scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data | Fan Yang | 2022 | 10.1038/s42256-022-00534-z | Nature Machine Intelligence | 大规模基于BERT的预训练模型，用于scRNA-seq数据的自动细胞类型注释。 |
| Geneformer | Transfer learning enables predictions in network biology | Christina V. Theodoris | 2023 | 10.1038/s41586-023-06139-9 | Nature | 在约3000万单细胞转录组上预训练的Transformer模型，用于基因网络生物学的迁移学习。 |
| scFoundation | Large-scale foundation model on single-cell transcriptomics | Minsheng Hao | 2024 | 10.1038/s41592-024-02305-7 | Nature Methods | 1亿参数单细胞转录组基础模型(xTrimoGene)，在5000万+人类细胞上训练。 |
| UCE | Universal Cell Embeddings: A Foundation Model for Cell Biology | Yanay Rosen | 2023 | 10.1101/2023.11.28.568918 | bioRxiv | 通用细胞嵌入模型，创建跨物种和组织的统一表示空间。 |
| GeneCompass | GeneCompass: deciphering universal gene regulatory mechanisms with a knowledge-informed cross-species foundation model | Xiaodong Yang | 2024 | 10.1038/s41422-024-01034-y | Cell Research | 知识增强的跨物种基础模型，在1亿+人和小鼠细胞上训练，用于解读基因调控机制。 |
| CellPLM | CellPLM: Pre-training of Cell Language Model Beyond Single Cells | Hongzhi Wen | 2024 | OpenReview:BKXvPDekud | ICLR 2024 | 超越单细胞的细胞语言模型预训练，整合基因-基因和细胞-细胞相互作用 |
| tGPT | Generative pretraining from large-scale transcriptomes for single-cell deciphering | Hongru Shen | 2023 | 10.1016/j.isci.2023.106536 | iScience | 在2,230万单细胞转录组上的生成式预训练模型，用于细胞解读和临床转化。 |
| CellFM | CellFM: a large-scale foundation model pre-trained on transcriptomics of 100 million human cells | Yuansong Zeng | 2025 | 10.1038/s41467-025-59926-5 | Nature Communications | 8亿参数基础模型，在1亿人类细胞转录组上预训练。 |
| Nicheformer | Nicheformer: a foundation model for single-cell and spatial omics | Alejandro Tejada-Lapuerta | 2025 | 10.1038/s41592-025-02814-z | Nature Methods | 单细胞和空间组学基础模型，在SpatialCorpus-110M（1.1亿+细胞）上训练，捕获空间微环境。 |
| scMulan | scMulan: A multitask generative pre-trained language model for single-cell analysis | Haiyang Bian | 2024 | RECOMB 2024 | RECOMB 2024 | 多任务生成式预训练单细胞语言模型，将细胞编码为结构化"c-句子" |
| Cell2Sentence | Cell2Sentence: Teaching large language models the language of biology | Daniel Levine | 2024 | ICML 2024 | ICML 2024 | 将基因表达数据转化为自然语言句子，使LLM(如GPT-2)适应单细胞转录组学 |
| GET | GET: A foundation model of transcription across human cell types | Xi Fu | 2025 | 10.1038/s41586-024-08391-z | Nature | 通用表达Transformer，从染色质可及性和序列预测213种人类细胞类型基因表达 |
| GenePT | GenePT: A Simple But Effective Foundation Model for Genes and Cells Built From ChatGPT | Yiqun Chen | 2023 | 10.1101/2023.10.16.562533 | bioRxiv | 简单有效的基因/细胞基础模型，使用ChatGPT嵌入进行基因和细胞表示。 |
| LangCell | LangCell: Language-Cell Pre-training for Cell Identity Understanding | Suyuan Zhao | 2024 | arXiv:2405.06708 | arXiv | 自然语言和单细胞转录组学的联合预训练，增强细胞身份理解。 |
| CellVQ | Illuminating cell states by a comprehensive and interpretable single cell foundation model | Jue Wang | 2026 | 10.1038/s41467-026-70071-5 | Nature Communications | 全面可解释的单细胞基础模型，在6800万细胞上训练，用于揭示细胞状态。 |
| scKGBERT | scKGBERT: A knowledge-enhanced foundation model for single-cell transcriptomics | — | 2025 | — | PMC | 知识图谱增强的单细胞转录组基础模型 |
| SATURN | Toward universal cell embeddings: integrating scRNA-seq datasets across species | Rosen et al. | 2024 | doi:10.1038/s41592-024-02191-z | Nature Methods | 跨物种通用细胞嵌入框架，整合不同物种的scRNA-seq数据。 |
| scTab | scTab: Scaling cross-tissue single-cell annotation models | Felix Fischer | 2024 | 10.1038/s41467-024-51059-5 | Nature Communications | 可扩展深度学习模型，在2200万细胞上训练，用于跨组织细胞类型注释。 |
| scPRINT | scPRINT: pre-training on 50 million cells allows robust gene network predictions | Jérémie Kalfon | 2025 | 10.1038/s41467-025-58699-1 | Nature Communications | Transformer基础模型，在5000万细胞上训练，用于鲁棒基因网络推断。 |
| scPRINT-2 | scPRINT-2: Towards the next-generation of cell foundation models | Kalfon et al. | 2025 | doi:10.64898/2025.12.11.693702 | bioRxiv | 下一代细胞基础模型，训练于16个物种的3.5亿细胞。 |
| scELMo | scELMo: Embeddings from Language Models are Good Learners for Single-cell Data Analysis | Tianyu Liu | 2023 | 10.1101/2023.12.07.569910 | bioRxiv | 语言模型嵌入应用于单细胞数据分析。 |
| scVI | scVI: Variational Inference for Single-Cell Gene Expression | Lopez et al. | 2018 | doi:10.1038/s41592-018-0229-2 | Nature Methods | 为单细胞转录组分析提供概率框架的深度生成模型。 |
| scANVI | scANVI: semi-supervised integration of single-cell multi-omic data | Xu et al. | 2021 | doi:10.15252/msb.20209620 | Molecular Systems Biology | 用于整合单细胞多组学数据的半监督深度生成模型。 |
| totalVI | Joint probabilistic modeling of single-cell multi-omic data with totalVI | Adam Gayoso | 2021 | 10.1038/s41592-020-01050-x | Nature Methods | 同时进行RNA和蛋白质单细胞数据分析的联合概率模型。 |
| CellTypist | Cross-tissue immune cell analysis reveals tissue-specific features in humans | C. Domínguez Conde | 2022 | 10.1126/science.abl5197 | Science | 自动细胞类型注释工具，配备大规模跨组织免疫细胞参考图谱。 |
| scPoli | Population-level integration of single-cell datasets enables multi-scale analysis | De Donno et al. | 2023 | doi:10.1038/s41592-023-02035-2 | Nature Methods | 群体级单细胞数据集整合，实现多尺度生物学分析。 |
| scHyena | scHyena: Foundation Model for Full-Length Single-Cell RNA-Seq Analysis in Brain | Gyutaek Oh | 2023 | arXiv:2310.02713 | arXiv | 基于Hyena架构的基础模型，用于脑组织全长度scRNA-seq分析。 |
| TOSICA | TOSICA: Transfer of Omics Single-Cell Analysis | — | 2023 | 10.1038/s41467-023-44066-5 | Nature Communications | 跨数据集和模态的单细胞组学分析迁移学习框架。 |
| xTrimoGene | xTrimoGene: An Efficient and Scalable Representation Learner for Single-Cell RNA-Seq Data | — | 2023 | OpenReview:gdwcoBCMVi | NeurIPS 2023 | 使用非对称编码器-解码器架构的高效可扩展scRNA-seq表征学习器。 |
| CancerFoundation | A single-cell RNA sequencing foundation model to decipher drug resistance in cancer | — | 2024 | doi:10.1101/2024.11.01.621087 | bioRxiv | 用于解析药物耐药机制的癌症特异性scRNA-seq基础模型。 |
| Cell-GraphCompass | Cell-GraphCompass: modeling single cells with graph structure foundation model | Chen Fang | 2025 | 10.1093/nsr/nwaf255 | National Science Review | 图结构基础模型，使用基于图的细胞表示进行单细胞分析。 |
| scLong | scLong: A billion-parameter foundation model for capturing long-range gene context | — | 2026 | doi:10.1038/s41467-026-69102-y | Nature Communications | 十亿参数基础模型，同时关注所有28,000个基因以捕获长程上下文。 |
| Tahoe-x1 | Tahoe-x1: Scaling Perturbation-Trained Single-Cell Foundation Models to 3 Billion Parameters | Shreshth Gandhi | 2025 | 10.1101/2025.10.23.683759 | bioRxiv | 30亿参数扰动训练单细胞基础模型，用于预测细胞响应。 |
| PULSAR | PULSAR: a Foundation Model for Multi-scale and Multicellular Biology | Kuan Pang | 2025 | 10.1101/2025.11.24.685470 | bioRxiv | 整合3600万+细胞的多尺度基础模型，用于多细胞生物学分析。 |
| TranscriptFormer | A Cross-Species Generative Cell Atlas Across 1.5 Billion Years of Evolution | — | 2025 | doi:10.1101/2025.04.25.650731 | bioRxiv | 跨越15亿年进化的跨物种生成式细胞图谱基础模型。 |
| CELLama | CELLama: Foundation Model for Single Cell and Spatial Transcriptomics | — | 2024 | doi:10.1101/2024.05.08.593094 | bioRxiv | 利用语言模型能力的细胞嵌入模型，用于单细胞和空间转录组学。 |
| scPROTEIN | scPROTEIN: versatile deep graph contrastive learning framework for single-cell proteomics | — | 2024 | doi:10.1038/s41592-024-02214-9 | Nature Methods | 用于单细胞蛋白质组学嵌入和分析的图对比学习框架。 |
| TEDDY | TEDDY: A Family of Foundation Models for Understanding Single Cell Biology | — | 2025 | arXiv:2503.03485 | ICML Workshop | 面向全面单细胞生物学理解的基础模型家族。 |
| Tabula | Tabula: A Tabular Self-Supervised Foundation Model for Single-Cell Transcriptomics | — | 2025 | NeurIPS 2025 Poster #117659 | NeurIPS 2025 | 面向单细胞转录组学数据的表格自监督基础模型。 |
| ChromFound | ChromFound: Towards A Universal Foundation Model for Single-Cell Chromatin Accessibility Data | — | 2025 | arXiv:2505.12638 | NeurIPS 2025 | 用于单细胞染色质可及性(scATAC-seq)数据分析的通用基础模型。 |
| EpiFoundation | EpiFoundation: A Foundation Model for Single-Cell ATAC-seq via Peak-to-Gene Alignment | Juncheng Wu | 2025 | 10.1101/2025.02.05.636688 | bioRxiv | 使用peak-to-gene对齐的scATAC-seq基础模型，用于表观基因组分析。 |
| SCARF | SCARF: Single Cell ATAC-seq and RNA-seq Foundation model | Guole Liu | 2025 | 10.1101/2025.04.07.647689 | bioRxiv | 联合建模scATAC-seq和scRNA-seq数据的多模态基础模型。 |
| CAPTAIN | CAPTAIN: A multimodal foundation model pretrained on co-assayed single-cell RNA and protein | Boya Ji | 2025 | 10.1101/2025.07.07.663366 | bioRxiv | 用于共检测scRNA和蛋白质数据整合的多模态基础模型。 |
| OKR-Cell | OKR-Cell: Open World Knowledge Aided Single-Cell Foundation Model with Robust Cross-Modal Cell-Language Pre-training | — | 2026 | arXiv:2601.05648 | arXiv | 开放世界知识增强的单细胞基础模型，跨模态预训练 |
| GeneJepa | GeneJepa: A Predictive World Model of the Transcriptome | Elon Litman | 2025 | 10.1101/2025.10.14.682378 | bioRxiv | 基于JEPA架构的转录组学预测世界模型。 |
| VCWorld | VCWorld: Biological world model for virtual cell simulation | — | 2025 | 10.48550/arXiv.2512.00306 | arXiv | 虚拟细胞模拟的生物世界模型 |
| CellForge | CellForge: Agentic Design of Virtual Cell Models | Xiangru Tang | 2025 | arXiv:2508.02276 | arXiv | 用于自动化虚拟细胞模型设计的智能体AI框架。 |
| CellHermes | Language may be all omics needs: Harmonizing multimodal data for omics understanding with CellHermes | — | 2025 | 10.1101/2025.11.07.687322 | bioRxiv | 多模态数据协调的组学理解模型 |
| CellTok | CellTok: Early-Fusion Multimodal Large Language Model for Single-Cell Transcriptomics via Tokenization | — | 2025 | 10.1101/2025.10.22.684047 | bioRxiv | 基于token化的早期融合多模态单细胞转录组LLM |
| sciLaMA | sciLaMA: A Single-Cell Representation Learning Framework to Leverage Prior Knowledge from Large Language Models | — | 2025 | PMLR v267 | ICML 2025 | 利用LLM先验知识的单细胞表示学习 |
| CASSIA | CASSIA: a multi-agent large language model for automated and interpretable cell annotation | — | 2025 | 10.1038/s41467-025-67084-x | Nature Communications | 多智能体LLM用于自动化可解释细胞标注 |
| scConcept | scConcept: Contrastive pretraining for technology-agnostic single-cell representations beyond reconstruction | — | 2025 | 10.1101/2025.10.14.682419 | bioRxiv | 对比预训练的技术无关单细胞表示学习 |
| scLinguist | scLinguist: A pre-trained hyena-based foundation model for cross-modality translation in single-cell multi-omics | — | 2025 | 10.1101/2025.09.30.679123 | bioRxiv | 基于Hyena的单细胞多组学跨模态翻译基础模型 |
| scNET | scNET: learning context-specific gene and cell embeddings by integrating single-cell gene expression data with protein–protein interactions | — | 2025 | 10.1038/s41592-025-02627-0 | Nature Methods | 整合scRNA和PPI的上下文特异性基因和细胞嵌入 |
| HEIMDALL | Heimdall: A Modular Framework for Tokenization in Single-Cell Foundation Models | — | 2025 | PMCID:PMC12642435 | PMC / bioRxiv | 单细胞基础模型中token化的模块化框架 |
| PertAdapt | PertAdapt: Unlocking Single-Cell Foundation Models for Genetic Perturbation Prediction via Condition-Sensitive Adaptation | — | 2025 | 10.1101/2025.11.21.689655 | bioRxiv | 解锁单细胞基础模型用于遗传扰动预测 |
| scPEFT | Harnessing the power of single-cell large language models with parameter-efficient fine-tuning using scPEFT | — | 2025 | 10.1038/s42256-025-01170-z | Nature Machine Intelligence | 单细胞大语言模型的参数高效微调方法 |
| scLAMBDA | Modeling and predicting single-cell multi-gene perturbation responses with scLAMBDA | — | 2024 | PMID:39677694 | PubMed (bioRxiv) | 单细胞多基因扰动响应建模 |
| GeneMamba | GeneMamba: An Efficient and Effective Foundation Model on Single Cell Data | Cong Qi | 2025 | arXiv:2504.16956 | arXiv | 基于Mamba架构的高效单细胞基础模型，具有可扩展计算能力。 |
| Atacformer | Atacformer: A transformer-based foundation model for analysis and interpretation of ATAC-seq data | — | 2025 | PMID:41279458 | PubMed (bioRxiv) | 基于Transformer的ATAC-seq数据分析基础模型，用于表观基因组学 |
| CLM-X | CLM-X: A multimodal single-cell foundation model with flexible multi-way Transformer for unified scRNA-seq and scATAC-seq analysis | — | 2026 | ScienceCast | ScienceCast | 跨模态单细胞语言模型，整合多组学数据实现统一的细胞表示学习。 |
| CellOracle | CellOracle: Dissecting cell identity via network inference and in silico gene perturbation | Kenji Kamimoto | 2023 | doi:10.1038/s41586-022-05688-9 | Nature | 基于基因调控网络的计算框架，模拟基因扰动对细胞身份的影响 |
| Stack | Stack: In-Context Learning of Single-Cell Biology | Mingze Dong | 2026 | 10.64898/2026.01.09.698608 | bioRxiv | Arc Institute单细胞基础模型，在1.49亿人类细胞上训练，支持通过上下文学习进行零样本预测。 |
| Lingshu-Cell | Lingshu-Cell: cellular world model for transcriptome modeling | Alibaba DAMO | 2026 | arXiv:2603.25240 | arXiv | 灵枢-细胞：掩码离散扩散细胞世界模型 |

### 虚拟细胞模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| AlphaCell | Towards building a World Model to simulate perturbation-induced cellular dynamics | — | 2026 | bioRxiv:2026.03.02.709176 | bioRxiv | 虚拟细胞世界模型，模拟细胞扰动响应动力学 |
| CellFluxV2 | CellFluxV2 : An Image Generative Foundation Model for Virtual Cell Modeling | Yuhui Zhang | 2026 | 10.64898/2026.01.19.696785 | bioRxiv | 基于流匹配的虚拟细胞图像建学生成基础模型。 |
| X-Cell | X-Cell: Scaling Causal Perturbation Prediction Across Diverse Cellular Contexts | Xaira Therapeutics | 2026 | bioRxiv:2026.03.18.712807 | bioRxiv | 大规模扩散语言模型，预测跨细胞环境的基因组级转录响应 |

---

<a id="life-sciences-section-05"></a>
## 多尺度生物学

### 多尺度生物基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Xpressor | Towards foundation models that learn across biological scales | Jeremie Kalfon | 2025 | bioRxiv:2025.05.16.653447 | ICML 2025 | 跨尺度学习框架，通过交叉注意力机制整合分子、细胞和组织层面的基因表达信息 |
| AIDO | Toward AI-Driven Digital Organism: Multiscale Foundation Models for Predicting, Simulating and Programming Biology at All Levels | Le Song | 2024 | arXiv:2412.06993 | arXiv | AI驱动的数字生物系统，整合DNA→RNA→蛋白质→细胞多尺度基础模型。 |
| AIDO.Protein | Mixture of experts enable efficient and effective protein understanding and design | — | 2024 | bioRxiv:2024.11.29 | NeurIPS 2024 Workshop | AIDO体系中的蛋白质模块，160亿参数MoE架构，在1.2万亿氨基酸上训练 |
| AIDO.ModelGenerator | Rapid and Reproducible Multimodal Biological Foundation Model Development with AIDO.ModelGenerator | Caleb N. Ellington | 2025 | 10.1101/2025.06.30.662437 | bioRxiv | 加速跨尺度多模态生物基础模型开发的开源工具包。 |
| SToFM | SToFM: A multi-scale foundation model for spatial transcriptomics | — | 2025 | — | ICML 2025 | 空间转录组多尺度基础模型，整合宏观组织形态和微观细胞环境 |
| OmniCell | OmniCell: Unified Foundation Modeling of Single-Cell and Spatial Transcriptomics | — | 2025 | doi:10.64898/2025.12.29.696804 | bioRxiv | 同时用于单细胞和空间转录组学分析的统一基础模型。 |

---

<a id="life-sciences-section-06"></a>
## 抗体与免疫

### 抗体语言模型

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
| FAbCon | A generative foundation model for antibody sequence understanding | Justin Barton | 2024 | bioRxiv:2024.05.22.594943 | NeurIPS 2025 | 24亿参数抗体生成基础模型 |
| S2ALM | S2ALM: Sequence-Structure Pre-trained Large Language Model for Comprehensive Antibody Representation Learning | Mingze Yin | 2025 | 10.34133/research.0721 | Research | 序列-结构联合预训练的抗体大语言模型，用于全面抗体表征学习。 |

### 抗体结构预测

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| IgFold | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Jeffrey A. Ruffolo | 2023 | 10.1038/s41467-023-38063-x | Nature Communications | 快速抗体结构预测，使用在5.58亿序列上预训练的语言模型和图神经网络。 |
| DeepAb | Antibody structure prediction using interpretable deep learning | Jeffrey A. Ruffolo | 2022 | 10.1016/j.patter.2021.100406 | Patterns (Cell Press) | 可解释深度学习抗体Fv结构预测模型，专注于CDR环建模。 |
| ABlooper | ABlooper: fast accurate antibody CDR loop structure prediction with accuracy estimation | Brennan Abanades | 2022 | 10.1093/bioinformatics/btac016 | Bioinformatics | 快速等变神经网络，用于带精度估计的抗体CDR环结构预测。 |
| AntiFold | AntiFold: Improved structure-based antibody design using inverse folding | Magnus Haraldson Høie | 2025 | 10.1093/bioadv/vbae202 | Bioinformatics Advances | 从ESM-IF1微调的抗体特异性逆折叠模型，从结构生成CDR序列。 |

### 抗体设计与生成

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
| CALM | Contrastive learning for antibody-antigen sequence-to-specificity prediction | — | 2026 | 10.64898/2026.02.25.707916 | bioRxiv | CALM是对比抗体-抗原序列模型，用于双向特异性预测。 |

### TCR与免疫模型

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
## 酶工程

### 酶工程基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| EnzyGen | Generative Enzyme Design Guided by Functionally Important Sites and Small-Molecule Substrates | Zhenqiao Song | 2024 | arXiv:2405.08205 | arXiv | 利用功能位点和底物信息的生成酶设计模型。 |
| RFdiffusion2 | Atom-level enzyme active site scaffolding using RFdiffusion2 | Woody Ahern | 2026 | 10.1038/s41592-025-02975-x | Nature Methods | 基于RFdiffusion架构的原子级酶活性位点支架工具。 |
| CLEAN | Enzyme function prediction using contrastive learning | Tianhao Yu | 2023 | 10.1126/science.adf2465 | Science | 酶EC编号预测的对比学习模型，性能超越BLAST和传统方法。 |
| CLEAN-Contact | Improved enzyme functional annotation prediction using contrastive learning with structural inference | Yuxin Yang | 2024 | 10.1038/s42003-024-07359-z | Communications Biology | CLEAN扩展版，整合蛋白质接触图改善酶功能注释。 |
| EnzBERT | Predicting enzymatic function of protein sequences with attention | Nicolas Buton | 2023 | 10.1093/bioinformatics/btad620 | Bioinformatics | 基于BERT的模型，使用注意力机制从蛋白质序列预测酶EC编号。 |
| EnzymeFlow | EnzymeFlow: Generating Reaction-specific Enzyme Catalytic Pockets through Flow Matching and Co-Evolutionary Dynamics | Chao Song | 2024 | arXiv:2410.00327 | NeurIPS 2024 | 使用流匹配设计反应特异性酶催化口袋的生成模型。 |
| EnzymeCAGE | EnzymeCAGE: A Geometric Foundation Model for Enzyme Retrieval with Evolutionary Insights | Yong Liu | 2024 | 10.1101/2024.12.15.628585 | bioRxiv | 几何基础模型，在约100万酶-反应对上训练，用于酶检索和功能预测。 |
| CatPred | CatPred: a comprehensive framework for deep learning in vitro enzyme kinetic parameters | Veda Sheersh Boorla | 2025 | 10.1038/s41467-025-57215-9 | Nature Communications | 深度学习框架，从序列预测酶动力学参数（kcat、Km、Ki）。 |
| UniKP | UniKP: a unified framework for the prediction of enzyme kinetic parameters | Han Yu | 2023 | 10.1038/s41467-023-44113-1 | Nature Communications | 使用预训练蛋白质语言模型的统一深度学习框架，预测kcat、Km和催化效率。 |
| TurNuP | Turnover number predictions for kinetically uncharacterized enzymes using machine and deep learning | Alexander Kroll | 2023 | 10.1038/s41467-023-39840-4 | Nature Communications | 深度学习模型，预测未表征酶的周转数（kcat）。 |
| EnzyControl | EnzyControl: Adding Functional and Substrate-Specific Control for Enzyme Backbone Generation | Chao Song | 2025 | arXiv:2510.25132 | arXiv | 底物特异性酶骨架生成框架，具有功能控制能力。 |
| ProtDETR | Interpretable Enzyme Function Prediction via Residue-Level Detection | Zhao Yang | 2025 | arXiv:2501.05644 | arXiv | 受目标检测启发的基于注意力的残基级酶EC编号预测框架。 |
| EZpred | EZpred: improving deep learning-based enzyme function prediction using unlabeled sequence homologs | N/A | 2025 | PMC12338500 | Bioinformatics | 利用未标记同源序列改进酶EC预测的深度学习框架。 |
| BEC-Pred | A general model for predicting enzyme functions based on enzymatic reactions | Wenjia Qian | 2024 | 10.1186/s13321-024-00827-y | Journal of Cheminformatics | 基于BERT的模型，从底物和产物的SMILES表示预测酶EC编号。 |
| HIT-EC | HIT-EC: Trustworthy prediction of enzyme commission numbers using a hierarchical interpretable transformer | — | 2026 | doi:10.1038/s41467-026-68727-3 | Nature Communications | 层次可解释Transformer预测酶EC编号，可信赖的酶功能预测 |
| ENZYME-UNIFIED | ENZYME-UNIFIED: Learning Holistic Representations of Enzyme Function with a Hybrid Interaction Model | — | 2025 | OpenReview:oTnFATrtCD | OpenReview | 酶功能全面表示学习基础模型，混合交互模型 |

---

<a id="life-sciences-section-08"></a>
## 空间转录组

### 空间转录组基础模型

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
| stFormer | stFormer: a foundation model for spatial transcriptomics | Shenghao Cao | 2024 | 10.1101/2024.09.27.615337 | bioRxiv | 将配体-受体相互作用整合到空间基因表示中的Transformer基础模型。 |
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
| CancerSTFormer | CancerSTFormer enables multi-scale analysis of spot-resolution spatial transcriptomes and dissects the gene and immune regulatory responses of targeted therapies | N/A | 2025 | 10.1101/2025.12.22.696102 | bioRxiv | 癌症多尺度空间转录组基础模型，支持50µm和250µm分辨率。 |
| STAGATE | Deciphering spatial domains from spatially resolved transcriptomics with adaptive graph attention auto-encoder | Kangning Dong | 2022 | 10.1038/s41467-022-29439-6 | Nature Communications | 通过整合基因表达和空间位置进行空间域识别的图注意力自编码器。 |
| CellViT | CellViT: Vision Transformers for precise cell segmentation and classification | Fabian Hörst | 2024 | 10.1016/j.media.2024.103143 | Medical Image Analysis | Vision Transformer，用于H&E全切片图像中精确的细胞/细胞核分割。 |
| STAMP | Interpretable spatially aware dimension reduction of spatial transcriptomics with STAMP | Chengwei Zhong | 2024 | 10.1038/s41592-024-02463-8 | Nature Methods | 深度生成模型，用于空间转录组的空间感知可解释降维。 |
| SpaGT | Spatially informed graph transformers for spatially resolved transcriptomics | Xinyu Bao | 2025 | 10.1038/s42003-025-08015-w | Communications Biology | 图Transformer，整合空间坐标和基因表达用于空间域识别。 |
| BrainBeacon | BrainBeacon: A Cross-Species Foundation Model for Single-cell Spatial Transcriptomics of Brain | — | 2025 | bioRxiv:2025.07.08.663729 | bioRxiv | 全球首个跨物种大脑空间转录组基础模型，整合多物种脑空间组学数据用于数字孪生大脑与靶标发现 |

---

<a id="life-sciences-section-09"></a>
## 糖链

### 糖链基础模型

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
## 代谢组学

### 代谢组学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MetaboLM | MetaboLM: a metabolomic language model for multi-disease early prediction and risk stratification | Shizheng Qiu | 2025 | 10.1038/s41467-025-66163-3 | Nature Communications | 基于Transformer的代谢组学语言模型，在~84,000健康血浆代谢组上训练，用于多疾病早期预测。 |
| DSCF | Deep spectral component filtering as a foundation model for spectral analysis demonstrated in metabolic profiling | Bingsen Xue | 2025 | 10.1038/s42256-025-01027-5 | Nature Machine Intelligence | 自监督深度光谱成分过滤基础模型，用于代谢谱分析。 |

---

<a id="life-sciences-section-11"></a>
## 冷冻电镜

### 冷冻电镜基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CryoFM | CryoFM: A Flow-based Foundation Model for Cryo-EM Densities | Yi Zhou | 2024 | arXiv:2410.08631 | arXiv | 基于流匹配的基础模型，学习高质量生物分子密度图分布。 |
| Cryo-IEF | A comprehensive foundation model for cryo-EM image processing | Yang Yan | 2026 | 10.1038/s41592-025-02916-8 | Nature Methods | 综合冷冻电镜图像处理基础模型，通过对比学习在6500万粒子图像上预训练。 |
| CryoLVM | CryoLVM: Self-supervised Learning from Cryo-EM Density Maps | — | 2025/2026 | arXiv:2602.02620 | arXiv | 使用JEPA架构的自监督冷冻电镜密度图基础模型 |
| CryoNet.Refine | CryoNet.Refine: A One-step Diffusion Model for Rapid Refinement of Structural Models with Cryo-EM Density Map Restraints | Fuyao Huang | 2026 | arXiv:2602.22263 | arXiv | 单步扩散模型，使用冷冻电镜密度图约束快速精修结构模型。 |
| CryoDRGN-AI | CryoDRGN-AI: neural ab initio reconstruction for cryo-EM | — | 2025 | doi:10.1038/s41592-025-02720-4 | Nature Methods | 神经网络从头重建异质性冷冻电镜数据 |

---

<a id="life-sciences-section-12"></a>
## 宏基因组

### 宏基因组基础模型

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
| ViraLM | ViraLM: virus discovery through genome foundation model | Cheng Peng | 2024 | bioRxiv:2024.01.30.577935 | Bioinformatics | 病毒基因组基础模型 |

---

<a id="life-sciences-section-13"></a>
## 系统发育

### 系统发育基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Phyla | Phyla: Towards a Foundation Model for Phylogenetic Inference | Andrew Shen | 2025 | bioRxiv:2025.01.17.633626 | ICLR 2025 | 首个系统发育推断基础模型，使用混合状态空间Transformer和树损失函数 |
| PhyloGPN | A Phylogenetic Approach to Genomic Language Modeling | Carlos Albors | 2025 | arXiv:2503.03773 | arXiv | 基于系统发育树的基因组语言模型，使用多物种全基因组比对和进化模型。 |

---

<a id="life-sciences-section-14"></a>
## 多组学整合

### 多组学整合基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| OmniBioTE | 大规模多组学生物序列Transformer用于建模蛋白质-核酸相互作用 | — | 2024 | arXiv:2408.16245 | PLOS ONE | 大规模多组学生物序列Transformer，训练于>250B token的蛋白质和核酸序列 |
| Omni-DNA | Omni-DNA: A Unified Genomic Foundation Model for Cross-Modal and Multi-Task Learning | Zehui Li | 2025 | arXiv:2502.03499 | NeurIPS 2025 (Microsoft) | 统一基因组基础模型，支持DNA/RNA/蛋白质跨模态多任务学习 |
| OmniNA | OmniNA: A foundation model for nucleotide sequences | Xilin Shen | 2024 | 10.1101/2024.01.14.575543 | bioRxiv | 核苷酸序列基础模型，在>9170万序列（>1万亿碱基）上预训练，用于跨物种理解。 |
| spEMO | Leveraging multi-modal foundation models for analysing spatial multi-omic and histopathology data | Tianyu Liu | 2026 | 10.1038/s41551-025-01602-6 | Nature Biomedical Engineering | 多模态基础模型框架，整合空间多组学与组织病理学图像数据。 |
| scMamba | scMamba: A Scalable Foundation Model for Single-Cell Multi-Omics Integration Beyond Highly Variable Feature Selection | Zhen Yuan | 2025 | arXiv:2506.20697 | arXiv | 可扩展的基于Mamba的基础模型，无需特征选择即可整合单细胞多组学。 |

---

---

<a id="life-sciences-section-15"></a>
## 表观基因组

### 表观基因组基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| CpGPT | CpGPT: a Foundation Model for DNA Methylation | Lucas Paulo de Lima Camillo | 2024 | 10.1101/2024.10.24.619766 | bioRxiv | DNA甲基化基础模型，预测CpG位点甲基化状态，用于衰老和疾病研究。 |
| MethylGPT | MethylGPT: a foundation model for the DNA methylome | Kejun Ying | 2024 | 10.1101/2024.10.30.621013 | bioRxiv | DNA甲基组基础模型，在大规模甲基化数据上预训练，用于表观遗传年龄预测和癌症分类。 |
| scDNAm-GPT | scDNAm-GPT: a foundation model for single-cell DNA methylation analysis | (多作者) | 2025 | 10.1101/2025.02.19.638959 | bioRxiv | 单细胞DNA甲基化分析基础模型，以单细胞分辨率解析表观遗传异质性。 |

---

<a id="life-sciences-section-16"></a>
## 质谱

### 质谱基础模型

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
## 神经科学

### 神经科学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| VFAM | Foundation model of neural activity predicts response to new stimulus types | Eric Y. Wang | 2025 | 10.1038/s41586-025-08829-y | Nature | 神经活动基础模型，在大规模小鼠视觉皮层数据上训练，预测对新刺激类型的响应。 |

---

<a id="life-sciences-section-18"></a>
## 合成生物学

### 合成生物学基础模型

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| DNA-Diffusion | Designing synthetic regulatory elements using DNA-Diffusion | — | 2025 | doi:10.1038/s41588-025-02441-6 | Nature Genetics | 生成式扩散模型设计合成DNA调控元件 |

---
