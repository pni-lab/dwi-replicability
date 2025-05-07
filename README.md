## Replicability of DWI Connectome-Based Brain-Wide Associations (BWAS)

### Overview

This project provides a comprehensive evaluation of the replicability of Brain-Wide Association Studies (BWAS) that are based on diffusion-weighted MRI (DWI) measures. We investigated how consistently associations between various DWI-derived brain metrics (including streamline connectivity, fractional anisotropy, and other tensor metrics) and a wide range of behavioral phenotypes can be replicated in independent samples.

### Methods

* **Data:** Analyses utilized the Human Connectome Project (HCP) dataset (N up to 425 per discovery/replication split, across 58 phenotypes) and the AOMIC dataset (N up to 425, 19 phenotypes) for validating streamline connectivity (SC) models.
* **DWI Metrics:** We assessed replicability for streamline connectivity (SC), fractional anisotropy (FA), radial diffusivity (RD), axial diffusivity (AD), and apparent diffusion coefficient (ADC).
* **Replicability Criteria:** A stringent definition of replicability was used, requiring a model to achieve significant prediction (p<0.05) in an unseen replication sample in over 80% of data shuffles, given a significant discovery set model.

### Key Findings

* Overall, 36% (21 out of 58) of the studied phenotypes demonstrated replicable BWAS in the HCP dataset.
* Trait-like behavioral measures showed higher replicability (50%, 16/32) compared to state-like measures (19%, 5/26).
* Streamline connectivity (SC) based models were found to be the most economical, requiring smaller average discovery sample sizes (n≈171) and showing higher replicable effect sizes.
* SC models successfully replicated 42% of tested phenotypes in the AOMIC validation dataset.
* Exploratory analyses indicated that using higher-resolution atlases could potentially improve replicability.
* SHAP analyses on replicable models identified influential white matter tracts that significantly correlated with their target behavioral measures, underscoring the potential for interpretable DWI-based brain-behavior characterization.

### Implications & Future Directions

This work highlights the critical roles of sample size, choice of connectome/DWI metric, and the nature of the phenotype in achieving replicable DWI-based BWAS.
* For **trait-like phenotypes**, further robust analyses and validation in larger datasets are essential.
* For **state-like phenotypes**, pursuing higher sample sizes and integrating dynamic neuroimaging modalities (e.g., fMRI, EEG, MEG) could be highly beneficial for advancing our understanding, particularly in areas like mental health.

### Data Availability Statement

The Jupyter notebooks containing the analysis code, key methodological information, and processing steps for this study are provided within this repository. These notebooks allow for an understanding of how the main results were generated. The primary processed neuroimaging derivatives (e.g., full subject-level connectome matrices, voxel-wise diffusion metric maps) used in this research are not directly hosted in this repository. 
