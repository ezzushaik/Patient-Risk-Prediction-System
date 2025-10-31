# Patient-Risk-Prediction-System
# 🩺 Patient Risk Prediction System

An AI/ML-powered healthcare solution designed to predict patient readmission risk and alert doctors early.

## 🚨 Problem
Hospitals face high patient readmission rates due to manual monitoring, delayed interventions, and lack of predictive insights.

## 💡 Solution
A cloud-based system that collects patient data, preprocesses it, trains an ML model (XGBoost / Random Forest) on AWS SageMaker or Azure ML, and deploys a Flask dashboard for real-time doctor alerts.

## 🧱 Architecture
- Data Storage: AWS S3 / Azure Blob
- Model: Random Forest / XGBoost
- Cloud: SageMaker / Azure ML
- Database: AWS RDS / Firestore
- Deployment: Flask / Streamlit
- Monitoring: CloudWatch / Stackdriver

## ⚙️ Run Locally
```bash
pip install -r requirements.txt
python model/train_model.py
python app/app.py
```
Then visit: [http://localhost:8080](http://localhost:8080)

## 📦 Files
- patient_risk_all_in_one_v2.pdf — Full report (summary + architecture)
- architecture.png — System diagram
- app/ — Flask API and UI
- model/ — Training and prediction scripts

## 👨‍💻 Author
**SHAIK MOHAMMAD ELIYAZ**  
📧 eliyazbasha18@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mohammad-eliyaz-shaik-105617250/)  
💻 [GitHub](https://github.com/ezzushaik)
