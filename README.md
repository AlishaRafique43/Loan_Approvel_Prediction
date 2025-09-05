# Loan Approval Prediction  

## 📌 Overview  
This project uses **Machine Learning** to predict whether a loan application should be **approved ✅** or **rejected ❌**.  
By automating the loan screening process, the system helps financial institutions save time, reduce manual effort, and ensure objective decision-making.  

---

## ✨ Features  
- 🔍 Data preprocessing & cleaning  
- 📈 Exploratory Data Analysis (EDA)  
- 🤖 Machine learning model training & evaluation  
- ✅ Final **Decision Tree model with 100% accuracy**  
- 📊 Feature importance analysis (e.g., Credit Score, Income, DTI Ratio)  

---

## 🛠️ Tech Stack  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 🚀 How to Run  
```bash
# Clone this repository
git clone https://github.com/AlishaRafique43/Loan_Approval_Prediction.git
cd Loan_Approval_Prediction

# Install dependencies
pip install -r requirements.txt
```


## 📊 Results
---

| Model                | Accuracy | Precision (Rejected) | Recall (Rejected) | Precision (Approved) | Recall (Approved) | F1-Score |
|-----------------------|----------|----------------------|-------------------|-----------------------|-------------------|----------|
| **Decision Tree ✅**  | **100%** | 0.99                 | 0.99              | 1.00                  | 1.00              | **1.00** |
| Logistic Regression   | 91%      | 0.65                 | 0.94              | 0.99                  | 0.91              | 0.95     |

📌 The Decision Tree significantly outperformed Logistic Regression, achieving perfect classification on the test set.

## 🔑 Key Insights
---
- Credit Score is the most important factor for loan approval.

- Income and DTI Ratio strongly influence decisions.

- Loan Purpose (text description) had little impact → can be excluded in future models.
---
## 📜 License
 
This project is licensed under the [MIT License](LICENSE).


