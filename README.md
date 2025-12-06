# Logistic Regression Tutorial: L1 vs L2 Regularisation  
### Student: Yogesh Yadav  
### Student ID: 24071578  

This repository contains all code, results, and documentation for the machine learning tutorial:  
**“Logistic Regression with L1 vs L2 Regularisation: Effects on Decision Boundaries, Coefficients, and Classification Performance.”**

It has been developed according to the requirements of the Machine Learning and Neural Networks module.

---

##  Repository Structure

```
├── logreg_regularisation_yogesh.ipynb     # Complete notebook (part 1 & 2)
├── README.md                               # Documentation (this file)
├── requirements.txt                        # Dependencies for reproducibility
├── figures/                                # Auto-generated figures
│      ├── synthetic_data.png
│      ├── decision_boundary_L2.png
│      ├── decision_boundary_L1.png
│      ├── C_vs_accuracy.png
│      ├── confusion_L1_L2.png
│      ├── roc_L1_L2.png
│      ├── top_coefficients.png
```

---

## 📘 Overview of Tutorial

This tutorial helps learners understand:

- How Logistic Regression works as a linear classifier  
- The role of **regularisation** in preventing overfitting  
- Differences between **L1 (Lasso)** and **L2 (Ridge)** penalties  
- How the regularisation strength parameter **C** affects performance  
- The impact of regularisation on feature coefficients  
- Interpretation of ROC curves, confusion matrices, and classification reports  

It includes both **visual intuition** (synthetic dataset) and **high‑dimensional application** (Breast Cancer Dataset).

---

## ▶️ Running the Tutorial

### Step 1 — Install Dependencies  
```
pip install -r requirements.txt
```

### Step 2 — Open Jupyter Notebook  
```
jupyter notebook logreg_regularisation_yogesh.ipynb
```

### Step 3 — Run All Cells  
All figures will be automatically saved in the `figures/` folder.

---

## 📊 Datasets Used

### 1. Synthetic 2D Dataset  
Created using `sklearn.datasets.make_classification()` with:  
- Two informative features  
- Clear separation for visualising boundaries  
- Controlled noise  

### 2. Breast Cancer Wisconsin Dataset  
Imported using `load_breast_cancer()` from sklearn.

Academic Reference (Harvard):  
Street, W.N., Wolberg, W.H. and Mangasarian, O.L. (1993). *Breast cancer diagnosis and prognosis via linear programming*. University of Wisconsin–Madison.

Dataset source:  
https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset

---

##  Accessibility Considerations

- Colour-blind-safe palettes  
- Large fonts for readability  
- Alternative text descriptions for plots in the PDF tutorial  
- Avoided screenshots of code to support screen readers  
- Clear structure and consistent layout  

---

##  Reproducibility

- Fixed random seed: `random_state=24071578`  
- All results produced directly via notebook execution  
- Python package versions pinned in requirements.txt  

---

## 📝 Licence  
This project is for educational use under the MSc Data Science programme.
