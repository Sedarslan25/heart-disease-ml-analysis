# Heart Disease Data Analysis & Machine Learning

An academic machine-learning study that explores a structured heart-disease dataset and compares multiple modelling approaches. It is intended for data-analysis and learning purposes only; it is **not** a clinical diagnostic tool.

> **Kısa Türkçe özet:** Kalp hastalığı veri seti üzerinde keşifsel veri analizi, görselleştirme, Random Forest sınıflandırması, K-Means kümeleme ve yapay sinir ağı denemeleri içeren akademik Python çalışmasıdır.

## Highlights

- Exploratory data analysis on 920 records and 16 fields
- Statistical summaries and visualisations with Matplotlib, Seaborn, and Plotly
- Data preparation with imputation, encoding, scaling, and train/test splitting
- Random Forest binary classification with an executed notebook accuracy of approximately **0.82**
- K-Means clustering for exploratory patient-group analysis
- TensorFlow/Keras neural-network experiment with an executed notebook accuracy of approximately **0.82**

## Repository Contents

| File | Purpose |
| --- | --- |
| `heart_disease_analysis.ipynb` | Main Jupyter notebook: EDA, visualisations, preprocessing, and models |
| `heart_disease_uci.csv` | Dataset used by the notebook |
| `requirements.txt` | Python package list |

## Run Locally

1. Create and activate a Python virtual environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook or JupyterLab in this folder.
4. Open `heart_disease_analysis.ipynb` and run the cells from top to bottom.

## Notes on Results

The reported values come from the notebook's saved execution with its current preprocessing and train/test split. They are exploratory results, not evidence of medical validity or deployment readiness. Results can vary after changing data preparation, package versions, or random seeds.

## Responsible Use

This repository must not be used for medical advice, patient triage, or real-world diagnosis. Any clinical use would require domain review, validation, governance, and regulatory assessment.
