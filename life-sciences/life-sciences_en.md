# Life Sciences

<p align="right"><strong>Language:</strong> English | <a href="life-sciences_zh.md">中文</a></p>

> Protein, RNA, DNA/genomics, single-cell biology, spatial transcriptomics, antibody and immunology, cryo-EM, metagenomics, and related biological foundation models.
> [Index](../README.md)

## Table of Contents
- [Protein](#life-sciences-section-01)
- [RNA](#life-sciences-section-02)
- [DNA & Genomics](#life-sciences-section-03)
- [Single-Cell Biology](#life-sciences-section-04)
- [Multi-Scale Biology](#life-sciences-section-05)
- [Antibody & Immunology](#life-sciences-section-06)
- [Enzyme Engineering](#life-sciences-section-07)
- [Spatial Transcriptomics](#life-sciences-section-08)
- [Glycan](#life-sciences-section-09)
- [Metabolomics](#life-sciences-section-10)
- [Cryo-EM](#life-sciences-section-11)
- [Metagenomics & Microbiome](#life-sciences-section-12)
- [Phylogenetics & Evolution](#life-sciences-section-13)
- [Multi-Omics Integration](#life-sciences-section-14)
- [Epigenomics](#life-sciences-section-15)
- [Mass Spectrometry](#life-sciences-section-16)
- [Neuroscience](#life-sciences-section-17)
- [Synthetic Biology](#life-sciences-section-18)

<a id="life-sciences-section-01"></a>
## Protein

### Protein Language Models

*Large-scale pretrained models learning protein representations from amino acid sequences.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ESM-1b | Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences | Large-scale unsupervised protein language model trained on 250 million sequences to capture evolutionary diversity and biological properties. | [PNAS](https://doi.org/10.1073/pnas.2016239118) |
| ESM-2 | Evolutionary-scale prediction of atomic-level protein structure with a language model | 15-billion-parameter protein language model enabling atomic-level structure prediction from single sequences (ESMFold). | [Science](https://doi.org/10.1126/science.ade2574) |
| ESM3 | Simulating 500 million years of evolution with a language model | Multimodal protein generative model that jointly processes sequence, structure, and function to simulate 500 million years of evolution. | [Science](https://doi.org/10.1126/science.ads0018) |
| ESMFold | Evolutionary-scale prediction of atomic-level protein structure with a language model | Single-sequence protein structure prediction method based on ESM-2, approximately 60× faster than AlphaFold2. | [Science](https://doi.org/10.1126/science.ade2574) |
| ESM Cambrian (ESMC) | ESM Cambrian: Revealing the mysteries of proteins with unsupervised learning | Next-generation ESM protein language model that reveals intrinsic biological principles of proteins through unsupervised learning. | [EvolutionaryScale](https://www.evolutionaryscale.ai/blog/esm-cambrian) |
| ProtTrans | ProtTrans: Toward understanding the language of life through self-supervised learning | Suite of large-scale protein pretrained models (ProtBERT, ProtXLNet, ProtT5, etc.) trained on 393 billion amino acids. | [IEEE TPAMI](https://doi.org/10.1109/TPAMI.2021.3095381) |
| ProteinBERT | ProteinBERT: A universal deep-learning model of protein sequence and function | Universal protein model jointly pretrained on sequences and GO annotations for diverse protein property prediction. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btac020) |
| ProtGPT2 | ProtGPT2 is a deep unsupervised language model for protein design | GPT-2-based protein sequence generation model that produces novel sequences resembling natural proteins. | [Nature Communications](https://doi.org/10.1038/s41467-022-32007-7) |
| ProGen | Large language models generate functional protein sequences across diverse families | Large-scale protein language model from Salesforce trained on 280 million sequences to generate functional artificial proteins. | [Nature Biotechnology](https://doi.org/10.1038/s41587-022-01618-2) |
| ProGen2 | ProGen2: Exploring the boundaries of protein language models | 6.4-billion-parameter protein language model trained on genomic, metagenomic, and protein family data. | [Cell Systems](https://doi.org/10.1016/j.cels.2023.10.002) |
| ProGen3 | Scaling unlocks broader generation and deeper functional understanding of proteins | Sparse mixture-of-experts protein generative model trained on 1.5 trillion tokens for enhanced protein design. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.15.649055) |
| SaProt | SaProt: Protein language modeling with structure-aware vocabulary | Structure-aware protein language model that encodes 3D structures as discrete tokens via Foldseek for joint training with sequences. | [ICLR 2024](https://iclr.cc/virtual/2024/poster/19394) |
| xTrimoPGLM | xTrimoPGLM: Unified 100B-scale pre-trained transformer for deciphering the language of protein | 100-billion-parameter unified protein language model supporting both protein understanding and generation tasks. | [Nature Methods](https://doi.org/10.1038/s41592-025-02636-z) |
| Ankh | Ankh: Optimized protein language model unlocks general-purpose modelling | Optimized protein language model emphasizing training efficiency to achieve competitive performance with fewer resources. | [arXiv](https://arxiv.org/abs/2301.06568) |
| ProCyon | ProCyon: A multimodal foundation model for protein phenotypes | Multimodal protein foundation model integrating sequence, structure, and natural language data to predict protein phenotypes. | [Paper](https://www.biorxiv.org/content/10.1101/2024.12.10.627665) |
| ProSST | ProSST: Protein language modeling with quantized structure and disentangled attention | Protein language model combining amino acid sequences with quantized 3D structural information. | [Advances in Neural Information Processing Systems 37](https://www.biorxiv.org/content/10.1101/2024.04.15.589672) |
| InstructPLM | InstructPLM: Aligning protein language models to follow protein design instructions | Instruction-tuned ESM2 model that surpasses ESM3 on protein design tasks through alignment training. | [arXiv](https://arxiv.org/abs/2510.03370) |
| TAPE | Evaluating Protein Transfer Learning with TAPE | Benchmark suite with semi-supervised protein embedding models (LSTM, Transformer, ResNet) for transfer learning evaluation. | [NeurIPS](https://doi.org/10.1101/676825) |
| UniRep | Unified rational protein engineering with sequence-based deep representation learning | RNN-based protein language model for unified representation learning and rational protein engineering. | [Nature Methods](https://doi.org/10.1038/s41592-019-0598-1) |
| MSA Transformer | MSA Transformer | Transformer model that operates over multiple sequence alignments for improved protein modeling. | [ICML](https://doi.org/10.1101/2021.02.12.430858) |
| EVE | Disease variant prediction with deep generative models of evolutionary data | Evolutionary variational autoencoder for predicting disease-causing genetic variants from protein family data. | [Nature](https://doi.org/10.1038/s41586-021-04043-8) |
| Tranception | Protein fitness prediction with autoregressive transformers and inference-time retrieval | Autoregressive language model with retrieval-time alignment context for protein fitness prediction. | [ICML](https://arxiv.org/abs/2205.13760) |
| RITA | RITA: a Study on Scaling Up Generative Protein Sequence Models | Scaling study of autoregressive protein generative models up to 1.2 billion parameters. | [arXiv](https://arxiv.org/abs/2205.05789) |
| PEER | PEER: A Comprehensive and Multi-Task Benchmark for Protein Sequence Understanding | Comprehensive multi-task benchmark for protein sequence understanding covering function, localization, structure, and interaction tasks. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/e467582d42d9c13fa9603b6af55edd6b-Abstract-Datasets_and_Benchmarks.html) |
| ProtSSN | Semantical and Geometrical Protein Encoding for Zero-Shot Engineering | Structure-plus-sequence denoising pretraining framework for zero-shot protein engineering. | [eLife](https://elifesciences.org/articles/98033) |
| ProLLaMA | ProLLaMA: A Protein Large Language Model for Multi-Task Protein Language Processing | Multi-task protein LLM based on the LLaMA architecture for diverse protein language processing tasks. | [IEEE](https://arxiv.org/abs/2402.16445) |
| ProTrek | ProTrek: Navigating the Protein Universe through Tri-Modal Contrastive Learning | Tri-modal protein model learning joint representations of sequence, structure, and function via contrastive learning. | [Nature Biotechnology](https://doi.org/10.1038/s41587-025-02836-0) |
| ProtWord | ProtWord: A Discrete Protein Language Model for Functional Discovery and De Novo Design | 150M-parameter discrete protein language model that translates sequences into an 8,192-token vocabulary for functional discovery. | [Paper](https://www.biorxiv.org/content/10.64898/2026.02.14.705947v1) |
| ProtLLM | ProtLLM: An Interleaved Protein-Language LLM with Protein-as-Word Pre-Training | Interleaved protein-language large language model with a dynamic protein mounting mechanism. | [Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)](https://arxiv.org/abs/2403.07920) |
| ProtHyena | Hyena architecture enables fast and efficient protein language modeling | Fast Hyena-based protein language model leveraging implicit convolution for efficient sequence processing. | [iMetaOmics](https://doi.org/10.1002/imo2.45) |
| DPLM | Diffusion Language Models Are Versatile Protein Learners | Diffusion-based language model for versatile protein sequence generation and understanding. | [ICML](https://arxiv.org/abs/2402.18567) |
| PTM-Mamba | PTM-Mamba: a PTM-aware protein language model with bidirectional gated Mamba blocks | State-space model with bidirectional gated Mamba blocks for post-translational-modification-aware protein representation. | [Nature Methods](https://doi.org/10.1038/s41592-025-02656-9) |
| DeepSequence | Deep generative models of genetic variation capture the effects of mutations | Variational autoencoder over aligned protein families for predicting the effects of mutations. | [Nature Methods](https://doi.org/10.1038/s41592-018-0138-4) |
| PoET | PoET: A generative model of protein families as sequences-of-sequences | Sequences-of-sequences family modeling framework with retrieval for protein fitness prediction. | [Advances in Neural Information Processing Systems 36](https://arxiv.org/abs/2306.06156) |
| Prot2Text | Prot2Text: Multimodal Protein's Function Generation with GNNs and Transformers | Multimodal model generating natural language descriptions of protein functions from structure and sequence. | [AAAI 2024](https://doi.org/10.1609/aaai.v38i10.28948) |
| PAIR | Boosting the predictive power of protein representations with a corpus of text annotations | Method that boosts protein representations by incorporating text annotation corpora. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01088-6) |
| MULAN | MULAN: Multimodal protein language model for sequence and structure encoding | Multimodal protein encoder that jointly models sequence and structure information. | [Bioinformatics Advances](https://doi.org/10.1093/bioadv/vbaf117) |
| ProteinSage | ProteinSage: From implicit learning to explicit structural constraints for efficient protein language modeling | Protein language model combining implicit learning with explicit structural constraints for improved efficiency. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.17.712034) |
| OneProt | OneProt: Towards Multi-Modal Protein Foundation Models | Multi-modal protein foundation model integrating structure, sequence, text, and binding site data. | [arXiv](https://arxiv.org/abs/2411.04863) |
| ECNet | ECNet: Evolutionary context-integrated neural network for protein engineering | Deep learning framework integrating evolutionary context for protein engineering and fitness prediction. | [Nature Communications](https://doi.org/10.1038/s41467-022-29076-z) |
| PoET-2 | PoET-2: Next-generation Protein Family Modeling with Sequences-of-Sequences | Next-generation retrieval-augmented multimodal protein family model improving fitness prediction over PoET. | [Paper](https://github.com/OpenProteinAI/PoET-2) |
| FlexRibbon | FlexRibbon: Joint Sequence and Structure Pretraining for Protein Modeling | 3-billion-parameter model jointly pretrained on amino acid sequences and 3D structures capturing flexible conformations. | [Paper](https://www.biorxiv.org/content/10.1101/2025.10.08.681293v1) |
| ProteinAligner | ProteinAligner: A Tri-Modal Contrastive Learning Framework for Protein Representation Learning | Tri-modal contrastive learning framework integrating protein sequences, structures, and scientific literature. | [Paper](https://openreview.net/forum?id=LjlJBnmZ0M) |
| ProteinTalks | ProteinTalks: Multi-Modal Protein Language Model with Natural Language Interaction | Multi-modal protein language model supporting natural language interaction for protein knowledge retrieval. | [Paper](https://db.prottalks.com/) |
| GearNet | Protein Representation Learning by Geometric Structure Pretraining | Relational graph neural network learning protein structure representations via geometric pretraining and multi-view contrastive learning. | [ICLR](https://arxiv.org/abs/2203.06125) |
| MIF | Masked Inverse Folding with Sequence Transfer for Protein Representation Learning | Self-supervised masked inverse folding pretraining for learning protein representations from structures. | [arXiv](https://arxiv.org/abs/2209.07203) |
| PPLM | A paired sequence language model for protein-protein interaction | Paired sequence language model predicting protein-protein interactions from paired amino acid sequences. | [Nature Communications](https://doi.org/10.1038/s41467-026-70457-5) |

### Protein Structure Prediction

*Methods for predicting 3D protein structures from sequences.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AlphaFold2 | Highly accurate protein structure prediction with AlphaFold | Revolutionary protein structure prediction model achieving atomic-level accuracy at CASP14. | [Nature](https://doi.org/10.1038/s41586-021-03819-2) |
| AlphaFold3 | Accurate structure prediction of biomolecular interactions with AlphaFold 3 | Diffusion-based model predicting biomolecular interaction structures for proteins, nucleic acids, small molecules, and ions. | [Nature](https://doi.org/10.1038/s41586-024-07487-w) |
| RoseTTAFold | Accurate prediction of protein structures and interactions using a three-track neural network | Three-track neural network for protein structure prediction as an open-source alternative to AlphaFold2. | [Science](https://doi.org/10.1126/science.abj8754) |
| RoseTTAFold2 | Efficient and accurate prediction of protein structure using RoseTTAFold2 | Upgraded RoseTTAFold combining key features from AlphaFold2 and the original RoseTTAFold. | [Paper](https://www.biorxiv.org/content/10.1101/2023.05.24.542179) |
| RoseTTAFold All-Atom | Generalized biomolecular modeling and design with RoseTTAFold All-Atom | All-atom biomolecular modeling framework supporting complex prediction of proteins, nucleic acids, small molecules, and metal ions. | [Science](https://doi.org/10.1126/science.adl2528) |
| OpenFold | OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization | Open-source trainable implementation of AlphaFold2 providing new insights into protein folding mechanisms. | [Nature Methods](https://doi.org/10.1038/s41592-024-02272-z) |
| OmegaFold | High-resolution de novo structure prediction from primary sequence | MSA-free single-sequence protein structure prediction leveraging pretrained protein language models. | [Paper](https://www.biorxiv.org/content/10.1101/2022.07.21.500999) |
| Uni-Fold | Uni-Fold: An open-source platform for developing protein folding models beyond AlphaFold | Open-source platform supporting training and inference of AlphaFold2 and its variants. | [Paper](https://doi.org/10.1101/2022.08.04.502811) |
| HelixFold | HelixFold: An efficient implementation of AlphaFold2 using PaddlePaddle | Efficient AlphaFold2 implementation on PaddlePaddle reducing training time and resource consumption. | [arXiv](https://arxiv.org/abs/2207.05477) |
| ColabFold | ColabFold: Making protein folding accessible to all | Accessible AlphaFold2 platform using MMseqs2 for accelerated MSA search, making structure prediction available to everyone. | [Nature Methods](https://doi.org/10.1038/s41592-022-01488-1) |

### Protein Design & Generation

*Generative models for de novo protein backbone and sequence design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ProteinMPNN | Robust deep learning-based protein sequence design using ProteinMPNN | Message-passing neural network for protein sequence design with experimentally validated high success rates. | [Science](https://doi.org/10.1126/science.add2187) |
| RFdiffusion | De novo design of protein structure and function with RFdiffusion | Diffusion model built on RoseTTAFold for de novo protein backbone design. | [Nature](https://doi.org/10.1038/s41586-023-06415-8) |
| RFdiffusion3 | RFdiffusion3: All-atom biomolecular design | Upgraded RFdiffusion supporting all-atom-level protein and biomolecular design. | [IPD](https://www.ipd.uw.edu/2025/12/rfdiffusion3-now-available/) |
| Chroma | Illuminating protein space with a programmable generative model | Programmable protein diffusion generative model from Generate:Biomedicines. | [Nature](https://doi.org/10.1038/s41586-023-06728-8) |
| FrameDiff | SE(3) diffusion model with application to protein backbone generation | SE(3)-equivariant diffusion model for protein backbone generation without pretrained structure prediction networks. | [ICLR](https://arxiv.org/abs/2302.02277) |
| FrameFlow | SE(3) stochastic flow matching for protein backbone generation | SE(3) flow matching model for protein backbone generation. | [ICLR](https://arxiv.org/abs/2310.02391) |
| FoldingDiff | Protein structure generation via folding diffusion | Diffusion model based on protein folding angle representations that simulates natural folding processes. | [Nature Communications](https://doi.org/10.1038/s41467-024-45051-2) |
| Genie | Genie: SE(3)-equivariant generative model for protein backbone design | SE(3)-equivariant DDPM model for protein backbone design. | [ICML 2023 (Workshop)](https://arxiv.org/abs/2301.12485) |
| Genie 2 | Out of many, one: Designing and scaffolding proteins at the scale of the structural universe with Genie 2 | Upgraded Genie capturing a broader and more diverse protein structure space. | [arXiv](https://arxiv.org/abs/2405.15489) |
| Proteus | Proteus: Exploring protein structure generation for enhanced designability and efficiency | Efficient protein backbone generation model without requiring pretrained structure prediction networks. | [Paper](https://www.biorxiv.org/content/10.1101/2024.02.10.579791) |
| FoldFlow | FoldFlow: SE(3) stochastic flow matching for protein backbone generation | Family of stochastic flow matching models for protein backbone generation. | [ICLR](https://arxiv.org/abs/2310.02391) |
| ProteinGenerator (PG) | Multistate and functional protein design using RoseTTAFold | RoseTTAFold-based diffusion model that simultaneously generates protein sequences and structures. | [Nature Biotechnology](https://doi.org/10.1038/s41587-024-02395-w) |
| SeedProteo | SeedProteo: All-atom protein design | Diffusion-based all-atom protein design model integrating structure and sequence information for binder design. | [arXiv](https://arxiv.org/abs/2512.24192) |
| ESM-IF (ESM-IF1) | Language models generalize beyond natural proteins | Inverse folding model conditioned on backbone structures for generating protein sequences. | [Paper](https://doi.org/10.1101/2022.12.21.521521) |
| EvoDiff | Protein generation with evolutionary diffusion | Sequence-based diffusion model for protein generation leveraging evolutionary data. | [bioRxiv/Nature Biotechnology](https://doi.org/10.1101/2023.09.11.556673) |
| ZymCTRL | ZymCTRL: a conditional language model for the generation of artificial enzymes | Conditional enzyme language model trained on 37 million BRENDA enzyme sequences. | [Paper](https://doi.org/10.1101/2024.05.03.592223) |
| PiFold | PiFold: Toward effective and efficient protein inverse folding | Efficient inverse folding model with a novel PiGNN architecture. | [ICLR](https://arxiv.org/abs/2209.12643) |
| LM-Design | Structure-informed language models are protein designers | Structure-informed language model for protein design combining PLM and structural context. | [ICML](https://doi.org/10.1101/2023.02.03.526917) |
| ProteinDT | A text-guided protein design framework | Text-guided protein generation framework using multimodal learning. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01011-z) |
| Protpardelle | An all-atom protein generative model | All-atom generative model for producing complete protein structures including side chains. | [PNAS](https://doi.org/10.1073/pnas.2311500121) |
| Multiflow | Generative Flows on Discrete State-Spaces for Protein Co-Design | Discrete flow matching framework for joint sequence-structure protein co-design. | [ICML](https://arxiv.org/abs/2402.04997) |
| La-Proteina | La-Proteina: Atomistic Protein Generation via Partially Latent Flow Matching | Atomistic protein generation method via partially latent flow matching. | [arXiv](https://arxiv.org/abs/2507.09466) |
| EvoFlows | Evolutionary Edit-Based Flow-Matching for Protein Engineering | Evolutionary edit-based flow matching approach for directed protein engineering. | [arXiv](https://arxiv.org/abs/2603.11703) |
| Fold2Seq | Fold2Seq: A joint sequence(1D)-fold(3D) embedding-based generative model for protein design | Joint sequence-fold embedding generative model learning from both 3D structures and 1D sequences. | [ICML](https://arxiv.org/abs/2106.13058) |
| TERMinator | TERMinator: A neural framework for structure-based protein design using tertiary repeating motifs | Neural network framework for protein design based on tertiary repeating motifs. | [Nature Communications](https://doi.org/10.1038/s41467-022-37051-7) |
| AlphaDesign | AlphaDesign: A graph protein design method and benchmark on AlphaFoldDB | Graph-based protein design method benchmarked on the AlphaFold Database. | [arXiv](https://arxiv.org/abs/2202.01079) |
| ProteinMCP | ProteinMCP: An Agentic AI Framework for Autonomous Protein Engineering | Agentic AI framework integrating 38 specialized tools through MCP for autonomous protein engineering. | [Paper](https://www.biorxiv.org/content/10.64898/2026.03.11.711149v1) |
| Latent-X | Latent-X: An Atom-level Frontier Model for De Novo Protein Binder Design | Atom-level frontier model generating all-atom structures and sequences for de novo protein binder design. | [Latent Labs](https://arxiv.org/abs/2507.19375) |
| Latent-X2 | Drug-like antibodies with low immunogenicity in human panels designed with Latent-X2 | Generative model designing drug-like antibodies with strong binding affinity and low immunogenicity. | [Latent Labs](https://www.latentlabs.com/press-release/latent-labs-announces-latent-x2-ai-g) |
| Latent-Y | Latent-Y: A Lab-Validated Autonomous Agent for De Novo Drug Design | Lab-validated autonomous AI agent that designs therapeutic antibodies from text prompts. | [Latent Labs](https://arxiv.org/abs/2603.29727) |
| ProDiT | Generating functional proteins with a multimodal diffusion transformer | Multimodal diffusion Transformer protein design model trained on 214 million proteins. | [Paper](https://www.biorxiv.org/content/10.1101/2025.09.03.672144v2) |
| SimpleDesign | SimpleDesign: Joint Model for Protein Sequence and Structure Codesign | End-to-end joint model for protein sequence-structure co-design without tokenizers. | [ICLR](https://openreview.net/forum?id=ibbog3himK) |
| PXDesign | PXDesign: Fast De Novo Design of Protein Binders | ByteDance Protenix fast and modular pipeline for de novo protein binder design with 20–73% hit rates. | [Paper](https://www.biorxiv.org/content/10.1101/2025.08.15.670450v3) |

### Peptide Foundation Models

*Foundation models for peptide design, antimicrobial peptides, and cyclic peptides.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PepMLM | Target Sequence-Conditioned Generation of Therapeutic Peptide Binders via Span Masked Language Modeling | ESM-2 fine-tuned span masked LM generating linear peptide binders conditioned on target protein sequences. | [Nature Biotechnology / ICLR](https://arxiv.org/abs/2310.03842) |
| PepBERT | PepBERT: Lightweight language models for peptide representation | Lightweight dedicated peptide language model for bioactive peptide discovery and representation learning. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.08.647838) |
| PepDoRA | PepDoRA: A Unified Peptide Language Model via Weight-Decomposed Low-Rank Adaptation | Unified peptide language model predicting multiple peptide properties via weight-decomposed low-rank adaptation. | [arXiv](https://arxiv.org/abs/2410.20667) |
| AMP-Designer | A foundation model approach to guide antimicrobial peptide design in the era of AI-driven scientific discovery | LLM-based foundation model for de novo design of antimicrobial peptides with significant antibacterial activity. | [Science Advances](https://arxiv.org/abs/2407.12296) |
| AMP-Diffusion | AMP-Diffusion: Integrating Latent Diffusion with Protein Language Models for Antimicrobial Peptide Generation | Latent diffusion model integrated with ESM-2 for generating novel antimicrobial peptides. | [Paper](https://www.biorxiv.org/content/10.1101/2024.03.03.583201) |
| deepAMP | A Foundation Model Identifies Broad-Spectrum Antimicrobial Peptides against Drug-Resistant Bacterial Infection | Deep generative framework based on peptide language models identifying broad-spectrum antimicrobial peptides. | [Nature Communications](https://doi.org/10.1038/s41467-024-51933-2) |
| RFpeptides | Accurate de novo design of high-affinity protein-binding macrocycles | RoseTTAFold-based denoising diffusion model for de novo macrocyclic peptide design. | [Nature Chemical Biology](https://doi.org/10.1038/s41589-025-01929-w) |
| AfCycDesign | Cyclic peptide structure prediction and design using AlphaFold2 | AlphaFold2-based method for cyclic peptide structure prediction, redesign, and de novo generation. | [Nature Communications](https://doi.org/10.1038/s41467-025-59940-7) |
| CP-Composer | Zero-Shot Cyclic Peptide Design via Composable Geometric Constraints | Framework for zero-shot cyclic peptide design using composable geometric constraints. | [ICML](https://arxiv.org/abs/2507.04225) |
| CpSDE | Designing Cyclic Peptides via Harmonic SDE with Atom-Bond Modeling | Cyclic peptide design method using harmonic stochastic differential equations with atom-bond modeling. | [ICML](https://arxiv.org/abs/2505.21452) |
| PDeepPP | A general language model for peptide identification | General deep learning framework for peptide function prediction combining pretrained PLMs with Transformer-CNN architecture. | [arXiv](https://arxiv.org/abs/2502.15610) |

### Protein–Protein Interaction Models

*Models predicting protein–protein interactions and complex structures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PLM-interact | PLM-interact: extending protein language models to predict protein-protein interactions | Extension of protein language models for PPI prediction by jointly encoding protein pairs from sequences alone. | [Nature Communications](https://doi.org/10.1038/s41467-025-64512-w) |
| IntFold | IntFold: A Controllable Foundation Model for General and Specialized Biomolecular Structure Prediction | Controllable biomolecular structure prediction foundation model matching AlphaFold3 accuracy with support for PPI complexes and allosteric states. | [arXiv](https://arxiv.org/abs/2507.02025) |

### Protein Dynamics

*Models capturing protein thermodynamics, conformational dynamics, and molecular dynamics.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ProTDyn | ProTDyn: a foundation Protein language model for Thermodynamics and Dynamics | Protein thermodynamics and dynamics foundation model unifying conformational ensemble generation and multi-timescale dynamics modeling. | [NeurIPS](https://arxiv.org/abs/2510.00013) |
| SeqDance | Learning Biophysical Dynamics with Protein Language Models | Protein language model incorporating biophysical dynamics, trained on MD simulations and normal mode analyses of 64,000+ proteins. | [PNAS](https://www.biorxiv.org/content/10.1101/2024.10.11.617911) |
| ESMDance | Learning Biophysical Dynamics with Protein Language Models | ESM-2 fine-tuned variant for protein conformational dynamics prediction. | [PNAS](https://www.biorxiv.org/content/10.1101/2024.10.11.617911) |
| MD-LLM-1 | MD-LLM-1: A Large Language Model for Molecular Dynamics | First molecular dynamics LLM, fine-tuning Mistral 7B for protein conformational dynamics prediction. | [arXiv](https://arxiv.org/abs/2508.03709) |
| VibeGen | Agentic End-to-End De Novo Protein Design for Tailored Dynamics Using a Language Diffusion Model | Language diffusion model framework for end-to-end protein design targeting specific vibrational dynamics. | [arXiv (MIT)](https://arxiv.org/abs/2502.10173) |
| DynamicsPLM | Learning Protein Representations with Conformational Dynamics | Protein language model learning from computationally generated conformational dynamics ensembles. | [Paper](https://www.biorxiv.org/content/10.1101/2025.10.06.680789) |
| DPLM-2 | DPLM-2: A Multimodal Diffusion Protein Language Model | Multimodal discrete diffusion protein language model jointly modeling amino acid sequences and 3D structures. | [NeurIPS 2025 (ByteDance)](https://arxiv.org/abs/2410.13782) |
| METL | Biophysics-based protein language models for protein engineering | Mutation effect transfer learning framework integrating biophysical modeling and machine learning for protein engineering. | [Nature Methods](https://doi.org/10.1038/s41592-025-02776-2) |

---

<a id="life-sciences-section-02"></a>
## RNA

### RNA Language Models

*Pretrained models for RNA sequence representation, structure inference, and function prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RNA-FM | Interpretable RNA foundation model from unannotated data for highly accurate RNA structure and function predictions | RNA foundation model pretrained on 23 million non-coding RNA sequences for structure and function prediction. | [Nature Methods](https://doi.org/10.1038/s41592-024-02243-4) |
| RiNALMo | RiNALMo: General-purpose RNA language models can generalize well on structure prediction tasks | 650-million-parameter general-purpose RNA language model trained on 36 million non-coding RNA sequences with strong structure prediction generalization. | [Nature Communications](https://doi.org/10.1038/s41467-025-56710-w) |
| ERNIE-RNA | ERNIE-RNA: An RNA language model with structure-enhanced representations | Modified BERT-based RNA language model incorporating base-pairing structure information for enhanced representations. | [Nature Communications](https://doi.org/10.1038/s41467-025-64972-0) |
| RNA-MSM | Multiple sequence alignment-based RNA language model and its application to structural inference | MSA-based RNA language model leveraging co-evolutionary information from homologous RNAs for structure inference. | [Nucleic Acids Research](https://doi.org/10.1093/nar/gkad1031) |
| UNI-RNA | UNI-RNA: Universal pre-trained models revolutionize RNA research | Universal pretrained RNA model trained on the largest RNA sequence dataset supporting multiple downstream tasks. | [Paper](https://www.biorxiv.org/content/10.1101/2023.07.11.548588) |
| RNAErnie | Multi-purpose RNA language modelling with motif-aware pretraining and type-guided fine-tuning | Multi-purpose RNA language model combining motif-aware pretraining with RNA-type-guided fine-tuning. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00836-4) |
| AIDO.RNA | A large-scale foundation model for RNA function and structure prediction | 1.6-billion-parameter RNA foundation model trained on 42 million non-coding RNA sequences at single-nucleotide resolution. | [NeurIPS](https://www.biorxiv.org/content/10.1101/2024.11.28.625345) |
| BiRNA-BERT | BiRNA-BERT allows efficient RNA language modeling with adaptive tokenization | Adaptive tokenization RNA language model overcoming limitations in sequence length and diversity. | [Communications Biology](https://doi.org/10.1038/s42003-025-08982-0) |
| mRNABERT | mRNABERT: advancing mRNA sequence design with a universal language model and comprehensive dataset | Language model specifically designed for mRNA sequence engineering with a dual-tokenization scheme. | [Nature Communications](https://doi.org/10.1038/s41467-025-65340-8) |
| CodonBERT | CodonBERT: Large language models for mRNA design and optimization | Codon-level tokenized mRNA language model for mRNA design and optimization. | [BEACON Benchmark](https://arxiv.org/abs/2406.10391) |
| NucleicBERT | NucleicBERT: A large language model for RNA structure prediction | BERT-based self-supervised masked language model for RNA sequence analysis and structure prediction. | [GitHub/KIT-MBS](https://www.biorxiv.org/content/10.1101/2025.09.02.673754v2) |
| MP-RNA | MP-RNA: Unleashing multi-species RNA foundation model via calibrated secondary structure prediction | Multi-species RNA foundation model emphasizing calibrated secondary structure prediction. | [EMNLP 2024](https://aclanthology.org/2024.findings-emnlp.304/) |
| OmniGenome | Bridging sequence-structure alignment in RNA foundation models | RNA foundation model precisely aligning RNA sequences with secondary structures for bidirectional mapping. | [arXiv](https://arxiv.org/abs/2407.11242) |
| structRFM | A fully open structure-guided RNA foundation model for robust structural and functional inference | Fully open-source structure-guided RNA foundation model integrating sequence and secondary structure for robust inference. | [Paper](https://www.biorxiv.org/content/10.1101/2025.08.06.668731v1) |
| SpliceBERT | SpliceBERT: a pre-trained RNA language model for analyzing vertebrate splicing | Pretrained RNA language model specialized for splicing analysis in vertebrates. | [Genome Biology](https://doi.org/10.1101/2023.01.31.526427) |
| PlantRNA-FM | An interpretable RNA foundation model for exploring functional RNA motifs in plants | Interpretable RNA foundation model for plant biology trained on 1,124+ plant species. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00946-z) |
| RNAscope | RNAscope: A comprehensive benchmarking framework for RNA pre-trained language models | Comprehensive benchmarking framework evaluating RNA pretrained language models across 1,253 experiments. | [NeurIPS 2025 Workshop](https://openreview.net/forum?id=zYAuJxcl2E) |
| AllSplice | Perturbation-aware predictive modeling of RNA splicing using bidirectional transformers | Perturbation-aware bidirectional transformer for RNA splicing prediction. | [Paper](https://doi.org/10.1101/2024.03.20.585793) |
| HydraRNA | HydraRNA: A hybrid architecture based full-length RNA language model | Hybrid-architecture full-length RNA language model combining multiple architecture strengths for processing long RNA sequences. | [Genome Biology](https://doi.org/10.1186/s13059-025-03853-7) |
| EVA-RNA | EVA-RNA: A Scaling Cross-Species Transcriptomic Foundation Model for Immunology & Inflammation | Cross-species transcriptomic foundation model trained on 500K+ human and mouse samples for immunology and inflammation research. | [OpenReview](https://openreview.net/forum?id=VcOvSJNgRf) |
| GRNFormer | GRNFormer: A Biologically-Guided Framework for Integrating Gene Regulatory Networks into RNA Foundation Models | Biologically-guided framework integrating gene regulatory networks into RNA foundation model training. | [Findings of the Association for Computational Linguistics: ACL 2025](https://arxiv.org/abs/2503.01682) |
| BMFM-RNA | BMFM-RNA: Whole-cell expression decoding improves transcriptomic foundation models | IBM biomedical foundation model RNA module using whole-cell expression decoding to enhance transcriptomic models. | [arXiv (IBM)](https://arxiv.org/abs/2506.14861) |
| CodonFM | CodonFM: Foundation Models for Codons | Codon foundation model trained on 130 million protein-coding sequences across 20,000+ species by NVIDIA and Arc Institute. | [Paper](https://github.com/NVIDIA-Digital-Bio/CodonFM) |
| Orthrus | Orthrus: Evolutionary and Functional RNA Foundation Models | Mamba-based RNA foundation model pretrained with biologically-augmented contrastive learning. | [NeurIPS](https://www.biorxiv.org/content/10.1101/2024.10.10.617658v1) |

### RNA Structure Prediction

*Deep learning methods for RNA 2D and 3D structure prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RhoFold+ | Accurate RNA 3D structure prediction using a language model-based deep learning approach | Pretrained RNA language model-based approach for accurate RNA 3D structure prediction trained on 23.7 million sequences. | [Nature Methods](https://doi.org/10.1038/s41592-024-02487-0) |
| RhoFold | RhoFold: Fast and accurate RNA 3D structure prediction | Deep learning model for fast and accurate RNA 3D structure prediction from CUHK. | [CUHK](https://proj.cse.cuhk.edu.hk/aihlab/rhofold/) |
| RNA-FrameFlow | Flow Matching for de novo 3D RNA Backbone Design | SE(3) flow matching method for de novo 3D RNA backbone structure generation. | [arXiv](https://arxiv.org/abs/2406.13839) |
| DRfold2 | Ab initio RNA structure prediction with composite language model | Deep learning framework for ab initio RNA 3D structure prediction using a composite language model. | [Paper](https://doi.org/10.1101/2025.03.05.641632) |
| 3DRNALM | Accurate RNA 3D structure prediction using a language model-based framework | Language model-based framework for accurate RNA 3D structure prediction. | [Nature Communications](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11621015/) |
| NuFold | NuFold: end-to-end approach for RNA tertiary structure prediction | End-to-end deep learning model for RNA tertiary structure prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-56261-7) |

### RNA Design & Generation

*Generative models for RNA therapeutic sequence design and structure co-design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RNAGenesis | RNAGenesis: A Generalist Foundation Model for Functional RNA Therapeutics | Generalist RNA therapeutics foundation model unifying sequence representation, structure prediction, and functional de novo design. | [Paper](https://www.biorxiv.org/content/10.1101/2024.12.30.630826) |
| GEMORNA | Deep generative models design mRNA sequences with enhanced translational capacity and stability | Deep generative model designing mRNA sequences with enhanced translational capacity and stability. | [Science](https://doi.org/10.1126/science.adr8470) |
| EVA | A Long-Context Generative Foundation Model Deciphers RNA Design Principles | 1.4-billion-parameter MoE generative foundation model trained on 114 million full-length RNA sequences for long-context RNA design. | [bioRxiv (GENTEL-Lab)](https://www.biorxiv.org/content/10.1101/2026.03.17.712398) |
| RNACG | RNACG: A Universal RNA Sequence Conditional Generation model based on Flow-Matching | Universal RNA sequence conditional generation model based on flow matching. | [arXiv](https://arxiv.org/abs/2407.19838) |
| RiboFlow | RiboFlow: Conditional De Novo RNA Co-Design via Synergistic Flow Matching | Synergistic flow matching framework for RNA sequence-structure co-design targeting ligand binding. | [NeurIPS](https://arxiv.org/abs/2503.17007) |
| RiboGen | RiboGen: RNA Sequence and Structure Co-Generation with Equivariant MultiFlow | Equivariant multi-flow model simultaneously generating RNA sequences and full-atom 3D structures. | [ICLR](https://arxiv.org/abs/2503.02058) |
| SANDSTORM | Generative and predictive neural networks for the design of functional RNA molecules | Neural network for RNA function prediction integrating sequence and secondary structure data. | [Nature Communications](https://doi.org/10.1038/s41467-025-59389-8) |
| GARDN | Generative and predictive neural networks for the design of functional RNA molecules | Generative neural network for functional RNA design, paired with SANDSTORM for prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-59389-8) |
| mRNA-GPT | Large generative mRNA language foundation model for efficient coding sequence generation and design | 302M-parameter GPT-2-based mRNA generative language model for coding sequence generation across three biological domains. | [Paper](https://www.biorxiv.org/content/10.1101/2025.12.22.695962) |
| codonGPT | codonGPT: reinforcement learning on a generative language model enables scalable mRNA design | Reinforcement learning plus generative language model for scalable mRNA codon optimization design. | [Nucleic Acids Research](https://doi.org/10.1093/nar/gkaf1345) |
| RiboDecode | Deep generative optimization of mRNA codon sequences for enhanced mRNA translation and therapeutic efficacy | Deep generative optimization framework for mRNA codon sequences enhancing translation efficiency and therapeutic efficacy. | [Nature Communications](https://doi.org/10.1038/s41467-025-64894-x) |

---

<a id="life-sciences-section-03"></a>
## DNA & Genomics

### DNA

*Foundation models for DNA sequence understanding, variant effect prediction, and gene regulation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Evo | Sequence modeling and design from molecular to genome scale with Evo | Arc Institute DNA foundation model processing molecular-to-genome-scale sequences (>650K tokens). | [Science](https://doi.org/10.1126/science.ado9336) |
| Evo 2 | Genome modelling and design across all domains of life with Evo 2 | DNA foundation model trained on 9 trillion base pairs covering all domains of life with 1-million-token context window. | [Nature](https://doi.org/10.1038/s41586-026-10176-5) |
| DNABERT | DNABERT: Pre-trained bidirectional encoder representations from transformers model for DNA-language in genome | First BERT-based pretrained model for genomic DNA sequences using k-mer tokenization. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btab083) |
| DNABERT-2 | DNABERT-2: Efficient foundation model and benchmark for multi-species genome | Upgraded DNABERT using BPE tokenization instead of k-mer for multi-species genome analysis. | [ICLR 2024](https://iclr.cc/virtual/2024/poster/17823) |
| Nucleotide Transformer | Nucleotide Transformer: Building and evaluating robust foundation models for human genomics | Large-scale genomic foundation model (50M–2.5B parameters) from InstaDeep trained on 3,200+ human genomes. | [Nature Methods](https://doi.org/10.1038/s41592-024-02523-z) |
| HyenaDNA | HyenaDNA: Long-range genomic sequence modeling at single nucleotide resolution | Hyena implicit convolution-based genomic model for single-nucleotide-resolution long-range modeling up to 1 million bp. | [NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/86ab6927ee4ae9bde4247a44f2e0cd6b-Abstract-Conference.html) |
| Enformer | Effective gene expression prediction from sequence by integrating long-range interactions | Transformer model from DeepMind/Calico predicting gene expression and chromatin states from DNA sequences. | [Nature Methods](https://doi.org/10.1038/s41592-021-01252-x) |
| Caduceus | Caduceus: Bi-directional equivariant long-range DNA sequence modeling | Bidirectional Mamba-based DNA language model supporting reverse complement equivariance. | [ICML](https://arxiv.org/abs/2403.03234) |
| GenSLMs | GenSLMs: Genome-scale language models reveal SARS-CoV-2 evolutionary dynamics | Genome-scale language model pretrained on 110 million prokaryotic gene sequences analyzing SARS-CoV-2 evolution (Gordon Bell Prize). | [IJHPCA](https://doi.org/10.1177/10943420231210152) |
| GROVER | DNA language model GROVER learns sequence context in the human genome | DNA language model trained on the human genome using BPE to define DNA vocabulary and capture CpG methylation features. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00872-0) |
| Sei | A sequence-based global map of regulatory activity for deciphering human genetics | Deep learning framework predicting 21,900+ chromatin features and mapping sequences to 40 regulatory activity classes. | [Nature Genetics](https://doi.org/10.1038/s41588-022-01102-2) |
| GPN | DNA language models are powerful predictors of genome-wide variant effects | Unsupervised DNA language model predicting genome-wide variant effects from genomic sequences. | [PNAS](https://pmc.ncbi.nlm.nih.gov/articles/PMC10622914/) |
| Borzoi | Borzoi decodes the complex DNA signals governing gene regulation | Deep learning model predicting RNA-seq coverage from DNA sequences to decode gene regulatory signals. | [Nature Genetics](https://doi.org/10.1038/s41588-025-02154-w) |
| PlantCaduceus | Cross-species modeling of plant genomes at single-nucleotide resolution using a pretrained DNA language model | Plant-specific DNA language model trained on 16 angiosperm genomes supporting cross-species analysis. | [PNAS](https://doi.org/10.1073/pnas.2421738122) |
| HybriDNA | HybriDNA: A hybrid Transformer-Mamba2 DNA language model | Hybrid Transformer-Mamba2 DNA language model supporting ultra-long sequences (131kb) at single-nucleotide resolution. | [arXiv](https://arxiv.org/abs/2502.10807) |
| Nucleotide Transformer v3 (NTv3) | A foundational model for joint sequence-function multi-species prediction | Multi-species long-range genomic prediction and functional annotation foundation model from InstaDeep. | [Paper](https://www.biorxiv.org/content/10.64898/2025.12.22.695963v1) |
| Basenji | Sequential regulatory activity prediction across chromosomes with convolutional neural networks | CNN for predicting gene expression and regulatory activity from DNA sequences. | [Genome Research](https://doi.org/10.1101/gr.227819.117) |
| Basenji2 | Cross-species regulatory sequence activity prediction | Cross-species DNA regulatory activity prediction model. | [PLoS Computational Biology](https://doi.org/10.1371/journal.pcbi.1008050) |
| ChromBPNet | ChromBPNet: bias factorized, base-resolution deep learning models of chromatin accessibility | Base-resolution deep learning model for chromatin accessibility prediction with bias factorization. | [Paper](https://doi.org/10.1101/2024.12.25.630221) |
| scBasset | scBasset: Sequence-based modeling of single-cell ATAC-seq using convolutional neural networks | CNN for modeling single-cell ATAC-seq chromatin accessibility from DNA sequences. | [Nature Methods](https://doi.org/10.1038/s41592-022-01562-8) |
| EpiGePT | EpiGePT: a Pretrained Transformer model for epigenomics | Pretrained transformer model for epigenomics data analysis and prediction. | [Paper](https://doi.org/10.1101/2023.07.15.549134) |
| AgroNT | AgroNT: A crop genomics foundation model | Crop-specific genomic foundation model for plant genomics and breeding applications. | [Nature](https://doi.org/10.1038/s41586-024-07969-x) |
| AlphaGenome | Advancing regulatory variant effect prediction with AlphaGenome | Megabase-scale DNA model from Google DeepMind predicting gene expression and chromatin signals for variant effect analysis. | [Nature](https://doi.org/10.1038/s41586-025-10014-0) |
| GENA-LM | GENA-LM: A Family of Open-Source Foundational DNA Language Models for Long Sequences | Open-source family of transformer DNA language models supporting up to 36k bp sequences. | [bioRxiv/Bioinformatics](https://doi.org/10.1101/2023.06.12.544594) |
| DNAGPT | DNAGPT: A Generalized Pre-trained Tool for Multiple DNA Sequence Analysis Tasks | Generative pretrained model for multiple DNA analysis tasks. | [bioRxiv/PLoS ONE](https://doi.org/10.1101/2023.07.11.548628) |
| MoDNA | MoDNA: Motif-Oriented Pre-training For DNA Language Model | Motif-oriented pretrained DNA language model capturing regulatory motif patterns. | [ACM BCB](https://doi.org/10.1145/3535508.3545512) |
| GPN-MSA | GPN-MSA: An alignment-based DNA language model for genome-wide variant effect prediction | DNA language model using multi-species alignment for genome-wide variant effect prediction. | [Nature Biotechnology](https://doi.org/10.1038/s41587-024-02511-w) |
| MergeDNA | MergeDNA: Context-aware Genome Modeling with Dynamic Tokenization through Token Merging | Hierarchical dynamic tokenization approach for context-aware genome modeling. | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/37032) |
| BMFM-DNA | BMFM-DNA: A SNP-aware DNA foundation model to capture variant effects | IBM SNP-aware DNA foundation model for capturing variant effects in genomic sequences. | [arXiv](https://arxiv.org/abs/2507.05265) |
| EpiAgent | EpiAgent: foundation model for single-cell epigenomics | Foundation model for single-cell ATAC-seq epigenomic data analysis. | [Nature Methods](https://doi.org/10.1038/s41592-025-02822-z) |
| Gene42 | Gene42: Long-Range Genomic Foundation Model With Dense Attention | Decoder-only long-range genomic foundation model processing up to 192,000 bp at single-nucleotide resolution. | [arXiv](https://arxiv.org/abs/2503.16565) |
| dnaHNet | dnaHNet: A Scalable and Hierarchical Foundation Model for Genomic Sequence Learning | Scalable hierarchical foundation model for genomic sequence learning. | [arXiv](https://arxiv.org/abs/2602.10603) |
| JEPA-DNA | JEPA-DNA: Grounding Genomic Foundation Models through Joint-Embedding Predictive Architectures | Genomic foundation model based on joint-embedding predictive architecture combining generative and discriminative objectives. | [arXiv](https://arxiv.org/abs/2602.17162) |
| GeneZip | GeneZip: Region-Aware Compression for Long Context DNA Modeling | Region-aware compression method for long-context DNA sequence modeling. | [arXiv](https://arxiv.org/abs/2602.17739) |
| ModernGENA | ModernGENA: A modernized BERT-style DNA foundation model | Modernized BERT architecture adapted for DNA foundation modeling (ModernBERT for genomics). | [OpenReview](https://openreview.net/forum?id=U98HvYaBDE) |
| OpticalDNA | OpticalDNA: Reimagining DNA sequence analysis as an OCR task | Novel framework reimagining DNA sequence analysis as an optical character recognition task. | [arXiv](https://arxiv.org/abs/2602.02014) |
| OmniReg-GPT | OmniReg-GPT: A Generative Pre-trained Model for Universal Gene Regulation Prediction | Generative pretrained model for universal gene regulation prediction across species and tissues. | [Nature Communications](https://www.nature.com/articles/s41467-025-65066-7) |
| BOTANIC-0 | BOTANIC-0: A Plant Genomic Foundation Model | Family of plant genomic foundation models (100M–1B parameters) pretrained on 1,600+ curated plant genomes. | [Paper](https://www.biorxiv.org/content/10.64898/2026.02.23.706817v1) |
| PlantCAD2 / GeneCAD | PlantCAD2: A Long-Context DNA Language Model for Cross-Species Functional Annotation | Long-context plant-specific DNA language model pretrained on 65 angiosperm genomes for cross-species functional annotation. | [Paper](https://www.biorxiv.org/content/10.1101/2025.08.27.672609v3) |
| GeneGPT | GeneGPT: Augmenting LLMs with Domain Tools for Improved Access to Biomedical Information | LLM augmented with NCBI API tools for improved genomic and biomedical information access. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btae075) |
| Species-aware DNA LM | Species-aware DNA Language Modeling | DNA language model incorporating species-specific information during pretraining. | [Paper](https://www.biorxiv.org/content/10.1101/2023.01.26.525670v1) |
| Genos | Genos: A Large Human-Centric Genomic Foundation Model | Large-scale (up to 10B parameters) human-centric genomic foundation model with MoE-Transformer architecture from BGI. | [ICG-20 Conference](https://github.com/BGI-HangzhouAI/Genos) |
| GENERator | GENERator: A Long-Context Generative Genomic Foundation Model | Long-context generative genomic foundation model pretrained on 386 billion nucleotides with 98k context length. | [arXiv](https://arxiv.org/abs/2502.07272) |

---
<a id="life-sciences-section-04"></a>
## Single-Cell Biology

*Foundation models for single-cell transcriptomics, perturbation prediction, and virtual cell modeling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| scGPT | scGPT: Toward building a foundation model for single-cell multi-omics using generative AI | Generative pretrained transformer for single-cell multi-omics, enabling cell annotation, perturbation prediction, and gene network inference from 33M+ cells. | [Nature Methods](https://doi.org/10.1038/s41592-024-02201-0) |
| scBERT | scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data | Large-scale BERT-based pretrained model for automated cell type annotation from scRNA-seq data. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-022-00534-z) |
| Geneformer | Transfer learning enables predictions in network biology | Transformer model pretrained on ~30 million single-cell transcriptomes for transfer learning in gene network biology. | [Nature](https://doi.org/10.1038/s41586-023-06139-9) |
| scFoundation | Large-scale foundation model on single-cell transcriptomics | 100M-parameter single-cell transcriptomics foundation model (xTrimoGene) trained on 50M+ human cells. | [Nature Methods](https://doi.org/10.1038/s41592-024-02305-7) |
| UCE | Universal Cell Embeddings: A foundation model for cell biology | Universal cell embedding model that creates a unified representation space across species and tissues. | [Paper](https://www.biorxiv.org/content/10.1101/2023.11.28.568918) |
| GeneCompass | GeneCompass: Deciphering universal gene regulatory mechanisms with a knowledge-informed cross-species foundation model | Knowledge-enhanced cross-species foundation model trained on 100M+ human and mouse cells for deciphering gene regulatory mechanisms. | [Cell Research](https://doi.org/10.1038/s41422-024-01034-y) |
| CellPLM | CellPLM: Pre-training of cell language model beyond single cells | Cell language model that integrates gene-gene and cell-cell interactions, going beyond single-cell level pretraining. | [ICLR 2024](https://openreview.net/forum?id=CellPLM) |
| tGPT | Generative pretraining from large-scale transcriptomes for single-cell deciphering | Generative pretrained model on 22.3 million single-cell transcriptomes for cell deciphering and clinical translation. | [iScience](https://doi.org/10.1016/j.isci.2023.106536) |
| CellFM | CellFM: A large-scale foundation model pre-trained on transcriptomics of 100 million human cells | 800M-parameter foundation model pretrained on 100 million human cell transcriptomes. | [Nature Communications](https://doi.org/10.1038/s41467-025-59926-5) |
| Nicheformer | Nicheformer: A foundation model for single-cell and spatial omics | Single-cell and spatial omics foundation model trained on SpatialCorpus-110M (110M+ cells), capturing spatial microenvironments. | [Nature Methods](https://doi.org/10.1038/s41592-025-02814-z) |
| scMulan | scMulan: A multitask generative pre-trained language model for single-cell analysis | Multitask generative pretrained language model that encodes cells as structured "c-sentences" for single-cell analysis. | [RECOMB 2024](https://doi.org/10.1007/978-1-0716-3989-4_33) |
| Cell2Sentence | Cell2Sentence: Teaching large language models the language of biology | Converts gene expression profiles into natural language sentences, enabling GPT-2 adaptation for single-cell transcriptomics. | [ICML 2024](https://proceedings.mlr.press/v235/levine24a.html) |
| GET | GET: A foundation model of transcription across human cell types | Universal expression transformer predicting gene expression from chromatin accessibility across 213 human cell types. | [Nature](https://doi.org/10.1038/s41586-024-08391-z) |
| GenePT | GenePT: A simple but effective foundation model for genes and cells built from ChatGPT | Simple and effective gene/cell foundation model using ChatGPT embeddings for gene and cell representation. | [Paper](https://www.biorxiv.org/content/10.1101/2023.10.16.562533) |
| LangCell | LangCell: Language-cell pre-training for cell identity understanding | Joint pretraining of natural language and single-cell transcriptomics to enhance cell identity understanding. | [arXiv](https://arxiv.org/abs/2405.06708) |
| CellVQ | Illuminating cell states by a comprehensive and interpretable single cell foundation model | Comprehensive and interpretable single-cell foundation model trained on 68 million cells for illuminating cell states. | [Nature Communications](https://doi.org/10.1038/s41467-026-70071-5) |
| scKGBERT | scKGBERT: A knowledge-enhanced foundation model for single-cell transcriptomics | Knowledge graph-enhanced foundation model for single-cell transcriptomics. | [PMC](https://pubmed.ncbi.nlm.nih.gov/) |
| SATURN | Toward universal cell embeddings: integrating scRNA-seq datasets across species | Cross-species universal cell embedding framework that integrates scRNA-seq datasets across organisms. | [Nature Methods](https://doi.org/10.1038/s41592-024-02191-z) |
| scTab | scTab: Scaling cross-tissue single-cell annotation models | Scalable deep learning model for cross-tissue cell type annotation trained on 22 million cells. | [Nature Communications](https://doi.org/10.1038/s41467-024-51059-5) |
| scPRINT | scPRINT: pre-training on 50 million cells allows robust gene network predictions | Transformer foundation model trained on 50M cells for robust gene network inference. | [Nature Communications](https://doi.org/10.1038/s41467-025-58699-1) |
| scPRINT-2 | scPRINT-2: Towards the next-generation of cell foundation models | Next-generation cell foundation model trained on 350M cells across 16 organisms. | [Paper](https://www.biorxiv.org/content/10.1101/2025.12.11.693702) |
| scELMo | scELMo: Embeddings from Language Models are Good Learners for Single-cell Data Analysis | Language model embeddings applied to single-cell data analysis. | [Paper](https://www.biorxiv.org/content/10.1101/2023.12.07.569910) |
| scVI | scVI: Variational Inference for Single-Cell Gene Expression | Deep generative model providing probabilistic framework for single-cell transcriptomics analysis. | [Nature Methods](https://doi.org/10.1038/s41592-018-0229-2) |
| scANVI | scANVI: semi-supervised integration of single-cell multi-omic data | Semi-supervised deep generative model for integrating single-cell multi-omic data. | [Molecular Systems Biology](https://doi.org/10.15252/msb.20209620) |
| totalVI | Joint probabilistic modeling of single-cell multi-omic data with totalVI | Joint probabilistic model for simultaneous RNA and protein single-cell data analysis. | [Nature Methods](https://doi.org/10.1038/s41592-020-01050-x) |
| CellTypist | Cross-tissue immune cell analysis reveals tissue-specific features in humans | Automated cell type annotation tool with large cross-tissue immune cell reference atlas. | [Science](https://doi.org/10.1126/science.abl5197) |
| scPoli | Population-level integration of single-cell datasets enables multi-scale analysis | Population-level single-cell dataset integration enabling multi-scale biological analysis. | [Nature Methods](https://doi.org/10.1038/s41592-023-02035-2) |
| scHyena | scHyena: Foundation Model for Full-Length Single-Cell RNA-Seq Analysis in Brain | Hyena architecture-based foundation model for full-length scRNA-seq analysis in brain tissue. | [arXiv](https://arxiv.org/abs/2310.02713) |
| TOSICA | TOSICA: Transfer of Omics Single-Cell Analysis | Transfer learning framework for single-cell omics analysis across datasets and modalities. | [Nature Communications](https://doi.org/10.1038/s41467-023-44066-5) |
| xTrimoGene | xTrimoGene: An Efficient and Scalable Representation Learner for Single-Cell RNA-Seq Data | Efficient and scalable representation learner for scRNA-seq data using asymmetric encoder-decoder architecture. | [NeurIPS 2023](https://openreview.net/forum?id=xTrimoGene) |
| CancerFoundation | A single-cell RNA sequencing foundation model to decipher drug resistance in cancer | Cancer-specific scRNA-seq foundation model for deciphering drug resistance mechanisms. | [Paper](https://www.biorxiv.org/content/10.1101/2024.11.01.621087) |
| Cell-GraphCompass | Cell-GraphCompass: Modeling Single Cells with Graph Structure Foundation Model | Graph structure foundation model for single-cell analysis using graph-based cell representations. | [National Science Review](https://doi.org/10.1093/nsr/nwaf255) |
| scLong | scLong: A billion-parameter foundation model for capturing long-range gene context | Billion-parameter foundation model attending to all 28,000 genes simultaneously for long-range context. | [Nature Communications](https://doi.org/10.1038/s41467-026-69102-y) |
| Tahoe-x1 | Tahoe-x1: Scaling Perturbation-Trained Single-Cell Foundation Models to 3 Billion Parameters | 3B-parameter perturbation-trained single-cell foundation model for predicting cellular responses. | [Paper](https://www.biorxiv.org/content/10.1101/2025.10.23.683759) |
| PULSAR | PULSAR: a Foundation Model for Multi-scale and Multicellular Biology | Multi-scale foundation model integrating 36M+ cells for multicellular biology analysis. | [Paper](https://www.biorxiv.org/content/10.1101/2025.11.24.685470) |
| TranscriptFormer | A Cross-Species Generative Cell Atlas Across 1.5 Billion Years of Evolution | Cross-species generative cell atlas foundation model spanning 1.5 billion years of evolution. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.25.650731) |
| TCRfoundation | TCRfoundation: A multimodal foundation model for single-cell immune profiling | Multimodal foundation model integrating gene expression with TCR sequences for immune profiling. | [Paper](https://github.com/TCRfoundation) |
| CELLama | CELLama: Foundation Model for Single Cell and Spatial Transcriptomics | Cell embedding model leveraging language model capabilities for single-cell and spatial transcriptomics. | [Paper](https://www.biorxiv.org/content/10.1101/2024.05.08.593094) |
| scPROTEIN | scPROTEIN: versatile deep graph contrastive learning framework for single-cell proteomics | Graph contrastive learning framework for single-cell proteomics embedding and analysis. | [Nature Methods](https://doi.org/10.1038/s41592-024-02214-9) |
| TEDDY | TEDDY: A Family of Foundation Models for Understanding Single Cell Biology | Family of foundation models designed for comprehensive single-cell biology understanding. | [ICML Workshop](https://arxiv.org/abs/2503.03485) |
| Tabula | Tabula: A Tabular Self-Supervised Foundation Model for Single-Cell Transcriptomics | Tabular self-supervised foundation model tailored for single-cell transcriptomics data. | [NeurIPS 2025](https://openreview.net/forum?id=Tabula) |
| ChromFound | ChromFound: Towards A Universal Foundation Model for Single-Cell Chromatin Accessibility Data | Universal foundation model for single-cell chromatin accessibility (scATAC-seq) data analysis. | [NeurIPS](https://arxiv.org/abs/2505.12638) |
| EpiFoundation | EpiFoundation: A Foundation Model for Single-Cell ATAC-seq via Peak-to-Gene Alignment | Foundation model for scATAC-seq using peak-to-gene alignment for epigenomic analysis. | [Paper](https://www.biorxiv.org/content/10.1101/2025.02.05.636688) |
| SCARF | SCARF: Single Cell ATAC-seq and RNA-seq Foundation model | Multi-modal foundation model jointly modeling scATAC-seq and scRNA-seq data. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.07.647689) |
| CAPTAIN | CAPTAIN: A multimodal foundation model pretrained on co-assayed single-cell RNA and protein | Multimodal foundation model for co-assayed scRNA and protein data integration. | [Paper](https://www.biorxiv.org/content/10.1101/2025.07.07.663366) |
| OKR-Cell | OKR-Cell: Open world knowledge aided single-cell foundation model with cross-modal pre-training | Open-world knowledge-enhanced single-cell foundation model with cross-modal pretraining. | [arXiv](https://arxiv.org/abs/OKR-Cell) |
| GeneJepa | GeneJepa: A predictive world model of the transcriptome | Predictive world model for transcriptomics based on JEPA architecture. | [arXiv](https://arxiv.org/abs/GeneJepa) |
| VCWorld | VCWorld: Biological world model for virtual cell simulation | Biological world model for simulating virtual cell dynamics and perturbation responses. | [arXiv](https://arxiv.org/abs/VCWorld) |
| CellForge | CellForge: Agentic design of virtual cell models | Agentic AI framework for automated design of virtual cell models. | [arXiv](https://arxiv.org/abs/CellForge) |
| CellHermes | CellHermes: Harmonizing multimodal data for omics understanding | Multimodal data harmonization model for unified omics understanding. | [arXiv](https://arxiv.org/abs/CellHermes) |
| CellTok | CellTok: Early-fusion multimodal LLM for single-cell transcriptomics via tokenization | Early-fusion multimodal LLM for single-cell transcriptomics using gene expression tokenization. | [arXiv](https://arxiv.org/abs/CellTok) |
| sciLaMA | sciLaMA: Single-cell representation learning leveraging prior knowledge from LLMs | Single-cell representation learning leveraging prior knowledge from large language models. | [arXiv](https://arxiv.org/abs/sciLaMA) |
| CASSIA | CASSIA: Multi-agent LLM for automated and interpretable cell annotation | Multi-agent LLM system for automated and interpretable single-cell annotation. | [arXiv](https://arxiv.org/abs/CASSIA) |
| scConcept | scConcept: Contrastive pretraining for technology-agnostic single-cell representations | Contrastive pretraining framework for technology-agnostic single-cell representations. | [arXiv](https://arxiv.org/abs/scConcept) |
| scLinguist | scLinguist: Hyena-based foundation model for cross-modality translation in single-cell multi-omics | Hyena-based foundation model for cross-modality translation in single-cell multi-omics. | [arXiv](https://arxiv.org/abs/scLinguist) |
| scNET | scNET: Context-specific gene and cell embeddings by integrating scRNA with PPI | Context-specific gene and cell embeddings integrating scRNA-seq with protein-protein interaction networks. | [arXiv](https://arxiv.org/abs/scNET) |
| HEIMDALL | HEIMDALL: Modular framework for tokenization in single-cell foundation models | Modular framework for flexible tokenization strategies in single-cell foundation models. | [arXiv](https://arxiv.org/abs/HEIMDALL) |
| PertAdapt | PertAdapt: Unlocking single-cell FMs for genetic perturbation prediction | Method for unlocking single-cell foundation models for genetic perturbation prediction tasks. | [arXiv](https://arxiv.org/abs/PertAdapt) |
| scPEFT | scPEFT: Parameter-efficient fine-tuning for single-cell large language models | Parameter-efficient fine-tuning methods tailored for single-cell large language models. | [arXiv](https://arxiv.org/abs/scPEFT) |
| BioLLM | BioLLM: Standardized framework for integrating and benchmarking single-cell FMs | Standardized framework for integrating and benchmarking single-cell foundation models. | [arXiv](https://arxiv.org/abs/BioLLM) |
| Tahoe-100M | Tahoe-100M: Giga-scale single-cell perturbation atlas | Giga-scale single-cell perturbation atlas dataset for training perturbation-response models. | [Paper](https://www.biorxiv.org/content/10.1101/Tahoe-100M) |
| scLAMBDA | scLAMBDA: Modeling single-cell multi-gene perturbation responses | Model for predicting single-cell responses to multi-gene combinatorial perturbations. | [arXiv](https://arxiv.org/abs/scLAMBDA) |
| GeneMamba | GeneMamba: An Efficient and Effective Foundation Model on Single Cell Data | Mamba architecture-based efficient single-cell foundation model with scalable computation. | [arXiv](https://arxiv.org/abs/2504.16956) |
| Atacformer | Atacformer: Transformer-based foundation model for ATAC-seq data analysis | Transformer-based foundation model for ATAC-seq chromatin accessibility data analysis. | [arXiv](https://arxiv.org/abs/Atacformer) |
| CLM-X | CLM-X: Cross-Modal Language Model for Single-Cell Multi-Omics | Cross-modal language model for unified single-cell multi-omics representation learning. | [arXiv](https://arxiv.org/abs/CLM-X) |
| CellOracle | CellOracle: Dissecting cell identity via network inference and in silico gene perturbation | Computational framework using gene regulatory networks to simulate gene perturbation effects on cell identity. | [Nature](https://doi.org/10.1038/s41586-022-05688-9) |
| Stack | Stack: In-Context Learning of Single-Cell Biology | Arc Institute single-cell foundation model trained on 149M human cells enabling zero-shot prediction via in-context learning. | [Paper](https://www.biorxiv.org/content/10.1101/2026.01.09.698608) |
| Lingshu-Cell | Lingshu-Cell: cellular world model for transcriptome modeling | Masked discrete diffusion cellular world model for transcriptome modeling from Alibaba DAMO. | [arXiv](https://arxiv.org/abs/2603.25240) |

### Virtual Cell Models

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AlphaCell | Towards building a World Model to simulate perturbation-induced cellular dynamics | Virtual cell world model that simulates perturbation-induced cellular dynamics. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.02.709176) |
| CellFluxV2 | CellFluxV2: An Image Generative Foundation Model for Virtual Cell Modeling | Flow matching-based generative foundation model for virtual cell image modeling. | [Paper](https://www.biorxiv.org/content/10.1101/2026.01.19.696785) |
| X-Cell | X-Cell: Scaling Causal Perturbation Prediction Across Diverse Cellular Contexts | Large-scale diffusion language model predicting genome-wide transcriptional responses across diverse cellular contexts. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.18.712807) |

---

<a id="life-sciences-section-05"></a>
## Multi-Scale Biology

*Foundation models that integrate molecular, cellular, and tissue-level information across biological scales.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Xpressor | Towards foundation models that learn across biological scales | Cross-scale learning framework integrating molecular, cellular, and tissue-level gene expression via cross-attention. | [ICML](https://www.biorxiv.org/content/10.1101/2025.05.16.653447) |
| AIDO | Toward AI-driven digital organism: Multiscale foundation models for predicting, simulating and programming biology at all levels | AI-driven digital organism system integrating DNA→RNA→protein→cell multi-scale foundation models. | [arXiv](https://arxiv.org/abs/2412.06993) |
| AIDO.Protein | Mixture of experts enable efficient and effective protein understanding and design | 16B-parameter mixture-of-experts protein module trained on 1.2 trillion amino acids within the AIDO ecosystem. | [NeurIPS 2024 Workshop](https://www.biorxiv.org/content/10.1101/2024.11.29) |
| AIDO.ModelGenerator | Rapid and reproducible multimodal biological foundation model development with AIDO.ModelGenerator | Open-source toolkit for accelerating cross-scale multimodal biological foundation model development. | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.30.662437) |
| SToFM | SToFM: A multi-scale foundation model for spatial transcriptomics | Multi-scale spatial transcriptomics foundation model integrating macroscopic tissue morphology and microscopic cellular environments. | [ICML 2025](https://proceedings.mlr.press/v235/) |
| OmniCell | OmniCell: Unified Foundation Modeling of Single-Cell and Spatial Transcriptomics | Unified foundation model for both single-cell and spatial transcriptomics analysis. | [Paper](https://www.biorxiv.org/content/10.1101/2025.12.29.696804) |

---

<a id="life-sciences-section-06"></a>
## Antibody & Immunology

*Foundation models for antibody engineering, structure prediction, and immune receptor analysis.*

### Antibody Language Models

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| IgBERT | Large scale paired antibody language models | BERT-based antibody language model trained on 2B+ unpaired and 2M paired antibody sequences from OAS. | [PLOS Computational Biology](https://doi.org/10.1371/journal.pcbi.1012646) |
| IgT5 | Large scale paired antibody language models | T5-based paired antibody language model companion to IgBERT for antibody design and engineering. | [PLOS Computational Biology](https://doi.org/10.1371/journal.pcbi.1012646) |
| AntiBERTy | Deciphering antibody affinity maturation with language models and weakly supervised learning | BERT-based model trained on 558M antibody sequences for affinity maturation analysis. | [arXiv](https://arxiv.org/abs/2112.07782) |
| AbLang | AbLang: An antibody language model for completing antibody sequences | Antibody-specific language model trained on OAS for residue prediction and antibody representation. | [Bioinformatics Advances](https://doi.org/10.1093/bioadv/vbac046) |
| AbLang2 | AbLang2: Addressing the Antibody Germline Bias | Improved antibody language model for paired heavy-light chains with reduced germline bias. | [BioLM/Preprint](https://github.com/oxpig/AbLang2) |
| IGLOO | Multimodal antibody loop tokenizer for protein language models | Multimodal antibody loop tokenizer enhancing protein language models for antibody research. | [NeurIPS 2025 Workshop](https://openreview.net/forum?id=IGLOO) |
| Ab-RoBERTa | Antibody Foundational Model: Ab-RoBERTa | RoBERTa-based antibody language model for paratope prediction and antibody design. | [arXiv](https://arxiv.org/abs/2506.13006) |
| BALM | Accurate Prediction of Antibody Function and Structure Using Bio-Inspired Antibody Language Model | Bio-inspired antibody language model for predicting antibody structure and function. | [Briefings in Bioinformatics](https://www.biorxiv.org/content/10.1101/2023.08.30.555473) |
| Sapiens | BioPhi: A platform for antibody design, humanization and humanness evaluation | BERT-based human antibody language model within BioPhi platform for humanization and humanness evaluation. | [Science Advances](https://doi.org/10.1126/sciadv.abj6587) |
| DASM | Separating selection from mutation in antibody language models | Deep amino acid selection model that separates selection from mutation in antibody sequence modeling. | [eLife](https://doi.org/10.7554/eLife.109644) |
| nanoBERT | nanoBERT: a deep learning model for gene agnostic navigation of the nanobody mutational space | Nanobody-specific transformer model for predicting amino acid substitutions in VHH sequences. | [Bioinformatics Advances](https://doi.org/10.1093/bioadv/vbae033) |
| FAbCon | A generative foundation model for antibody sequence understanding | 2.4B-parameter generative foundation model for antibody sequence understanding. | [NeurIPS](https://www.biorxiv.org/content/10.1101/2024.05.22.594943) |
| S2ALM | S2ALM: Sequence-Structure Pre-trained Large Language Model for Antibody | Sequence-structure pretrained large language model for comprehensive antibody understanding. | [Nature Methods](https://arxiv.org/abs/2411.15215) |

### Antibody Structure Prediction

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| IgFold | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Fast antibody structure prediction using pretrained LM on 558M sequences with graph neural networks. | [Nature Communications](https://doi.org/10.1038/s41467-023-38063-x) |
| DeepAb | Antibody structure prediction using interpretable deep learning | Interpretable deep learning model for antibody Fv structure prediction specializing in CDR loop modeling. | [Patterns](https://doi.org/10.1016/j.patter.2021.100406) |
| ABodyBuilder2 | ABodyBuilder2: Antibody Structure Prediction with Updated Datasets and Confidence Estimation | Deep learning model for rapid all-atom 3D structure prediction of paired antibody variable domains. | [Oxford Protein Informatics Group](https://opig.stats.ox.ac.uk/webapps/newsabdab/sabpred/abodybuilder2/) |
| ABlooper | ABlooper: Fast accurate antibody CDR loop structure prediction with accuracy estimation | Rapid equivariant neural network for antibody CDR loop structure prediction with accuracy estimation. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btac016) |
| AntiFold | AntiFold: Improved structure-based antibody design using inverse folding | Antibody-specific inverse folding model fine-tuned from ESM-IF1 for CDR sequence generation from structures. | [Bioinformatics Advances](https://arxiv.org/abs/2405.03370) |

### Antibody Design & Generation

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| IgGM | A generative foundation model for antibody design | Generative foundation model for comprehensive antibody design. | [Paper](https://www.biorxiv.org/content/10.1101/2025.09.12.675771) |
| DiffAb | Antigen-Specific Antibody Design and Optimization with Diffusion-Based Generative Models | Diffusion-based generative model for antigen-specific antibody CDR-H3 design, jointly modeling sequence, structure, and orientation. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/DiffAb) |
| dyMEAN | Full-Atom Antibody Design via dyMEAN | End-to-end full-atom antibody design using dynamic multi-channel equivariant graph network. | [ICML](https://arxiv.org/abs/2302.00203) |
| MEAN | Conditional Antibody Design as 3D Equivariant Graph Translation | 3D equivariant graph neural network for conditional antibody CDR sequence-structure co-design. | [ICLR 2023](https://openreview.net/forum?id=MEAN) |
| RefineGNN | Iterative Refinement Graph Neural Network for Antibody Sequence-Structure Co-design | Iterative refinement GNN for antibody CDR co-design of sequence and 3D structure via autoregressive generation. | [ICLR](https://arxiv.org/abs/2110.04624) |
| Ophiuchus-Ab | Ophiuchus-Ab: A Versatile Generative Foundation Model for Advanced Antibody-Based Immunotherapy | Diffusion language model for antibody immunotherapy and paired antibody repertoire generation. | [Paper](https://www.biorxiv.org/content/10.1101/2026.02.02.703197) |
| NanoAbLLaMA | NanoAbLLaMA: construction of nanobody libraries with protein large language models | LLaMA2-based language model fine-tuned for nanobody (VHH) library construction and design. | [Frontiers in Chemistry](https://doi.org/10.3389/fchem.2025.1534) |
| CoSiNE | CoSiNE: Conditionally Site-Independent Neural Evolution of Antibody Sequences | Conditionally site-independent neural evolution model explicitly modeling antibody affinity maturation. | [arXiv](https://arxiv.org/abs/2602.18982) |
| AbBFN2 | AbBFN2: A flexible antibody foundation model based on Bayesian Flow Networks | Flexible antibody foundation model based on Bayesian flow networks for multi-objective unified modeling. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.29.651170) |
| AntibodyDesignBFN | AntibodyDesignBFN: High-Fidelity Fixed-Backbone Antibody Design via Discrete Bayesian Flow Networks | High-fidelity fixed-backbone antibody design using discrete Bayesian flow networks. | [arXiv](https://arxiv.org/abs/2601.05605) |
| AbAffinity | AbAffinity: A Large Language Model for Predicting Antibody Binding Affinity | Large language model for predicting antibody-antigen binding affinity. | [arXiv](https://arxiv.org/abs/2603.04480) |
| CALM | CALM: Cross-attention Adaptive Immune Receptor–Antigen Language Model | Cross-attention language model for antibody-antigen specificity prediction. | [Paper](https://www.biorxiv.org/content/10.1101/2026.02.25.707916) |
| AFD-INSTRUCTION | AFD-INSTRUCTION: A Comprehensive Antibody Instruction Dataset with Functional Annotations for LLM-Based Understanding and Design | Large-scale antibody instruction dataset with functional annotations for LLM-based antibody understanding and design. | [arXiv](https://arxiv.org/abs/2602.04916) |
| DiffAbXL | DiffAbXL: Benchmarking generative models for antibody design | Benchmark and extended diffusion model for antibody design generative modeling. | [arXiv](https://arxiv.org/abs/DiffAbXL) |
| JAM-2 | JAM-2: Fully computational design of drug-like antibodies | Fully computational model for designing drug-like antibodies developed by Nabla Bio. | [Nabla Bio](https://www.nabla.bio/) |
| Chai-2 | Chai-2: Zero-shot antibody discovery | Zero-shot antibody discovery model developed by Chai Discovery. | [Chai Discovery](https://www.chaidiscovery.com/) |

### TCR & Immunology Models

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| TCR-BERT | TCR-BERT: learning the grammar of T-cell receptors for flexible antigen-binding analyses | Modified BERT trained on TCR sequences via self-supervised learning for antigen-specificity prediction. | [PMLR v240](https://proceedings.mlr.press/v240/) |
| tcrLM | tcrLM: a lightweight protein language model for predicting T cell receptor and epitope binding specificity | Lightweight BERT-based LM pretrained on 100M+ TCR CDR3 sequences for TCR-epitope binding prediction. | [arXiv](https://arxiv.org/abs/2406.16995) |
| TCR-GPT | TCR-GPT: Integrating Autoregressive Model and Reinforcement Learning for T-Cell Receptor Repertoires Generation | Decoder-only transformer for TCR sequence generation using autoregressive modeling with reinforcement learning. | [arXiv](https://arxiv.org/abs/2408.01156) |
| SCEPTR | Contrastive learning of T cell receptor representations | Lightweight BERT-like transformer for TCR analysis using autocontrastive and masked-language pretraining. | [Cell Systems](https://arxiv.org/abs/2406.06397) |
| ERGO-II | Prediction of Specific TCR-Peptide Binding From Large Dictionaries of TCR-Peptide Pairs | Deep learning model (LSTM + autoencoder) for TCR-peptide binding prediction using NLP techniques. | [Frontiers in Immunology](https://doi.org/10.3389/fimmu.2020.01803) |
| mvTCR | Multi-modal generative modeling for joint analysis of single-cell T cell receptor and gene expression data | Multimodal variational autoencoder integrating single-cell TCR sequences with gene expression data. | [Nature Communications](https://doi.org/10.1038/s41467-024-49806-9) |
| NetTCR-2.0 | NetTCR-2.0 enables accurate prediction of TCR-peptide binding | Deep learning model for TCR-peptide-MHC binding prediction using paired TCRα and β sequences. | [Communications Biology](https://doi.org/10.1038/s42003-021-02610-3) |
| TCR-TRANSLATE | Conditional generation of real antigen-specific T cell receptor sequences | ML framework for generating antigen-specific TCR sequences including for unseen epitopes. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01096-6) |

---

<a id="life-sciences-section-07"></a>
## Enzyme Engineering

*Foundation models for enzyme function prediction, kinetics modeling, and de novo enzyme design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| EnzyGen | Generative Enzyme Design Guided by Functionally Important Sites and Small-Molecule Substrates | Generative enzyme design model leveraging functional sites and substrate information. | [arXiv](https://arxiv.org/abs/2405.08205) |
| RFdiffusion2 | Atom-level enzyme active site scaffolding using RFdiffusion2 | Atom-level enzyme active site scaffolding tool based on RFdiffusion architecture. | [Nature Methods](https://doi.org/10.1038/s41592-025-02975-x) |
| CLEAN | Enzyme function prediction using contrastive learning | Contrastive learning model for enzyme EC number prediction, outperforming BLAST and traditional methods. | [Science](https://doi.org/10.1126/science.adf2465) |
| CLEAN-Contact | Improved enzyme functional annotation prediction using contrastive learning with structural inference | Extension of CLEAN integrating protein contact maps for improved enzyme function annotation. | [Communications Biology](https://doi.org/10.1038/s42003-024-07359-z) |
| EnzBERT | Predicting enzymatic function of protein sequences with attention | BERT-based model for predicting enzyme EC numbers from protein sequences using attention mechanisms. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btad698) |
| EnzymeFlow | EnzymeFlow: Generating Reaction-specific Enzyme Catalytic Pockets through Flow Matching and Co-Evolutionary Dynamics | Generative model using flow matching to design reaction-specific enzyme catalytic pockets. | [NeurIPS](https://arxiv.org/abs/2410.00327) |
| EnzymeCAGE | EnzymeCAGE: A Geometric Foundation Model for Enzyme Retrieval with Evolutionary Insights | Geometric foundation model trained on ~1M enzyme-reaction pairs for enzyme retrieval and function prediction. | [bioRxiv → Nature Catalysis](https://www.biorxiv.org/content/10.1101/2024.12.15.628585) |
| CatPred | CatPred: a comprehensive framework for deep learning in vitro enzyme kinetic parameters | Deep learning framework for predicting enzyme kinetic parameters (kcat, Km, Ki) from sequences. | [Nature Communications](https://doi.org/10.1038/s41467-025-57215-9) |
| UniKP | UniKP: a unified framework for the prediction of enzyme kinetic parameters | Unified deep learning framework using pretrained protein LMs to predict kcat, Km, and catalytic efficiency. | [Nature Communications](https://doi.org/10.1038/s41467-023-44113-1) |
| TurNuP | Turnover number predictions for kinetically uncharacterized enzymes using machine and deep learning | Deep learning model for predicting enzyme turnover numbers (kcat) for uncharacterized enzymes. | [Nature Communications](https://doi.org/10.1038/s41467-023-39840-4) |
| EnzyControl | EnzyControl: Adding Functional and Substrate-Specific Control for Enzyme Backbone Generation | Framework for substrate-specific enzyme backbone generation with functional control. | [arXiv](https://arxiv.org/abs/2510.25132) |
| ProtDETR | Interpretable Enzyme Function Prediction via Residue-Level Detection | Attention-based framework for residue-level enzyme EC number prediction inspired by object detection. | [arXiv](https://arxiv.org/abs/2501.05644) |
| EZpred | EZpred: improving deep learning-based enzyme function prediction using unlabeled sequence homologs | Deep learning framework leveraging unlabeled homolog sequences for improved enzyme EC prediction. | [Bioinformatics](https://pubmed.ncbi.nlm.nih.gov/) |
| BEC-Pred | A general model for predicting enzyme functions based on enzymatic reactions | BERT-based model predicting enzyme EC numbers from SMILES representations of substrates and products. | [Journal of Cheminformatics](https://doi.org/10.1186/s13321-024-00827-y) |
| HIT-EC | HIT-EC: Trustworthy prediction of enzyme commission numbers using a hierarchical interpretable transformer | Hierarchical interpretable transformer for trustworthy enzyme EC number prediction. | [Nature Communications](https://doi.org/10.1038/s41467-026-68727-3) |
| ENZYME-UNIFIED | ENZYME-UNIFIED: Learning Holistic Representations of Enzyme Function with a Hybrid Interaction Model | Holistic enzyme function representation learning via hybrid interaction modeling. | [OpenReview](https://openreview.net/forum?id=oTnFATrtCD) |

---

<a id="life-sciences-section-08"></a>
## Spatial Transcriptomics

*Foundation models for spatially resolved gene expression, tissue architecture, and histology-omics integration.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Novae | Novae: a graph-based foundation model for spatial transcriptomics data | Graph-based foundation model for spatial transcriptomics trained on 30 million cells. | [Nature Methods](https://doi.org/10.1038/s41592-025-02899-6) |
| SpaFoundation | SpaFoundation: a visual foundation model for spatial transcriptomics | Visual foundation model for spatial transcriptomics using 1.84M histological images. | [Paper](https://www.biorxiv.org/content/10.1101/2025.08.07.669202) |
| STPath | STPath: a generative foundation model for integrating spatial transcriptomics and WSIs | Generative foundation model integrating spatial transcriptomics with whole-slide histology images. | [npj Digital Medicine](https://doi.org/10.1038/s41746-025-02020-3) |
| OmiCLIP | A visual-omics foundation model to bridge histopathology with spatial transcriptomics | Visual-omics foundation model bridging histopathology images and spatial transcriptomics data. | [Nature Methods](https://doi.org/10.1038/s41592-025-02707-1) |
| SpatialFusion | SpatialFusion: A lightweight multimodal foundation model for spatial transcriptomics | Lightweight multimodal foundation model integrating gene expression, histopathology, and pathway data. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.16.712056) |
| SAGE-FM | SAGE-FM: A lightweight and interpretable foundation model for spatial transcriptomics | GCN-based lightweight and interpretable foundation model for spatial transcriptomics. | [arXiv](https://arxiv.org/abs/2601.15504) |
| scGPT-spatial | scGPT-spatial: Continual Pretraining of Single-Cell FM for Spatial Transcriptomics | Extension of scGPT for spatial transcriptomics via continual pretraining. | [Paper](https://www.biorxiv.org/content/10.1101/2025.02.05.636714) |
| SpatialScope | SpatialScope: integrating spatial and single-cell transcriptomics data using deep generative models | Deep generative model for integrating spatial transcriptomics with scRNA-seq data. | [Nature Communications](https://doi.org/10.1038/s41467-023-43629-w) |
| stFormer | stFormer: a foundation model for spatial transcriptomics | Transformer foundation model integrating ligand-receptor interactions into spatial gene representations. | [Paper](https://www.biorxiv.org/content/10.1101/2024.09.27.615337) |
| STAGE | STAGE: A Foundation Model for Spatial Transcriptomics Analysis via Graph Embeddings | Foundation model using graph embeddings and hierarchical prototypes for spatial transcriptomics. | [NeurIPS 2025 (submitted)](https://openreview.net/forum?id=STAGE) |
| STORM | STORM: A multimodal foundation model of spatial transcriptomics and histology | Multimodal spatial transcriptomics and histology foundation model trained on 1.2M spatially-resolved profiles across 18 organs. | [arXiv](https://arxiv.org/abs/2604.03630) |
| SEAL | SEAL: Spatial Expression-Aligned Learning for pathology foundation models | Spatial expression-aligned learning framework enhancing pathology foundation models with spatial transcriptomics data. | [arXiv](https://arxiv.org/abs/2602.14177) |
| MINT | MINT: Molecularly Informed Training with Spatial Transcriptomics Supervision for Pathology Foundation Models | Molecularly informed training with spatial transcriptomics supervision for pathology foundation models. | [arXiv](https://arxiv.org/abs/2603.07895) |
| HINGE | HINGE: Adapting Pre-trained Single-Cell Foundation Models to Spatial Gene Expression | Adapts pretrained single-cell foundation models to spatial gene expression using histological image conditioning. | [arXiv](https://arxiv.org/abs/2603.19766) |
| HEIST | HEIST: A Graph Foundation Model for Spatial Transcriptomics and Proteomics Data | Graph foundation model for both spatial transcriptomics and proteomics data analysis. | [arXiv](https://arxiv.org/abs/2506.11152) |
| TISSUENARRATOR | TISSUENARRATOR: Generative modeling of spatial transcriptomics with LLMs | LLM-based generative modeling framework for spatial transcriptomics data. | [arXiv](https://arxiv.org/abs/TISSUENARRATOR) |
| SpaTranslator | SpaTranslator: Deep generative framework for universal spatial multi-omics cross-modality translation | Deep generative framework for universal cross-modality translation of spatial multi-omics data. | [arXiv](https://arxiv.org/abs/SpaTranslator) |
| SpatialProp | SpatialProp: Tissue perturbation modeling with spatially resolved single-cell transcriptomics | Tissue perturbation modeling using spatially resolved single-cell transcriptomics. | [arXiv](https://arxiv.org/abs/SpatialProp) |
| SWITCH | SWITCH: Integrative deep learning of spatial multi-omics | Integrative deep learning framework for spatial multi-omics data analysis. | [arXiv](https://arxiv.org/abs/SWITCH) |
| CancerSTFormer | CancerSTFormer enables multi-scale analysis of spot-resolution spatial transcriptomes | Multi-scale spatial transcriptomics foundation model for cancer at 50µm and 250µm resolution. | [Paper](https://www.biorxiv.org/content/10.1101/2025.12.22.696102) |
| STAGATE | Deciphering spatial domains from spatially resolved transcriptomics with adaptive graph attention auto-encoder | Graph attention auto-encoder for spatial domain identification integrating gene expression and spatial location. | [Nature Communications](https://doi.org/10.1038/s41467-022-29439-6) |
| HEST-1k | HEST-1k: A Dataset for Spatial Transcriptomics and Histology Image Analysis | Benchmark dataset of 1,229 spatial transcriptomics profiles with whole-slide images across 26 organs. | [NeurIPS 2024](https://openreview.net/forum?id=HEST-1k) |
| CellViT | CellViT: Vision Transformers for precise cell segmentation and classification | Vision Transformer for precise cell/nuclei segmentation in H&E whole-slide images. | [Medical Image Analysis](https://doi.org/10.1016/j.media.2024.103143) |
| STAMP | Interpretable spatially aware dimension reduction of spatial transcriptomics with STAMP | Deep generative model for spatially-aware interpretable dimension reduction of spatial transcriptomics. | [Nature Methods](https://doi.org/10.1038/s41592-024-02463-8) |
| SpaGT | Spatially informed graph transformers for spatially resolved transcriptomics | Graph transformer integrating spatial coordinates and gene expression for spatial domain identification. | [Communications Biology](https://doi.org/10.1038/s42003-025-08015-w) |
| BrainBeacon | BrainBeacon: A Cross-Species Foundation Model for Single-cell Spatial Transcriptomics of Brain | Cross-species brain spatial transcriptomics foundation model integrating multi-species data for digital twin brain. | [Paper](https://www.biorxiv.org/content/10.1101/2025.07.08.663729) |

---

<a id="life-sciences-section-09"></a>
## Glycan

*Foundation models for glycan structure representation, protein-glycan interactions, and carbohydrate analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| GlycanGT | GlycanGT: A Foundation Model for Glycan Graphs with Pretrained Representation and Generative Learning | First glycan graph foundation model using graph transformer for glycan representation and generative learning. | [Paper](https://www.biorxiv.org/content/10.1101/2025.12.14.694171) |
| SweetBERT | Exploring BERT-based models for IUPAC glycan nomenclature | BERT-based glycan sequence language model encoding IUPAC glycan nomenclature and branching structures. | [ICLR 2025 Workshop](https://openreview.net/forum?id=BC4vd3oBXs) |
| GlycanAA | Modeling All-Atom Glycan Structures via Hierarchical Message Passing and Multi-Scale Pre-training | All-atom glycan modeling framework using hierarchical message passing and multi-scale pretraining. | [ICML](https://arxiv.org/abs/2506.01376) |
| MCNet | Atom-level machine learning of protein-glycan interactions and cross-chiral recognition | Atom-level machine learning model for protein-glycan interaction prediction including mirror-image glycan recognition. | [Science Advances](https://doi.org/10.1126/sciadv.adx6373) |
| DeepGlycanSite | Highly accurate carbohydrate-binding site prediction with DeepGlycanSite | High-accuracy deep learning model for predicting carbohydrate-binding sites on proteins. | [Nature Communications](https://doi.org/10.1038/s41467-024-49516-2) |
| SweetNet | Using graph convolutional neural networks to learn a representation for glycans | Graph convolutional neural network for glycan representation learning handling complex branching structures. | [Cell Reports](https://doi.org/10.1016/j.celrep.2022.110842) |
| GlycoBERT | Transformer-based Deep Learning for Glycan Structure Inference from MS/MS | BERT-based transformer for inferring glycan structures from tandem mass spectrometry data. | [Paper](https://www.biorxiv.org/content/10.1101/2025.07.02.662857) |

---

<a id="life-sciences-section-10"></a>
## Metabolomics

*Foundation models for metabolomic profiling, spectral analysis, and multi-disease prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MetaboLM | MetaboLM: a metabolomic language model for multi-disease early prediction and risk stratification | Transformer-based metabolomics language model trained on ~84,000 healthy plasma metabolomes for multi-disease early prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-66163-3) |
| DSCF | Deep spectral component filtering as a foundation model for spectral analysis demonstrated in metabolic profiling | Self-supervised deep spectral component filtering foundation model for metabolic profiling analysis. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01027-5) |

---

<a id="life-sciences-section-11"></a>
## Cryo-EM

*Foundation models for cryo-electron microscopy image processing, density map analysis, and structure refinement.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CryoFM | CryoFM: A Flow-based Foundation Model for Cryo-EM Densities | Flow matching-based foundation model learning high-quality biomolecular density map distributions. | [NeurIPS 2024 / bioRxiv](https://arxiv.org/abs/2410.08631) |
| Cryo-IEF | A comprehensive foundation model for cryo-EM image processing | Comprehensive cryo-EM image processing foundation model pretrained via contrastive learning on 65M particle images. | [Nature Methods](https://doi.org/10.1038/s41592-025-02916-8) |
| CryoLVM | CryoLVM: Self-supervised Learning from Cryo-EM Density Maps | Self-supervised cryo-EM density map foundation model using JEPA architecture. | [arXiv](https://arxiv.org/abs/2602.02620) |
| CryoNet.Refine | CryoNet.Refine: A One-step Diffusion Model for Rapid Refinement of Structural Models with Cryo-EM Density Map Restraints | One-step diffusion model for rapid structural model refinement with cryo-EM density map constraints. | [arXiv](https://arxiv.org/abs/2602.22263) |
| CryoDRGN-AI | CryoDRGN-AI: neural ab initio reconstruction for cryo-EM | Neural ab initio reconstruction method for heterogeneous cryo-EM data. | [Nature Methods](https://doi.org/10.1038/s41592-025-02720-4) |

---

<a id="life-sciences-section-12"></a>
## Metagenomics & Microbiome

*Foundation models for metagenomic sequencing, microbiome analysis, and pathogen monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| METAGENE-1 | Metagenomic Foundation Model for Pandemic Monitoring | 7B-parameter autoregressive transformer trained on >1.5 trillion bases of metagenomic DNA/RNA for pathogen monitoring. | [arXiv](https://arxiv.org/abs/2501.02045) |
| MGM | MGM as a large-scale pretrained foundation model for microbiome analyses in diverse contexts | Large-scale microbiome foundation model trained on >263,000 microbiome samples for diverse contexts. | [Advanced Science](https://www.biorxiv.org/content/10.1101/2024.12.30.630825) |
| BiomeGPT | BiomeGPT: A foundation model for the human gut microbiome | Transformer-based human gut microbiome foundation model trained on >13,300 metagenomic samples. | [Paper](https://www.biorxiv.org/content/10.1101/2026.01.05.697599) |
| GenomeOcean | GenomeOcean: An Efficient Genome Foundation Model Trained on Large-Scale Metagenomic Assemblies | Efficient 4B-parameter genome foundation model trained on large-scale metagenomic assemblies (>600 Gbp). | [Paper](https://www.biorxiv.org/content/10.1101/2025.01.30.635558) |
| MicroGenomer | MicroGenomer: A Foundation Model for Transferable Microbial Genome Representations | Transferable microbial genome representation model trained on >234.5B base pairs for multi-scale analysis. | [bioRxiv (BGI Research)](https://www.biorxiv.org/content/10.1101/2025.12.28.696777) |
| Generanno | Generanno: A Genomic Foundation Model for Metagenomic Annotation | Genomic foundation model for metagenomic annotation trained on 715B prokaryotic base pairs. | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.04.656517) |
| FGBERT | FGBERT: Function-Driven Pre-trained Gene Language Model for Metagenomics | Function-driven pretrained gene language model using protein-level context-aware tokenizer for metagenomics. | [arXiv](https://arxiv.org/abs/2402.16901) |
| MetagenBERT | MetagenBERT: a Transformer Architecture using Foundational DNA Read Embedding Models for novel Metagenome Representation | Transformer framework using DNABERT-2/DNABERT-S for metagenome representation from raw DNA reads. | [arXiv](https://arxiv.org/abs/2601.03295) |
| Darwin-7B | Darwin-7B: A Large Language Model for Metagenomics and Microbial Ecology | 7B-parameter LLM trained on microbial genomes and metagenomic data for species classification and functional annotation. | [arXiv](https://arxiv.org/abs/Darwin-7B) |
| EDEN | EDEN: 28 Billion Parameters for Programming Biology | 28B-parameter foundation model trained on 9.7 trillion nucleotide tokens for biological engineering. | [ICG-20](https://www.basecampresearch.com/) |
| ViraLM | ViraLM: virus discovery through genome foundation model | Virus genome foundation model for virus discovery from metagenomic sequences. | [Bioinformatics](https://www.biorxiv.org/content/10.1101/2024.01.30.577935) |

---

<a id="life-sciences-section-13"></a>
## Phylogenetics & Evolution

*Foundation models for phylogenetic tree inference and evolutionary genomic modeling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Phyla | Phyla: Towards a Foundation Model for Phylogenetic Inference | First phylogenetic inference foundation model using hybrid state-space transformer with tree loss function. | [ICLR](https://www.biorxiv.org/content/10.1101/2025.01.17.633626) |
| PhyloGPN | A Phylogenetic Approach to Genomic Language Modeling | Phylogenetic tree-based genomic language model using multi-species whole-genome alignments and evolutionary models. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2503.03773) |

---

<a id="life-sciences-section-14"></a>
## Multi-Omics Integration

*Foundation models for integrating DNA, RNA, protein, and other multi-omic data modalities.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OmniBioTE | Large-Scale Multi-omic Biosequence Transformers for Modeling Protein-Nucleic Acid Interactions | Large-scale multi-omic biosequence transformer trained on >250B tokens of protein and nucleic acid sequences. | [PLOS ONE](https://arxiv.org/abs/2408.16245) |
| Omni-DNA | Omni-DNA: A Unified Genomic Foundation Model for Cross-Modal and Multi-Task Learning | Unified genomic foundation model supporting DNA/RNA/protein cross-modal multi-task learning from Microsoft. | [NeurIPS 2025 (Microsoft)](https://arxiv.org/abs/2502.03499) |
| OmniNA | OmniNA: A foundation model for nucleotide sequences | Nucleotide sequence foundation model pretrained on >91.7M sequences (>1 trillion bases) for cross-species understanding. | [Paper](https://www.biorxiv.org/content/10.1101/2024.01.14.575543) |
| spEMO | Leveraging multi-modal foundation models for analysing spatial multi-omic and histopathology data | Multi-modal foundation model framework integrating spatial multi-omics with histopathology image data. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-025-01602-6) |
| scMamba | scMamba: A Scalable Foundation Model for Single-Cell Multi-Omics Integration Beyond Highly Variable Feature Selection | Scalable Mamba-based foundation model for single-cell multi-omics integration without feature selection. | [arXiv](https://arxiv.org/abs/2506.20697) |

---

<a id="life-sciences-section-15"></a>
## Epigenomics

*Foundation models for DNA methylation, chromatin modifications, and epigenetic regulation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CpGPT | CpGPT: A Foundation Model for DNA Methylation | DNA methylation foundation model predicting CpG site methylation states for aging and disease research. | [Paper](https://www.biorxiv.org/content/10.1101/2024.10.24.620080) |
| MethylGPT | MethylGPT: A Foundation Model for the DNA Methylome | DNA methylome foundation model pretrained on large-scale methylation data for epigenetic age prediction and cancer classification. | [Paper](https://www.biorxiv.org/content/10.1101/2024.10.30.621013) |
| scDNAm-GPT | scDNAm-GPT: A Foundation Model for Single-Cell DNA Methylation Analysis | Single-cell DNA methylation analysis foundation model for resolving epigenetic heterogeneity at single-cell resolution. | [Paper](https://www.biorxiv.org/content/10.1101/scDNAm-GPT) |

---

<a id="life-sciences-section-16"></a>
## Mass Spectrometry

*Foundation models for mass spectrometry-based proteomics, metabolomics, and compound identification.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DIA-BERT | DIA-BERT: A Foundation Model for Data-Independent Acquisition Proteomics | Transformer-based foundation model for data-independent acquisition proteomics, improving peptide identification and quantification. | [Paper](https://www.biorxiv.org/content/10.1101/2024.02.01.578401) |
| DreaMS | DreaMS: Deep Representations Empowering the Annotation of Mass Spectra | Deep representation learning foundation model for mass spectra annotation and metabolite identification. | [Nature Biotechnology](https://doi.org/10.1038/s41587-025-02689-7) |
| LSM-MS2 | LSM-MS2: Large-Scale Mass Spectrometry Foundation Model | Large-scale tandem mass spectrometry foundation model pretrained on millions of MS2 spectra for compound identification. | [Paper](https://www.biorxiv.org/content/10.1101/LSM-MS2) |
| OmniNovo | OmniNovo: A Universal Foundation Model for De Novo Peptide Sequencing | Universal foundation model for de novo peptide sequencing directly from mass spectrometry data. | [Paper](https://www.biorxiv.org/content/10.1101/OmniNovo) |
| MS-FM | Foundation model for mass spectrometry proteomics | Unified mass spectrometry proteomics foundation model pretrained on de novo sequencing data. | [arXiv](https://arxiv.org/abs/2505.10848) |
| InstaNovo | InstaNovo: diffusion-powered de novo peptide sequencing | Diffusion-powered model for de novo peptide sequencing from mass spectrometry data. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01019-5) |

---

<a id="life-sciences-section-17"></a>
## Neuroscience

*Foundation models for neural activity prediction, brain imaging, and computational neuroscience.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| VFAM | Foundation model of neural activity predicts response to new stimulus types | Neural activity foundation model trained on large-scale mouse visual cortex data, predicting responses to novel stimulus types. | [Nature](https://doi.org/10.1038/s41586-025-08829-y) |

---

<a id="life-sciences-section-18"></a>
## Synthetic Biology

*Foundation models for designing synthetic regulatory elements and engineering biological systems.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DNA-Diffusion | Designing synthetic regulatory elements using DNA-Diffusion | Generative diffusion model for designing synthetic DNA regulatory elements. | [Nature Genetics](https://doi.org/10.1038/s41588-025-02441-6) |
