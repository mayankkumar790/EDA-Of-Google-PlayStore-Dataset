# 📱 Google Play Store Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Google Play Store dataset to extract meaningful business insights. The objective is to analyze app categories, installation trends, ratings, and user engagement patterns.

The analysis helps in understanding which categories dominate the Play Store and how app performance varies across different metrics.

---

## 🎯 Problem Statement

With millions of applications available on the Google Play Store, identifying top-performing categories and apps is essential for understanding market trends.

This project answers the following key questions:

- Which category has the largest number of installations?
- What are the top 5 most installed apps in popular categories?
- How many apps have a perfect 5.0 rating?
- What is the distribution of free vs paid apps?
- What trends can be observed from installs, reviews, and ratings?

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning & Preprocessing

The dataset was cleaned and prepared using the following steps:

- Removed duplicate records based on App name
- Handled missing values
- Cleaned `Installs` and `Price` columns (removed `+`, `,`, `$`)
- Converted numerical columns to correct data types
- Processed `Last Updated` column into Day, Month, and Year
- Converted `Reviews` column to integer
- Removed inconsistent records

This ensured the dataset was structured and ready for analysis.

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Category Analysis
- Identified categories with the highest number of apps.
- Found that **GAME** category has the highest total installations.
- Family and Tools categories also contain a large number of apps.

### 🔹 Installation Trends
- Installations are highly right-skewed.
- A small percentage of apps account for the majority of total installs.

### 🔹 Rating Analysis
- Very few apps achieve a perfect 5.0 rating.
- Most apps fall within the 4.0–4.5 rating range.

### 🔹 Top Apps Analysis
- Extracted top 5 most installed apps within popular categories.
- Identified dominant apps that significantly outperform competitors.

---

## 📊 Key Insights

- 🎮 GAME category dominates in total installations.
- 📱 Majority of apps are Free, indicating a freemium-based ecosystem.
- ⭐ Perfect ratings are rare.
- 📈 App popularity distribution is highly uneven.
- 🚀 A small group of apps drives the majority of engagement.

---

## 💡 Business Implications

- High-install categories are competitive and demand strong differentiation.
- Free app model is the primary user acquisition strategy.
- Maintaining high ratings at scale is challenging.
- Market dominance is concentrated among a few high-performing apps.

---

## 📌 Conclusion

This project demonstrates strong skills in:

- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis  
- Data Visualization  
- Extracting Business Insights from Real-World Data  

The analysis reveals that the Google Play Store ecosystem is highly competitive, with a small percentage of apps generating the majority of installations and user engagement.

---

## 👤 Author

**Mayank Kumar**  
Data Analyst  
Skilled in Python, SQL, Power BI & Data Visualization  
🔗 [LinkedIn](https://www.linkedin.com/in/mayank-kumar-2003y/)  
💻 [GitHub](https://github.com/mayankkumar790)  
📧 [Mail](mailto:mayankkumar21july@gmail.com)

---
