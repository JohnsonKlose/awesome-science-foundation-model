# 化学

<p align="right"><strong>Language:</strong> <a href="chemistry_en.md">English</a> | 中文</p>

> 覆盖分子表示、分子生成、反应预测、逆合成、化学语言模型、光谱分析等化学基础模型。
> [总览](../README.zh.md)

## 目录
- [小分子](#chemistry-section-01)
- [化学反应与逆合成](#chemistry-section-02)
- [蛋白质配体](#chemistry-section-03)
- [3D等变分子表示](#chemistry-section-04)
- [分子生成](#chemistry-section-05)
- [光谱与分析化学](#chemistry-section-06)
- [食品科学](#chemistry-section-07)
- [电化学](#chemistry-section-08)

# 化学_Chemistry - Scientific Foundation Models 综合目录

> 更新日期：2026-04-09 | 总计：94 个模型

<a id="chemistry-section-01"></a>
## 小分子

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MoLFormer | Large-Scale Chemical Language Representations Capture Molecular Structure and Properties | Jerret Ross | 2022 | doi:10.1038/s42256-022-00580-7 | Nature Machine Intelligence | 基于Transformer的大规模化学语言模型，在11亿SMILES上预训练，使用线性注意力和旋转位置编码学习分子表示，用于属性预测。 |
| GP-MoLFormer | GP-MoLFormer: A Foundation Model For Molecular Generation | Jerret Ross | 2024 | arXiv:2405.04912 | Digital Discovery (RSC) | 基于Transformer的大规模分子生成基础模型，在11亿SMILES上训练的4680万参数decoder模型，用于分子生成任务。 |
| ChemBERTa | ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction | Seyone Chithrananda | 2020 | arXiv:2010.09885 | NeurIPS ML4Molecules Workshop | 基于RoBERTa架构的化学语言模型，在1000万PubChem SMILES上预训练，用于分子属性预测。 |
| ChemBERTa-2 | ChemBERTa-2: Towards Chemical Foundation Models | Walid Ahmad | 2022 | arXiv:2209.01712 | arXiv preprint | ChemBERTa的进化版本，在7700万PubChem SMILES上训练，优化了预训练方法（含多任务回归），探索化学基础模型方向。 |
| ChemBERTa-3 | ChemBERTa-3: An Open Source Training Framework for Chemical Foundation Models | - | 2026 | doi:10.1016/j.ailsci.2026.100112 | Artificial Intelligence in the Life Sciences | 开源化学基础模型训练框架，扩展了ChemBERTa系列方法。 |
| ChemFM | ChemFM as a Scaling Law Guided Foundation Model Pre-trained on Informative Chemicals | - | 2024 | arXiv:2410.21422 | Communications Chemistry | 30亿参数化学基础模型，在UniChem的1.78亿分子上使用自监督因果语言建模训练，遵循缩放定律指导。 |
| ChemDFM | Developing ChemDFM as a Large Language Foundation Model for Chemistry | - | 2024 | arXiv:2401.14818 | NeurIPS 2024 | 基于LLaMa-13B的化学领域大语言模型，在340亿token化学文献上训练，270万指令对微调。 |
| Uni-Mol | Uni-Mol: A Universal 3D Molecular Representation Learning Framework | Gengmo Zhou | 2022 | arXiv:2204.07599 | ICLR 2023 | 通用3D分子表示学习框架，直接利用分子三维结构信息进行预训练，在分子属性预测等任务达到SOTA。 |
| Uni-Mol2 | Uni-Mol2: Exploring Molecular Pretraining Model at Scale | Xiaohong Ji | 2024 | arXiv:2406.14969 | NeurIPS 2024 | 最大3D分子基础模型（11亿参数），双轨Transformer架构整合原子、图和3D几何特征，在8.84亿分子上训练。 |
| MolBERT | MolBERT: Molecular Representation Learning with Language Models and Domain-Relevant Auxiliary Tasks | Fabian Simm | 2020 | arXiv:2011.13230 | arXiv preprint | 基于BERT的分子表示学习模型（BenevolentAI），使用SMILES表示并结合自监督任务生成有意义的分子嵌入。 |
| GROVER | Self-Supervised Graph Transformer on Large-Scale Molecular Data | Yu Rong | 2020 | arXiv:2007.02835 | NeurIPS 2020 | 自监督图Transformer模型，在大规模分子数据上预训练（Tencent AI Lab），融合GNN消息传递与Transformer注意力。 |
| GEM | Geometry-Enhanced Molecular Representation Learning for Property Prediction | Xiaomin Fang | 2022 | doi:10.1038/s42256-021-00438-4 | Nature Machine Intelligence | 几何增强分子表示学习框架（百度PaddleHelix），利用分子三维空间结构信息改进属性预测。 |
| Graphormer | Do Transformers Really Perform Bad for Graph Representation? | Chengxuan Ying | 2021 | arXiv:2106.05234 | NeurIPS 2021 | 微软的图Transformer框架，在OGB-LSC分子任务中获得第一名，引入空间编码和边编码用于图结构建模。 |
| MoleculeSTM | Multi-modal Molecule Structure-text Model for Text-based Retrieval and Editing | Shengchao Liu | 2023 | doi:10.1038/s42256-023-00759-6 | Nature Machine Intelligence | 多模态分子结构-文本模型，联合学习分子结构与文本描述，支持文本驱动的分子检索和编辑。 |
| 3D-MoLM | Towards 3D Molecule-Text Interpretation in Language Models | Sihang Li | 2024 | arXiv:2401.13923 | ICLR 2024 | 将3D分子编码器与语言模型集成的开创性框架，通过3D分子-文本投影器实现LLM的3D分子理解能力。 |
| MolE | MolE: A Foundation Model for Molecular Graphs Using Disentangled Attention | Pablo Méndez-Lucio | 2024 | doi:10.1038/s41467-024-53751-y | Nature Communications | Recursion公司的分子图基础模型，采用解耦注意力的Transformer架构，在约8.42亿分子上两步自监督预训练。 |
| MiniMol | MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning | Kerstin Kläser | 2024 | arXiv:2404.14986 | ICML 2024 | 参数高效的分子学习基础模型（仅1000万参数），在600万分子的3300+多样化生物活性数据上预训练。 |
| SMILES-Mamba | SMILES-Mamba: Chemical Mamba Foundation Models for Drug ADMET Prediction | - | 2024 | arXiv:2408.05696 | NeurIPS 2024 Workshop | 基于Mamba架构的化学基础模型，两阶段训练（自监督预训练+监督微调）用于药物ADMET预测。 |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | - | 2024 | OpenReview | ICLR 2024 Workshop | IBM开发的大规模SMILES编码器-解码器基础模型，在PubChem 9100万SMILES上自监督训练，用于化学和材料科学。 |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | - | 2023 | doi:10.1038/s41467-023-43214-1 | Nature Communications | 知识引导的图Transformer预训练框架，整合化学知识增强分子表示学习。 |
| GIN (Pretrained) | Strategies for Pre-Training Graph Neural Networks | Weihua Hu | 2020 | arXiv:1905.12265 | ICLR 2020 | 提出GNN预训练策略（节点级+图级），在200万分子上预训练GIN模型用于分子属性预测，开创性工作。 |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | - | 2025 | arXiv:2510.18900 | arXiv preprint | 大规模分子基础模型家族（Molecular Insight SMILES Transformers），在大量无标注分子上训练，可预测400+结构-性质关系。 |
| M2UMol | Multi-to-Uni Modal Knowledge Transfer Pre-training for Molecular Representation Learning | - | 2026 | doi:10.1038/s41467-026-69302-6 | Nature Communications | 多模态到单模态知识迁移预训练框架，将多种分子模态知识有效转移到2D编码器中。 |
| Chemprop (D-MPNN) | Analyzing Learned Molecular Representations for Property Prediction | Kevin Yang | 2019 | doi:10.1021/acs.jcim.9b00237 | J. Chem. Inf. Model. | Directed message passing neural network for molecular property prediction |
| Omni-Mol | Exploring Universal Convergent Space for Omni-Molecular Tasks | Chengxin Hu | 2025 | arXiv:2502.01074 | NeurIPS 2025 | Unified language model for any-to-any modality molecular tasks |
| ADMET-AI | ADMET-AI: A Machine Learning ADMET Platform | Kyle Swanson | 2024 | doi:10.1093/bioinformatics/btae416 | Bioinformatics | ML platform for ADMET property prediction of large chemical libraries |
| TamGen | TamGen: Drug Design with Target-Aware Molecule Generation through a Chemical Language Model | Microsoft/GHDDI | 2024 | doi:10.1038/s41467-024-53632-4 | Nature Communications | GPT风格化学语言模型，用于靶标感知的分子生成和药物设计 |
| MoleculeGPT | MoleculeGPT: Instruction Following LLMs for Molecular Property Prediction | — | 2024 | arXiv:2306.09048 | NeurIPS 2024 Workshop | 通过分子指令数据微调的LLM，用于自然语言驱动的分子属性预测 |
| SAFE-GPT | SAFE: A Molecular-Centric Foundation Model with SAFE Representation | — | 2024 | doi:10.1039/D4DD00019F | Digital Discovery | 使用SAFE(Sequential Attachment-based Fragment Embedding)表示的分子基础模型 |
| DrugGPT | DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins | — | 2023 | bioRxiv:2023.06.29.543848 | bioRxiv | 基于GPT的药物设计模型，生成靶向特定蛋白质口袋的类药分子 |
| MultiPUFFIN | Multimodal domain-constrained foundation model | — | 2026 | arXiv:2603.00857 | arXiv | 多模态域约束基础模型，整合SMILES、分子图和3D几何 |
| FragCLM | Foundation chemical language model for fragment-based drug discovery | — | 2025 | arXiv:2509.19586 | arXiv | 基于片段的药物发现化学语言基础模型 |

<a id="chemistry-section-02"></a>
## 化学反应与逆合成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Molecular Transformer | Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction | Philippe Schwaller | 2019 | doi:10.1021/acscentsci.9b00576 | ACS Central Science | 开创性的seq2seq Transformer模型，将化学反应预测建模为SMILES翻译问题，支持不确定性校准。 |
| Chemformer | Chemformer: A Pre-trained Transformer for Computational Chemistry | Ross Irwin | 2022 | doi:10.1088/2632-2153/ac3ffb | Machine Learning: Science and Technology | 基于BART架构的预训练Transformer，用于分子SMILES的化学反应预测和逆合成等计算化学任务。 |
| RXNFP | Mapping the Space of Chemical Reactions Using Attention-Based Neural Networks | Philippe Schwaller | 2021 | doi:10.1038/s42256-020-00284-w | Nature Machine Intelligence | IBM开发的Transformer模型，学习化学反应指纹（reaction fingerprints），用于反应分类和反应空间映射。 |
| T5Chem | Unified Deep Learning Model for Multitask Reaction Predictions with Explanation | Jieyu Lu | 2022 | doi:10.1021/acs.jcim.1c01467 | Journal of Chemical Information and Modeling | 基于T5的统一Transformer模型，支持多任务化学反应预测（正向预测、逆合成、产率预测等）。 |
| LocalRetro | Deep Retrosynthetic Reaction Prediction Using Local Reactivity and Global Attention | Shuan Chen | 2021 | doi:10.1021/jacsau.1c00246 | JACS Au | 深度学习逆合成预测框架，强调化学局部反应性和全局注意力，在模板半端方法中达到SOTA。 |
| Retroformer | Retroformer: Pushing the Limits of Interpretable End-to-end Retrosynthesis Transformer | Yue Wan | 2022 | arXiv:2201.12475 | ICML 2022 | 端到端逆合成Transformer模型，引入局部注意力机制同时编码分子序列和图，无模板方法。 |
| Llamole | Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning | Gang Liu | 2024 | arXiv:2410.04223 | NeurIPS 2024 | 多模态大语言模型，集成图扩散Transformer和GNN，支持逆向分子设计和逆合成路线规划。 |
| RetroSynFormer | Retrosynformer: Planning Multi-step Chemical Synthesis Routes via a Decision Transformer | Emma Granqvist | 2025 | doi:10.1039/D5DD00153F | Digital Discovery (RSC) | 基于决策Transformer的多步逆合成规划模型，将逆合成建模为序列预测问题。 |
| SynLlama | SynLlama: Generating Synthesizable Molecules and Their Analogs with Large Language Models | - | 2025 | arXiv:2503.12602 | arXiv preprint | 基于Meta Llama3微调的大语言模型，用于生成可合成分子及完整合成路线。 |
| SynFormer | Generative Artificial Intelligence for Navigating Synthesizable Chemical Space | Wenhao Gao | 2024 | arXiv:2410.03494 | PNAS 2025 | 生成模型框架，专注于可合成化学空间的探索，生成分子时同时保证其可合成性。 |
| ReactionT5 | ReactionT5: A Pre-trained Transformer Model for Accurate Chemical Reaction Prediction with Limited Data | - | 2025 | doi:10.1186/s13321-025-01075-4 | Journal of Cheminformatics | 基于T5的预训练Transformer模型，在Open Reaction Database上预训练，在小数据场景下表现优异。 |
| DeepRetro | DeepRetro Discovers Retrosynthetic Pathways Through Iterative Large Language Model Reasoning | - | 2026 | doi:10.1038/s41598-026-38821-z | Scientific Reports | 结合LLM推理、传统反应模板和专家反馈的高级逆合成框架。 |
| RXNGraphormer | A unified pre-trained deep learning framework for cross-task reaction performance prediction | Li-Cheng Xu | 2025 | doi:10.1038/s42256-025-01098-4 | Nature Machine Intelligence | 统一预训练反应图Transformer，整合GNN和Transformer学习键形成/断裂机制 |
| RSGPT | RSGPT: a generative transformer for retrosynthesis planning pre-trained on ten billion datapoints | Yafeng Deng | 2025 | doi:10.1038/s41467-025-62308-6 | Nature Communications | 在100亿数据点上预训练的逆合成规划生成Transformer |
| RetroChimera | RetroChimera: a frontier retrosynthesis model built on ensembling | Microsoft Research | 2025 | arXiv:2412.05269 | NeurIPS 2025 | 微软开发的前沿逆合成模型 |
| Chem-R | Chemical Reasoning Model | — | 2025 | arXiv:2510.16880 | NeurIPS 2025 | 化学推理模型，模拟化学家深思过程 |
| DeepMech | Graph-based deep learning for predicting reaction mechanisms | — | 2025 | arXiv:2509.15872 | arXiv | 图深度学习预测化学反应机理 |

<a id="chemistry-section-03"></a>
## 蛋白质配体

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| Pearl | Pearl: A Foundation Model for Placing Every Atom in the Right Location | Genesis Research Team | 2025 | arXiv:2510.24670 | NeurIPS 2025 | 蛋白质-配体结构预测基础模型（Genesis Molecular AI），使用大规模合成数据和SO(3)-等变架构，超越AlphaFold 3。 |
| DiffDock | DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking | Gabriele Corso | 2023 | arXiv:2210.01776 | ICLR 2023 | 基于扩散模型的分子对接方法，将蛋白质-配体对接建模为SE(3)上的生成问题，无需先验结合位点信息。 |
| DiffDock-L | Fine-Tuning DiffDock-L for Allosteric Kinase Docking | - | 2026 | doi:10.1021/acs.jcim.5c02846 | J. Chem. Inf. Model. | DiffDock的大规模版本，针对变构激酶结合位点进行微调的扩散对接模型。 |
| NeuralPLexer | State-specific Protein-Ligand Complex Structure Prediction with a Multiscale Deep Generative Model | Zhuoran Qiao | 2024 | doi:10.1038/s42256-024-00792-z | Nature Machine Intelligence | 多尺度深度生成模型，从蛋白质序列和配体分子图直接预测蛋白质-配体复合物3D结构，包括构象变化。 |
| TankBind | TANKBind: Trigonometry-Aware Neural Networks for Drug-Protein Binding Structure Prediction | Wei Lu | 2022 | NeurIPS 2022 | NeurIPS 2022 | 三角函数感知神经网络，通过将蛋白质分割为功能块并引入三角几何约束预测药物-蛋白质结合结构。 |
| Uni-Mol Docking V2 | Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction | - | 2024 | arXiv:2405.11769 | arXiv preprint | Uni-Mol系列的分子对接方法，使用预训练分子和口袋编码器预测蛋白质-配体结合位姿，>77%成功率。 |
| FABind | FABind: Fast and Accurate Protein-Ligand Binding | Qizhi Pei | 2023 | arXiv:2310.06763 | NeurIPS 2023 | 端到端深度学习模型，整合配体引导的口袋预测与对接，快速准确预测蛋白质-配体结合结构。 |
| EquiBind | EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction | Hannes Stärk | 2022 | arXiv:2202.05146 | ICML 2022 | 几何深度学习模型，使用SE(3)-等变GNN直接预测药物-蛋白质结合位点和配体位姿，无需采样。 |
| Umol | Structure Prediction of Protein-Ligand Complexes from Sequence Information with Umol | - | 2024 | doi:10.1038/s41467-024-48837-6 | Nature Communications | 仅从氨基酸序列和SMILES预测全柔性、全原子蛋白质-配体复合物结构的AI系统。 |
| LigUnity | A Foundation Model for Protein-Ligand Affinity Prediction Through Unified Representation | - | 2025 | bioRxiv:2025.02.17.638554 | bioRxiv preprint | 统一表示学习的蛋白质-配体亲和力预测基础模型，同时支持虚拟筛选和先导优化。 |
| PhysDock | Physics-guided all-atom diffusion for protein-ligand prediction | — | 2025 | bioRxiv:2025.04.28.650887 | bioRxiv | 物理引导全原子扩散分子对接 |
| Boltz-2 | Boltz-2: binding affinity prediction of protein-ligand complexes | — | 2025 | bioRxiv:2025.06.14.659707 | bioRxiv | 蛋白质-配体亲和力预测 |
| DiffSBDD | SE(3)-equivariant diffusion for structure-based drug design | — | 2024 | Nature Computational Science | Nature Comp. Sci. | SE(3)等变扩散结构药物设计 |

<a id="chemistry-section-04"></a>
## 3D等变分子表示

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| SchNet | SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions | Kristof Schütt | 2018 | doi:10.1063/1.5019779 | J. Chem. Phys. | 连续滤波卷积神经网络，学习原子间量子相互作用的旋转不变表示，用于分子能量和力预测。 |
| DimeNet | Directional Message Passing for Molecular Graphs | Johannes Gasteiger | 2020 | arXiv:2003.03123 | ICLR 2020 | 方向性消息传递神经网络，利用原子间距离和角度信息进行分子属性预测，引入球面Bessel基函数。 |
| DimeNet++ | Fast and Uncertainty-Aware Directional Message Passing for Non-Equilibrium Molecules | Johannes Gasteiger | 2020 | arXiv:2011.14115 | NeurIPS 2020 Workshop | DimeNet的高效改进版本，通过架构优化实现8倍加速，同时保持预测精度。 |
| PaiNN | Equivariant Message Passing for the Prediction of Tensorial Properties and Molecular Spectra | Kristof Schütt | 2021 | arXiv:2102.03150 | ICML 2021 | 极化原子间交互网络，使用等变消息传递同时更新标量和矢量特征，预测张量属性和分子光谱。 |
| GemNet | GemNet: Universal Directional Graph Neural Networks for Molecules | Johannes Gasteiger | 2021 | arXiv:2106.08903 | NeurIPS 2021 | 通用方向性图神经网络，使用几何消息传递和二面角信息，在分子属性预测上达到SOTA。 |
| GemNet-OC | GemNet-OC: Developing Graph Neural Networks for Large and Diverse Molecular Simulation Datasets | Johannes Gasteiger | 2022 | arXiv:2204.02782 | TMLR 2022 | GemNet针对Open Catalyst大规模数据集的优化版本，改进计算效率和泛化能力。 |
| SphereNet | Spherical Message Passing for 3D Molecular Graphs | Yi Liu | 2022 | arXiv:2102.05013 | ICLR 2022 | 球面消息传递网络，利用完整的球面坐标（距离、角度、二面角）构建3D分子图表示。 |
| ComENet | ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs | Limei Wang | 2022 | arXiv:2206.08515 | NeurIPS 2022 | 完整高效的3D分子消息传递框架，同时编码所有几何信息（距离、角度、扭转角）并保持计算效率。 |
| SEGNN | Geometric and Physical Quantities Improve E(3) Equivariant Message Passing | Johannes Brandstetter | 2022 | arXiv:2110.02905 | ICLR 2022 | Steerable E(3) 等变图神经网络，使用球谐函数基的可操纵特征进行等变消息传递。 |
| LEFTNet | A New Perspective on Building Efficient and Expressive 3D Equivariant Graph Neural Networks | Weitao Du | 2023 | arXiv:2305.07895 | NeurIPS 2023 | 局部等变帧Transformer网络，通过局部参考帧实现高效且富有表达力的3D等变图神经网络。 |
| ViSNet | ViSNet: An Equivariant Geometry-Enhanced Graph Neural Network with Vector-Scalar Interactive Message Passing | Yusong Wang | 2024 | doi:10.1038/s41467-024-50014-6 | Nature Communications | 矢量-标量交互消息传递的等变几何增强GNN，通过运行时几何计算避免昂贵的高阶张量运算。 |
| TorchMD-NET | TorchMD-NET: Equivariant Transformers for Neural Network Based Molecular Potentials | Philipp Thölke | 2022 | arXiv:2202.02541 | ICLR 2022 Workshop | 等变Transformer框架用于构建神经网络分子势函数，支持SchNet和PaiNN等多种架构的统一实现。 |
| EPT | Equivariant Pretrained Transformer for unified 3D molecular representation | — | 2026 | Nature Communications | Nature Communications | E(3)等变全原子预训练Transformer |

<a id="chemistry-section-05"></a>
## 分子生成

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MolGPT | MolGPT: Molecular Generation Using a Transformer-Decoder Model | Viraj Bagal | 2022 | doi:10.1021/acs.jcim.1c00600 | J. Chem. Inf. Model. | 基于GPT的分子生成模型，使用Transformer解码器从SMILES自回归生成满足特定属性约束的分子。 |
| cMolGPT | cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific de novo Molecular Generation | Haiyan Wang | 2023 | doi:10.3390/molecules28114430 | Molecules | 条件分子GPT模型，在MolGPT基础上增加条件控制，针对特定靶点进行从头分子生成。 |
| REINVENT 4 | REINVENT 4: Modern AI-Driven Generative Molecule Design | Hannes Löffler | 2024 | doi:10.1021/acs.jcim.4c00120 | J. Chem. Inf. Model. | AstraZeneca开发的第四代分子生成平台，集成强化学习、迁移学习和多目标优化的工业级分子设计工具。 |
| JT-VAE | Junction Tree Variational Autoencoder for Molecular Graph Generation | Wengong Jin | 2018 | arXiv:1802.04364 | ICML 2018 | 基于连接树分解的变分自编码器，以化学子结构为基本单元生成分子图，保证化学有效性。 |
| MoLeR | Learning to Extend Molecular Scaffolds with Structural Motifs | Krzysztof Maziarz | 2022 | arXiv:2103.03864 | ICLR 2022 | 微软的分子生成模型，通过结构母题逐步扩展分子骨架，支持基于片段的分子设计。 |
| GeoDiff | GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation | Minkai Xu | 2022 | arXiv:2203.02923 | ICLR 2022 | 几何扩散模型用于3D分子构象生成，在SE(3)-等变框架下通过扩散过程生成分子3D坐标。 |
| EDM | Equivariant Diffusion for Molecule Generation in 3D | Emiel Hoogeboom | 2022 | arXiv:2203.17003 | ICML 2022 | E(3)-等变扩散模型，直接在3D空间中生成分子的原子类型和坐标，开创等变分子扩散生成。 |
| GDSS | Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations | Jaehyeong Jo | 2022 | arXiv:2202.02514 | ICML 2022 | 基于分数的图生成模型，通过联合节点-边随机微分方程系统对图进行扩散生成。 |
| DiGress | DiGress: Discrete Denoising Diffusion for Graph Generation | Clément Vignac | 2023 | arXiv:2209.14734 | ICLR 2023 | 离散去噪扩散模型用于图生成，直接在离散节点和边特征空间中进行扩散，适用于分子图生成。 |
| GeoLDM | Geometric Latent Diffusion Models for 3D Molecule Generation | Minkai Xu | 2023 | arXiv:2305.01140 | ICML 2023 | 几何潜在扩散模型，在等变潜在空间中进行3D分子扩散生成，比直接在原子空间扩散更高效。 |
| GFlowNet | Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation | Emmanuel Bengio | 2021 | arXiv:2106.04399 | NeurIPS 2021 | 基于流网络的生成模型，通过学习能量函数的比例采样策略生成多样化分子候选。 |
| TacoGFN | TacoGFN: Target-Conditioned GFlowNet for Structure-Based Drug Design | Tony Shen | 2024 | arXiv:2310.03223 | ICML 2024 Workshop | 靶点条件化的GFlowNet模型，结合蛋白质口袋结构信息进行基于结构的药物分子生成。 |
| GenMol | GenMol: A Drug Discovery Generalist with Discrete Diffusion | Seul Lee (NVIDIA) | 2025 | PMLR v267 | ICLR 2025 | 使用SAFE表示的掩码离散扩散通用分子生成模型 |
| NExT-Mol | NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | Zhiyuan Liu | 2025 | OpenReview | ICLR 2025 | 整合1D SELFIES语言建模与3D扩散的分子生成基础模型 |
| Torsional Diffusion | Torsional Diffusion for Molecular Conformer Generation | Bowen Jing | 2022 | arXiv:2206.01729 | NeurIPS 2022 | 基于扭转角扩散的分子构象生成模型 |
| ConfGF | Learning Gradient Fields for Molecular Conformation Generation | Chence Shi | 2021 | arXiv:2105.03902 | ICML 2021 | 学习梯度场的分子构象生成模型 |
| DMCG | Direct Molecular Conformation Generation | — | 2022 | arXiv:2202.01356 | TMLR 2022 | 直接分子构象生成方法 |
| DiTMC | Sampling 3D Molecular Conformers with Diffusion Transformers | — | 2025 | arXiv:2506.15378 | NeurIPS 2025 | 基于扩散Transformer的3D分子构象生成 |
| SynCoGen | Synthesizable 3D molecule generation via joint reaction and coordinate modeling | — | 2025 | arXiv:2507.11818 | ICLR 2026 | 可合成3D分子生成 |

<a id="chemistry-section-06"></a>
## 光谱与分析化学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| MolSpectLLM | MolSpectLLM: A Large Language Model for Molecular Spectroscopy Interpretation | - | 2025 | arXiv:2502.13094 | arXiv preprint | 大语言模型用于分子光谱解释，将NMR、IR、MS等多种光谱数据与分子结构关联，支持光谱到结构的推理。 |
| MACE4IR | MACE4IR: Machine Learning Interatomic Potentials for Infrared Spectroscopy Prediction | - | 2025 | arXiv:2503.08205 | arXiv preprint | 基于MACE等变图神经网络的红外光谱预测模型，利用机器学习原子间势能直接预测IR光谱。 |
| Vib2Mol | Vib2Mol: From Vibrational Spectra to Molecular Structures | - | 2025 | arXiv:2504.01187 | arXiv preprint | 振动光谱到分子结构的深度学习模型，从IR/Raman光谱直接推断分子结构信息。 |
| FIDDLE | Deep learning predicting chemical formulas from tandem mass spectra | — | 2025 | Nature Communications | Nature Comms | 从串联质谱预测化学分子式 |
| NMRTrans | Set Transformer for molecular structure elucidation from NMR | — | 2026 | arXiv:2602.10158 | arXiv | 从NMR光谱解析分子结构 |

<a id="chemistry-section-07"></a>
## 食品科学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| FART | A chemical language model for molecular taste prediction | — | 2025 | doi:10.1038/s41538-025-00474-z | npj Science of Food | 化学语言模型，从SMILES预测分子味觉 |

<a id="chemistry-section-08"></a>
## 电化学

| 模型名称 | 论文标题 | 第一作者 | 年份 | ArXiv/DOI | 发表venue | 简述 |
|---------|---------|---------|------|-----------|----------|------|
| HELENA | Hierarchical Moiety-Aware Graph Transformer for Li-metal Electrolyte Design | — | 2025 | chemRxiv | chemRxiv | 层次基团感知图transformer，用于锂金属电池电解质设计 |
