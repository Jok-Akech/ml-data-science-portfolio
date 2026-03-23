# ML & Data Science Portfolio

### Jok Akech Atem Mabior | Carnegie Mellon University Africa

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3%2B-f7931e?style=flat-square&logo=scikit-learn)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13%2B-ff6f00?style=flat-square&logo=tensorflow)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7%2B-189fdd?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## Overview

This portfolio presents a comprehensive collection of machine learning and data science projects focused on **East African contexts** — spanning agriculture, public health, and financial technology. Each notebook applies rigorous ML methodology to problems that matter: predicting crop yields in Kenya's maize belt, identifying malaria risk factors across the Great Lakes region, detecting mobile money fraud, and classifying satellite land cover imagery.

The datasets are synthetically generated to reflect real-world distributions observed in East African surveys, agricultural reports, and health studies — enabling reproducible experimentation without privacy concerns while maintaining domain authenticity. The work draws on my training at Carnegie Mellon University Africa and a commitment to applying data science where it can improve livelihoods across the continent.

---

## Notebooks

| # | Notebook | Topic | Dataset Context | Key Techniques |
|---|----------|-------|-----------------|----------------|
| 01 | [Linear Regression](notebooks/01_linear_regression.ipynb) | Crop Yield Prediction | Kenya Agriculture | OLS, Ridge, Lasso, ElasticNet |
| 02 | [Logistic Regression](notebooks/02_logistic_regression.ipynb) | Malaria Risk Prediction | East Africa Health | Binary Classification, ROC-AUC |
| 03 | [Decision Trees](notebooks/03_decision_trees.ipynb) | Loan Default Prediction | Microfinance East Africa | CART, Pruning, Feature Importance |
| 04 | [Random Forests](notebooks/04_random_forests.ipynb) | Coffee Quality Prediction | Ethiopia/Rwanda Agriculture | Ensemble, OOB Error |
| 05 | [Support Vector Machines](notebooks/05_svm.ipynb) | Land Cover Classification | Satellite Remote Sensing | Kernel Methods, Grid Search |
| 06 | [K-Means Clustering](notebooks/06_kmeans_clustering.ipynb) | Mobile Money Segmentation | M-Pesa Style Finance | Elbow Method, Silhouette Score |
| 07 | [PCA](notebooks/07_pca.ipynb) | Socioeconomic Survey Analysis | East Africa Multi-Country | Dimensionality Reduction, Biplots |
| 08 | [CNN Image Classification](notebooks/08_cnn_image_classification.ipynb) | Crop Disease Detection | East Africa Agriculture | Conv2D, Data Augmentation |
| 09 | [RNN / LSTM](notebooks/09_rnn_time_series.ipynb) | Commodity Price Forecasting | East Africa Markets | LSTM, Sequence Modeling |
| 10 | [NLP Text Classification](notebooks/10_nlp_text_classification.ipynb) | News Article Classification | East African Media | TF-IDF, NLTK, Text Preprocessing |
| 11 | [Recommendation Systems](notebooks/11_recommendation_systems.ipynb) | Agricultural Input Recommendation | Farmer Data East Africa | Collaborative Filtering, SVD |
| 12 | [Anomaly Detection](notebooks/12_anomaly_detection.ipynb) | Mobile Money Fraud Detection | East Africa Finance | Isolation Forest, LOF, Autoencoder |
| 13 | [Transfer Learning](notebooks/13_transfer_learning.ipynb) | Malaria Cell Classification | Medical Imaging | Fine-tuning, Feature Extraction |
| 14 | [XGBoost](notebooks/14_xgboost.ipynb) | Household Welfare Prediction | East Africa Survey Data | Gradient Boosting, SHAP |

---

## Setup

```bash
# Clone the repository
git clone https://github.com/jokakech/ml-data-science-portfolio.git

# Navigate into the project
cd ml-data-science-portfolio

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

> **Recommended:** Use a virtual environment (`python -m venv venv && source venv/bin/activate` on Linux/Mac or `venv\Scripts\activate` on Windows) before installing requirements.

---

## Technologies

| Category | Libraries |
|----------|-----------|
| **Language** | Python 3.9+ |
| **Data Manipulation** | NumPy, Pandas, SciPy |
| **Machine Learning** | Scikit-learn, XGBoost, LightGBM, imbalanced-learn |
| **Deep Learning** | TensorFlow / Keras |
| **NLP** | NLTK |
| **Explainability** | SHAP |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Utilities** | joblib, tqdm, Pillow, statsmodels |
| **Recommendation** | Scikit-Surprise |

---

## Project Structure

```
ml-data-science-portfolio/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01_linear_regression.ipynb        # Crop Yield Prediction
│   ├── 02_logistic_regression.ipynb      # Malaria Risk Prediction
│   ├── 03_decision_trees.ipynb           # Loan Default Prediction
│   ├── 04_random_forests.ipynb           # Coffee Quality Prediction
│   ├── 05_svm.ipynb                      # Land Cover Classification
│   ├── 06_kmeans_clustering.ipynb        # Mobile Money Segmentation
│   ├── 07_pca.ipynb                      # Socioeconomic Survey Analysis
│   ├── 08_cnn_image_classification.ipynb # Crop Disease Detection
│   ├── 09_rnn_time_series.ipynb          # Commodity Price Forecasting
│   ├── 10_nlp_text_classification.ipynb  # News Article Classification
│   ├── 11_recommendation_systems.ipynb   # Agricultural Input Recommendation
│   ├── 12_anomaly_detection.ipynb        # Mobile Money Fraud Detection
│   ├── 13_transfer_learning.ipynb        # Malaria Cell Classification
│   └── 14_xgboost.ipynb                  # Household Welfare Prediction
├── data/
│   └── processed/                        # Processed / feature-engineered data
├── models/                               # Saved model artifacts (gitignored)
└── figures/                              # Exported plots and visualizations
```

---

## Contact

**Jok Akech Atem Mabior**
Carnegie Mellon University Africa
Kigali, Rwanda

- GitHub: [@jokakech](https://github.com/jokakech)
- LinkedIn: [linkedin.com/in/jok-mabior-542346206](https://www.linkedin.com/in/jok-mabior-542346206)
- Email: [jmabior@andrew.cmu.edu](mailto:jmabior@andrew.cmu.edu) | [jokakech@gmail.com](mailto:jokakech@gmail.com)

---

*Built with purpose — applying machine learning to challenges that matter in East Africa.*
