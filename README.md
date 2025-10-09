# SHAP2NAM-An-Interpretable-Hybrid-Machine-Learning-Model-for-Heart-Disease-Prediction

**SHAP2NAM** is a hybrid machine learning framework designed for accurate and explainable heart disease prediction.  
It integrates **SHAP (SHapley Additive exPlanations)**–based feature interaction selection with **second-order Neural Additive Models (NAMs)** to capture both individual and pairwise feature effects.  
The model achieves **95.1 % accuracy** and **100 % recall** on the Cleveland Heart Disease dataset while remaining fully interpretable for clinical decision support.

---

##  Overview
Heart disease remains one of the leading causes of mortality worldwide, yet early and accurate diagnosis continues to be challenging.  
This project bridges the gap between **predictive accuracy** and **explainability** by combining the strengths of feature-attribution methods and interpretable deep learning.

Developed as part of a **Master of Engineering (MEng) research project at Toronto Metropolitan University (AI specialization)**, SHAP2NAM aims to provide clinicians with a reliable and transparent decision-support tool.

---

##  Key Features
- **Hybrid interpretability pipeline:**  
  Combines SHAP-based feature-interaction ranking with second-order NAMs.  
- **Visual explanations:**  
  Generates 1-D risk curves and 2-D interaction surfaces showing how features jointly affect prediction.  
- **High performance:**  
  95.1 % accuracy, 100 % recall, and 0.97 AUC on the Cleveland dataset.  
- **Robust preprocessing:**  
  Iterative imputation, one-hot encoding, standard scaling, and cross-validation.  
- **Clinically meaningful insights:**  
  Highlights feature relationships such as `thal × cp`, `age × chol`, and `oldpeak × slope`.

---

##  Technologies Used
- **Python 3.10+**
- **Libraries:** NumPy, Pandas, Scikit-learn, PyTorch, SHAP, Matplotlib, Seaborn
- **Dataset:** UCI Cleveland Heart Disease Dataset

---

##  Results

| Metric | Value |
|:--|:--|
| Accuracy | 95.1 % |
| Recall | 100 % |
| F1-Score | 95.0 % |
| AUC | 0.97 |

---

##  Visualizations
- **First-Order Risk Curves** (https://drive.google.com/file/d/1izm_RcnzAYUD4z542cAROJAbQKK6geW1/view?usp=drive_link)
- **Second-Order Interaction Surfaces** (https://drive.google.com/file/d/1ytLhFPdQhBA0GZeQzJWRoEhDaTfkFlB6/view?usp=drive_link)
  
