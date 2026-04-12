# Medicine & Biomedicine

<p align="right"><strong>Language:</strong> English | <a href="medicine_zh.md">中文</a></p>

> Medical imaging, pathology, radiology, clinical language models, surgical AI, digital health, drug discovery, and related medical foundation models.
> [Index](../README.md)

## Table of Contents
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
## Medical Imaging

*Foundation models for CT, MRI, X-ray, and other modalities — covering segmentation, classification, detection, and report generation across clinical imaging tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MRI-CORE | MRI-CORE: A Foundation Model for Magnetic Resonance Imaging | Foundation model pretrained on 110,000+ MRI volumes (6M+ slices) covering 18 body regions, supporting segmentation, classification, and zero-shot analysis. | [arXiv](https://arxiv.org/abs/2506.12186) |
| Pillar-0 | Pillar-0: A New Frontier for Radiology Foundation Models | Radiology foundation model from UC Berkeley/UCSF pretrained on abdominal-pelvic CT, chest CT, head CT, and breast MRI for interpreting 3D volumetric data. | [arXiv](https://arxiv.org/abs/2511.17803) |
| CineMA | CineMA: A Foundation Model for Cine Cardiac MRI | Cardiac MRI foundation model trained on 15 million cardiac MR images (~75,000 subjects), supporting ventricular segmentation, ejection fraction estimation, and disease detection. | [arXiv](https://arxiv.org/abs/2506.00679) |
| OmniMRI | OmniMRI: A Unified Vision-Language Foundation Model for MRI | Unified MRI foundation model covering acquisition, reconstruction, segmentation, detection, diagnosis, and report generation. | [arXiv](https://arxiv.org/abs/2508.17524) |
| BiomedCLIP | BiomedCLIP: A Multimodal Biomedical Foundation Model Pretrained from Fifteen Million Scientific Image-Text Pairs | Microsoft biomedical vision-language model pretrained on PMC-15M (15M image-text pairs), supporting cross-modal retrieval and zero-shot classification. | [NeurIPS](https://doi.org/10.1056/aioa2400640) |
| SAM-Med2D | SAM-Med2D | Adaptation of Segment Anything Model (SAM) for 2D medical image segmentation, fine-tuned on 4.6M images and 19.7M masks. | [arXiv](https://arxiv.org/abs/2308.16184) |
| SAM-Med3D | SAM-Med3D: Towards General-purpose Segmentation Models for Volumetric Medical Images | General-purpose 3D medical image segmentation model supporting multiple anatomical structures and lesions with minimal interactive annotation. | [Lecture Notes in Computer Science](https://doi.org/10.1007/978-3-031-91721-9_4) |
| MedSAM | Segment Anything in Medical Images | First universal medical image segmentation foundation model trained on 1.57M+ image-mask pairs across 10 imaging modalities. | [Nature Communications](https://doi.org/10.1038/s41467-024-44824-z) |
| MedSAM2 | MedSAM2: Segment Anything in 3D Medical Images and Videos | SAM 2-based 3D medical image and video segmentation model fine-tuned on 455,000+ 3D image-mask pairs. | [arXiv](https://arxiv.org/abs/2504.03600) |
| CT-CLIP | A Foundation Model Utilizing Chest CT Volumes and Radiology Reports for Supervised-Level Zero-Shot Detection of Abnormalities | 3D chest CT foundation model using contrastive language-image pretraining on CT-RATE dataset for zero-shot abnormality detection. | [arXiv](https://arxiv.org/abs/2403.17834) |
| CheXzero | Expert-Level Detection of Pathologies from Unannotated Chest X-ray Images via Self-Supervised Learning | Self-supervised contrastive learning model for zero-shot chest X-ray analysis achieving expert-level pathology detection without annotations. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-022-00936-9) |
| BioViL | Making the Most of Text Semantics to Improve Biomedical Vision-Language Processing | Microsoft biomedical vision-language model combining domain-specific language model CXR-BERT for enhanced chest X-ray analysis. | [Lecture Notes in Computer Science](https://doi.org/10.1007/978-3-031-20059-5_1) |
| BioViL-T | Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing | Microsoft temporal vision-language model for longitudinal chest X-ray analysis and phrase grounding in radiology. | [CVPR](https://doi.org/10.1109/CVPR52729.2023.01442) |
| LVM-Med | LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-Order Graph Matching | Large-scale self-supervised medical imaging vision model trained on ~1.3M multi-modal images (CT/MRI/X-ray/ultrasound). | [NeurIPS 2024](https://papers.nips.cc/paper_files/paper/2023/hash/58cc11cda2a2679e8af5c6317aed0af8-Abstract-Conference.html) |
| STU-Net | STU-Net: Scalable and Transferable Medical Image Segmentation Models Empowered by Large-Scale Supervised Pre-training | Scalable medical image segmentation model up to 1.4B parameters with strong transferability via large-scale supervised pretraining. | [arXiv](https://arxiv.org/abs/2304.06716) |
| UniverSeg | UniverSeg: Universal Medical Image Segmentation | Medical image segmentation model that generalizes to unseen tasks without additional training using in-context learning. | [ICCV 2023](https://doi.org/10.1109/ICCV51070.2023.01960) |
| RETFound | A Foundation Model for Generalizable Disease Detection from Retinal Images | Ophthalmic foundation model self-supervised pretrained on 1.6M unlabeled retinal images, supporting multiple eye and systemic disease detection. | [Nature](https://doi.org/10.1038/s41586-023-06555-x) |
| SkinGPT-4 | Pre-trained Multimodal Large Language Model Enhances Dermatological Diagnosis Using SkinGPT-4 | Interactive dermatological diagnosis system integrating a vision transformer and Llama-2-13b-chat, trained on 52,000+ skin disease images. | [Nature Communications](https://doi.org/10.1038/s41467-024-50043-3) |
| PanDerm | A Multimodal Vision Foundation Model for Clinical Dermatology | Multimodal dermatology foundation model pretrained on 2M+ skin disease images from 11 institutions across 4 imaging modalities. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03747-y) |
| RadFM | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data | Generalist radiology foundation model using 13M 2D images and 615K 3D scans for multi-modal training. | [Nature Communications](https://doi.org/10.1038/s41467-025-62385-7) |
| CheXFound | Chest X-ray Foundation Model with Global and Local Self-supervised Learning | Foundation model self-supervised pretrained on ~1M chest X-rays combining global and local learning strategies for improved clinical task generalization. | [arXiv](https://arxiv.org/abs/2502.05142) |
| REMEDIS | Robust and Data-Efficient Generalization of Self-Supervised Machine Learning for Diagnostic Imaging | Google medical imaging representation learning framework combining large-scale self-supervised pretraining with task-specific fine-tuning for improved robustness and data efficiency. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-023-01049-7) |
| MedicoSAM | MedicoSAM: Towards Foundation Models for Medical Image Segmentation | Systematic study exploring the adaptation of SAM as a foundation model for medical image segmentation. | [arXiv](https://arxiv.org/abs/2501.11734) |
| BiomedParse | BiomedParse: Biomedical Foundation Model for Image Parsing | Microsoft unified biomedical image parsing foundation model supporting segmentation, detection, and recognition. | [Nature Methods](https://doi.org/10.1038/s41592-024-02499-w) |
| SegVol | SegVol: Universal and Interactive Volumetric Medical Image Segmentation | Universal interactive 3D medical image segmentation supporting semantic and spatial prompts. | [NeurIPS 2024](https://papers.nips.cc/paper_files/paper/2024/hash/c7c7cf10082e454b9662a686ce6f1b6f-Abstract-Conference.html) |
| SuPreM | SuPreM: Label-Efficient 3D Medical Image Segmentation via Supervised Pre-training | Supervised pretrained 3D segmentation foundation model trained on 2,100+ CT scans. | [IEEE TMI](https://arxiv.org/abs/2410.06667) |
| VISTA3D | VISTA3D: Versatile Imaging Segmentation and Annotation Model for 3D | NVIDIA versatile 3D medical image segmentation and annotation model. | [MICCAI](https://doi.org/10.1109/cvpr52734.2025.01943) |
| CT-FM | CT Foundation Model for Body Composition Analysis | CT foundation model for body composition analysis. | [arXiv](https://arxiv.org/abs/2501.09001) |
| LCTfound | Learning CT Foundation Representations | Foundation representation learning for CT imaging. | [arXiv](https://arxiv.org/abs/2501.09001) |
| EVA-X | EVA-X: A Foundation Model for General Chest X-ray Analysis | Foundation model for general chest X-ray analysis. | [arXiv](https://arxiv.org/abs/2405.05237) |
| vesselFM | vesselFM: A Foundation Model for Universal 3D Blood Vessel Segmentation | Universal 3D blood vessel segmentation foundation model. | [arXiv](https://arxiv.org/abs/2504.02750) |
| Rad-DINO | RAD-DINO: Exploring Scalable Medical Image Encoders Beyond Text Supervision | Scalable medical image encoder going beyond text supervision. | [arXiv](https://arxiv.org/abs/2401.10815) |
| MAIRA-2 | MAIRA-2: Grounded Radiology Report Generation | Microsoft grounded radiology report generation combining localization and text. | [arXiv](https://arxiv.org/abs/2406.04449) |
| MedCLIP | MedCLIP: Contrastive Learning from Unpaired Medical Images and Text | Decoupled contrastive learning medical vision-language model from unpaired data. | [EMNLP 2022](https://doi.org/10.18653/v1/2022.emnlp-main.256) |
| PMC-CLIP | PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents | Biomedical CLIP pretrained on PubMed Central documents. | [Lecture Notes in Computer Science](https://doi.org/10.1007/978-3-031-43993-3_51) |
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
| SkinCLIP-VL | SkinCLIP-VL: Consistency-Aware Vision-Language Learning for Multimodal Skin Cancer Diagnosis | Consistency-aware vision-language learning for multimodal skin cancer diagnosis. | [arXiv](https://arxiv.org/abs/2603.21010) |
| BioMedGPT-R1 | BioMedGPT-R1: A 17B Multimodal Biomedical Foundation Model | Tsinghua University 17B-parameter multimodal biomedical foundation model integrating medical imaging and text understanding. | [Hugging Face](https://huggingface.co/PharMolix/BioMedGPT-R1) |
| LLaVA-NeXT-Med | LLaVA-NeXT-Med: Medical Multimodal Large Language Model | Medical version of LLaVA-NeXT enhanced through medical visual instruction tuning for improved multimodal medical image understanding and reasoning. | [IEEE](https://ieeexplore.ieee.org/document/10936400) |
| ChexGen | A Generative Foundation Model for Chest Radiography | Generative foundation model for chest X-ray synthesis. | [arXiv](https://arxiv.org/abs/2509.03903) |
| CheXficient | A data- and compute-efficient chest X-ray foundation model | Data- and compute-efficient chest X-ray foundation model. | [arXiv](https://arxiv.org/abs/2602.22843) |
| Ark+ | Fully open AI foundation model for chest radiography | Fully open AI foundation model for chest radiography published in Nature. | [Nature](https://doi.org/10.1038/s41586-025-08954-4) |
| MedSigLIP | Medical dual-tower vision-language encoder | Medical dual-tower vision-language encoder developed by Google Health, part of Health AI Developer Foundations. | [Google HADF](https://developers.google.com/health-ai-developer-foundations/medsiglip) |
| FM-CT | 3D Foundation Model for Generalizable Disease Detection in Head Computed Tomography | 3D head CT foundation model self-supervised pretrained on 361,663 non-contrast head CT scans using self-distillation and masked image modeling for generalizable disease detection. | [arXiv](https://arxiv.org/abs/2502.02779) |

---

<a id="medicine-section-02"></a>
## Neuroimaging

*Foundation models for brain MRI and fMRI data analysis — covering brain disease detection, brain region segmentation, cognitive state decoding, and neuroscience tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BrainIAC | A Generalizable Foundation Model for Analysis of Human Brain MRI | Foundation model self-supervised pretrained on ~49,000 unlabeled brain MRIs, learning universal brain representations for multiple downstream clinical tasks. | [Nature Neuroscience](https://doi.org/10.1038/s41593-026-02202-6) |
| GenBrain | GenBrain: A Generative Foundation Model of Multimodal Brain Imaging | Large-scale multimodal brain imaging generative foundation model pretrained on ~1.2M 3D MRI scans (44,000+ individuals, 34 imaging modalities). | [medRxiv](https://doi.org/10.1101/2025.12.19.25342614) |
| Prima | Learning Neuroimaging Models from Health System-Scale Data | Large-scale AI neuroimaging foundation model from University of Michigan trained on 220,000+ health system MRI studies, capable of reading brain MRIs within seconds. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-025-01608-0) |
| BrainSymphony | BrainSymphony: A Parameter-Efficient Multimodal Foundation Model for Neuroimaging | Lightweight, parameter-efficient multimodal neuroimaging foundation model integrating fMRI time series and diffusion MRI-derived structural connectivity. | [arXiv](https://arxiv.org/abs/2506.18314) |
| CytoNet | CytoNet: A Foundation Model for the Human Cerebral Cortex | Foundation model for analyzing human cerebral cortex at cellular resolution, trained on 1M+ unlabeled histological image patches. | [arXiv](https://arxiv.org/abs/2511.01870) |
| BrainLM | BrainLM: A Foundation Model for Brain Activity Recordings | Brain activity foundation model trained on 6,700 hours of fMRI data using self-supervised masked prediction for predicting age, sex, and clinical variables. | [ICLR](https://openreview.net/forum?id=RwI7ZEfR27) |
| BrainFM | BrainFM: A Modality-Agnostic Multi-task Foundation Model for Human Brain Imaging | Modality-agnostic multi-task brain imaging foundation model that generalizes across MRI/fMRI/EEG and other neuroimaging modalities. | [arXiv](https://arxiv.org/abs/2509.00549) |
| BrainGFM | BrainGFM: A Brain Graph Foundation Model for Neuroimaging Analysis | Brain graph foundation model using graph contrastive learning and masked autoencoders for fMRI data. | [NeurIPS](https://openreview.net/forum?id=BrainGFM) |
| BrainFounder | BrainFounder: Towards 3D Foundation Models for Neuroimage Segmentation | Large-scale neuroimaging segmentation foundation model pretrained on multimodal MRI from 41,400 participants with a two-stage pretraining strategy. | [MICCAI](https://doi.org/10.1016/j.media.2024.103301) |
| Brain Harmony | Brain Harmony: A Multimodal Foundation Model Unifying Brain Structural Morphology and Functional Dynamics | First multimodal brain foundation model unifying brain structural morphology (T1-MRI) and functional dynamics (fMRI). | [arXiv](https://arxiv.org/abs/2509.24693) |
| Brain-OF | Brain-OF: An Omnifunctional Foundation Model for fMRI, EEG and MEG | Omnifunctional foundation model spanning fMRI, EEG, and MEG neuroimaging modalities. | [arXiv](https://arxiv.org/abs/2602.23410) |
| SAM-Brain3D | Brain Foundation Models with Hypergraph Dynamic Adapter for Brain Disease Analysis | Brain imaging foundation model trained on 66,000+ MRI image-label pairs (14 sub-modalities) for brain disease analysis. | [Pattern Recognition](https://doi.org/10.1016/j.patcog.2025.112595) |
| MindLLM | MindLLM: A Subject-Agnostic and Versatile Model for fMRI-to-Text Decoding | Subject-agnostic fMRI-to-text decoding model advancing brain-computer interface research. | [ICML 2025](https://openreview.net/forum?id=MindLLM) |
| Decipher-MR | Decipher-MR: A Vision-Language Foundation Model for 3D MRI Representations | 3D MRI vision-language foundation model trained on 200,000+ MRI sequences, supporting multiple brain disease analysis including psychiatric disorders. | [npj Digital Medicine](https://doi.org/10.1038/s41746-026-02596-4) |
| SLIM-Brain | Data-efficient FM for fMRI analysis | Data-efficient foundation model for fMRI analysis. | [arXiv](https://arxiv.org/abs/2512.21881) |

---

<a id="medicine-section-03"></a>
## Pathology

*Foundation models for whole-slide image (WSI) analysis in histopathology — covering cancer detection, biomarker prediction, disease classification, and computational pathology tasks.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Virchow | Virchow: A Million-Slide Digital Pathology Foundation Model | Paige/Microsoft digital pathology foundation model self-supervised trained on 1.5M H&E-stained WSIs, supporting cancer detection and rare cancer identification. | [Nature Medicine](https://doi.org/10.1038/s41591-024-03141-0) |
| Virchow2 | Virchow 2: Scaling Self-Supervised Mixed Magnification Models in Pathology | Second-generation Virchow including Virchow2 (632M params) and Virchow2G (1.85B params), trained at mixed magnifications. | [arXiv](https://arxiv.org/abs/2408.00738) |
| UNI | Towards a General-Purpose Foundation Model for Computational Pathology | Mahmood Lab general-purpose computational pathology foundation model self-supervised trained on 100K+ WSIs across 20+ major tissue types. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02857-3) |
| UNI2 | Towards a General-Purpose Foundation Model for Computational Pathology | Upgraded UNI with ViT-H (UNI2-h) and ViT-G (UNI2-g-preview) variants, pretrained on 200M+ pathology images (350,000+ slides), released January 2025. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02857-3) |
| CONCH | A Visual-Language Foundation Model for Computational Pathology | First pathology visual-language foundation model (CONtrastive learning from Captions for Histopathology) trained on 1.17M+ image-text pairs. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02856-4) |
| TITAN | A Multimodal Whole-Slide Foundation Model for Pathology | Multimodal whole-slide foundation model combining visual self-supervised learning on 335,000+ WSIs with pathology report visual-language alignment. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03982-3) |
| Prov-GigaPath | A Whole-Slide Foundation Model for Digital Pathology from Real-World Data | Microsoft whole-slide foundation model pretrained on 1.3B image tiles (171,000+ real-world slides) with open-source weights. | [Nature](https://doi.org/10.1038/s41586-024-07441-w) |
| PLIP | A Visual-Language Foundation Model for Pathology Image Analysis Using Medical Twitter | CLIP-based pathology visual-language foundation model trained on medical social media data (OpenPath dataset). | [Nature Medicine](https://doi.org/10.1038/s41591-023-02504-3) |
| PathChat | A Foundational Multimodal Vision Language AI Assistant for Human Pathology | Multimodal pathology AI assistant integrating a vision encoder trained on 100M histology images and an LLM for interactive pathology analysis. | [Nature](https://doi.org/10.1038/s41586-024-08328-6) |
| CTransPath | Transformer-Based Unsupervised Contrastive Learning for Histopathological Image Classification | Histopathology feature extractor based on CNN-Swin Transformer hybrid architecture with self-supervised contrastive learning. | [Medical Image Analysis](https://doi.org/10.1016/j.media.2022.102559) |
| Hibou | Hibou: A Family of Foundational Vision Transformers for Pathology | HistAI family of pathology vision transformers (Hibou-B and Hibou-L) for cell detection, tissue classification, and more. | [arXiv](https://arxiv.org/abs/2406.05074) |
| Phikon | Scaling Self-Supervised Learning for Histopathology with Masked Image Modeling | Owkin histopathology self-supervised foundation model using iBOT framework trained on large-scale pathology data. | [arXiv](https://arxiv.org/abs/2310.08778) |
| Phikon-v2 | Phikon-v2: A Large and Public Feature Extractor for Biomarker Prediction | Upgraded Phikon trained on 460M+ pathology tiles (55,000+ slides, 30+ cancer types) as a large-scale public feature extractor. | [arXiv](https://arxiv.org/abs/2409.09173) |
| H-optimus-0 | H-optimus-0: An Open-Source AI Foundation Model for Pathology | World's largest open-source pathology AI foundation model (1.1B parameters) trained on 500,000+ WSIs, developed by Bioptimus. | [arXiv](https://arxiv.org/abs/2411.05114) |
| PathChat+ | A Clinical-Grade Agentic and Generative AI-Driven Copilot for Pathology | Clinical-grade upgrade of PathChat trained on 1M+ pathology-specific instruction samples and 5.5M QA pairs. | [arXiv](https://arxiv.org/abs/2506.20964) |
| UniBiomed | UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation | Unified biomedical image interpretation foundation model integrating multimodal LLM and segmentation model for simultaneous conversation and segmentation. | [arXiv](https://arxiv.org/abs/2504.21336) |
| CHIEF | Clinical Histopathology Imaging Evaluation Foundation | Universal clinical histopathology AI system pretrained on 60,000+ WSIs (19 anatomical sites), supporting cancer detection, grading, and molecular marker prediction. | [Nature](https://doi.org/10.1038/s41586-024-07894-z) |
| Atlas | Atlas: A Whole-Slide Foundation Model for Computational Pathology | Whole-slide level pathology foundation model. | [arXiv](https://arxiv.org/abs/2407.05325) |
| MUSK | A Vision-Language Foundation Model for Precision Oncology | Precision oncology vision-language foundation model supporting multimodal cancer diagnosis and prognosis prediction. | [Nature](https://doi.org/10.1038/s41586-025-08780-8) |
| PRISM | PRISM: A Multi-Modal Generative Foundation Model for Slide-Level Histopathology | Pathology multimodal foundation model integrating visual and molecular information. | [arXiv](https://arxiv.org/abs/2405.10254) |
| PRISM2 | PRISM2: Unlocking Multi-Modal General Pathology AI with Clinical Dialogue | Multimodal slide-level foundation model trained on 700K diagnostic specimen-report pairs (2.3M WSIs, 14M QA pairs), enabling clinical dialogue for general pathology AI. | [arXiv](https://arxiv.org/abs/2506.13063) |
| PathOrchestra | PathOrchestra: A Comprehensive Foundation Model for Computational Pathology | Comprehensive computational pathology foundation model covering multiple pathology tasks. | [arXiv](https://arxiv.org/abs/2503.00203) |
| kaiko.ai | Towards Training Large-Scale Pathology Foundation Models | Large-scale pathology foundation model training providing multi-scale ViT variants. | [arXiv](https://arxiv.org/abs/2404.15217) |
| RudolfV | A Foundation Model Connecting Pathology Images and Genomic Sequences | Foundation model connecting pathology images and genomic sequences. | [arXiv](https://arxiv.org/abs/2401.09027) |
| BEPH | A foundation model for generalizable cancer diagnosis and survival prediction from histopathological images | Foundation model for generalizable cancer diagnosis and survival prediction from histopathological images. | [Nature Communications](https://doi.org/10.1038/s41467-025-57587-y) |
| GPFM | A Generalizable Pathology Foundation Model | Generalizable pathology foundation model trained on 190K+ WSIs. | [arXiv](https://arxiv.org/abs/2407.18807) |
| mSTAR | Multi-Scale Tissue-Aware Representation | Multi-scale tissue-aware representation learning for pathology. | [arXiv](https://arxiv.org/abs/2407.15362) |
| HIPT | Hierarchical Image Pyramid Transformer for Whole-Slide Image Analysis | Hierarchical image pyramid Transformer for self-supervised learning on whole-slide images. | [CVPR](https://doi.org/10.1109/cvpr52688.2022.01567) |
| RetCCL | Retention-based Contrastive Learning for Histopathology | Retention-based contrastive learning pathology feature extractor. | [Medical Image Analysis](https://doi.org/10.1016/j.media.2022.102645) |
| PathoDuet | Foundation Models for Pathological Image Analysis via Self-Supervised Learning | Dual-scale self-supervised pathology foundation model. | [arXiv](https://arxiv.org/abs/2312.09849) |
| PLUTO | Pathology-Universal Transformer | Universal pathology Transformer model. | [arXiv](https://arxiv.org/abs/2405.07905) |
| COBRA | Unsupervised Foundation Model-Agnostic Slide-Level Representation Learning | Unsupervised foundation model-agnostic slide-level representation learning for pathology. | [CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Lenz_Unsupervised_Foundation_Model-Agnostic_Slide-Level_Representation_Learning_CVPR_2025_paper.pdf) |
| THREADS | Molecular-driven Foundation Model for Oncologic Pathology | Slide-level foundation model pretrained on 47K+ H&E sections paired with genomic/transcriptomic profiles via multimodal learning. | [arXiv](https://arxiv.org/abs/2501.16652) |
| MADELEINE | Multimodal ADaptive LEarning with INtegrated Embeddings | Multimodal adaptive pathology learning with integrated embeddings. | [arXiv](https://arxiv.org/abs/2405.15836) |
| Lunit-DINO | Benchmarking Self-Supervised Learning on Diverse Pathology Datasets | Lunit's DINOv2-based large-scale pathology pretraining. | [arXiv](https://arxiv.org/abs/2401.08527) |
| Quilt-LLaVA | Visual Instruction Tuning for Histopathology | Pathology visual instruction tuned multimodal model. | [arXiv](https://arxiv.org/abs/2312.04746) |
| Path Foundation | Developing and Validating a Foundation Model for Pathology | Google-developed pathology foundation model, part of the Health AI Developer Foundations (HADF) suite. | [Google HADF](https://developers.google.com/health-ai-developer-foundations/path-foundation) |
| CONCH 1.5 | A Multimodal Whole-Slide Foundation Model for Pathology | Upgraded CONCH with enhanced vision-language alignment, serving as the vision-language backbone of TITAN. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03982-3) |
| H-optimus-1 | H-optimus-1: Advanced Pathology Foundation Model | Upgraded H-optimus-0 with larger-scale training by Bioptimus. | [Hugging Face](https://huggingface.co/bioptimus/H-optimus-1) |
| Giga-SSL | Giga-SSL: Self-Supervised Learning for Gigapixel Images | Self-supervised learning method for gigapixel pathology images. | [CVPRW 2023](https://openaccess.thecvf.com/content/CVPR2023W/CVMI/papers/Lazard_Giga-SSL_Self-Supervised_Learning_for_Gigapixel_Images_CVPRW_2023_paper.pdf) |
| MUPAD | MUPAD: A Generative Foundation Model for Multimodal Histopathology | Multimodal histopathology generative foundation model integrating histology images, RNA molecular profiles, and clinical text. | [arXiv](https://arxiv.org/abs/2604.03635) |
| VISTA-PATH | VISTA-PATH: An interactive foundation model for pathology image segmentation and quantitative analysis | Interactive pathology image segmentation and quantitative analysis foundation model enhancing clinical relevance and accuracy. | [arXiv](https://arxiv.org/abs/2601.16451) |
| CARE | CARE: A Molecular-Guided Foundation Model with Adaptive Region Modeling for WSI Analysis | Molecular-guided adaptive region modeling foundation model for whole-slide image analysis. | [arXiv](https://arxiv.org/abs/2602.21637) |
| BRIGHT | BRIGHT: A Collaborative Generalist-Specialist Foundation Model for Breast Pathology | Collaborative generalist-specialist foundation model for breast pathology. | [arXiv](https://arxiv.org/abs/2603.03030) |
| GenBio-PathFM | GenBio-PathFM: A State-of-the-Art Foundation Model for Histopathology | 1.1B-parameter state-of-the-art histopathology foundation model fully trained on public data. | [bioRxiv Preprint](https://doi.org/10.1101/2026.03.17.712534) |
| Atlas 2 | State-of-the-art pathology FM trained on 5.5M WSIs | Pathology foundation model trained on 5.5M whole-slide images by Aignostics/Mayo. | [arXiv](https://arxiv.org/abs/2601.05148) |
| LongViT | LongViT: Long-Context Vision Transformer for Pathology | Long-context vision Transformer directly processing ultra-large pathology whole-slide images. | [arXiv](https://arxiv.org/abs/2403.14576) |
| Pixel-Mamba | Pixel-Mamba: Efficient Mamba-Based Foundation Model for Computational Pathology | Efficient Mamba architecture-based computational pathology foundation model with pixel-level processing. | [arXiv](https://arxiv.org/abs/2502.08058) |
| Virchow 2G | Virchow 2G: Scaling Self-Supervised Models to 1.9B Parameters for Pathology | ViT-G architecture 1.9B-parameter pathology foundation model trained on 3.1M WSIs (largest version in Virchow2 series). | [arXiv](https://arxiv.org/abs/2408.00738) |
| Campanella DINO | Campanella et al. (DINO): Self-Supervised ViT-S for Digital Pathology | ViT-S architecture pathology foundation model with DINOv1 self-supervised training on 420K WSIs. | [arXiv](https://arxiv.org/abs/2310.07033) |
| Campanella MAE | Campanella et al. (MAE): Masked Autoencoder ViT-L for Digital Pathology | ViT-L architecture pathology foundation model with MAE self-supervised training on 420K WSIs. | [arXiv](https://arxiv.org/abs/2310.07033) |
| SP22M | SP22M: Mount Sinai Computational Pathology Foundation Model (22M params) | Mount Sinai 22M-parameter computational pathology foundation model. | [Hugging Face](https://huggingface.co/MountSinaiCompPath/SP22M) |
| SP85M | SP85M: Mount Sinai Computational Pathology Foundation Model (85M params) | Mount Sinai 85M-parameter computational pathology foundation model. | [Hugging Face](https://huggingface.co/MountSinaiCompPath/SP85M) |

---
<a id="medicine-section-04"></a>
## Endoscopy & Surgery

*Foundation models for endoscopic video analysis, surgical scene understanding, phase recognition, and robotic surgery planning.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Endo-FM | Foundation Model for Endoscopy Video Analysis | First endoscopy video foundation model, self-supervised pretrained on 33,000+ endoscopy videos for scene recognition, action detection, and polyp segmentation. | [MICCAI](https://doi.org/10.1007/978-3-031-43996-4_10) |
| EndoDINO | A Foundation Model for GI Endoscopy | DINOv2-based gastrointestinal endoscopy foundation model pretrained on 1.75M+ images for GI disease classification and detection. | [arXiv](https://arxiv.org/abs/2501.05488) |
| EndoMamba | Efficient Foundation Model for Endoscopic Videos | Mamba-architecture efficient endoscopy video foundation model for temporal modeling in surgical video understanding. | [MICCAI](https://arxiv.org/abs/2502.19090) |
| SurgVISTA | Large-scale Self-supervised Video Foundation Model for Intelligent Surgery | Large-scale self-supervised surgical video foundation model trained on 3,650 videos / 3.55M frames, jointly learning spatiotemporal representations. | [npj Digital Medicine](https://doi.org/10.1038/s41746-026-02403-0) |
| SurgVLP | Learning Multi-modal Representations by Watching Hundreds of Surgical Video Lectures | Surgical vision-language pretraining framework learning joint visual and linguistic representations from surgical video lectures. | [MedIA](https://doi.org/10.1016/j.media.2025.103644) |
| SurgLLM | A Versatile Large Multimodal Model for Surgical Video Understanding | Large multimodal model for surgical video understanding, integrating vision and language for comprehensive surgical scene analysis. | [arXiv](https://arxiv.org/abs/2509.00357) |
| GSViT | General Surgery Vision Transformer: A Video Pre-trained Foundation Model for General Surgery | Video-pretrained vision Transformer foundation model for general surgery, advancing surgical video understanding through large-scale pretraining. | [arXiv](https://arxiv.org/abs/2403.05949) |
| HecVL | Hierarchical Video-Language Pretraining for Zero-shot Surgical Phase Recognition | Hierarchical video-language pretraining approach enabling zero-shot surgical phase recognition through three-level text supervision. | [MICCAI](https://doi.org/10.1007/978-3-031-72089-5_29) |
| PeskaVLP | Procedure-Aware Surgical Video-language Pretraining with Hierarchical Knowledge Augmentation | Procedure-aware surgical video-language pretraining framework augmented with hierarchical surgical knowledge for improved video understanding. | [NeurIPS 2024](https://papers.nips.cc/paper_files/paper/2024/hash/de0f2a9943b7bd060e5c10c2fb2654f3-Abstract-Conference.html) |
| SurgiSAM 2 | A Fine-tuned Foundational Model SurgiSAM2 for Surgical Video Anatomy Segmentation | Fine-tuned SAM2 model for surgical video anatomy segmentation and detection across multiple surgical datasets. | [Scientific Reports](https://doi.org/10.1038/s41598-025-11759-4) |
| ZEN | ZEN: A Generalizable Foundation Model for Intraoperative Understanding Across Surgical Procedures | Generalizable foundation model for real-time intraoperative understanding, supporting cross-procedure surgical video analysis. | [arXiv](https://arxiv.org/abs/2602.13633) |
| SurgMotion | SurgMotion: A Video-Native Foundation Model for Universal Understanding of Surgical Videos | Video-native surgical foundation model that learns directly from video rather than frame-level features for universal surgical video understanding. | [arXiv](https://arxiv.org/abs/2602.05638) |
| Surg-R1 | Surg-R1: A Hierarchical Reasoning Foundation Model for Scalable and Interpretable Surgical Decision Support | Hierarchical reasoning surgical foundation model with three-level reasoning architecture, validated across multiple clinical centers. | [arXiv](https://arxiv.org/abs/2603.12430) |
| Cosmos-H-Surgical | Learning Surgical Robot Policies from Videos via World Modeling | NVIDIA surgical robotics physical AI foundation model based on Cosmos world model architecture for surgical scene understanding and robot operation planning. | [arXiv](https://arxiv.org/abs/2512.23162) |
| SurgRec | Scaling Video Pretraining for Surgical Foundation Models | Large-scale self-supervised surgical video pretraining framework supporting multiple surgical visual understanding tasks. | [arXiv](https://arxiv.org/abs/2603.29966) |

---

<a id="medicine-section-05"></a>
## Ultrasound

*Foundation models for ultrasound imaging across organs including cardiac, fetal, and general abdominal ultrasound.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| USFM | A Universal Ultrasound Foundation Model Generalized to Tasks and Organs | Universal ultrasound foundation model generalizing across multiple organs and tasks with label-efficient learning. | [MedIA](https://doi.org/10.1016/j.media.2024.103202) |
| UltraFedFM | From Pretraining to Privacy: Federated Ultrasound Foundation Model with Self-Supervised Learning | Federated learning ultrasound foundation model trained across 16 institutions on 1M+ images, preserving data privacy. | [npj Digital Medicine](https://doi.org/10.1038/s41746-025-02085-0) |
| UltraDINO | General Methods Make Great Domain-Specific Foundation Models | DINOv2-based fetal ultrasound foundation model pretrained on 2M fetal ultrasound images for domain-specific tasks. | [MICCAI](https://doi.org/10.1007/978-3-032-04981-0_26) |
| EchoCare | Fully Open Foundation Model for Ultrasound | Fully open ultrasound foundation model pretrained on 4.5M images spanning multiple organs and clinical scenarios. | [arXiv](https://arxiv.org/abs/2509.11752) |
| OpenUS | Open-Source Foundation Model for Ultrasound | Fully open-source ultrasound foundation model pretrained on 308K+ images for broad ultrasound analysis. | [arXiv](https://arxiv.org/abs/2511.11510) |
| EchoFM | Foundation Model for Generalizable Echocardiogram Analysis | Self-supervised echocardiography video foundation model pretrained on 20M+ images for generalizable cardiac analysis. | [arXiv](https://arxiv.org/abs/2410.23413) |
| EchoApex | A General-Purpose Vision Foundation Model for Echocardiography | General-purpose vision foundation model for echocardiography pretrained on 20M+ echo images with self-supervised learning. | [arXiv](https://arxiv.org/abs/2410.11092) |
| EchoCLIP | Vision–Language Foundation Model for Echocardiogram Interpretation | Vision-language foundation model for echocardiography trained on 1M+ echo video–report pairs via contrastive learning. | [Nature Medicine](https://doi.org/10.1038/s41591-024-02959-y) |
| EchoPrime | Comprehensive Echocardiogram Evaluation with View Classification and AI-Enabled Measurements | Largest echocardiography AI model trained on 12M video–report pairs, supporting comprehensive echo evaluation and measurements. | [Nature](https://doi.org/10.1038/s41586-025-09850-x) |
| FetalCLIP | Visual-Language Foundation Model for Fetal Ultrasound | Vision-language foundation model for fetal ultrasound, enabling zero-shot and few-shot classification of fetal anatomy and pathology. | [arXiv](https://arxiv.org/abs/2502.14807) |
| UltraSam | Foundation Model for Ultrasound Segmentation | SAM-based ultrasound segmentation foundation model adapted for universal ultrasound image segmentation. | [arXiv](https://arxiv.org/abs/2411.16222) |
| Sonomate | A Visually Grounded Language Model for Fetal Ultrasound | Fetal ultrasound vision-language model integrating ultrasound imaging and clinical text for obstetric clinical decision support. | [Nature](https://doi.org/10.1038/s41551-025-01578-3) |
| EchoJEPA | EchoJEPA: A Latent Predictive Foundation Model for Echocardiography | Latent predictive echocardiography foundation model pretrained on 18M echocardiograms from 300K patients using V-JEPA 2 architecture; outperforms baselines by ~20% in LVEF estimation with zero-shot pediatric generalization. | [arXiv](https://arxiv.org/abs/2602.02603) |
| BUSGen | A foundation generative model for breast ultrasound image analysis | Generative foundation model pretrained on 3.5M+ breast ultrasound images; few-shot synthetic data generation for cancer screening, diagnosis, and prognosis, outperforming all 9 board-certified radiologists with 16.5% sensitivity improvement. | [Nature Biomedical Engineering](https://doi.org/10.1038/s41551-026-01639-1) |

---

<a id="medicine-section-06"></a>
## ECG & Physiological Signals

*Foundation models for electrocardiogram (ECG), electroencephalogram (EEG), electromyography (EMG), and other biosignal analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ECG-FM | Open Electrocardiogram Foundation Model | Open ECG foundation model pretrained on 1.5M ECGs for cardiac diagnosis and health profiling. | [npj Digital Medicine](https://doi.org/10.1093/jamiaopen/ooaf122) |
| ECGFounder | An Electrocardiogram Foundation Model Built on over 10 Million Recordings | ECG foundation model trained on 10.7M ECGs covering 150 diagnostic categories for comprehensive cardiac analysis. | [NEJM AI](https://doi.org/10.1056/aix2500913) |
| AnyECG | Evolved ECG Foundation Model for Health Profiling | Comprehensive health profiling ECG foundation model trained on 13.3M ECGs across diverse populations. | [arXiv](https://arxiv.org/abs/2601.10748) |
| MIRA | Medical Time Series Foundation Model | Microsoft medical time-series foundation model pretrained on 454B tokens covering ECG and other clinical time series. | [NeurIPS](https://arxiv.org/abs/2506.07584) |
| REVE | A Foundation Model for EEG | EEG foundation model pretrained on 60,000 hours of recordings from 25,000 subjects for brain-signal understanding. | [NeurIPS](https://arxiv.org/abs/2510.21585) |
| EEGPT | Unleashing the Potential of EEG Generalist Foundation Model by Autoregressive Pre-training | First generalist EEG foundation model using autoregressive pretraining for universal EEG understanding and decoding. | [arXiv](https://arxiv.org/abs/2410.19779) |
| FoME | A Foundation Model for EEG using Adaptive Temporal-Lateral Attention Scaling | EEG foundation model with adaptive temporal-lateral attention scaling for both scalp and intracranial EEG analysis. | [arXiv](https://arxiv.org/abs/2409.12454) |
| TinyMyo | Tiny Foundation Model for EMG | Lightweight EMG foundation model designed for edge deployment on wearable devices for muscle signal analysis. | [arXiv](https://arxiv.org/abs/2512.15729) |
| ECG-MoE | ECG-MoE: Mixture-of-Expert Electrocardiogram Foundation Model | Mixture-of-experts ECG foundation model that simultaneously captures periodicity and morphological features for enhanced cardiac diagnosis. | [arXiv](https://arxiv.org/abs/2603.04589) |
| LAMAE | LAMAE: Foundation Model for Cardiac Time Series via Masked Latent Attention | Cardiac time-series foundation model using ECG structural priors with latent attention masked autoencoder. | [arXiv](https://arxiv.org/abs/2603.26475) |
| ECG-Soup | ECG-Soup: Harnessing Multi-Layer Synergy for ECG Foundation Models | ECG foundation model leveraging multi-layer Transformer synergy for improved cardiac signal representation. | [arXiv](https://arxiv.org/abs/2509.00102) |
| BIOT | BIOT: Cross-data Biosignal Learning in the Wild | Cross-dataset biosignal Transformer that unifies EEG, ECG, EMG, and other physiological signal processing in a single framework. | [NeurIPS](https://papers.nips.cc/paper_files/paper/2023/hash/f6b30f3e2dd9cb53bbf2024402d02295-Abstract-Conference.html) |
| LaBraM | Large Brain Model for Learning Generic Representations with Tremendous EEG Data | Large-scale brain model pretrained on massive EEG data for universal EEG representation learning in brain–computer interfaces. | [ICLR](https://openreview.net/forum?id=QzTpTRVtrP) |
| CBraMod | CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding | Criss-cross Transformer brain foundation model for EEG decoding, separately modeling spatial and temporal dependencies. | [arXiv](https://arxiv.org/abs/2412.07236) |
| NeuroGPT | Neuro-GPT: Towards a Foundation Model for EEG | EEG foundation model combining an EEG encoder with a GPT-style architecture for brain signal understanding and generation. | [ISBI 2024](https://doi.org/10.1109/ISBI56570.2024.10635453) |
| BrainWave | BrainWave: A Brain Signal Foundation Model for Clinical Applications | Brain signal foundation model pretrained on 40,000+ hours of both invasive and non-invasive neural recordings for clinical applications. | [arXiv](https://arxiv.org/abs/2402.10251) |
| Brant-2 | Brant-2: Foundation Model for Brain Signals | Second-generation brain signal foundation model handling both EEG and intracranial EEG (iEEG/SEEG) for diverse neuroscience tasks. | [arXiv](https://arxiv.org/abs/2402.10251) |
| S-JEPA | S-JEPA: Towards Seamless Cross-Dataset Transfer Through Dynamic Spatial Attention | Self-supervised joint embedding predictive architecture for cross-dataset EEG transfer learning with dynamic spatial attention. | [arXiv](https://arxiv.org/abs/2403.11772) |
| EEG2Rep | EEG2Rep: Enhancing Self-supervised EEG Representation Through Informative Masking | Self-supervised EEG representation learning method using informative masked inputs to handle low-SNR and non-stationary brain signals. | [arXiv](https://arxiv.org/abs/2402.17772) |
| MaEEG | MAEEG: Masked Auto-encoder for EEG Representation Learning | Masked autoencoder for EEG data that reconstructs masked EEG features for self-supervised brain signal representation learning. | [arXiv](https://arxiv.org/abs/2211.02625) |

---

<a id="medicine-section-07"></a>
## Dental Imaging

*Foundation models for dental radiography analysis including panoramic X-rays, caries detection, and oral disease diagnosis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| DentVFM | Vision Foundation Models for Oral Radiology | Vision foundation model for oral and maxillofacial radiology supporting dental disease detection and classification. | [arXiv](https://arxiv.org/abs/2510.14532) |
| DentVLM | Multimodal Vision-Language Model for Dental Diagnosis | Multimodal vision-language model for dental diagnosis integrating dental imaging with clinical text. | [arXiv](https://arxiv.org/abs/2509.23344) |
| DVCTNet | Adapting Foundation Model for Dental Caries Detection | Dual-view foundation model adapted for dental caries detection from radiographic images. | [arXiv](https://arxiv.org/abs/2508.20813) |
| OralGPT-Omni | Versatile Dental Multimodal Large Language Model | Versatile dental multimodal large language model supporting comprehensive oral disease analysis and clinical dialogue. | [arXiv](https://arxiv.org/abs/2511.22055) |

---

<a id="medicine-section-08"></a>
## Ophthalmology

*Foundation models for retinal imaging, optical coherence tomography (OCT), fundus photography, and ophthalmic surgery video analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OCTCube | A 3D Foundation Model for Optical Coherence Tomography | 3D OCT foundation model for volumetric retinal image analysis and ophthalmic disease detection. | [arXiv](https://arxiv.org/abs/2408.11227) |
| MIRAGE | Multimodal Foundation Model and Benchmark for Comprehensive Retinal OCT Image Analysis | Multimodal foundation model for comprehensive retinal OCT and SLO image analysis with large-scale benchmark. | [npj Digital Medicine](https://doi.org/10.1038/s41746-025-01852-3) |
| VisionFM | Development and Validation of a Multimodal Multitask Vision Foundation Model for Generalist Ophthalmic AI | Multimodal ophthalmic vision foundation model pretrained on 3.4M images across multiple eye imaging modalities for generalist ophthalmic AI. | [NEJM AI](https://doi.org/10.1056/AIoa2300221) |
| EyeFound | Multimodal Generalist Foundation Model for Ophthalmic Imaging | Multimodal generalist foundation model pretrained on 2.78M retinal images across 11 modalities for comprehensive ophthalmic imaging analysis. | [arXiv](https://arxiv.org/abs/2405.11338) |
| FLAIR | A Foundation LAnguage-Image Model of the Retina | Vision-language foundation model for retinal fundus image understanding, aligning visual and textual expert knowledge. | [MedIA](https://doi.org/10.1016/j.media.2024.103357) |
| RET-CLIP | A Retinal Image Foundation Model Pre-trained with Clinical Diagnostic Reports | CLIP-style retinal image foundation model pretrained with clinical diagnostic reports for ophthalmic disease classification. | [MICCAI](https://doi.org/10.1007/978-3-031-72390-2_66) |
| VOLMO | VOLMO: Versatile and Open Large Models for Ophthalmology | Open large-scale versatile ophthalmology foundation model with three-stage training covering multiple ophthalmic tasks. | [arXiv](https://arxiv.org/abs/2603.23953) |
| Dual-IFM | Dual-IFM: Towards Interpretable Foundation Models for Retinal Fundus Images | Interpretable retinal fundus image foundation model with local-to-global interpretability for clinical transparency. | [arXiv](https://arxiv.org/abs/2603.18846) |
| OCTCube-M | OCTCube-M: A 3D Multimodal Optical Coherence Tomography Foundation Model for Ophthalmic Disease Diagnosis | Upgraded OCTCube integrating multimodal OCT data for comprehensive 3D ophthalmic disease diagnosis. | [arXiv](https://arxiv.org/abs/2408.11227) |
| EyeFM | An Eyecare Foundation Model for Clinical Assistance | Universal eyecare foundation model published in Nature Medicine, pretrained on large-scale multimodal ophthalmic data for AI-assisted clinical care. | [Nature Medicine](https://doi.org/10.1038/s41591-025-03900-7) |
| OVFM | An Ophthalmic Video Foundation Model for Surgical Recognition and Navigation | Self-supervised ophthalmic video Transformer for real-time surgical recognition and navigation during microscopic procedures. | [Nature BME](https://doi.org/10.1038/s41551-026-01622-w) |

---
<a id="medicine-section-09"></a>
## Medical NLP

*Foundation models for biomedical and clinical natural language processing, including medical LLMs, clinical text mining, and biomedical language understanding.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Med-PaLM | Large Language Models Encode Clinical Knowledge | Google's first medical LLM, achieving expert-level performance on medical question answering benchmarks by encoding clinical knowledge in a large language model. | [Nature](https://doi.org/10.1038/s41586-023-06291-2) |
| Med-PaLM 2 | Towards Expert-Level Medical Question Answering with Large Language Models | Second-generation Google medical LLM reaching expert-level medical QA performance, significantly improving over Med-PaLM on multiple clinical benchmarks. | [Nature Medicine](https://doi.org/10.1038/s41591-024-03423-7) |
| Med-Gemini | Advancing Multimodal Medical Capabilities of Gemini | Google multimodal medical AI extending Gemini's capabilities to clinical reasoning across text, images, and genomics. | [arXiv](https://arxiv.org/abs/2405.03162) |
| MedGemma | Open Models for Health AI | Google's open-source collection of Gemma variants tailored for medical text and image understanding, offering multimodal and text-only pretrained formats. | [Google](https://developers.google.com/health-ai-developer-foundations/medgemma) |
| PubMedBERT | Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing | BERT model pretrained from scratch exclusively on PubMed abstracts and full texts, demonstrating that domain-specific pretraining outperforms mixed-domain approaches for biomedical NLP. | [ACM HEALTH](https://doi.org/10.1145/3458754) |
| GatorTron | A Large Clinical Language Model to Unlock Patient Information from Unstructured Electronic Health Records | Large-scale clinical language model (up to 8.9B parameters) pretrained on over 90 billion words of clinical text, designed to unlock patient information from unstructured EHRs. | [npj Digital Medicine](https://doi.org/10.1038/s41746-022-00742-2) |
| BioGPT | Generative Pre-trained Transformer for Biomedical Text Generation and Mining | Domain-specific generative Transformer pretrained on large-scale biomedical literature for both text generation and mining tasks in biomedicine. | [Briefings in Bioinformatics](https://doi.org/10.1093/bib/bbac409) |
| PMC-LLaMA | Building Open-Source Language Models for Medicine | Open-source medical LLM fine-tuned on PubMed Central papers, enabling accessible medical language understanding and generation. | [JAMIA](https://doi.org/10.1093/jamia/ocae045) |
| MedAlpaca | An Open-Source Collection of Medical Conversational AI Models and Training Data | Open-source collection of medical conversational AI models fine-tuned for clinical dialogue and medical question answering. | [arXiv](https://arxiv.org/abs/2304.08247) |
| Meditron | Open Medical Foundation LLMs Adapted from Llama 2 | Medical foundation LLM adapted from LLaMA 2, fine-tuned on 48B tokens of curated medical literature from PubMed, clinical guidelines, and medical papers. | [arXiv](https://arxiv.org/abs/2311.16079) |
| ClinicalBERT | ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission | BERT model adapted for clinical notes, pretrained on clinical text to learn patient representations for hospital readmission prediction and other clinical tasks. | [CHIL](https://arxiv.org/abs/1904.05342) |
| HuatuoGPT | HuatuoGPT, Towards Taming Language Model to Be a Doctor | Chinese medical LLM combining ChatGPT-distilled data and real physician data with supervised fine-tuning and RLHF for medical consultation. | [EMNLP 2023 Findings](https://doi.org/10.18653/v1/2023.findings-emnlp.725) |
| HuatuoGPT-o1 | HuatuoGPT-o1, Towards Medical Complex Reasoning with LLMs | Medical complex reasoning LLM that uses verifier-guided search and reinforcement learning to enhance medical diagnostic reasoning capabilities. | [ACL 2025 Findings](https://doi.org/10.18653/v1/2025.findings-acl.751) |
| ChatDoctor | ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model Meta AI Using Medical Domain Knowledge | Medical dialogue model fine-tuned on LLaMA using 100K anonymized patient-doctor conversations for clinical consultation. | [arXiv / PMC](https://arxiv.org/abs/2303.14070) |
| DoctorGLM | DoctorGLM: Fine-tuning Your Chinese Doctor is Not a Herculean Task | Chinese medical LLM based on ChatGLM-6B, fine-tuned with Chinese medical dialogue data for accessible Chinese medical consultation. | [arXiv](https://arxiv.org/abs/2304.01097) |
| BioMistral | BioMistral: A Collection of Open-Source Pretrained Large Language Models for Medical Domain | Open-source biomedical LLM based on Mistral, continually pretrained on PubMed Central data for improved performance on medical benchmarks. | [ACL](https://doi.org/10.18653/v1/2024.findings-acl.348) |
| Me-LLaMA | Me-LLaMA: Foundation Large Language Models for Medical Applications | Medical foundation LLM (13B/70B) based on LLaMA 2, continually pretrained on large-scale biomedical and clinical data with instruction fine-tuning for medical applications. | [npj Digital Medicine](https://arxiv.org/abs/2402.12749) |
| OpenBioLLM | OpenBioLLM-70B: Advancing Open-Source Large Language Models in Medical Domain | 70B-parameter open-source biomedical LLM based on Llama 3, outperforming GPT-4 and other closed-source models on multiple medical benchmarks. | [Open Release](https://huggingface.co/aaditya/Llama3-OpenBioLLM-70B) |
| MMedLM | Towards Building Multilingual Language Model for Medicine | Multilingual medical language model trained on the MMedC multilingual medical corpus, supporting cross-language medical question answering across multiple languages. | [Nature Communications](https://doi.org/10.1038/s41467-024-52417-z) |
| ClinicalMamba | ClinicalMamba: A Generative Clinical Language Model on Longitudinal Clinical Notes | Generative clinical language model based on Mamba architecture, designed for processing longitudinal clinical notes with efficient sequence modeling. | [ClinicalNLP 2024](https://doi.org/10.18653/v1/2024.clinicalnlp-1.5) |
| ChiMed-GPT | ChiMed-GPT: A Chinese Medical Large Language Model with Full Training Regime and Better Alignment to Human Preferences | Full-training-regime Chinese medical LLM combining pre-training, supervised fine-tuning, and RLHF for aligned Chinese medical language understanding. | [ACL 2024](https://doi.org/10.18653/v1/2024.acl-long.386) |
| BioBART | BioBART: Pretraining and Evaluation of a Biomedical Generative Language Model | Biomedical generative language model based on BART architecture, pretrained on PubMed abstracts for biomedical text generation and summarization. | [BioNLP 2022](https://doi.org/10.18653/v1/2022.bionlp-1.9) |
| ClinicalT5 | ClinicalT5: A Generative Language Model for Clinical Text | Clinical text generative language model based on T5 architecture, pretrained on clinical notes to bridge the gap between general-domain and clinical-domain NLP. | [EMNLP 2023 Findings](https://aclanthology.org/2022.findings-emnlp.398) |
| KeBioLM | Improving Biomedical Pretrained Language Models with Knowledge | Knowledge-enhanced biomedical pretrained language model integrating UMLS knowledge graph entities to improve biomedical text understanding. | [BioNLP 2021](https://doi.org/10.18653/v1/2021.bionlp-1.20) |
| BioELMo | Probing Biomedical Embeddings from Language Models | Biomedical embedding model based on ELMo, pretrained on PubMed text to produce contextualized biomedical word representations for downstream tasks. | [RepEval 2019](https://doi.org/10.18653/v1/w19-2011) |
| RadBERT | RadBERT: Adapting Transformer-based Language Models to Radiology | Radiology-domain adapted BERT language model for improved understanding of radiological text and report processing. | [Radiology: Artificial Intelligence](https://doi.org/10.1148/ryai.210258) |
| BioBERT | BioBERT: A Pre-trained Biomedical Language Representation Model for Biomedical Text Mining | First biomedical domain BERT pretrained on PubMed abstracts and PMC full-text articles, widely used as a foundation for biomedical text mining tasks. | [Bioinformatics](https://doi.org/10.1093/bioinformatics/btz682) |
| SciBERT | SciBERT: A Pretrained Language Model for Scientific Text | BERT model pretrained on 1.14M scientific papers (primarily biomedical), serving as a foundation for scientific and biomedical NLP tasks. | [EMNLP 2019](https://doi.org/10.18653/v1/D19-1371) |
| BioLinkBERT | LinkBERT: Pretraining Language Models with Document Links | BERT model pretrained with document link information from biomedical literature, enhancing cross-document knowledge capture for biomedical NLP. | [ACL 2022](https://doi.org/10.18653/v1/2022.acl-long.551) |
| MetaReact | MetaReact: Reaction-Aware Transformer for Drug Metabolism Prediction | Reaction-aware Transformer for predicting drug metabolism pathways, integrating chemical reaction knowledge into drug metabolism modeling. | [bioRxiv](https://doi.org/10.1101/2026.03.14.711529) |

---
<a id="medicine-section-10"></a>
## Medical Multimodal

*Foundation models integrating multiple medical data modalities (vision, language, speech) for cross-modal biomedical understanding, diagnosis, and generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LLaVA-Med | LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day | Microsoft's cost-efficient multimodal conversational AI for biomedicine, trained on biomedical image-text data using a curriculum learning approach. | [NeurIPS 2023](https://papers.nips.cc/paper_files/paper/2023/hash/5abcdf8ecdcacba028c6662789194572-Abstract-Datasets_and_Benchmarks.html) |
| BiomedGPT | A Generalist Vision–Language Foundation Model for Diverse Biomedical Tasks | Open-source, lightweight generalist vision-language foundation model capable of handling 16 diverse biomedical tasks across imaging and text. | [Nature Medicine](https://doi.org/10.1038/s41591-024-03185-2) |
| XrayGPT | XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models | Conversational medical vision-language model that integrates MedClip and Vicuna for chest X-ray analysis and report summarization. | [arXiv](https://arxiv.org/abs/2306.07971) |
| Med-Flamingo | Med-Flamingo: a Multimodal Medical Few-shot Learner | Multimodal medical few-shot learner based on OpenFlamingo-9B, continued pretraining on paired medical image-text data for few-shot medical visual QA. | [ML4H](https://proceedings.mlr.press/v225/moor23a.html) |
| MedASR | MedASR: A Conformer-Based Medical Speech Recognition Model | Google Health's open-weight Conformer-based medical speech-to-text model (105M parameters) trained on 5,000+ hours of de-identified medical speech data. | [Google HADF](https://developers.google.com/health-ai-developer-foundations/medasr/get-started) |
| MedGemma 1.5 | MedGemma 1.5 Technical Report | Google's latest multimodal medical foundation model with significantly enhanced capabilities for high-dimensional medical imaging (CT, MRI, histopathology WSI). | [arXiv](https://arxiv.org/abs/2604.05081) |
| MedMO | MedMO: Grounding and Understanding Multimodal Large Language Model for Medical Images | Medical multimodal LLM trained on 26M+ diverse medical samples, supporting both grounding and understanding of medical images. | [arXiv](https://arxiv.org/abs/2602.06965) |
| UNIMEDVL | UniMedVL: Unifying Medical Multimodal Understanding and Generation Through Observation-Knowledge-Analysis | Unified medical multimodal framework that simultaneously handles image understanding and generation within a single architecture for clinical diagnosis. | [arXiv](https://arxiv.org/abs/2510.15710) |
| MeDiM | MeDiM: Discrete Diffusion Models with MLLMs for Unified Medical Multimodal Generation | First medical discrete diffusion model that unifies multimodal medical generation (image-text bidirectional translation) without modality-specific components. | [OpenReview](https://openreview.net/forum?id=E6jDNtfj6X) |
| Lingshu | Lingshu: A Generalist Foundation Model for Unified Multimodal Medical Understanding and Reasoning | Generalist multimodal medical LLM supporting unified understanding and reasoning across diverse medical data modalities. | [arXiv](https://arxiv.org/abs/2506.07044) |
| CLEAR | CLEAR: An Auditable Foundation Model for Radiology Grounded in Clinical Concepts | Auditable radiology foundation model trained on ~870K chest X-ray image-report pairs, grounding predictions in explicit clinical concepts for transparency. | [medRxiv](https://www.medrxiv.org/content/10.64898/2026.01.15.26344222v1) |
| GreenRFM | GreenRFM: Toward a Resource-Efficient Radiology Foundation Model | Resource-efficient radiology foundation model that achieves state-of-the-art performance with dramatically reduced compute and memory requirements. | [arXiv](https://arxiv.org/abs/2603.06467) |
| Curia-2 | Curia-2: Scaling Self-Supervised Learning for Radiology Foundation Models | Raidium's advanced self-supervised radiology foundation model, scaling CT/MRI representation learning beyond its predecessor Curia. | [arXiv](https://arxiv.org/abs/2604.01987) |
| MediVLM | MediVLM: A Vision Language Model for Radiology Report Generation | Vision-language model combining a pretrained object detector and image encoder with an LLM decoder for automated radiology report generation. | [EMNLP 2025](https://aclanthology.org/2025.findings-emnlp.544/) |
| InfiMed-Foundation | InfiMed-Foundation: Pioneering Advanced Multimodal Medical Foundation Models | Compute-efficient medical multimodal LLMs (1.7B and 4B) delivering state-of-the-art medical performance with reduced computational overhead. | [arXiv](https://arxiv.org/abs/2509.22261) |

---

<a id="medicine-section-11"></a>
## Electronic Health Records

*Foundation models for structured and unstructured electronic health record (EHR) data, supporting disease prediction, patient timeline modeling, and clinical event extraction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| BEHRT | BEHRT: Transformer for Electronic Health Records | BERT-based deep neural sequence model trained on ~1.6M patient EHRs for predicting future health outcomes from longitudinal medical codes. | [Scientific Reports](https://doi.org/10.1038/s41598-020-62922-y) |
| Med-BERT | Med-BERT: Pretrained Contextualized Embeddings on Large-Scale Structured Electronic Health Records for Disease Prediction | BERT-style model pretrained on large-scale structured EHR data for improved disease prediction, especially with limited labeled data. | [JAMIA](https://doi.org/10.1038/s41746-021-00455-y) |
| CLMBR | Modeling EHR with Self-Supervised Learning | Autoregressive clinical language model (141M parameters) pretrained on 2.57M de-identified EHRs from Stanford for clinical prediction tasks. | [NeurIPS](https://arxiv.org/abs/2307.02028) |
| CEHR-BERT | CEHR-BERT: Incorporating Temporal Information from Structured EHR Data to Improve Prediction Tasks | Temporal-enhanced BERT adaptation for structured EHR data that incorporates time intervals to improve clinical prediction tasks. | [ML4H 2021](https://proceedings.mlr.press/v158/pang21a.html) |
| EHRMamba | EHRMamba: Towards Generalizable and Scalable Foundation Models for Electronic Health Records | Mamba-architecture foundation model for EHR data, designed for generalizable and scalable clinical prediction across diverse healthcare settings. | [arXiv](https://arxiv.org/abs/2405.14567) |
| MOTOR | MOTOR: A Time-To-Event Foundation Model For Structured Medical Records | Self-supervised time-to-event foundation model for structured medical records that pretrains on timestamped clinical event sequences. | [NeurIPS](https://openreview.net/forum?id=NialiwI2V6) |
| CEHR-GPT | CEHR-GPT: Generating Electronic Health Records with Chronological Patient Timelines | GPT-based model for generating synthetic EHR data as chronological patient timelines, supporting privacy-preserving data augmentation. | [arXiv](https://arxiv.org/abs/2402.04400) |
| Foresight | Foresight—A Generative Pretrained Transformer for Modelling of Patient Timelines Using Electronic Health Records | Generative pretrained transformer modeling patient timelines from EHRs for clinical event prediction and digital twin generation. | [Lancet Digital Health](https://doi.org/10.1016/S2589-7500%2824%2900025-6) |
| Panacea | Panacea: A Foundation Model for Clinical Trial Search, Summarization, Design and Recruitment | Foundation model for clinical trial tasks including search, summarization, design, and patient-trial matching. | [arXiv](https://arxiv.org/abs/2407.11007) |

---

<a id="medicine-section-12"></a>
## Nuclear Medicine

*Foundation models for PET/CT functional imaging, supporting whole-body metabolic analysis, tumor detection, organ segmentation, and report generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SDF-HOLO | A Generalist Foundation Model for Total-body PET/CT Enables Diagnostic Reporting and System-wide Metabolic Profiling | Multimodal foundation model trained on >10,000 patients' total-body PET/CT data with dual-stream architecture for diagnostic reporting and whole-body metabolic profiling. | [arXiv](https://arxiv.org/abs/2601.12820) |
| FratMAE | Developing a PET/CT Foundation Model for Cross-Modal Anatomical and Functional Imaging | Dual-ViT-encoder PET/CT cross-modal foundation model for joint functional-anatomical analysis in oncology applications. | [arXiv](https://arxiv.org/abs/2503.02824) |
| SegAnyPET | Developing Foundation Models for Universal Segmentation from 3D Whole-Body Positron Emission Tomography | First universal PET image segmentation foundation model, trained on >11,000 PET scans with 600K annotations for organ and lesion segmentation. | [ICCV](https://arxiv.org/abs/2603.11627) |

---

<a id="medicine-section-13"></a>
## Mammography

*Foundation models for mammographic imaging analysis, supporting breast cancer screening, diagnosis, prognosis prediction, and report generation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Mammo-CLIP | Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography | Vision-language foundation model pretrained on large-scale mammogram-report pairs to improve data efficiency and robustness in breast cancer detection. | [Lecture Notes in Computer Science](https://doi.org/10.1007/978-3-031-72390-2_59) |
| MammoDINO | MammoDINO: Anatomically Aware Self-Supervision for Mammographic Images | Self-supervised foundation model based on DINOv2 trained on >1.4M mammographic images with anatomy-aware augmentation and cross-view learning. | [arXiv](https://arxiv.org/abs/2510.11883) |
| VersaMammo | A Versatile Foundation Model for AI-enabled Mammogram Interpretation | Versatile foundation model trained on >700K multi-institutional mammograms supporting multiple breast cancer detection and diagnostic tasks. | [arXiv](https://arxiv.org/abs/2509.20271) |
| Mammo-FM | Mammo-FM: Breast-specific Foundational Model for Integrated Mammographic Diagnosis, Prognosis, and Reporting | Breast-specific foundation model trained on >140K patients and 820K images, unifying mammographic diagnosis, prognosis prediction, and report generation. | [arXiv](https://arxiv.org/abs/2512.00198) |
| HOPPR EB Mammo | HOPPR EB 2D Mammography Foundation Model | ViT-based 2D mammography foundation model trained via self-supervised learning and expert distillation for diverse breast imaging downstream tasks. | [Industry Release](https://www.hoppr.ai/build/ai-foundry) |
| OMAFound | A Foundation Model for Breast and Lung Cancer Screening Using Non-contrast CT | Multi-cancer screening foundation model trained on 325K CT volumes from 151K+ patients for simultaneous breast and lung cancer detection from non-contrast CT. | [Nature Health](https://doi.org/10.1038/s44360-026-00055-8) |

---

<a id="medicine-section-14"></a>
## Musculoskeletal Imaging

*Foundation models for musculoskeletal X-ray and MRI analysis, supporting orthopedic disease diagnosis, joint pathology detection, and multi-anatomy assessment.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OrthoFoundation | A Multimodal Vision Foundation Model for Generalizable Knee Pathology | Multimodal orthopedic vision foundation model trained on 1.2M unlabeled knee X-ray and MRI images via self-supervised contrastive learning for generalizable knee pathology assessment. | [arXiv](https://arxiv.org/abs/2601.18250) |
| OrthoDiffusion | OrthoDiffusion: A Generalizable Multi-Task Diffusion Foundation Model for Musculoskeletal MRI Interpretation | Diffusion-based multi-task foundation model for musculoskeletal MRI trained on ~16,000 unlabeled knee MRIs, supporting segmentation and classification. | [arXiv](https://arxiv.org/abs/2602.20752) |
| XR-0 | Multi Anatomy X-Ray Foundation Model | Self-supervised multi-anatomy X-ray foundation model trained on 1.15M X-ray images spanning multiple anatomical regions including musculoskeletal structures. | [arXiv](https://arxiv.org/abs/2509.12146) |

---

<a id="medicine-section-15"></a>
## Wearable & Digital Health

*Foundation models for wearable sensor data (accelerometer, PPG, ECG, etc.), supporting health monitoring, activity recognition, and clinical prediction from continuous physiological signals.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LSM | Scaling Wearable Foundation Models | Google's large-scale multimodal wearable foundation model trained on >40M hours of per-minute data from 165K+ individuals for health prediction tasks. | [ICLR](https://openreview.net/forum?id=yb4QE6b22f) |
| LSM-2 | LSM-2: Learning from Incomplete Wearable Sensor Data | Upgraded LSM using Adaptive and Inherited Masking (AIM) to learn directly from incomplete wearable sensor data without imputation. | [ICLR](https://arxiv.org/abs/2506.05321) |
| NormWear | Toward Foundation Model for Multivariate Wearable Sensing of Physiological Signals | First multi-modal wearable foundation model for physiological signals (PPG, ECG, EEG, GSR, IMU) using channel-aware attention mechanisms. | [ACM HEALTH](https://doi.org/10.1145/3803808) |
| SensorLM | SensorLM: Learning the Language of Wearable Sensors | Sensor-language foundation model trained on ~60M hours of wearable data from 103K+ individuals, translating sensor signals into natural language descriptions. | [NeurIPS](https://arxiv.org/abs/2506.09108) |
| WAX-FM | Wearable Accelerometer Foundation Models for Health via Knowledge Distillation | Apple-developed wearable accelerometer foundation model using PPG-to-accelerometer knowledge distillation, trained on 20M minutes of unlabeled data. | [arXiv](https://arxiv.org/abs/2412.11276) |

---

<a id="medicine-section-16"></a>
## Radiation Therapy

*Foundation models and AI systems for automating radiation therapy planning, including target delineation, dose prediction, and treatment plan optimization.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|

---

<a id="medicine-section-17"></a>
## Microscopy

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
## Sleep Medicine

*Foundation models for polysomnography (PSG) and sleep data analysis, supporting automated sleep staging, respiratory event detection, and sleep disorder diagnosis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SleepFM | SleepFM: A Multi-Modal Foundation Model for Sleep Medicine | Multimodal sleep foundation model pretrained on large-scale PSG data, integrating EEG, ECG, and respiratory signals for sleep staging and disease prediction. | [Nature Medicine](https://doi.org/10.1038/s41591-025-04133-4) |

---

<a id="medicine-section-19"></a>
## Veterinary Medicine

*Foundation models for veterinary medical imaging and clinical data analysis, supporting animal disease diagnosis and anatomical understanding.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| VET-DINO | VET-DINO: Learning Anatomical Understanding Through Multi-View Distillation in Veterinary Imaging | Self-supervised veterinary imaging foundation model using multi-view radiograph knowledge distillation for robust anatomical representation learning. | [arXiv](https://arxiv.org/abs/2505.15248) |

---

<a id="medicine-section-20"></a>
## Forensic Science

*Foundation models for forensic pathology and forensic identification, supporting cause-of-death determination and injury classification.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SongCi | Large-vocabulary Forensic Pathological Analyses via Prototypical Cross-modal Contrastive Learning | Vision-language foundation model for forensic pathology using prototypical cross-modal contrastive learning on gross findings and whole-slide images. | [Nature Communications](https://doi.org/10.1038/s41467-025-62060-x) |
