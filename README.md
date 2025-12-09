# 🧠 Customer Spending Score Prediction using Min-Max Scaling

This project analyzes customer behavior using the Mall Customer Segmentation dataset and applies **Min–Max Scaling** to normalize numerical features for clustering and predictive modeling. Scaling ensures that all features contribute equally to distance-based algorithms such as K-Means.

---

## 📌 Project Overview
The project focuses on:
- Understanding customer demographics and spending habits
- Cleaning and preprocessing raw data
- Encoding categorical variables
- Applying **Min-Max Scaling** to normalize numerical features
- Preparing the dataset for ML tasks such as clustering or prediction
- Visualizing distributions before and after scaling

The goal is to create a clean, standardized dataset ready for machine learning or customer segmentation.

---

## 📊 Dataset Information
**Source:** Mall Customers Dataset (Kaggle)  
**Features Included:**
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🛠️ Tech Stack
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🔧 Steps Performed

### **1. Data Import & Initial Analysis**
- Loaded dataset using Pandas  
- Checked shape, data types, missing values, and summary statistics  

### **2. Data Cleaning**
- Removed irrelevant column: `CustomerID`
- Encoded `Gender` → numeric form (0/1)
- Verified no missing values remain

### **3. Feature Scaling**
Applied **MinMaxScaler** to:
- `Age`
- `Annual Income (k$)`
- `Spending Score`

This converts all values to the range **0–1**.

### **4. Visualization**
- Distribution before scaling  
- Distribution after scaling  
- Relationship plots for income vs. spending score  

### **5. Exporting Scaled Data**
Final processed & normalized dataset saved for clustering or modeling.

---

## 🚀 Output
- Cleaned dataset  
- Scaled dataset (0–1 range)  
- Ready for ML models like clustering or customer segmentation  

---

## 📁 Project Structure
-ProjectFile_MinMaxScaling.ipynb
-Mall_Customers.csv
-README.md


---

## 📌 Author
**Tanuj Singh**  
Data Analyst | BI Developer | Creative Technologist  
📧 *tanuj.singh.da@gmail.com*  
🔗 [in/tanuj-singh-101703a1](https://www.linkedin.com/in/tanuj-singh-visuals/) / [GitHub](https://github.com/CoderTanujSingh)*

---

## ⭐ If you found this project helpful, consider giving it a star!
