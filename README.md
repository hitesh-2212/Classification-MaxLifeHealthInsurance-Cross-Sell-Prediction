<h1 align="center">🧠 Max Life Insurance Cross-Sell Prediction</h1>
<p align="center">
  <b>Machine Learning | Insurance Analytics | Classification Project</b>
</p>

<hr>

<h2>📋 Project Summary</h2>
<p>
This project focuses on helping <b>Max Life Insurance</b> improve its
<b>cross-selling strategy</b> by predicting which existing
<b>health insurance policyholders</b> are most likely to purchase
<b>vehicle insurance</b>.
</p>

<p>
Using a dataset of <b>280,000+ customer records</b>, the problem was framed as a
<b>binary classification task</b>, where the target variable indicates
whether a customer is interested in vehicle insurance.
</p>

<p><b>Industry:</b> Insurance / Financial Services</p>

<hr>

<h2>🎯 Project Objective</h2>
<p>
To build a predictive machine learning model that identifies high-probability
customers for vehicle insurance cross-sell, enabling Max Life Insurance to:
</p>

<ul>
  <li>Optimize marketing campaigns</li>
  <li>Focus outreach on high-likelihood customers</li>
  <li>Increase cross-sell conversion rates</li>
  <li>Improve revenue and customer lifetime value</li>
</ul>

<hr>

<h2>🌐 Industry Context</h2>
<p>
The insurance industry increasingly relies on <b>data analytics and machine learning</b>
to enhance customer acquisition, retention, and cross-selling.
Leading insurers such as <b>HDFC Life, ICICI Lombard, and Max Life Insurance</b>
use predictive models to identify customers most likely to purchase
complementary products, improving efficiency and profitability.
</p>

<hr>

<h2>⚙️ Tools & Technologies</h2>
<ul>
  <li><b>Programming Language:</b> Python</li>
  <li><b>Libraries:</b> Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn</li>
  <li><b>Algorithms:</b> Decision Tree, Random Forest</li>
  <li><b>Techniques:</b>
    <ul>
      <li>Data Encoding</li>
      <li>Outlier Detection</li>
      <li>Class Imbalance Handling</li>
      <li>Hyperparameter Tuning (RandomizedSearchCV)</li>
      <li>Evaluation Metrics (ROC AUC, Recall, F1-score)</li>
    </ul>
  </li>
</ul>

<hr>

<h2>🧩 Data & Preprocessing</h2>
<p>
The dataset contains demographic, vehicle, and insurance-related attributes
for over <b>280,000 customers</b>.
</p>

<ul>
  <li>Handled missing values and ensured data consistency</li>
  <li>Encoded categorical variables into numerical form</li>
  <li>Detected and treated outliers</li>
  <li>Performed feature correlation analysis</li>
  <li>Addressed class imbalance using <b>class weighting</b></li>
</ul>

<p><b>Key Features:</b> Age, Vintage, Annual Premium, Vehicle Damage, Policy Sales Channel</p>

<hr>

<h2>🧱 Challenges & Solutions</h2>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th align="left">Challenge</th>
    <th align="left">Solution</th>
  </tr>
  <tr>
    <td>Highly imbalanced dataset</td>
    <td>Used class weighting to prioritize minority class</td>
  </tr>
  <tr>
    <td>Risk of overfitting</td>
    <td>Applied RandomizedSearchCV for hyperparameter tuning</td>
  </tr>
  <tr>
    <td>Non-linear relationships</td>
    <td>Implemented Random Forest for better generalization</td>
  </tr>
  <tr>
    <td>Large dataset size</td>
    <td>Optimized computations using vectorized Pandas and NumPy</td>
  </tr>
</table>

<hr>

<h2>💡 Actionable Insights</h2>
<ul>
  <li>Customers with <b>vehicle damage history</b> showed significantly higher purchase intent</li>
  <li><b>Older customers</b> and those with <b>higher annual premiums</b> were more likely to cross-buy</li>
  <li>New customers (low vintage) were less likely to purchase vehicle insurance</li>
  <li>Certain <b>sales channels</b> consistently demonstrated higher conversion rates</li>
</ul>

<hr>

<h2>📊 Model Performance</h2>

<table border="1" cellpadding="8" cellspacing="0" width="100%">
  <tr>
    <th>Model</th>
    <th>ROC AUC</th>
    <th>Recall (Positive Class)</th>
    <th>F1-Score</th>
  </tr>
  <tr>
    <td>Decision Tree</td>
    <td>0.79</td>
    <td>88%</td>
    <td>0.82</td>
  </tr>
  <tr>
    <td><b>Random Forest (Final Model)</b></td>
    <td><b>0.85</b></td>
    <td><b>93%</b></td>
    <td><b>0.87</b></td>
  </tr>
</table>

<hr>

<h2>💼 Business Impact</h2>
<ul>
  <li>Enabled <b>targeted marketing</b> by identifying high-likelihood customers</li>
  <li>Improved cross-sell conversion without additional acquisition cost</li>
  <li>Supported data-driven marketing and policy design decisions</li>
  <li>Enhanced customer engagement through personalized offers</li>
</ul>

<hr>

<h2>📂 Dataset</h2>
<p>
<a href="https://drive.google.com/file/d/1AW5Gz6IqktDOoIjaBeWvy-HMaF5Y84sX/view?usp=sharing" target="_blank">
👉 Click here to access the dataset
</a>
</p>

<hr>

<p align="center">
  <i>📌 This project demonstrates how machine learning can drive smarter cross-selling strategies in the insurance domain.</i>
</p>


