# **Data Preparation and Feature Selection for Machine Learning**  

## **Project Overview**  
This project focuses on **data cleaning, augmentation, merging, and feature selection** to create a structured dataset for machine learning. The goal is to improve data quality and ensure consistency before using it in predictive models.

---

## **Key Tasks**  

### **1. Data Cleaning and Augmentation**  
- Loaded the **customer transactions dataset**.  
- Handled **missing values** using mean, median, mode imputation, and predictive modeling.  
- Applied **synthetic data generation** techniques, including:  
  - Adding random noise to numerical values.  
  - Using **SMOTE** for data balancing.  
  - Applying log transformation for skewed data.  
- Saved the cleaned dataset as `customer_transactions_augmented.csv`.  

### **2. Merging Datasets**  
- Merged **customer transactions** with **social profile data**, linking them using an **ID mapping dataset**.  
- Standardized different customer ID formats to maintain consistency.  
- Handled cases where a single customer ID had multiple records.  
- Saved the merged dataset as `final_customer_data_[Databases-Peer-2].csv`.  

### **3. Feature Selection**  
- Created a **Customer Engagement Score** using transaction history and social media activity.  
- Engineered new features like:  
  - Moving averages of transactions.  
  - Time-based purchase aggregation.  
  - Text-based features using **TF-IDF**.  
- Identified **highly correlated features** using a **correlation heatmap**.  
- Selected the **top 10 most important features** using **SelectKBest**.  
- Saved the final dataset as `final_dataset_ready_[groupNumber].csv`.  

---

## **Presentation**  

📜 VIDEO [LINK](https://youtu.be/kFfM_hPpt6c)

---


## **Contributors**  

### **Data Cleaning and Augmentation**
- **[Name]** – Processed missing values, applied augmentation techniques.  

### **Dataset Merging**
- **[Name]** – Merged multiple datasets, standardized formats.  

### **Feature Selection**
- **Peter Johnson** – Analyzed correlations and selected key features.  

### **Project Documentation**
- **Peter Johnson & Glen Bonyu** – Organized reports, notebooks, and project structure.  

---

## **Conclusion**  
This project ensures **clean, structured, and well-prepared data** for machine learning. By handling missing values, merging datasets, and selecting key features, it provides a high-quality dataset ready for predictive modeling.
