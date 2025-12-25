# 🧠 Max Life Insurance Cross-Sell Prediction

<img width="938" height="667" alt="image" src="https://github.com/user-attachments/assets/7e25dcea-94c3-4617-a89d-7df68cba6111" />

## 📋 Summary

This project aimed to help **Max Life Insurance** improve its cross-selling strategy by predicting which existing health insurance policyholders are most likely to purchase **vehicle insurance**. The dataset included over **280,000 customer records**, covering demographics, vehicle ownership, previous insurance history, and premium details.

The problem was framed as a **binary classification task**, where the target variable indicated whether a customer showed interest in vehicle insurance.

**Industry:** Insurance / Financial Services

---

## ⚙️ Tools and Technologies Used

* **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Machine Learning Algorithms:** Decision Tree, Random Forest
* **Techniques:**

  * Data Encoding
  * Outlier Detection
  * Class Imbalance Handling
  * Hyperparameter Tuning (RandomizedSearchCV)
  * Evaluation Metrics (ROC AUC, Recall, F1-score)

---

## 🌐 Industry Context

The insurance industry is increasingly leveraging **data analytics and machine learning** to enhance customer acquisition, retention, and cross-selling strategies.
With rising competition and digital transformation, companies such as **HDFC Life**, **ICICI Lombard**, and **Max Life Insurance** are integrating predictive analytics to identify customers most likely to purchase complementary products—like **vehicle or life insurance** for existing health insurance holders.

---

## 🎯 Project Objective

To develop a **predictive model** that identifies health insurance policyholders who are likely to purchase vehicle insurance.
This enables **Max Life Insurance** to:

* Optimize marketing strategies
* Focus outreach on high-probability customers
* Boost cross-sell conversions
* Increase revenue and customer lifetime value

---

## 🧩 Data and Preprocessing

The dataset contained over **280,000 customer records** with demographic and insurance-related details.

### Key Preprocessing Steps:

* Handled missing values and ensured data type consistency
* Encoded categorical features into numerical form
* Detected and treated outliers
* Performed feature correlation analysis
* Addressed **class imbalance** using class weighting

**Important Features:**
Age, Vintage, Annual Premium, Vehicle Damage, and Policy Sales Channel

---

## 🧱 Challenges and Solutions

| **Challenge**             | **Solution**                                                       |
| ------------------------- | ------------------------------------------------------------------ |
| Highly imbalanced dataset | Used class weighting to ensure minority class importance           |
| Risk of overfitting       | Applied RandomizedSearchCV for optimal hyperparameter tuning       |
| Non-linear relationships  | Implemented Random Forest for better generalization                |
| Large dataset             | Optimized computations with NumPy and vectorized Pandas operations |

---

## 💡 Actionable Insights

* Customers with **vehicle damage history** were significantly more likely to purchase vehicle insurance.
* **Older customers** and those with **higher annual premiums** showed greater purchase intent.
* **New customers (low vintage)** were less likely to cross-purchase.
* Certain **sales channels** demonstrated higher conversion rates than others.

---

## 📊 Key Results

| **Model**     | **ROC AUC Score** | **Recall (Positive Class)** | **F1-Score** |
| ------------- | ----------------- | --------------------------- | ------------ |
| Decision Tree | 0.79              | 88%                         | 0.82         |
| Random Forest | 0.85              | 93%                         | 0.87         |

---

## 💼 Business Impact

* Enabled **targeted marketing** by identifying high-likelihood customers
* Improved **cross-sell conversion rates**, boosting revenue without added acquisition cost
* Supported **data-driven decision-making** for marketing and policy design
* Enhanced **customer engagement and retention** through personalized offers

---

## Data set Link :- https://drive.google.com/file/d/1AW5Gz6IqktDOoIjaBeWvy-HMaF5Y84sX/view?usp=sharing

