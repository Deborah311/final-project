# 🌐 Darknet Threat Intelligence: Big Data Analytics for Hidden Networks

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🚀 Overview

This capstone project aims to explore and analyze **Darknet activity data** to uncover hidden threats and patterns using **Big Data Analytics**. By combining the power of **Python** for data analysis and **Power BI** for visualization, this project provides a comprehensive end-to-end pipeline to understand and detect potential risks within dark web traffic and forums.

> 📚 Course: INSY 8413 | Introduction to Big Data Analytics  
> 🧑‍🏫 Lecturer: Assistant Lecturer Eric Maniraguha  
> 📆 Academic Year: 2024–2025, SEM III  
> 📍 Institution: Adventist University of Central Africa (AUCA)

---

## ❓ Problem Statement

How can we leverage big data analytics techniques to monitor, detect, and visualize suspicious activities in Darknet traffic to improve cybersecurity decision-making?

---

## 🎯 Objectives

- 📥 Ingest and preprocess Darknet-related datasets (e.g., logs, traffic, transactions).
- 📊 Explore data to identify anomalies, suspicious behavior, or hidden patterns.
- 🤖 Apply ML techniques for classification of potentially malicious activities.
- 📈 Build interactive dashboards using **Power BI** to visualize threats and indicators.
- 📡 Provide strategic insights to help mitigate darknet-related cyber threats.

---

## 💡 Innovations

- 🔎 **Multisource Data Fusion**: Merging structured and unstructured darknet logs to gain deeper visibility.
- 🧠 **Threat Intelligence via ML**: Using classifiers to identify possible malicious actors or activities.
- 📊 **Live Power BI Dashboard**: Dynamic reports for non-technical stakeholders to monitor darknet trends.
- ⚡ **Hybrid Workflow**: Combining Python in Google Colab for backend analysis with Power BI for business insights.

---

## 🔍 Dataset Information

- **Source**: Publicly available Darknet Traffic datasets (e.g., [CIC Darknet](https://www.unb.ca/cic/datasets/darknet.html))
- **Rows**: 1,000,000+ entries (varies by dataset)
- **Columns**: IP Address, Port, Protocol, Country, Timestamp, Flags, Attack Type, etc.
- **Format**: CSV, JSON, PCAP

> You may upload your dataset under the `data/` folder for reproducibility.

---

## 🔬 Methodology

1. **Data Collection**
   - Downloaded open-access darknet datasets
   - Verified schema and structure

2. **Preprocessing (Python & Pandas)**
   - Null handling, normalization, data type conversion
   - Label encoding, filtering for specific indicators

3. **Exploratory Data Analysis**
   - IP trends, attack frequency by port, countries involved
   - Detected anomalies using visual tools and statistics

4. **Machine Learning (Optional)**
   - Logistic Regression or Decision Trees for classification
   - ROC-AUC, Precision, Recall as evaluation metrics

5. **Visualization (Power BI)**
   - Built a real-time, filterable dashboard
   - KPIs: Attack Frequency, Protocols, Suspicious IPs

---

## 🛠️ Tools & Technologies

| Tool            | Purpose                            |
|-----------------|------------------------------------|
| 🐍 Python        | Data manipulation & preprocessing  |
| 📘 Pandas, NumPy | Data cleaning and transformation  |
| 📊 Power BI      | Data visualization & dashboarding |
| 🧠 Scikit-learn  | Machine learning classification   |
| ☁️ Google Colab  | Cloud-based Python development    |
| 📁 GitHub        | Version control and project repo  |
---

## 📎 Screenshots



<br> *🔍 Data Exploration*
<img src="https://github.com/user/repo/assets/data_exploration.png" width="700"/>

<br> *📊 Power BI Dashboard*

<img width="825" height="491" alt="image" src="https://github.com/user-attachments/assets/c7356133-e3b6-4868-aa7c-b418384508c7" />

---
---

## 📈 Key Visualizations

- Suspicious IP heatmap
- Protocol usage distribution
- Country-based threat sources
- Time series of attacks
- Flag types and anomalies

*All visualizations are exported as PNGs and available in the `reports/` folder and live in the Power BI dashboard.*

---

## 🧪 Evaluation Metrics

- **Precision & Recall**: For identifying true positive threats
- **ROC-AUC**: For classifier effectiveness
- **F1 Score**: For balanced threat detection
- **Threat Surface Analysis**: Based on IP density and protocol exploitation

---

## 🔐 Strategic Insights

- A small percentage of ports account for the majority of malicious activity.
- Suspicious activities spike during certain time windows—indicating automation.
- Geolocation analysis reveals regions contributing heavily to attacks.

---

## 🚧 Challenges Faced

- 🔄 Data imbalance in malicious vs. benign entries
- ⚙️ Difficulty in decoding obfuscated darknet data
- 📉 Limited labeled data for supervised learning

---

## 🧭 Way Forward

- Incorporate **Natural Language Processing (NLP)** to mine dark web forums.
- Integrate **real-time streaming data** using tools like Apache Kafka or Spark.
- Expand classification using ensemble methods (e.g., Random Forest, XGBoost).
- Use advanced network analysis (e.g., graph theory) to detect actor connections.

---

## 📌 Recommendations

- Organizations should continuously monitor darknets to stay ahead of threats.
- Invest in automated AI/ML systems for proactive threat identification.
- Leverage visualization tools like Power BI to democratize cybersecurity data.
- Encourage collaboration between governments, ISPs, and cybersecurity agencies.

---

## 📝 Acknowledgments

Special thanks to:
- **Eric Maniraguha**, Assistant Lecturer at AUCA
- The **CIC Research Lab**, University of New Brunswick for dataset availability  
- **Zindi** and **Kaggle** for platform evaluatio
