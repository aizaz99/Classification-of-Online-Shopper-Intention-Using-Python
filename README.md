# 🛍️ Online Shopper Intention Classification

This project uses real-world e-commerce session data to predict whether a user will complete a purchase. It applies supervised machine learning models to classify user behavior into revenue-generating or not, based on features like page visits, time spent, bounce rate, and user type.

---

## 🔍 Overview

- **Goal**: Predict if an online session ends in a purchase (`Revenue = True/False`)
- **Dataset**: [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/online+shoppers+purchasing+intention+dataset) (UCI ML Repository)
- **Models Used**:
  - Logistic Regression
  - Random Forest Classifier (with GridSearchCV)

---

## 🧠 Features in the Dataset

- Page visit counts and durations (Administrative, Informational, ProductRelated)
- Bounce & Exit Rates
- Month, Operating System, Region, TrafficType
- VisitorType (New, Returning)
- Weekend flag
- Target: `Revenue` (True if purchase was made)

---

## ⚙️ Technologies Used

- Python
- pandas, NumPy
- scikit-learn (Logistic Regression, Random Forest, GridSearchCV, metrics)
- matplotlib & seaborn (visualizations)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shopper-intention-classification.git
   cd shopper-intention-classification
Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Online_Shopper_Classification.ipynb
📊 Model Performance
Metric	Logistic Regression	Random Forest
Accuracy	86.9%	89.6%
Precision	72.7%	77.2%
Recall	34.3%	53.5%
F1 Score	46.6%	63.2%
ROC AUC	0.878	0.925

Random Forest outperformed Logistic Regression across all metrics, especially recall and AUC, making it more suitable for predicting potential buyers.

📁 Files Included
Online_Shopper_Classification.ipynb – Full code (preprocessing, training, evaluation)

online_shoppers_intention.csv – The dataset

Online_Shopper_Report.docx – Final report summarizing approach and results

