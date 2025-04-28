# Deep learning-driven discovery of cell-penetrating peptides in human, viral, and bacterial Proteomes Using Saprot.
SAP-CPP predict cell-penetrating peptide using Saprot platform
## Overview
This repository includes datsets and instructions of how to use Saprot platform to easily train your own model.

## Web Server
You can access the Saprot platform at:https://colab.research.google.com/github/westlake-repl/SaprotHub/blob/main/colab/SaprotHub_v2.ipynb?hl=en
This web includes a very detailed instruction of how to train your own protein prediction model.

## Usage
**1. Build the dataset you want use for training:** You can use the data provided in "datasets" for a CPP classifier training.

**2. Train the model on Saprot:** Just follow the instruction on Saprot. The parameters will be provided below.

**3. Evaluation:** You can use the data from independent dataset for model evaluation.

**4. Prediction:** Just use the model you trained on Saprot for simple prediction, or you can also install it in local environment.

## Directory Structure
- **`dataset/`**: Contains datasets for training and evaluation.
- **`PTMs/`**: The PTMs data used for analysis in the article.
- **`Proteome/`**: The proteome data we scanned in the article.

## Datasets
- **`SAP-CPP_dataset_CPP.xlsx`** and **`SAP-CPP_dataset_Non-CPP.xlsx`**: Datasets for training and evaluation.
- **`Independent_dataset_CPP.xlsx`** and **`Independent_dataset_Non-CPP.xlsx`**: Independent datasets for evaluation.

