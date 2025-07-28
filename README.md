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
- Current Ver
- Android Ver

### 2. `reviews.csv`
Contains user reviews:
- App name
- Translated review text
- Sentiment
- Sentiment polarity (computed)
- Sentiment label (Positive, Neutral, Negative)

---

## 🎯 Business Objective

The goal is to help app developers and marketers:
- Identify features common in successful apps
- Understand user sentiment and rating trends
- Optimize app design and pricing strategies
- Benchmark performance across categories

---

## 🔍 Key Questions Explored

- Which app categories receive the highest ratings?
- Do free apps perform better than paid ones?
- How do installs, size, and price affect app success?

---

## 🛠️ Tools & Libraries Used

- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib, Seaborn & Plotly** – Visualizations
- **DateTime** - Date and Time manipulations

---

## 📊 Visualizations Included

- Bar Chart - Number of apps released per year
- Bar Chart - Apps per Category
- Treemap - Total Installs and Average Rating per Category
- Bar Chart - average number of installs per apps grouped by their 'Category'
- Bar Chart - Average of Reviews per genre
- Bar Chart - Installs vs Size
- Bar Charts - Distribution of Apps by Type
- Box Plot - Family Category Analysis
- Scatter Plot - Rating vs Reviews vs Installs
- Bar Chart - Installs vs content rating
- Bar Charts - Sentiment per category
- Correlation Heatmap of App Features
- Pair Plot for Apps(Reviews, Rating and Installs)
  
---

## 🧼 Production-Grade Features

- Modular functions for data cleaning and EDA
- Exception handling for robust execution
- Clean and readable code with comments
  
---

## 📌 Recommendations

- Prioritize app quality and user experience to achieve high ratings and positive sentiment.
- Focus on high-engagement categories while being mindful of the competition.
- Adopt a freemium model for most apps, but consider paid options for niche categories with high value.
- Actively monitor and respond to user feedback to continuously improve your app and user satisfaction.

---

## 📁 Project Structure  

README.md     
data  
&emsp;-> Play Store Data.csv  
&emsp;-> User Reviews.csv  
playstore_eda.ipynb   
requirements.txt  

---

