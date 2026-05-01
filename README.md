# 🏥 Diabetes Prediction with KNN

A machine learning project that predicts diabetes using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 📋 Dataset
- **Source:** Pima Indians Diabetes Dataset
- **Samples:** 768
- **Features:** 8
- **Target:** `Outcome` (1 = Diabetic, 0 = Healthy)

---

## 🔧 Workflow
1. Exploratory Data Analysis (EDA)
2. Missing Value Treatment (0 → NaN → Median Imputation)
3. Outlier Detection & Capping (IQR Method)
4. Feature Engineering
5. Handling Class Imbalance (SMOTE)
6. Scaling (StandardScaler)
7. Modeling & Hyperparameter Optimization (GridSearchCV)
8. Model Evaluation (Confusion Matrix, ROC Curve)

---

## 📊 Results

| Metric | Baseline | Final Model |
|--------|----------|-------------|
| Accuracy | 0.73 | 0.74 |
| F1 Score | 0.59 | 0.64 |
| ROC-AUC | 0.78 | 0.78 |

---

## 🛠️ Libraries
- pandas, numpy
- scikit-learn
- imbalanced-learn
- matplotlib, seaborn

---

## 🚀 How to Run
1. Clone the repo
```bash
   git clone https://github.com/caglauzumcuu/Diabetes.git
```
2. Open `Diabetes_Prediction_with_KNN.ipynb` in Google Colab or Jupyter Notebook
3. Upload `diabetes.csv` to your environment
4. Run all cells

---

## 📁 Project Structure
```
Diabetes/
│
├── Diabetes_Prediction_with_KNN.ipynb
├── diabetes.csv
└── README.md
```
