# Breast Cancer Biomarkers: Survival Analysis and Modeling [![DOI](https://zenodo.org/badge/986749058.svg)](https://doi.org/10.5281/zenodo.15468985)

This repository contains all code, manuscript source, and reproducible outputs for:

**"Breast Cancer Biomarkers in Population Survival Analysis and Modeling"**  
by Zachary D. Rife, Liberty University (Independent Study)

---

## Overview

This study investigates population-level breast cancer data to identify and evaluate key prognostic biomarkers. The modeling framework includes:

- Kaplan–Meier survival estimation
- Stratified log-rank testing
- Multivariate Cox proportional hazards modeling
- Time-stratified risk profiling
- Subgroup progression speed analysis
- Forecasting survivability through regression modeling

All statistical methods are documented with symbolic math, visualizations in PGFPlots, and reproducible code in both R and SAS Clinical Trial Programming.

---

## Code Overview

### `code/survival_models.R`
- Cleans and encodes variables
- Performs survival analysis and modeling
- Computes stratified and time-interval Cox models
- Produces LaTeX-ready output for KM and HR visualizations

### `code/clinical_programming.sas`
- Executes PROC PHREG for Cox regression
- Mirrors R-based model outputs
- Complies with clinical reporting standards

---

## Repository Structure

    breast-cancer-biomarkers/
    ├── manuscript/
    │   ├── manuscript.tex              # Full LaTeX source
    │   ├── manuscript.pdf              # Compiled PDF version
    ├── code/
    │   ├── survival_models.R           # R survival analysis and modeling
    │   ├── clinical_programming.sas    # SAS clinical trial programming
    ├── figures/
    │   ├── KM_plot.tex                 # Kaplan–Meier LaTeX figure
    │   ├── cox_HR_plot.tex             # Cox model hazard ratio barplot
    │   ├── forecast_plot.tex           # Survival forecast regression figure
    ├── appendix/
    │   ├── R_output.txt                # R model outputs for reproducibility
    │   ├── SAS_output.txt              # SAS output logs
    ├── LICENSE                         # MIT License file
    └── README.md                       # This file

    ---

## Citation

Zachary D. Rife. (2025). *Breast Cancer Biomarkers in Population Survival Analysis and Modeling*.  
GitHub repository: [https://github.com/zdrife/breast-cancer-biomarkers](https://github.com/zdrife/breast-cancer-biomarkers)  
DOI: [https://doi.org/10.5281/zenodo.15468986](https://doi.org/10.5281/zenodo.15468986)

**Dataset source:**  
Namdari, R. (2021). *Breast Cancer Dataset*. Kaggle.  
[https://www.kaggle.com/datasets/reihanenamdari/breast-cancer](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer)

---

## Author

**Zachary D. Rife**  
Computational Mathematics and Applied Statistics  
Liberty University  
[ORCID: 0009-0002-1156-7064](https://orcid.org/0009-0002-1156-7064)

> *This research was conducted independently and is not sponsored or endorsed by Liberty University.*

---

## License

This project is licensed under the MIT License (see the `LICENSE` file for terms).  
It is intended for academic, non-commercial use only.
