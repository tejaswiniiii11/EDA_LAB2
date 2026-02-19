# EXPLORATION OF DATA DISTRIBUTION & VARIABILITY USING R

**Name:** Tejaswini M  
**Register Number:** 23BAD121  
**Course:** Artificial Intelligence & Data Science  

----------------------------------------------

## 📌 Project Overview

This project explores data distribution and variability using advanced visualization techniques.

A startup analyzes e-commerce transaction data to understand customer spending behavior and detect abnormal purchase patterns.

The lab demonstrates how histograms, boxplots, and heatmaps help identify trends, variability, and outliers in transaction data.

-------------------------------------------------

## 🗂️ Dataset Information

**File Name:** `2.ecommerce_transactions.csv`  
**Type:** CSV file containing e-commerce transaction records  

-------------------------------------------------

## 📄 Key Attributes

- **Transaction_Date** – Date of purchase  
- **Transaction_Amount** – Value of each transaction  
- **Product_Category** – Category of purchased product  

The dataset represents transaction-level data used to analyze customer spending patterns.

-------------------------------------------------

## 🛠️ Tools & Libraries Used

### Software
- R  
- RStudio  

### Libraries
- `ggplot2` – Data visualization  
- `dplyr` – Data manipulation  
- `lubridate` – Date handling and month extraction  

------------------------------------------------

## ⚙️ Implementation Steps

### 1️⃣ Data Loading & Preprocessing

- Imported dataset using `read.csv()`  
- Converted `Transaction_Date` into Date format  
- Used `lubridate::month()` to extract month for time-based analysis  

------------------------------------------------

### 2️⃣ Histogram – Transaction Amount Distribution

- Plotted histogram using `geom_histogram()`  
- Used 20 bins to visualize spending distribution  
- Analyzed frequency of different transaction ranges  

📊 **Output:** Histogram of Transaction Amounts  

------------------------------------------------

### 3️⃣ Boxplot – Outlier Detection

- Plotted boxplot using `geom_boxplot()`  
- Visualized median, quartiles, and spread  
- Identified abnormal high or low transactions  

📊 **Output:** Boxplot of Transaction Amounts  

------------------------------------------------

### 4️⃣ Heatmap – Monthly Sales Intensity

- Extracted month from transaction date  
- Grouped data by Product_Category and Month  
- Calculated total sales per month per category  
- Used `geom_tile()` to create heatmap  

📊 **Output:** Heatmap of Monthly Sales Intensity  

------------------------------------------------

## 📈 Visualizations Generated

- Histogram of transaction amounts  
- Boxplot for outlier detection  
- Heatmap of monthly sales intensity by product category  

All visualizations were created using `ggplot2`.

------------------------------------------------

## 🎯 Key Insights

- Histogram reveals spending distribution patterns.  
- Boxplot helps detect abnormal transactions or outliers.  
- Heatmap highlights high and low sales months across product categories.  

These techniques assist businesses in identifying customer behavior trends and potential risk patterns.

