# 📊 Customer Churn Prediction - Telco Dataset

## 📌 Overview
This project aims to **predict customer churn** using the **Telco Customer Churn dataset**.  
Churn prediction helps telecom companies identify customers likely to leave, enabling them to take proactive steps to improve retention.

A **Logistic Regression** model was trained on customer demographics, account information, and service usage features to classify whether a customer will **stay (0)** or **churn (1)**.

---

## 📂 Dataset
The project uses the **Telco Customer Churn dataset** (commonly available on Kaggle).  
It contains information such as:
- Customer demographics (gender, senior citizen, partner, dependents)
- Service details (internet service, contract type, phone services)
- Account information (tenure, monthly charges, payment method)
- Churn label (Yes/No → converted to 1/0)

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Normalizing numerical features  

2. **Model Training**
   - Logistic Regression used as the classification model  
   - Train-test split applied for evaluation  

3. **Evaluation**
   - Accuracy: **0.816**  
   - Precision, Recall, and F1-score calculated  

---

## 📈 Results
```
Accuracy: 0.816
Classification Report:
               precision    recall  f1-score   support

           0       0.85      0.91      0.88      1036
           1       0.69      0.57      0.62       373

    accuracy                           0.82      1409
   macro avg       0.77      0.74      0.75      1409
weighted avg       0.81      0.82      0.81      1409
```

✔️ The model performs well in predicting non-churners, with decent performance for churners.  
✔️ Useful for churn analysis and customer retention strategy.  

---

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/SHALINISAURAV/customer-churn-prediction.git
   cd customer-churn-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project:
   ```bash
   python churn_prediction.py
   ```

---

## 📦 Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn (for visualization)

Install with:
```bash
pip install -r requirements.txt
```

---

## 📌 Future Work
- Try advanced models (Random Forest, XGBoost, Neural Networks)
- Apply hyperparameter tuning
- Build a web dashboard for real-time churn prediction  

---

## 🙌 Acknowledgments
Dataset: [Telco Customer Churn - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

---
## 👩‍💻 Author :
     SHALINI SAURAV ;)
