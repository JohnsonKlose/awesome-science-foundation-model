# Materials Science

<p align="right"><strong>Language:</strong> English | <a href="materials-science_zh.md">中文</a></p>

> Universal atomic models, atomistic force fields, crystal and materials generation, catalysts, batteries, alloys, polymers, and related materials foundation models.
> [Index](../README.md)

## Table of Contents
- [Atomistic Force Fields](#materials-science-section-01)
- [Crystal & Materials Property](#materials-science-section-02)
- [Universal Atomic Models](#materials-science-section-03)
- [Crystal Structure Generation & Inverse Design](#materials-science-section-04)
- [Catalyst & Surface Models](#materials-science-section-05)
- [Electronic Structure Prediction](#materials-science-section-06)
- [Polymer & Soft Matter](#materials-science-section-07)
- [Battery & Energy Materials](#materials-science-section-08)
- [Foundational GNN Architectures](#materials-science-section-09)
- [Metamaterials](#materials-science-section-10)
- [Superconductors](#materials-science-section-11)

<a id="materials-science-section-01"></a>
## Atomistic Force Fields
*Machine-learned interatomic potentials for molecular dynamics simulations.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MACE | MACE: Higher Order Equivariant Message Passing Neural Networks for Fast and Accurate Force Fields | Higher-order equivariant message passing framework using atomic cluster expansion for accurate and efficient force field computation. | [NeurIPS 2022](https://papers.nips.cc/paper_files/paper/2022/hash/4a36c3c51af11ed9f34615b81edb5bbc-Abstract-Conference.html) |
| MACE-MP-0 | A Foundation Model for Atomistic Materials Chemistry | Pre-trained universal force field covering 89 elements, trained on Materials Project data for general materials chemistry simulation. | [J. Chem. Phys.](https://doi.org/10.1063/5.0297006) |
| CHGNet | CHGNet as a Pretrained Universal Neural Network Potential for Charge-Informed Atomistic Modelling | Pre-trained universal graph neural network potential with charge information, trained on Materials Project DFT data. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00716-3) |
| M3GNet | A Universal Graph Deep Learning Interatomic Potential for the Periodic Table | Universal graph deep learning interatomic potential trained on Materials Project relaxation data, covering all periodic table elements. | [Nature Computational Science](https://doi.org/10.1038/s43588-022-00349-3) |
| SevenNet | SevenNet: Scalable Graph Neural Network Interatomic Potential | Scalable GNN interatomic potential based on NequIP architecture with LAMMPS parallel MD support. | [J. Chem. Theory Comput.](https://doi.org/10.1021/acs.jctc.4c00190) |
| Orb | Orb: A Fast, Scalable Neural Network Potential | Fast and scalable neural network potential by Orbital Materials, 3–6× faster than existing universal potentials while maintaining SOTA accuracy. | [arXiv](https://arxiv.org/abs/2410.22570) |
| NequIP | E(3)-Equivariant Graph Neural Networks for Data-Efficient and Accurate Interatomic Potentials | E(3)-equivariant GNN using equivariant convolutions instead of invariant descriptors, achieving high accuracy with minimal training data. | [Nature Communications](https://doi.org/10.1038/s41467-022-29939-5) |
| Allegro | Learning Local Equivariant Representations for Large-Scale Atomistic Dynamics | Highly scalable E(3)-equivariant architecture using local equivariant representations to support large-scale molecular dynamics. | [Nature Communications](https://doi.org/10.1038/s41467-023-36329-y) |
| Allegro-FM | Allegro-FM: Toward an Equivariant Foundation Model for Exascale Molecular Dynamics Simulations | Equivariant foundation model targeting exascale molecular dynamics simulations based on the Allegro architecture. | [J. Phys. Chem. Lett.](https://doi.org/10.1021/acs.jpclett.5c00605) |
| DPA-2 | DPA-2: A Large Atomic Model as a Multi-task Learner | Large-scale Deep Potential multi-task atomic model pre-trained across diverse chemical and materials systems with fine-tuning support. | [npj Computational Materials](https://doi.org/10.1038/s41524-024-01493-2) |
| ANI-1 | ANI-1: An Extensible Neural Network Potential with DFT Accuracy at Force Field Computational Cost | Pioneering extensible neural network potential achieving DFT accuracy at force-field computational cost for H/C/N/O organic molecules. | [Chemical Science](https://doi.org/10.1039/C6SC05720A) |
| ANI-2x | Extending the Applicability of the ANI Deep Learning Molecular Potential to Sulfur and Halogens | Extension of ANI to sulfur and halogens (F/Cl), broadening coverage to a wider organic molecular space. | [J. Chem. Theory Comput.](https://doi.org/10.1021/acs.jctc.0c00121) |
| AIMNet2 | AIMNet2: A Neural Network Potential to Meet Your Neutral, Charged, Organic, and Elemental-Organic Needs | Highly transferable neural network potential supporting neutral and charged organic molecules across 14 elements. | [Chemical Science](https://doi.org/10.1039/D4SC08572H) |
| GRACE | Graph Atomic Cluster Expansion | Universal MLIP framework based on graph atomic cluster expansion, covering 97 elements. | [npj Comp. Mater.](https://doi.org/10.1038/s41524-025-01504-w) |
| Orb-v3 | Orb-v3: Atomistic Simulation at Scale | Major upgrade of Orb with improved accuracy and efficiency for large-scale atomistic simulation. | [arXiv](https://arxiv.org/abs/2504.06231) |
| PET-MAD | Lightweight universal interatomic potential for advanced materials | Lightweight universal interatomic potential covering the full periodic table for advanced materials simulations. | [Nature Communications](https://doi.org/10.1038/s41467-025-58678-8) |
| Grappa | Machine-learned molecular mechanics via E(3)-equivariant neural networks | E(3)-equivariant neural network approach to machine-learned molecular mechanics force fields. | [Chemical Science](https://doi.org/10.1039/D4SC05730A) |

---

<a id="materials-science-section-02"></a>
## Crystal & Materials Property
*Predicting physical, electronic, and structural properties of crystalline and molecular materials.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CGCNN | Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties | Pioneering crystal graph convolutional neural network for direct, interpretable prediction of material properties from crystal structures. | [Physical Review Letters](https://doi.org/10.1103/PhysRevLett.120.145301) |
| MEGNet | Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals | Universal materials graph network supporting property prediction for both molecules and crystals with global state features. | [Chemistry of Materials](https://doi.org/10.1021/acs.chemmater.9b01294) |
| ALIGNN | Atomistic Line Graph Neural Network for Improved Materials Property Predictions | NIST atomistic line graph neural network that explicitly models bond angles, outperforming CGCNN and MEGNet. | [npj Computational Materials](https://doi.org/10.1038/s41524-021-00650-1) |
| MultiMat | Multimodal Foundation Models for Material Property Prediction and Discovery | Multimodal foundation model integrating crystal structure, density of states, charge density, and text for comprehensive materials property prediction. | [Newton](https://doi.org/10.1016/j.newton.2025.100016) |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | IBM large-scale SMILES encoder-decoder model pre-trained on 91M PubChem SMILES for materials and chemistry applications. | [ICLR 2024 Workshop](https://openreview.net/forum?id=smi-ted) |
| DARWIN 1.5 | DARWIN 1.5: Large Language Models as Materials Science Adapted Learners | Open-source materials science LLM that predicts material properties and facilitates discovery from natural language input. | [arXiv](https://arxiv.org/abs/2412.11970) |
| MatBERT | Quantifying the Advantage of Domain-Specific Pre-training on Named Entity Recognition Tasks in Materials Science | BERT model pre-trained on materials science literature (LBNL), outperforming general models on materials NLP tasks. | [Patterns](https://doi.org/10.1016/j.patter.2022.100488) |
| MatSciBERT | MatSciBERT: A Materials Domain Language Model for Text Mining and Information Extraction | Domain-specific BERT trained on materials science literature for enhanced text mining and information extraction. | [npj Computational Materials](https://doi.org/10.1038/s41524-022-00784-w) |
| MOFTransformer | A Multi-modal Pre-training Transformer for Universal Transfer Learning in Metal-Organic Frameworks | Multi-modal pre-trained Transformer for MOF property prediction, trained on 1M hypothetical MOFs with atomic graph and energy grid embeddings. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00628-2) |
| CrystalFormer | Space Group Informed Transformer for Crystalline Materials Generation | Autoregressive Transformer guided by space group symmetry and Wyckoff positions for crystalline materials generation. | [Science Bulletin](https://doi.org/10.1016/j.scib.2024.07.032) |
| MatInFormer | Materials Informatics Transformer: A Language Model for Interpretable Materials Properties Prediction | Materials informatics Transformer leveraging LLM techniques for interpretable materials property prediction. | [arXiv](https://arxiv.org/abs/2308.16259) |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | Knowledge-guided graph Transformer pre-training framework using chemical knowledge to enhance molecular representation learning. | [Nature Communications](https://doi.org/10.1038/s41467-023-43214-1) |
| Matformer | Periodic Graph Transformers for Crystal Material Property Prediction | Periodic graph Transformer with periodicity-aware multi-graph attention for crystal material property prediction. | [NeurIPS 2022](https://papers.nips.cc/paper_files/paper/2022/hash/6145c70a4a4bf353a31ac5496a72a72d-Abstract-Conference.html) |
| PotNet | Complete and Efficient Graph Transformers for Crystal Material Property Prediction | Complete and efficient crystal graph Transformer achieving full graph representation via interatomic potential information. | [ICLR](https://openreview.net/forum?id=BnQY9XiRAS) |
| LLM-Prop | LLM-Prop: Predicting Physical And Electronic Properties of Crystalline Solids From Their Text Descriptions | Uses large language models to predict physical and electronic properties of crystals from text descriptions. | [arXiv](https://arxiv.org/abs/2310.14029) |
| EScAIP | EScAIP: Efficiently Scaled Attention Interatomic Potential | Efficiently scaled attention-based interatomic potential achieving high accuracy and scalability for materials property prediction. | [ICLR](https://arxiv.org/abs/2411.15019) |
| AlloyGPT | End-to-end prediction and design of additively manufacturable alloys | Autoregressive language model for end-to-end alloy design and property prediction. | [npj Computational Materials](https://doi.org/10.1038/s41524-025-01768-2) |
| aLLoyM | aLLoyM: a large language model for alloy phase diagram prediction | Large language model for predicting alloy phase diagrams. | [npj Computational Materials](https://doi.org/10.1038/s41524-026-01966-6) |
| MaskTerial | MaskTerial: a foundation model for automated 2D material flake detection | Foundation model for automated detection of 2D material flakes. | [Digital Discovery](https://doi.org/10.1039/D5DD00156K) |
| CLOUD | Scalable physics-informed foundation model for crystal representation | Scalable physics-informed crystal representation foundation model trained on 6M+ crystal structures. | [Nature Communications](https://doi.org/10.1038/s41467-026-57867-x) |
| LLaMat | Large language models for materials science | Family of large language models adapted for materials science tasks. | [Nature MI](https://doi.org/10.1038/s42256-026-00964-9) |

---

<a id="materials-science-section-03"></a>
## Universal Atomic Models
*Large-scale pre-trained models spanning molecules, materials, and catalysts across the periodic table.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| UMA | UMA: A Family of Universal Models for Atoms | Meta FAIR universal atomic model family trained on 500M+ 3D atomic structures spanning molecules, materials, and catalysts. | [NeurIPS](https://arxiv.org/abs/2506.23971) |
| Zatom-1 | Zatom-1: A Multimodal Flow Foundation Model for 3D Molecules and Materials | Open-source multimodal flow foundation model unifying generation and prediction for 3D molecules and materials. | [arXiv](https://arxiv.org/abs/2602.22251) |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Large-scale molecular foundation model family (Molecular Insight SMILES Transformers) predicting 400+ structure-property relationships. | [arXiv](https://arxiv.org/abs/2510.18900) |
| MatterSim | MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures | Microsoft deep learning atomic model covering all elements at 0–5000 K and 0–1000 GPa. | [arXiv](https://arxiv.org/abs/2405.04967) |
| GNoME | Scaling Deep Learning for Materials Discovery | Google DeepMind GNN materials explorer discovering 2.2M new stable inorganic crystal structures. | [Nature](https://doi.org/10.1038/s41586-023-06735-9) |
| JMP | From Molecules to Materials: Pre-training Large Generalizable Models for Atomic Property Prediction | Meta FAIR joint multi-domain pre-training on ~120M atomic systems spanning molecules and materials. | [ICLR](https://openreview.net/forum?id=PfPnugdxup) |
| ATOMICA | Learning Universal Representations of Intermolecular Interactions with ATOMICA | Geometric deep learning model learning universal atomic-level representations of intermolecular interactions. | [bioRxiv](https://doi.org/10.1101/2025.04.02.646906) |
| eSEN | Efficient Scalable Equivariant Networks | Scalable equivariant architecture forming the backbone of UMA, achieving SOTA on molecular and materials benchmarks. | [arXiv](https://arxiv.org/abs/2501.02063) |

---

<a id="materials-science-section-04"></a>
## Crystal Structure Generation & Inverse Design
*Generative models for discovering and designing novel crystal structures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CDVAE | Crystal Diffusion Variational Autoencoder for Periodic Material Generation | Crystal diffusion VAE combining diffusion processes with VAE for end-to-end stable periodic crystal structure generation. | [ICLR](https://openreview.net/forum?id=03RLpj-tc_) |
| DiffCSP | Crystal Structure Prediction by Joint Equivariant Diffusion | Joint equivariant diffusion model simultaneously diffusing atom coordinates and lattice parameters for crystal structure prediction. | [NeurIPS 2023](https://papers.nips.cc/paper_files/paper/2023/hash/38b787fc530d0b31825827e2cc306656-Abstract-Conference.html) |
| SyMat | Towards Symmetry-Aware Generation of Periodic Materials | Symmetry-aware periodic material generation model explicitly leveraging space group symmetry constraints. | [NeurIPS 2023](https://papers.nips.cc/paper_files/paper/2023/hash/a73474c359ed523e6cd3174ed29a4d56-Abstract-Conference.html) |
| MatterGen | MatterGen: A Generative Model for Inorganic Materials Design | Microsoft diffusion model for inverse design of inorganic crystals conditioned on chemistry, symmetry, and property constraints. | [Nature](https://doi.org/10.1038/s41586-025-08628-5) |
| Crystal-GFN | Crystal-GFN: Sampling Crystals with Desirable Properties and Constraints | GFlowNet-based crystal sampling framework that efficiently explores crystal space under property and composition constraints. | [arXiv](https://arxiv.org/abs/2310.04925) |
| FlowMM | FlowMM: Generating Materials with Riemannian Flow Matching | Riemannian flow matching on crystal manifolds for geometry-aware materials structure generation. | [ICML](https://proceedings.mlr.press/v235/miller24a.html) |
| FlowLLM | FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions | Combines LLM base distributions with flow matching, leveraging chemical priors for improved crystal generation. | [NeurIPS 2024](https://papers.nips.cc/paper_files/paper/2024/hash/51d317df78eded9eb3c9d3fb1091c279-Abstract-Conference.html) |
| CrystalFlow | CrystalFlow: A Flow-Based Generative Model for Crystalline Materials | Flow-based generative model achieving high-fidelity crystal structure generation via normalizing flows. | [Nature Communications](https://doi.org/10.1038/s41467-025-64364-4) |
| WyckoffDiff | WyckoffDiff: Diffusion in the Wyckoff Space for Crystal Structure Generation | Diffusion model operating in Wyckoff position space with symmetry-aware representations for improved structural validity. | [ICML](https://arxiv.org/abs/2502.03035) |
| MatterGPT | MatterGPT: A Generative Transformer for Multi-Property Inverse Design of Solid-State Materials | Autoregressive Transformer supporting multi-property conditioned inverse design of solid-state materials. | [arXiv](https://arxiv.org/abs/2408.07608) |
| CrystaLLM | CrystaLLM: Large Language Model for Crystallography | LLM that generates crystal structures directly from CIF text without explicit geometric encoding. | [Nature Communications](https://doi.org/10.1038/s41467-024-54639-7) |
| UniMat | Scalable Diffusion for Materials Generation | Scalable diffusion model for crystal materials generation with a unified representation across varying crystal sizes. | [ICLR](https://openreview.net/forum?id=wm4WlHoXpC) |
| DAO-G / DAO-P | Siamese Foundation Models for Crystal Structure Prediction | Siamese pre-training framework: DAO-G for crystal generation and DAO-P for property prediction. | [arXiv](https://arxiv.org/abs/2503.10471) |
| MOFGPT | Transformer-based generative model for de novo MOF design | Transformer generative model for de novo design of metal-organic frameworks. | [arXiv](https://arxiv.org/abs/2506.00198) |
| Matra-Genoa | Autoregressive generative material Transformer | Autoregressive Transformer for generative materials design. | [npj Comp. Mater.](https://doi.org/10.1038/s41524-026-01550-8) |

---

<a id="materials-science-section-05"></a>
## Catalyst & Surface Models
*Models for catalytic reaction prediction, adsorption energies, and surface chemistry.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AdsorbML | AdsorbML: A Leap in Efficiency for Adsorption Energy Calculations using Generalizable Machine Learning Potentials | Generalizable ML potentials for efficient adsorption energy calculation, accelerating catalyst screening with OC20 pre-trained models. | [npj Computational Materials](https://doi.org/10.1038/s41524-023-01121-5) |
| CatBERTa | CatBERTa: A RoBERTa-based Catalyst Property Prediction Model | RoBERTa-based model predicting catalyst adsorption energies and activities from textual descriptions. | [arXiv](https://arxiv.org/abs/2305.08628) |
| GemNet-OC | GemNet-OC: Developing Graph Neural Networks for Large and Diverse Molecular Simulation Datasets | GemNet variant optimized for Open Catalyst datasets, achieving SOTA on large-scale catalyst simulations. | [npj Computational Materials](https://doi.org/10.1038/s41524-022-00891-8) |
| eSCN | Reducing SO(3) Convolutions to SO(2) for Efficient Equivariant GNNs | Efficient equivariant spherical channel network reducing SO(3) to SO(2) convolutions for major computational speedup. | [ICML](https://proceedings.mlr.press/v202/passaro23a.html) |
| SCN | Spherical Channels for Modeling Atomic Interactions | Spherical channel network using spherical harmonics for atomic interaction modeling, excelling on OC20 catalyst tasks. | [NeurIPS 2022](https://papers.nips.cc/paper_files/paper/2022/hash/3501bea1ac61fedbaaff2f88e5fa9447-Abstract-Conference.html) |
| EquiformerV2 | EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations | Improved equivariant Transformer supporting higher-degree representations, achieving SOTA on OC20/OC22 benchmarks. | [ICLR](https://openreview.net/forum?id=mCOBKZmrzD) |
| eqV2 | Improved EquiformerV2 for OC20/OC22 | Improved EquiformerV2 variant for general atomic property prediction on Open Catalyst datasets. | [arXiv](https://arxiv.org/abs/2401.13013) |
| CatDRX | Reaction-conditioned generative model for catalyst design | Reaction-conditioned generative model for designing catalysts tailored to specific reactions. | [Comms. Chem.](https://doi.org/10.1038/s42004-025-01462-y) |

---

<a id="materials-science-section-06"></a>
## Electronic Structure Prediction
*Deep learning models for predicting DFT Hamiltonians and electronic properties.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DeepH | Deep-Learning Density Functional Theory Hamiltonian for Efficient ab initio Electronic-Structure Calculation | Deep learning model that directly predicts DFT Hamiltonian matrices to accelerate ab initio electronic structure calculations. | [Nature Computational Science](https://doi.org/10.1038/s43588-022-00265-6) |
| DeepH-E3 | DeepH-E3: E(3)-Equivariant Deep Learning for Efficient ab initio Electronic Structure | E(3)-equivariant version of DeepH for more accurate and efficient Hamiltonian matrix element prediction. | [Nature Communications](https://doi.org/10.1038/s41467-023-38468-8) |
| HamGNN | HamGNN: Graph Neural Networks for Predicting Hamiltonian Matrix | Graph neural network for Hamiltonian matrix prediction via equivariant message passing at DFT-level accuracy. | [arXiv](https://arxiv.org/abs/2305.10844) |
| NextHAM | NextHAM: Next-Generation Hamiltonian Prediction with Equivariant Graph Neural Networks | Next-generation equivariant GNN for electronic structure prediction of larger-scale materials systems. | [arXiv](https://arxiv.org/abs/2405.14788) |
| MACE-H | MACE-based GNN for equivariant electronic Hamiltonian prediction | MACE-based equivariant GNN for predicting electronic Hamiltonians. | [npj Comp. Mater.](https://doi.org/10.1038/s41524-026-01600-9) |

---

<a id="materials-science-section-07"></a>
## Polymer & Soft Matter
*Language models and graph networks for polymer informatics and design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| polyBERT | polyBERT: A Chemical Language Model to Enable Fully Machine-Driven Ultrafast Polymer Informatics | BERT-based chemical language model trained on polymer SMILES for ultrafast polymer property prediction. | [Nature Communications](https://doi.org/10.1038/s41467-023-39868-6) |
| polyGNN | polyGNN: Multitask Graph Neural Networks for Polymer Informatics | Multitask graph neural network for simultaneous polymer property prediction and structure-property learning. | [Chemistry of Materials](https://doi.org/10.1021/acs.chemmater.2c02991) |
| polyBART | polyBART: A Generative Transformer for Polymer Design | BART-based generative Transformer for conditional polymer generation and property-guided inverse design. | [arXiv](https://arxiv.org/abs/2404.02535) |
| POLYT5 | Encoder-decoder foundation chemical language model for polymer design | T5 encoder-decoder foundation chemical language model for polymer design. | [npj AI](https://doi.org/10.1038/s44335-026-00013-5) |

---

<a id="materials-science-section-08"></a>
## Battery & Energy Materials
*Pre-trained models for battery research, electrode materials, and energy storage.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BatteryBERT | BatteryBERT: A Pretrained Language Model for Battery Research | BERT fine-tuned on battery literature for text mining and information extraction in battery research. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.2c00035) |
| BatteryFormer | BatteryFormer: Graph Transformer for Battery Material Property Prediction | Graph Transformer predicting battery electrode capacity, voltage, and cycle life properties. | [arXiv](https://arxiv.org/abs/2404.07862) |

---

<a id="materials-science-section-09"></a>
## Foundational GNN Architectures
*Foundational graph neural network architectures underlying many materials science models.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SchNet | SchNet: A Continuous-Filter Convolutional Neural Network for Modeling Quantum Interactions | Pioneering continuous-filter convolutional network encoding interatomic distances as continuous representations for quantum interactions. | [NeurIPS](https://proceedings.neurips.cc/paper/2017/hash/303ed4c69846ab36c2904d3ba8573050-Abstract.html) |
| DimeNet | Directional Message Passing for Molecular Graphs | Directional message passing network using bond angle information for 3D geometry-aware molecular property prediction. | [ICLR](https://openreview.net/forum?id=B1eWbxStPH) |
| PaiNN | Equivariant Message Passing for the Prediction of Tensorial Properties and Molecular Spectra | Polarizable atom interaction network using equivariant message passing for tensorial property and spectra prediction. | [ICML](https://proceedings.mlr.press/v139/schutt21a.html) |
| GemNet | GemNet: Universal Directional Graph Neural Networks for Molecules | Universal directional GNN using dihedral angles for complete geometric representation in molecular property prediction. | [NeurIPS](https://proceedings.neurips.cc/paper/2021/hash/35cf8659cfcb13224cbd47863a34fc58-Abstract.html) |
| TorchMD-NET | TorchMD-NET: Equivariant Transformers for Neural Network Potentials | Modular equivariant Transformer framework for neural network potentials supporting diverse materials simulation tasks. | [ICLR 2022 Workshop](https://arxiv.org/abs/2202.02541) |

---

<a id="materials-science-section-10"></a>
## Metamaterials
*Foundation models for metamaterial structure-property relationships.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MetaFO | Toward a robust and generalizable metamaterial foundation model | Bayesian Transformer metamaterial foundation model for zero-shot structure-property prediction. | [npj Computational Materials](https://doi.org/10.1038/s41524-025-01925-7) |

---

<a id="materials-science-section-11"></a>
## Superconductors
*Models for predicting superconducting properties and critical temperatures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BEE-NET | Developing a complete AI-accelerated workflow for superconductor discovery | Equivariant GNN predicting Eliashberg spectral functions and critical temperatures for superconductor discovery. | [npj Computational Materials](https://doi.org/10.1038/s41524-026-01964-8) |
| DeeperBand | A deep learning approach to search for superconductors from electronic bands | Symmetry-aware 3D Vision Transformer predicting superconductivity from electronic band structures. | [IOPscience](https://doi.org/10.1088/3050-287X/adf6cb) |
