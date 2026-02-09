📊 Credit Risk Analytics — Python & Power BI Project
📌 Project Overview

This project focuses on Credit Risk Analytics for loan approval decisions.
The objective is to analyze borrower behavior, evaluate default risk, and support lending decisions using rule-based credit scoring and business-driven performance metrics.

The project intentionally covers Analytics only (no ML) to ensure strong business understanding before introducing predictive models.

🎯 Business Problem

Financial institutions must balance:

Approving more loans to drive growth

Controlling defaults to reduce financial risk

This project evaluates how different risk score thresholds impact:

Approval rate

Default rate

Precision & Recall

Business cost of wrong decisions

🛠️ Tools & Technologies

Python: Pandas, NumPy, Matplotlib

Power BI: DAX, Data Modeling, Interactive Dashboards

Concepts: EDA, Rule-Based Scoring, Confusion Matrix, Threshold Analysis

🔍 Project Workflow
1️⃣ Data Preparation (Python)

Cleaned raw loan dataset

Handled missing values and outliers

Performed Exploratory Data Analysis (EDA)

Validated all metrics in Python before visualization

2️⃣ Rule-Based Credit Risk Scoring

Created a risk score (0–4) based on business rules

Simulated approval policies using multiple thresholds

Compared outcomes across thresholds

3️⃣ Performance Evaluation

Approval Rate & Rejection Rate

Default Rate

Precision & Recall

Dynamic Confusion Matrix (TP, FP, TN, FN)

4️⃣ Power BI Dashboard

Star-schema data model

Threshold-driven DAX measures

Dynamic confusion matrix using disconnected dimensions

Executive-level visuals for decision-making

📊 Key Insights

Higher approval rates increase recall but also increase default risk

Precision vs Recall is a business trade-off, not a purely technical decision

Confusion matrix analysis explains why losses happen, not just how many

Rule-based systems provide transparency and interpretability

📁 Repository Structure

data/ → Raw and processed datasets

notebooks/ → Python EDA and validation notebooks

powerbi/ → Power BI dashboard and screenshots

docs/ → Business and metric documentation

🚀 What’s Next

This project will continue as a Machine Learning extension, where:

ML models will be trained on the same dataset

Results will be compared against the rule-based baseline

Business impact of ML will be evaluated, not just accuracy

📌 Disclaimer

This project is created for learning and portfolio purposes using a sample dataset.
It does not represent real customer data or production credit policies.
