# Agriculture & Ecology

<p align="right"><strong>Language:</strong> English | <a href="agriculture-ecology_zh.md">Chinese</a></p>

> Crop science, plant phenotyping, remote sensing for agriculture, biodiversity, wildlife, and related agriculture and ecology foundation models.
> [Index](../README.md)
> Curation note: pure datasets, benchmarks, challenges, libraries, and product-only release pages are excluded; a few adjacent precursor models remain where scientific FM boundaries are still unsettled.

## Table of Contents
- [Agricultural AI Foundation Models](#agriculture-ecology-section-01)
- [Ecology & Biodiversity AI Foundation Models](#agriculture-ecology-section-02)
- [Related Remote Sensing Foundation Models](#agriculture-ecology-section-03)

<a id="agriculture-ecology-section-01"></a>
## Agricultural AI Foundation Models
*Foundation models for crop detection, plant disease identification, agricultural remote sensing, precision farming, and livestock management.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AgriGPT | AgriGPT: A Strong Plant Disease Detection Model via Visual Instruction Tuning | A multimodal AI model integrating visual and text data for precise plant disease detection and crop health assessment. | [Springer](https://doi.org/10.1007/978-981-96-9921-6_20) |
| AgroGPT | AgroGPT: Efficient Agricultural Vision-Language Model with Expert Tuning | An agriculture-specific vision-language model trained via expert tuning on 70,000 images from the AgroInstruct dataset for crop disease dialogue. | [WACV](https://doi.org/10.1109/WACV61041.2025.00555) |
| IPM-AgriGPT | IPM-AgriGPT: A Large Language Model for Pest and Disease Management with a G-EA Framework | A large language model for integrated pest and disease management using agricultural context reasoning via the G-EA framework. | [Mathematics](https://doi.org/10.3390/math13040566) |
| AgriGPT-Omni | AgriGPT-Omni: A Unified Speech-Vision-Text Framework for Multilingual Agricultural Intelligence | A unified speech-vision-text multilingual agricultural AI framework by Zhejiang University. | [arXiv](https://arxiv.org/abs/2512.10624) |
| AgriFM | AgriFM: A Multi-source Temporal Remote Sensing Foundation Model for Crop Mapping | A multi-source temporal remote sensing foundation model integrating MODIS/Landsat/Sentinel-2 satellite data with an improved Video Swin Transformer for crop mapping. | [arXiv](https://arxiv.org/abs/2505.21357) |
| CropSTS | CropSTS: A Remote Sensing Foundation Model for Cropland Classification with Decoupled Spatiotemporal Attention | A crop classification remote sensing foundation model using decoupled spatiotemporal attention to address blurry field boundaries and limited temporal modeling. | [Remote Sensing](https://doi.org/10.3390/rs17142481) |
| AlphaEarth Foundation | Evaluating Geospatial Foundation Models for Agricultural Applications | A geospatial foundation model trained on multi-source earth observation data evaluated for agricultural applications including crop yield prediction. | [arXiv](https://arxiv.org/abs/2601.00857) |
| VITA | VITA: Variational Pretraining of Transformers for Climate-Robust Crop Yield Forecasting | A variational Transformer model for crop yield prediction combining temporal remote sensing and environmental data. | [arXiv](https://arxiv.org/abs/2508.03589) |
| AQUA | AQUA: A Large Language Model for Aquaculture and Fisheries | The first large language model for aquaculture and fisheries covering farming management, disease diagnosis, and domain knowledge. | [arXiv](https://arxiv.org/abs/2507.20520) |
| FoMo4Wheat | FoMo4Wheat: Toward Reliable Crop Vision Foundation Models | A wheat phenotyping foundation model for reliable crop vision analysis developed by the PheniX-Lab. | [arXiv](https://arxiv.org/abs/2509.06907) |
| SPROUT | SPROUT: Scalable Diffusion Foundation Model for Agricultural Vision | A scalable diffusion-based pre-trained foundation model for diverse agricultural vision tasks. | [arXiv](https://arxiv.org/abs/2603.27519) |

---

<a id="agriculture-ecology-section-02"></a>
## Ecology & Biodiversity AI Foundation Models
*Foundation models for wildlife identification, species distribution modeling, bioacoustics, and biodiversity monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SpeciesNet | SpeciesNet: Open-Source AI Model for Wildlife Species Identification | An open-source AI model by Google identifying nearly 2,500 wildlife species, trained on 65 million camera trap images for biodiversity monitoring. | [GitHub](https://github.com/google/cameratrapai) |
| BioAnalyst | BioAnalyst: A Foundation Model for Biodiversity | The first multimodal biodiversity foundation model integrating species records, remote sensing, and climate data for European conservation planning. | [NeurIPS](https://arxiv.org/abs/2507.09080) |
| NatureLM-audio | NatureLM-audio: An Audio-Language Foundation Model for Bioacoustics | The first large-scale bioacoustic audio-language foundation model supporting zero-shot species classification and sound description for ecological monitoring. | [arXiv](https://arxiv.org/abs/2411.07186) |
| Tighnari | Tighnari: Multi-modal Plant Species Prediction Based on Hierarchical Cross-Attention | A multimodal plant species prediction model integrating satellite imagery, climate time-series, land cover, and soil variables for spatiotemporal distribution prediction. | [arXiv](https://arxiv.org/abs/2501.02649) |
| Tighnari v2 | Tighnari v2: Mitigating Label Noise and Distribution Shift in Multi-modal Plant Species Prediction | An upgraded Tighnari addressing noisy labels and distribution shift for more robust plant species distribution prediction. | [arXiv](https://arxiv.org/abs/2602.08282) |
| BirdNET | BirdNET: A Deep Learning Solution for Avian Diversity Monitoring | A deep learning bird sound recognition model by Cornell Lab of Ornithology supporting 6,500+ species (V3.0: 11,000+), widely used for ecological acoustic monitoring. | [Cornell Lab](https://doi.org/10.1016/j.ecoinf.2021.101236) |
| NicheFlow | NicheFlow: A Generative Foundation Model for Species Distribution Modeling | The first generative flow matching-based foundation model for species distribution modeling, learning continuous environment-species relationships. | [bioRxiv Preprint](https://www.biorxiv.org/content/10.1101/2024.10.15.618541) |
| EcoCast | EcoCast: A Spatio-Temporal Model for Continual Biodiversity and Climate Risk Forecasting | A spatio-temporal model for continual biodiversity and climate risk forecasting for ecosystem health assessment. | [NeurIPS Workshop](https://arxiv.org/abs/2512.02260) |
| MiTREE | MiTREE: Multi-input Transformer Ecoregion Encoder for Species Distribution Modelling | A multi-input Transformer model for species distribution estimation integrating multi-source environmental and remote sensing data. | [arXiv](https://arxiv.org/abs/2412.18995) |
| Granite-Geospatial-Ocean | Granite Geospatial Ocean: IBM Foundation Model for Ocean Monitoring | A geospatial foundation model by IBM Research based on the Granite series for ocean environmental change detection and prediction. | [arXiv](https://arxiv.org/abs/2509.21273) |
| OceanSAR | OceanSAR: SAR Ocean Observation Foundation Model | A SAR ocean observation foundation model specializing in sea surface monitoring, ship detection, and marine environment analysis. | [arXiv](https://arxiv.org/abs/2601.07392) |
| SatBird | SatBird: Bird Species Distribution Modeling with Remote Sensing and Citizen Science Data | A bird species distribution model combining satellite imagery with eBird citizen science data for avian ecology. | [NeurIPS](https://doi.org/10.52202/075280-3317) |
| Insect-Foundation | Insect-Foundation: A Foundation Model for Visual Insect Understanding | A visual insect understanding foundation model trained on 1 million insect images for automated entomological analysis. | [CVPR](https://doi.org/10.1109/CVPR52733.2024.02072) |
| Atlantes | Atlantes: GPS Transformers for Global-Scale Maritime Intelligence | A GPS Transformer model by Allen AI for global-scale maritime vessel behavior analysis and intelligence. | [arXiv](https://arxiv.org/abs/2504.19036) |

---

<a id="agriculture-ecology-section-03"></a>
## Related Remote Sensing Foundation Models
*Multi-modal remote sensing models with direct applications to agricultural and ecological monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SkySense++ | SkySense++: A Semantic-Enhanced Multi-Modal Remote Sensing Foundation Model for Earth Observation | A semantic-enhanced multimodal remote sensing foundation model trained on 27 million remote sensing samples supporting agricultural mapping and diverse earth observation tasks. | [Nature Machine Intelligence](https://doi.org/10.1038/s42256-025-01078-8) |
| SkySense V2 | SkySense V2: A Unified Foundation Model for Multi-modal Remote Sensing | A unified multimodal remote sensing foundation model with a single Transformer backbone processing multiple remote sensing modalities. | [ICCV](https://arxiv.org/abs/2507.13812) |
