# 🎬 Netflix Customer Churn Prediction

## 📌 Objective

Build a machine learning model to predict whether a user will churn (leave the platform) based on their engagement, subscription, and behavioral data.

---

## 📊 Dataset

The dataset contains user-level information such as:

* Watch hours
* Average watch time per day
* Last login (inactivity)
* Subscription type
* Monthly fee
* Device and region

Target variable:

* **churned (0 = active, 1 = churned)**

---

## 🧠 Models Used

* Logistic Regression
* Random Forest Classifier

---

## ⚙️ Project Workflow

1. Data preprocessing (handling missing values, encoding categorical variables)
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Model training and evaluation
5. Performance comparison

---

## 📈 Results

* Achieved ~80% accuracy
* Random Forest performed better than Logistic Regression
* Evaluated using:

  * Confusion Matrix
  * Precision, Recall, F1-score
  * ROC-AUC Score

---

## 🔍 Key Insights

* Users with **low watch hours** are more likely to churn
* Users with **high inactivity (last login days)** show higher churn probability
* Subscription type influences churn behavior

---

## 💡 Business Recommendations

* Target inactive users with notifications and reminders
* Provide personalized content recommendations to increase engagement
* Offer discounts or plan upgrades to low-engagement users

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 🚀 Future Improvements

* Hyperparameter tuning for better performance
* Deployment using Streamlit
* Real-time churn prediction system

---

## 📎 Project Structure

```
netflix-churn-prediction/
│
├── data/
├── churn_analysis.ipynb
├── README.md
```

---

## 👨‍💻 Author

Tejash Misra
