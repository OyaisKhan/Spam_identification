📡 KMeans‑based Spammer Detection with Real‑Time Alerts
Final Year Project | Dec 2023 – Mar 2024

A novel machine learning system using K‑means clustering to analyze SMS/communication patterns, detect spammer activity, and trigger real‑time alerts. Built upon the sms-spam-detection codebase by thantthet, enhanced to support anomaly scoring and live notification functionality.

🔍 Project Overview
Objective: Detect spam messages/clusters using unsupervised learning, alert users proactively.

Dataset: UCI SMS Spam Collection (~5,600 labeled SMS) 

Approach:

Preprocessing: Load SMS data → clean → TF‑IDF vectorization

K‑means Clustering: Group messages into candidate spam/ham clusters 


Anomaly Detection: Identify clusters/messages deviating from typical 'ham' patterns

Real‑Time Alerts: Upon detecting an anomaly, the system sends notifications (configurable via console, email, or push)

🛠️ Tech Stack
Language: Python 3.x

Key Libraries:

scikit-learn for K-means and TF-IDF

pandas, numpy for data handling

Flask or custom alerting scripts for notification delivery

📋 Repository Structure
bash
Copy
Edit
.
├── dataset/                   # SMS Spam Collection raw data
├── spam_detector.py          # Core clustering + alerting logic
├── alerting/                 # Notification module (console/email/push)
├── results/                  # Output CSV / metrics / logs
├── requirements.txt          
└── README.md
🚀 Getting Started

UCI Machine Learning Repository for the SMS dataset
