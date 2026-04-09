# Scientific Foundation Models

<p align="right"><strong>Language:</strong> English | <a href="README.zh.md">中文</a></p>

A bilingual catalog of scientific foundation models across nine major scientific domains.

Models with clear interdisciplinary relevance may appear in more than one domain.

## Browse by Domain

| Domain | Folder | English | Chinese |
|--------|--------|---------|---------|
| Life Sciences | `life-sciences/` | [English](life-sciences/life-sciences_en.md) | [Chinese](life-sciences/life-sciences_zh.md) |
| Chemistry | `chemistry/` | [English](chemistry/chemistry_en.md) | [Chinese](chemistry/chemistry_zh.md) |
| Materials Science | `materials-science/` | [English](materials-science/materials-science_en.md) | [Chinese](materials-science/materials-science_zh.md) |
| Physics | `physics/` | [English](physics/physics_en.md) | [Chinese](physics/physics_zh.md) |
| Earth Sciences | `earth-sciences/` | [English](earth-sciences/earth-sciences_en.md) | [Chinese](earth-sciences/earth-sciences_zh.md) |
| Astronomy | `astronomy/` | [English](astronomy/astronomy_en.md) | [Chinese](astronomy/astronomy_zh.md) |
| Medicine & Biomedicine | `medicine/` | [English](medicine/medicine_en.md) | [Chinese](medicine/medicine_zh.md) |
| Mathematics & Scientific Reasoning | `mathematics/` | [English](mathematics/mathematics_en.md) | [Chinese](mathematics/mathematics_zh.md) |
| Agriculture & Ecology | `agriculture-ecology/` | [English](agriculture-ecology/agriculture-ecology_en.md) | [Chinese](agriculture-ecology/agriculture-ecology_zh.md) |

