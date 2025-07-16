# 💊 Pharma Sales Time Series Analysis & Forecasting

Welcome to the **Pharma Sales Forecasting** project — a comprehensive time series analysis pipeline built to analyze and predict pharmaceutical product sales over time. This project combines statistical modeling, data visualization, and machine learning techniques to forecast trends and support data-driven decision-making in the healthcare domain.

---

## 📌 Project Overview

This repository presents an end-to-end workflow for:
- Exploring and visualizing pharmaceutical sales data
- Preprocessing and cleaning time series data
- Detecting and handling outliers
- Forecasting future sales using statistical models like **ARIMA** and **SARIMAX**

---

## 🗃️ Dataset Summary

- **Duration**: January 2014 to October 2019  
- **Frequency**: Monthly  
- **Drugs Analyzed**: 57 drugs grouped into 8 categories based on the **ATC (Anatomical Therapeutic Chemical) Classification System**:

### 🔬 ATC Drug Categories

- **M01AB** – Non-steroidal Anti-inflammatory (Acetic acid derivatives)  
- **M01AE** – Non-steroidal Anti-inflammatory (Propionic acid derivatives)  
- **N02BA** – Analgesics & Antipyretics (Salicylic acid derivatives)  
- **N02BE** – Analgesics & Antipyretics (Pyrazolones & Anilides)  
- **N05B** – Psycholeptics – Anxiolytics  
- **N05C** – Psycholeptics – Hypnotics & Sedatives  
- **R03** – Drugs for Obstructive Airway Diseases  
- **R06** – Systemic Antihistamines  

---

## 📊 Exploratory Data Analysis (EDA)

- Performed statistical summaries and time-based visualizations  
- Analyzed sales distribution by drug category  
- Identified key patterns in seasonality and sales spikes

---

## 🧹 Data Preprocessing

- Converted `datum` column to `datetime` format  
- Extracted `year` and `month` as separate features  
- Replaced zero values with mean sales per drug for data integrity  

---

## ⚠️ Outlier Detection

- Used box plots to visualize sales distributions  
- Detected and handled zero or extreme values appropriately

---

## 📈 Time Series Analysis

- Decomposed time series into **trend**, **seasonality**, and **residuals**  
- Tested stationarity using the **Augmented Dickey-Fuller (ADF)** test  
- Differenced non-stationary series for modeling

---

## 🔮 Forecasting

- Implemented and tuned **ARIMA** and **SARIMAX** models  
- Forecasted future sales across each drug category  
- Visualized predicted vs actual trends to interpret model performance

---

## 📁 Repository Structure

