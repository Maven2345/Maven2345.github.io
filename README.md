# Hi, I'm Rafael Marvin Gert Karawora 👋
### Cybersecurity Analyst | SIEM & SOC Specialist | Fraud Analytics Specialist

I am a detail-oriented Cybersecurity professional focused on protecting institutional data integrity through advanced analytics, SIEM orchestration, and proactive threat defense.

---

## 🛡️ Top Verified Credentials
- **Fraud Detection on Financial Transactions (Google Cloud)** | [Verify Credential](https://coursera.org/verify/4BQ76ZMGPIL3)
- **Advanced Ethical Hacking & Cybersecurity** | [Verify Credential](https://coursera.org/verify/GZAEFEZKKPDM)
- **System & Network Security Essentials** | [Verify Credential](https://coursera.org/verify/KFGNYDJJLVVW)
- **GenAI for Fraud Analysts: Improving Detection** | [Verify Credential](https://coursera.org/verify/656IB45SGUZN)

---

## 🚀 Featured Security Labs

### 📡 [Wazuh SIEM/XDR Orchestration](https://github.com/Maven2345/Wazuh-SOC-Orchestration)
*Designed and deployed a centralized Security Operations Center (SOC) environment.*
* **Objective:** Real-time log analysis and endpoint monitoring.
* **Key Achievement:** Configured **Active Response** to automatically mitigate SSH/RDP brute-force attacks and implemented **File Integrity Monitoring (FIM)** for sensitive system files.
* **Stack:** Wazuh, Ubuntu Server, Docker, RegEx.

### 💳 [AI-Driven Fraud Detection System](https://github.com/Maven2345/fraud-detection-system)
*Developing high-precision financial integrity models on Google Cloud.*
* **Objective:** Detect sophisticated credit card fraud in imbalanced datasets.
* **Key Achievement:** Leveraged **Generative AI** for data balancing and utilized **Random Forest** classifiers to achieve 99.9% detection accuracy.
* **Stack:** Python, SQL, Google Cloud Platform (GCP), BigQuery.

### 🕵️ [Information Integrity: Fake News Detector](https://github.com/Maven2345/fake-news-detector)
*NLP-based defense against social engineering and misinformation.*
* **Objective:** Classify and filter malicious news data.
* **Key Achievement:** Built an NLP pipeline using **Passive Aggressive Classifiers** to analyze linguistic patterns and metadata.
* **Stack:** Scikit-learn, TF-IDF Vectorization, Python.

---

## 🛠️ Technical Arsenal

| Category | Skills & Tools |
| :--- | :--- |
| **Security Ops** | SIEM (Wazuh), SOC Workflows, Incident Response, Threat Hunting |
| **Defense** | Network Hardening, Vulnerability Management, NIST Framework |
| **Data & AI** | SQL (BigQuery), Fraud Analytics, Python (Pandas/Scikit-learn), GenAI |
| **Infrastructure** | Google Cloud (GCP) Security, Linux Admin (Fedora/Debian), Microsoft 365 |

---

## 📈 GitHub Stats
![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=Maven2345&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Maven2345&layout=compact&theme=tokyonight)

---

## 📫 Connect with Me
- **LinkedIn:** [linkedin.com/in/gert-karawora-11373818a](https://linkedin.com/in/gert-karawora-11373818a)
- **Portfolio Website:** [https://Maven2345.github.io](https://Maven2345.github.io)
# 💳 Credit Card Fraud Detection System
### Machine Learning for Financial Integrity & Risk Mitigation

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![GCP](https://img.shields.io/badge/Cloud-Google_Cloud-orange.svg)](https://cloud.google.com/)
[![Verified](https://img.shields.io/badge/Certification-Verified-green.svg)](https://coursera.org/verify/4BQ76ZMGPIL3)

## 📌 Project Overview
This project focuses on the identification of fraudulent credit card transactions using advanced Machine Learning techniques. Financial fraud detection is a critical challenge due to **highly imbalanced datasets** (fraudulent cases are rare compared to legitimate ones). 

In this lab, I implemented a robust pipeline that leverages **Google Cloud Platform (GCP)** and **Generative AI** to enhance detection accuracy and reduce false positives.

## 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, Scikit-learn, Imbalanced-learn (SMOTE), Matplotlib, Seaborn
* **Infrastructure:** Google Cloud Platform (GCP), BigQuery
* **Methodology:** Random Forest Classifier, Generative AI for Synthetic Data Balancing

## 🚀 Key Features
- **Data Preprocessing:** Handled 284,000+ transactions, performing scaling on 'Amount' and 'Time' features.
- **Handling Class Imbalance:** Utilized **SMOTE** (Synthetic Minority Over-sampling Technique) and GenAI to balance the training data, ensuring the model doesn't ignore fraud cases.
- **Fraud Classification:** Trained a **Random Forest Classifier** to achieve high precision and recall.
- **Risk Assessment:** Developed a scoring system to flag transactions for human review based on probability thresholds.

## 📊 Performance Metrics
The model was evaluated using the Area Under the Precision-Recall Curve (AUPRC), which is more effective for imbalanced fraud data than standard accuracy:
* **Precision:** 0.99
* **Recall:** 0.92
* **AUPRC Score:** 0.95

## 📁 Repository Structure
```text
├── data/               # Dataset documentation (Note: Original data is kept private)
├── notebooks/          # Jupyter Notebooks for Exploratory Data Analysis (EDA)
├── scripts/            # Python scripts for training and prediction
├── sql/                # BigQuery SQL queries for transaction filtering
└── README.md           # Project documentation
