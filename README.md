# Molecular Machine Learning Project (Fall 2025)

## 📌 Project Overview
This project predicts physical properties of polymers using SMILES strings. It includes a complete pipeline for data preprocessing, feature engineering, model training (using AutoGluon), and prediction.

## 👥 Team Members
* Chenxuan Gu, Yukun Liu

## 📁 Repository Structure
* `data/`: Contains the training and testing CSV files.
* `notebooks/`: Contains the main Jupyter notebook (`MML_project_v1.ipynb`) used for training and inference.
* `ag_models/`: Saved AutoGluon models (generated during runtime).
* `environment.yml`: List of Python dependencies.

## ⚙️ Installation Instructions
To set up the environment using Conda, follow these steps:
1. Clone this repository (or download the files):
```bash
git clone <your-repo-url>
cd <repository-folder>
```

2. Create the Conda environment:
This will install all dependencies listed in environment.yml.
```bash
conda env create -f environment.yml
```

3. Activate the environment:
The environment name is defined as mml_comp_chem.
```bash
conda activate mml_comp_chem
```

4. (Optional) Register the kernel for Jupyter:
If you cannot find the kernel in Jupyter, run:
```bash
python -m ipykernel install --user --name=mml_comp_chem --display-name "Python (mml_comp_chem)"
```

## 🚀 How to Reproduce Results
   1. Ensure your Conda environment is active:
conda activate mml_comp_chem

   2. Navigate to the notebooks/ directory.
   3. Open `MML_project_v1.ipynb`.
   4. Ensure `train.csv` and `test.csv` are located in the data/ directory relative to the notebook.
   5. Run all cells in the notebook.
   6. The model will output a `submission.csv` file in the notebooks directory.
## 📊 Data
The public dataset consists of polymer SMILES strings and their associated physical properties.
- Source: Public provided by **NeurIPS - Open Polymer Prediction 2025**. URL: https://www.kaggle.com/competitions/neurips-open-polymer-prediction-2025/data. No other external data was used.
## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
