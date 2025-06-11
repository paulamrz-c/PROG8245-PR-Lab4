# PROG8245-PR-Lab4 - Tidying, Cleaning, Imputation, and Outlier Detection

Welcome to my repository for the lab Tidying, Cleaning, Imputation, and Outlier Detection.

This repo contains:

### - The jupyter notebook 
The notebook `PROG8245_Lab4_Data_Cleaning_Imputation_Outlier.ipynb`  implementing:

- Tidying with PEW Research Dataset

- Cleaning and Tidying with Billboard Dataset

- Data Cleaning (Cars Dataset)

- Outlier Detection (Diabetes Dataset)

### HTML Export (for GitHub Pages)
You can view the published notebook [here](https://paulamrz-c.github.io/PROG8245-PR-Lab4/PROG8245_Lab4_Data_Cleaning_Imputation_Outlier.html)

## Quick Start

```bash
python -m venv venv-PR-Lab4
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv-PR-Lab4\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python PR (venv)"
jupyter notebook

```
## Data-sources

- Scikit-learn Diabetes Dataset (https://scikit-learn.org/stable/datasets/toy_dataset.html#diabetes-dataset)
- CSV Files (PEW, Billboard, Cars)