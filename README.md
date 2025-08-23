# msc-loan-approval-automation
Machine Learning-Based Loan Approval Automation: Enhancing Efficiency, Accuracy, and Fairness in Credit Decision-Making
# Loan Approval Automation using Machine Learning

This repository contains the MSc dissertation project:  
**"Machine Learning-Based Loan Approval Automation: Enhancing Efficiency, Accuracy, and Fairness in Credit Decision-Making."**  

The project explores the use of **Random Forest**, **XGBoost**, and **ensemble models** (stacking and voting) to automate the loan approval process, improve predictive accuracy, and ensure fairer decision-making.

---

## Project Overview
Financial institutions traditionally rely on manual evaluation for loan approvals, which is time-consuming and prone to human bias.  
This project automates the loan approval process using **machine learning techniques**, enhancing efficiency, accuracy, and fairness.

Key objectives:
- Automate the loan approval workflow.
- Optimize predictive performance via **hyperparameter tuning**.
- Improve interpretability using **LIME** and **SHAP** for explainable AI.
- Ensure balanced decision-making by addressing **class imbalance**.

---

## Models Implemented
- **Random Forest** – Tuned using GridSearchCV.
- **XGBoost** – Optimized for improved performance.
- **Stacking Ensemble** – Combines Random Forest and XGBoost with a **Logistic Regression meta-learner**.
- **Voting Ensemble** – Soft voting combining tuned Random Forest and XGBoost.

---

## Evaluation Metrics
We evaluated performance using:
- **Accuracy** – Overall correctness.
- **Precision & Recall** – For class-specific performance.
- **F1 Score** – Balance between precision and recall.
- **ROC-AUC** – Discrimination ability.

---

## Repository Structure
msc-loan-approval-automation/
│── msc_project_hellen.py # Main machine learning pipeline
│── MSc Report - Hellen.docx # Full dissertation
│── README.md # Project documentation
│── requirements.txt # Libraries and dependencies
└── data/ # Dataset folder 


---

## Installation
Clone this repository:
```bash
git clone https://github.com/<your-username>/msc-loan-approval-automation.git
cd msc-loan-approval-automation

pip install -r requirements.txt

## Results

Best Model: Tuned Random Forest

F1 Score: 87%

ROC-AUC: 90%

Future Work

Integrate generative AI for enhanced credit recommendations.

Add interactive financial tools for loan applicants.

Strengthen fairness and transparency in collaboration with regulators.

📧 Contact

Hellen Amimo Otieno
📍 MSc Data Analytics
🔗 www.linkedin.com/in/hellen-otieno

📧 hellenamimo72@gmail.com
