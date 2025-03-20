# Fraud Detection in Financial Transactions: Data Cleaning & Visualization

## 📌 Project Overview
Fraud detection is a critical challenge in the financial sector, where millions of transactions occur daily. Detecting fraudulent activities in real-time is essential to prevent financial losses and enhance security. However, due to the vast volume of transactions, identifying fraud patterns requires a combination of **data preprocessing, sampling techniques, and visualization tools**.

In this project, I analyzed a **large dataset of financial transactions (over 6 million records)**, applied **data cleaning techniques**, and performed **random sampling** to balance the dataset between fraudulent and non-fraudulent transactions. Using **Tableau**, I developed an **interactive dashboard** that provides insights into **fraudulent transaction trends, high-risk merchants, and suspicious activities over time**. This project aims to **identify fraud patterns, improve anomaly detection, and support decision-making for financial institutions**.

---
## 📂 Data Understanding & Preprocessing

### 🛠 **Cleaning Data:**
- Converted numerical fields (**Amount, Old Balance, New Balance**) for better consistency.
- Extracted transaction timestamps and converted **step (hourly data) into days** for trend analysis.
- Removed **duplicate and incomplete records** to ensure data quality.

### 🎯 **Handling Data Imbalance:**
- The dataset contained **6.3 million transactions**, with only **8,000 fraudulent transactions**.
- **Random sampling** was applied, selecting **200,000 non-fraudulent transactions** while keeping all fraudulent ones.
- This approach improved **data balance**, ensuring fairer analysis and more reliable insights.

---
## 📊 Data Visualization (Tableau)
### **1️⃣ Transaction Overview**
- Distribution of **fraudulent vs. non-fraudulent transactions**.
- **Total transactions and average transaction amount**.
- **Highest transaction amount and fraud transaction ratio**.

### **2️⃣ Time-Series Analysis**
- Transaction **volume over time** to identify patterns.
- **Peak transaction hours and days**.

### **3️⃣ Merchant & Transaction Analysis**
- **Top recipients of high-value transactions**.
- **Merchants with high occurrences of fraudulent transactions**.

### **4️⃣ Interactive Filtering**
- A **Fraudulent vs. Non-Fraudulent button** allows users to dynamically switch between insights.
- Filters for **transaction types** (cash-in, cash-out, transfer, etc.).
- Weekly distribution of transactions.

---


---
## 🛠 Project Tools Used
✅ **Data Cleaning & Preprocessing:** Excel  
✅ **Data Visualization:** Tableau  
✅ **Sampling & Data Processing:** Random Sampling  

---
## 🔎 Conclusion
This project provides a **data-driven approach to fraud detection**, helping to visualize **fraudulent trends and anomalies**. The dashboard is **interactive**, allowing financial analysts to filter transactions and identify high-risk transactions quickly.

By applying **data preprocessing, sampling techniques, and visual analytics**, this project demonstrates how **fraudulent transactions can be detected and analyzed effectively** to improve financial security and risk management.
