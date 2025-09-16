# Mapping indicators of cultural ecosystem services use in urban green spaces based on text classification of geosocial media data

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17131841.svg)](https://doi.org/10.5281/zenodo.17131841)


This repository contains supplementary material for the article:  

**Gugulica, M., & Burghardt, D. (2023). Mapping indicators of cultural ecosystem services use in urban green spaces based on text classification of geosocial media data. *Ecosystem Services, 60*, 101508. https://doi.org/10.1016/j.ecoser.2022.101508**  

The material includes Jupyter notebooks, HTML exports for easy browsing, and a conda environment file to reproduce the computational workflow described in the study.  

---

## Repository Contents  

- **Notebooks (HTML and IPYNB)**  
  - `S1_GSM_Data_Processing&LanguageModelTraining.ipynb` / `.html`  
    Data preprocessing of geosocial media (GSM) textual metadata, including text normalization, language detection, and training of word embedding models.  

  - `S2_GSM_Data_TextClassification.ipynb` / `.html`  
    Unsupervised text classification workflow to detect GSM posts related to aesthetic appreciation and wildlife recreation. Includes similarity computation, thresholding, and validation metrics.  

  - `S3_Generate_ChiValueExpectationSurface.ipynb` / `.html`  
    Spatial analysis workflow for computing chi expectation surfaces and mapping over- and under-representation of cultural ecosystem service flows in urban green spaces.  

- **Environment file**  
  - `environment.yml` — contains all dependencies required to run the notebooks in a reproducible Python environment.  

---

## How to Use  

### Option 1: View Only  
Open the `.html` versions of the notebooks directly in any web browser (no installation required).  

### Option 2: Reproduce the Workflow  
Clone this repository and open the Jupyter Notebooks in Jupyter Lab  
   ```bash
   conda env create -f nlp_environment.yml
   conda activate nlp_env
   jupyterlab
```
---

## Citation  

If you use the notebooks or build upon this workflow, please cite the original article:  

> Gugulica, M., & Burghardt, D. (2023). *Mapping indicators of cultural ecosystem services use in urban green spaces based on text classification of geosocial media data*. Ecosystem Services, 60, 101508. https://doi.org/10.1016/j.ecoser.2022.101508  

If you use the code or supplementary material from this repository, please cite:  

> Gugulica, M. (2025). *Mapping CES Indicators — Supplementary Material* [Code and data]. Zenodo. https://doi.org/10.5281/zenodo.17131841  

   

