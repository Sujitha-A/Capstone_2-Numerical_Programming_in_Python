# Capstone_2-Numerical_Programming_in_Python
This repository contains files for the capstone project for Module 2: Numerical Programming in Python.

# 📱 Play Store App Review Analysis

## 🧠 Overview

This project analyzes Google Play Store app metadata and user reviews to uncover the key factors that drive app engagement and success. By combining structured data (e.g., category, rating, installs, price) with unstructured user feedback, we explore how different features and sentiments influence app performance.

The notebook has been refactored to meet production standards, including:
- ✅ Exception handling
- ✅ Modular functions
- ✅ Clean code structure
- ✅ Deployment-ready formatting

---

## 📂 Dataset Description

### 1. `apps.csv`
Contains metadata for each app:
- App name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated

### 2. `reviews.csv`
Contains user reviews:
- App name
- Translated review text
- Sentiment polarity (computed)
- Sentiment label (Positive, Neutral, Negative)

---

## 🎯 Business Objective

The goal is to help app developers and marketers:
- Identify features common in successful apps
- Understand user sentiment and feedback trends
- Optimize app design and pricing strategies
- Benchmark performance across categories

---

## 🔍 Key Questions Explored

- Which app categories receive the highest ratings?
- Do free apps perform better than paid ones?
- What are the most common sentiments in user reviews?
- How do installs, size, and price affect app success?

---

## 🛠️ Tools & Libraries Used

- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Visualizations
- **TextBlob** – Sentiment analysis
- **WordCloud** – Text visualization

---

## 📊 Visualizations Included

- Ratings distribution histogram
- Category-wise average rating bar chart
- Price vs Rating scatter plot
- Free vs Paid app rating comparison
- Sentiment distribution from user reviews
- Word cloud of review text

---

## 🧼 Production-Grade Features

- Modular functions for data cleaning, EDA, and sentiment analysis
- Exception handling for robust execution
- Clean and readable code with comments and docstrings
- Ready for deployment as a Python script or Streamlit app

---

## 💡 Key Insights

- Apps in categories like Productivity and Health & Fitness show high ratings but lower installs.
- Free apps dominate in downloads but receive more mixed reviews.
- Negative reviews often mention ads, bugs, and crashes.
- Positive reviews highlight ease of use and helpful features.

---

## 📌 Recommendations

- Focus on app stability and user experience to boost ratings.
- Use sentiment trends to guide feature updates.
- Benchmark against top-rated apps in similar categories.
- Monitor review feedback regularly to stay competitive.

---

## 📁 Project Structure  
  
data  
&emsp;-> Play Store Data.csv  
&emsp;-> User Reviews.csv  
playstore_eda.ipynb  
playstore_analysis.py  
requirements.txt  
README.md

---

