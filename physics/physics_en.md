# Physics

<p align="right"><strong>Language:</strong> English | <a href="physics_zh.md">中文</a></p>

> PDE solvers, fluid dynamics, quantum systems, particle physics, plasma physics, optics, scientific simulation, and related physics foundation models.
> [Index](../README.md)

## Table of Contents
- [Particle Physics](#physics-section-01)
- [Fluid Dynamics & PDE Solving](#physics-section-02)
- [General Physics Simulation](#physics-section-03)
- [World Models](#physics-section-04)
- [Quantum Physics & Many-Body Systems](#physics-section-05)
- [Plasma Physics & Fusion](#physics-section-06)
- [Optics & Photonics](#physics-section-07)
- [Structure-Preserving & Geometric Physics ML](#physics-section-08)
- [Quantum Chemistry & Electronic Structure](#physics-section-09)
- [Combustion Simulation](#physics-section-10)
- [Nuclear Engineering](#physics-section-11)

<a id="physics-section-01"></a>
## Particle Physics
*Foundation models and deep learning architectures for jet tagging, particle tracking, and collider event analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FM4NPP | A Scaling Foundation Model for Nuclear and Particle Physics | Large-scale self-supervised foundation model for sparse detector data, trained on 11M+ collision events achieving SOTA on sPHENIX experiments. | [ICLR](https://arxiv.org/abs/2508.14087) |
| OmniLearn | OmniLearn: A Method to Simultaneously Facilitate All Jet Physics Tasks | Multi-task jet physics foundation model learning universal representations via multi-class classification pre-training. | [arXiv](https://arxiv.org/abs/2404.16091) |
| OmniLearned | Foundation Model Framework for All Tasks Involving Jet Physics | Upgraded OmniLearn framework trained on 1B+ jet events with Transformer architecture for jet classification, regression, and generation. | [Physical Review D](https://arxiv.org/abs/2510.24066) |
| OmniJet-α | OmniJet-α: The first cross-task foundation model for particle physics | First cross-task particle physics foundation model supporting both jet generation and jet tagging. | [Machine Learning: Science and Technology](https://arxiv.org/abs/2403.05618) |
| Bumblebee | Bumblebee: Foundation Model for Particle Physics Discovery | BERT-inspired particle physics foundation model embedding four-momentum vectors without positional encoding to capture generative and reconstruction-level information. | [NeurIPS 2024 Workshop](https://arxiv.org/abs/2412.07867) |
| EveNet | EveNet: A Foundation Model for Particle Collision Data Analysis | Event-level collision data foundation model pre-trained on 500M simulated events with hybrid self-supervised learning for multi-task analysis. | [arXiv](https://arxiv.org/abs/2601.17126) |
| HEP-JEPA | HEP-JEPA: A foundation model for collider physics using joint embedding predictive architecture | Collider physics foundation model using joint embedding predictive architecture (JEPA) for self-supervised jet tagging. | [arXiv](https://arxiv.org/abs/2502.03933) |
| Particle Transformer | Particle Transformer for Jet Tagging | Transformer-based jet tagging architecture with pairwise particle interaction features, excelling on the JetClass dataset. | [arXiv](https://arxiv.org/abs/2202.03772) |
| PELICAN | Explainable Equivariant Neural Networks for Particle Physics: PELICAN | Permutation-equivariant and Lorentz-invariant aggregation network for explainable jet tagging and reconstruction. | [Journal of High Energy Physics](https://arxiv.org/abs/2307.16506) |
| LorentzNet | An Efficient Lorentz Equivariant Graph Neural Network for Jet Tagging | Efficient Lorentz-equivariant GNN that respects spacetime symmetries for high-performance jet tagging. | [Journal of High Energy Physics](https://arxiv.org/abs/2201.08187) |
| ParticleNet | ParticleNet: Jet Tagging via Particle Clouds | Influential GNN treating jets as particle clouds using EdgeConv for jet classification. | [Phys. Rev. D](https://arxiv.org/abs/1902.08570) |
| JetCLR | Symmetries, Safety, and Self-Supervision | Contrastive self-supervised jet representation learning framework using permutation-invariant Transformer encoder with symmetry augmentation. | [SciPost Phys.](https://arxiv.org/abs/2108.04253) |
| ABCNet | ABCNet: An attention-based method for particle tagging | Attention-enhanced GNN treating collider data as point clouds for quark/gluon tagging. | [EPJ Plus](https://arxiv.org/abs/2001.05311) |
| JEDI-net | JEDI-net: a jet identification algorithm based on interaction networks | Deep learning jet identification via interaction networks modeling pairwise particle interactions. | [EPJ C 2020](https://arxiv.org/abs/1908.05318) |
| CaloFM | Foundation Model for Calorimetry via MoE | Mixture-of-experts foundation model for calorimeter simulation. | [arXiv](https://arxiv.org/abs/2603.28804) |
| CaloDREAM | Detector Response Emulation via Attentive Flow Matching | High-fidelity fast calorimeter simulation using attentive flow matching. | [SciPost Phys.](https://arxiv.org/abs/2405.09629) |
| JetFormer | Scalable Transformer for Jet Tagging | Scalable Transformer architecture for jet tagging. | [arXiv](https://arxiv.org/abs/2601.17215) |
| PanopTag | PanopTag: Simultaneously Tagging All Jets in a Particle Collision Event | First method to simultaneously tag all jets in a collision event using encoder-decoder Transformer with event-level context. | [arXiv](https://arxiv.org/abs/2601.16417) |
| GN2 | Transforming jet flavour tagging at ATLAS | ATLAS Transformer graph neural network for jet flavour tagging, dramatically improving b-jet identification. | [Nature Comm.](https://arxiv.org/abs/2505.19689) |
| TrackingBERT | A Language Model for Particle Tracking | BERT-based foundation model for particle track reconstruction by tokenizing detector data for LHC tracking. | [arXiv](https://arxiv.org/abs/2402.10239) |

---

<a id="physics-section-02"></a>
## Fluid Dynamics & PDE Solving
*Neural operators and foundation models for solving partial differential equations and fluid simulations.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FNO | Fourier Neural Operator for Parametric Partial Differential Equations | Pioneering neural operator learning function mappings in Fourier space, resolution-independent and efficient for parametric PDEs. | [arXiv](https://arxiv.org/abs/2010.08895) |
| DeepONet | Learning nonlinear operators via DeepONet based on the universal approximation theorem of operators | Deep operator network with branch/trunk architecture learning continuous nonlinear operators for PDE solving. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-021-00302-5) |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators | NVIDIA high-resolution global weather model based on adaptive Fourier neural operators at 0.25° resolution. | [arXiv](https://arxiv.org/abs/2202.11214) |
| Poseidon | Poseidon: Efficient Foundation Models for PDEs | Efficient PDE foundation model using multi-scale operator Transformer with temporal conditional layer normalization. | [NeurIPS 2024](https://arxiv.org/abs/2405.19101) |
| MPP | Multiple Physics Pretraining for Physical Surrogate Models | Task-agnostic Transformer pre-trained autoregressively on multiple spatiotemporal physical systems for enhanced generalization. | [NeurIPS](https://arxiv.org/abs/2310.02994) |
| ICON / ICON-LM | In-context operator learning with data prompts for differential equation problems | In-context operator learning network solving multiple PDE families via data prompts without retraining. | [PNAS 2023](https://doi.org/10.1073/pnas.2310142120) |
| VICON | VICON: Vision In-Context Operator Networks for Multi-Physics Fluid Dynamics | Vision in-context operator network applying Vision Transformer to multi-physics fluid dynamics prediction. | [arXiv](https://arxiv.org/abs/2411.16063) |
| DPOT | DPOT: Auto-Regressive Denoising Operator Transformer for Large-Scale PDE Pre-Training | Autoregressive denoising operator Transformer with Fourier attention for large-scale PDE pre-training. | [ICML](https://arxiv.org/abs/2403.03542) |
| PROSE-PDE | Towards a Foundation Model for Partial Differential Equations: Multi-Operator Learning and Extrapolation | Multimodal PDE foundation model supporting multi-operator learning, extrapolation, and equation identification. | [Phys. Rev. E](https://arxiv.org/abs/2404.12355) |
| PROSE-FD | PROSE-FD: A Multimodal PDE Foundation Model for Learning Fluid Dynamics | Multimodal zero-shot PDE foundation model for shallow water and Navier-Stokes equations across varied geometries. | [arXiv](https://arxiv.org/abs/2409.09811) |
| OmniArch | OmniArch: Building Foundation Model for Scientific Computing | Multi-scale multi-physics scientific computing foundation model with Fourier encoder-decoder supporting 1D/2D/3D PDE simulation. | [ICML](https://arxiv.org/abs/2402.16014) |
| Unisolver | Unisolver: PDE-Conditional Transformers Are Universal PDE Solvers | Universal PDE solver using PDE-conditioned Transformer pre-trained with equation, coefficient, and boundary condition information. | [NeurIPS](https://arxiv.org/abs/2405.17527) |
| PINO | Physics-Informed Neural Operator for Learning Partial Differential Equations | Physics-informed neural operator combining data-driven and physical constraint losses to learn PDE solution operators with minimal labeled data. | [ACM / IMS Journal of Data Science](https://arxiv.org/abs/2111.03794) |
| PI-MFM | PI-MFM: Physics-informed multimodal foundation model for solving partial differential equations | Physics-informed multimodal foundation model embedding physical priors to reduce data dependency for PDE solving. | [arXiv](https://arxiv.org/abs/2512.23056) |
| Walrus | Walrus: A Cross-Domain Foundation Model for Continuum Dynamics | 1.3B-parameter cross-domain continuum dynamics foundation model pre-trained on 19 physical systems covering fluids and solids. | [arXiv](https://arxiv.org/abs/2511.15684) |
| DISCO | DISCO: Distributional Synthesis of Compositional Operators | Distributional compositional operator synthesis method for efficient PDE solving and generalization. | [ICML 2025](https://proceedings.mlr.press/v235/disco) |
| LFNO | Latent Fourier Neural Operator | Latent-space Fourier neural operator performing transforms in low-dimensional space for improved efficiency. | [arXiv](https://arxiv.org/abs/2404.10317) |
| RNO | Recurrent Neural Operator | Recurrent neural operator combining recurrent structure with operator learning for temporal PDE dynamics. | [arXiv](https://arxiv.org/abs/2402.07718) |
| MINO | Masked Implicit Neural Operator | Masked implicit neural operator using masking strategies to enhance generalization in operator learning. | [arXiv](https://arxiv.org/abs/2401.08871) |
| TNO | Transolver / Transformer Neural Operator | Transformer-based neural operator for PDEs on complex geometries and irregular grids. | [arXiv](https://arxiv.org/abs/2402.02366) |
| HyPINO | Hybrid Physics-Informed Neural Operator | Hybrid physics-informed neural operator combining physical constraints with data-driven learning for enhanced PDE accuracy. | [arXiv](https://arxiv.org/abs/2312.10364) |
| PI-Latent-NO | Physics-Informed Latent Neural Operator | Physics-informed latent-space neural operator integrating equation constraints in latent space for PDE solving. | [arXiv](https://arxiv.org/abs/2404.06907) |
| Transolver | Transolver: A Fast Transformer Solver for PDEs on General Geometries | Physics-Attention Transformer PDE solver supporting arbitrary geometries, achieving multi-benchmark SOTA. | [ICML](https://arxiv.org/abs/2402.02366) |
| SFNO | Spherical Fourier Neural Operators: Learning Stable Dynamics on the Sphere | Spherical Fourier neural operator serving as the backbone of FourCastNet V2 for global weather prediction. | [ICML](https://arxiv.org/abs/2306.03838) |
| WIND | WIND: Weather Inverse Diffusion for Zero-Shot Atmospheric Modeling | Zero-shot atmospheric modeling foundation model based on inverse diffusion. | [arXiv](https://arxiv.org/abs/2602.03924) |
| STAR-MD | Scalable Spatio-Temporal SE(3) Diffusion for Long-Horizon Protein Dynamics | Scalable SE(3)-equivariant diffusion model for simulating long-horizon protein dynamics. | [arXiv](https://arxiv.org/abs/2602.02128) |
| MORPH | Shape-agnostic PDE Foundation Models | Shape-agnostic autoregressive PDE foundation model handling arbitrary domain geometries. | [ICLR](https://arxiv.org/abs/2509.21670) |
| PDEformer-2 | Versatile Foundation Model for 2D PDEs | Versatile 2D PDE foundation model encoding equation structure as computational graphs. | [arXiv](https://arxiv.org/abs/2507.15409) |
| NESTOR | Nested MOE Neural Operator for Large-Scale PDE Pre-Training | Nested mixture-of-experts neural operator for large-scale PDE pre-training. | [arXiv](https://arxiv.org/abs/2602.22059) |

---

<a id="physics-section-03"></a>
## General Physics Simulation
*Large-scale models for multi-physics simulation, mesh-based dynamics, and surrogate modeling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| GPhyT | Towards a Physics Foundation Model | General physics Transformer trained on 1.8 TB of diverse simulation data with zero-shot generalization to unseen physics scenarios. | [arXiv](https://arxiv.org/abs/2509.13805) |
| PhysiX | PhysiX: A Foundation Model for Physics Simulations | 4.5B-parameter physics simulation foundation model using discrete tokenizer for multi-scale physical processes with autoregressive generation. | [NeurIPS](https://arxiv.org/abs/2506.17774) |
| PhysicsNeMo | PhysicsNeMo: An Open-Source Framework for Physics-AI | NVIDIA open-source framework for building, training, and deploying physics-informed AI models supporting GNN, FNO, and other architectures. | [Paper](https://github.com/NVIDIA/physicsnemo) |
| PDE-Transformer | PDE-Transformer: Efficient and Versatile Transformers for Physics Simulations | Scalable Transformer architecture for efficient surrogate modeling across multiple PDE types on regular grids. | [ICML 2025](https://openreview.net/forum?id=pde-transformer) |
| M2PDE | M2PDE: Compositional Generative Multiphysics and Multi-component PDE Simulation | Compositional diffusion-based framework for generative multi-physics and multi-component PDE simulation. | [arXiv](https://arxiv.org/abs/2412.04134) |
| UPS | Unified PDE Solvers | Unified PDE solver foundation model handling cross-domain, cross-dimension, and cross-resolution spatiotemporal PDEs. | [arXiv](https://arxiv.org/abs/2403.07187) |
| CompNO | CompNO: A Novel Foundation Model approach for solving Partial Differential Equations | Compositional neural operator splitting monolithic models into composable modules for efficient parametric PDE solving. | [Applied Sciences](https://arxiv.org/abs/2601.07384) |
| GNS | Learning to Simulate Complex Physics with Graph Networks | DeepMind graph network simulator learning particle interaction rules to generalize across fluids, rigid bodies, and deformable objects. | [ICML](https://arxiv.org/abs/2002.09405) |
| MeshGraphNets | Learning Mesh-Based Simulation with Graph Networks | Graph network simulation on unstructured meshes for aerodynamics and structural mechanics. | [ICLR](https://arxiv.org/abs/2010.03409) |
| X-MeshGraphNet | X-MeshGraphNet: Scalable Multi-Scale Graph Neural Networks for Physics Simulation | NVIDIA multi-scale mesh graph network extending MeshGraphNets to large-scale industrial physics simulation. | [NVIDIA 2024](https://docs.nvidia.com/deeplearning/physicsnemo/user-guide/latest/) |
| DHN | Deep Hamiltonian Networks | Deep Hamiltonian network learning physical dynamics within an energy-conserving structure. | [NeurIPS 2025](https://proceedings.neurips.cc/paper/2025) |
| AI-HAMILTON | AI-HAMILTON: Learning Hamiltonians from Data | Framework for learning Hamiltonians from data with symmetry priors for physically consistent dynamics modeling. | [NeurIPS 2025](https://proceedings.neurips.cc/paper/2025) |
| GeoPT | Scaling Physics Simulation via Lifted Geometric Pre-Training | Geometric pre-training foundation model for scaling physics simulation. | [arXiv](https://arxiv.org/abs/2602.20399) |

---

<a id="physics-section-04"></a>
## World Models
*Generative models that learn physical dynamics for interactive environment simulation and embodied AI.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Cosmos | Cosmos World Foundation Model Platform for Physical AI | NVIDIA open-source world foundation model platform generating physics-aware video and world states for robotics and autonomous driving. | [arXiv / NVIDIA](https://arxiv.org/abs/2501.03575) |
| Genie | Genie: Generative Interactive Environments | DeepMind 11B-parameter unsupervised world model generating interactive virtual worlds from a single image. | [ICML](https://arxiv.org/abs/2402.15391) |
| Genie 2 | Genie 2: A large-scale foundation world model | Upgraded Genie generating diverse, controllable interactive 3D environments from a single image for embodied AI. | [DeepMind](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) |
| Genie 3 | Genie 3: A new frontier for world models | General world model generating consistent interactive 3D worlds from text or images in real time with physical consistency. | [DeepMind](https://deepmind.google/discover/blog/genie-3/) |
| DIAMOND | Diffusion for World Modeling: Visual Details Matter in Atari | Diffusion-based world modeling achieving high visual fidelity for RL agent training in Atari environments. | [NeurIPS 2024](https://arxiv.org/abs/2405.12399) |
| WorldDreamer | WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens | General world model capturing physical dynamics across multiple environments via masked token prediction for video generation. | [arXiv](https://arxiv.org/abs/2401.09985) |
| GameNGen | Diffusion Models Are Real-Time Game Engines | Google Research neural game engine using diffusion models to simulate complex game environments (DOOM) at 20+ fps. | [arXiv preprint (Google)](https://arxiv.org/abs/2408.14837) |
| OASIS | Oasis: A Universe in a Transformer | Real-time open-world AI model generating interactive Minecraft-like gameplay at 20 fps via Transformer and diffusion. | [Decart AI](https://oasis-model.github.io) |
| Pandora | Pandora: Towards General World Model with Natural Language Actions and Video States | Hybrid autoregressive-diffusion world model controlling video state generation through natural language actions. | [arXiv](https://arxiv.org/abs/2406.09455) |
| UniSim | Learning Interactive Real-World Simulators | Universal world simulator learning to simulate diverse human-world interactions from text, actions, and image inputs. | [ICLR](https://arxiv.org/abs/2310.06114) |
| PAN | PAN: A World Model for General, Interactable, and Long-Horizon World Simulation | Action-conditioned world model for general, interactable, long-horizon simulation with environment dynamics consistency. | [arXiv](https://arxiv.org/abs/2511.09057) |
| PhysDreamer | PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation | Physics-based 3D object interaction generation via video generation for physically consistent object manipulation. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2404.13026) |
| PhyRecon | PhyRecon: Physically Plausible Neural Scene Reconstruction | Physically plausible neural scene reconstruction method combining physical constraints with 3D reconstruction. | [Advances in Neural Information Processing Systems 37](https://arxiv.org/abs/2404.16666) |
| Astra | General Interactive World Model with Autoregressive Denoising | General interactive world model combining autoregressive and denoising generation. | [ICLR](https://arxiv.org/abs/2512.08931) |

---

<a id="physics-section-05"></a>
## Quantum Physics & Many-Body Systems
*Foundation models for quantum state representation, many-body simulation, and quantum dynamics.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FNQS | Foundation Model for Quantum Many-Body States via Transformers | Transformer-based foundation model pre-trained on quantum state data, generalizing across different Hamiltonians and lattice structures. | [Nature Communications](https://doi.org/10.1038/s41467-025-58492-2) |
| Attention-Based FM for Quantum States | Attention-Based Foundation Model for Quantum States | Attention-based foundation model using self-attention to capture quantum correlations for cross-system quantum state representation. | [arXiv](https://arxiv.org/abs/2501.07079) |
| NOQS | Neural Operator for Quantum States | Neural operator learning continuous mappings over quantum state space for efficient quantum simulation and prediction. | [arXiv](https://arxiv.org/abs/2601.08978) |
| Large Electron Model | Large Electron Model: A Foundation Model for Electron Systems | Foundation model for electron systems pre-trained on large-scale electronic structure data, supporting quantum chemistry and materials physics tasks. | [arXiv](https://arxiv.org/abs/2602.09793) |
| DysonNet | Constant-Time Local Updates for Neural Quantum States | Neural quantum state architecture achieving O(1) local update efficiency for scalable quantum simulation. | [arXiv](https://arxiv.org/abs/2603.11189) |

---

<a id="physics-section-06"></a>
## Plasma Physics & Fusion
*Multi-modal models for tokamak plasma behavior prediction and fusion control.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| TokaMind | TokaMind: A Multi-Modal Transformer Foundation Model for Tokamak Plasma | Multi-modal Transformer foundation model fusing multiple diagnostic modalities for tokamak plasma behavior prediction and fusion control. | [arXiv](https://arxiv.org/abs/2501.14809) |

---

<a id="physics-section-07"></a>
## Optics & Photonics
*Foundation models for optical design, thin-film structures, and photonic inverse design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OptoGPT | OptoGPT: A Foundation Model for Inverse Design in Optical Multilayer Thin Film Structures | GPT-based foundation model for automatic inverse design of optical multilayer thin-film structures to meet target spectral properties. | [Opto-Electronic Advances](https://doi.org/10.29026/oea.2024.240062) |
| MOCLIP | MOCLIP: Multi-modal Optical Contrastive Learning for Inverse Photonic Design | Multi-modal optical contrastive learning model using a CLIP framework for cross-modal photonic structure inverse design. | [arXiv](https://arxiv.org/abs/2504.01754) |

---

<a id="physics-section-08"></a>
## Structure-Preserving & Geometric Physics ML
*Neural architectures that preserve physical symmetries, conservation laws, and geometric structure.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| HNN | Hamiltonian Neural Networks | Pioneering Hamiltonian neural network learning dynamics while preserving Hamiltonian structure and energy conservation. | [NeurIPS](https://arxiv.org/abs/1906.01563) |
| LNN | Lagrangian Neural Networks | Lagrangian neural network learning the Lagrangian in generalized coordinates, automatically satisfying Euler-Lagrange equations. | [ICLR 2020 Workshop](https://arxiv.org/abs/2003.04630) |
| GeoHNNs | Geometric Hamiltonian Neural Networks | Geometric Hamiltonian neural network integrating Riemannian geometry with symplectic structure to preserve physical symmetries. | [arXiv](https://arxiv.org/abs/2501.08459) |
| CGENN | Clifford Group Equivariant Neural Networks | Clifford algebra-based group equivariant neural network unifying rotation, reflection, and translation symmetries for physics modeling. | [NeurIPS 2023](https://arxiv.org/abs/2305.11141) |
| Multivector Neurons | Multivector Neurons: Better and Faster O(n)-Equivariant Clifford Graph Neural Networks | Multivector neurons achieving faster and more efficient O(n)-equivariant graph neural networks via Clifford algebra. | [NeurIPS](https://arxiv.org/abs/2406.04052) |

---

<a id="physics-section-09"></a>
## Quantum Chemistry & Electronic Structure
*Models for electronic structure calculation, wavefunction prediction, and molecular quantum properties.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Skala | Skala: A Foundation Model for Quantum Chemistry | Microsoft quantum chemistry foundation model for electronic structure computation and cross-system molecular property prediction. | [Microsoft](https://www.microsoft.com/en-us/research/publication/skala-a-foundation-model-for-quantum-chemistry/) |
| Orbformer | Orbformer: Orbital Transformer for Electronic Structure Prediction | Orbital Transformer predicting electronic structure from molecular orbital representations with physical symmetry priors. | [arXiv](https://arxiv.org/abs/2502.16068) |
| OrbEvo | Orbital Transformers for Predicting Wavefunctions in TD-DFT | Equivariant graph Transformer predicting real-time TD-DFT wavefunction evolution. | [arXiv](https://arxiv.org/abs/2603.03511) |

---

<a id="physics-section-10"></a>
## Combustion Simulation
*Deep learning platforms for reactive flow and combustion CFD.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DeepFlame | Deep Learning-Enabled Supercritical Flame Simulation | Open-source deep learning combustion CFD platform integrating ML surrogate models for reactive flow simulation. | [arXiv](https://arxiv.org/abs/2508.18969) |

---

<a id="physics-section-11"></a>
## Nuclear Engineering
*Domain-specific foundation models for nuclear reactor control and simulation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| NucReactor-FM | Agentic Physical AI toward a Domain-Specific FM for Nuclear Reactor Control | Domain-specific foundation model for nuclear reactor control combining physics simulation with reinforcement learning. | [arXiv](https://arxiv.org/abs/2512.23292) |
