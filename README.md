# 🏦 Loan Approval Prediction Engine

An end-to-end **Machine Learning system** that predicts whether a loan application will be approved or rejected based on applicant details. This project demonstrates **classification modeling, handling imbalanced data, and performance evaluation** using real-world financial features.

---

## 🚀 Overview

Financial institutions rely on data-driven systems to evaluate loan applications. This project builds a predictive model that:

* Classifies loan applications as **Approved (1)** or **Rejected (0)**
* Handles **imbalanced datasets**
* Optimizes performance using **evaluation metrics like precision, recall, and F1-score**

---

## 🎯 Key Features

* ✅ End-to-end ML pipeline (data → preprocessing → training → evaluation)
* ✅ Logistic Regression-based classification model
* ✅ Handles **class imbalance** using techniques like class weighting / resampling
* ✅ Model evaluation using **confusion matrix & classification report**
* ✅ Scalable and modular code structure

---

## 🧠 Tech Stack

* **Language:** Python
* **Libraries:**

  * scikit-learn
  * pandas
  * numpy
  * matplotlib / seaborn

---

## 📊 Dataset

The dataset contains applicant details such as:

* Applicant Income
* Loan Amount
* Credit History
* Gender, Marital Status
* Education Level
* Property Area

🎯 Target Variable:

* `Loan_Approved` → (0 = Rejected, 1 = Approved)

---

## ⚙️ Workflow

1. **Data Preprocessing**

   * Handle missing values
   * Encode categorical variables
   * Feature scaling

2. **Model Training**

   * Logistic Regression
   * Train-test split

3. **Handling Imbalance**

   * Class weights / resampling techniques

4. **Evaluation**

   * Accuracy
   * Precision / Recall / F1-score
   * Confusion Matrix

---

## 📈 Model Performance

| Metric              | Score |
| ------------------- | ----- |
| Accuracy            | 79%   |
| Precision (Class 1) | 0.70  |
| Recall (Class 1)    | 0.62  |
| F1 Score            | 0.66  |

🔍 Insight:

* Model performs well for **loan rejections (Class 0)**
* Needs improvement in **identifying approved loans (Class 1)**

---

## ⚠️ Challenges & Improvements

* 🔸 Class imbalance affecting recall
* 🔸 Missed positive (approved) cases

### Future Improvements:

* Apply **SMOTE** for better balancing
* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy as a web application

---

## 📂 Project Structure

```
Loan-Approval-Prediction/
│
├── data/
├── notebooks/
├── src/
├── model/
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction
uv init
uv venv --python 3.12
uv pip install -r requirements.txt
python main.py
```

---

## 💡 Use Cases

* Banking & Financial Institutions
* Credit Risk Assessment
* Loan Automation Systems

---

## 📌 Conclusion

This project demonstrates how machine learning can assist in **automating loan approval decisions**, improving efficiency and reducing manual effort while highlighting the importance of handling **imbalanced data in classification problems**.

---

## 👤 Author

**Monishwaran K**


---
