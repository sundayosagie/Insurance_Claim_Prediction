# Insurance Claim Prediction Project

## Project Overview
This project focuses on building a **machine learning classification model** to predict the **probability of an insurance claim** occurring for a building within a specified insured period.

The goal is to support **data-driven decision-making** for insurance companies by identifying high-risk policies, improving underwriting accuracy, and optimizing risk management strategies.

---

## Business Problem
Insurance companies face significant financial risks when claims are inaccurately predicted.

**Key Question:**  
Will a building have at least one insurance claim during the insured period?

The model provides probability-based predictions to:
- Improve underwriting decisions  
- Reduce unexpected losses  
- Enhance risk assessment strategies  

---

## Dataset Description
The dataset contains structured insurance and building-level attributes including:

- Building characteristics  
- Policy details  
- Risk indicators  

**Target Variable**
- `Claim`  
  - `1` → Claim occurred  
  - `0` → No claim occurred  

---

## Tools & Technologies
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  

---

## Project Workflow

### 1️. Data Cleaning & Preparation
- Handled missing values  
- Encoded categorical variables  
- Feature scaling  
- Train-test split  

### 2️. Exploratory Data Analysis (EDA)
- Distribution analysis  
- Correlation analysis  
- Claim vs non-claim insights  

### 3️. Modeling
Models trained:
- Logistic Regression  
- Random Forest  
- XGBoost  

### 4️. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

### 5️. Model Selection
The final model was selected based on:
- Overall performance  
- Balance between recall and precision  
- Business interpretability  

---

## Key Insights
- Certain building and policy features strongly influence claim probability  
- High-risk policies can be identified proactively  
- Supports smarter premium pricing and risk mitigation  

---

## Project Structure
```
Insurance_Claim_Prediction/
│
├── Insurance_Claim_Prediction_FINAL.ipynb
├── Insurance_Claim_Prediction_v1.html
├── README.md
├── requirements.txt
│
├── data/
│   ├── Train_data.csv
│   └── Variable_Description.csv
│
├── models/
│   ├── preprocessor.pkl
│   └── XGBoost_Insurance_Claim_Model.pkl
│
└── images/
    └── 


```

---

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Insurance_Claim_Prediction_v1.ipynb
```

---

## Future Enhancements
- Deploy with Flask or FastAPI  
- Interactive dashboard  
- Cost-sensitive learning  

---

## Author
**Sunday Osagie**  
Data Analyst & Machine Learning Practitioner  

---

## License
For educational and research purposes.