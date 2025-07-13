# Credit Card Fraud Detection System

A complete end-to-end Credit Card Fraud Detection solution combining machine learning, REST API, and a Flutter frontend for real-time transaction analysis.

---

## 🚀 Project Overview

This project uses Logistic Regression and Random Forest models trained on a real-world credit card dataset to detect fraudulent transactions. It applies dynamic threshold tuning for better accuracy and velocity checks to flag suspicious transaction patterns.

The backend is built with Flask, exposing an API that accepts CSV transaction files and returns fraud predictions along with detailed context. A Flutter app serves as the frontend, allowing users to upload transaction data and instantly see fraud detection results and alerts.

---

## ✨ Key Features

- **Dual ML Models:** Logistic Regression and Random Forest for fast and accurate fraud detection  
- **Dynamic Thresholding:** Uses F1-score optimization for best precision-recall balance  
- **Transaction Velocity Monitoring:** Flags rapid multiple transactions that indicate fraud attempts  
- **Contextual Fraud Explanation:** Provides human-readable reasons for each flagged transaction  
- **REST API:** Easy integration via a Flask-based API accepting CSV files  
- **Flutter Frontend:** User-friendly mobile app for uploading CSVs and visualizing results  
- **SMS Alert Simulation:** Alerts for high-risk activities and unusual transaction patterns

---

## 📦 Tech Stack

- **Backend:** Python, Flask, scikit-learn, pandas, joblib  
- **Frontend:** Flutter, Dart, http, file_picker  
- **Visualization:** Matplotlib, Seaborn  
- **Data:** Kaggle Credit Card Fraud Dataset

🎯 Future Enhancements
Add user authentication and secure API access

Deploy backend to cloud platforms like AWS, GCP, or Railway

Implement real SMS/email alerts for flagged fraud

Develop a live dashboard to monitor transactions and trends

Support streaming data analysis with Kafka or WebSockets

Add multi-language support on frontend (English + local languages)

📜 License
MIT License — feel free to use and improve this project!

🙌 Credits
Dataset from Kaggle Credit Card Fraud Detection