## Domains
- [Life Sciences](#life-sciences)
- [Chemistry](#chemistry)
- [Materials Science](#materials-science)
- [Physics](#physics)
- [Earth Sciences](#earth-sciences)
- [Astronomy](#astronomy)
- [Medicine & Biomedicine](#medicine--biomedicine)
- [Mathematics & Scientific Reasoning](#mathematics--scientific-reasoning)
- [Agriculture & Ecology](#agriculture--ecology)

## Life Sciences

> [English](life-sciences/life-sciences_en.md) | [Chinese](life-sciences/life-sciences_zh.md)

### Table of Contents
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
### Protein

#### Protein Language Models

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

#### Protein Structure Prediction

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

#### Protein Design & Generation

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
| Genie | Genie: SE(3)-equivariant generative model for protein backbone design | SE(3)-equivariant DDPM model for protein backbone design. | [ICML](https://arxiv.org/abs/2301.12485) |
| Genie 2 | Out of many, one: Designing and scaffolding proteins at the scale of the structural universe with Genie 2 | Upgraded Genie capturing a broader and more diverse protein structure space. | [DeepMind](https://arxiv.org/abs/2405.15489) |
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

#### Peptide Foundation Models

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

#### Protein–Protein Interaction Models

*Models predicting protein–protein interactions and complex structures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PLM-interact | PLM-interact: extending protein language models to predict protein-protein interactions | Extension of protein language models for PPI prediction by jointly encoding protein pairs from sequences alone. | [Nature Communications](https://doi.org/10.1038/s41467-025-64512-w) |
| IntFold | IntFold: A Controllable Foundation Model for General and Specialized Biomolecular Structure Prediction | Controllable biomolecular structure prediction foundation model matching AlphaFold3 accuracy with support for PPI complexes and allosteric states. | [arXiv](https://arxiv.org/abs/2507.02025) |

#### Protein Dynamics

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
### RNA

#### RNA Language Models

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

#### RNA Structure Prediction

*Deep learning methods for RNA 2D and 3D structure prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RhoFold+ | Accurate RNA 3D structure prediction using a language model-based deep learning approach | Pretrained RNA language model-based approach for accurate RNA 3D structure prediction trained on 23.7 million sequences. | [Nature Methods](https://doi.org/10.1038/s41592-024-02487-0) |
| RhoFold | RhoFold: Fast and accurate RNA 3D structure prediction | Deep learning model for fast and accurate RNA 3D structure prediction from CUHK. | [CUHK](https://proj.cse.cuhk.edu.hk/aihlab/rhofold/) |
| RNA-FrameFlow | Flow Matching for de novo 3D RNA Backbone Design | SE(3) flow matching method for de novo 3D RNA backbone structure generation. | [arXiv](https://arxiv.org/abs/2406.13839) |
| DRfold2 | Ab initio RNA structure prediction with composite language model | Deep learning framework for ab initio RNA 3D structure prediction using a composite language model. | [Paper](https://doi.org/10.1101/2025.03.05.641632) |
| 3DRNALM | Accurate RNA 3D structure prediction using a language model-based framework | Language model-based framework for accurate RNA 3D structure prediction. | [Nature Communications](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11621015/) |
| NuFold | NuFold: end-to-end approach for RNA tertiary structure prediction | End-to-end deep learning model for RNA tertiary structure prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-56261-7) |

#### RNA Design & Generation

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
### DNA & Genomics

#### DNA

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
### Single-Cell Biology

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

#### Virtual Cell Models

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AlphaCell | Towards building a World Model to simulate perturbation-induced cellular dynamics | Virtual cell world model that simulates perturbation-induced cellular dynamics. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.02.709176) |
| CellFluxV2 | CellFluxV2: An Image Generative Foundation Model for Virtual Cell Modeling | Flow matching-based generative foundation model for virtual cell image modeling. | [Paper](https://www.biorxiv.org/content/10.1101/2026.01.19.696785) |
| X-Cell | X-Cell: Scaling Causal Perturbation Prediction Across Diverse Cellular Contexts | Large-scale diffusion language model predicting genome-wide transcriptional responses across diverse cellular contexts. | [Paper](https://www.biorxiv.org/content/10.1101/2026.03.18.712807) |

---

<a id="life-sciences-section-05"></a>
### Multi-Scale Biology

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
### Antibody & Immunology

*Foundation models for antibody engineering, structure prediction, and immune receptor analysis.*

#### Antibody Language Models

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

#### Antibody Structure Prediction

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| IgFold | Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies | Fast antibody structure prediction using pretrained LM on 558M sequences with graph neural networks. | [Nature Communications](https://doi.org/10.1038/s41467-023-38063-x) |
| DeepAb | Antibody structure prediction using interpretable deep learning | Interpretable deep learning model for antibody Fv structure prediction specializing in CDR loop modeling. | [Patterns](https://doi.org/10.1016/j.patter.2021.100406) |
| ABodyBuilder2 | ABodyBuilder2: Antibody Structure Prediction with Updated Datasets and Confidence Estimation | Deep learning model for rapid all-atom 3D structure prediction of paired antibody variable domains. | [Oxford Protein Informatics Group](https://opig.stats.ox.ac.uk/webapps/newsabdab/sabpred/abodybuilder2/) |
| ABlooper | ABlooper: Fast accurate antibody CDR loop structure prediction with accuracy estimation | Rapid equivariant neural network for antibody CDR loop structure prediction with accuracy estimation. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btac016) |
| AntiFold | AntiFold: Improved structure-based antibody design using inverse folding | Antibody-specific inverse folding model fine-tuned from ESM-IF1 for CDR sequence generation from structures. | [Bioinformatics Advances](https://arxiv.org/abs/2405.03370) |

#### Antibody Design & Generation

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

#### TCR & Immunology Models

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
### Enzyme Engineering

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
### Spatial Transcriptomics

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
### Glycan

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
### Metabolomics

*Foundation models for metabolomic profiling, spectral analysis, and multi-disease prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MetaboLM | MetaboLM: a metabolomic language model for multi-disease early prediction and risk stratification | Transformer-based metabolomics language model trained on ~84,000 healthy plasma metabolomes for multi-disease early prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-66163-3) |
| DSCF | Deep spectral component filtering as a foundation model for spectral analysis demonstrated in metabolic profiling | Self-supervised deep spectral component filtering foundation model for metabolic profiling analysis. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01027-5) |

---

<a id="life-sciences-section-11"></a>
### Cryo-EM

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
### Metagenomics & Microbiome

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
### Phylogenetics & Evolution

*Foundation models for phylogenetic tree inference and evolutionary genomic modeling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Phyla | Phyla: Towards a Foundation Model for Phylogenetic Inference | First phylogenetic inference foundation model using hybrid state-space transformer with tree loss function. | [ICLR](https://www.biorxiv.org/content/10.1101/2025.01.17.633626) |
| PhyloGPN | A Phylogenetic Approach to Genomic Language Modeling | Phylogenetic tree-based genomic language model using multi-species whole-genome alignments and evolutionary models. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2503.03773) |

---

<a id="life-sciences-section-14"></a>
### Multi-Omics Integration

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
### Epigenomics

*Foundation models for DNA methylation, chromatin modifications, and epigenetic regulation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CpGPT | CpGPT: A Foundation Model for DNA Methylation | DNA methylation foundation model predicting CpG site methylation states for aging and disease research. | [Paper](https://www.biorxiv.org/content/10.1101/2024.10.24.620080) |
| MethylGPT | MethylGPT: A Foundation Model for the DNA Methylome | DNA methylome foundation model pretrained on large-scale methylation data for epigenetic age prediction and cancer classification. | [Paper](https://www.biorxiv.org/content/10.1101/2024.10.30.621013) |
| scDNAm-GPT | scDNAm-GPT: A Foundation Model for Single-Cell DNA Methylation Analysis | Single-cell DNA methylation analysis foundation model for resolving epigenetic heterogeneity at single-cell resolution. | [Paper](https://www.biorxiv.org/content/10.1101/scDNAm-GPT) |

---

<a id="life-sciences-section-16"></a>
### Mass Spectrometry

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
### Neuroscience

*Foundation models for neural activity prediction, brain imaging, and computational neuroscience.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| VFAM | Foundation model of neural activity predicts response to new stimulus types | Neural activity foundation model trained on large-scale mouse visual cortex data, predicting responses to novel stimulus types. | [Nature](https://doi.org/10.1038/s41586-025-08829-y) |

---

<a id="life-sciences-section-18"></a>
### Synthetic Biology

*Foundation models for designing synthetic regulatory elements and engineering biological systems.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DNA-Diffusion | Designing synthetic regulatory elements using DNA-Diffusion | Generative diffusion model for designing synthetic DNA regulatory elements. | [Nature Genetics](https://doi.org/10.1038/s41588-025-02441-6) |

## Chemistry

> [English](chemistry/chemistry_en.md) | [Chinese](chemistry/chemistry_zh.md)

### Table of Contents
- [Small Molecules](#chemistry-section-01)
- [Reactions & Retrosynthesis](#chemistry-section-02)
- [Protein-Ligand Interactions](#chemistry-section-03)
- [3D Equivariant Molecular Representations](#chemistry-section-04)
- [Molecular Generation & Diffusion](#chemistry-section-05)
- [Spectroscopy & Analytical Chemistry](#chemistry-section-06)
- [Food Science](#chemistry-section-07)
- [Electrochemistry](#chemistry-section-08)

<a id="chemistry-section-01"></a>
### Small Molecules

*Foundation models for molecular property prediction, representation learning, and chemical language modeling on SMILES and molecular graphs.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MoLFormer | Large-Scale Chemical Language Representations Capture Molecular Structure and Properties | Transformer-based chemical language model pretrained on 1.1B SMILES with linear attention and rotary embeddings for molecular property prediction. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-022-00580-7) |
| GP-MoLFormer | GP-MoLFormer: A Foundation Model For Molecular Generation | Transformer-based generative foundation model with 46.8M parameters trained on 1.1B SMILES for molecular generation tasks. | [Digital Discovery](https://arxiv.org/abs/2405.04912) |
| ChemBERTa | ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction | RoBERTa-based chemical language model pretrained on 10M PubChem SMILES for molecular property prediction. | [NeurIPS ML4Molecules Workshop](https://arxiv.org/abs/2010.09885) |
| ChemBERTa-2 | ChemBERTa-2: Towards Chemical Foundation Models | Evolved ChemBERTa pretrained on 77M PubChem SMILES with optimized pretraining strategies including multi-task regression. | [arXiv](https://arxiv.org/abs/2209.01712) |
| ChemBERTa-3 | ChemBERTa-3: An Open Source Training Framework for Chemical Foundation Models | Open-source training framework extending the ChemBERTa series for building chemical foundation models. | [Artificial Intelligence in the Life Sciences](https://doi.org/10.1016/j.ailsci.2026.100112) |
| ChemFM | ChemFM as a Scaling Law Guided Foundation Model Pre-trained on Informative Chemicals | 3B-parameter chemical foundation model trained on 178M UniChem molecules using self-supervised causal language modeling guided by scaling laws. | [Communications Chemistry](https://arxiv.org/abs/2410.21422) |
| ChemDFM | Developing ChemDFM as a Large Language Foundation Model for Chemistry | LLaMA-13B-based chemistry LLM trained on 34B tokens of chemical literature and fine-tuned with 2.7M instruction pairs. | [Cell Reports Physical Science](https://arxiv.org/abs/2401.14818) |
| Uni-Mol | Uni-Mol: A Universal 3D Molecular Representation Learning Framework | Universal 3D molecular representation learning framework that directly leverages molecular 3D structures for pretraining and achieves SOTA on property prediction. | [ICLR](https://arxiv.org/abs/2204.07599) |
| Uni-Mol2 | Uni-Mol2: Exploring Molecular Pretraining Model at Scale | Largest 3D molecular foundation model (1.1B parameters) with dual-track Transformer integrating atomic, graph, and 3D geometric features trained on 884M molecules. | [NeurIPS](https://arxiv.org/abs/2406.14969) |
| MolBERT | MolBERT: Molecular Representation Learning with Language Models and Domain-Relevant Auxiliary Tasks | BERT-based molecular representation model using SMILES with self-supervised auxiliary tasks for meaningful molecular embeddings. | [arXiv](https://arxiv.org/abs/2011.13230) |
| GROVER | Self-Supervised Graph Transformer on Large-Scale Molecular Data | Self-supervised graph Transformer combining GNN message passing with Transformer attention, pretrained on large-scale molecular data. | [NeurIPS](https://arxiv.org/abs/2007.02835) |
| GEM | Geometry-Enhanced Molecular Representation Learning for Property Prediction | Geometry-enhanced molecular representation learning framework that exploits 3D spatial structure information for improved property prediction. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-021-00438-4) |
| Graphormer | Do Transformers Really Perform Bad for Graph Representation? | Graph Transformer framework from Microsoft that won 1st place on OGB-LSC molecular tasks, introducing spatial and edge encodings for graph structure modeling. | [NeurIPS](https://arxiv.org/abs/2106.05234) |
| MoleculeSTM | Multi-modal Molecule Structure-text Model for Text-based Retrieval and Editing | Multi-modal model jointly learning molecular structures and text descriptions for text-driven molecular retrieval and editing. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00759-6) |
| 3D-MoLM | Towards 3D Molecule-Text Interpretation in Language Models | Pioneering framework integrating a 3D molecular encoder with language models via a 3D molecule-text projector for LLM-based molecular understanding. | [ICLR](https://arxiv.org/abs/2401.13923) |
| MolE | MolE: A Foundation Model for Molecular Graphs Using Disentangled Attention | Molecular graph foundation model from Recursion using disentangled-attention Transformers, pretrained in two self-supervised stages on ~842M molecules. | [Nature Communications](https://doi.org/10.1038/s41467-024-53751-y) |
| MiniMol | MiniMol: A Parameter-Efficient Foundation Model for Molecular Learning | Parameter-efficient molecular foundation model (only 10M parameters) pretrained on 3,300+ diverse bioactivity datasets from 6M molecules. | [ICML](https://arxiv.org/abs/2404.14986) |
| SMILES-Mamba | SMILES-Mamba: Chemical Mamba Foundation Models for Drug ADMET Prediction | Mamba-architecture chemical foundation model with two-stage training (self-supervised pretraining + supervised fine-tuning) for drug ADMET prediction. | [NeurIPS 2024 Workshop](https://arxiv.org/abs/2408.05696) |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | Large-scale SMILES encoder-decoder foundation model from IBM, self-supervised on 91M PubChem SMILES for chemistry and materials science. | [ICLR 2024 Workshop](https://openreview.net/forum?id=Yq8At31hLi) |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | Knowledge-guided graph Transformer pretraining framework integrating chemical knowledge to enhance molecular representation learning. | [Nature Communications](https://doi.org/10.1038/s41467-023-43214-1) |
| GIN (Pretrained) | Strategies for Pre-Training Graph Neural Networks | Pioneering work proposing GNN pretraining strategies (node-level + graph-level) with GIN pretrained on 2M molecules for property prediction. | [ICLR](https://arxiv.org/abs/1905.12265) |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Family of large-scale molecular foundation models (Molecular Insight SMILES Transformers) trained on vast unlabeled molecules, predicting 400+ structure-property relationships. | [arXiv](https://arxiv.org/abs/2510.18900) |
| M2UMol | Multi-to-Uni Modal Knowledge Transfer Pre-training for Molecular Representation Learning | Multi-modal to uni-modal knowledge transfer pretraining framework that distills diverse molecular modality knowledge into a 2D encoder. | [Nature Communications](https://doi.org/10.1038/s41467-026-69302-6) |
| Chemprop (D-MPNN) | Analyzing Learned Molecular Representations for Property Prediction | Directed message passing neural network for molecular property prediction with learned representations. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.9b00237) |
| Omni-Mol | Exploring Universal Convergent Space for Omni-Molecular Tasks | Unified language model enabling any-to-any modality molecular tasks in a universal convergent space. | [NeurIPS](https://arxiv.org/abs/2502.01074) |
| ADMET-AI | ADMET-AI: A Machine Learning ADMET Platform | Machine learning platform for rapid ADMET property prediction across large chemical libraries. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btae416) |
| TamGen | TamGen: Drug Design with Target-Aware Molecule Generation through a Chemical Language Model | GPT-style chemical language model for target-aware molecule generation and drug design. | [Nature Communications](https://doi.org/10.1038/s41467-024-53632-4) |
| MoleculeGPT | MoleculeGPT: Instruction Following LLMs for Molecular Property Prediction | LLM fine-tuned with molecular instruction data for natural-language-driven molecular property prediction. | [NeurIPS 2024 Workshop](https://arxiv.org/abs/2306.09048) |
| SAFE-GPT | SAFE: A Molecular-Centric Foundation Model with SAFE Representation | Foundation model using Sequential Attachment-based Fragment Embedding (SAFE) molecular representation for generative chemistry. | [Digital Discovery](https://doi.org/10.1039/D4DD00019F) |
| DrugGPT | DrugGPT: A GPT-based Strategy for Designing Potential Ligands Targeting Specific Proteins | GPT-based drug design model that generates drug-like molecules targeting specific protein binding pockets. | [Paper](https://www.biorxiv.org/content/10.1101/2023.06.29.543848) |
| MultiPUFFIN | Multimodal domain-constrained foundation model | Multi-modal domain-constrained foundation model integrating SMILES, molecular graphs, and 3D geometry for molecular understanding. | [arXiv](https://arxiv.org/abs/2603.00857) |
| FragCLM | Foundation chemical language model for fragment-based drug discovery | Foundation chemical language model trained on the ZINC-22 fragment dataset for comprehensive fragment-based drug discovery. | [arXiv](https://arxiv.org/abs/2509.19586) |

---

<a id="chemistry-section-02"></a>
### Reactions & Retrosynthesis

*Foundation models for chemical reaction prediction, retrosynthetic planning, and synthesis route design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Molecular Transformer | Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction | Pioneering seq2seq Transformer that frames chemical reaction prediction as SMILES translation with uncertainty calibration. | [ACS Central Science](https://doi.org/10.1021/acscentsci.9b00576) |
| Chemformer | Chemformer: A Pre-trained Transformer for Computational Chemistry | BART-based pretrained Transformer for reaction prediction, retrosynthesis, and other computational chemistry tasks over molecular SMILES. | [Machine Learning: Science and Technology](https://doi.org/10.1088/2632-2153/ac3ffb) |
| RXNFP | Mapping the Space of Chemical Reactions Using Attention-Based Neural Networks | Transformer model from IBM that learns chemical reaction fingerprints for reaction classification and reaction space mapping. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-020-00284-w) |
| T5Chem | Unified Deep Learning Model for Multitask Reaction Predictions with Explanation | T5-based unified Transformer supporting multi-task chemical reaction predictions including forward synthesis, retrosynthesis, and yield prediction. | [Journal of Chemical Information and Modeling](https://doi.org/10.1021/acs.jcim.1c01467) |
| LocalRetro | Deep Retrosynthetic Reaction Prediction Using Local Reactivity and Global Attention | Deep learning retrosynthesis framework emphasizing local chemical reactivity and global attention, achieving SOTA among semi-template methods. | [JACS Au](https://doi.org/10.1021/jacsau.1c00246) |
| Retroformer | Retroformer: Pushing the Limits of Interpretable End-to-end Retrosynthesis Transformer | End-to-end retrosynthesis Transformer with local attention that jointly encodes molecular sequences and graphs in a template-free approach. | [ICML](https://arxiv.org/abs/2201.12475) |
| Llamole | Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning | Multi-modal LLM integrating graph diffusion Transformer and GNN for inverse molecular design with retrosynthetic route planning. | [NeurIPS](https://arxiv.org/abs/2410.04223) |
| RetroSynFormer | Retrosynformer: Planning Multi-step Chemical Synthesis Routes via a Decision Transformer | Decision Transformer for multi-step retrosynthetic planning that models retrosynthesis as a sequence prediction problem. | [Digital Discovery](https://doi.org/10.1039/D5DD00153F) |
| SynLlama | SynLlama: Generating Synthesizable Molecules and Their Analogs with Large Language Models | LLM fine-tuned from Meta Llama 3 for generating synthesizable molecules along with complete synthesis routes. | [ACS Central Science](https://arxiv.org/abs/2503.12602) |
| SynFormer | Generative Artificial Intelligence for Navigating Synthesizable Chemical Space | Generative model framework for exploring synthesizable chemical space, ensuring generated molecules are synthetically accessible. | [PNAS](https://arxiv.org/abs/2410.03494) |
| ReactionT5 | ReactionT5: A Pre-trained Transformer Model for Accurate Chemical Reaction Prediction with Limited Data | T5-based pretrained Transformer for chemical reaction prediction, pretrained on the Open Reaction Database and excelling with limited data. | [Journal of Cheminformatics](https://doi.org/10.1186/s13321-025-01075-4) |
| DeepRetro | DeepRetro Discovers Retrosynthetic Pathways Through Iterative Large Language Model Reasoning | Advanced retrosynthesis framework combining LLM reasoning, reaction templates, and expert feedback for iterative pathway discovery. | [Scientific Reports](https://doi.org/10.1038/s41598-026-38821-z) |
| RXNGraphormer | A unified pre-trained deep learning framework for cross-task reaction performance prediction | Unified pretrained reaction graph Transformer integrating GNN and Transformer to learn bond formation/breaking mechanisms across tasks. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01098-4) |
| RSGPT | RSGPT: a generative transformer for retrosynthesis planning pre-trained on ten billion datapoints | Generative Transformer for retrosynthesis planning pretrained on 10 billion datapoints for large-scale synthetic route prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-62308-6) |
| RetroChimera | Chemist-aligned retrosynthesis by ensembling diverse inductive biases | Frontier retrosynthesis model from Microsoft built on ensembling complementary models with diverse inductive biases. | [NeurIPS](https://arxiv.org/abs/2412.05269) |
| Chem-R | Chem-R: Learning to Reason as a Chemist | Chemical reasoning model that emulates chemists' deep thinking processes through a three-phase training framework. | [NeurIPS](https://arxiv.org/abs/2510.16880) |
| DeepMech | DeepMech: A Machine Learning Framework for Chemical Reaction Mechanism Prediction | Graph deep learning framework for predicting complete chemical reaction mechanisms with interpretable outputs. | [arXiv](https://arxiv.org/abs/2509.15872) |

---

<a id="chemistry-section-03"></a>
### Protein-Ligand Interactions

*Foundation models for molecular docking, binding affinity prediction, and protein-ligand complex structure prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Pearl | Pearl: A Foundation Model for Placing Every Atom in the Right Location | Protein-ligand structure prediction foundation model from Genesis Molecular AI using large-scale synthetic data and SO(3)-equivariant architecture, surpassing AlphaFold 3. | [NeurIPS](https://arxiv.org/abs/2510.24670) |
| DiffDock | DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking | Diffusion-based molecular docking method that models protein-ligand docking as a generative problem on SE(3) without requiring prior binding site knowledge. | [ICLR](https://arxiv.org/abs/2210.01776) |
| DiffDock-L | Fine-Tuning DiffDock-L for Allosteric Kinase Docking | Large-scale DiffDock variant fine-tuned for allosteric kinase binding site docking. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.5c02846) |
| NeuralPLexer | State-specific Protein-Ligand Complex Structure Prediction with a Multiscale Deep Generative Model | Multi-scale deep generative model that predicts protein-ligand complex 3D structures directly from protein sequence and ligand graph, including conformational changes. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-024-00792-z) |
| TankBind | TANKBind: Trigonometry-Aware Neural Networks for Drug-Protein Binding Structure Prediction | Trigonometry-aware neural network that segments proteins into functional blocks with geometric constraints for drug-protein binding structure prediction. | [NeurIPS 2022](https://proceedings.neurips.cc/paper_files/paper/2022/hash/2f89a23a19d1617e7fb16d4f7a049ce2-Abstract-Conference.html) |
| Uni-Mol Docking V2 | Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction | Molecular docking method in the Uni-Mol series using pretrained molecular and pocket encoders to predict protein-ligand binding poses with >77% success rate. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2405.11769) |
| FABind | FABind: Fast and Accurate Protein-Ligand Binding | End-to-end model integrating ligand-guided pocket prediction and docking for fast and accurate protein-ligand binding structure prediction. | [NeurIPS 2023](https://arxiv.org/abs/2310.06763) |
| EquiBind | EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction | SE(3)-equivariant GNN that directly predicts drug-protein binding sites and ligand poses without sampling. | [ICML](https://arxiv.org/abs/2202.05146) |
| Umol | Structure Prediction of Protein-Ligand Complexes from Sequence Information with Umol | AI system predicting full-flexibility, all-atom protein-ligand complex structures solely from amino acid sequence and SMILES. | [Nature Communications](https://doi.org/10.1038/s41467-024-48837-6) |
| LigUnity | A Foundation Model for Protein-Ligand Affinity Prediction Through Unified Representation | Unified representation learning foundation model for protein-ligand affinity prediction supporting both virtual screening and lead optimization. | [bioRxiv preprint](https://www.biorxiv.org/content/10.1101/2025.02.17.638554) |
| PhysDock | PhysDock: A Physics-Guided All-Atom Diffusion Model for Protein-Ligand Complex Prediction | Physics-guided all-atom diffusion model for protein-ligand complex prediction integrating detailed atomic-level flexibility modeling. | [Paper](https://www.biorxiv.org/content/10.1101/2025.04.28.650887) |
| Boltz-2 | Boltz-2: Towards Accurate and Efficient Binding Affinity Prediction | Advanced model for accurate and efficient protein-ligand binding affinity prediction building on AlphaFold3 and Boltz-1 architectures. | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.14.659707) |
| DiffSBDD | Structure-based drug design with equivariant diffusion models | SE(3)-equivariant diffusion model that generates 3D molecular ligands conditioned on protein binding pockets for structure-based drug design. | [Nature Comp. Sci.](https://doi.org/10.1038/s43588-024-00737-x) |

---

<a id="chemistry-section-04"></a>
### 3D Equivariant Molecular Representations

*Equivariant and invariant neural network architectures for learning 3D molecular representations, energy prediction, and force fields.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SchNet | SchNet: A Continuous-filter Convolutional Neural Network for Modeling Quantum Interactions | Continuous-filter convolutional neural network learning rotationally invariant representations of quantum interactions for molecular energy and force prediction. | [NeurIPS 2017](https://doi.org/10.1063/1.5019779) |
| DimeNet | Directional Message Passing for Molecular Graphs | Directional message passing neural network leveraging inter-atomic distances and angles with spherical Bessel basis functions for molecular property prediction. | [ICLR](https://arxiv.org/abs/2003.03123) |
| DimeNet++ | Fast and Uncertainty-Aware Directional Message Passing for Non-Equilibrium Molecules | Efficient DimeNet variant achieving 8× speedup through architectural optimizations while maintaining prediction accuracy. | [NeurIPS 2020 Workshop](https://arxiv.org/abs/2011.14115) |
| PaiNN | Equivariant Message Passing for the Prediction of Tensorial Properties and Molecular Spectra | Polarizable atom interaction network using equivariant message passing to jointly update scalar and vector features for tensorial property and spectrum prediction. | [ICML](https://arxiv.org/abs/2102.03150) |
| GemNet | GemNet: Universal Directional Graph Neural Networks for Molecules | Universal directional graph neural network using geometric message passing and dihedral angle information for SOTA molecular property prediction. | [NeurIPS](https://arxiv.org/abs/2106.08903) |
| GemNet-OC | GemNet-OC: Developing Graph Neural Networks for Large and Diverse Molecular Simulation Datasets | GemNet variant optimized for the Open Catalyst large-scale dataset with improved computational efficiency and generalization. | [npj Computational Materials](https://arxiv.org/abs/2204.02782) |
| SphereNet | Spherical Message Passing for 3D Molecular Graphs | Spherical message passing network using complete spherical coordinates (distance, angle, dihedral) for 3D molecular graph representation. | [ICLR](https://arxiv.org/abs/2102.05013) |
| ComENet | ComENet: Towards Complete and Efficient Message Passing for 3D Molecular Graphs | Complete and efficient 3D molecular message passing framework encoding all geometric information (distance, angle, torsion) while maintaining efficiency. | [NeurIPS 2022](https://arxiv.org/abs/2206.08515) |
| SEGNN | Geometric and Physical Quantities Improve E(3) Equivariant Message Passing | Steerable E(3)-equivariant graph neural network using spherical harmonics-based steerable features for equivariant message passing. | [ICLR](https://arxiv.org/abs/2110.02905) |
| LEFTNet | A New Perspective on Building Efficient and Expressive 3D Equivariant Graph Neural Networks | Local equivariant frame Transformer network achieving efficient and expressive 3D equivariant graph neural networks through local reference frames. | [NeurIPS 2023](https://arxiv.org/abs/2305.07895) |
| ViSNet | ViSNet: An Equivariant Geometry-Enhanced Graph Neural Network with Vector-Scalar Interactive Message Passing | Equivariant geometry-enhanced GNN with vector-scalar interactive message passing that avoids expensive higher-order tensor operations via runtime geometric computation. | [Nature Communications](https://doi.org/10.1038/s41467-024-50014-6) |
| TorchMD-NET | TorchMD-NET: Equivariant Transformers for Neural Network Based Molecular Potentials | Equivariant Transformer framework for neural network molecular potentials, providing a unified implementation of architectures like SchNet and PaiNN. | [ICLR 2022 Workshop](https://arxiv.org/abs/2202.02541) |
| EPT | An equivariant pretrained transformer for unified 3D molecular representation learning | E(3)-equivariant all-atom pretrained Transformer for unified 3D molecular representation learning across diverse scientific domains. | [Nature Communications](https://doi.org/10.1038/s41467-026-69185-7) |

---

<a id="chemistry-section-05"></a>
### Molecular Generation & Diffusion

*Generative models for de novo molecular design, 3D conformation generation, and structure-based molecule generation using diffusion, VAEs, autoregressive, and flow-based approaches.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolGPT | MolGPT: Molecular Generation Using a Transformer-Decoder Model | GPT-based molecular generation model using a Transformer decoder to autoregressively generate SMILES satisfying specific property constraints. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.1c00600) |
| cMolGPT | cMolGPT: A Conditional Generative Pre-Trained Transformer for Target-Specific de novo Molecular Generation | Conditional molecular GPT extending MolGPT with target-specific controls for de novo molecular generation. | [Molecules](https://doi.org/10.3390/molecules28114430) |
| REINVENT 4 | REINVENT 4: Modern AI-Driven Generative Molecule Design | Fourth-generation industrial molecular design platform from AstraZeneca integrating reinforcement learning, transfer learning, and multi-objective optimization. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.4c00120) |
| JT-VAE | Junction Tree Variational Autoencoder for Molecular Graph Generation | Variational autoencoder using junction tree decomposition to generate molecular graphs from chemical substructure building blocks, guaranteeing chemical validity. | [ICML](https://arxiv.org/abs/1802.04364) |
| MoLeR | Learning to Extend Molecular Scaffolds with Structural Motifs | Molecular generation model from Microsoft that incrementally extends molecular scaffolds with structural motifs for fragment-based molecular design. | [ICLR](https://arxiv.org/abs/2103.03864) |
| GeoDiff | GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation | Geometric diffusion model for 3D molecular conformation generation within an SE(3)-equivariant framework. | [ICLR](https://arxiv.org/abs/2203.02923) |
| EDM | Equivariant Diffusion for Molecule Generation in 3D | E(3)-equivariant diffusion model that directly generates atomic types and 3D coordinates in 3D space, pioneering equivariant molecular diffusion generation. | [ICML](https://arxiv.org/abs/2203.17003) |
| GDSS | Score-based Generative Modeling of Graphs via the System of Stochastic Differential Equations | Score-based graph generative model using a joint node-edge system of stochastic differential equations for diffusion-based graph generation. | [ICML](https://arxiv.org/abs/2202.02514) |
| DiGress | DiGress: Discrete Denoising Diffusion for Graph Generation | Discrete denoising diffusion model for graph generation operating directly in discrete node and edge feature space, suited for molecular graph generation. | [ICLR](https://arxiv.org/abs/2209.14734) |
| GeoLDM | Geometric Latent Diffusion Models for 3D Molecule Generation | Geometric latent diffusion model performing 3D molecular generation in equivariant latent space, more efficient than direct atomic-space diffusion. | [ICML](https://arxiv.org/abs/2305.01140) |
| GFlowNet | Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation | Flow network-based generative model learning proportional sampling strategies from energy functions for diverse molecular candidate generation. | [NeurIPS](https://arxiv.org/abs/2106.04399) |
| TacoGFN | TacoGFN: Target-Conditioned GFlowNet for Structure-Based Drug Design | Target-conditioned GFlowNet incorporating protein pocket structural information for structure-based drug molecule generation. | [ICML 2024 Workshop](https://arxiv.org/abs/2310.03223) |
| GenMol | GenMol: A Drug Discovery Generalist with Discrete Diffusion | General-purpose molecular generation model from NVIDIA using masked discrete diffusion over SAFE representations for multi-stage drug discovery. | [ICLR](https://arxiv.org/abs/2501.06158) |
| NExT-Mol | NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | Foundation model integrating 1D SELFIES language modeling with 3D diffusion for 3D molecule generation. | [ICLR 2025](https://openreview.net/forum?id=tbo1Svjrxz) |
| Torsional Diffusion | Torsional Diffusion for Molecular Conformer Generation | Diffusion model operating on torsion angles for efficient and accurate molecular conformer generation. | [NeurIPS 2022](https://arxiv.org/abs/2206.01729) |
| ConfGF | Learning Gradient Fields for Molecular Conformation Generation | Gradient field learning approach for molecular conformation generation from 2D molecular graphs to stable 3D structures. | [ICML](https://arxiv.org/abs/2105.03902) |
| DMCG | Direct Molecular Conformation Generation | Direct method for generating 3D molecular conformations by predicting atomic coordinates without intermediate distance geometry. | [TMLR](https://arxiv.org/abs/2202.01356) |
| DiTMC | Sampling 3D Molecular Conformers with Diffusion Transformers | Diffusion Transformer framework for sampling accurate 3D molecular conformers integrating discrete molecular graphs with continuous coordinates. | [NeurIPS](https://arxiv.org/abs/2506.15378) |
| SynCoGen | Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling | Framework for synthesizable 3D molecule generation that jointly models molecular building blocks, chemical reactions, and atomic coordinates. | [ICLR](https://arxiv.org/abs/2507.11818) |

---

<a id="chemistry-section-06"></a>
### Spectroscopy & Analytical Chemistry

*Foundation models for interpreting and predicting molecular spectra including NMR, IR, Raman, and mass spectrometry.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MolSpectLLM | MolSpectLLM: A Large Language Model for Molecular Spectroscopy Interpretation | Large language model for molecular spectroscopy interpretation, linking NMR, IR, and MS spectral data to molecular structures for spectrum-to-structure reasoning. | [arXiv](https://arxiv.org/abs/2502.13094) |
| MACE4IR | MACE4IR: Machine Learning Interatomic Potentials for Infrared Spectroscopy Prediction | Equivariant graph neural network based on MACE for infrared spectroscopy prediction using machine-learned interatomic potentials. | [arXiv](https://arxiv.org/abs/2503.08205) |
| Vib2Mol | Vib2Mol: From Vibrational Spectra to Molecular Structures | Deep learning model that infers molecular structures directly from IR/Raman vibrational spectra. | [arXiv](https://arxiv.org/abs/2504.01187) |
| FIDDLE | FIDDLE: a deep learning method for chemical formulas prediction from tandem mass spectra | Deep learning method predicting chemical molecular formulas from tandem mass spectrometry data, trained on 38,000+ molecules and 1M spectra. | [Nature Communications](https://doi.org/10.1038/s41467-025-66060-9) |
| NMRTrans | NMRTrans: Structure Elucidation from Experimental NMR Spectra via Set Transformers | Set Transformer model for molecular structure elucidation from experimental NMR spectra. | [arXiv](https://arxiv.org/abs/2602.10158) |

---

<a id="chemistry-section-07"></a>
### Food Science

*Chemical language models applied to food-related molecular property prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FART | A chemical language model for molecular taste prediction | Chemical language model predicting molecular taste properties from SMILES representations. | [npj Science of Food](https://doi.org/10.1038/s41538-025-00474-z) |

---

<a id="chemistry-section-08"></a>
### Electrochemistry

*Foundation models for electrochemical applications including battery electrolyte design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| HELENA | Hierarchical Moiety-Aware Graph Transformer for Li-metal Electrolyte Formulation Design | Hierarchical moiety-aware graph Transformer for lithium-metal battery electrolyte formulation optimization. | [chemRxiv](https://doi.org/10.26434/chemrxiv-2025-c0ttj-v3) |

## Materials Science

> [English](materials-science/materials-science_en.md) | [Chinese](materials-science/materials-science_zh.md)

### Table of Contents
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
### Atomistic Force Fields
*Machine-learned interatomic potentials for molecular dynamics simulations.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MACE | MACE: Higher Order Equivariant Message Passing Neural Networks for Fast and Accurate Force Fields | Higher-order equivariant message passing framework using atomic cluster expansion for accurate and efficient force field computation. | [NeurIPS 2022](https://arxiv.org/abs/2206.07697) |
| MACE-MP-0 | A Foundation Model for Atomistic Materials Chemistry | Pre-trained universal force field covering 89 elements, trained on Materials Project data for general materials chemistry simulation. | [J. Chem. Phys.](https://arxiv.org/abs/2401.00096) |
| CHGNet | CHGNet as a Pretrained Universal Neural Network Potential for Charge-Informed Atomistic Modelling | Pre-trained universal graph neural network potential with charge information, trained on Materials Project DFT data. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00716-3) |
| M3GNet | A Universal Graph Deep Learning Interatomic Potential for the Periodic Table | Universal graph deep learning interatomic potential trained on Materials Project relaxation data, covering all periodic table elements. | [Nature Computational Science](https://doi.org/10.1038/s43588-022-00349-3) |
| SevenNet | SevenNet: Scalable Graph Neural Network Interatomic Potential | Scalable GNN interatomic potential based on NequIP architecture with LAMMPS parallel MD support. | [J. Chem. Theory Comput.](https://doi.org/10.1021/acs.jctc.4c00190) |
| Orb | Orb: A Fast, Scalable Neural Network Potential | Fast and scalable neural network potential by Orbital Materials, 3–6× faster than existing universal potentials while maintaining SOTA accuracy. | [arXiv](https://arxiv.org/abs/2410.22570) |
| NequIP | E(3)-Equivariant Graph Neural Networks for Data-Efficient and Accurate Interatomic Potentials | E(3)-equivariant GNN using equivariant convolutions instead of invariant descriptors, achieving high accuracy with minimal training data. | [Nature Communications](https://doi.org/10.1038/s41467-022-29939-5) |
| Allegro | Learning Local Equivariant Representations for Large-Scale Atomistic Dynamics | Highly scalable E(3)-equivariant architecture using local equivariant representations to support large-scale molecular dynamics. | [Nature Communications](https://doi.org/10.1038/s41467-023-36329-y) |
| Allegro-FM | Allegro-FM: Toward an Equivariant Foundation Model for Exascale Molecular Dynamics Simulations | Equivariant foundation model targeting exascale molecular dynamics simulations based on the Allegro architecture. | [J. Phys. Chem. Lett.](https://arxiv.org/abs/2502.06073) |
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
### Crystal & Materials Property
*Predicting physical, electronic, and structural properties of crystalline and molecular materials.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CGCNN | Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties | Pioneering crystal graph convolutional neural network for direct, interpretable prediction of material properties from crystal structures. | [Physical Review Letters](https://doi.org/10.1103/PhysRevLett.120.145301) |
| MEGNet | Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals | Universal materials graph network supporting property prediction for both molecules and crystals with global state features. | [Chemistry of Materials](https://doi.org/10.1021/acs.chemmater.9b01294) |
| ALIGNN | Atomistic Line Graph Neural Network for Improved Materials Property Predictions | NIST atomistic line graph neural network that explicitly models bond angles, outperforming CGCNN and MEGNet. | [npj Computational Materials](https://doi.org/10.1038/s41524-021-00650-1) |
| MultiMat | Multimodal Foundation Models for Material Property Prediction and Discovery | Multimodal foundation model integrating crystal structure, density of states, charge density, and text for comprehensive materials property prediction. | [Newton](https://arxiv.org/abs/2312.00111) |
| SMI-TED | SMI-TED: Large-Scale Foundation Model for Materials and Chemistry | IBM large-scale SMILES encoder-decoder model pre-trained on 91M PubChem SMILES for materials and chemistry applications. | [ICLR 2024 Workshop](https://openreview.net/forum?id=smi-ted) |
| DARWIN 1.5 | DARWIN 1.5: Large Language Models as Materials Science Adapted Learners | Open-source materials science LLM that predicts material properties and facilitates discovery from natural language input. | [arXiv](https://arxiv.org/abs/2412.11970) |
| MatBERT | Quantifying the Advantage of Domain-Specific Pre-training on Named Entity Recognition Tasks in Materials Science | BERT model pre-trained on materials science literature (LBNL), outperforming general models on materials NLP tasks. | [Patterns](https://doi.org/10.1016/j.patter.2022.100488) |
| MatSciBERT | MatSciBERT: A Materials Domain Language Model for Text Mining and Information Extraction | Domain-specific BERT trained on materials science literature for enhanced text mining and information extraction. | [npj Computational Materials](https://doi.org/10.1038/s41524-022-00784-w) |
| MOFTransformer | A Multi-modal Pre-training Transformer for Universal Transfer Learning in Metal-Organic Frameworks | Multi-modal pre-trained Transformer for MOF property prediction, trained on 1M hypothetical MOFs with atomic graph and energy grid embeddings. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-023-00628-2) |
| CrystalFormer | Space Group Informed Transformer for Crystalline Materials Generation | Autoregressive Transformer guided by space group symmetry and Wyckoff positions for crystalline materials generation. | [Science Bulletin](https://arxiv.org/abs/2403.15734) |
| MatInFormer | Materials Informatics Transformer: A Language Model for Interpretable Materials Properties Prediction | Materials informatics Transformer leveraging LLM techniques for interpretable materials property prediction. | [arXiv](https://arxiv.org/abs/2308.16259) |
| KPGT | A Knowledge-Guided Pre-training Framework for Improving Molecular Representation | Knowledge-guided graph Transformer pre-training framework using chemical knowledge to enhance molecular representation learning. | [Nature Communications](https://doi.org/10.1038/s41467-023-43214-1) |
| Matformer | Periodic Graph Transformers for Crystal Material Property Prediction | Periodic graph Transformer with periodicity-aware multi-graph attention for crystal material property prediction. | [NeurIPS 2022](https://arxiv.org/abs/2209.11807) |
| PotNet | Complete and Efficient Graph Transformers for Crystal Material Property Prediction | Complete and efficient crystal graph Transformer achieving full graph representation via interatomic potential information. | [ICLR](https://arxiv.org/abs/2306.10045) |
| LLM-Prop | LLM-Prop: Predicting Physical And Electronic Properties of Crystalline Solids From Their Text Descriptions | Uses large language models to predict physical and electronic properties of crystals from text descriptions. | [arXiv](https://arxiv.org/abs/2310.14029) |
| EScAIP | EScAIP: Efficiently Scaled Attention Interatomic Potential | Efficiently scaled attention-based interatomic potential achieving high accuracy and scalability for materials property prediction. | [ICLR](https://arxiv.org/abs/2411.15019) |
| AlloyGPT | End-to-end prediction and design of additively manufacturable alloys | Autoregressive language model for end-to-end alloy design and property prediction. | [npj Computational Materials](https://doi.org/10.1038/s41524-025-01768-2) |
| aLLoyM | aLLoyM: a large language model for alloy phase diagram prediction | Large language model for predicting alloy phase diagrams. | [npj Computational Materials](https://doi.org/10.1038/s41524-026-01966-6) |
| MaskTerial | MaskTerial: a foundation model for automated 2D material flake detection | Foundation model for automated detection of 2D material flakes. | [Digital Discovery](https://doi.org/10.1039/D5DD00156K) |
| CLOUD | Scalable physics-informed foundation model for crystal representation | Scalable physics-informed crystal representation foundation model trained on 6M+ crystal structures. | [Nature Communications](https://doi.org/10.1038/s41467-026-57867-x) |
| LLaMat | Large language models for materials science | Family of large language models adapted for materials science tasks. | [Nature MI](https://doi.org/10.1038/s42256-026-00964-9) |

---

<a id="materials-science-section-03"></a>
### Universal Atomic Models
*Large-scale pre-trained models spanning molecules, materials, and catalysts across the periodic table.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| UMA | UMA: A Family of Universal Models for Atoms | Meta FAIR universal atomic model family trained on 500M+ 3D atomic structures spanning molecules, materials, and catalysts. | [NeurIPS](https://arxiv.org/abs/2506.23971) |
| Zatom-1 | Zatom-1: A Multimodal Flow Foundation Model for 3D Molecules and Materials | Open-source multimodal flow foundation model unifying generation and prediction for 3D molecules and materials. | [arXiv](https://arxiv.org/abs/2602.22251) |
| MIST | Foundation Models for Discovery and Exploration in Chemical Space | Large-scale molecular foundation model family (Molecular Insight SMILES Transformers) predicting 400+ structure-property relationships. | [arXiv](https://arxiv.org/abs/2510.18900) |
| MatterSim | MatterSim: A Deep Learning Atomistic Model Across Elements, Temperatures and Pressures | Microsoft deep learning atomic model covering all elements at 0–5000 K and 0–1000 GPa. | [arXiv](https://arxiv.org/abs/2405.04967) |
| GNoME | Scaling Deep Learning for Materials Discovery | Google DeepMind GNN materials explorer discovering 2.2M new stable inorganic crystal structures. | [Nature](https://doi.org/10.1038/s41586-023-06735-9) |
| JMP | From Molecules to Materials: Pre-training Large Generalizable Models for Atomic Property Prediction | Meta FAIR joint multi-domain pre-training on ~120M atomic systems spanning molecules and materials. | [ICLR](https://arxiv.org/abs/2310.16802) |
| ATOMICA | Learning Universal Representations of Intermolecular Interactions with ATOMICA | Geometric deep learning model learning universal atomic-level representations of intermolecular interactions. | [NeurIPS 2025](https://proceedings.neurips.cc/paper/2025/hash/atomica) |
| OMAT24 | Open Materials 2024 Dataset and Models | Open materials dataset with 100M+ DFT calculations and pre-trained eSEN models. | [arXiv](https://arxiv.org/abs/2410.12771) |
| eSEN | Efficient Scalable Equivariant Networks | Scalable equivariant architecture forming the backbone of UMA, achieving SOTA on molecular and materials benchmarks. | [arXiv](https://arxiv.org/abs/2501.02063) |
| OMol25 | The Open Molecules 2025 Dataset, Evaluations, and Models | Meta FAIR large-scale open molecular property dataset with 100M+ DFT calculations and baseline models. | [arXiv](https://arxiv.org/abs/2505.08762) |
| OC25 | Open Catalyst 2025 for solid-liquid interfaces | Open Catalyst 2025 dataset and models for solid-liquid interface catalysis. | [arXiv](https://arxiv.org/abs/2509.17862) |

---

<a id="materials-science-section-04"></a>
### Crystal Structure Generation & Inverse Design
*Generative models for discovering and designing novel crystal structures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CDVAE | Crystal Diffusion Variational Autoencoder for Periodic Material Generation | Crystal diffusion VAE combining diffusion processes with VAE for end-to-end stable periodic crystal structure generation. | [ICLR](https://arxiv.org/abs/2110.06197) |
| DiffCSP | Crystal Structure Prediction by Joint Equivariant Diffusion | Joint equivariant diffusion model simultaneously diffusing atom coordinates and lattice parameters for crystal structure prediction. | [NeurIPS 2023](https://arxiv.org/abs/2309.04475) |
| SyMat | Towards Symmetry-Aware Generation of Periodic Materials | Symmetry-aware periodic material generation model explicitly leveraging space group symmetry constraints. | [NeurIPS 2023](https://arxiv.org/abs/2307.02554) |
| MatterGen | MatterGen: A Generative Model for Inorganic Materials Design | Microsoft diffusion model for inverse design of inorganic crystals conditioned on chemistry, symmetry, and property constraints. | [Nature](https://arxiv.org/abs/2312.03687) |
| Crystal-GFN | Crystal-GFN: Sampling Crystals with Desirable Properties and Constraints | GFlowNet-based crystal sampling framework that efficiently explores crystal space under property and composition constraints. | [arXiv](https://arxiv.org/abs/2310.04925) |
| FlowMM | FlowMM: Generating Materials with Riemannian Flow Matching | Riemannian flow matching on crystal manifolds for geometry-aware materials structure generation. | [ICML](https://arxiv.org/abs/2406.04713) |
| FlowLLM | FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions | Combines LLM base distributions with flow matching, leveraging chemical priors for improved crystal generation. | [NeurIPS 2024](https://arxiv.org/abs/2410.23405) |
| CrystalFlow | CrystalFlow: A Flow-Based Generative Model for Crystalline Materials | Flow-based generative model achieving high-fidelity crystal structure generation via normalizing flows. | [Nature Communications](https://arxiv.org/abs/2412.12345) |
| WyckoffDiff | WyckoffDiff: Diffusion in the Wyckoff Space for Crystal Structure Generation | Diffusion model operating in Wyckoff position space with symmetry-aware representations for improved structural validity. | [ICML](https://arxiv.org/abs/2502.03035) |
| MatterGPT | MatterGPT: A Generative Transformer for Multi-Property Inverse Design of Solid-State Materials | Autoregressive Transformer supporting multi-property conditioned inverse design of solid-state materials. | [arXiv](https://arxiv.org/abs/2408.07608) |
| CrystaLLM | CrystaLLM: Large Language Model for Crystallography | LLM that generates crystal structures directly from CIF text without explicit geometric encoding. | [Nature Communications](https://doi.org/10.1038/s41467-024-54639-7) |
| UniMat | Scalable Diffusion for Materials Generation | Scalable diffusion model for crystal materials generation with a unified representation across varying crystal sizes. | [ICLR](https://arxiv.org/abs/2311.09235) |
| DAO-G / DAO-P | Siamese Foundation Models for Crystal Structure Prediction | Siamese pre-training framework: DAO-G for crystal generation and DAO-P for property prediction. | [arXiv](https://arxiv.org/abs/2503.10471) |
| MOFGPT | Transformer-based generative model for de novo MOF design | Transformer generative model for de novo design of metal-organic frameworks. | [arXiv](https://arxiv.org/abs/2506.00198) |
| Matra-Genoa | Autoregressive generative material Transformer | Autoregressive Transformer for generative materials design. | [npj Comp. Mater.](https://doi.org/10.1038/s41524-026-01550-8) |

---

<a id="materials-science-section-05"></a>
### Catalyst & Surface Models
*Models for catalytic reaction prediction, adsorption energies, and surface chemistry.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OC20 | Open Catalyst 2020 (OC20) Dataset and Community Challenges | Meta FAIR open catalyst dataset with 155M DFT-computed adsorption configurations for ML-driven catalyst discovery. | [ACS Catalysis](https://doi.org/10.1021/acscatal.0c04525) |
| OC22 | The Open Catalyst 2022 (OC22) Dataset and Challenges for Oxide Electrocatalysts | Extension of Open Catalyst to oxide electrocatalysts with DFT relaxation data for oxide surfaces. | [ACS Catalysis](https://doi.org/10.1021/acscatal.2c05426) |
| AdsorbML | AdsorbML: A Leap in Efficiency for Adsorption Energy Calculations using Generalizable Machine Learning Potentials | Generalizable ML potentials for efficient adsorption energy calculation, accelerating catalyst screening with OC20 pre-trained models. | [npj Computational Materials](https://doi.org/10.1038/s41524-023-01121-5) |
| CatBERTa | CatBERTa: A RoBERTa-based Catalyst Property Prediction Model | RoBERTa-based model predicting catalyst adsorption energies and activities from textual descriptions. | [arXiv](https://arxiv.org/abs/2305.08628) |
| GemNet-OC | GemNet-OC: Developing Graph Neural Networks for Large and Diverse Molecular Simulation Datasets | GemNet variant optimized for Open Catalyst datasets, achieving SOTA on large-scale catalyst simulations. | [npj Computational Materials](https://doi.org/10.1038/s41524-022-00891-8) |
| eSCN | Reducing SO(3) Convolutions to SO(2) for Efficient Equivariant GNNs | Efficient equivariant spherical channel network reducing SO(3) to SO(2) convolutions for major computational speedup. | [ICML](https://arxiv.org/abs/2302.03655) |
| SCN | Spherical Channels for Modeling Atomic Interactions | Spherical channel network using spherical harmonics for atomic interaction modeling, excelling on OC20 catalyst tasks. | [NeurIPS 2022](https://arxiv.org/abs/2206.14331) |
| EquiformerV2 | EquiformerV2: Improved Equivariant Transformer for Scaling to Higher-Degree Representations | Improved equivariant Transformer supporting higher-degree representations, achieving SOTA on OC20/OC22 benchmarks. | [ICLR](https://arxiv.org/abs/2306.12059) |
| eqV2 | Improved EquiformerV2 for OC20/OC22 | Improved EquiformerV2 variant for general atomic property prediction on Open Catalyst datasets. | [arXiv](https://arxiv.org/abs/2401.13013) |
| CatDRX | Reaction-conditioned generative model for catalyst design | Reaction-conditioned generative model for designing catalysts tailored to specific reactions. | [Comms. Chem.](https://doi.org/10.1038/s42004-025-01462-y) |

---

<a id="materials-science-section-06"></a>
### Electronic Structure Prediction
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
### Polymer & Soft Matter
*Language models and graph networks for polymer informatics and design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| polyBERT | polyBERT: A Chemical Language Model to Enable Fully Machine-Driven Ultrafast Polymer Informatics | BERT-based chemical language model trained on polymer SMILES for ultrafast polymer property prediction. | [Nature Communications](https://doi.org/10.1038/s41467-023-39868-6) |
| polyGNN | polyGNN: Multitask Graph Neural Networks for Polymer Informatics | Multitask graph neural network for simultaneous polymer property prediction and structure-property learning. | [Chemistry of Materials](https://doi.org/10.1021/acs.chemmater.2c02991) |
| polyBART | polyBART: A Generative Transformer for Polymer Design | BART-based generative Transformer for conditional polymer generation and property-guided inverse design. | [arXiv](https://arxiv.org/abs/2404.02535) |
| POLYT5 | Encoder-decoder foundation chemical language model for polymer design | T5 encoder-decoder foundation chemical language model for polymer design. | [npj AI](https://doi.org/10.1038/s44335-026-00013-5) |

---

<a id="materials-science-section-08"></a>
### Battery & Energy Materials
*Pre-trained models for battery research, electrode materials, and energy storage.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BatteryBERT | BatteryBERT: A Pretrained Language Model for Battery Research | BERT fine-tuned on battery literature for text mining and information extraction in battery research. | [J. Chem. Inf. Model.](https://doi.org/10.1021/acs.jcim.2c00035) |
| BatteryFormer | BatteryFormer: Graph Transformer for Battery Material Property Prediction | Graph Transformer predicting battery electrode capacity, voltage, and cycle life properties. | [arXiv](https://arxiv.org/abs/2404.07862) |

---

<a id="materials-science-section-09"></a>
### Foundational GNN Architectures
*Foundational graph neural network architectures underlying many materials science models.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SchNet | SchNet: A Continuous-Filter Convolutional Neural Network for Modeling Quantum Interactions | Pioneering continuous-filter convolutional network encoding interatomic distances as continuous representations for quantum interactions. | [NeurIPS](https://arxiv.org/abs/1706.08566) |
| DimeNet | Directional Message Passing for Molecular Graphs | Directional message passing network using bond angle information for 3D geometry-aware molecular property prediction. | [ICLR](https://arxiv.org/abs/1903.02428) |
| PaiNN | Equivariant Message Passing for the Prediction of Tensorial Properties and Molecular Spectra | Polarizable atom interaction network using equivariant message passing for tensorial property and spectra prediction. | [ICML](https://arxiv.org/abs/2102.03150) |
| GemNet | GemNet: Universal Directional Graph Neural Networks for Molecules | Universal directional GNN using dihedral angles for complete geometric representation in molecular property prediction. | [NeurIPS](https://arxiv.org/abs/2106.08903) |
| TorchMD-NET | TorchMD-NET: Equivariant Transformers for Neural Network Potentials | Modular equivariant Transformer framework for neural network potentials supporting diverse materials simulation tasks. | [ICLR 2022 Workshop](https://arxiv.org/abs/2202.02541) |

---

<a id="materials-science-section-10"></a>
### Metamaterials
*Foundation models for metamaterial structure-property relationships.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MetaFO | Toward a robust and generalizable metamaterial foundation model | Bayesian Transformer metamaterial foundation model for zero-shot structure-property prediction. | [npj Computational Materials](https://doi.org/10.1038/s41524-025-01925-7) |

---

<a id="materials-science-section-11"></a>
### Superconductors
*Models for predicting superconducting properties and critical temperatures.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BEE-NET | Developing a complete AI-accelerated workflow for superconductor discovery | Equivariant GNN predicting Eliashberg spectral functions and critical temperatures for superconductor discovery. | [npj Computational Materials](https://doi.org/10.1038/s41524-026-01964-8) |
| DeeperBand | A deep learning approach to search for superconductors from electronic bands | Symmetry-aware 3D Vision Transformer predicting superconductivity from electronic band structures. | [IOPscience](https://doi.org/10.1088/3050-287X/adf6cb) |

## Physics

> [English](physics/physics_en.md) | [Chinese](physics/physics_zh.md)

### Table of Contents
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
### Particle Physics
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
### Fluid Dynamics & PDE Solving
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
### General Physics Simulation
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
### World Models
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
### Quantum Physics & Many-Body Systems
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
### Plasma Physics & Fusion
*Multi-modal models for tokamak plasma behavior prediction and fusion control.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| TokaMind | TokaMind: A Multi-Modal Transformer Foundation Model for Tokamak Plasma | Multi-modal Transformer foundation model fusing multiple diagnostic modalities for tokamak plasma behavior prediction and fusion control. | [arXiv](https://arxiv.org/abs/2501.14809) |

---

<a id="physics-section-07"></a>
### Optics & Photonics
*Foundation models for optical design, thin-film structures, and photonic inverse design.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OptoGPT | OptoGPT: A Foundation Model for Inverse Design in Optical Multilayer Thin Film Structures | GPT-based foundation model for automatic inverse design of optical multilayer thin-film structures to meet target spectral properties. | [Opto-Electronic Advances](https://doi.org/10.29026/oea.2024.240062) |
| MOCLIP | MOCLIP: Multi-modal Optical Contrastive Learning for Inverse Photonic Design | Multi-modal optical contrastive learning model using a CLIP framework for cross-modal photonic structure inverse design. | [arXiv](https://arxiv.org/abs/2504.01754) |

---

<a id="physics-section-08"></a>
### Structure-Preserving & Geometric Physics ML
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
### Quantum Chemistry & Electronic Structure
*Models for electronic structure calculation, wavefunction prediction, and molecular quantum properties.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Skala | Skala: A Foundation Model for Quantum Chemistry | Microsoft quantum chemistry foundation model for electronic structure computation and cross-system molecular property prediction. | [Microsoft](https://www.microsoft.com/en-us/research/publication/skala-a-foundation-model-for-quantum-chemistry/) |
| Orbformer | Orbformer: Orbital Transformer for Electronic Structure Prediction | Orbital Transformer predicting electronic structure from molecular orbital representations with physical symmetry priors. | [arXiv](https://arxiv.org/abs/2502.16068) |
| OrbEvo | Orbital Transformers for Predicting Wavefunctions in TD-DFT | Equivariant graph Transformer predicting real-time TD-DFT wavefunction evolution. | [arXiv](https://arxiv.org/abs/2603.03511) |

---

<a id="physics-section-10"></a>
### Combustion Simulation
*Deep learning platforms for reactive flow and combustion CFD.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DeepFlame | Deep Learning-Enabled Supercritical Flame Simulation | Open-source deep learning combustion CFD platform integrating ML surrogate models for reactive flow simulation. | [arXiv](https://arxiv.org/abs/2508.18969) |

---

<a id="physics-section-11"></a>
### Nuclear Engineering
*Domain-specific foundation models for nuclear reactor control and simulation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| NucReactor-FM | Agentic Physical AI toward a Domain-Specific FM for Nuclear Reactor Control | Domain-specific foundation model for nuclear reactor control combining physics simulation with reinforcement learning. | [arXiv](https://arxiv.org/abs/2512.23292) |

## Earth Sciences

> [English](earth-sciences/earth-sciences_en.md) | [Chinese](earth-sciences/earth-sciences_zh.md)

### Table of Contents
- [Weather & Climate](#earth-sciences-section-01)
- [Remote Sensing](#earth-sciences-section-02)
- [Oceanography](#earth-sciences-section-03)
- [Seismology](#earth-sciences-section-04)
- [Hydrology](#earth-sciences-section-05)
- [Wildfire Prediction](#earth-sciences-section-06)
- [Air Quality](#earth-sciences-section-07)
- [Cryosphere](#earth-sciences-section-08)
- [Geoscience Language Models](#earth-sciences-section-09)
- [Subsurface & Exploration Geophysics](#earth-sciences-section-10)
- [SAR-Specific Models](#earth-sciences-section-11)
- [Land Use](#earth-sciences-section-12)
- [Climate Downscaling](#earth-sciences-section-13)

<a id="earth-sciences-section-01"></a>
### Weather & Climate
*Foundation models for global weather forecasting and climate prediction at various spatial and temporal scales.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Aurora | Aurora: A Foundation Model of the Earth System | A large-scale earth system foundation model by Microsoft trained on over one million hours of multi-source geophysical data for atmosphere, ocean, and air quality prediction. | [Nature (2025)](https://arxiv.org/abs/2405.13063) |
| Pangu-Weather | Accurate Medium-range Global Weather Forecasting with 3D Neural Networks | A 3D high-resolution AI weather forecasting model by Huawei trained on 43 years of ERA5 reanalysis data, generating 10-day global forecasts in seconds. | [Nature](https://arxiv.org/abs/2211.02556) |
| GraphCast | Learning Skillful Medium-range Global Weather Forecasting | A graph neural network-based global medium-range weather forecasting model by Google DeepMind at 0.25° resolution, outperforming ECMWF HRES for 10-day forecasts. | [Science](https://arxiv.org/abs/2212.12794) |
| GenCast | GenCast: Diffusion-based Ensemble Forecasting for Medium-range Weather | A diffusion-based ensemble weather forecasting system by Google DeepMind generating probabilistic 15-day forecasts that surpass ECMWF ENS. | [Nature (2024)](https://arxiv.org/abs/2312.15796) |
| ClimaX | ClimaX: A Foundation Model for Weather and Climate | The first weather and climate foundation model based on Transformer architecture supporting flexible fine-tuning for multiple downstream meteorological tasks. | [ICML](https://arxiv.org/abs/2301.10343) |
| FengWu | FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead | A multi-modal multi-task weather forecasting system by Shanghai AI Lab that extends deterministic forecast skill to 10.75 days. | [Nature Communications (2025)](https://arxiv.org/abs/2304.02948) |
| FuXi | FuXi: A Cascade Machine Learning Forecasting System for 15-day Global Weather Forecast | A cascade machine learning weather forecasting system trained on 39 years of ERA5 data, achieving 15-day forecast performance comparable to ECMWF ensemble mean. | [npj Climate and Atmospheric Science](https://arxiv.org/abs/2306.12873) |
| NeuralGCM | Neural General Circulation Models for Weather and Climate | A neural GCM by Google Research combining differentiable atmospheric dynamics solvers with machine learning for weather-to-climate timescale prediction. | [Nature](https://arxiv.org/abs/2311.07222) |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Forecasting System | A high-resolution global weather forecasting model by NVIDIA using adaptive Fourier neural operators (AFNO) at 0.25° resolution. | [arXiv](https://arxiv.org/abs/2202.11214) |
| ECMWF AIFS | AIFS — ECMWF's Data-driven Forecasting System | ECMWF's operational AI forecasting system combining graph neural networks and Transformers for data-driven weather prediction. | [arXiv](https://arxiv.org/abs/2406.01465) |
| Stormer | Scaling Transformer Neural Networks for Skillful and Reliable Medium-range Weather Forecasting | A streamlined and efficient Transformer weather forecasting model achieving state-of-the-art performance with less training data. | [Advances in Neural Information Processing Systems 37](https://arxiv.org/abs/2312.03876) |
| AtmoRep | AtmoRep: A Stochastic Model of Atmosphere Dynamics Using Large Scale Representation Learning | A task-agnostic atmospheric foundation model based on large-scale representation learning for stochastic atmosphere dynamics. | [arXiv](https://arxiv.org/abs/2308.13280) |
| SkyGPT | SkyGPT: Probabilistic Short-term Solar Forecasting Using Synthetic Sky Videos from Physics-constrained VideoGPT | A physics-constrained probabilistic short-term solar irradiance forecasting model using synthetic sky image video prediction. | [Advances in Applied Energy (2024)](https://arxiv.org/abs/2306.11682) |
| WeatherGFT | WeatherGFT: Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling | A hybrid physics-AI weather forecasting model extending predictions to finer temporal resolutions at 30-minute intervals. | [NeurIPS](https://arxiv.org/abs/2405.13796) |
| WeatherGFM | WeatherGFM: Learning A Weather Generalist Foundation Model via In-context Learning | A weather generalist foundation model unifying forecasting, super-resolution, image translation, and post-processing via in-context learning. | [ICLR](https://arxiv.org/abs/2411.05420) |
| Prithvi WxC | Prithvi WxC: Foundation Model for Weather and Climate | A 2.3-billion-parameter weather and climate foundation model by IBM and NASA trained on 160 MERRA-2 variables. | [arXiv](https://arxiv.org/abs/2409.13598) |
| FuXi-2.0 | FuXi-2.0: Advancing Machine Learning Weather Forecasting Model for Practical Applications | An upgraded version of FuXi providing hourly global forecasts with a more comprehensive set of meteorological variables. | [arXiv](https://arxiv.org/abs/2409.07188) |
| ArchesWeather | ArchesWeather: An Efficient AI Weather Forecasting Model at 1.5° Resolution | A lightweight and efficient AI weather forecasting model at 1.5° resolution using a combination of 2D and column-wise attention. | [arXiv](https://arxiv.org/abs/2405.14527) |
| W-MAE | W-MAE: Pre-trained Weather Model with Masked Autoencoder | A task-agnostic atmospheric foundation model based on masked autoencoder pre-training for weather data. | [arXiv](https://arxiv.org/abs/2304.08754) |
| WeatherNext 2 | WeatherNext 2: Google DeepMind's Most Advanced Forecasting Model | Google DeepMind's most advanced high-resolution ensemble weather forecasting model for operational-scale predictions. | [Google DeepMind](https://blog.google/technology/google-deepmind/weathernext-2/) |
| Omni-Weather | Omni-Weather: Unified Multimodal Foundation Model for Weather Generation and Understanding | A unified multimodal foundation model integrating radar, satellite, and numerical data for weather generation and understanding. | [arXiv](https://arxiv.org/abs/2512.21643) |

---

<a id="earth-sciences-section-02"></a>
### Remote Sensing
*Foundation models for satellite imagery analysis, multi-spectral and multi-temporal earth observation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Prithvi-EO-2.0 | Prithvi-EO-2.0: A Versatile Multi-Temporal Foundation Model for Earth Observation Applications | A multi-temporal earth observation foundation model by NASA/IBM trained on 4.2 million global time-series samples supporting Landsat and Sentinel-2. | [arXiv](https://arxiv.org/abs/2412.02732) |
| SpectralGPT | SpectralGPT: Spectral Remote Sensing Foundation Model | The first spectral remote sensing foundation model using a 3D generative pre-trained Transformer designed for multi-spectral and hyperspectral satellite imagery. | [IEEE TPAMI (2024)](https://arxiv.org/abs/2311.07113) |
| SatMAE | SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery | A masked autoencoder pre-training framework for temporal and multi-spectral satellite imagery. | [NeurIPS 2022](https://arxiv.org/abs/2207.08051) |
| SeaMo | SeaMo: A Multi-Seasonal and Multimodal Remote Sensing Foundation Model | A multi-seasonal multimodal remote sensing foundation model fusing optical, SAR, and meteorological data. | [arXiv](https://arxiv.org/abs/2412.19237) |
| TerraMind | TerraMind: Large-Scale Generative Multimodality for Earth Observation | A large-scale generative multimodal earth observation foundation model by IBM/ESA/DLR trained on 500 billion tokens. | [ICCV](https://arxiv.org/abs/2504.11171) |
| RingMo | RingMo: A Remote Sensing Foundation Model with Masked Image Modeling | A remote sensing foundation model by the Chinese Academy of Sciences using masked image modeling for large-scale pre-training. | [IEEE TGRS](https://doi.org/10.1109/TGRS.2022.3194732) |
| SatCLIP | SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery | A global general-purpose location encoder by Microsoft using Sentinel-2 contrastive learning to generate location embeddings. | [AAAI](https://arxiv.org/abs/2311.17179) |
| Clay Foundation Model | Clay: An Open Source AI Model for Earth | An open-source earth observation foundation model based on masked autoencoder architecture supporting Sentinel-1/2 and DEM data. | [开源项目](https://clay-foundation.github.io/model/) |
| SkySense | SkySense: A Multi-Modal Remote Sensing Foundation Model Towards Universal Interpretation for Earth Observation Imagery | A large-scale multimodal remote sensing foundation model pre-trained on 21.5 million temporal optical and SAR data samples. | [CVPR](https://arxiv.org/abs/2312.10115) |
| Scale-MAE | Scale-MAE: A Scale-Aware Masked Autoencoder for Multiscale Geospatial Representation Learning | A scale-aware masked autoencoder that explicitly models spatial resolution relationships for multiscale geospatial representation learning. | [ICCV 2023](https://arxiv.org/abs/2212.14532) |
| RSPrompter | RSPrompter: Learning to Prompt for Remote Sensing Instance Segmentation | A SAM-based prompt learning method for remote sensing instance segmentation adapting vision foundation models to remote sensing. | [IEEE TGRS (2024)](https://arxiv.org/abs/2306.16269) |
| ChangeFormer | ChangeFormer: A Transformer-Based Siamese Network for Change Detection | A Transformer-based siamese network for remote sensing change detection. | [IGARSS](https://arxiv.org/abs/2201.01293) |
| DOFA | Neural Plasticity-Inspired Multimodal Foundation Model for Earth Observation | A neural plasticity-inspired multimodal EO foundation model using dynamic wavelength-adaptive hypernetworks to handle diverse sensor data. | [arXiv](https://arxiv.org/abs/2403.15356) |
| GFM (Prithvi-EO-1.0) | Foundation Models for Generalist Geospatial Artificial Intelligence | NASA/IBM's first-generation earth science foundation model based on self-supervised Vision Transformers trained on HLS data. | [arXiv](https://arxiv.org/abs/2310.18660) |
| S2MAE | S2MAE: A Spatial-Spectral Pretraining Foundation Model for Spectral Remote Sensing Image | A spatial-spectral masked autoencoder providing joint spatial-spectral pre-training for spectral remote sensing imagery. | [CVPR 2024](https://openaccess.thecvf.com/content/CVPR2024/html/Li_S2MAE_A_Spatial-Spectral_Pretraining_Foundation_Model_for_Spectral_Remote_Sensing_Data_CVPR_2024_paper.html) |
| RingMoE | RingMoE: Mixture-of-Modality-Experts Multi-Modal Foundation Models for Universal Remote Sensing Image Interpretation | A 14.7-billion-parameter mixture-of-modality-experts remote sensing foundation model pre-trained on 400M+ samples. | [arXiv](https://arxiv.org/abs/2504.03166) |
| WaveMAE | WaveMAE: Wavelet-decomposition Masked Autoencoder for Multispectral Satellite Imagery | A self-supervised foundation model combining wavelet decomposition with geospatial priors for multispectral satellite imagery. | [arXiv](https://arxiv.org/abs/2510.22697) |
| RoMA | RoMA: Scaling up Mamba-based Foundation Models for Remote Sensing | A scalable Mamba-architecture remote sensing foundation model addressing ViT limitations in large-scale remote sensing pre-training. | [NeurIPS](https://arxiv.org/abs/2503.10392) |
| CROMA | CROMA: Contrastive Radar-Optical Masked Autoencoders for Remote Sensing | A contrastive radar-optical masked autoencoder for multimodal remote sensing representation learning. | [NeurIPS](https://arxiv.org/abs/2311.00566) |
| SSL4EO | SSL4EO: Self-Supervised Learning for Earth Observation | A large-scale self-supervised learning benchmark and pre-trained model for earth observation. | [IEEE TGRS](https://doi.org/10.1109/TGRS.2023.3251668) |
| SatLAS | SatLAS: A Large-Scale Satellite Image Dataset with Automatic Labels | A dataset of 137 million labeled satellite images with pre-trained Swin Transformer models for diverse geospatial tasks. | [ICCV](https://arxiv.org/abs/2211.15660) |
| AnySat | AnySat: One Earth Observation Model for Many Resolutions, Scales, and Modalities | A unified multi-resolution multimodal earth observation model using JEPA architecture for diverse EO tasks. | [CVPR](https://arxiv.org/abs/2412.14123) |
| TerraFM | TerraFM: A Scalable Foundation Model for Unified Multisensor Earth Observation | A scalable self-supervised foundation model for unified multisensor earth observation pre-trained on 18.7 million samples. | [ICLR 2026](https://openreview.net/forum?id=cBxuzdUDNx) |

---

<a id="earth-sciences-section-03"></a>
### Oceanography
*Foundation models for ocean forecasting, eddy-resolving prediction, and marine environment monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OceanGPT | OceanGPT: A Large Language Model for Ocean Science Tasks | A domain-specific large language model for ocean science by Zhejiang University using the DoInstruct framework for ocean domain instruction data. | [ACL 2024](https://arxiv.org/abs/2310.02031) |
| XiHe | XiHe: A Data-Driven Model for Global Ocean Eddy-Resolving Forecasting | A data-driven global ocean eddy-resolving forecast model at 1/12° resolution trained on 25 years of reanalysis data. | [arXiv](https://arxiv.org/abs/2402.02995) |
| WV-Net | WV-Net: A Foundation Model for SAR WV-mode Satellite Imagery Trained Using Contrastive Self-supervised Learning | The first foundation model for SAR ocean satellite imagery using self-supervised contrastive learning on synthetic aperture radar data. | [期刊论文](https://arxiv.org/abs/2406.18765) |
| GLONET | GLONET: Mercator's End-to-End Neural Global Ocean Forecasting System | An end-to-end neural network global ocean forecasting system by Mercator Ocean trained on GLORYS12 reanalysis data. | [Journal of Geophysical Research: Machine Learning and Computation](https://arxiv.org/abs/2412.05454) |
| WenHai | Forecasting the Eddying Ocean with a Deep Neural Network | A deep neural network ocean forecasting system excelling at mesoscale eddy dynamics prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-57389-2) |
| FuXi-Ocean | FuXi-Ocean: A Global Ocean Forecasting System with Sub-Daily Resolution | A data-driven global ocean forecasting system with 6-hour temporal and 1/12° spatial resolution reaching 1500-meter depth. | [NeurIPS](https://arxiv.org/abs/2506.03210) |
| OceanCastNet | Ocean Wave Forecasting with Deep Learning as Alternative to Physical Models | A deep learning ocean wave forecasting model that can replace the traditional physical model ECWAM. | [JAMES (2025)](https://arxiv.org/abs/2406.03848) |
| ORCA-DL | Data-driven Global Ocean Modeling for Seasonal to Decadal Prediction | A data-driven global ocean model supporting 3D ocean predictions from seasonal to decadal timescales. | [Science Advances](https://arxiv.org/abs/2405.15412) |
| FuXi-ONS | Data-driven Ensemble Prediction of the Global Ocean | A machine-learning ensemble global ocean forecasting system for 5-to-365-day predictions. | [arXiv](https://arxiv.org/abs/2603.19591) |

---

<a id="earth-sciences-section-04"></a>
### Seismology
*Foundation models for earthquake detection, seismic phase picking, and waveform analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PhaseNet | PhaseNet: A Deep-Neural-Network-Based Seismic Arrival-Time Picking Method | One of the most widely used deep learning models for seismic arrival-time picking in seismology. | [Geophysical Journal International](https://doi.org/10.1093/gji/ggy423) |
| EQTransformer | EQTransformer: An Attentive Deep-Learning Model for Simultaneous Earthquake Detection and Phase Picking | An attention-based deep learning model for simultaneous earthquake detection and seismic phase picking. | [Nature Communications](https://doi.org/10.1038/s41467-020-17591-w) |
| SeisT | SeisT: A Foundational Deep Learning Model for Earthquake Monitoring Tasks | A Transformer-based seismic monitoring foundation model supporting multiple earthquake tasks including detection, phase picking, and magnitude estimation. | [IEEE Transactions on Geoscience and Remote Sensing](https://arxiv.org/abs/2310.01037) |
| SeisLM | SeisLM: A Foundation Model for Seismic Waveforms | A large-scale self-supervised seismic waveform foundation model pre-trained via contrastive learning on massive open-source seismic data. | [arXiv](https://arxiv.org/abs/2410.15765) |
| SeisMoLLM | SeisMoLLM: Advancing Seismic Monitoring via Cross-modal Transfer with Pre-trained Large Language Model | A seismic monitoring foundation model leveraging cross-modal transfer from GPT-2 architecture for seismic analysis. | [arXiv](https://arxiv.org/abs/2502.19960) |
| SeismicXM | SeismicXM: A Cross-Task Foundation Model for Single-Station Seismic Waveform Processing | A cross-task seismic waveform processing foundation model by China Earthquake Administration supporting multiple single-station tasks. | [SRL](https://doi.org/10.1785/0220250290) |
| U-Trans | U-Trans: A Foundation Model for Seismic Waveform Representation | A U-Net encoder-decoder architecture seismic waveform representation foundation model trained on 2M+ three-component waveforms. | [Scientific Reports](https://doi.org/10.1038/s41598-026-41454-x) |
| EQCCT | EQCCT: A Production-Ready Earthquake Detection and Phase-Picking Method Using the Compact Convolutional Transformer | A production-ready compact convolutional Transformer for earthquake detection and phase picking. | [IEEE TGRS](https://doi.org/10.1109/TGRS.2023.3264212) |
| PhaseNet+ | PhaseNet+: Towards End-to-End Earthquake Monitoring Using a Multitask Deep Learning Model | A multi-task extension of PhaseNet enabling end-to-end earthquake monitoring. | [arXiv](https://arxiv.org/abs/2506.06939) |
| WaveCastNet | Rapid Wavefield Forecasting for Earthquake Early Warning | A deep learning model for real-time seismic wavefield prediction enabling rapid earthquake early warning. | [Nature Communications](https://doi.org/10.1038/s41467-025-65435-2) |
| SeisCLIP | SeisCLIP: Contrastive Multimodal Seismology Foundation Model | A contrastive multimodal seismology foundation model learning joint representations from seismic waveforms and metadata. | [arXiv](https://arxiv.org/abs/2309.02320) |

---

<a id="earth-sciences-section-05"></a>
### Hydrology
*Foundation models for hydrological prediction, flood modeling, and river forecasting.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| WaterGPT | WaterGPT: Training a Large Language Model to Become a Hydrology Expert | A hydrology-focused large language model fine-tuned on domain data for expert-level hydrological question answering and analysis. | [Water (MDPI, 2024)](https://www.mdpi.com/2073-4441/16/21/3075) |
| HydroGAT | HydroGAT: Distributed Heterogeneous Graph Attention Transformer for Spatiotemporal Flood Prediction | A graph attention network-based hydrological prediction foundation model capturing spatial dependencies across watersheds. | [arXiv](https://arxiv.org/abs/2509.02481) |
| δHBV-globe1.0 | δHBV-globe1.0: A Differentiable Global Hydrological Model | A differentiable global hydrological model combining the classic HBV conceptual model with deep learning gradient optimization. | [Geoscientific Model Development](https://doi.org/10.5194/gmd-17-7181-2024) |
| FloodCastBench | FloodCastBench: A Large-Scale Dataset and Foundation Models for Flood Modeling | A large-scale flood modeling dataset and accompanying foundation models for flood prediction. | [Scientific Data](https://doi.org/10.1038/s41597-025-04725-2) |
| ZeroFlood | ZeroFlood: A Geospatial Foundation Model for Data-Efficient Flood Susceptibility Mapping | A geospatial foundation model for data-efficient flood susceptibility mapping. | [arXiv](https://arxiv.org/abs/2510.23364) |
| PIFF | PIFF: Physics-Informed Generative Flow Model for Real-Time Flood Depth Mapping | A physics-informed generative flow model for real-time flood depth mapping. | [arXiv](https://arxiv.org/abs/2511.09130) |
| GraphRiverCast | Topology-informed AI Foundation Model for Global River Forecasting | A topology-informed AI foundation model for global river hydrodynamic forecasting. | [arXiv](https://arxiv.org/abs/2602.22293) |

---

<a id="earth-sciences-section-06"></a>
### Wildfire Prediction
*Models for wildfire danger forecasting and fire spread prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FireCastNet | FireCastNet: Earth-as-a-Graph for Seasonal Fire Prediction | A deep learning global wildfire danger forecasting model fusing meteorological, vegetation, and terrain data for multi-timescale prediction. | [Scientific Reports](https://doi.org/10.1038/s41598-025-30645-7) |
| FireScope | FireScope: Wildfire Risk Prediction with a Chain-of-Thought Oracle | A wildfire risk prediction foundation model and benchmark using multi-modal data for fire risk assessment. | [arXiv](https://arxiv.org/abs/2511.17171) |

---

<a id="earth-sciences-section-07"></a>
### Air Quality
*Foundation models for atmospheric pollution forecasting.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AirCast | AirCast: Improving Air Pollution Forecasting Through Multi-Variable Data Alignment | A data-driven air quality forecasting foundation model supporting multi-variable atmospheric pollutant concentration prediction. | [arXiv](https://arxiv.org/abs/2502.17919) |
| FuXi-Air | FuXi-Air: Urban Air Quality Forecasting Based on Emission-Meteorology-Pollutant Multimodal Machine Learning | A multimodal machine learning air quality forecasting extension of the FuXi series integrating emission, meteorological, and observational data. | [arXiv](https://arxiv.org/abs/2506.07616) |

---

<a id="earth-sciences-section-08"></a>
### Cryosphere
*Foundation models for sea ice monitoring and polar region forecasting.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SIFM | SIFM: A Foundation Model for Multi-granularity Arctic Sea Ice Forecasting | A sea ice foundation model for multi-granularity Arctic sea ice concentration forecasting from satellite observations. | [arXiv](https://arxiv.org/abs/2410.14732) |
| IceNet | IceNet: Seasonal Arctic Sea Ice Forecasting with Probabilistic Deep Learning | A probabilistic deep learning model for seasonal Arctic sea ice forecasting that significantly outperforms dynamical physics models. | [Nature Communications](https://doi.org/10.1038/s41467-021-25257-4) |
| IceMamba | IceMamba: Seasonal Forecasting of Pan-Arctic Sea Ice with State Space Model | A Mamba state space model-based sea ice forecasting foundation model efficiently processing polar spatiotemporal sequence data. | [arXiv](https://arxiv.org/abs/2505.10665) |

---

<a id="earth-sciences-section-09"></a>
### Geoscience Language Models
*Large language models specialized for earth science knowledge understanding and reasoning.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| K2 | K2: A Foundation Language Model for Geoscience Knowledge Understanding and Utilization | The first 7-billion-parameter geoscience LLM based on LLaMA, further pre-trained and instruction-tuned on earth science literature. | [Proceedings of the 17th ACM International Conference on Web Search and Data Mining](https://arxiv.org/abs/2306.05064) |
| JiuZhou | JiuZhou: Open Foundation Language Models for Geoscience | A multilingual geoscience LLM by Tsinghua University supporting Chinese and English earth science knowledge QA and reasoning. | [清华大学](https://github.com/THU-ESIS/JiuZhou) |
| GeoGPT | GeoGPT: A Large Language Model for Geospatial Artificial Intelligence | A geospatial AI LLM by Zhejiang Lab combining tool-calling capabilities for geospatial analysis and reasoning. | [之江实验室](https://github.com/GeoGPT-Research-Project/GeoGPT) |
| GeoGalactica | GeoGalactica: A Scientific Large Language Model for Geoscience | A 30-billion-parameter geoscience LLM based on Galactica architecture pre-trained on earth science corpora. | [arXiv](https://arxiv.org/abs/2401.00434) |

---

<a id="earth-sciences-section-10"></a>
### Subsurface & Exploration Geophysics
*Foundation models for subsurface characterization, seismic exploration, and well log analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Transparent Earth | The Transparent Earth: A Multimodal Foundation Model for the Earth's Subsurface | A multimodal transformer-based foundation model by LANL for subsurface structure imaging and inversion. | [LANL (2025)](https://arxiv.org/abs/2509.02783) |
| GEM 3D | Geological Everything Model 3D: A Promptable Foundation Model for Subsurface Understanding | A promptable generative 3D earth model unifying multiple geophysical tasks for subsurface structure modeling and geological property prediction. | [arXiv](https://arxiv.org/abs/2507.00419) |
| SFM-Exploration | Seismic Foundation Model (SFM): A New Generation Deep Learning Model in Geophysics | A Transformer-based self-supervised seismic foundation model for exploration geophysics supporting multiple downstream tasks. | [Geophysics (2025)](https://arxiv.org/abs/2309.02791) |
| WLFM | WLFM: A Well-Logs Foundation Model for Multi-Task Subsurface Analysis | A well log foundation model self-supervised pre-trained on large-scale well log data for lithology identification and reservoir prediction. | [arXiv](https://arxiv.org/abs/2509.18152) |

---

<a id="earth-sciences-section-11"></a>
### SAR-Specific Models
*Foundation models specialized for synthetic aperture radar data processing and interpretation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SARATR-X | SARATR-X: Toward Building A Foundation Model for SAR Target Recognition | A SAR target recognition foundation model pre-trained on large-scale SAR imagery supporting multiple recognition downstream tasks. | [IEEE Transactions on Image Processing](https://arxiv.org/abs/2405.09365) |
| SUMMIT | SUMMIT: A SAR Foundation Model with Multiple Auxiliary Tasks Enhanced Intrinsic Characteristics | A SAR universal multi-task foundation model unifying detection, segmentation, and classification via physics-driven self-supervised learning. | [Paper](https://www.sciencedirect.com/science/article/pii/S1569843225002717) |
| SAR-W-MixMAE | SAR-W-MixMAE: SAR Foundation Model Training Using Backscatter Power Weighting | A mixed masked autoencoder for SAR image pre-training optimizing speckle noise and geometric feature learning with polarization awareness. | [IGARSS 2025 - 2025 IEEE International Geoscience and Remote Sensing Symposium](https://arxiv.org/abs/2503.01181) |
| CrossEarth-SAR | CrossEarth: Billion-scale SAR Foundation Model for Domain-Generalizable Segmentation | A billion-scale SAR foundation model for domain-generalizable semantic segmentation across diverse SAR datasets. | [arXiv](https://arxiv.org/abs/2603.12008) |

---

<a id="earth-sciences-section-12"></a>
### Land Use
*Foundation models for land use and land cover mapping.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LandSegmenter | LandSegmenter: Towards a Flexible Foundation Model for Land Use and Land Cover Segmentation | A flexible land use/land cover segmentation foundation model pre-trained on large-scale multi-source remote sensing data for global LULC mapping. | [arXiv](https://arxiv.org/abs/2511.08156) |

---

<a id="earth-sciences-section-13"></a>
### Climate Downscaling
*Foundation models for high-resolution climate and weather downscaling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ORBIT-2 | ORBIT-2: Scaling Exascale Vision Transformer for Weather and Climate Downscaling | A climate downscaling foundation model trained on exascale computing infrastructure for efficient high-resolution climate inference. | [SC 2025](https://e3sm.org/best-paper-award-at-sc25-ai-driven-weather-prediction-with-orbit-2/) |
| SR-Weather | SR-Weather: Super-Resolution Framework for Weather Downscaling | A deep learning super-resolution framework downscaling coarse-resolution weather forecasts to kilometer-scale surface air temperature. | [npj Climate and Atmospheric Science](https://www.nature.com/articles/s41612-026-01328-5) |

## Astronomy

> [English](astronomy/astronomy_en.md) | [Chinese](astronomy/astronomy_zh.md)

### Table of Contents
- [Multimodal Astronomy](#astronomy-section-01)
- [Gravitational Wave Science](#astronomy-section-02)
- [Radio Astronomy](#astronomy-section-03)
- [Exoplanet Detection](#astronomy-section-04)
- [Cosmological Simulations](#astronomy-section-05)
- [CMB Analysis](#astronomy-section-06)
- [Survey Classifiers](#astronomy-section-07)
- [Planetary Science](#astronomy-section-08)

<a id="astronomy-section-01"></a>
### Multimodal Astronomy

#### Multimodal & Cross-Modal Foundation Models
*Foundation models that integrate multiple astronomical data modalities including imaging, spectra, and scalar measurements.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AION-1 | AION-1: Omnimodal Foundation Model for Astronomical Sciences | A large-scale omnimodal astronomical foundation model integrating 39 data modalities (imaging, spectra, scalar measurements) covering 200M+ astronomical objects. | [NeurIPS](https://arxiv.org/abs/2510.17960) |
| AstroCLIP | AstroCLIP: A Cross-Modal Foundation Model for Galaxies | A cross-modal galaxy foundation model using self-supervised contrastive learning to embed galaxy images and spectra into a shared physically meaningful latent space. | [Monthly Notices of the Royal Astronomical Society](https://arxiv.org/abs/2310.03024) |
| AstroLLaMA | AstroLLaMA: Towards Specialized Foundation Models in Astronomy | A 7-billion-parameter astronomy-specialized LLM based on LLaMA-2, fine-tuned on 300K+ astronomical abstracts. | [Proceedings of the Second Workshop on Information Extraction from Scientific Publications](https://arxiv.org/abs/2309.06126) |
| AstroLLaMA-2-70B | AstroMLab 2: AstroLLaMA-2-70B Model and Benchmarking Specialized LLMs for Astronomy | A 70-billion-parameter upgrade of AstroLLaMA providing more powerful domain-specific language understanding for astronomy. | [arXiv](https://arxiv.org/abs/2409.19750) |
| AstroPT | AstroPT: Scaling Large Observation Models for Astronomy | An open-source autoregressive pre-trained Transformer trained on 8.6 million DESI Legacy Survey galaxy images as a scalable large observation model. | [arXiv](https://arxiv.org/abs/2405.14930) |
| GalaxiesML | GalaxiesML: A Dataset of Galaxy Images, Photometry, Redshifts, and Structural Parameters for Machine Learning | A standardized astronomical ML dataset of 286K galaxy images with photometry, redshifts, and structural parameters for foundation model training and evaluation. | [arXiv](https://arxiv.org/abs/2410.00271) |
| astroBERT | astroBERT: A Language Model for Astronomy | A BERT-based language model pre-trained on astrophysics literature for astronomical text mining and NLP tasks. | [Astronomy & Computing](https://huggingface.co/adsabs/astroBERT) |

#### Spectral Foundation Models
*Models designed for processing and analyzing astronomical spectra across instruments and wavelengths.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OmniSpectra | OmniSpectra: A Unified Foundation Model for Native Resolution Astronomical Spectra | A unified astronomical spectral foundation model that processes arbitrary-length, any-instrument native-resolution spectra without resampling or interpolation. | [arXiv](https://arxiv.org/abs/2601.15351) |
| SpectraFM | SpectraFM: Tuning into Stellar Foundation Models | A stellar spectral foundation model pre-trained on large-scale stellar spectral data supporting spectral classification and parameter estimation. | [NeurIPS FM4Science Workshop (2024)](https://arxiv.org/abs/2411.04750) |

#### Time-Domain Astronomy & Light Curve Models
*Foundation models for astronomical light curve analysis, classification, and time-domain phenomena.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FALCO | FALCO: Foundation Model of Astronomical Light Curves for Time Domain Astronomy | An astronomical light curve foundation model based on Transformer self-supervised learning trained on Kepler data for multiple time-domain downstream tasks. | [AJ (2026)](https://arxiv.org/abs/2504.20290) |
| Astromer 2 | Astromer 2: Few-shot Light Curve Classification | A self-supervised light curve foundation model pre-trained on 1.5 million MACHO survey light curves supporting few-shot classification. | [A&A (2026)](https://arxiv.org/abs/2502.02717) |
| ASTROMER | ASTROMER: A Transformer-based Embedding for the Representation of Light Curves | The first Transformer-based pre-trained model for astronomical light curve representation, transferable across multiple survey datasets. | [A&A](https://doi.org/10.1051/0004-6361/202243928) |
| AstroCo | AstroCo: Self-Supervised Conformer-Style Transformers for Light-Curve Embeddings | A self-supervised Conformer-style Transformer encoder for processing irregular stellar light curves. | [arXiv](https://arxiv.org/abs/2509.24134) |

---

<a id="astronomy-section-02"></a>
### Gravitational Wave Science
*Foundation models for gravitational wave detection, parameter estimation, and signal analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| GraviBERT | GraviBERT: Transformer-based Inference for Gravitational-Wave Time Series | A BERT-style transformer foundation model for gravitational wave signal analysis supporting detection and parameter estimation. | [Machine Learning: Science and Technology](https://arxiv.org/abs/2512.21390) |
| Dingo-T1 | Dingo-T1: Flexible Gravitational-Wave Parameter Estimation with Transformers | A transformer-based foundation model for near real-time gravitational wave posterior parameter estimation. | [NeurIPS ML4PS (2025)](https://arxiv.org/abs/2512.02968) |
| WaveFormer | WaveFormer: Transformer-based Denoising Method for Gravitational-Wave Data | A Transformer-based model for denoising and signal recovery in LIGO gravitational wave interferometer time-series data. | [Machine Learning: Science and Technology](https://arxiv.org/abs/2212.14283) |
| GW-FALCON | GW-FALCON: Feature-driven Deep Learning for Early Gravitational Wave Detection | A feature-driven deep learning model for early-stage gravitational wave detection from interferometer data. | [arXiv](https://arxiv.org/abs/2602.15073) |

---

<a id="astronomy-section-03"></a>
### Radio Astronomy
*Foundation models for radio telescope data analysis, source classification, and morphology.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RGZ-FM | Radio Galaxy Zoo: Towards Building the First Multi-purpose Foundation Model for Radio Astronomy | The first multi-purpose radio astronomy foundation model pre-trained on Radio Galaxy Zoo data for radio source classification and morphology analysis. | [arXiv](https://arxiv.org/abs/2305.16127) |
| STRADAViT | STRADAViT: Towards a Foundational Model for Radio Astronomy through Self-Supervised Transfer | A self-supervised Vision Transformer foundation model for radio astronomy data handling diverse radio interferometric imaging tasks. | [arXiv](https://arxiv.org/abs/2603.29660) |
| SKATR | SKATR: A Self-Supervised Summary Transformer for SKA Radio Continuum Data | A self-supervised summary Transformer foundation model for SKA radio continuum survey data providing universal feature representations. | [SciPost (2025)](https://arxiv.org/abs/2410.18899) |

---

<a id="astronomy-section-04"></a>
### Exoplanet Detection
*Deep learning models for transit detection and exoplanet validation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ExoMiner++ | ExoMiner++: Enhanced Transit Classification and a New Vetting Catalog | An improved deep learning model by NASA for exoplanet transit validation with enhanced accuracy and reliability for TESS data. | [NASA](https://doi.org/10.3847/1538-3881/ae03a4) |
| PANOPTICON | PANOPTICON: A Novel Deep Learning Model to Detect Single Transit Events in PLATO Light Curves | A deep learning foundation model for automatic detection of single exoplanet transit events in PLATO light curves without prior data filtering. | [A&A](https://doi.org/10.1051/0004-6361/202452124) |

---

<a id="astronomy-section-05"></a>
### Cosmological Simulations
*Foundation models and emulators for cosmological power spectra, structure formation, and N-body simulations.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CosmoPower | CosmoPower: Emulating Cosmological Power Spectra for Accelerated Bayesian Inference | A neural network emulator for rapid and accurate cosmological power spectrum generation replacing traditional Boltzmann solvers. | [arXiv](https://arxiv.org/abs/2106.03846) |
| GOTHAM | GOTHAM: Teaching Dark Matter Simulations to Speak the Halo Language | A conditional generative Transformer for auto-regressive halo catalog modeling that rapidly populates cosmological simulations. | [arXiv](https://arxiv.org/abs/2409.11401) |
| COCA | COCA: COmoving Computer Acceleration for N-body Simulations | A hybrid machine learning framework accelerating N-body cosmological simulations by emulating particle displacements in a comoving frame. | [A&A (2025)](https://arxiv.org/abs/2409.02154) |
| EMBER-2 | EMBER-2: Emulating Baryons from Dark Matter Across Cosmic Time | A machine learning emulator that predicts baryonic effects from dark matter simulations across cosmological time with deep modulation networks. | [arXiv](https://arxiv.org/abs/2502.15875) |
| CosmosGalaxyFM | Multi-modal Foundation Model for Cosmological Simulation Data | A multi-modal encoder-only transformer foundation model for cosmological galaxy simulation data. | [NeurIPS ML4PS](https://arxiv.org/abs/2510.07684) |

---

<a id="astronomy-section-06"></a>
### CMB Analysis
*Deep learning models for cosmic microwave background component separation and analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| CMB-ML | CMB-ML: A Cosmic Microwave Background Dataset for the Oldest Possible Computer Vision Task | A deep learning framework and dataset for CMB component separation enabling foreground signal removal. | [ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/html/Amato_CMB-ML_A_Cosmic_Microwave_Background_Dataset_for_the_Oldest_Possible_Computer_Vision_Task_ICCV_2025_paper.html) |
| PUREPath | PUREPath: A Deep Learning Approach for CMB B-mode Delensing | A deep learning method for CMB B-mode delensing that removes gravitational lensing effects to detect primordial gravitational wave signals. | [arXiv](https://arxiv.org/abs/2503.20774) |
| Deep Needlet | Deep Needlet: A CNN-based Full Sky Component Separation Method in Needlet Space | A CNN-based CMB analysis method operating on needlet coefficients for efficient full-sky component separation. | [arXiv](https://arxiv.org/abs/2501.07469) |

---

<a id="astronomy-section-07"></a>
### Survey Classifiers
*Foundation models for automated classification in large astronomical surveys.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ORACLE | ORACLE: A Real-time, Hierarchical, Deep Learning Photometric Classifier for the LSST | A real-time hierarchical deep learning classifier for automated transient and variable astrophysical source classification in LSST survey data. | [The Astrophysical Journal](https://arxiv.org/abs/2501.01496) |
| SPLASH | SPLASH: A Rapid Host-Based Supernova Classifier for Wide-Field Surveys | A fast host-galaxy-based supernova classifier using only host photometry for rapid type inference in LSST-scale surveys. | [arXiv](https://arxiv.org/abs/2506.00121) |

---

<a id="astronomy-section-08"></a>
### Planetary Science
*Foundation models for planetary remote sensing and orbital data analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MOMO | MOMO: Mars Orbital Model Foundation Model | A multi-sensor Mars orbital remote sensing foundation model for planetary surface analysis. | [arXiv](https://arxiv.org/abs/2604.02719) |

## Medicine & Biomedicine

> [English](medicine/medicine_en.md) | [Chinese](medicine/medicine_zh.md)

### Table of Contents
- [Medical Imaging](#medicine-section-01)
- [Neuroimaging](#medicine-section-02)
- [Pathology](#medicine-section-03)
- [Endoscopy & Surgery](#medicine-section-04)
- [Ultrasound](#medicine-section-05)
- [ECG & Physiological Signals](#medicine-section-06)
- [Dental Imaging](#medicine-section-07)
- [Ophthalmology](#medicine-section-08)
- [Medical NLP](#medicine-section-09)
- [Medical Multimodal](#medicine-section-10)
- [Electronic Health Records](#medicine-section-11)
- [Nuclear Medicine](#medicine-section-12)
- [Mammography](#medicine-section-13)
- [Musculoskeletal Imaging](#medicine-section-14)
- [Wearable & Digital Health](#medicine-section-15)
- [Radiation Therapy](#medicine-section-16)
- [Microscopy](#medicine-section-17)
- [Sleep Medicine](#medicine-section-18)
- [Veterinary Medicine](#medicine-section-19)
- [Forensic Science](#medicine-section-20)

<a id="medicine-section-01"></a>
### Medical Imaging

*Foundation models for CT, MRI, X-ray, and other modalities — covering segmentation, classification, detection, and report generation across clinical imaging tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MRI-CORE | MRI-CORE: A Foundation Model for Magnetic Resonance Imaging | Foundation model pretrained on 110,000+ MRI volumes (6M+ slices) covering 18 body regions, supporting segmentation, classification, and zero-shot analysis. | [arXiv](https://arxiv.org/abs/2506.12186) |
| Pillar-0 | Pillar-0: A New Frontier for Radiology Foundation Models | Radiology foundation model from UC Berkeley/UCSF pretrained on abdominal-pelvic CT, chest CT, head CT, and breast MRI for interpreting 3D volumetric data. | [arXiv](https://arxiv.org/abs/2511.17803) |
| CineMA | CineMA: A Foundation Model for Cine Cardiac MRI | Cardiac MRI foundation model trained on 15 million cardiac MR images (~75,000 subjects), supporting ventricular segmentation, ejection fraction estimation, and disease detection. | [arXiv](https://arxiv.org/abs/2506.00679) |
| OmniMRI | OmniMRI: A Unified Vision-Language Foundation Model for MRI | Unified MRI foundation model covering acquisition, reconstruction, segmentation, detection, diagnosis, and report generation. | [arXiv](https://arxiv.org/abs/2508.17524) |
| BiomedCLIP | BiomedCLIP: A Multimodal Biomedical Foundation Model Pretrained from Fifteen Million Scientific Image-Text Pairs | Microsoft biomedical vision-language model pretrained on PMC-15M (15M image-text pairs), supporting cross-modal retrieval and zero-shot classification. | [NeurIPS](https://arxiv.org/abs/2303.00915) |
| SAM-Med2D | SAM-Med2D | Adaptation of Segment Anything Model (SAM) for 2D medical image segmentation, fine-tuned on 4.6M images and 19.7M masks. | [arXiv](https://arxiv.org/abs/2308.16184) |
| SAM-Med3D | SAM-Med3D: Towards General-purpose Segmentation Models for Volumetric Medical Images | General-purpose 3D medical image segmentation model supporting multiple anatomical structures and lesions with minimal interactive annotation. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2310.15161) |
| MedSAM | Segment Anything in Medical Images | First universal medical image segmentation foundation model trained on 1.57M+ image-mask pairs across 10 imaging modalities. | [Nature Communications](https://arxiv.org/abs/2304.12306) |
| MedSAM2 | MedSAM2: Segment Anything in 3D Medical Images and Videos | SAM 2-based 3D medical image and video segmentation model fine-tuned on 455,000+ 3D image-mask pairs. | [arXiv](https://arxiv.org/abs/2504.03600) |
| CT-CLIP | A Foundation Model Utilizing Chest CT Volumes and Radiology Reports for Supervised-Level Zero-Shot Detection of Abnormalities | 3D chest CT foundation model using contrastive language-image pretraining on CT-RATE dataset for zero-shot abnormality detection. | [Nature Biomedical Engineering](https://arxiv.org/abs/2403.17834) |
| CheXzero | Expert-Level Detection of Pathologies from Unannotated Chest X-ray Images via Self-Supervised Learning | Self-supervised contrastive learning model for zero-shot chest X-ray analysis achieving expert-level pathology detection without annotations. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-022-00936-9) |
| BioViL | Making the Most of Text Semantics to Improve Biomedical Vision-Language Processing | Microsoft biomedical vision-language model combining domain-specific language model CXR-BERT for enhanced chest X-ray analysis. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2204.09817) |
| BioViL-T | Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing | Microsoft temporal vision-language model for longitudinal chest X-ray analysis and phrase grounding in radiology. | [CVPR](https://arxiv.org/abs/2301.04558) |
| LVM-Med | LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-Order Graph Matching | Large-scale self-supervised medical imaging vision model trained on ~1.3M multi-modal images (CT/MRI/X-ray/ultrasound). | [NeurIPS 2024](https://arxiv.org/abs/2306.11925) |
| STU-Net | STU-Net: Scalable and Transferable Medical Image Segmentation Models Empowered by Large-Scale Supervised Pre-training | Scalable medical image segmentation model up to 1.4B parameters with strong transferability via large-scale supervised pretraining. | [arXiv](https://arxiv.org/abs/2304.06716) |
| UniverSeg | UniverSeg: Universal Medical Image Segmentation | Medical image segmentation model that generalizes to unseen tasks without additional training using in-context learning. | [2023 IEEE/CVF International Conference on Computer Vision (ICCV)](https://arxiv.org/abs/2304.06131) |
| RadImageNet | RadImageNet: An Open Radiologic Deep Learning Research Dataset for Effective Transfer Learning | Large-scale dataset and pretrained models on 1.35M radiologic images (CT/MRI/ultrasound) for medical imaging transfer learning. | [Radiology: AI](https://doi.org/10.1148/ryai.210315) |
| RETFound | A Foundation Model for Generalizable Disease Detection from Retinal Images | Ophthalmic foundation model self-supervised pretrained on 1.6M unlabeled retinal images, supporting multiple eye and systemic disease detection. | [Nature](https://doi.org/10.1038/s41586-023-06555-x) |
| SkinGPT-4 | Pre-trained Multimodal Large Language Model Enhances Dermatological Diagnosis Using SkinGPT-4 | Interactive dermatological diagnosis system integrating a vision transformer and Llama-2-13b-chat, trained on 52,000+ skin disease images. | [Nature Communications](https://arxiv.org/abs/2304.10691) |
| PanDerm | A Multimodal Vision Foundation Model for Clinical Dermatology | Multimodal dermatology foundation model pretrained on 2M+ skin disease images from 11 institutions across 4 imaging modalities. | [Nature Medicine](https://arxiv.org/abs/2410.15038) |
| RadFM | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data | Generalist radiology foundation model using 13M 2D images and 615K 3D scans for multi-modal training. | [Nature Communications](https://arxiv.org/abs/2308.02463) |
| CheXFound | Chest X-ray Foundation Model with Global and Local Self-supervised Learning | Foundation model self-supervised pretrained on ~1M chest X-rays combining global and local learning strategies for improved clinical task generalization. | [arXiv](https://arxiv.org/abs/2502.05142) |
| REMEDIS | Robust and Data-Efficient Generalization of Self-Supervised Machine Learning for Diagnostic Imaging | Google medical imaging representation learning framework combining large-scale self-supervised pretraining with task-specific fine-tuning for improved robustness and data efficiency. | [Nature Biomedical Engineering](https://arxiv.org/abs/2205.09723) |
| Medical SAM Adapter | Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation | Adapter-based approach to adapt SAM for medical image segmentation while preserving SAM's original capabilities. | [Medical Image Analysis](https://arxiv.org/abs/2304.12620) |
| MedicoSAM | MedicoSAM: Towards Foundation Models for Medical Image Segmentation | Systematic study exploring the adaptation of SAM as a foundation model for medical image segmentation. | [arXiv](https://arxiv.org/abs/2501.11734) |
| BiomedParse | BiomedParse: Biomedical Foundation Model for Image Parsing | Microsoft unified biomedical image parsing foundation model supporting segmentation, detection, and recognition. | [Nature Methods](https://arxiv.org/abs/2405.12971) |
| TotalSegmentator | TotalSegmentator: Robust Segmentation of 104 Anatomic Structures in CT Images | Automatic CT segmentation of 104 anatomical structures, trained on 1,228 cases. | [Radiology: AI](https://doi.org/10.1148/ryai.230024) |
| SegVol | SegVol: Universal and Interactive Volumetric Medical Image Segmentation | Universal interactive 3D medical image segmentation supporting semantic and spatial prompts. | [Advances in Neural Information Processing Systems 37](https://arxiv.org/abs/2311.13385) |
| SuPreM | SuPreM: Label-Efficient 3D Medical Image Segmentation via Supervised Pre-training | Supervised pretrained 3D segmentation foundation model trained on 2,100+ CT scans. | [IEEE TMI](https://arxiv.org/abs/2410.06667) |
| VISTA3D | VISTA3D: Versatile Imaging Segmentation and Annotation Model for 3D | NVIDIA versatile 3D medical image segmentation and annotation model. | [MICCAI](https://arxiv.org/abs/2406.05236) |
| CT-FM | CT Foundation Model for Body Composition Analysis | CT foundation model for body composition analysis. | [arXiv](https://arxiv.org/abs/2501.09001) |
| LCTfound | Learning CT Foundation Representations | Foundation representation learning for CT imaging. | [arXiv](https://arxiv.org/abs/2501.09001) |
| EVA-X | EVA-X: A Foundation Model for General Chest X-ray Analysis | Foundation model for general chest X-ray analysis. | [arXiv](https://arxiv.org/abs/2405.05237) |
| vesselFM | vesselFM: A Foundation Model for Universal 3D Blood Vessel Segmentation | Universal 3D blood vessel segmentation foundation model. | [arXiv](https://arxiv.org/abs/2504.02750) |
| Rad-DINO | RAD-DINO: Exploring Scalable Medical Image Encoders Beyond Text Supervision | Scalable medical image encoder going beyond text supervision. | [arXiv](https://arxiv.org/abs/2401.10815) |
| MAIRA-2 | MAIRA-2: Grounded Radiology Report Generation | Microsoft grounded radiology report generation combining localization and text. | [arXiv](https://arxiv.org/abs/2406.04449) |
| MedCLIP | MedCLIP: Contrastive Learning from Unpaired Medical Images and Text | Decoupled contrastive learning medical vision-language model from unpaired data. | [EMNLP 2022](https://arxiv.org/abs/2210.10163) |
| PMC-CLIP | PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents | Biomedical CLIP pretrained on PubMed Central documents. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2303.07240) |
| M3D | M3D: Advancing 3D Medical Image Analysis with Multi-Modal Large Language Models | 3D medical imaging multi-modal large language model. | [arXiv](https://arxiv.org/abs/2404.00578) |
| Merlin | Merlin: A Vision Language Foundation Model for 3D Computed Tomography | 3D CT vision-language foundation model trained on 15,000+ CTs. | [arXiv](https://arxiv.org/abs/2406.06512) |
| ELIXR | ELIXR: Towards a general purpose X-ray AI system through alignment of large language models with radiology vision encoders | Google system aligning large language models with radiology vision encoders for general-purpose X-ray AI. | [Nature](https://doi.org/10.1038/s41586-024-08397-x) |
| CXR-LLaVA | CXR-LLaVA: Multimodal Large Language Model for Interpreting Chest X-ray | Multimodal large language model for chest X-ray interpretation. | [arXiv](https://arxiv.org/abs/2310.18341) |
| 3DINO | 3DINO: Self-supervised 3D Anatomical Representation Learning | Self-supervised 3D anatomical representation learning. | [arXiv](https://arxiv.org/abs/2501.00825) |
| DeepMedix-R1 | DeepMedix-R1: Reasoning-Based Medical Imaging Foundation Model | Reasoning-enhanced medical imaging foundation model. | [arXiv](https://arxiv.org/abs/2503.07287) |
| MedImageInsight | MedImageInsight: An Open-Source Embedding Model for General Domain Medical Imaging | Microsoft open-source medical imaging embedding foundation model covering 14 imaging modalities, supporting multiple downstream tasks. | [arXiv / Microsoft](https://arxiv.org/abs/2410.06542) |
| Curia | Curia: A Multi-Modal Foundation Model for Radiology | Large-scale radiology multi-modal foundation model trained on 150K CT/MRI exams (130TB data), supporting report generation and image understanding. | [arXiv](https://arxiv.org/abs/2509.06830) |
| Medical SAM3 | Medical SAM3: A Foundation Model for Universal Prompt-Driven Medical Image Segmentation | Universal prompt-driven medical image segmentation foundation model based on SAM3, supporting both 2D and 3D medical data. | [arXiv](https://arxiv.org/abs/2601.10880) |
| OmniRad | OmniRad: A self-supervised radiological foundation model | Self-supervised radiology foundation model trained on 1.2M medical images with strong cross-task transfer capabilities. | [arXiv](https://arxiv.org/abs/2602.04547) |
| MedVAR | MedVAR: Towards Scalable and Efficient Medical Image Generation via Next-scale Autoregressive Prediction | Scalable and efficient medical image generation foundation model using next-scale autoregressive prediction. | [arXiv](https://arxiv.org/abs/2602.14512) |
| FMIR | FMIR: A foundation model-based Image Registration Framework for Robust Image Registration | Foundation model-based medical image registration framework for robust image registration. | [arXiv](https://arxiv.org/abs/2601.17529) |
| Citrus-V | Citrus-V: Advancing Medical Foundation Models with Unified Medical Image Grounding for Clinical Reasoning | Unified medical image grounding and clinical reasoning multi-modal foundation model integrating detection, segmentation, and structured reasoning. | [arXiv](https://arxiv.org/abs/2509.19090) |
| DermFM-Zero | DermFM-Zero: A Vision-Language Foundation Model for Zero-shot Clinical Dermatology | Dermatology vision-language foundation model trained on 4M+ multi-modal data for zero-shot diagnosis. | [arXiv](https://arxiv.org/abs/2602.10624) |
| DermFM | DermFM: A Dermatology Foundation Model by Google Health | Google Health dermatology foundation model pretrained on large-scale clinical dermatological data supporting AI-assisted diagnosis of multiple skin conditions. | [Google Research](https://arxiv.org/search/?query=DermFM+dermatology+foundation+model) |
| SkinCLIP-VL | SkinCLIP-VL: Consistency-Aware Vision-Language Learning for Multimodal Skin Cancer Diagnosis | Consistency-aware vision-language learning for multimodal skin cancer diagnosis. | [arXiv](https://arxiv.org/abs/2603.21010) |
| PRISM-MRI | PRISM: A Multi-Modal MRI Foundation Model | Multi-modal MRI foundation model integrating multiple MRI sequences for multi-task clinical analysis. | [arXiv](https://arxiv.org/search/?query=PRISM+multi-modal+MRI+foundation+model) |
| BioMedGPT-R1 | BioMedGPT-R1: A 17B Multimodal Biomedical Foundation Model | Tsinghua University 17B-parameter multimodal biomedical foundation model integrating medical imaging and text understanding. | [Tsinghua](https://arxiv.org/search/?query=BioMedGPT-R1+multimodal+biomedical) |
| LLaVA-NeXT-Med | LLaVA-NeXT-Med: Medical Visual Instruction Tuning for Next-Generation Multimodal LLMs | Medical version of LLaVA-NeXT enhanced through medical visual instruction tuning for improved multimodal medical image understanding and reasoning. | [arXiv](https://arxiv.org/search/?query=LLaVA-NeXT-Med+medical+visual+instruction) |
| ChexGen | A Generative Foundation Model for Chest Radiography | Generative foundation model for chest X-ray synthesis. | [arXiv](https://arxiv.org/abs/2509.03903) |
| CheXficient | A data- and compute-efficient chest X-ray foundation model | Data- and compute-efficient chest X-ray foundation model. | [arXiv](https://arxiv.org/abs/2602.22843) |
| Ark+ | Fully open AI foundation model for chest radiography | Fully open AI foundation model for chest radiography published in Nature. | [Nature](https://doi.org/10.1038/s41586-025-08954-4) |
| MedSigLIP | Medical dual-tower vision-language encoder | Medical dual-tower vision-language encoder developed by Google Health. | [Google Health](https://arxiv.org/search/?query=MedSigLIP+medical+vision+language) |

---

<a id="medicine-section-02"></a>
### Neuroimaging

*Foundation models for brain MRI and fMRI data analysis — covering brain disease detection, brain region segmentation, cognitive state decoding, and neuroscience tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BrainIAC | A Generalizable Foundation Model for Analysis of Human Brain MRI | Foundation model self-supervised pretrained on ~49,000 unlabeled brain MRIs, learning universal brain representations for multiple downstream clinical tasks. | [Nature Neuroscience](https://doi.org/10.1038/s41593-026-02202-6) |
| GenBrain | GenBrain: A Generative Foundation Model of Multimodal Brain Imaging | Large-scale multimodal brain imaging generative foundation model pretrained on ~1.2M 3D MRI scans (44,000+ individuals, 34 imaging modalities). | [medRxiv](https://doi.org/10.1101/2025.12.19.25342614) |
| Prima | Learning Neuroimaging Models from Health System-Scale Data | Large-scale AI neuroimaging foundation model from University of Michigan trained on 220,000+ health system MRI studies, capable of reading brain MRIs within seconds. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-025-01608-0) |
| BrainSymphony | BrainSymphony: A Parameter-Efficient Multimodal Foundation Model for Neuroimaging | Lightweight, parameter-efficient multimodal neuroimaging foundation model integrating fMRI time series and diffusion MRI-derived structural connectivity. | [arXiv](https://arxiv.org/abs/2506.18314) |
| CytoNet | CytoNet: A Foundation Model for the Human Cerebral Cortex | Foundation model for analyzing human cerebral cortex at cellular resolution, trained on 1M+ unlabeled histological image patches. | [arXiv](https://arxiv.org/abs/2511.01870) |
| BrainLM | BrainLM: A Foundation Model for Brain Activity Recordings | Brain activity foundation model trained on 6,700 hours of fMRI data using self-supervised masked prediction for predicting age, sex, and clinical variables. | [ICLR](https://arxiv.org/abs/2311.00768) |
| BrainFM | BrainFM: A Modality-Agnostic Multi-task Foundation Model for Human Brain Imaging | Modality-agnostic multi-task brain imaging foundation model that generalizes across MRI/fMRI/EEG and other neuroimaging modalities. | [arXiv](https://arxiv.org/abs/2509.00549) |
| BrainGFM | BrainGFM: A Brain Graph Foundation Model for Neuroimaging Analysis | Brain graph foundation model using graph contrastive learning and masked autoencoders for fMRI data. | [NeurIPS](https://openreview.net/forum?id=BrainGFM) |
| BrainFounder | BrainFounder: Towards 3D Foundation Models for Neuroimage Segmentation | Large-scale neuroimaging segmentation foundation model pretrained on multimodal MRI from 41,400 participants with a two-stage pretraining strategy. | [MICCAI](https://arxiv.org/abs/2406.10395) |
| Brain Harmony | Brain Harmony: A Multimodal Foundation Model Unifying Brain Structural Morphology and Functional Dynamics | First multimodal brain foundation model unifying brain structural morphology (T1-MRI) and functional dynamics (fMRI). | [arXiv](https://arxiv.org/abs/2509.24693) |
| Brain-OF | Brain-OF: An Omnifunctional Foundation Model for fMRI, EEG and MEG | Omnifunctional foundation model spanning fMRI, EEG, and MEG neuroimaging modalities. | [arXiv](https://arxiv.org/abs/2602.23410) |
| SAM-Brain3D | Brain Foundation Models with Hypergraph Dynamic Adapter for Brain Disease Analysis | Brain imaging foundation model trained on 66,000+ MRI image-label pairs (14 sub-modalities) for brain disease analysis. | [Pattern Recognition](https://arxiv.org/abs/2505.00627) |
| MindLLM | MindLLM: A Subject-Agnostic and Versatile Model for fMRI-to-Text Decoding | Subject-agnostic fMRI-to-text decoding model advancing brain-computer interface research. | [ICML 2025](https://openreview.net/forum?id=MindLLM) |
| Decipher-MR | Decipher-MR: A Vision-Language Foundation Model for 3D MRI Representations | 3D MRI vision-language foundation model trained on 200,000+ MRI sequences, supporting multiple brain disease analysis including psychiatric disorders. | [npj Digital Medicine](https://arxiv.org/abs/2509.21249) |
| SLIM-Brain | Data-efficient FM for fMRI analysis | Data-efficient foundation model for fMRI analysis. | [arXiv](https://arxiv.org/abs/2512.21881) |

---

<a id="medicine-section-03"></a>
### Pathology

*Foundation models for whole-slide image (WSI) analysis in histopathology — covering cancer detection, biomarker prediction, disease classification, and computational pathology tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Virchow | Virchow: A Million-Slide Digital Pathology Foundation Model | Paige/Microsoft digital pathology foundation model self-supervised trained on 1.5M H&E-stained WSIs, supporting cancer detection and rare cancer identification. | [Nature Medicine](https://arxiv.org/abs/2309.07778) |
| Virchow2 | Virchow 2: Scaling Self-Supervised Mixed Magnification Models in Pathology | Second-generation Virchow including Virchow2 (632M params) and Virchow2G (1.85B params), trained at mixed magnifications. | [arXiv](https://arxiv.org/abs/2408.00738) |
| UNI | Towards a General-Purpose Foundation Model for Computational Pathology | Mahmood Lab general-purpose computational pathology foundation model self-supervised trained on 100K+ WSIs across 20+ major tissue types. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02857-3) |
| UNI2 | UNI2: A Universal Foundation Model for Computational Pathology | Upgraded UNI pretrained on 200M+ pathology images (350,000+ slides), released January 2025. | [arXiv](https://arxiv.org/abs/2501.07581) |
| CONCH | A Visual-Language Foundation Model for Computational Pathology | First pathology visual-language foundation model (CONtrastive learning from Captions for Histopathology) trained on 1.17M+ image-text pairs. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02856-4) |
| TITAN | A Multimodal Whole-Slide Foundation Model for Pathology | Multimodal whole-slide foundation model combining visual self-supervised learning on 335,000+ WSIs with pathology report visual-language alignment. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03982-3) |
| Prov-GigaPath | A Whole-Slide Foundation Model for Digital Pathology from Real-World Data | Microsoft whole-slide foundation model pretrained on 1.3B image tiles (171,000+ real-world slides) with open-source weights. | [Nature](https://doi.org/10.1038/s41586-024-07441-w) |
| PLIP | A Visual-Language Foundation Model for Pathology Image Analysis Using Medical Twitter | CLIP-based pathology visual-language foundation model trained on medical social media data (OpenPath dataset). | [Nature Medicine](https://doi.org/10.1038/s41591-023-02504-3) |
| PathChat | A Foundational Multimodal Vision Language AI Assistant for Human Pathology | Multimodal pathology AI assistant integrating a vision encoder trained on 100M histology images and an LLM for interactive pathology analysis. | [Nature](https://arxiv.org/abs/2312.07814) |
| CTransPath | Transformer-Based Unsupervised Contrastive Learning for Histopathological Image Classification | Histopathology feature extractor based on CNN-Swin Transformer hybrid architecture with self-supervised contrastive learning. | [Medical Image Analysis](https://doi.org/10.1016/j.media.2022.102559) |
| Hibou | Hibou: A Family of Foundational Vision Transformers for Pathology | HistAI family of pathology vision transformers (Hibou-B and Hibou-L) for cell detection, tissue classification, and more. | [arXiv](https://arxiv.org/abs/2406.05074) |
| Phikon | Scaling Self-Supervised Learning for Histopathology with Masked Image Modeling | Owkin histopathology self-supervised foundation model using iBOT framework trained on large-scale pathology data. | [arXiv](https://arxiv.org/abs/2310.08778) |
| Phikon-v2 | Phikon-v2: A Large and Public Feature Extractor for Biomarker Prediction | Upgraded Phikon trained on 460M+ pathology tiles (55,000+ slides, 30+ cancer types) as a large-scale public feature extractor. | [arXiv](https://arxiv.org/abs/2409.09173) |
| H-optimus-0 | H-optimus-0: An Open-Source AI Foundation Model for Pathology | World's largest open-source pathology AI foundation model (1.1B parameters) trained on 500,000+ WSIs, developed by Bioptimus. | [arXiv](https://arxiv.org/abs/2411.05114) |
| PathChat+ | A Clinical-Grade Agentic and Generative AI-Driven Copilot for Pathology | Clinical-grade upgrade of PathChat trained on 1M+ pathology-specific instruction samples and 5.5M QA pairs. | [arXiv](https://arxiv.org/abs/2506.20964) |
| UniBiomed | UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation | Unified biomedical image interpretation foundation model integrating multimodal LLM and segmentation model for simultaneous conversation and segmentation. | [arXiv](https://arxiv.org/abs/2504.21336) |
| CHIEF | Clinical Histopathology Imaging Evaluation Foundation | Universal clinical histopathology AI system pretrained on 60,000+ WSIs (19 anatomical sites), supporting cancer detection, grading, and molecular marker prediction. | [Nature](https://doi.org/10.1038/s41586-024-07894-3) |
| Atlas | Atlas: A Whole-Slide Foundation Model for Computational Pathology | Whole-slide level pathology foundation model. | [arXiv](https://arxiv.org/abs/2407.05325) |
| MUSK | A Vision-Language Foundation Model for Precision Oncology | Precision oncology vision-language foundation model supporting multimodal cancer diagnosis and prognosis prediction. | [Nature](https://doi.org/10.1038/s41586-025-08780-8) |
| PRISM | Predicting Regulatory Interactions from Single Morphology | Pathology multimodal foundation model integrating visual and molecular information. | [Nature Medicine](https://doi.org/10.1038/s41591-024-03141-0) |
| PathOrchestra | PathOrchestra: A Comprehensive Foundation Model for Computational Pathology | Comprehensive computational pathology foundation model covering multiple pathology tasks. | [arXiv](https://arxiv.org/abs/2503.00203) |
| kaiko.ai | Towards Training Large-Scale Pathology Foundation Models | Large-scale pathology foundation model training providing multi-scale ViT variants. | [arXiv](https://arxiv.org/abs/2404.15217) |
| RudolfV | A Foundation Model Connecting Pathology Images and Genomic Sequences | Foundation model connecting pathology images and genomic sequences. | [arXiv](https://arxiv.org/abs/2401.09027) |
| BEPH | A Foundation Model for Pathology using Bioptimus | Bioptimus-developed pathology foundation model. | [Bioptimus](https://arxiv.org/search/?query=BEPH+Bioptimus+pathology+foundation) |
| GPFM | A Generalizable Pathology Foundation Model | Generalizable pathology foundation model trained on 190K+ WSIs. | [arXiv](https://arxiv.org/abs/2407.18807) |
| mSTAR | Multi-Scale Tissue-Aware Representation | Multi-scale tissue-aware representation learning for pathology. | [arXiv](https://arxiv.org/abs/2407.15362) |
| HIPT | Hierarchical Image Pyramid Transformer for Whole-Slide Image Analysis | Hierarchical image pyramid Transformer for self-supervised learning on whole-slide images. | [CVPR](https://arxiv.org/abs/2206.02647) |
| RetCCL | Retention-based Contrastive Learning for Histopathology | Retention-based contrastive learning pathology feature extractor. | [Medical Image Analysis](https://doi.org/10.1016/j.media.2022.102645) |
| PathoDuet | Foundation Models for Pathological Image Analysis via Self-Supervised Learning | Dual-scale self-supervised pathology foundation model. | [arXiv](https://arxiv.org/abs/2312.09849) |
| PLUTO | Pathology-Universal Transformer | Universal pathology Transformer model. | [arXiv](https://arxiv.org/search/?query=PLUTO+pathology+universal+transformer) |
| COBRA | Context-Aware Representation for Pathology | Context-aware pathology representation learning. | [arXiv](https://arxiv.org/search/?query=COBRA+context+aware+pathology+representation) |
| THREADS | Tissue Histopathology Representation with Efficient and Dense Self-Supervision | Efficient and dense self-supervised tissue histopathology representation learning. | [arXiv](https://arxiv.org/search/?query=THREADS+tissue+histopathology+dense+self-supervision) |
| MADELEINE | Multimodal ADaptive LEarning with INtegrated Embeddings | Multimodal adaptive pathology learning with integrated embeddings. | [arXiv](https://arxiv.org/abs/2405.15836) |
| Lunit-DINO | Benchmarking Self-Supervised Learning on Diverse Pathology Datasets | Lunit's DINOv2-based large-scale pathology pretraining. | [arXiv](https://arxiv.org/abs/2401.08527) |
| QuiltNet | Quilt-1M: One Million Image-Text Pairs for Histopathology | Vision-language model pretrained on 1M+ pathology image-text pairs. | [NeurIPS 2023](https://arxiv.org/abs/2306.11207) |
| Quilt-LLaVA | Visual Instruction Tuning for Histopathology | Pathology visual instruction tuned multimodal model. | [arXiv](https://arxiv.org/abs/2312.04746) |
| PathGen | PathGen-1.6M: 1.6 Million Pathology Image-text Pairs Generation | 1.6M pathology image-text pairs generation and pretraining. | [arXiv](https://arxiv.org/abs/2407.00203) |
| Path Foundation | Developing and Validating a Foundation Model for Pathology | Google-developed pathology foundation model. | [Nature](https://doi.org/10.1038/s41586-024-07894-3) |
| CONCH 1.5 | Task-Agnostic Vision-Language Foundation Model for Pathology | Upgraded CONCH with enhanced vision-language alignment. | [arXiv](https://arxiv.org/abs/2501.07581) |
| H-optimus-1 | H-optimus-1: Advanced Pathology Foundation Model | Upgraded H-optimus-0 with larger-scale training by Bioptimus. | [Bioptimus](https://arxiv.org/search/?query=H-optimus-1+Bioptimus+pathology) |
| GigaSSL | GigaPath-like Self-Supervised Learning for Pathology | Large-scale self-supervised learning method for pathology. | [arXiv](https://arxiv.org/search/?query=GigaSSL+pathology+self-supervised) |
| MUPAD | MUPAD: A Generative Foundation Model for Multimodal Histopathology | Multimodal histopathology generative foundation model integrating histology images, RNA molecular profiles, and clinical text. | [arXiv](https://arxiv.org/abs/2604.03635) |
| VISTA-PATH | VISTA-PATH: An interactive foundation model for pathology image segmentation and quantitative analysis | Interactive pathology image segmentation and quantitative analysis foundation model enhancing clinical relevance and accuracy. | [arXiv](https://arxiv.org/abs/2601.16451) |
| CARE | CARE: A Molecular-Guided Foundation Model with Adaptive Region Modeling for WSI Analysis | Molecular-guided adaptive region modeling foundation model for whole-slide image analysis. | [arXiv](https://arxiv.org/abs/2602.21637) |
| BRIGHT | BRIGHT: A Collaborative Generalist-Specialist Foundation Model for Breast Pathology | Collaborative generalist-specialist foundation model for breast pathology. | [arXiv](https://arxiv.org/abs/2603.03030) |
| GenBio-PathFM | GenBio-PathFM: A State-of-the-Art Foundation Model for Histopathology | 1.1B-parameter state-of-the-art histopathology foundation model fully trained on public data. | [bioRxiv Preprint](https://doi.org/10.1101/2026.03.17.712534) |
| Atlas 2 | State-of-the-art pathology FM trained on 5.5M WSIs | Pathology foundation model trained on 5.5M whole-slide images by Aignostics/Mayo. | [arXiv](https://arxiv.org/abs/2601.05148) |
| LongViT | LongViT: Long-Context Vision Transformer for Pathology | Long-context vision Transformer directly processing ultra-large pathology whole-slide images. | [arXiv](https://arxiv.org/abs/2403.14576) |
| Pixel-Mamba | Pixel-Mamba: Efficient Mamba-Based Foundation Model for Computational Pathology | Efficient Mamba architecture-based computational pathology foundation model with pixel-level processing. | [arXiv](https://arxiv.org/abs/2502.08058) |
| Virchow 2G | Virchow 2G: Scaling Self-Supervised Models to 1.9B Parameters for Pathology | ViT-G architecture 1.9B-parameter pathology foundation model trained on 3.1M WSIs (largest version in Virchow2 series). | [arXiv](https://arxiv.org/abs/2408.00738) |
| UNI 2-g-preview | UNI 2-g-preview: ViT-G Version of Universal Foundation Model for Computational Pathology | ViT-G large-scale version preview of UNI2, further expanding computational pathology foundation model parameter scale. | [arXiv](https://arxiv.org/abs/2501.07581) |
| Campanella DINO | Campanella et al. (DINO): Self-Supervised ViT-S for Digital Pathology | ViT-S architecture pathology foundation model with DINOv1 self-supervised training on 420K WSIs. | [arXiv](https://arxiv.org/abs/2310.07033) |
| Campanella MAE | Campanella et al. (MAE): Masked Autoencoder ViT-L for Digital Pathology | ViT-L architecture pathology foundation model with MAE self-supervised training on 420K WSIs. | [arXiv](https://arxiv.org/abs/2310.07033) |
| SP22M | SP22M: Mount Sinai Computational Pathology Foundation Model (22M params) | Mount Sinai 22M-parameter computational pathology foundation model. | [arXiv](https://arxiv.org/search/?query=Mount+Sinai+computational+pathology+foundation) |
| SP85M | SP85M: Mount Sinai Computational Pathology Foundation Model (85M params) | Mount Sinai 85M-parameter computational pathology foundation model. | [arXiv](https://arxiv.org/search/?query=Mount+Sinai+computational+pathology+foundation) |

---
<a id="medicine-section-04"></a>
### Endoscopy & Surgery

*Foundation models for endoscopic video analysis, surgical scene understanding, phase recognition, and robotic surgery planning.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Endo-FM | Foundation Model for Endoscopy Video Analysis | First endoscopy video foundation model, self-supervised pretrained on 33,000+ endoscopy videos for scene recognition, action detection, and polyp segmentation. | [MICCAI](https://arxiv.org/abs/2306.16741) |
| EndoDINO | A Foundation Model for GI Endoscopy | DINOv2-based gastrointestinal endoscopy foundation model pretrained on 1.75M+ images for GI disease classification and detection. | [arXiv](https://arxiv.org/abs/2501.05488) |
| EndoMamba | Efficient Foundation Model for Endoscopic Videos | Mamba-architecture efficient endoscopy video foundation model for temporal modeling in surgical video understanding. | [MICCAI](https://arxiv.org/abs/2502.19090) |
| SurgVISTA | Large-scale Self-supervised Video Foundation Model for Intelligent Surgery | Large-scale self-supervised surgical video foundation model trained on 3,650 videos / 3.55M frames, jointly learning spatiotemporal representations. | [npj Digital Medicine](https://arxiv.org/abs/2506.02692) |
| SurgVLP | Learning Multi-modal Representations by Watching Hundreds of Surgical Video Lectures | Surgical vision-language pretraining framework learning joint visual and linguistic representations from surgical video lectures. | [MedIA](https://arxiv.org/abs/2307.15220) |
| SurgLLM | A Versatile Large Multimodal Model for Surgical Video Understanding | Large multimodal model for surgical video understanding, integrating vision and language for comprehensive surgical scene analysis. | [arXiv](https://arxiv.org/abs/2509.00357) |
| SurgFM / Surg-3M | A Dataset and Foundation Model for Perception in Surgical Settings | 4,000+ surgical video dataset and foundation model for perception in diverse surgical settings. | [arXiv](https://arxiv.org/abs/2503.19740) |
| LEMON | A Large Endoscopic MONocular Dataset and Foundation Model | Large-scale endoscopic monocular dataset and foundation model for surgical perception including depth estimation and surface reconstruction. | [CVPR](https://arxiv.org/abs/2503.19740) |
| GSViT | General Surgery Vision Transformer: A Video Pre-trained Foundation Model for General Surgery | Video-pretrained vision Transformer foundation model for general surgery, advancing surgical video understanding through large-scale pretraining. | [arXiv](https://arxiv.org/abs/2403.05949) |
| HecVL | Hierarchical Video-Language Pretraining for Zero-shot Surgical Phase Recognition | Hierarchical video-language pretraining approach enabling zero-shot surgical phase recognition through three-level text supervision. | [MICCAI](https://arxiv.org/abs/2405.10075) |
| PeskaVLP | Procedure-Aware Surgical Video-language Pretraining with Hierarchical Knowledge Augmentation | Procedure-aware surgical video-language pretraining framework augmented with hierarchical surgical knowledge for improved video understanding. | [NeurIPS 2024](https://arxiv.org/abs/2410.00263) |
| SurgiSAM 2 | A Fine-tuned Foundational Model SurgiSAM2 for Surgical Video Anatomy Segmentation | Fine-tuned SAM2 model for surgical video anatomy segmentation and detection across multiple surgical datasets. | [Scientific Reports](https://doi.org/10.1038/s41598-025-11759-4) |
| ZEN | ZEN: A Generalizable Foundation Model for Intraoperative Understanding Across Surgical Procedures | Generalizable foundation model for real-time intraoperative understanding, supporting cross-procedure surgical video analysis. | [arXiv](https://arxiv.org/abs/2602.13633) |
| SurgMotion | SurgMotion: A Video-Native Foundation Model for Universal Understanding of Surgical Videos | Video-native surgical foundation model that learns directly from video rather than frame-level features for universal surgical video understanding. | [arXiv](https://arxiv.org/abs/2602.05638) |
| Surg-R1 | Surg-R1: A Hierarchical Reasoning Foundation Model for Scalable and Interpretable Surgical Decision Support | Hierarchical reasoning surgical foundation model with three-level reasoning architecture, validated across multiple clinical centers. | [arXiv](https://arxiv.org/abs/2603.12430) |
| Cosmos-H-Surgical | Learning Surgical Robot Policies from Videos via World Modeling | NVIDIA surgical robotics physical AI foundation model based on Cosmos world model architecture for surgical scene understanding and robot operation planning. | [NVIDIA Research](https://arxiv.org/abs/2512.23162) |
| SurgRec | Scaling Video Pretraining for Surgical Foundation Models | Large-scale self-supervised surgical video pretraining framework supporting multiple surgical visual understanding tasks. | [arXiv](https://arxiv.org/abs/2603.29966) |

---

<a id="medicine-section-05"></a>
### Ultrasound

*Foundation models for ultrasound imaging across organs including cardiac, fetal, and general abdominal ultrasound.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| USFM | A Universal Ultrasound Foundation Model Generalized to Tasks and Organs | Universal ultrasound foundation model generalizing across multiple organs and tasks with label-efficient learning. | [MedIA](https://arxiv.org/abs/2401.00153) |
| UltraFedFM | From Pretraining to Privacy: Federated Ultrasound Foundation Model with Self-Supervised Learning | Federated learning ultrasound foundation model trained across 16 institutions on 1M+ images, preserving data privacy. | [npj Digital Medicine](https://doi.org/10.1038/s41746-025-02085-0) |
| UltraDINO | General Methods Make Great Domain-Specific Foundation Models | DINOv2-based fetal ultrasound foundation model pretrained on 2M fetal ultrasound images for domain-specific tasks. | [MICCAI](https://arxiv.org/abs/2506.19552) |
| EchoCare | Fully Open Foundation Model for Ultrasound | Fully open ultrasound foundation model pretrained on 4.5M images spanning multiple organs and clinical scenarios. | [arXiv](https://arxiv.org/abs/2509.11752) |
| OpenUS | Open-Source Foundation Model for Ultrasound | Fully open-source ultrasound foundation model pretrained on 308K+ images for broad ultrasound analysis. | [arXiv](https://arxiv.org/abs/2511.11510) |
| EchoFM | Foundation Model for Generalizable Echocardiogram Analysis | Self-supervised echocardiography video foundation model pretrained on 20M+ images for generalizable cardiac analysis. | [arXiv](https://arxiv.org/abs/2410.23413) |
| EchoApex | A General-Purpose Vision Foundation Model for Echocardiography | General-purpose vision foundation model for echocardiography pretrained on 20M+ echo images with self-supervised learning. | [arXiv](https://arxiv.org/abs/2410.11092) |
| EchoCLIP | Vision–Language Foundation Model for Echocardiogram Interpretation | Vision-language foundation model for echocardiography trained on 1M+ echo video–report pairs via contrastive learning. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02959-y) |
| EchoPrime | Comprehensive Echocardiogram Evaluation with View Classification and AI-Enabled Measurements | Largest echocardiography AI model trained on 12M video–report pairs, supporting comprehensive echo evaluation and measurements. | [Nature](https://doi.org/10.1038/s41586-025-09850-x) |
| FetalCLIP | Visual-Language Foundation Model for Fetal Ultrasound | Vision-language foundation model for fetal ultrasound, enabling zero-shot and few-shot classification of fetal anatomy and pathology. | [arXiv](https://arxiv.org/abs/2502.14807) |
| UltraSam | Foundation Model for Ultrasound Segmentation | SAM-based ultrasound segmentation foundation model adapted for universal ultrasound image segmentation. | [arXiv](https://arxiv.org/abs/2411.16222) |
| Sonomate | A Visually Grounded Language Model for Fetal Ultrasound | Fetal ultrasound vision-language model integrating ultrasound imaging and clinical text for obstetric clinical decision support. | [Nature](https://doi.org/10.1038/s41551-025-01578-3) |

---

<a id="medicine-section-06"></a>
### ECG & Physiological Signals

*Foundation models for electrocardiogram (ECG), electroencephalogram (EEG), electromyography (EMG), and other biosignal analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ECG-FM | Open Electrocardiogram Foundation Model | Open ECG foundation model pretrained on 1.5M ECGs for cardiac diagnosis and health profiling. | [npj Digital Medicine](https://arxiv.org/abs/2408.05178) |
| ECGFounder | An Electrocardiogram Foundation Model Built on over 10 Million Recordings | ECG foundation model trained on 10.7M ECGs covering 150 diagnostic categories for comprehensive cardiac analysis. | [NEJM AI](https://arxiv.org/abs/2410.04133) |
| AnyECG | Evolved ECG Foundation Model for Health Profiling | Comprehensive health profiling ECG foundation model trained on 13.3M ECGs across diverse populations. | [arXiv](https://arxiv.org/abs/2601.10748) |
| MIRA | Medical Time Series Foundation Model | Microsoft medical time-series foundation model pretrained on 454B tokens covering ECG and other clinical time series. | [NeurIPS](https://arxiv.org/abs/2506.07584) |
| REVE | A Foundation Model for EEG | EEG foundation model pretrained on 60,000 hours of recordings from 25,000 subjects for brain-signal understanding. | [NeurIPS](https://arxiv.org/abs/2510.21585) |
| EEGPT | Unleashing the Potential of EEG Generalist Foundation Model by Autoregressive Pre-training | First generalist EEG foundation model using autoregressive pretraining for universal EEG understanding and decoding. | [arXiv](https://arxiv.org/abs/2410.19779) |
| FoME | A Foundation Model for EEG using Adaptive Temporal-Lateral Attention Scaling | EEG foundation model with adaptive temporal-lateral attention scaling for both scalp and intracranial EEG analysis. | [arXiv](https://arxiv.org/abs/2409.12454) |
| TinyMyo | Tiny Foundation Model for EMG | Lightweight EMG foundation model designed for edge deployment on wearable devices for muscle signal analysis. | [arXiv](https://arxiv.org/abs/2512.15729) |
| ECG-MoE | ECG-MoE: Mixture-of-Expert Electrocardiogram Foundation Model | Mixture-of-experts ECG foundation model that simultaneously captures periodicity and morphological features for enhanced cardiac diagnosis. | [arXiv](https://arxiv.org/abs/2603.04589) |
| LAMAE | LAMAE: Foundation Model for Cardiac Time Series via Masked Latent Attention | Cardiac time-series foundation model using ECG structural priors with latent attention masked autoencoder. | [arXiv](https://arxiv.org/abs/2603.26475) |
| ECG-Soup | ECG-Soup: Harnessing Multi-Layer Synergy for ECG Foundation Models | ECG foundation model leveraging multi-layer Transformer synergy for improved cardiac signal representation. | [arXiv](https://arxiv.org/abs/2509.00102) |
| BIOT | BIOT: Cross-data Biosignal Learning in the Wild | Cross-dataset biosignal Transformer that unifies EEG, ECG, EMG, and other physiological signal processing in a single framework. | [NeurIPS](https://arxiv.org/abs/2305.10351) |
| LaBraM | Large Brain Model for Learning Generic Representations with Tremendous EEG Data | Large-scale brain model pretrained on massive EEG data for universal EEG representation learning in brain–computer interfaces. | [ICLR](https://arxiv.org/abs/2405.18765) |
| CBraMod | CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding | Criss-cross Transformer brain foundation model for EEG decoding, separately modeling spatial and temporal dependencies. | [arXiv](https://arxiv.org/abs/2412.07236) |
| NeuroGPT | Neuro-GPT: Towards a Foundation Model for EEG | EEG foundation model combining an EEG encoder with a GPT-style architecture for brain signal understanding and generation. | [2024 IEEE International Symposium on Biomedical Imaging (ISBI)](https://arxiv.org/abs/2311.03764) |
| BrainWave | BrainWave: A Brain Signal Foundation Model for Clinical Applications | Brain signal foundation model pretrained on 40,000+ hours of both invasive and non-invasive neural recordings for clinical applications. | [arXiv](https://arxiv.org/abs/2402.10251) |
| Brant-2 | Brant-2: Foundation Model for Brain Signals | Second-generation brain signal foundation model handling both EEG and intracranial EEG (iEEG/SEEG) for diverse neuroscience tasks. | [arXiv](https://arxiv.org/abs/2402.10251) |
| S-JEPA | S-JEPA: Towards Seamless Cross-Dataset Transfer Through Dynamic Spatial Attention | Self-supervised joint embedding predictive architecture for cross-dataset EEG transfer learning with dynamic spatial attention. | [arXiv](https://arxiv.org/abs/2403.11772) |
| EEG2Rep | EEG2Rep: Enhancing Self-supervised EEG Representation Through Informative Masking | Self-supervised EEG representation learning method using informative masked inputs to handle low-SNR and non-stationary brain signals. | [arXiv](https://arxiv.org/abs/2402.17772) |
| MaEEG | MAEEG: Masked Auto-encoder for EEG Representation Learning | Masked autoencoder for EEG data that reconstructs masked EEG features for self-supervised brain signal representation learning. | [arXiv](https://arxiv.org/abs/2211.02625) |
| OpenECG | OpenECG: Benchmarking ECG Foundation Models with Public 1.2 Million Records | Large-scale benchmark of ECG foundation models with 1.2M public 12-lead ECG recordings from nine centers. | [arXiv](https://arxiv.org/abs/2503.00711) |

---

<a id="medicine-section-07"></a>
### Dental Imaging

*Foundation models for dental radiography analysis including panoramic X-rays, caries detection, and oral disease diagnosis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DentVFM | Vision Foundation Models for Oral Radiology | Vision foundation model for oral and maxillofacial radiology supporting dental disease detection and classification. | [arXiv](https://arxiv.org/abs/2510.14532) |
| MMOral | Multimodal Benchmark for Dental X-ray | Multimodal benchmark for panoramic dental X-ray analysis with vision-language evaluation. | [NeurIPS](https://arxiv.org/abs/2509.09254) |
| DentVLM | Multimodal Vision-Language Model for Dental Diagnosis | Multimodal vision-language model for dental diagnosis integrating dental imaging with clinical text. | [arXiv](https://arxiv.org/abs/2509.23344) |
| DVCTNet | Adapting Foundation Model for Dental Caries Detection | Dual-view foundation model adapted for dental caries detection from radiographic images. | [arXiv](https://arxiv.org/abs/2508.20813) |
| OralGPT-Omni | Versatile Dental Multimodal Large Language Model | Versatile dental multimodal large language model supporting comprehensive oral disease analysis and clinical dialogue. | [arXiv](https://arxiv.org/abs/2511.22055) |

---

<a id="medicine-section-08"></a>
### Ophthalmology

*Foundation models for retinal imaging, optical coherence tomography (OCT), fundus photography, and ophthalmic surgery video analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OCTCube | A 3D Foundation Model for Optical Coherence Tomography | 3D OCT foundation model for volumetric retinal image analysis and ophthalmic disease detection. | [arXiv](https://arxiv.org/abs/2408.11227) |
| MIRAGE | Multimodal Foundation Model and Benchmark for Comprehensive Retinal OCT Image Analysis | Multimodal foundation model for comprehensive retinal OCT and SLO image analysis with large-scale benchmark. | [npj Digital Medicine](https://arxiv.org/abs/2506.08900) |
| VisionFM | Development and Validation of a Multimodal Multitask Vision Foundation Model for Generalist Ophthalmic AI | Multimodal ophthalmic vision foundation model pretrained on 3.4M images across multiple eye imaging modalities for generalist ophthalmic AI. | [NEJM AI](https://doi.org/10.1056/AIoa2300221) |
| EyeFound | Multimodal Generalist Foundation Model for Ophthalmic Imaging | Multimodal generalist foundation model pretrained on 2.78M retinal images across 11 modalities for comprehensive ophthalmic imaging analysis. | [arXiv](https://arxiv.org/abs/2405.11338) |
| FLAIR | A Foundation LAnguage-Image Model of the Retina | Vision-language foundation model for retinal fundus image understanding, aligning visual and textual expert knowledge. | [MedIA](https://arxiv.org/abs/2308.07898) |
| RET-CLIP | A Retinal Image Foundation Model Pre-trained with Clinical Diagnostic Reports | CLIP-style retinal image foundation model pretrained with clinical diagnostic reports for ophthalmic disease classification. | [MICCAI](https://arxiv.org/abs/2405.14137) |
| VOLMO | VOLMO: Versatile and Open Large Models for Ophthalmology | Open large-scale versatile ophthalmology foundation model with three-stage training covering multiple ophthalmic tasks. | [arXiv](https://arxiv.org/abs/2603.23953) |
| Dual-IFM | Dual-IFM: Towards Interpretable Foundation Models for Retinal Fundus Images | Interpretable retinal fundus image foundation model with local-to-global interpretability for clinical transparency. | [arXiv](https://arxiv.org/abs/2603.18846) |
| OCTCube-M | OCTCube-M: A 3D Multimodal Optical Coherence Tomography Foundation Model for Ophthalmic Disease Diagnosis | Upgraded OCTCube integrating multimodal OCT data for comprehensive 3D ophthalmic disease diagnosis. | [arXiv](https://arxiv.org/abs/2408.11227) |
| EyeFM | An Eyecare Foundation Model for Clinical Assistance | Universal eyecare foundation model published in Nature Medicine, pretrained on large-scale multimodal ophthalmic data for AI-assisted clinical care. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03900-7) |
| OVFM | An Ophthalmic Video Foundation Model for Surgical Recognition and Navigation | Self-supervised ophthalmic video Transformer for real-time surgical recognition and navigation during microscopic procedures. | [Nature BME](https://doi.org/10.1038/s41551-026-01622-w) |

---
<a id="medicine-section-09"></a>
### Medical NLP

*Foundation models for biomedical and clinical natural language processing, including medical LLMs, clinical text mining, and biomedical language understanding.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Med-PaLM | Large Language Models Encode Clinical Knowledge | Google's first medical LLM, achieving expert-level performance on medical question answering benchmarks by encoding clinical knowledge in a large language model. | [Nature](https://arxiv.org/abs/2212.13138) |
| Med-PaLM 2 | Towards Expert-Level Medical Question Answering with Large Language Models | Second-generation Google medical LLM reaching expert-level medical QA performance, significantly improving over Med-PaLM on multiple clinical benchmarks. | [Nature Medicine](https://arxiv.org/abs/2305.09617) |
| Med-Gemini | Advancing Multimodal Medical Capabilities of Gemini | Google multimodal medical AI extending Gemini's capabilities to clinical reasoning across text, images, and genomics. | [arXiv](https://arxiv.org/abs/2405.03162) |
| MedGemma | Open Models for Health AI | Google's open-source collection of Gemma variants tailored for medical text and image understanding, offering multimodal and text-only pretrained formats. | [Google](https://developers.google.com/health-ai-developer-foundations/medgemma) |
| PubMedBERT | Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing | BERT model pretrained from scratch exclusively on PubMed abstracts and full texts, demonstrating that domain-specific pretraining outperforms mixed-domain approaches for biomedical NLP. | [ACM Transactions on Computing for Healthcare](https://arxiv.org/abs/2007.15779) |
| GatorTron | A Large Clinical Language Model to Unlock Patient Information from Unstructured Electronic Health Records | Large-scale clinical language model (up to 8.9B parameters) pretrained on over 90 billion words of clinical text, designed to unlock patient information from unstructured EHRs. | [npj Digital Medicine](https://arxiv.org/abs/2203.03540) |
| BioGPT | Generative Pre-trained Transformer for Biomedical Text Generation and Mining | Domain-specific generative Transformer pretrained on large-scale biomedical literature for both text generation and mining tasks in biomedicine. | [Briefings in Bioinformatics](https://arxiv.org/abs/2210.10341) |
| PMC-LLaMA | Building Open-Source Language Models for Medicine | Open-source medical LLM fine-tuned on PubMed Central papers, enabling accessible medical language understanding and generation. | [JAMIA](https://arxiv.org/abs/2304.14454) |
| MedAlpaca | An Open-Source Collection of Medical Conversational AI Models and Training Data | Open-source collection of medical conversational AI models fine-tuned for clinical dialogue and medical question answering. | [arXiv](https://arxiv.org/abs/2304.08247) |
| Meditron | Open Medical Foundation LLMs Adapted from Llama 2 | Medical foundation LLM adapted from LLaMA 2, fine-tuned on 48B tokens of curated medical literature from PubMed, clinical guidelines, and medical papers. | [arXiv](https://arxiv.org/abs/2311.16079) |
| ClinicalBERT | ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission | BERT model adapted for clinical notes, pretrained on clinical text to learn patient representations for hospital readmission prediction and other clinical tasks. | [CHIL](https://arxiv.org/abs/1904.05342) |
| HuatuoGPT | HuatuoGPT, Towards Taming Language Model to Be a Doctor | Chinese medical LLM combining ChatGPT-distilled data and real physician data with supervised fine-tuning and RLHF for medical consultation. | [Findings of the Association for Computational Linguistics: EMNLP 2023](https://arxiv.org/abs/2305.15075) |
| HuatuoGPT-o1 | HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs | Medical complex reasoning LLM that uses verifier-guided search and reinforcement learning to enhance medical diagnostic reasoning capabilities. | [ACL 2025 Findings](https://arxiv.org/abs/2412.18925) |
| ChatDoctor | ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model Meta AI Using Medical Domain Knowledge | Medical dialogue model fine-tuned on LLaMA using 100K anonymized patient-doctor conversations for clinical consultation. | [arXiv / PMC](https://arxiv.org/abs/2303.14070) |
| DoctorGLM | DoctorGLM: Fine-tuning Your Chinese Doctor is Not a Herculean Task | Chinese medical LLM based on ChatGLM-6B, fine-tuned with Chinese medical dialogue data for accessible Chinese medical consultation. | [arXiv](https://arxiv.org/abs/2304.01097) |
| BioMistral | BioMistral: A Collection of Open-Source Pretrained Large Language Models for Medical Domain | Open-source biomedical LLM based on Mistral, continually pretrained on PubMed Central data for improved performance on medical benchmarks. | [ACL](https://arxiv.org/abs/2402.10373) |
| Me-LLaMA | Me-LLaMA: Foundation Large Language Models for Medical Applications | Medical foundation LLM (13B/70B) based on LLaMA 2, continually pretrained on large-scale biomedical and clinical data with instruction fine-tuning for medical applications. | [npj Digital Medicine](https://arxiv.org/abs/2402.12749) |
| OpenBioLLM | OpenBioLLM-70B: Advancing Open-Source Large Language Models in Medical Domain | 70B-parameter open-source biomedical LLM based on Llama 3, outperforming GPT-4 and other closed-source models on multiple medical benchmarks. | [Open Release](https://huggingface.co/aaditya/Llama3-OpenBioLLM-70B) |
| MMedLM | Towards Building Multilingual Language Model for Medicine | Multilingual medical language model trained on the MMedC multilingual medical corpus, supporting cross-language medical question answering across multiple languages. | [Nature Communications](https://arxiv.org/abs/2402.13963) |
| RadGraph-XL | RadGraph-XL: A Large-Scale Expert-Annotated Dataset for Entity and Relation Extraction from Radiology Reports | Large-scale radiology report entity and relation extraction dataset with 2,300 reports and 410,000+ annotated entities across four imaging modalities. | [ACL 2024](https://aclanthology.org/2024.findings-acl.765/) |
| RadEx | RadEx: A Framework for Structured Information Extraction from Radiology Reports | End-to-end LLM-based framework for structured information extraction from radiology reports, enabling systematic clinical data mining. | [arXiv](https://arxiv.org/abs/2406.15465) |
| ClinicalMamba | ClinicalMamba: A Generative Clinical Language Model on Longitudinal Clinical Notes | Generative clinical language model based on Mamba architecture, designed for processing longitudinal clinical notes with efficient sequence modeling. | [Proceedings of the 6th Clinical Natural Language Processing Workshop](https://arxiv.org/abs/2403.05795) |
| ChiMed-GPT | ChiMed-GPT: A Chinese Medical Large Language Model with Full Training Regime and Better Alignment to Human Preferences | Full-training-regime Chinese medical LLM combining pre-training, supervised fine-tuning, and RLHF for aligned Chinese medical language understanding. | [Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)](https://arxiv.org/abs/2311.06025) |
| BioBART | BioBART: Pretraining and Evaluation of a Biomedical Generative Language Model | Biomedical generative language model based on BART architecture, pretrained on PubMed abstracts for biomedical text generation and summarization. | [Proceedings of the 21st Workshop on Biomedical Language Processing](https://arxiv.org/abs/2204.03905) |
| ClinicalT5 | ClinicalT5: A Generative Language Model for Clinical Text | Clinical text generative language model based on T5 architecture, pretrained on clinical notes to bridge the gap between general-domain and clinical-domain NLP. | [EMNLP 2023 Findings](https://aclanthology.org/2022.findings-emnlp.398) |
| KeBioLM | Improving Biomedical Pretrained Language Models with Knowledge | Knowledge-enhanced biomedical pretrained language model integrating UMLS knowledge graph entities to improve biomedical text understanding. | [Proceedings of the 20th Workshop on Biomedical Language Processing](https://arxiv.org/abs/2104.10344) |
| BioELMo | Probing Biomedical Embeddings from Language Models | Biomedical embedding model based on ELMo, pretrained on PubMed text to produce contextualized biomedical word representations for downstream tasks. | [Proceedings of the 3rd Workshop on Evaluating Vector Space Representations for](https://arxiv.org/abs/1904.02181) |
| RadBERT | RadBERT: Adapting Transformer-based Language Models to Radiology | Radiology-domain adapted BERT language model for improved understanding of radiological text and report processing. | [Radiology: Artificial Intelligence](https://arxiv.org/abs/2201.06125) |
| BioBERT | BioBERT: A Pre-trained Biomedical Language Representation Model for Biomedical Text Mining | First biomedical domain BERT pretrained on PubMed abstracts and PMC full-text articles, widely used as a foundation for biomedical text mining tasks. | [Bioinformatics](https://arxiv.org/abs/1901.08746) |
| SciBERT | SciBERT: A Pretrained Language Model for Scientific Text | BERT model pretrained on 1.14M scientific papers (primarily biomedical), serving as a foundation for scientific and biomedical NLP tasks. | [EMNLP 2019](https://arxiv.org/abs/1903.10676) |
| BioLinkBERT | LinkBERT: Pretraining Language Models with Document Links | BERT model pretrained with document link information from biomedical literature, enhancing cross-document knowledge capture for biomedical NLP. | [ACL 2022](https://arxiv.org/abs/2203.15827) |
| MetaReact | MetaReact: Reaction-Aware Transformer for Drug Metabolism Prediction | Reaction-aware Transformer for predicting drug metabolism pathways, integrating chemical reaction knowledge into drug metabolism modeling. | [Paper](https://doi.org/10.1101/2026.03.14.711529) |

---
<a id="medicine-section-10"></a>
### Medical Multimodal

*Foundation models integrating multiple medical data modalities (vision, language, speech) for cross-modal biomedical understanding, diagnosis, and generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LLaVA-Med | LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day | Microsoft's cost-efficient multimodal conversational AI for biomedicine, trained on biomedical image-text data using a curriculum learning approach. | [NeurIPS 2023](https://arxiv.org/abs/2306.00890) |
| BiomedGPT | A Generalist Vision–Language Foundation Model for Diverse Biomedical Tasks | Open-source, lightweight generalist vision-language foundation model capable of handling 16 diverse biomedical tasks across imaging and text. | [Nature Medicine](https://doi.org/10.1038/s41591-024-03185-2) |
| XrayGPT | XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models | Conversational medical vision-language model that integrates MedClip and Vicuna for chest X-ray analysis and report summarization. | [arXiv](https://arxiv.org/abs/2306.07971) |
| ChatCAD | ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models | Framework integrating LLMs with medical image CAD systems for interactive, LLM-enhanced computer-aided diagnosis. | [arXiv](https://arxiv.org/abs/2302.07257) |
| Med-Flamingo | Med-Flamingo: a Multimodal Medical Few-shot Learner | Multimodal medical few-shot learner based on OpenFlamingo-9B, continued pretraining on paired medical image-text data for few-shot medical visual QA. | [ML4H](https://arxiv.org/abs/2307.15189) |
| PVLens | PVLens: Enhancing Pharmacovigilance Through Automated Label Extraction | GSK-developed automated pipeline for extracting adverse drug reactions from FDA drug labels and mapping them to MedDRA terminology. | [arXiv / PMC](https://arxiv.org/abs/2503.20639) |
| MedASR | MedASR: A Conformer-Based Medical Speech Recognition Model | Google Health's open-weight Conformer-based medical speech-to-text model (105M parameters) trained on 5,000+ hours of de-identified medical speech data. | [Google HADF](https://developers.google.com/health-ai-developer-foundations/medasr/get-started) |
| MedGemma 1.5 | MedGemma 1.5 Technical Report | Google's latest multimodal medical foundation model with significantly enhanced capabilities for high-dimensional medical imaging (CT, MRI, histopathology WSI). | [arXiv](https://arxiv.org/abs/2604.05081) |
| MedMO | MedMO: Grounding and Understanding Multimodal Large Language Model for Medical Images | Medical multimodal LLM trained on 26M+ diverse medical samples, supporting both grounding and understanding of medical images. | [arXiv](https://arxiv.org/abs/2602.06965) |
| UNIMEDVL | UniMedVL: Unifying Medical Multimodal Understanding and Generation Through Observation-Knowledge-Analysis | Unified medical multimodal framework that simultaneously handles image understanding and generation within a single architecture for clinical diagnosis. | [OpenReview](https://arxiv.org/abs/2510.15710) |
| MeDiM | MeDiM: Discrete Diffusion Models with MLLMs for Unified Medical Multimodal Generation | First medical discrete diffusion model that unifies multimodal medical generation (image-text bidirectional translation) without modality-specific components. | [OpenReview](https://openreview.net/forum?id=E6jDNtfj6X) |
| Lingshu | Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning | Generalist multimodal medical LLM supporting unified understanding and reasoning across diverse medical data modalities. | [arXiv](https://arxiv.org/abs/2506.07044) |
| CLEAR | CLEAR: An Auditable Foundation Model for Radiology Grounded in Clinical Concepts | Auditable radiology foundation model trained on ~870K chest X-ray image-report pairs, grounding predictions in explicit clinical concepts for transparency. | [medRxiv](https://www.medrxiv.org/content/10.64898/2026.01.15.26344222v1) |
| GreenRFM | GreenRFM: Toward a Resource-Efficient Radiology Foundation Model | Resource-efficient radiology foundation model that achieves state-of-the-art performance with dramatically reduced compute and memory requirements. | [arXiv](https://arxiv.org/abs/2603.06467) |
| Curia-2 | Curia-2: Scaling Self-Supervised Learning for Radiology Foundation Models | Raidium's advanced self-supervised radiology foundation model, scaling CT/MRI representation learning beyond its predecessor Curia. | [arXiv](https://arxiv.org/abs/2604.01987) |
| MediVLM | MediVLM: A Vision Language Model for Radiology Report Generation | Vision-language model combining a pretrained object detector and image encoder with an LLM decoder for automated radiology report generation. | [EMNLP 2025](https://aclanthology.org/2025.findings-emnlp.544/) |
| InfiMed-Foundation | InfiMed-Foundation: Pioneering Advanced Multimodal Medical Foundation Models | Compute-efficient medical multimodal LLMs (1.7B and 4B) delivering state-of-the-art medical performance with reduced computational overhead. | [arXiv](https://arxiv.org/abs/2509.22261) |

---

<a id="medicine-section-11"></a>
### Electronic Health Records

*Foundation models for structured and unstructured electronic health record (EHR) data, supporting disease prediction, patient timeline modeling, and clinical event extraction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BEHRT | BEHRT: Transformer for Electronic Health Records | BERT-based deep neural sequence model trained on ~1.6M patient EHRs for predicting future health outcomes from longitudinal medical codes. | [Scientific Reports](https://doi.org/10.1038/s41598-020-62922-y) |
| Med-BERT | Med-BERT: Pretrained Contextualized Embeddings on Large-Scale Structured Electronic Health Records for Disease Prediction | BERT-style model pretrained on large-scale structured EHR data for improved disease prediction, especially with limited labeled data. | [JAMIA](https://doi.org/10.1038/s41746-021-00455-y) |
| CLMBR | Modeling EHR with Self-Supervised Learning | Autoregressive clinical language model (141M parameters) pretrained on 2.57M de-identified EHRs from Stanford for clinical prediction tasks. | [NeurIPS](https://arxiv.org/abs/2307.02028) |
| CEHR-BERT | CEHR-BERT: Incorporating Temporal Information from Structured EHR Data to Improve Prediction Tasks | Temporal-enhanced BERT adaptation for structured EHR data that incorporates time intervals to improve clinical prediction tasks. | [ML4H 2021](https://proceedings.mlr.press/v158/pang21a.html) |
| EHRMamba | EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic Health Records | Mamba-architecture foundation model for EHR data, designed for generalizable and scalable clinical prediction across diverse healthcare settings. | [arXiv](https://arxiv.org/abs/2405.14567) |
| MOTOR | MOTOR: A Time-To-Event Foundation Model For Structured Medical Records | Self-supervised time-to-event foundation model for structured medical records that pretrains on timestamped clinical event sequences. | [NeurIPS](https://arxiv.org/abs/2301.03150) |
| CEHR-GPT | CEHR-GPT: Generating Electronic Health Records with Chronological Patient Timelines | GPT-based model for generating synthetic EHR data as chronological patient timelines, supporting privacy-preserving data augmentation. | [arXiv](https://arxiv.org/abs/2402.04400) |
| Foresight | Foresight—A Generative Pretrained Transformer for Modelling of Patient Timelines Using Electronic Health Records | Generative pretrained transformer modeling patient timelines from EHRs for clinical event prediction and digital twin generation. | [Lancet Digital Health](https://doi.org/10.1016/S2589-7500(24)00025-6) |
| Panacea | Panacea: A Foundation Model for Clinical Trial Search, Summarization, Design and Recruitment | Foundation model for clinical trial tasks including search, summarization, design, and patient-trial matching. | [arXiv](https://arxiv.org/abs/2407.11007) |
| GENIE-EHR | GENIE: Generative Note Information Extraction Model for Structuring EHR Data | Unified end-to-end system using fine-tuned LLMs to convert unstructured clinical notes into standardized structured EHR formats. | [arXiv](https://arxiv.org/abs/2501.18435) |

---

<a id="medicine-section-12"></a>
### Nuclear Medicine

*Foundation models for PET/CT functional imaging, supporting whole-body metabolic analysis, tumor detection, organ segmentation, and report generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SDF-HOLO | A Generalist Foundation Model for Total-body PET/CT Enables Diagnostic Reporting and System-wide Metabolic Profiling | Multimodal foundation model trained on >10,000 patients' total-body PET/CT data with dual-stream architecture for diagnostic reporting and whole-body metabolic profiling. | [arXiv](https://arxiv.org/abs/2601.12820) |
| FratMAE | Developing a PET/CT Foundation Model for Cross-Modal Anatomical and Functional Imaging | Dual-ViT-encoder PET/CT cross-modal foundation model for joint functional-anatomical analysis in oncology applications. | [arXiv](https://arxiv.org/abs/2503.02824) |
| SegAnyPET | Developing Foundation Models for Universal Segmentation from 3D Whole-Body Positron Emission Tomography | First universal PET image segmentation foundation model, trained on >11,000 PET scans with 600K annotations for organ and lesion segmentation. | [ICCV](https://arxiv.org/abs/2603.11627) |
| PET-F2I | PET-F2I: A Comprehensive Benchmark and Parameter-Efficient Fine-Tuning of LLMs for PET/CT Report Impression Generation | Large-scale benchmark of 41K real PET/CT reports evaluating 27 LLMs on PET/CT report impression generation with parameter-efficient fine-tuning. | [arXiv](https://arxiv.org/abs/2603.10560) |

---

<a id="medicine-section-13"></a>
### Mammography

*Foundation models for mammographic imaging analysis, supporting breast cancer screening, diagnosis, prognosis prediction, and report generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Mammo-CLIP | Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography | Vision-language foundation model pretrained on large-scale mammogram-report pairs to improve data efficiency and robustness in breast cancer detection. | [Lecture Notes in Computer Science](https://arxiv.org/abs/2405.12255) |
| MammoDINO | MammoDINO: Anatomically Aware Self-Supervision for Mammographic Images | Self-supervised foundation model based on DINOv2 trained on >1.4M mammographic images with anatomy-aware augmentation and cross-view learning. | [arXiv](https://arxiv.org/abs/2510.11883) |
| VersaMammo | A Versatile Foundation Model for AI-enabled Mammogram Interpretation | Versatile foundation model trained on >700K multi-institutional mammograms supporting multiple breast cancer detection and diagnostic tasks. | [arXiv](https://arxiv.org/abs/2509.20271) |
| Mammo-FM | Mammo-FM: Breast-specific Foundational Model for Integrated Mammographic Diagnosis, Prognosis, and Reporting | Breast-specific foundation model trained on >140K patients and 820K images, unifying mammographic diagnosis, prognosis prediction, and report generation. | [arXiv](https://arxiv.org/abs/2512.00198) |
| HOPPR EB Mammo | HOPPR EB 2D Mammography Foundation Model | ViT-based 2D mammography foundation model trained via self-supervised learning and expert distillation for diverse breast imaging downstream tasks. | [Industry Release](https://www.hoppr.ai/build/ai-foundry) |
| OMAFound | A Foundation Model for Breast and Lung Cancer Screening Using Non-contrast CT | Multi-cancer screening foundation model trained on 325K CT volumes from 151K+ patients for simultaneous breast and lung cancer detection from non-contrast CT. | [Nature Health](https://doi.org/10.1038/s44360-026-00055-8) |

---

<a id="medicine-section-14"></a>
### Musculoskeletal Imaging

*Foundation models for musculoskeletal X-ray and MRI analysis, supporting orthopedic disease diagnosis, joint pathology detection, and multi-anatomy assessment.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OrthoFoundation | A Multimodal Vision Foundation Model for Generalizable Knee Pathology | Multimodal orthopedic vision foundation model trained on 1.2M unlabeled knee X-ray and MRI images via self-supervised contrastive learning for generalizable knee pathology assessment. | [arXiv](https://arxiv.org/abs/2601.18250) |
| OrthoDiffusion | OrthoDiffusion: A Generalizable Multi-Task Diffusion Foundation Model for Musculoskeletal MRI Interpretation | Diffusion-based multi-task foundation model for musculoskeletal MRI trained on ~16,000 unlabeled knee MRIs, supporting segmentation and classification. | [arXiv](https://arxiv.org/abs/2602.20752) |
| XR-0 | Multi Anatomy X-Ray Foundation Model | Self-supervised multi-anatomy X-ray foundation model trained on 1.15M X-ray images spanning multiple anatomical regions including musculoskeletal structures. | [arXiv](https://arxiv.org/abs/2509.12146) |

---

<a id="medicine-section-15"></a>
### Wearable & Digital Health

*Foundation models for wearable sensor data (accelerometer, PPG, ECG, etc.), supporting health monitoring, activity recognition, and clinical prediction from continuous physiological signals.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LSM | Scaling Wearable Foundation Models | Google's large-scale multimodal wearable foundation model trained on >40M hours of per-minute data from 165K+ individuals for health prediction tasks. | [ICLR](https://arxiv.org/abs/2410.13638) |
| LSM-2 | LSM-2: Learning from Incomplete Wearable Sensor Data | Upgraded LSM using Adaptive and Inherited Masking (AIM) to learn directly from incomplete wearable sensor data without imputation. | [ICLR](https://arxiv.org/abs/2506.05321) |
| NormWear | Toward Foundation Model for Multivariate Wearable Sensing of Physiological Signals | First multi-modal wearable foundation model for physiological signals (PPG, ECG, EEG, GSR, IMU) using channel-aware attention mechanisms. | [ACM Transactions on Computing for Healthcare](https://arxiv.org/abs/2412.09758) |
| SensorLM | SensorLM: Learning the Language of Wearable Sensors | Sensor-language foundation model trained on ~60M hours of wearable data from 103K+ individuals, translating sensor signals into natural language descriptions. | [NeurIPS](https://arxiv.org/abs/2506.09108) |
| WAX-FM | Wearable Accelerometer Foundation Models for Health via Knowledge Distillation | Apple-developed wearable accelerometer foundation model using PPG-to-accelerometer knowledge distillation, trained on 20M minutes of unlabeled data. | [arXiv](https://arxiv.org/abs/2412.11276) |

---

<a id="medicine-section-16"></a>
### Radiation Therapy

*Foundation models and AI systems for automating radiation therapy planning, including target delineation, dose prediction, and treatment plan optimization.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AIRT | AI End-to-End Radiation Treatment Planning Under One Second | End-to-end deep learning framework generating deliverable prostate VMAT treatment plans from CT images in under one second. | [arXiv](https://arxiv.org/abs/2603.06338) |
| DOLA | Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent | Privacy-preserving LLM-based agent (built on LLaMA 3.1) for autonomous local radiotherapy plan optimization without cloud dependencies. | [arXiv](https://arxiv.org/abs/2503.17553) |
| GPT-RadPlan | Automated Radiotherapy Treatment Planning Guided by GPT-4Vision | Fully automated radiotherapy planning system leveraging GPT-4Vision's multimodal reasoning to simulate a human planner's clinical decision-making. | [Physics in Medicine &amp; Biology](https://arxiv.org/abs/2406.15609) |
| AIRTP | Automating High Quality RT Planning at Scale | Scalable automated pipeline for generating high-quality radiotherapy treatment plans, automating target delineation, dose prediction, and plan optimization. | [Nature Communications](https://arxiv.org/abs/2501.11803) |

---

<a id="medicine-section-17"></a>
### Microscopy

*Foundation models for non-pathological microscopy including fluorescence, electron, and single-molecule microscopy, supporting image restoration, enhancement, segmentation, and structural analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FluoResFM | A Foundation Model for Multi-task Cross-distribution Restoration of Fluorescence Microscopy Images | Multi-task fluorescence microscopy image restoration foundation model using text priors for denoising, deconvolution, and super-resolution across distributions. | [Nature Communications](https://doi.org/10.1038/s41467-026-70307-4) |
| FluoGen | FluoGen: An Open-Source Generative Foundation Model for Fluorescence Microscopy Image Enhancement | Open-source diffusion-based foundation model trained on 3.5M fluorescence images for microscopy image enhancement and analysis under data-scarce conditions. | [Research Square](https://doi.org/10.21203/rs.3.rs-8334792/v1) |
| MorphGen | MorphGen: Controllable and Morphologically Plausible Generative Cell-Imaging | CZI AI's diffusion-based generative model for controllable fluorescence microscopy cell imaging across multiple cell types and perturbation conditions. | [arXiv](https://arxiv.org/abs/2510.01298) |
| META-SiM | Foundation Model for Efficient Biological Discovery in Single-Molecule Time Traces | Transformer-based foundation model for single-molecule fluorescence microscopy, accelerating classification, counting, and kinetics analysis of time traces. | [Nature Methods](https://doi.org/10.1038/s41592-025-02839-4) |
| DF5T | A Foundation AI Model Enhances Electron Microscopy Image Analysis | Unsupervised electron microscopy foundation model supporting five tasks: denoising, deblurring, super-resolution, 2D inpainting, and 3D isotropic restoration. | [bioRxiv Preprint](https://doi.org/10.64898/2026.02.28.708664) |

---

<a id="medicine-section-18"></a>
### Sleep Medicine

*Foundation models for polysomnography (PSG) and sleep data analysis, supporting automated sleep staging, respiratory event detection, and sleep disorder diagnosis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SleepFM | SleepFM: A Multi-Modal Foundation Model for Sleep Medicine | Multimodal sleep foundation model pretrained on large-scale PSG data, integrating EEG, ECG, and respiratory signals for sleep staging and disease prediction. | [Nature Medicine](https://doi.org/10.1038/s41591-025-04133-4) |

---

<a id="medicine-section-19"></a>
### Veterinary Medicine

*Foundation models for veterinary medical imaging and clinical data analysis, supporting animal disease diagnosis and anatomical understanding.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| VET-DINO | VET-DINO: Learning Anatomical Understanding Through Multi-View Distillation in Veterinary Imaging | Self-supervised veterinary imaging foundation model using multi-view radiograph knowledge distillation for robust anatomical representation learning. | [arXiv](https://arxiv.org/abs/2505.15248) |

---

<a id="medicine-section-20"></a>
### Forensic Science

*Foundation models for forensic pathology and forensic identification, supporting cause-of-death determination and injury classification.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SongCi | Large-vocabulary Forensic Pathological Analyses via Prototypical Cross-modal Contrastive Learning | Vision-language foundation model for forensic pathology using prototypical cross-modal contrastive learning on gross findings and whole-slide images. | [Nature Communications](https://doi.org/10.1038/s41467-025-62060-x) |

## Mathematics & Scientific Reasoning

> [English](mathematics/mathematics_en.md) | [Chinese](mathematics/mathematics_zh.md)

### Table of Contents
- [Theorem Proving](#mathematics-section-01)
- [Scientific Multimodal Reasoning](#mathematics-section-02)
- [Mathematical Reasoning LLMs](#mathematics-section-03)

<a id="mathematics-section-01"></a>
### Theorem Proving
*Foundation models for formal mathematical reasoning, combining LLMs with proof assistants such as Lean for automated theorem proving and mathematical competition problem solving.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AlphaProof | Olympiad-Level Formal Mathematical Reasoning with AlphaProof | A formal mathematical reasoning system by DeepMind combining reinforcement learning with Lean proof assistant, solving 4/6 problems at the 2024 IMO to reach silver-medal level. | [Nature](https://doi.org/10.1038/s41586-025-09833-y) |
| AlphaGeometry | Solving Olympiad Geometry Without Human Demonstrations | A neuro-symbolic geometry theorem prover by DeepMind that solves Olympiad-level plane geometry problems without human demonstrations. | [Nature](https://doi.org/10.1038/s41586-023-06747-5) |
| AlphaGeometry 2 | Gold-Medalist Performance in Solving Olympiad Geometry with AlphaGeometry2 | An upgraded AlphaGeometry achieving 84% success rate on 25 years of IMO geometry problems, exceeding human gold-medalist average. | [arXiv](https://arxiv.org/abs/2502.03544) |
| Lean Copilot | Large Language Models as Copilots for Theorem Proving in Lean | A framework integrating LLMs into the Lean theorem prover for tactic suggestion, proof search, and premise selection. | [NeurIPS](https://arxiv.org/abs/2404.12534) |
| LeanDojo | LeanDojo: Theorem Proving with Retrieval-Augmented Language Models | An open-source platform advancing machine learning theorem proving in Lean via retrieval-augmented language models. | [NeurIPS 2023](https://arxiv.org/abs/2306.15626) |
| LeanDojo-v2 | LeanDojo-v2: Advanced AI-Assisted Theorem Proving for Lean 4 | An upgraded LeanDojo integrating repository tracking, dataset management, retrieval-augmented agents, and LLMs for Lean 4. | [开源工具](https://github.com/lean-dojo/LeanDojo) |
| LLEMMA | Llemma: An Open Language Model for Mathematics | An open-source math language model by EleutherAI trained on Proof-Pile-2 via continued pre-training of Code Llama, supporting mathematical reasoning and tool use. | [ICLR](https://arxiv.org/abs/2310.10631) |
| DeepSeek-Prover | DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data | An LLM enhanced for Lean formal theorem proving using large-scale synthetic data generation. | [arXiv](https://arxiv.org/abs/2405.14333) |
| DeepSeek-Prover-V1.5 | DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search | A Lean 4 theorem proving model optimized with proof assistant feedback, reinforcement learning, and Monte-Carlo tree search. | [arXiv](https://arxiv.org/abs/2408.08152) |
| DeepSeek-Prover-V2 | DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition | The latest open-source formal theorem proving model using recursive proof pipelines and DeepSeek-V3 for subgoal decomposition. | [arXiv](https://arxiv.org/abs/2504.21801) |
| InternLM-Math | InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning | An open-source bilingual math reasoning model by Shanghai AI Lab integrating chain-of-thought reasoning, Lean 4 proofs, and MATH problem solving. | [arXiv](https://arxiv.org/abs/2402.06332) |
| MathCoder | MathCoder: Seamless Code Integration in LLMs for Enhanced Mathematical Reasoning | A model series enhancing LLM mathematical reasoning through seamless code integration, fine-tuned on the MathCodeInstruct dataset. | [ICLR](https://arxiv.org/abs/2310.03731) |
| Minerva | Solving Quantitative Reasoning Problems with Language Models | A Google LLM trained on scientific and mathematical papers to enhance quantitative reasoning for math, physics, and engineering problems. | [NeurIPS 2022](https://arxiv.org/abs/2206.14858) |
| Goedel-Prover | Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving | An open-source Lean formal theorem proving model trained on large-scale synthetic data, advancing the automated theorem proving frontier. | [arXiv](https://arxiv.org/abs/2502.07640) |
| Goedel-Prover-V2 | Goedel-Prover-V2: Scaling Up Automated Theorem Proving with Reinforcement Learning | An extended Goedel-Prover incorporating reinforcement learning to further improve theorem proving capability. | [arXiv](https://arxiv.org/abs/2508.03613) |
| Kimina-Prover | Kimina-Prover: 72B Parameter Model Achieving 80.7% on miniF2F | A 72-billion-parameter Lean theorem proving model by Moonshot AI achieving 80.7% pass rate on the miniF2F benchmark. | [arXiv](https://arxiv.org/abs/2504.11354) |
| Seed-Prover | Seed-Prover: Advancing Formal Mathematical Reasoning | A formal mathematical reasoning model by ByteDance that solved 5/6 problems at the 2025 IMO. | [arXiv](https://arxiv.org/abs/2507.23726) |
| Seed-Prover 1.5 | Seed-Prover 1.5: Large-Scale Reinforcement Learning for Theorem Proving | An upgraded Seed-Prover using large-scale reinforcement learning training to further improve formal proof capability. | [arXiv](https://arxiv.org/abs/2512.17260) |
| InternLM2.5-StepProver | InternLM2.5-StepProver: Advancing Automated Theorem Proving via Expert Iteration on Large-Scale LEAN Problems | An expert iteration-based Lean theorem proving model by Shanghai AI Lab with critique-guided search strategies. | [arXiv](https://arxiv.org/abs/2410.15700) |
| FunSearch | Mathematical Discoveries from Program Search with Large Language Models | An evolutionary program search framework by DeepMind leveraging LLMs for mathematical discovery, finding new constructions for the cap set problem. | [Nature](https://doi.org/10.1038/s41586-023-06924-6) |
| LLM-SR | LLM-SR: Scientific Equation Discovery via Programming with Large Language Models | A framework for symbolic regression and scientific equation discovery using large language models. | [arXiv](https://arxiv.org/abs/2404.18400) |
| TheoremLlama | TheoremLlama: Transforming LLMs into Lean4 Experts | A framework that transforms a general-purpose LLM (LLaMA-3-8B) into a Lean 4 theorem proving expert. | [EMNLP](https://arxiv.org/abs/2407.03203) |
| HTPS | HyperTree Proof Search for Neural Theorem Proving | A Monte-Carlo tree search method for automatic theorem proving in Lean/Metamath achieving state-of-the-art results. | [NeurIPS 2022](https://arxiv.org/abs/2205.11491) |
| APOLLO | APOLLO: Automated LLM and Lean Collaboration for Proof Generation | A modular framework combining LLMs with Lean 4 formal verification for automated proof generation. | [NeurIPS](https://arxiv.org/abs/2505.05758) |
| LeanNavigator | Generating Millions of Lean Theorems with Proofs by Exploring State Transitions | A system for large-scale generation of Lean theorems and proofs through systematic state transition exploration. | [arXiv](https://arxiv.org/abs/2503.04772) |
| Numina-Lean-Agent | An Open and General Agentic Reasoning System for Formal Mathematics | An open and general agentic reasoning system for formal mathematical reasoning in Lean. | [arXiv](https://arxiv.org/abs/2601.14027) |
| Goedel-Code-Prover | Hierarchical Proof Search for Open Automated Code Verification | A hierarchical proof search system for automated code formal verification. | [arXiv](https://arxiv.org/abs/2603.19329) |
| AlphaVerus | Bootstrapping Formally Verified Code Generation through Self-Improving Translation | A self-improving LLM system that generates formally verified code by bootstrapping translation quality. | [ICLR](https://arxiv.org/abs/2412.06176) |
| SymCode | SymCode: Neurosymbolic Approach to Mathematical Reasoning via Verifiable Code | A neurosymbolic mathematical reasoning framework combining neural generation with formal code verification. | [EACL](https://arxiv.org/abs/2510.25975) |
| Leanstral | Leanstral: First Open-Source AI Agent for Formal Verification in Lean 4 | Mistral AI's first open-source AI agent for formal verification in Lean 4. | [Mistral AI](https://huggingface.co/mistralai/Leanstral-7B) |
| STP | Self-play Theorem Prover in Lean | A self-play LLM that alternates between conjecturing and proving theorems in Lean. | [ICML](https://arxiv.org/abs/2502.00212) |
| Hilbert | Hilbert: Recursively Building Formal Proofs via LLM and Lean | A system that recursively combines LLM reasoning with Lean verification to construct formal proofs. | [arXiv](https://arxiv.org/abs/2509.22819) |

---

<a id="mathematics-section-02"></a>
### Scientific Multimodal Reasoning
*Large-scale models for cross-disciplinary scientific knowledge understanding and reasoning, supporting text, images, molecules, and other scientific data modalities.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Intern-S1 | Intern-S1: A Scientific Multimodal Foundation Model | A 241B-parameter MoE scientific multimodal foundation model by Shanghai AI Lab trained on trillion-scale scientific data, supporting text/image/video scientific reasoning. | [arXiv](https://arxiv.org/abs/2508.15763) |
| Galactica | Galactica: A Large Language Model for Science | A scientific language model (125M–120B parameters) by Meta AI trained on 106 billion tokens of scientific literature, supporting paper summarization, math reasoning, and molecular understanding. | [arXiv](https://arxiv.org/abs/2211.09085) |
| SciGLM | SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning | A scientific language model enhanced via self-reflective instruction tuning for reasoning in physics, chemistry, math, and formal proofs. | [ACL](https://arxiv.org/abs/2401.07950) |
| SciDFM | SciDFM: A Large Language Model with Mixture-of-Experts for Science | An 18.2B-parameter (5.6B active) MoE science foundation model trained from scratch, supporting domain-specific knowledge including molecules and amino acid sequences. | [NeurIPS](https://arxiv.org/abs/2409.18412) |
| MathCoder2 | MathCoder2: Better Math Reasoning from Continued Pretraining on Model-Translated Mathematical Code | A method for enhancing LLM mathematical reasoning through continued pre-training on model-translated mathematical code. | [arXiv](https://arxiv.org/abs/2410.08196) |
| Intern-S1-Pro | Intern-S1-Pro: Scientific Multimodal Foundation Model at Trillion Scale | A trillion-parameter MoE scientific multimodal foundation model covering chemistry, physics, life sciences, and earth sciences. | [arXiv](https://arxiv.org/abs/2603.25040) |
| FuXi-Uni | FuXi-Uni: A Unified Multimodal Foundation Model for Cross-Disciplinary Scientific Research | A unified multimodal foundation model for cross-disciplinary scientific research integrating diverse scientific data types. | [arXiv](https://arxiv.org/abs/2601.01363) |
| Aletheia | Aletheia: Autonomous Math Research Agent for Professional Discoveries | An autonomous mathematical research agent by DeepMind capable of making professional-level mathematical discoveries. | [arXiv](https://arxiv.org/abs/2602.10177) |
| TongGeometry | TongGeometry: Proposing and Solving Olympiad Geometry with Guided Tree Search | A neuro-symbolic AI system for Olympiad geometry that can both solve and generate geometry problems. | [Nature MI](https://doi.org/10.1038/s42256-025-01164-x) |
| SR-Scientist | LLMs as AI Scientists for Scientific Equation Discovery | A framework that transforms LLMs into AI scientists for discovering scientific equations from data. | [ICLR](https://arxiv.org/abs/2510.11661) |

---

<a id="mathematics-section-03"></a>
### Mathematical Reasoning LLMs
*Large language models specialized for mathematical problem solving through pre-training and fine-tuning on large-scale math corpora and synthetic data.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Qwen2.5-Math | Qwen2.5-Math Technical Report: Toward Mathematical Expert Model via Self-Improvement | A bilingual (Chinese-English) math LLM series by Alibaba (1.5B–72B parameters) achieving leading performance on math reasoning benchmarks. | [技术报告](https://arxiv.org/abs/2409.12122) |
| DeepSeekMath | DeepSeek-Math: Pushing the Limits of Mathematical Reasoning in Open Language Models | A 7B-parameter math reasoning model trained on 120 billion math tokens via continued pre-training, pushing open-source math reasoning limits. | [arXiv](https://arxiv.org/abs/2402.03300) |
| NuminaMath | NuminaMath: AI Mathematical Olympiad (AIMO) Prize Winning Solution | The winning solution for the 1st AIMO Progress Prize using tool-integrated reasoning strategies to solve competition-level math problems. | [AIMO竞赛](https://huggingface.co/blog/winning-aimo-progress-prize) |
| Mathstral | MathΣtral: Mathematics-Specialized 7B Model | A 7B-parameter math-specialized model by Mistral AI optimized for mathematical reasoning and STEM problem solving. | [Mistral AI发布](https://mistral.ai/news/mathstral) |
| WizardMath | WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct | A model that enhances LLM mathematical reasoning through a reinforced evolutionary instruction method. | [arXiv](https://arxiv.org/abs/2308.09583) |
| MetaMath | MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models | A method that enhances LLM math training data by bootstrapping diverse mathematical question variants. | [ICLR](https://arxiv.org/abs/2309.12284) |
| ToRA | ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving | A tool-integrated reasoning agent that interleaves natural language reasoning with Python code execution for mathematical problem solving. | [ICLR](https://arxiv.org/abs/2309.17452) |
| MAmmoTH | MAmmoTH: Building Math Generalist Models through Hybrid Instruction Tuning | A math generalist model built through hybrid instruction tuning (CoT + PoT) using the MathInstruct dataset. | [ICLR](https://arxiv.org/abs/2309.05653) |
| MAmmoTH2 | MAmmoTH2: Scaling Instructions from the Web | An upgraded MAmmoTH leveraging web-scale data to expand mathematical instruction training. | [Advances in Neural Information Processing Systems 37](https://arxiv.org/abs/2405.03548) |
| DART-Math | DART-Math: Difficulty-Aware Rejection Tuning for Mathematical Reasoning | A difficulty-aware rejection sampling tuning method with biased training on high-difficulty math problems. | [NeurIPS](https://arxiv.org/abs/2407.13690) |
| JiuZhang3.0 | JiuZhang 3.0: Efficiently Improving Mathematical Reasoning by Training Small Data Synthesis Models | A method that efficiently improves math reasoning by training small data synthesis models, reducing data dependency. | [NeurIPS](https://arxiv.org/abs/2405.14365) |
| rStar-Math | rStar-Math: Small LLMs Can Master Math Reasoning with Self-Evolved Deep Thinking | A framework enabling small LLMs to master math reasoning via Monte-Carlo tree search and self-evolved deep thinking. | [ICML](https://arxiv.org/abs/2501.04519) |
| Skywork-Math | Skywork-Math: Data Scaling Laws for Mathematical Reasoning in Large Language Models | A study exploring data scaling laws for mathematical reasoning in LLMs, providing guidance for math LLM training. | [技术报告](https://arxiv.org/abs/2407.08348) |
| OpenMathInstruct-2 | OpenMathInstruct-2: Accelerating AI for Math with Massive Open-Source Instruction Tuning Data | A large-scale open-source math instruction tuning dataset by NVIDIA containing 14 million math question-answer pairs to advance math AI research. | [NeurIPS](https://arxiv.org/abs/2410.01560) |

## Agriculture & Ecology

> [English](agriculture-ecology/agriculture-ecology_en.md) | [Chinese](agriculture-ecology/agriculture-ecology_zh.md)

### Table of Contents
- [Agricultural AI Foundation Models](#agriculture-ecology-section-01)
- [Ecology & Biodiversity AI Foundation Models](#agriculture-ecology-section-02)
- [Related Remote Sensing Foundation Models](#agriculture-ecology-section-03)

<a id="agriculture-ecology-section-01"></a>
### Agricultural AI Foundation Models
*Foundation models for crop detection, plant disease identification, agricultural remote sensing, precision farming, and livestock management.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AgriGPT | AgriGPT: A Strong Plant Disease Detection Model via Visual Instruction Tuning | A multimodal AI model integrating visual and text data for precise plant disease detection and crop health assessment. | [Scholar XJTLU](https://scholar.xjtlu.edu.cn/en/publications/agrigpt-a-strong-plant-disease-detection-model-via-visual-instruct) |
| AgriGPT (Ecosystem) | AgriGPT: A Large Language Model Ecosystem for Agriculture | An agriculture-specific LLM ecosystem with a multi-agent data engine that compiles high-quality agricultural domain data. | [arXiv](https://arxiv.org/abs/2508.08632) |
| AgroGPT | AgroGPT: Efficient Agricultural Vision-Language Model with Expert Tuning | An agriculture-specific vision-language model trained via expert tuning on 70,000 images from the AgroInstruct dataset for crop disease dialogue. | [WACV](https://arxiv.org/abs/2410.08405) |
| IPM-AgriGPT | IPM-AgriGPT: A Large Language Model for Pest and Disease Management with a G-EA Framework | A large language model for integrated pest and disease management using agricultural context reasoning via the G-EA framework. | [Mathematics](https://doi.org/10.3390/math13040566) |
| AgriGPT-Omni | AgriGPT-Omni: A Unified Speech-Vision-Text Framework for Multilingual Agricultural Intelligence | A unified speech-vision-text multilingual agricultural AI framework by Zhejiang University. | [arXiv](https://arxiv.org/abs/2512.10624) |
| AgriFM | AgriFM: A Multi-source Temporal Remote Sensing Foundation Model for Crop Mapping | A multi-source temporal remote sensing foundation model integrating MODIS/Landsat/Sentinel-2 satellite data with an improved Video Swin Transformer for crop mapping. | [arXiv](https://arxiv.org/abs/2505.21357) |
| CropSTS | CropSTS: A Remote Sensing Foundation Model for Cropland Classification with Decoupled Spatiotemporal Attention | A crop classification remote sensing foundation model using decoupled spatiotemporal attention to address blurry field boundaries and limited temporal modeling. | [Remote Sensing](https://doi.org/10.3390/rs17142481) |
| PlantCaFo | PlantCaFo: An Efficient Few-Shot Plant Disease Recognition Method Leveraging Foundation Models | A few-shot crop disease recognition method leveraging CLIP and DINO foundation models for improved detection accuracy with limited data. | [Plant Phenomics](https://doi.org/10.1016/j.plaphe.2025.100024) |
| AlphaEarth Foundation | Evaluating Geospatial Foundation Models for Agricultural Applications | A geospatial foundation model trained on multi-source earth observation data evaluated for agricultural applications including crop yield prediction. | [arXiv](https://arxiv.org/abs/2601.00857) |
| MetaFruit | MetaFruit: Leveraging a Comprehensive Multi-Fruit Dataset for Advancing Agricultural Foundation Models | A multi-fruit detection foundation model by Penn State University for automated detection and counting of various fruits. | [Penn State](https://arxiv.org/abs/2407.04711) |
| VITA | VITA: Variational Pretraining of Transformers for Climate-Robust Crop Yield Forecasting | A variational Transformer model for crop yield prediction combining temporal remote sensing and environmental data. | [arXiv](https://arxiv.org/abs/2508.03589) |
| SoilNet | SoilNet: A Multimodal Multitask Model for Hierarchical Classification of Soil Horizons | A multimodal soil horizon classification foundation model integrating soil images, chemical, and physical property data. | [Geoderma](https://arxiv.org/abs/2508.03785) |
| AQUA | AQUA: A Large Language Model for Aquaculture and Fisheries | The first large language model for aquaculture and fisheries covering farming management, disease diagnosis, and domain knowledge. | [arXiv](https://arxiv.org/abs/2507.20520) |
| HarvestFlex | HarvestFlex: Strawberry Harvesting via Vision-Language-Action Policy Adaptation in the Wild | A vision-language-action model combining visual perception with robotic manipulation for automated strawberry harvesting. | [arXiv](https://arxiv.org/abs/2603.05982) |
| AnimalFormer | AnimalFormer: Multimodal Vision Framework for Behavior-based Livestock Monitoring | A Transformer-based livestock behavior recognition model supporting automated analysis of multiple animal behaviors. | [CVPR Workshop](https://arxiv.org/abs/2406.09711) |
| FoMo4Wheat | FoMo4Wheat: Toward Reliable Crop Vision Foundation Models | A wheat phenotyping foundation model for reliable crop vision analysis developed by the PheniX-Lab. | [arXiv](https://arxiv.org/abs/2509.06907) |
| SPROUT | SPROUT: Scalable Diffusion Foundation Model for Agricultural Vision | A scalable diffusion-based pre-trained foundation model for diverse agricultural vision tasks. | [arXiv](https://arxiv.org/abs/2603.27519) |
| PhenoAssistant | PhenoAssistant: Conversational Multi-agent AI for Plant Phenotyping | A conversational multi-agent AI system for automated plant phenotype analysis. | [Nature Communications](https://doi.org/10.1038/s41467-026-71090-y) |
| LeafNet | LeafNet: Large-scale Plant Disease Vision-Language Dataset and Benchmark | A large-scale plant disease vision-language dataset and benchmark for multimodal disease diagnosis research. | [arXiv](https://arxiv.org/abs/2602.13662) |

---

<a id="agriculture-ecology-section-02"></a>
### Ecology & Biodiversity AI Foundation Models
*Foundation models for wildlife identification, species distribution modeling, bioacoustics, and biodiversity monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SpeciesNet | SpeciesNet: Open-Source AI Model for Wildlife Species Identification | An open-source AI model by Google identifying nearly 2,500 wildlife species, trained on 65 million camera trap images for biodiversity monitoring. | [开源发布](https://github.com/google/cameratrapai) |
| BioAnalyst | BioAnalyst: A Foundation Model for Biodiversity | The first multimodal biodiversity foundation model integrating species records, remote sensing, and climate data for European conservation planning. | [NeurIPS](https://arxiv.org/abs/2507.09080) |
| NatureLM-audio | NatureLM-audio: An Audio-Language Foundation Model for Bioacoustics | The first large-scale bioacoustic audio-language foundation model supporting zero-shot species classification and sound description for ecological monitoring. | [arXiv](https://arxiv.org/abs/2411.07186) |
| Tighnari | Tighnari: Multi-modal Plant Species Prediction Based on Hierarchical Cross-Attention | A multimodal plant species prediction model integrating satellite imagery, climate time-series, land cover, and soil variables for spatiotemporal distribution prediction. | [arXiv](https://arxiv.org/abs/2501.02649) |
| Tighnari v2 | Tighnari v2: Mitigating Label Noise and Distribution Shift in Multi-modal Plant Species Prediction | An upgraded Tighnari addressing noisy labels and distribution shift for more robust plant species distribution prediction. | [arXiv](https://arxiv.org/abs/2602.08282) |
| OpenWildlife | OpenWildlife: Open-Vocabulary Multi-Species Wildlife Detector for Geographically-Diverse Aerial Imagery | An open-vocabulary multi-species wildlife detector using language-vision foundation models for terrestrial and marine aerial imagery. | [arXiv](https://arxiv.org/abs/2506.19204) |
| PlantCLEF | Overview of PlantCLEF 2024: Multi-species Plant Identification in Vegetation Plot Images | A multi-species plant identification challenge and model series based on 1.7M+ plant images for ecology and biodiversity research. | [arXiv](https://arxiv.org/abs/2509.15768) |
| GeoLifeCLEF | Overview of GeoLifeCLEF 2025: Plant Species Presence Prediction | A competition and benchmark for plant species distribution modeling using high-resolution environmental and remote sensing data across Europe. | [CLEF 2025](https://ceur-ws.org/Vol-4038/paper_234.pdf) |
| BirdNET | BirdNET: A Deep Learning Solution for Avian Diversity Monitoring | A deep learning bird sound recognition model by Cornell Lab of Ornithology supporting 6,500+ species (V3.0: 11,000+), widely used for ecological acoustic monitoring. | [Cornell Lab](https://doi.org/10.1016/j.ecoinf.2021.101236) |
| NicheFlow | NicheFlow: A Generative Foundation Model for Species Distribution Modeling | The first generative flow matching-based foundation model for species distribution modeling, learning continuous environment-species relationships. | [bioRxiv Preprint](https://www.biorxiv.org/content/10.1101/2024.10.15.618541) |
| EcoCast | EcoCast: A Spatio-Temporal Model for Continual Biodiversity and Climate Risk Forecasting | A spatio-temporal model for continual biodiversity and climate risk forecasting for ecosystem health assessment. | [NeurIPS Workshop](https://arxiv.org/abs/2512.02260) |
| MiTREE | MiTREE: Multi-input Transformer Ecoregion Encoder for Species Distribution Modelling | A multi-input Transformer model for species distribution estimation integrating multi-source environmental and remote sensing data. | [arXiv](https://arxiv.org/abs/2412.18995) |
| FoMo-Bench | FoMo-Bench: Foundation Model Benchmark for Forest Monitoring | A comprehensive benchmark evaluating multiple foundation models on forest monitoring tasks including forest cover change detection. | [AAAI](https://arxiv.org/abs/2312.10114) |
| Cattle-CLIP | Cattle-CLIP: A Multimodal Framework for Cattle Behaviour Recognition | A CLIP-based cattle behavior recognition model using vision-language learning for grazing behavior classification. | [arXiv](https://arxiv.org/abs/2510.09203) |
| Granite-Geospatial-Ocean | Granite Geospatial Ocean: IBM Foundation Model for Ocean Monitoring | A geospatial foundation model by IBM Research based on the Granite series for ocean environmental change detection and prediction. | [IBM Research](https://arxiv.org/abs/2509.21273) |
| OceanSAR | OceanSAR: SAR Ocean Observation Foundation Model | A SAR ocean observation foundation model specializing in sea surface monitoring, ship detection, and marine environment analysis. | [arXiv](https://arxiv.org/abs/2601.07392) |
| SatBird | SatBird: Bird Species Distribution Modeling with Remote Sensing and Citizen Science Data | A bird species distribution model combining satellite imagery with eBird citizen science data for avian ecology. | [NeurIPS](https://arxiv.org/abs/2311.02179) |
| Insect-Foundation | Insect-Foundation: A Foundation Model for Visual Insect Understanding | A visual insect understanding foundation model trained on 1 million insect images for automated entomological analysis. | [CVPR](https://arxiv.org/abs/2311.15206) |
| Atlantes | Atlantes: GPS Transformers for Global-Scale Maritime Intelligence | A GPS Transformer model by Allen AI for global-scale maritime vessel behavior analysis and intelligence. | [arXiv](https://arxiv.org/abs/2504.19036) |
| FMRAG | FMRAG: Retrieval-Augmented Multimodal LLM for Fisheries Intelligence | A retrieval-augmented multimodal LLM for fisheries intelligence supporting knowledge-grounded marine science QA. | [Frontiers in Marine Science](https://www.frontiersin.org/journals/marine-science/articles/10.3389/fmars.2026.1601584) |
| Buzzdetect | Buzzdetect: Open-source Deep Learning for Bioacoustic Pollinator Monitoring | An open-source deep learning system for automated bioacoustic monitoring of pollinators. | [Paper](https://www.biorxiv.org/content/10.1101/2025.06.13.659554) |
| BugNet | BugNet: Rapid Scalable Pipeline for Automated Insect Monitoring | A rapid and scalable automated insect monitoring pipeline using deep learning for ecological surveys. | [Frontiers Ecol. Evo.](https://doi.org/10.3389/fevo.2026.1750931) |

---

<a id="agriculture-ecology-section-03"></a>
### Related Remote Sensing Foundation Models
*Multi-modal remote sensing models with direct applications to agricultural and ecological monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SkySense++ | SkySense++: A Semantic-Enhanced Multi-Modal Remote Sensing Foundation Model for Earth Observation | A semantic-enhanced multimodal remote sensing foundation model trained on 27 million remote sensing samples supporting agricultural mapping and diverse earth observation tasks. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01078-8) |
| SkySense V2 | SkySense V2: A Unified Foundation Model for Multi-modal Remote Sensing | A unified multimodal remote sensing foundation model with a single Transformer backbone processing multiple remote sensing modalities. | [ICCV](https://arxiv.org/abs/2507.13812) |
| iNatAg | iNatAg: Multi-Class Classification Models with 4.7M Images of 2,959 Crop and Weed Species | A large-scale benchmark dataset of 4.7 million images covering 2,959 crop and weed species with classification models for agricultural applications. | [arXiv](https://arxiv.org/abs/2503.20068) |
