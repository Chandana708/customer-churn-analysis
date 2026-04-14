# 📊 Customer Churn Analysis Project

## 📌 Project Overview
This project focuses on analyzing customer data to understand why customers leave a service. The dataset was explored, cleaned, and visualized to identify key patterns related to customer churn.

A machine learning model was built to predict customer churn and help businesses identify high-risk customers in advance.

---

## 📂 Dataset Information
- Contains customer details such as age, total purchase, number of sites, etc.
- Target variable: **Churn (0 = No, 1 = Yes)**

---

## 🧹 Data Preprocessing
- Handled missing values
- Removed unnecessary columns (Name, Onboard Date)
- Encoded categorical variables
- Scaled numerical features using StandardScaler

---

## 📊 Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Boxplots for:
  - Age vs Churn
  - Total Purchase vs Churn
  - Number of Sites vs Churn
- Correlation heatmap

---

## 🤖 Model Building
- Algorithm used: Logistic Regression
- Train-test split performed (70/30)
- Features used: Age, Total Purchase, Number of Sites (and encoded features)

---

## 📈 Model Evaluation
- Accuracy: ~90%
- Confusion Matrix used for performance evaluation

---

## 💡 Key Insights
- Customers with lower spending are more likely to churn
- Higher number of site visits is linked to churn
- Older customers show higher churn probability

---

## 🚀 Business Impact
This project helps businesses:
- Identify customers likely to leave
- Improve customer retention strategies
- Take proactive business actions

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab

---

## 📌 Conclusion
This project demonstrates how data analysis and machine learning can be used to predict customer churn and support business decision-making.
