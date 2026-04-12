# Astronomy

<p align="right"><strong>Language:</strong> English | <a href="astronomy_zh.md">中文</a></p>

> Multi-modal astronomy, exoplanets, gravitational waves, cosmology, radio astronomy, solar physics, and related astronomical foundation models.
> [Index](../README.md)
> Curation note: pure datasets, benchmarks, challenges, libraries, and product-only release pages are excluded; a few adjacent precursor models remain where scientific FM boundaries are still unsettled.

## Table of Contents
- [Multimodal Astronomy](#astronomy-section-01)
- [Gravitational Wave Science](#astronomy-section-02)
- [Radio Astronomy](#astronomy-section-03)
- [Exoplanet Detection](#astronomy-section-04)
- [Cosmological Simulations](#astronomy-section-05)
- [CMB Analysis](#astronomy-section-06)
- [Survey Classifiers](#astronomy-section-07)
- [Planetary Science](#astronomy-section-08)

<a id="astronomy-section-01"></a>
## Multimodal Astronomy

### Multimodal & Cross-Modal Foundation Models
*Foundation models that integrate multiple astronomical data modalities including imaging, spectra, and scalar measurements.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| AION-1 | AION-1: Omnimodal Foundation Model for Astronomical Sciences | A large-scale omnimodal astronomical foundation model integrating 39 data modalities (imaging, spectra, scalar measurements) covering 200M+ astronomical objects. | [NeurIPS](https://arxiv.org/abs/2510.17960) |
| AstroCLIP | AstroCLIP: a cross-modal foundation model for galaxies | A cross-modal galaxy foundation model using self-supervised contrastive learning to embed galaxy images and spectra into a shared physically meaningful latent space. | [Monthly Notices of the Royal Astronomical Society](https://doi.org/10.1093/mnras/stae1450) |
| AstroLLaMA | AstroLLaMA: Towards Specialized Foundation Models in Astronomy | A 7-billion-parameter astronomy-specialized LLM based on LLaMA-2, fine-tuned on 300K+ astronomical abstracts. | [Proceedings of the Second Workshop on Information Extraction from Scientific Publications](https://arxiv.org/abs/2309.06126) |
| AstroLLaMA-2-70B | AstroMLab 2: AstroLLaMA-2-70B Model and Benchmarking Specialized LLMs for Astronomy | A 70-billion-parameter upgrade of AstroLLaMA providing more powerful domain-specific language understanding for astronomy. | [arXiv](https://arxiv.org/abs/2409.19750) |
| AstroPT | AstroPT: Scaling Large Observation Models for Astronomy | An open-source autoregressive pre-trained Transformer trained on 8.6 million DESI Legacy Survey galaxy images as a scalable large observation model. | [arXiv](https://arxiv.org/abs/2405.14930) |
| astroBERT | astroBERT: A Language Model for Astronomy | A BERT-based language model pre-trained on astrophysics literature for astronomical text mining and NLP tasks. | [arXiv](https://arxiv.org/abs/2112.00590) |

### Spectral Foundation Models
*Models designed for processing and analyzing astronomical spectra across instruments and wavelengths.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| OmniSpectra | OmniSpectra: A Unified Foundation Model for Native Resolution Astronomical Spectra | A unified astronomical spectral foundation model that processes arbitrary-length, any-instrument native-resolution spectra without resampling or interpolation. | [arXiv](https://arxiv.org/abs/2601.15351) |
| SpectraFM | SpectraFM: Tuning into Stellar Foundation Models | A stellar spectral foundation model pre-trained on large-scale stellar spectral data supporting spectral classification and parameter estimation. | [NeurIPS FM4Science Workshop (2024)](https://arxiv.org/abs/2411.04750) |

### Time-Domain Astronomy & Light Curve Models
*Foundation models for astronomical light curve analysis, classification, and time-domain phenomena.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| FALCO | FALCO: Foundation Model of Astronomical Light Curves for Time Domain Astronomy | An astronomical light curve foundation model based on Transformer self-supervised learning trained on Kepler data for multiple time-domain downstream tasks. | [AJ (2026)](https://arxiv.org/abs/2504.20290) |
| Astromer 2 | Astromer 2: Few-shot Light Curve Classification | A self-supervised light curve foundation model pre-trained on 1.5 million MACHO survey light curves supporting few-shot classification. | [A&A (2026)](https://arxiv.org/abs/2502.02717) |
| ASTROMER | ASTROMER: A Transformer-based Embedding for the Representation of Light Curves | The first Transformer-based pre-trained model for astronomical light curve representation, transferable across multiple survey datasets. | [A&A](https://doi.org/10.1051/0004-6361/202243928) |
| AstroCo | ASTROCO: Self-Supervised Conformer-Style Transformers for Light-Curve Embeddings | A self-supervised Conformer-style Transformer encoder for processing irregular stellar light curves. | [arXiv](https://arxiv.org/abs/2509.24134) |

---

<a id="astronomy-section-02"></a>
## Gravitational Wave Science
*Foundation models for gravitational wave detection, parameter estimation, and signal analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| GraviBERT | GraviBERT: Transformer-based inference for gravitational-wave time series | A BERT-style transformer foundation model for gravitational wave signal analysis supporting detection and parameter estimation. | [Machine Learning: Science and Technology](https://arxiv.org/abs/2512.21390) |
| Dingo-T1 | Dingo-T1: Flexible Gravitational-Wave Parameter Estimation with Transformers | A transformer-based foundation model for near real-time gravitational wave posterior parameter estimation. | [NeurIPS ML4PS (2025)](https://arxiv.org/abs/2512.02968) |
| WaveFormer | WaveFormer: transformer-based denoising method for gravitational-wave data | A Transformer-based model for denoising and signal recovery in LIGO gravitational wave interferometer time-series data. | [Machine Learning: Science and Technology](https://arxiv.org/abs/2212.14283) |
| GW-FALCON | GW-FALCON: Feature-driven Deep Learning for Early Gravitational Wave Detection | A feature-driven deep learning model for early-stage gravitational wave detection from interferometer data. | [arXiv](https://arxiv.org/abs/2602.15073) |

---

<a id="astronomy-section-03"></a>
## Radio Astronomy
*Foundation models for radio telescope data analysis, source classification, and morphology.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| RGZ-FM | Radio Galaxy Zoo: Towards Building the First Multi-purpose Foundation Model for Radio Astronomy | The first multi-purpose radio astronomy foundation model pre-trained on Radio Galaxy Zoo data for radio source classification and morphology analysis. | [arXiv](https://arxiv.org/abs/2305.16127) |
| STRADAViT | STRADAViT: Towards a Foundational Model for Radio Astronomy through Self-Supervised Transfer | A self-supervised Vision Transformer foundation model for radio astronomy data handling diverse radio interferometric imaging tasks. | [arXiv](https://arxiv.org/abs/2603.29660) |
| SKATR | SKATR: A Self-Supervised Summary Transformer for SKA Radio Continuum Data | A self-supervised summary Transformer foundation model for SKA radio continuum survey data providing universal feature representations. | [SciPost (2025)](https://arxiv.org/abs/2410.18899) |

---

<a id="astronomy-section-04"></a>
## Exoplanet Detection
*Deep learning models for transit detection and exoplanet validation.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ExoMiner++ | ExoMiner++: Enhanced Transit Classification and a New Vetting Catalog | An improved deep learning model by NASA for exoplanet transit validation with enhanced accuracy and reliability for TESS data. | [The Astronomical Journal](https://doi.org/10.3847/1538-3881/ae03a4) |
| PANOPTICON | PANOPTICON: A Novel Deep Learning Model to Detect Single Transit Events in PLATO Light Curves | A deep learning foundation model for automatic detection of single exoplanet transit events in PLATO light curves without prior data filtering. | [A&A](https://doi.org/10.1051/0004-6361/202452124) |

---

<a id="astronomy-section-05"></a>
## Cosmological Simulations
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
## CMB Analysis
*Deep learning models for cosmic microwave background component separation and analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| PUREPath | PUREPath: A Deep Learning Approach for CMB B-mode Delensing | A deep learning method for CMB B-mode delensing that removes gravitational lensing effects to detect primordial gravitational wave signals. | [arXiv](https://arxiv.org/abs/2503.20774) |
| Deep Needlet | Deep Needlet: a CNN based full sky component separation method in Needlet space | A CNN-based CMB analysis method operating on needlet coefficients for efficient full-sky component separation. | [Journal of Cosmology and Astroparticle Physics](https://doi.org/10.1088/1475-7516/2025/08/058) |

---

<a id="astronomy-section-07"></a>
## Survey Classifiers
*Foundation models for automated classification in large astronomical surveys.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| ORACLE | ORACLE: A Real-time, Hierarchical, Deep Learning Photometric Classifier for the LSST | A real-time hierarchical deep learning classifier for automated transient and variable astrophysical source classification in LSST survey data. | [The Astrophysical Journal](https://doi.org/10.3847/1538-4357/ae1130) |
| SPLASH | SPLASH: A Rapid Host-Based Supernova Classifier for Wide-Field Surveys | A fast host-galaxy-based supernova classifier using only host photometry for rapid type inference in LSST-scale surveys. | [arXiv](https://arxiv.org/abs/2506.00121) |

---

<a id="astronomy-section-08"></a>
## Planetary Science
*Foundation models for planetary remote sensing and orbital data analysis.*

| Model | Paper Title | Description | Link |
|-------|------------|-------------|------|
| MOMO | MOMO: Mars Orbital Model Foundation Model | A multi-sensor Mars orbital remote sensing foundation model for planetary surface analysis. | [arXiv](https://arxiv.org/abs/2604.02719) |
