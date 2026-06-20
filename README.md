# 🧑‍💼 Adult Census Income Prediction

## 📌 Overview
This project uses the **Adult Census Income dataset** (UCI/Kaggle) to predict whether an individual earns more than $50K/year based on demographic and employment attributes.  
It demonstrates supervised learning workflows with **Logistic Regression** and **Random Forest**, comparing performance using evaluation metrics and visualizations.

---

## 🛠️ Tools & Libraries
- Python → pandas, numpy, scikit‑learn  
- Visualization → matplotlib, seaborn  
- Environment → Jupyter Notebook / Google Colab  

---

---


## ⚙️ Workflow
1. **Data Preprocessing**
   - Handle missing values (`?` replaced with NaN, dropped).  
   - Encode categorical variables (Label Encoding).  
   - Scale numerical features (StandardScaler).  

2. **Model Training**
   - Logistic Regression → interpretable baseline.  
   - Random Forest → ensemble method for higher accuracy.  

3. **Evaluation**
   - Accuracy, Precision, Recall, F1‑score.  
   - Confusion Matrix heatmaps.  
   - ROC Curve comparison.  

---

## 📈 Results
| Model              | Accuracy | Precision | Recall | F1‑Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| ~0.83    | ~0.82     | ~0.80  | ~0.81    |
| Random Forest      | ~0.86    | ~0.85     | ~0.83  | ~0.84    |

*(Values will vary depending on preprocessing and hyperparameters.)*

---

## 🎯 Key Insights
- Random Forest outperforms Logistic Regression.  
- Proper preprocessing is critical for performance.  
- ROC curves highlight trade‑offs between models.  

---

## 🚀 Outcome
- Hands‑on experience with **real‑world socioeconomic data**.  
- Demonstrated ability to **train, evaluate, and compare ML models**.  
- Recruiter‑friendly showcase of **supervised learning and model evaluation**.  

---

## 📂 Repository Structure

 adult-income-prediction-ml/
 
│
├── notebooks/
│   └── Adult_Census_Income_project.ipynb

│
├── src/
│   └── preprocessing.py
│   └── train_models.py

│
├── results/
│   └── Logistic Regression_confusion_matrix.png
│   └── Random Forest_confusion_matrix.png
│   └── roc_curve.png

│
├── README.md
└── requirements.txt

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
python src/train_models.py

