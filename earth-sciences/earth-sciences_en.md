# Earth Sciences

<p align="right"><strong>Language:</strong> English | <a href="earth-sciences_zh.md">中文</a></p>

> Weather and climate, remote sensing, hydrology, wildfire, seismology, ocean science, air quality, and related earth science foundation models.
> [Index](../README.md)

## Table of Contents
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
## Weather & Climate
*Foundation models for global weather forecasting and climate prediction at various spatial and temporal scales.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Aurora | Aurora: A Foundation Model of the Earth System | A large-scale earth system foundation model by Microsoft trained on over one million hours of multi-source geophysical data for atmosphere, ocean, and air quality prediction. | [Nature](https://arxiv.org/abs/2405.13063) |
| Pangu-Weather | Accurate Medium-range Global Weather Forecasting with 3D Neural Networks | A 3D high-resolution AI weather forecasting model by Huawei trained on 43 years of ERA5 reanalysis data, generating 10-day global forecasts in seconds. | [Nature](https://arxiv.org/abs/2211.02556) |
| GraphCast | Learning Skillful Medium-range Global Weather Forecasting | A graph neural network-based global medium-range weather forecasting model by Google DeepMind at 0.25° resolution, outperforming ECMWF HRES for 10-day forecasts. | [Science](https://arxiv.org/abs/2212.12794) |
| GenCast | GenCast: Diffusion-based Ensemble Forecasting for Medium-range Weather | A diffusion-based ensemble weather forecasting system by Google DeepMind generating probabilistic 15-day forecasts that surpass ECMWF ENS. | [Nature](https://arxiv.org/abs/2312.15796) |
| ClimaX | ClimaX: A Foundation Model for Weather and Climate | The first weather and climate foundation model based on Transformer architecture supporting flexible fine-tuning for multiple downstream meteorological tasks. | [ICML 2023](https://arxiv.org/abs/2301.10343) |
| FengWu | FengWu: Pushing the Skillful Global Medium-range Weather Forecast beyond 10 Days Lead | A multi-modal multi-task weather forecasting system by Shanghai AI Lab that extends deterministic forecast skill to 10.75 days. | [Nature Communications](https://arxiv.org/abs/2304.02948) |
| FuXi | FuXi: A Cascade Machine Learning Forecasting System for 15-day Global Weather Forecast | A cascade machine learning weather forecasting system trained on 39 years of ERA5 data, achieving 15-day forecast performance comparable to ECMWF ensemble mean. | [npj Climate and Atmospheric Science](https://arxiv.org/abs/2306.12873) |
| NeuralGCM | Neural General Circulation Models for Weather and Climate | A neural GCM by Google Research combining differentiable atmospheric dynamics solvers with machine learning for weather-to-climate timescale prediction. | [Nature](https://arxiv.org/abs/2311.07222) |
| FourCastNet | FourCastNet: A Global Data-driven High-resolution Weather Forecasting System | A high-resolution global weather forecasting model by NVIDIA using adaptive Fourier neural operators (AFNO) at 0.25° resolution. | [arXiv](https://arxiv.org/abs/2202.11214) |
| ECMWF AIFS | AIFS — ECMWF's Data-driven Forecasting System | ECMWF's operational AI forecasting system combining graph neural networks and Transformers for data-driven weather prediction. | [arXiv](https://arxiv.org/abs/2406.01465) |
| Stormer | Scaling Transformer Neural Networks for Skillful and Reliable Medium-range Weather Forecasting | A streamlined and efficient Transformer weather forecasting model achieving state-of-the-art performance with less training data. | [arXiv](https://arxiv.org/abs/2312.03876) |
| AtmoRep | AtmoRep: A Stochastic Model of Atmosphere Dynamics Using Large Scale Representation Learning | A task-agnostic atmospheric foundation model based on large-scale representation learning for stochastic atmosphere dynamics. | [arXiv](https://arxiv.org/abs/2308.13280) |
| SkyGPT | SkyGPT: Probabilistic Short-term Solar Forecasting Using Synthetic Sky Videos from Physics-constrained VideoGPT | A physics-constrained probabilistic short-term solar irradiance forecasting model using synthetic sky image video prediction. | [Advances in Applied Energy](https://arxiv.org/abs/2306.11682) |
| WeatherGFT | WeatherGFT: Generalizing Weather Forecast to Fine-grained Temporal Scales via Physics-AI Hybrid Modeling | A hybrid physics-AI weather forecasting model extending predictions to finer temporal resolutions at 30-minute intervals. | [NeurIPS 2024](https://arxiv.org/abs/2405.13796) |
| WeatherGFM | WeatherGFM: Learning A Weather Generalist Foundation Model via In-context Learning | A weather generalist foundation model unifying forecasting, super-resolution, image translation, and post-processing via in-context learning. | [ICLR 2025](https://arxiv.org/abs/2411.05420) |
| Prithvi WxC | Prithvi WxC: Foundation Model for Weather and Climate | A 2.3-billion-parameter weather and climate foundation model by IBM and NASA trained on 160 MERRA-2 variables. | [arXiv](https://arxiv.org/abs/2409.13598) |
| FuXi-2.0 | FuXi-2.0: Advancing Machine Learning Weather Forecasting Model for Practical Applications | An upgraded version of FuXi providing hourly global forecasts with a more comprehensive set of meteorological variables. | [arXiv](https://arxiv.org/abs/2409.07188) |
| ArchesWeather | ArchesWeather: An Efficient AI Weather Forecasting Model at 1.5° Resolution | A lightweight and efficient AI weather forecasting model at 1.5° resolution using a combination of 2D and column-wise attention. | [arXiv](https://arxiv.org/abs/2405.14527) |
| W-MAE | W-MAE: Pre-trained Weather Model with Masked Autoencoder | A task-agnostic atmospheric foundation model based on masked autoencoder pre-training for weather data. | [arXiv](https://arxiv.org/abs/2304.08754) |
| WeatherNext 2 | WeatherNext 2: Google DeepMind's Most Advanced Forecasting Model | Google DeepMind's most advanced high-resolution ensemble weather forecasting model for operational-scale predictions. | [Google DeepMind](https://blog.google/technology/google-deepmind/weathernext-2/) |
| Omni-Weather | Omni-Weather: Unified Multimodal Foundation Model for Weather Generation and Understanding | A unified multimodal foundation model integrating radar, satellite, and numerical data for weather generation and understanding. | [arXiv](https://arxiv.org/abs/2512.21643) |

---

<a id="earth-sciences-section-02"></a>
## Remote Sensing
*Foundation models for satellite imagery analysis, multi-spectral and multi-temporal earth observation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Prithvi-EO-2.0 | Prithvi-EO-2.0: A Versatile Multi-Temporal Foundation Model for Earth Observation Applications | A multi-temporal earth observation foundation model by NASA/IBM trained on 4.2 million global time-series samples supporting Landsat and Sentinel-2. | [arXiv](https://arxiv.org/abs/2412.02732) |
| SpectralGPT | SpectralGPT: Spectral Remote Sensing Foundation Model | The first spectral remote sensing foundation model using a 3D generative pre-trained Transformer designed for multi-spectral and hyperspectral satellite imagery. | [IEEE TPAMI](https://arxiv.org/abs/2311.07113) |
| SatMAE | SatMAE: Pre-training Transformers for Temporal and Multi-Spectral Satellite Imagery | A masked autoencoder pre-training framework for temporal and multi-spectral satellite imagery. | [NeurIPS 2022](https://arxiv.org/abs/2207.08051) |
| SeaMo | SeaMo: A Multi-Seasonal and Multimodal Remote Sensing Foundation Model | A multi-seasonal multimodal remote sensing foundation model fusing optical, SAR, and meteorological data. | [arXiv](https://arxiv.org/abs/2412.19237) |
| TerraMind | TerraMind: Large-Scale Generative Multimodality for Earth Observation | A large-scale generative multimodal earth observation foundation model by IBM/ESA/DLR trained on 500 billion tokens. | [ICCV 2025](https://arxiv.org/abs/2504.11171) |
| RingMo | RingMo: A Remote Sensing Foundation Model with Masked Image Modeling | A remote sensing foundation model by the Chinese Academy of Sciences using masked image modeling for large-scale pre-training. | [IEEE TGRS](https://doi.org/10.1109/TGRS.2022.3194732) |
| SatCLIP | SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery | A global general-purpose location encoder by Microsoft using Sentinel-2 contrastive learning to generate location embeddings. | [AAAI 2025](https://arxiv.org/abs/2311.17179) |
| Clay Foundation Model | Clay: An Open Source AI Model for Earth | An open-source earth observation foundation model based on masked autoencoder architecture supporting Sentinel-1/2 and DEM data. | [开源项目](https://clay-foundation.github.io/model/) |
| SkySense | SkySense: A Multi-Modal Remote Sensing Foundation Model Towards Universal Interpretation for Earth Observation Imagery | A large-scale multimodal remote sensing foundation model pre-trained on 21.5 million temporal optical and SAR data samples. | [CVPR 2024](https://arxiv.org/abs/2312.10115) |
| Scale-MAE | Scale-MAE: A Scale-Aware Masked Autoencoder for Multiscale Geospatial Representation Learning | A scale-aware masked autoencoder that explicitly models spatial resolution relationships for multiscale geospatial representation learning. | [ICCV 2023](https://arxiv.org/abs/2212.14532) |
| RSPrompter | RSPrompter: Learning to Prompt for Remote Sensing Instance Segmentation | A SAM-based prompt learning method for remote sensing instance segmentation adapting vision foundation models to remote sensing. | [IEEE TGRS](https://arxiv.org/abs/2306.16269) |
| ChangeFormer | ChangeFormer: A Transformer-Based Siamese Network for Change Detection | A Transformer-based siamese network for remote sensing change detection. | [IGARSS 2022](https://arxiv.org/abs/2201.01293) |
| DOFA | Neural Plasticity-Inspired Multimodal Foundation Model for Earth Observation | A neural plasticity-inspired multimodal EO foundation model using dynamic wavelength-adaptive hypernetworks to handle diverse sensor data. | [arXiv](https://arxiv.org/abs/2403.15356) |
| GFM (Prithvi-EO-1.0) | Foundation Models for Generalist Geospatial Artificial Intelligence | NASA/IBM's first-generation earth science foundation model based on self-supervised Vision Transformers trained on HLS data. | [arXiv](https://arxiv.org/abs/2310.18660) |
| S2MAE | S2MAE: A Spatial-Spectral Pretraining Foundation Model for Spectral Remote Sensing Image | A spatial-spectral masked autoencoder providing joint spatial-spectral pre-training for spectral remote sensing imagery. | [CVPR 2024](https://openaccess.thecvf.com/content/CVPR2024/html/Li_S2MAE_A_Spatial-Spectral_Pretraining_Foundation_Model_for_Spectral_Remote_Sensing_Data_CVPR_2024_paper.html) |
| RingMoE | RingMoE: Mixture-of-Modality-Experts Multi-Modal Foundation Models for Universal Remote Sensing Image Interpretation | A 14.7-billion-parameter mixture-of-modality-experts remote sensing foundation model pre-trained on 400M+ samples. | [arXiv](https://arxiv.org/abs/2504.03166) |
| WaveMAE | WaveMAE: Wavelet-decomposition Masked Autoencoder for Multispectral Satellite Imagery | A self-supervised foundation model combining wavelet decomposition with geospatial priors for multispectral satellite imagery. | [arXiv](https://arxiv.org/abs/2510.22697) |
| RoMA | RoMA: Scaling up Mamba-based Foundation Models for Remote Sensing | A scalable Mamba-architecture remote sensing foundation model addressing ViT limitations in large-scale remote sensing pre-training. | [NeurIPS 2025](https://arxiv.org/abs/2503.10392) |
| CROMA | CROMA: Contrastive Radar-Optical Masked Autoencoders for Remote Sensing | A contrastive radar-optical masked autoencoder for multimodal remote sensing representation learning. | [NeurIPS 2024](https://arxiv.org/abs/2311.00566) |
| SSL4EO | SSL4EO: Self-Supervised Learning for Earth Observation | A large-scale self-supervised learning benchmark and pre-trained model for earth observation. | [IEEE TGRS](https://doi.org/10.1109/TGRS.2023.3251668) |
| SatLAS | SatLAS: A Large-Scale Satellite Image Dataset with Automatic Labels | A dataset of 137 million labeled satellite images with pre-trained Swin Transformer models for diverse geospatial tasks. | [ICCV 2023](https://arxiv.org/abs/2211.15660) |
| AnySat | AnySat: One Earth Observation Model for Many Resolutions, Scales, and Modalities | A unified multi-resolution multimodal earth observation model using JEPA architecture for diverse EO tasks. | [CVPR 2025](https://arxiv.org/abs/2412.14123) |
| TerraFM | TerraFM: A Scalable Foundation Model for Unified Multisensor Earth Observation | A scalable self-supervised foundation model for unified multisensor earth observation pre-trained on 18.7 million samples. | [ICLR 2026](https://openreview.net/forum?id=cBxuzdUDNx) |

---

<a id="earth-sciences-section-03"></a>
## Oceanography
*Foundation models for ocean forecasting, eddy-resolving prediction, and marine environment monitoring.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OceanGPT | OceanGPT: A Large Language Model for Ocean Science Tasks | A domain-specific large language model for ocean science by Zhejiang University using the DoInstruct framework for ocean domain instruction data. | [ACL 2024](https://arxiv.org/abs/2310.02031) |
| XiHe | XiHe: A Data-Driven Model for Global Ocean Eddy-Resolving Forecasting | A data-driven global ocean eddy-resolving forecast model at 1/12° resolution trained on 25 years of reanalysis data. | [arXiv](https://arxiv.org/abs/2402.02995) |
| WV-Net | WV-Net: A Foundation Model for SAR WV-mode Satellite Imagery Trained Using Contrastive Self-supervised Learning | The first foundation model for SAR ocean satellite imagery using self-supervised contrastive learning on synthetic aperture radar data. | [arXiv](https://arxiv.org/abs/2406.18765) |
| GLONET | GLONET: Mercator's End-to-End Neural Global Ocean Forecasting System | An end-to-end neural network global ocean forecasting system by Mercator Ocean trained on GLORYS12 reanalysis data. | [arXiv](https://arxiv.org/abs/2412.05454) |
| WenHai | Forecasting the Eddying Ocean with a Deep Neural Network | A deep neural network ocean forecasting system excelling at mesoscale eddy dynamics prediction. | [Nature Communications](https://doi.org/10.1038/s41467-025-57389-2) |
| FuXi-Ocean | FuXi-Ocean: A Global Ocean Forecasting System with Sub-Daily Resolution | A data-driven global ocean forecasting system with 6-hour temporal and 1/12° spatial resolution reaching 1500-meter depth. | [NeurIPS 2025](https://arxiv.org/abs/2506.03210) |
| OceanCastNet | Ocean Wave Forecasting with Deep Learning as Alternative to Physical Models | A deep learning ocean wave forecasting model that can replace the traditional physical model ECWAM. | [JAMES](https://arxiv.org/abs/2406.03848) |
| ORCA-DL | Data-driven Global Ocean Modeling for Seasonal to Decadal Prediction | A data-driven global ocean model supporting 3D ocean predictions from seasonal to decadal timescales. | [arXiv](https://arxiv.org/abs/2405.15412) |
| FuXi-ONS | Data-driven Ensemble Prediction of the Global Ocean | A machine-learning ensemble global ocean forecasting system for 5-to-365-day predictions. | [arXiv](https://arxiv.org/abs/2603.19591) |

---

<a id="earth-sciences-section-04"></a>
## Seismology
*Foundation models for earthquake detection, seismic phase picking, and waveform analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PhaseNet | PhaseNet: A Deep-Neural-Network-Based Seismic Arrival-Time Picking Method | One of the most widely used deep learning models for seismic arrival-time picking in seismology. | [Geophysical Journal International](https://doi.org/10.1093/gji/ggy423) |
| EQTransformer | EQTransformer: An Attentive Deep-Learning Model for Simultaneous Earthquake Detection and Phase Picking | An attention-based deep learning model for simultaneous earthquake detection and seismic phase picking. | [Nature Communications](https://doi.org/10.1038/s41467-020-17591-w) |
| SeisT | SeisT: A Foundational Deep Learning Model for Earthquake Monitoring Tasks | A Transformer-based seismic monitoring foundation model supporting multiple earthquake tasks including detection, phase picking, and magnitude estimation. | [IEEE TGRS](https://arxiv.org/abs/2310.01037) |
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
## Hydrology
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
## Wildfire Prediction
*Models for wildfire danger forecasting and fire spread prediction.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FireCastNet | FireCastNet: Earth-as-a-Graph for Seasonal Fire Prediction | A deep learning global wildfire danger forecasting model fusing meteorological, vegetation, and terrain data for multi-timescale prediction. | [Scientific Reports](https://doi.org/10.1038/s41598-025-30645-7) |
| FireScope | FireScope: Wildfire Risk Prediction with a Chain-of-Thought Oracle | A wildfire risk prediction foundation model and benchmark using multi-modal data for fire risk assessment. | [arXiv](https://arxiv.org/abs/2511.17171) |

---

<a id="earth-sciences-section-07"></a>
## Air Quality
*Foundation models for atmospheric pollution forecasting.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AirCast | AirCast: Improving Air Pollution Forecasting Through Multi-Variable Data Alignment | A data-driven air quality forecasting foundation model supporting multi-variable atmospheric pollutant concentration prediction. | [arXiv](https://arxiv.org/abs/2502.17919) |
| FuXi-Air | FuXi-Air: Urban Air Quality Forecasting Based on Emission-Meteorology-Pollutant Multimodal Machine Learning | A multimodal machine learning air quality forecasting extension of the FuXi series integrating emission, meteorological, and observational data. | [arXiv](https://arxiv.org/abs/2506.07616) |

---

<a id="earth-sciences-section-08"></a>
## Cryosphere
*Foundation models for sea ice monitoring and polar region forecasting.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SIFM | SIFM: A Foundation Model for Multi-granularity Arctic Sea Ice Forecasting | A sea ice foundation model for multi-granularity Arctic sea ice concentration forecasting from satellite observations. | [arXiv](https://arxiv.org/abs/2410.14732) |
| IceNet | IceNet: Seasonal Arctic Sea Ice Forecasting with Probabilistic Deep Learning | A probabilistic deep learning model for seasonal Arctic sea ice forecasting that significantly outperforms dynamical physics models. | [Nature Communications](https://doi.org/10.1038/s41467-021-25257-4) |
| IceMamba | IceMamba: Seasonal Forecasting of Pan-Arctic Sea Ice with State Space Model | A Mamba state space model-based sea ice forecasting foundation model efficiently processing polar spatiotemporal sequence data. | [arXiv](https://arxiv.org/abs/2505.10665) |

---

<a id="earth-sciences-section-09"></a>
## Geoscience Language Models
*Large language models specialized for earth science knowledge understanding and reasoning.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| K2 | K2: A Foundation Language Model for Geoscience Knowledge Understanding and Utilization | The first 7-billion-parameter geoscience LLM based on LLaMA, further pre-trained and instruction-tuned on earth science literature. | [arXiv](https://arxiv.org/abs/2306.05064) |
| JiuZhou | JiuZhou: Open Foundation Language Models for Geoscience | A multilingual geoscience LLM by Tsinghua University supporting Chinese and English earth science knowledge QA and reasoning. | [清华大学](https://github.com/THU-ESIS/JiuZhou) |
| GeoGPT | GeoGPT: A Large Language Model for Geospatial Artificial Intelligence | A geospatial AI LLM by Zhejiang Lab combining tool-calling capabilities for geospatial analysis and reasoning. | [之江实验室](https://github.com/GeoGPT-Research-Project/GeoGPT) |
| GeoGalactica | GeoGalactica: A Scientific Large Language Model for Geoscience | A 30-billion-parameter geoscience LLM based on Galactica architecture pre-trained on earth science corpora. | [arXiv](https://arxiv.org/abs/2401.00434) |

---

<a id="earth-sciences-section-10"></a>
## Subsurface & Exploration Geophysics
*Foundation models for subsurface characterization, seismic exploration, and well log analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| Transparent Earth | The Transparent Earth: A Multimodal Foundation Model for the Earth's Subsurface | A multimodal transformer-based foundation model by LANL for subsurface structure imaging and inversion. | [LANL](https://arxiv.org/abs/2509.02783) |
| GEM 3D | Geological Everything Model 3D: A Promptable Foundation Model for Subsurface Understanding | A promptable generative 3D earth model unifying multiple geophysical tasks for subsurface structure modeling and geological property prediction. | [arXiv](https://arxiv.org/abs/2507.00419) |
| SFM-Exploration | Seismic Foundation Model (SFM): A New Generation Deep Learning Model in Geophysics | A Transformer-based self-supervised seismic foundation model for exploration geophysics supporting multiple downstream tasks. | [Geophysics](https://arxiv.org/abs/2309.02791) |
| WLFM | WLFM: A Well-Logs Foundation Model for Multi-Task Subsurface Analysis | A well log foundation model self-supervised pre-trained on large-scale well log data for lithology identification and reservoir prediction. | [arXiv](https://arxiv.org/abs/2509.18152) |

---

<a id="earth-sciences-section-11"></a>
## SAR-Specific Models
*Foundation models specialized for synthetic aperture radar data processing and interpretation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| SARATR-X | SARATR-X: Toward Building A Foundation Model for SAR Target Recognition | A SAR target recognition foundation model pre-trained on large-scale SAR imagery supporting multiple recognition downstream tasks. | [IEEE TGRS](https://arxiv.org/abs/2405.09365) |
| SUMMIT | SUMMIT: A SAR Foundation Model with Multiple Auxiliary Tasks Enhanced Intrinsic Characteristics | A SAR universal multi-task foundation model unifying detection, segmentation, and classification via physics-driven self-supervised learning. | [arXiv](https://www.sciencedirect.com/science/article/pii/S1569843225002717) |
| SAR-W-MixMAE | SAR-W-MixMAE: SAR Foundation Model Training Using Backscatter Power Weighting | A mixed masked autoencoder for SAR image pre-training optimizing speckle noise and geometric feature learning with polarization awareness. | [arXiv](https://arxiv.org/abs/2503.01181) |
| CrossEarth-SAR | CrossEarth: Billion-scale SAR Foundation Model for Domain-Generalizable Segmentation | A billion-scale SAR foundation model for domain-generalizable semantic segmentation across diverse SAR datasets. | [arXiv](https://arxiv.org/abs/2603.12008) |

---

<a id="earth-sciences-section-12"></a>
## Land Use
*Foundation models for land use and land cover mapping.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| LandSegmenter | LandSegmenter: Towards a Flexible Foundation Model for Land Use and Land Cover Segmentation | A flexible land use/land cover segmentation foundation model pre-trained on large-scale multi-source remote sensing data for global LULC mapping. | [arXiv](https://arxiv.org/abs/2511.08156) |

---

<a id="earth-sciences-section-13"></a>
## Climate Downscaling
*Foundation models for high-resolution climate and weather downscaling.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ORBIT-2 | ORBIT-2: Scaling Exascale Vision Transformer for Weather and Climate Downscaling | A climate downscaling foundation model trained on exascale computing infrastructure for efficient high-resolution climate inference. | [SC 2025](https://e3sm.org/best-paper-award-at-sc25-ai-driven-weather-prediction-with-orbit-2/) |
| SR-Weather | SR-Weather: Super-Resolution Framework for Weather Downscaling | A deep learning super-resolution framework downscaling coarse-resolution weather forecasts to kilometer-scale surface air temperature. | [arXiv](https://www.nature.com/articles/s41612-026-01328-5) |
