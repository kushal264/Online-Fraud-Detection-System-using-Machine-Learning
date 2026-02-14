# Online-Fraud-Detection-System-using-Machine-Learning
This project implements a Machine Learning-based Fraud Detection System that predicts whether a financial transaction is fraudulent in real time.  The system is deployed using Streamlit, allowing users to input transaction details and instantly receive a fraud prediction.
 📌 Problem Statement

With the rapid growth of digital payments, fraudulent transactions have increased significantly. Financial institutions require:

Real-time fraud detection

High accuracy with minimal false positives

Scalable and reliable prediction systems

This project addresses these challenges using a supervised binary classification model.

⚙️ System Architecture

Workflow:

User enters transaction details via Streamlit UI

Input data is converted into a structured Pandas DataFrame

Pre-trained ML pipeline (.pkl file) is loaded using Joblib

Model processes features

Binary output generated:

1 → Fraud

0 → Legitimate

Architecture Flow:

User → Streamlit UI → ML Pipeline (.pkl) → Prediction → UI Result

🛠 Tech Stack

Python

Scikit-learn – Model building & pipeline

Pandas – Data handling

Joblib – Model serialization

Streamlit – Deployment interface

📊 Model Type

Supervised Binary Classification Model

Designed for real-time fraud prediction

🚀 Features

Real-time transaction classification

Interactive web-based interface

End-to-end ML pipeline integration

Lightweight and deployable architecture

📂 Project Structure
├── fraud_detection_pipeline.pkl
├── app.py
└── README.md

📈 Future Improvements

Add probability score output

Deploy on cloud (AWS / Render / Streamlit Cloud)

Improve model performance with advanced algorithms

Add transaction history visualization
