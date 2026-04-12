# Chemistry

<p align="right"><strong>Language:</strong> English | <a href="chemistry_zh.md">中文</a></p>

> Molecular representation, molecular generation, reaction prediction, retrosynthesis, chemical language models, spectroscopy, and related chemistry foundation models.
> [Index](../README.md)

## Table of Contents
- [Small Molecules](#chemistry-section-01)
- [Reactions & Retrosynthesis](#chemistry-section-02)
- [Protein-Ligand Interactions](#chemistry-section-03)
- [3D Equivariant Molecular Representations](#chemistry-section-04)
- [Molecular Generation & Diffusion](#chemistry-section-05)
- [Spectroscopy & Analytical Chemistry](#chemistry-section-06)
- [Food Science](#chemistry-section-07)
- [Electrochemistry](#chemistry-section-08)

<a id="chemistry-section-01"></a>
## Small Molecules

*Foundation models for molecular property prediction, representation learning, and chemical language modeling on SMILES and molecular graphs.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MoLFormer | Large-Scale Chemical Language Representations Capture Molecular Structure and Properties | Transformer-based chemical language model pretrained on 1.1B SMILES with linear attention and rotary embeddings for molecular property prediction. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-022-00580-7) |
| GP-MoLFormer | GP-MoLFormer: A Foundation Model For Molecular Generation | Transformer-based generative foundation model with 46.8M parameters trained on 1.1B SMILES for molecular generation tasks. | [Digital Discovery](https://doi.org/10.1039/d5dd00122f) |
| ChemBERTa | ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction | RoBERTa-based chemical language model pretrained on 10M PubChem SMILES for molecular property prediction. | [NeurIPS ML4Molecules Workshop](https://arxiv.org/abs/2010.09885) |
| ChemBERTa-2 | ChemBERTa-2: Towards Chemical Foundation Models | Evolved ChemBERTa pretrained on 77M PubChem SMILES with optimized pretraining strategies including multi-task regression. | [arXiv](https://arxiv.org/abs/2209.01712) |
| ChemFM | ChemFM as a Scaling Law Guided Foundation Model Pre-trained on Informative Chemicals | 3B-parameter chemical foundation model trained on 178M UniChem molecules using self-supervised causal language modeling guided by scaling laws. | [Communications Chemistry](https://doi.org/10.1038/s42004-025-01793-8) |
| ChemDFM | Developing ChemDFM as a Large Language Foundation Model for Chemistry | LLaMA-13B-based chemistry LLM trained on 34B tokens of chemical literature and fine-tuned with 2.7M instruction pairs. | [Cell Reports Physical Science](https://doi.org/10.1016/j.xcrp.2025.102523) |
| Uni-Mol | Uni-Mol: A Universal 3D Molecular Representation Learning Framework | Universal 3D molecular representation learning framework that directly leverages molecular 3D structures for pretraining and achieves SOTA on property prediction. | [ICLR](https://openreview.net/forum?id=6K2RM6wVqKu) |
| Uni-Mol2 | Uni-Mol2: Exploring Molecular Pretraining Model at Scale | Largest 3D molecular foundation model (1.1B parameters) with dual-track Transformer integrating atomic, graph, and 3D geometric features trained on 884M molecules. | [NeurIPS](https://doi.org/10.52202/079017-1489) |
| MolBERT | MolBERT: Molecular Representation Learning with Language Models and Domain-Relevant Auxiliary Tasks | BERT-based molecular representation model using SMILES with self-supervised auxiliary tasks for meaningful molecular embeddings. | [arXiv](https://arxiv.org/abs/2011.13230) |
| GROVER | Self-Supervised Graph Transformer on Large-Scale Molecular Data | Self-supervised graph Transformer combining GNN message passing with Transformer attention, pretrained on large-scale molecular data. | [NeurIPS](https://proceedings.neurips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html) |
| GEM | Geometry-Enhanced Molecular Representation Learning for Property Prediction | Geometry-enhanced molecular representation learning framework that exploits 3D spatial structure information for improved property prediction. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-021-00438-4) |
| Graphormer | Do Transformers Really Perform Bad for Graph Representation? | Graph Transformer framework from Microsoft that won 1st place on OGB-LSC molecular tasks, introducing spatial and edge encodings for graph structure modeling. | [NeurIPS](https://proceedings.neurips.cc/paper/2021/hash/f1c1592588411002af340cbaedd6fc33-Abstract.html) |
| MoleculeSTM | Multi-modal Molecule Structure-text Model for Text-based Retrieval and Editing | Multi-modal model jointly learning molecular structures and text descriptions for text-driven molecular retrieval and editing. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00759-6) |
| 3D-MoLM | Towards 3D Molecule-Text Interpretation in Language Models | Pioneering framework integrating a 3D molecular encoder with language models via a 3D molecule-text projector for LLM-based molecular understanding. | [ICLR](https://openreview.net/forum?id=xI4yNlkaqh) |
| MolE | MolE: A Foundation Model for Molecular Graphs Using Disentangled Attention | Molecular graph foundation model from Recursion using disentangled-attention Transformers, pretrained in two self-supervised stages on ~842M molecules. | [Nature Communications](https://doi.org/10.1038/s41467-024-53751-y) |
| MiniMol | MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning | Parameter-efficient molecular foundation model (only 10M parameters) pretrained on 3,300+ diverse bioactivity datasets from 6M molecules. | [ICML](https://arxiv.org/abs/2404.14986) |
| SMILES-Mamba | SMILES-Mamba: Chemical Mamba Foundation Models for Drug ADMET Prediction | Mamba-architecture chemical foundation model with two-stage training (self-supervised pretraining + supervised fine-tuning) for drug ADMET prediction. | [NeurIPS 2024 Workshop](https://arxiv.org/abs/2408.05696) |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | Large-scale SMILES encoder-decoder foundation model from IBM, self-supervised on 91M PubChem SMILES for chemistry and materials science. | [ICLR 2024 Workshop](https://openreview.net/forum?id=Yq8At31hLi) |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | Knowledge-guided graph Transformer pretraining framework integrating chemical knowledge to enhance molecular representation learning. | [Nature Communications](https://doi.org/10.1038/s41467-023-43214-1) |
| GIN (Pretrained) | Strategies for Pre-Training Graph Neural Networks | Pioneering work proposing GNN pretraining strategies (node-level + graph-level) with GIN pretrained on 2M molecules for property prediction. | [ICLR](https://openreview.net/forum?id=HJlWWJSFDH) |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Family of large-scale molecular foundation models (Molecular Insight SMILES Transformers) trained on vast unlabeled molecules, predicting 400+ structure-property relationships. | [arXiv](https://arxiv.org/abs/2510.18900) |
| M2UMol | Multi-to-Uni Modal Knowledge Transfer Pre-training for Molecular Representation Learning | Multi-modal to uni-modal knowledge transfer pretraining framework that distills diverse molecular modality knowledge into a 2D encoder. | [Nature Communications](https://doi.org/10.1038/s41467-026-69302-6) |
| Omni-Mol | Exploring Universal Convergent Space for Omni-Molecular Tasks | Unified language model enabling any-to-any modality molecular tasks in a universal convergent space. | [NeurIPS](https://arxiv.org/abs/2502.01074) |
| TamGen | TamGen: Drug Design with Target-Aware Molecule Generation through a Chemical Language Model | GPT-style chemical language model for target-aware molecule generation and drug design. | [Nature Communications](https://doi.org/10.1038/s41467-024-53632-4) |
| MoleculeGPT | MoleculeGPT: Instruction Following LLMs for Molecular Property Prediction | LLM fine-tuned with molecular instruction data for natural-language-driven molecular property prediction. | [NeurIPS 2024 Workshop](https://arxiv.org/abs/2306.09048) |
| SAFE-GPT | SAFE: A Molecular-Centric Foundation Model with SAFE Representation | Foundation model using Sequential Attachment-based Fragment Embedding (SAFE) molecular representation for generative chemistry. | [Digital Discovery](https://doi.org/10.1039/D4DD00019F) |
| DrugGPT | DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins | GPT-based drug design model that generates drug-like molecules targeting specific protein binding pockets. | [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.06.29.543848) |
| MultiPUFFIN | Multimodal domain-constrained foundation model | Multi-modal domain-constrained foundation model integrating SMILES, molecular graphs, and 3D geometry for molecular understanding. | [arXiv](https://arxiv.org/abs/2603.00857) |
| FragCLM | Foundation chemical language model for fragment-based drug discovery | Foundation chemical language model trained on the ZINC-22 fragment dataset for comprehensive fragment-based drug discovery. | [arXiv](https://arxiv.org/abs/2509.19586) |

---

<a id="chemistry-section-02"></a>
## Reactions & Retrosynthesis

*Foundation models for chemical reaction prediction, retrosynthetic planning, and synthesis route design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Molecular Transformer | Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction | Pioneering seq2seq Transformer that frames chemical reaction prediction as SMILES translation with uncertainty calibration. | [ACS Central Science](https://doi.org/10.1021/acscentsci.9b00576) |
| Chemformer | Chemformer: A Pre-trained Transformer for Computational Chemistry | BART-based pretrained Transformer for reaction prediction, retrosynthesis, and other computational chemistry tasks over molecular SMILES. | [Machine Learning: Science and Technology](https://doi.org/10.1088/2632-2153/ac3ffb) |
| RXNFP | Mapping the Space of Chemical Reactions Using Attention-Based Neural Networks | Transformer model from IBM that learns chemical reaction fingerprints for reaction classification and reaction space mapping. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-020-00284-w) |
| T5Chem | Unified Deep Learning Model for Multitask Reaction Predictions with Explanation | T5-based unified Transformer supporting multi-task chemical reaction predictions including forward synthesis, retrosynthesis, and yield prediction. | [JCIM](https://doi.org/10.1021/acs.jcim.1c01467) |
| Llamole | Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning | Multi-modal LLM integrating graph diffusion Transformer and GNN for inverse molecular design with retrosynthetic route planning. | [NeurIPS](https://openreview.net/forum?id=rQ7fz9NO7f) |
| RetroSynFormer | Retrosynformer: Planning Multi-step Chemical Synthesis Routes via a Decision Transformer | Decision Transformer for multi-step retrosynthetic planning that models retrosynthesis as a sequence prediction problem. | [Digital Discovery](https://doi.org/10.1039/D5DD00153F) |
| SynLlama | SynLlama: Generating Synthesizable Molecules and Their Analogs with Large Language Models | LLM fine-tuned from Meta Llama 3 for generating synthesizable molecules along with complete synthesis routes. | [ACS Central Science](https://doi.org/10.1021/acscentsci.5c01285) |
| SynFormer | Generative Artificial Intelligence for Navigating Synthesizable Chemical Space | Generative model framework for exploring synthesizable chemical space, ensuring generated molecules are synthetically accessible. | [PNAS](https://doi.org/10.1073/pnas.2415665122) |
| ReactionT5 | ReactionT5: A Pre-trained Transformer Model for Accurate Chemical Reaction Prediction with Limited Data | T5-based pretrained Transformer for chemical reaction prediction, pretrained on the Open Reaction Database and excelling with limited data. | [Journal of Cheminformatics](https://doi.org/10.1186/s13321-025-01075-4) |
| DeepRetro | DeepRetro Discovers Retrosynthetic Pathways Through Iterative Large Language Model Reasoning | Advanced retrosynthesis framework combining LLM reasoning, reaction templates, and expert feedback for iterative pathway discovery. | [Scientific Reports](https://doi.org/10.1038/s41598-026-38821-z) |
| RXNGraphormer | A unified pre-trained deep learning framework for cross-task reaction performance prediction | Unified pretrained reaction graph Transformer integrating GNN and Transformer to learn bond formation/breaking mechanisms across tasks. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01098-4) |
| RSGPT | RSGPT: a generative transformer for retrosynthesis planning pre-trained on ten billion datapoints | Generative Transformer for retrosynthesis planning pretrained on 10 billion datapoints for large-scale synthetic route prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-62308-6) |
| Chem-R | Chem-R: Learning to Reason as a Chemist | Chemical reasoning model that emulates chemists' deep thinking processes through a three-phase training framework. | [NeurIPS](https://arxiv.org/abs/2510.16880) |

---

<a id="chemistry-section-03"></a>
## Protein-Ligand Interactions

*Foundation models for molecular docking, binding affinity prediction, and protein-ligand complex structure prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Pearl | Pearl: A Foundation Model for Placing Every Atom in the Right Location | Protein-ligand structure prediction foundation model from Genesis Molecular AI using large-scale synthetic data and SO(3)-equivariant architecture, surpassing AlphaFold 3. | [NeurIPS](https://arxiv.org/abs/2510.24670) |
| DiffDock | DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking | Diffusion-based molecular docking method that models protein-ligand docking as a generative problem on SE(3) without requiring prior binding site knowledge. | [ICLR](https://openreview.net/forum?id=kKF8_K-mBbS) |
| DiffDock-L | Fine-Tuning DiffDock-L for Allosteric Kinase Docking | Large-scale DiffDock variant fine-tuned for allosteric kinase binding site docking. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.5c02846) |
| NeuralPLexer | State-specific Protein-Ligand Complex Structure Prediction with a Multiscale Deep Generative Model | Multi-scale deep generative model that predicts protein-ligand complex 3D structures directly from protein sequence and ligand graph, including conformational changes. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00792-z) |
| Uni-Mol Docking V2 | Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction | Molecular docking method in the Uni-Mol series using pretrained molecular and pocket encoders to predict protein-ligand binding poses with >77% success rate. | [Lecture Notes in Computer Science](https://doi.org/10.1007/978-3-032-04552-2_5) |
| Umol | Structure Prediction of Protein-Ligand Complexes from Sequence Information with Umol | AI system predicting full-flexibility, all-atom protein-ligand complex structures solely from amino acid sequence and SMILES. | [Nature Communications](https://doi.org/10.1038/s41467-024-48837-6) |
| LigUnity | A Foundation Model for Protein-Ligand Affinity Prediction Through Unified Representation | Unified representation learning foundation model for protein-ligand affinity prediction supporting both virtual screening and lead optimization. | [bioRxiv preprint](https://www.biorxiv.org/content/10.1101/2025.02.17.638554) |
| PhysDock | PhysDock: A Physics-Guided All-Atom Diffusion Model for Protein-Ligand Complex Prediction | Physics-guided all-atom diffusion model for protein-ligand complex prediction integrating detailed atomic-level flexibility modeling. | [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.04.28.650887) |
| Boltz-2 | Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction | Advanced model for accurate and efficient protein-ligand binding affinity prediction building on AlphaFold3 and Boltz-1 architectures. | [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.06.14.659707) |

---

<a id="chemistry-section-04"></a>
## 3D Equivariant Molecular Representations

*Equivariant and invariant neural network architectures for learning 3D molecular representations, energy prediction, and force fields.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SchNet | SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions | Continuous-filter convolutional neural network learning rotationally invariant representations of quantum interactions for molecular energy and force prediction. | [NeurIPS 2017](https://doi.org/10.1063/1.5019779) |
| ViSNet | ViSNet: An Equivariant Geometry-Enhanced Graph Neural Network with Vector-Scalar Interactive Message Passing | Equivariant geometry-enhanced GNN with vector-scalar interactive message passing that avoids expensive higher-order tensor operations via runtime geometric computation. | [Nature Communications](https://doi.org/10.1038/s41467-024-50014-6) |
| EPT | An equivariant pretrained transformer for unified 3D molecular representation learning | E(3)-equivariant all-atom pretrained Transformer for unified 3D molecular representation learning across diverse scientific domains. | [Nature Communications](https://doi.org/10.1038/s41467-026-69185-7) |

---

<a id="chemistry-section-05"></a>
## Molecular Generation & Diffusion

*Generative models for de novo molecular design, 3D conformation generation, and structure-based molecule generation using diffusion, VAEs, autoregressive, and flow-based approaches.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolGPT | MolGPT: Molecular Generation Using a Transformer-Decoder Model | GPT-based molecular generation model using a Transformer decoder to autoregressively generate SMILES satisfying specific property constraints. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.1c00600) |
| cMolGPT | cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific de novo Molecular Generation | Conditional molecular GPT extending MolGPT with target-specific controls for de novo molecular generation. | [Molecules](https://doi.org/10.3390/molecules28114430) |
| GenMol | GenMol: A Drug Discovery Generalist with Discrete Diffusion | General-purpose molecular generation model from NVIDIA using masked discrete diffusion over SAFE representations for multi-stage drug discovery. | [ICLR](https://proceedings.mlr.press/v267/lee25o.html) |
| NExT-Mol | NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | Foundation model integrating 1D SELFIES language modeling with 3D diffusion for 3D molecule generation. | [ICLR 2025](https://openreview.net/forum?id=tbo1Svjrxz) |
| DiTMC | Sampling 3D Molecular Conformers with Diffusion Transformers | Diffusion Transformer framework for sampling accurate 3D molecular conformers integrating discrete molecular graphs with continuous coordinates. | [NeurIPS](https://arxiv.org/abs/2506.15378) |
| SynCoGen | Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling | Framework for synthesizable 3D molecule generation that jointly models molecular building blocks, chemical reactions, and atomic coordinates. | [ICLR](https://arxiv.org/abs/2507.11818) |

---

<a id="chemistry-section-06"></a>
## Spectroscopy & Analytical Chemistry

*Foundation models for interpreting and predicting molecular spectra including NMR, IR, Raman, and mass spectrometry.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolSpectLLM | MolSpectLLM: A Large Language Model for Molecular Spectroscopy Interpretation | Large language model for molecular spectroscopy interpretation, linking NMR, IR, and MS spectral data to molecular structures for spectrum-to-structure reasoning. | [arXiv](https://arxiv.org/abs/2502.13094) |

---

<a id="chemistry-section-07"></a>
## Food Science

*Chemical language models applied to food-related molecular property prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FART | A chemical language model for molecular taste prediction | Chemical language model predicting molecular taste properties from SMILES representations. | [npj Science of Food](https://doi.org/10.1038/s41538-025-00474-z) |

---

<a id="chemistry-section-08"></a>
## Electrochemistry

*Foundation models for electrochemical applications including battery electrolyte design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
