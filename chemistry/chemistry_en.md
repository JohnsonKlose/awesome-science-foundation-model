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
| GP-MoLFormer | GP-MoLFormer: A Foundation Model For Molecular Generation | Transformer-based generative foundation model with 46.8M parameters trained on 1.1B SMILES for molecular generation tasks. | [Digital Discovery](https://arxiv.org/abs/2405.04912) |
| ChemBERTa | ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction | RoBERTa-based chemical language model pretrained on 10M PubChem SMILES for molecular property prediction. | [Paper](https://arxiv.org/abs/2010.09885) |
| ChemBERTa-2 | ChemBERTa-2: Towards Chemical Foundation Models | Evolved ChemBERTa pretrained on 77M PubChem SMILES with optimized pretraining strategies including multi-task regression. | [Paper](https://arxiv.org/abs/2209.01712) |
| ChemBERTa-3 | ChemBERTa-3: An Open Source Training Framework for Chemical Foundation Models | Open-source training framework extending the ChemBERTa series for building chemical foundation models. | [Artificial Intelligence in the Life Sciences](https://doi.org/10.1016/j.ailsci.2026.100112) |
| ChemFM | ChemFM as a Scaling Law Guided Foundation Model Pre-trained on Informative Chemicals | 3B-parameter chemical foundation model trained on 178M UniChem molecules using self-supervised causal language modeling guided by scaling laws. | [Communications Chemistry](https://arxiv.org/abs/2410.21422) |
| ChemDFM | Developing ChemDFM as a Large Language Foundation Model for Chemistry | LLaMA-13B-based chemistry LLM trained on 34B tokens of chemical literature and fine-tuned with 2.7M instruction pairs. | [Cell Reports Physical Science](https://arxiv.org/abs/2401.14818) |
| Uni-Mol | Uni-Mol: A Universal 3D Molecular Representation Learning Framework | Universal 3D molecular representation learning framework that directly leverages molecular 3D structures for pretraining and achieves SOTA on property prediction. | [Paper](https://arxiv.org/abs/2204.07599) |
| Uni-Mol2 | Uni-Mol2: Exploring Molecular Pretraining Model at Scale | Largest 3D molecular foundation model (1.1B parameters) with dual-track Transformer integrating atomic, graph, and 3D geometric features trained on 884M molecules. | [Paper](https://arxiv.org/abs/2406.14969) |
| MolBERT | MolBERT: Molecular Representation Learning with Language Models and Domain-Relevant Auxiliary Tasks | BERT-based molecular representation model using SMILES with self-supervised auxiliary tasks for meaningful molecular embeddings. | [Paper](https://arxiv.org/abs/2011.13230) |
| GROVER | Self-Supervised Graph Transformer on Large-Scale Molecular Data | Self-supervised graph Transformer combining GNN message passing with Transformer attention, pretrained on large-scale molecular data. | [Paper](https://arxiv.org/abs/2007.02835) |
| GEM | Geometry-Enhanced Molecular Representation Learning for Property Prediction | Geometry-enhanced molecular representation learning framework that exploits 3D spatial structure information for improved property prediction. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-021-00438-4) |
| Graphormer | Do Transformers Really Perform Bad for Graph Representation? | Graph Transformer framework from Microsoft that won 1st place on OGB-LSC molecular tasks, introducing spatial and edge encodings for graph structure modeling. | [Paper](https://arxiv.org/abs/2106.05234) |
| MoleculeSTM | Multi-modal Molecule Structure-text Model for Text-based Retrieval and Editing | Multi-modal model jointly learning molecular structures and text descriptions for text-driven molecular retrieval and editing. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00759-6) |
| 3D-MoLM | Towards 3D Molecule-Text Interpretation in Language Models | Pioneering framework integrating a 3D molecular encoder with language models via a 3D molecule-text projector for LLM-based molecular understanding. | [Paper](https://arxiv.org/abs/2401.13923) |
| MolE | MolE: A Foundation Model for Molecular Graphs Using Disentangled Attention | Molecular graph foundation model from Recursion using disentangled-attention Transformers, pretrained in two self-supervised stages on ~842M molecules. | [Nature Communications](https://doi.org/10.1038/s41467-024-53751-y) |
| MiniMol | MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning | Parameter-efficient molecular foundation model (only 10M parameters) pretrained on 3,300+ diverse bioactivity datasets from 6M molecules. | [Paper](https://arxiv.org/abs/2404.14986) |
| SMILES-Mamba | SMILES-Mamba: Chemical Mamba Foundation Models for Drug ADMET Prediction | Mamba-architecture chemical foundation model with two-stage training (self-supervised pretraining + supervised fine-tuning) for drug ADMET prediction. | [Paper](https://arxiv.org/abs/2408.05696) |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | Large-scale SMILES encoder-decoder foundation model from IBM, self-supervised on 91M PubChem SMILES for chemistry and materials science. | [Paper](https://openreview.net/forum?id=Yq8At31hLi) |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | Knowledge-guided graph Transformer pretraining framework integrating chemical knowledge to enhance molecular representation learning. | [Nature Communications](https://doi.org/10.1038/s41467-023-43214-1) |
| GIN (Pretrained) | Strategies for Pre-Training Graph Neural Networks | Pioneering work proposing GNN pretraining strategies (node-level + graph-level) with GIN pretrained on 2M molecules for property prediction. | [Paper](https://arxiv.org/abs/1905.12265) |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Family of large-scale molecular foundation models (Molecular Insight SMILES Transformers) trained on vast unlabeled molecules, predicting 400+ structure-property relationships. | [Paper](https://arxiv.org/abs/2510.18900) |
| M2UMol | Multi-to-Uni Modal Knowledge Transfer Pre-training for Molecular Representation Learning | Multi-modal to uni-modal knowledge transfer pretraining framework that distills diverse molecular modality knowledge into a 2D encoder. | [Nature Communications](https://doi.org/10.1038/s41467-026-69302-6) |
| Chemprop (D-MPNN) | Analyzing Learned Molecular Representations for Property Prediction | Directed message passing neural network for molecular property prediction with learned representations. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.9b00237) |
| Omni-Mol | Exploring Universal Convergent Space for Omni-Molecular Tasks | Unified language model enabling any-to-any modality molecular tasks in a universal convergent space. | [Paper](https://arxiv.org/abs/2502.01074) |
| ADMET-AI | ADMET-AI: A Machine Learning ADMET Platform | Machine learning platform for rapid ADMET property prediction across large chemical libraries. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btae416) |
| TamGen | TamGen: Drug Design with Target-Aware Molecule Generation through a Chemical Language Model | GPT-style chemical language model for target-aware molecule generation and drug design. | [Nature Communications](https://doi.org/10.1038/s41467-024-53632-4) |
| MoleculeGPT | MoleculeGPT: Instruction Following LLMs for Molecular Property Prediction | LLM fine-tuned with molecular instruction data for natural-language-driven molecular property prediction. | [Paper](https://arxiv.org/abs/2306.09048) |
| SAFE-GPT | SAFE: A Molecular-Centric Foundation Model with SAFE Representation | Foundation model using Sequential Attachment-based Fragment Embedding (SAFE) molecular representation for generative chemistry. | [Digital Discovery](https://doi.org/10.1039/D4DD00019F) |
| DrugGPT | DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins | GPT-based drug design model that generates drug-like molecules targeting specific protein binding pockets. | [Paper](https://www.biorxiv.org/content/10.1101/2023.06.29.543848) |
| MultiPUFFIN | Multimodal domain-constrained foundation model | Multi-modal domain-constrained foundation model integrating SMILES, molecular graphs, and 3D geometry for molecular understanding. | [Paper](https://arxiv.org/abs/2603.00857) |
| FragCLM | Foundation chemical language model for fragment-based drug discovery | Foundation chemical language model trained on the ZINC-22 fragment dataset for comprehensive fragment-based drug discovery. | [Paper](https://arxiv.org/abs/2509.19586) |

---

<a id="chemistry-section-02"></a>
## Reactions & Retrosynthesis

*Foundation models for chemical reaction prediction, retrosynthetic planning, and synthesis route design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Molecular Transformer | Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction | Pioneering seq2seq Transformer that frames chemical reaction prediction as SMILES translation with uncertainty calibration. | [ACS Central Science](https://doi.org/10.1021/acscentsci.9b00576) |
| Chemformer | Chemformer: A Pre-trained Transformer for Computational Chemistry | BART-based pretrained Transformer for reaction prediction, retrosynthesis, and other computational chemistry tasks over molecular SMILES. | [Machine Learning: Science and Technology](https://doi.org/10.1088/2632-2153/ac3ffb) |
| RXNFP | Mapping the Space of Chemical Reactions Using Attention-Based Neural Networks | Transformer model from IBM that learns chemical reaction fingerprints for reaction classification and reaction space mapping. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-020-00284-w) |
| T5Chem | Unified Deep Learning Model for Multitask Reaction Predictions with Explanation | T5-based unified Transformer supporting multi-task chemical reaction predictions including forward synthesis, retrosynthesis, and yield prediction. | [Journal of Chemical Information and Modeling](https://doi.org/10.1021/acs.jcim.1c01467) |
| LocalRetro | Deep Retrosynthetic Reaction Prediction Using Local Reactivity and Global Attention | Deep learning retrosynthesis framework emphasizing local chemical reactivity and global attention, achieving SOTA among semi-template methods. | [JACS Au](https://doi.org/10.1021/jacsau.1c00246) |
| Retroformer | Retroformer: Pushing the Limits of Interpretable End-to-end Retrosynthesis Transformer | End-to-end retrosynthesis Transformer with local attention that jointly encodes molecular sequences and graphs in a template-free approach. | [Paper](https://arxiv.org/abs/2201.12475) |
| Llamole | Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning | Multi-modal LLM integrating graph diffusion Transformer and GNN for inverse molecular design with retrosynthetic route planning. | [Paper](https://arxiv.org/abs/2410.04223) |
| RetroSynFormer | Retrosynformer: Planning Multi-step Chemical Synthesis Routes via a Decision Transformer | Decision Transformer for multi-step retrosynthetic planning that models retrosynthesis as a sequence prediction problem. | [Digital Discovery](https://doi.org/10.1039/D5DD00153F) |
| SynLlama | SynLlama: Generating Synthesizable Molecules and Their Analogs with Large Language Models | LLM fine-tuned from Meta Llama 3 for generating synthesizable molecules along with complete synthesis routes. | [ACS Central Science](https://arxiv.org/abs/2503.12602) |
| SynFormer | Generative Artificial Intelligence for Navigating Synthesizable Chemical Space | Generative model framework for exploring synthesizable chemical space, ensuring generated molecules are synthetically accessible. | [Paper](https://arxiv.org/abs/2410.03494) |
| ReactionT5 | ReactionT5: A Pre-trained Transformer Model for Accurate Chemical Reaction Prediction with Limited Data | T5-based pretrained Transformer for chemical reaction prediction, pretrained on the Open Reaction Database and excelling with limited data. | [Journal of Cheminformatics](https://doi.org/10.1186/s13321-025-01075-4) |
| DeepRetro | DeepRetro Discovers Retrosynthetic Pathways Through Iterative Large Language Model Reasoning | Advanced retrosynthesis framework combining LLM reasoning, reaction templates, and expert feedback for iterative pathway discovery. | [Scientific Reports](https://doi.org/10.1038/s41598-026-38821-z) |
| RXNGraphormer | A unified pre-trained deep learning framework for cross-task reaction performance prediction | Unified pretrained reaction graph Transformer integrating GNN and Transformer to learn bond formation/breaking mechanisms across tasks. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01098-4) |
| RSGPT | RSGPT: a generative transformer for retrosynthesis planning pre-trained on ten billion datapoints | Generative Transformer for retrosynthesis planning pretrained on 10 billion datapoints for large-scale synthetic route prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-62308-6) |
| RetroChimera | Chemist-aligned retrosynthesis by ensembling diverse inductive biases | Frontier retrosynthesis model from Microsoft built on ensembling complementary models with diverse inductive biases. | [Paper](https://arxiv.org/abs/2412.05269) |
| Chem-R | Chem-R: Learning to Reason as a Chemist | Chemical reasoning model that emulates chemists' deep thinking processes through a three-phase training framework. | [Paper](https://arxiv.org/abs/2510.16880) |
| DeepMech | DeepMech: A Machine Learning Framework for Chemical Reaction Mechanism Prediction | Graph deep learning framework for predicting complete chemical reaction mechanisms with interpretable outputs. | [Paper](https://arxiv.org/abs/2509.15872) |

---

<a id="chemistry-section-03"></a>
## Protein-Ligand Interactions

*Foundation models for molecular docking, binding affinity prediction, and protein-ligand complex structure prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Pearl | Pearl: A Foundation Model for Placing Every Atom in the Right Location | Protein-ligand structure prediction foundation model from Genesis Molecular AI using large-scale synthetic data and SO(3)-equivariant architecture, surpassing AlphaFold 3. | [Paper](https://arxiv.org/abs/2510.24670) |
| DiffDock | DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking | Diffusion-based molecular docking method that models protein-ligand docking as a generative problem on SE(3) without requiring prior binding site knowledge. | [Paper](https://arxiv.org/abs/2210.01776) |
| DiffDock-L | Fine-Tuning DiffDock-L for Allosteric Kinase Docking | Large-scale DiffDock variant fine-tuned for allosteric kinase binding site docking. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.5c02846) |
| NeuralPLexer | State-specific Protein-Ligand Complex Structure Prediction with a Multiscale Deep Generative Model | Multi-scale deep generative model that predicts protein-ligand complex 3D structures directly from protein sequence and ligand graph, including conformational changes. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00792-z) |
| TankBind | TANKBind: Trigonometry-Aware Neural Networks for Drug-Protein Binding Structure Prediction | Trigonometry-aware neural network that segments proteins into functional blocks with geometric constraints for drug-protein binding structure prediction. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/2f89a23a19d1617e7fb16d4f7a049ce2-Abstract-Conference.html) |
| Uni-Mol Docking V2 | Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction | Molecular docking method in the Uni-Mol series using pretrained molecular and pocket encoders to predict protein-ligand binding poses with >77% success rate. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2405.11769) |
| FABind | FABind: Fast and Accurate Protein-Ligand Binding | End-to-end model integrating ligand-guided pocket prediction and docking for fast and accurate protein-ligand binding structure prediction. | [NeurIPS 2023](https://arxiv.org/abs/2310.06763) |
| EquiBind | EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction | SE(3)-equivariant GNN that directly predicts drug-protein binding sites and ligand poses without sampling. | [Paper](https://arxiv.org/abs/2202.05146) |
| Umol | Structure Prediction of Protein-Ligand Complexes from Sequence Information with Umol | AI system predicting full-flexibility, all-atom protein-ligand complex structures solely from amino acid sequence and SMILES. | [Nature Communications](https://doi.org/10.1038/s41467-024-48837-6) |
| LigUnity | A Foundation Model for Protein-Ligand Affinity Prediction Through Unified Representation | Unified representation learning foundation model for protein-ligand affinity prediction supporting both virtual screening and lead optimization. | [Paper](https://www.biorxiv.org/content/10.1101/2025.02.17.638554) |
| PhysDock | PhysDock: A Physics-Guided All-Atom Diffusion Model for Protein-Ligand Complex Prediction | Physics-guided all-atom diffusion model for protein-ligand complex prediction integrating detailed atomic-level flexibility modeling. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.28.650887) |
| Boltz-2 | Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction | Advanced model for accurate and efficient protein-ligand binding affinity prediction building on AlphaFold3 and Boltz-1 architectures. | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.14.659707) |
| DiffSBDD | Structure-based drug design with equivariant diffusion models | SE(3)-equivariant diffusion model that generates 3D molecular ligands conditioned on protein binding pockets for structure-based drug design. | [Nature Comp. Sci.](https://doi.org/10.1038/s43588-024-00737-x) |

---

<a id="chemistry-section-04"></a>
## 3D Equivariant Molecular Representations

*Equivariant and invariant neural network architectures for learning 3D molecular representations, energy prediction, and force fields.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SchNet | SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions | Continuous-filter convolutional neural network learning rotationally invariant representations of quantum interactions for molecular energy and force prediction. | [NeurIPS 2017](https://doi.org/10.1063/1.5019779) |
| DimeNet | Directional Message Passing for Molecular Graphs | Directional message passing neural network leveraging inter-atomic distances and angles with spherical Bessel basis functions for molecular property prediction. | [Paper](https://arxiv.org/abs/2003.03123) |
| DimeNet++ | Fast and Uncertainty-Aware Directional Message Passing for Non-Equilibrium Molecules | Efficient DimeNet variant achieving 8× speedup through architectural optimizations while maintaining prediction accuracy. | [Paper](https://arxiv.org/abs/2011.14115) |
| PaiNN | Equivariant Message Passing for the Prediction of Tensorial Properties and Molecular Spectra | Polarizable atom interaction network using equivariant message passing to jointly update scalar and vector features for tensorial property and spectrum prediction. | [Paper](https://arxiv.org/abs/2102.03150) |
| GemNet | GemNet: Universal Directional Graph Neural Networks for Molecules | Universal directional graph neural network using geometric message passing and dihedral angle information for SOTA molecular property prediction. | [Paper](https://arxiv.org/abs/2106.08903) |
| GemNet-OC | GemNet-OC: Developing Graph Neural Networks for Large and Diverse Molecular Simulation Datasets | GemNet variant optimized for the Open Catalyst large-scale dataset with improved computational efficiency and generalization. | [Paper](https://arxiv.org/abs/2204.02782) |
| SphereNet | Spherical Message Passing for 3D Molecular Graphs | Spherical message passing network using complete spherical coordinates (distance, angle, dihedral) for 3D molecular graph representation. | [Paper](https://arxiv.org/abs/2102.05013) |
| ComENet | ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs | Complete and efficient 3D molecular message passing framework encoding all geometric information (distance, angle, torsion) while maintaining efficiency. | [NeurIPS 2022](https://arxiv.org/abs/2206.08515) |
| SEGNN | Geometric and Physical Quantities Improve E(3) Equivariant Message Passing | Steerable E(3)-equivariant graph neural network using spherical harmonics-based steerable features for equivariant message passing. | [Paper](https://arxiv.org/abs/2110.02905) |
| LEFTNet | A New Perspective on Building Efficient and Expressive 3D Equivariant Graph Neural Networks | Local equivariant frame Transformer network achieving efficient and expressive 3D equivariant graph neural networks through local reference frames. | [NeurIPS 2023](https://arxiv.org/abs/2305.07895) |
| ViSNet | ViSNet: An Equivariant Geometry-Enhanced Graph Neural Network with Vector-Scalar Interactive Message Passing | Equivariant geometry-enhanced GNN with vector-scalar interactive message passing that avoids expensive higher-order tensor operations via runtime geometric computation. | [Nature Communications](https://doi.org/10.1038/s41467-024-50014-6) |
| TorchMD-NET | TorchMD-NET: Equivariant Transformers for Neural Network Based Molecular Potentials | Equivariant Transformer framework for neural network molecular potentials, providing a unified implementation of architectures like SchNet and PaiNN. | [Paper](https://arxiv.org/abs/2202.02541) |
| EPT | An equivariant pretrained transformer for unified 3D molecular representation learning | E(3)-equivariant all-atom pretrained Transformer for unified 3D molecular representation learning across diverse scientific domains. | [Nature Communications](https://doi.org/10.1038/s41467-026-69185-7) |

---

<a id="chemistry-section-05"></a>
## Molecular Generation & Diffusion

*Generative models for de novo molecular design, 3D conformation generation, and structure-based molecule generation using diffusion, VAEs, autoregressive, and flow-based approaches.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolGPT | MolGPT: Molecular Generation Using a Transformer-Decoder Model | GPT-based molecular generation model using a Transformer decoder to autoregressively generate SMILES satisfying specific property constraints. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.1c00600) |
| cMolGPT | cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific de novo Molecular Generation | Conditional molecular GPT extending MolGPT with target-specific controls for de novo molecular generation. | [Molecules](https://doi.org/10.3390/molecules28114430) |
| REINVENT 4 | REINVENT 4: Modern AI-Driven Generative Molecule Design | Fourth-generation industrial molecular design platform from AstraZeneca integrating reinforcement learning, transfer learning, and multi-objective optimization. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.4c00120) |
| JT-VAE | Junction Tree Variational Autoencoder for Molecular Graph Generation | Variational autoencoder using junction tree decomposition to generate molecular graphs from chemical substructure building blocks, guaranteeing chemical validity. | [Paper](https://arxiv.org/abs/1802.04364) |
| MoLeR | Learning to Extend Molecular Scaffolds with Structural Motifs | Molecular generation model from Microsoft that incrementally extends molecular scaffolds with structural motifs for fragment-based molecular design. | [Paper](https://arxiv.org/abs/2103.03864) |
| GeoDiff | GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation | Geometric diffusion model for 3D molecular conformation generation within an SE(3)-equivariant framework. | [Paper](https://arxiv.org/abs/2203.02923) |
| EDM | Equivariant Diffusion for Molecule Generation in 3D | E(3)-equivariant diffusion model that directly generates atomic types and 3D coordinates in 3D space, pioneering equivariant molecular diffusion generation. | [Paper](https://arxiv.org/abs/2203.17003) |
| GDSS | Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations | Score-based graph generative model using a joint node-edge system of stochastic differential equations for diffusion-based graph generation. | [Paper](https://arxiv.org/abs/2202.02514) |
| DiGress | DiGress: Discrete Denoising Diffusion for Graph Generation | Discrete denoising diffusion model for graph generation operating directly in discrete node and edge feature space, suited for molecular graph generation. | [Paper](https://arxiv.org/abs/2209.14734) |
| GeoLDM | Geometric Latent Diffusion Models for 3D Molecule Generation | Geometric latent diffusion model performing 3D molecular generation in equivariant latent space, more efficient than direct atomic-space diffusion. | [Paper](https://arxiv.org/abs/2305.01140) |
| GFlowNet | Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation | Flow network-based generative model learning proportional sampling strategies from energy functions for diverse molecular candidate generation. | [Paper](https://arxiv.org/abs/2106.04399) |
| TacoGFN | TacoGFN: Target-Conditioned GFlowNet for Structure-Based Drug Design | Target-conditioned GFlowNet incorporating protein pocket structural information for structure-based drug molecule generation. | [Paper](https://arxiv.org/abs/2310.03223) |
| GenMol | GenMol: A Drug Discovery Generalist with Discrete Diffusion | General-purpose molecular generation model from NVIDIA using masked discrete diffusion over SAFE representations for multi-stage drug discovery. | [Paper](https://arxiv.org/abs/2501.06158) |
| NExT-Mol | NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | Foundation model integrating 1D SELFIES language modeling with 3D diffusion for 3D molecule generation. | [ICLR 2025](https://openreview.net/forum?id=tbo1Svjrxz) |
| Torsional Diffusion | Torsional Diffusion for Molecular Conformer Generation | Diffusion model operating on torsion angles for efficient and accurate molecular conformer generation. | [NeurIPS 2022](https://arxiv.org/abs/2206.01729) |
| ConfGF | Learning Gradient Fields for Molecular Conformation Generation | Gradient field learning approach for molecular conformation generation from 2D molecular graphs to stable 3D structures. | [Paper](https://arxiv.org/abs/2105.03902) |
| DMCG | Direct Molecular Conformation Generation | Direct method for generating 3D molecular conformations by predicting atomic coordinates without intermediate distance geometry. | [Paper](https://arxiv.org/abs/2202.01356) |
| DiTMC | Sampling 3D Molecular Conformers with Diffusion Transformers | Diffusion Transformer framework for sampling accurate 3D molecular conformers integrating discrete molecular graphs with continuous coordinates. | [Paper](https://arxiv.org/abs/2506.15378) |
| SynCoGen | Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling | Framework for synthesizable 3D molecule generation that jointly models molecular building blocks, chemical reactions, and atomic coordinates. | [Paper](https://arxiv.org/abs/2507.11818) |

---

<a id="chemistry-section-06"></a>
## Spectroscopy & Analytical Chemistry

*Foundation models for interpreting and predicting molecular spectra including NMR, IR, Raman, and mass spectrometry.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolSpectLLM | MolSpectLLM: A Large Language Model for Molecular Spectroscopy Interpretation | Large language model for molecular spectroscopy interpretation, linking NMR, IR, and MS spectral data to molecular structures for spectrum-to-structure reasoning. | [Paper](https://arxiv.org/abs/2502.13094) |
| MACE4IR | MACE4IR: Machine Learning Interatomic Potentials for Infrared Spectroscopy Prediction | Equivariant graph neural network based on MACE for infrared spectroscopy prediction using machine-learned interatomic potentials. | [Paper](https://arxiv.org/abs/2503.08205) |
| Vib2Mol | Vib2Mol: From Vibrational Spectra to Molecular Structures | Deep learning model that infers molecular structures directly from IR/Raman vibrational spectra. | [Paper](https://arxiv.org/abs/2504.01187) |
| FIDDLE | FIDDLE: a deep learning method for chemical formulas prediction from tandem mass spectra | Deep learning method predicting chemical molecular formulas from tandem mass spectrometry data, trained on 38,000+ molecules and 1M spectra. | [Nature Communications](https://doi.org/10.1038/s41467-025-66060-9) |
| NMRTrans | NMRTrans: Structure Elucidation from Experimental NMR Spectra via Set Transformers | Set Transformer model for molecular structure elucidation from experimental NMR spectra. | [Paper](https://arxiv.org/abs/2602.10158) |

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
| HELENA | Hierarchical Moiety-Aware Graph Transformer for Li-metal Electrolyte Formulation Design | Hierarchical moiety-aware graph Transformer for lithium-metal battery electrolyte formulation optimization. | [chemRxiv](https://doi.org/10.26434/chemrxiv-2025-c0ttj-v3) |
