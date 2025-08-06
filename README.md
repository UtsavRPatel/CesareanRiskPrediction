# Cesarean Delivery Risk Prediction Using Machine Learning

This repository contains the complete code and documentation for the research project titled:

**"Identifying Determinants of Cesarean Births: A Machine Learning Framework for Maternal Health Research"**

Developed as part of an academic research paper using the 2022 National Vital Statistics System (NVSS) natality dataset, this project leverages Python-based machine learning techniques to predict the likelihood of cesarean delivery and uncover the most influential clinical and demographic features using SHAP explanations.

---

## 📊 Project Overview

Cesarean (C-section) births account for a significant portion of deliveries in the U.S., with increasing concern over clinical necessity and health disparities. This project develops and evaluates several predictive models—including **Random Forest**, **Gradient Boosting**, and **XGBoost**—using a cleaned subset of the NVSS 2022 dataset. SHAP analysis is used for interpretability of results.

Key components:
- Data cleaning and preprocessing
- Train/Validation/Test split using 5 deterministic seeds
- Hyperparameter tuning with **Optuna**
- Model evaluation (accuracy, F1, ROC-AUC, confusion matrix)
- SHAP feature importance, dependence plots, and individual-level force plots

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `research.ipynb` | Full Jupyter Notebook with data cleaning, modeling, evaluation, and SHAP analysis |
| `cesarean_model.pkl` | Trained XGBoost model (if included) |
| `plots/` | Directory containing visualizations (ROC curves, SHAP plots, etc.) |
| `requirements.txt` | Python dependencies for environment setup |
| `README.md` | Project documentation (this file) |

---

## 🧠 Dependencies

Install the following Python packages (recommended: use a virtual environment):

```bash
pip install pandas scikit-learn xgboost shap optuna matplotlib seaborn joblib


Here’s a complete and professional `README.md` file for your GitHub repository, tailored to your cesarean prediction project:

---

````markdown
# Cesarean Delivery Risk Prediction Using Machine Learning

This repository contains the complete code and documentation for the research project titled:

**"Identifying Determinants of Cesarean Births: A Machine Learning Framework for Maternal Health Research"**

Developed as part of an academic research paper using the 2022 National Vital Statistics System (NVSS) natality dataset, this project leverages Python-based machine learning techniques to predict the likelihood of cesarean delivery and uncover the most influential clinical and demographic features using SHAP explanations.

---

## 📊 Project Overview

Cesarean (C-section) births account for a significant portion of deliveries in the U.S., with increasing concern over clinical necessity and health disparities. This project develops and evaluates several predictive models—including **Random Forest**, **Gradient Boosting**, and **XGBoost**—using a cleaned subset of the NVSS 2022 dataset. SHAP analysis is used for interpretability of results.

Key components:
- Data cleaning and preprocessing
- Train/Validation/Test split using 5 deterministic seeds
- Hyperparameter tuning with **Optuna**
- Model evaluation (accuracy, F1, ROC-AUC, confusion matrix)
- SHAP feature importance, dependence plots, and individual-level force plots

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `research.ipynb` | Full Jupyter Notebook with data cleaning, modeling, evaluation, and SHAP analysis |
| `cesarean_model.pkl` | Trained XGBoost model (if included) |
| `plots/` | Directory containing visualizations (ROC curves, SHAP plots, etc.) |
| `requirements.txt` | Python dependencies for environment setup |
| `README.md` | Project documentation (this file) |

---

## 🧠 Dependencies

Install the following Python packages (recommended: use a virtual environment):

```bash
pip install pandas scikit-learn xgboost shap optuna matplotlib seaborn joblib
````

Or use the provided `requirements.txt` file.

---

## 📂 Dataset

This project uses the **2022 Natality Public-Use File** from the **National Vital Statistics System (NVSS)**.
Download from the CDC: [https://www.cdc.gov/nchs/nvss/births.htm](https://www.cdc.gov/nchs/nvss/births.htm)

Due to size constraints (\~2 GB), the dataset is not hosted in this repository.

---

## 🔎 Reproducibility

All model training uses deterministic random seeds derived from a hashed student ID for reproducibility.
To replicate the results:

1. Download the NVSS data.
2. Follow the Jupyter Notebook in sequence.
3. Evaluate models using the test set or apply your own data (if similarly formatted).

---

## 📈 Outputs

* Accuracy > 78% across all models
* Best Model: **XGBoost** (Accuracy: 79.1%, ROC-AUC: 0.85)
* Top features: Attendant at birth, Induction, Fetal presentation, Maternal age

---

## 📜 License

This repository is released under the [MIT License](https://opensource.org/licenses/MIT).

---

## 📧 Contact

For questions or collaborations, contact:
**\Utsav Patel**
\[[utsavpatel8828@gmail.com](mailto:utsavpatel8828@gmail.com)]
Harrisburg University of Science and Technology, Harrisburg, PA

---

## 📝 Citation

If you use this code or dataset in your own research, please cite:

> Patel, U (2025). Identifying Determinants of Cesarean Births: A Machine Learning Framework for Maternal Health Research. Unpublished manuscript.

```



