# Churn Prediction Model for Telecommunication Companies Based on Huawei SmartCare

## Project Overview
This project was developed as part of the Huawei Internship Program (Carrier Network Business Group) in collaboration with Kuwait University. It replicates a simplified version of Huawei SmartCare’s churn analysis capabilities using analytics on public telecom data.  
The goal was to simulate how SmartCare monitors customer experience and predicts churn by engineering SmartCare-style metrics (KQI, SQM, NPM) and training predictive models to identify at-risk customers.

## Supervisors

- **Supervisor Trainee:** Dr. Essam Alruqobah  
- **Supervisor Engineer:** Eng. Ali Alsairafi  
- **Supervisor Huawei Site:** Eng. Rahaf Alhasan


## Problem Statement
Telecom companies increasingly face customer churn, which directly impacts revenue and customer loyalty. Inspired by Huawei’s SmartCare platform, this project uses machine learning to simulate churn detection by analyzing service usage, demographics, and simulated customer experience metrics like KQI, SQM, and NPM.


## Dataset
- **Title:** Telco Customer Churn  
- **Source:** [Kaggle - blastchar](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Provider:** IBM  
- **Size:** 7,043 customer records  
- **Features:**
  
          1. **Churn Status**
            - Whether the customer left within the last month (`Churn` column)

          2. **Subscribed Services**
            - Phone service
            - Multiple lines
            - Internet service
            - Online security
            - Online backup
            - Device protection
            - Tech support
            - Streaming TV and movies

          3. **Account Information**
            - Customer tenure (in months)
            - Contract type (Month-to-month, One year, Two year)
            - Payment method
            - Paperless billing status
            - Monthly charges
            - Total charges

          4. **Demographics**
            - Gender
            - Senior citizen status
            - Partner status
            - Dependents

## Project Pipeline
1. Data Collection  
2. Data Preprocessing  
3. Feature Engineering (KQI, SQM, NPM)  
4. Model Training & Tuning (Logistic Regression, XGBoost, Optuna)  
5. Model Evaluation (Accuracy, Recall, F1-score)  
6. Insight Generation  
7. SmartCare Simulation Personas & Dashboards (Futuer Work)

## Tools & Technologies
- Python (Colab Notebook)  
- pandas, NumPy  
- scikit-learn, XGBoost, Optuna  
- matplotlib, seaborn  
- StandardScaler, OrdinalEncoder, LabelEncoder

## Integration with LINK. Platform

This machine learning model is deployed as part of the larger **LINK. – AI-Powered Customer Retention Platform for Telecoms**
The MERN full-stack architecture includes:
- **Frontend** – React.js dashboard for telecom operators  
  → [View Frontend Repo](https://github.com/halacoded/LINK.)

- **Backend** – Node.js + Express API for handling user authentication and model requests  
  → [View Backend Repo](https://github.com/halacoded/LINK-Backend)

- **Flask Microservice** – Interfaces with this model to provide churn predictions via REST API  
  → [View Flask Microservice Repo](https://github.com/halacoded/LINK-FLASK-Microserver)

## License & Usage
This project is open-source and free to use for educational and non-commercial purposes.  
Feel free to explore, modify, and build upon this code to support your own learning or telecom analytics projects.

## Installation & Setup
### Prerequisites
- Python 3.x
- COLAP 
- Optuna
  
Click COLAP Link and Download the Dataset and prerequisites, then you are ready to start

## Contributors
- Hala Almutairi – Project Developer & Intern  
