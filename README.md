 Darknet Threat Detection with Python & Power BI

 Capstone Project: Big Data Analytics
 
🚀 Overview

This project tackles the challenge of detecting and analyzing illicit activities on the Darknet using Big Data Analytics. 
By leveraging data from hidden marketplaces, forums, and 
anonymized network traffic, we build a model that identifies suspicious patterns, user behaviors, and potential threats


🎯 Problem Statement
How can STEG detect fraudulent activities from their customers while improving satisfaction and maintaining operational efficiency?

The objective is to classify customers into two categories:

Fraudulent (1)
Not Fraudulent (0)
Using past behavior and billing data, we aim to identify suspicious patterns using supervised machine learning models

🧠 Objectives

Develop a machine learning model to classify potentially malicious or suspicious darknet activities.

Analyze hidden network traffic patterns, communication behavior, and marketplace/user profiles.

Enhance the accuracy of threat detection to support cybersecurity analysts and law enforcement agencies.

Utilize Python for modeling and Power BI for visualizing darknet activity insights.

Enable real-time monitoring and actionable intelligence for proactive threat mitigation.

🛠️ Tools & Technologies

Python – for data preprocessing, modeling, and analysis

Pandas, NumPy – for efficient data manipulation and transformation

Scikit-learn, XGBoost, LightGBM – for building and tuning machine learning classification models

Google Colab – as the collaborative development environment

Power BI – for visualizing darknet activity trends and threat patterns

Tor Network Datasets / Darknet Logs – as sources for training and testing

Kaggle / Zindi / Custom Evaluation Scripts – for model evaluation and benchmarking

📊 Evaluation
The model’s performance is evaluated using classification metrics such as ROC-AUC, Precision, Recall, and F1-score, which measure how effectively the system distinguishes between malicious and benign darknet
 
## 📊 Dataset Information  
- **Dataset Title:** Fraud Detection in Electricity and Gas Consumption Challenge *(replace if using a different darknet dataset)*  
- **Source Link:** [Darknet Dataset](https://zindi.africa/competitions/fraud-detection-in-electricity-and-gas-consumption-challenge)  
- **Number of Rows and Columns:** ~1,939,730 rows × 20 columns  
- **Data Structure:**
- - **Data Status:** 


### 🐍 Python (Jupyter Notebook)

Loading data using panda analysing dataset information

<img width="368" height="150" alt="image" src="https://github.com/user-attachments/assets/17e3d6fd-bd3e-4722-b366-f95e807c5380" />

~~~
import pandas as pd

def load_dataset(url=".Darknetsv"):
    df = pd.read_csv(url, encoding='latin1')
    return df

load_dataset()

~~~
### 📈 Power BI
- Dashboard Design with Filters, Slicers, and Drill-downs  
- Visuals: Line charts, bar charts, maps, pie charts  
- DAX Formulas and Tooltips for dynamic interactivity

## 🧪 Methodology

1. **Data Collection** from darknet sources  
2. **Preprocessing:** Handle missing values, outliers, encode and scale features  
3. **Exploratory Data Analysis (EDA):** Use charts, stats, and plots  
4. **Modeling:** Apply ML model (e.g., clustering, classification)  
5. **Evaluation:** Use metrics like accuracy, precision, F1-score  
6. **Visualization:** Build Power BI dashboard  
7. **Innovation:** Implement anomaly detection or NLP insights

---

## 📌 Strategic Insights

- Integrating multiple sources improves detection accuracy  
- NLP helps uncover suspicious communication trends  
