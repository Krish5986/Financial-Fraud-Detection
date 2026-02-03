# Financial Fraud Detection Pipeline

### 📌 Project Overview
This project involves building an end-to-end Machine Learning pipeline to detect fraudulent transactions in a massive financial dataset. The goal was to develop a robust model capable of identifying fraud patterns within **6.3 million transaction records**, focusing on precision and minimizing false positives.

This analysis was conducted as part of a Data Analyst case study for Accredian.

### 🚀 Key Features
* **Large-Scale Data Processing:** Efficiently handled and cleaned a dataset of **6.3 million rows** involving financial transfer logs.
* **Advanced Feature Engineering:**
    * Created new features to track balance discrepancies (origin vs. destination accounts).
    * Calculated **Variance Inflation Factor (VIF)** to detect and remove multicollinearity between independent variables.
* **Model Architecture:** Implemented a **Random Forest Classifier** optimized for imbalanced data.
* **Strategic Insights:** Derived actionable insights on fraud prevention and real-time monitoring strategies.

### 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Techniques:** SMOTE (imbalance handling), VIF Analysis, Correlation Matrix

### 📊 Results
* **Precision:** Achieved **95% precision** on the fraud class, ensuring reliable detection with minimal false alarms.
* **Key Drivers:** Identified that specific transaction types (CASH_OUT and TRANSFER) were the primary vectors for fraud.

---
*Created by Krish*
