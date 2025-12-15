# MML Fall 2025 Final Project: Polymer Property Prediction

## 🧪 Project Description
Project implements a machine learning pipeline to predict physical properties of polymers (Tg, FFV, Tc, Density, Rg) based on their SMILES representation. We utilize a hybrid feature engineering approach combining RDKit descriptors, Morgan Fingerprints, and ChemBERTa transformer embeddings, followed by an AutoGluon AutoML ensemble for prediction.

## 👥 Team Members
* Benjamin Gu

## 📁 Repository Structure
* `data/`: Contains the training and testing CSV files.
* `notebooks/`: Contains the main Jupyter notebook (`main_pipeline.ipynb`) used for training and inference.
* `src/`: (Optional) Helper scripts.
* `ag_models/`: Saved AutoGluon models (generated during runtime).
* `requirements.txt`: List of Python dependencies.

## ⚙️ Installation Instructions
1. Clone this repository.
2. Install dependencies:
  ```bash
  pip install -r requirements.txt

🚀 How to Reproduce Results
   1. Navigate to the notebooks/ directory.
   2. Open main_pipeline.ipynb.
   3. Ensure train.csv and test.csv are located in the data/ directory relative to the notebook.
   4. Run all cells in the notebook.
   5. The model will output a submission.csv file in the notebooks directory.
📊 Data
The dataset consists of polymer SMILES strings and their associated physical properties.
   * Source: Provided by the MML Fall 2025 Course6.

   * Note: We utilized the provided course datasets and did not generate external data.
