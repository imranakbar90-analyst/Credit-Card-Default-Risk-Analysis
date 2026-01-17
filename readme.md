📊 Credit Card Default Risk Analysis

Objective:
To analyze customer credit card behavior and build predictive models to identify default risk using demographic, financial, and behavioral features.

📁 Dataset

Source: Default of Credit Card Clients (Taiwan)

Records: 30,000 customers

Target Variable: Default payment next month (0 = No, 1 = Yes)

🛠️ Key Steps

Data Cleaning

Handled inconsistent payment status values

Validated billing and payment amounts

Exploratory Data Analysis (EDA)

Default rate analysis

Impact of age, education, marriage, credit limit

**Default Rate by Age Group
**
[images/Default Rate by Age Group.JPG](https://github.com/imranakbar90-analyst/Credit-Card-Default-Risk-Analysis/blob/2c10d01332e33c5feb14a9cecdaf9d84476c0e57/images/Default%20Rate%20by%20Age%20Group.JPG)

**Default Rate by Martial Status
**

[images/Default Rate by Martial Status.JPG](https://github.com/imranakbar90-analyst/Credit-Card-Default-Risk-Analysis/blob/2c10d01332e33c5feb14a9cecdaf9d84476c0e57/images/Default%20Rate%20by%20Martial%20Status.JPG)

**Default Rate by Martial Status
**
[images/Default Rate by Recent Payment Status.JPG](https://github.com/imranakbar90-analyst/Credit-Card-Default-Risk-Analysis/blob/2c10d01332e33c5feb14a9cecdaf9d84476c0e57/images/Default%20Rate%20by%20Recent%20Payment%20Status.JPG)

Payment behavior & delinquency patterns

Feature Engineering

[images/Feature Importance.JPG](https://github.com/imranakbar90-analyst/Credit-Card-Default-Risk-Analysis/blob/2c10d01332e33c5feb14a9cecdaf9d84476c0e57/images/Feature%20Importance.JPG)

Delay count

Inactive months

Total bill & payment

Payment ratio

Machine Learning

Logistic Regression (baseline, interpretable)

Random Forest (non-linear relationships)

Model Evaluation

ROC-AUC

https://github.com/imranakbar90-analyst/Credit-Card-Default-Risk-Analysis/blob/2c10d01332e33c5feb14a9cecdaf9d84476c0e57/images/ML%20model%20-%20metrics.JPG

Precision, Recall, F1-score

Feature importance analysis

📈 Key Findings

Payment behavior is the most important predictor of default

Repeated delinquency significantly increases risk

Demographic features are secondary compared to behavioral signals

Random Forest outperformed Logistic Regression


📷 Business Visualization Preview
Business Visualization Preview


🔧 Tools & Libraries

Python, Pandas, NumPy

Matplotlib, Seaborn

👤 Author
Imran Akbar — AML & IT Project Management Professional 10+ years in Compliance, Sanctions, and Financial Crime Systems. 
🌐 LinkedIn www.linkedin.com/in/mr-imran-akbar

Scikit-learn
