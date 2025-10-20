# 🧠 Parkinson’s Disease – UPDRS Regression & Classification

This project focuses on **predicting and classifying Parkinson’s Disease severity** using voice measurement features and machine learning models.  
It uses both **regression** (to predict total UPDRS scores) and **binary classification** (healthy vs patient) approaches.

---

## 📊 Project Overview

- **Objective:** Predict UPDRS scores and classify Parkinson's disease severity  
- **Dataset:** Parkinson’s dataset (e.g. from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons))  
- **Tech Stack:** Python, pandas, scikit-learn, matplotlib  
- **Methods:**  
  - Data preprocessing  
  - Regression models (SVR, Lasso, KNN, Random Forest)  
  - Classification models (Logistic Regression, Random Forest)  
  - ROC analysis & performance metrics

---

## 🧰 Project Structure
```
parkinson-s-disase/
├─ data/ # dataset (not uploaded if restricted)
│ └─ README.md
├─ results/ # generated graphs & metrics
│ └─ .gitkeep
├─ pd (1).ipynb # main notebook (regression + classification)
├─ requirements.txt # dependencies
└─ README.md
```


## 🚀 How to Run

1. **Clone the repo**
```bash
git clone https://github.com/Tugceaydinn/parkinson-s-disase.git
cd parkinson-s-disase
Install dependencies

bash
pip install -r requirements.txt
Place the dataset
Put parkinsons.csv inside the data/ folder.

Run the notebook

bash
jupyter notebook "pd.ipynb"
The outputs will be saved into the results/ folder:

roc_curve.png – ROC curve plot

regression_test_mse.csv – regression results

classification_metrics.csv – classification metrics

🧪 Model Performance
Model	Type	Metric	Score
SVR	Regression	MSE (↓)	91.71
Random Forest	Regression	MSE (↓)	184.66
Logistic Regression	Classification	Accuracy (↑)	0.87
Random Forest	Classification	Accuracy (↑)	0.91

✅ SVR achieved the lowest error in regression.
✅ Random Forest achieved the highest classification accuracy.

📈 Visualizations

📚 References
UCI Parkinson’s Disease Dataset

Little MA, McSharry PE, Hunter EJ, Spielman J, Ramig LO (2009)

👩‍💻 Author
Tuğçe Aydın
🎓 MSc Data & Computational Science @ UCD
💻 Data Science | Machine Learning | Python | R
📍 Dublin, Ireland
🔗 LinkedIn · GitHub

🌟 Future Work
Hyperparameter tuning for better model performance

Exploring deep learning approaches (MLP)

Feature selection improvements

Real-time detection prototype
