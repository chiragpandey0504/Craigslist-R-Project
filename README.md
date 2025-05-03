# Craigslist Cars & Trucks Data Analysis

**An exploratory analysis of Craigslist vehicle listings (2019–2021) using R and R Markdown.**

---

## 🚀 Project Overview

This project ingests and analyzes the **Craigslist Cars & Trucks** dataset (9 million+ records) to uncover insights on pricing, location, and vehicle characteristics. It was developed as a Phase-3 deliverable for our Data Science capstone.

---

## 📝 Data Source

The raw dataset is **not** included in this repo. To reproduce the analysis:

1. Go to Kaggle:  
   https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data  
2. Download **`listings.csv`** (≈2.5 GB uncompressed)  
3. Place it in this repo under `data/listings.csv`

---

## 📊 Key Analyses & Insights

- **State distribution:** California has the highest number of vehicle listings, making it the primary market for used-car activity in our dataset :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}.  
- **Brand price extremes:** Among all makes, GMC commands the highest listing prices, while Saturn vehicles appear at the lowest end of the price spectrum :contentReference[oaicite:2]{index=2}:contentReference[oaicite:3]{index=3}.  
- **Condition breakdown:** Over half of all listings (52.8%) are in “Excellent” condition, 29.44% are “Good,” and only 0.39% are flagged as “Salvage,” highlighting overall high quality of listed vehicles :contentReference[oaicite:4]{index=4}:contentReference[oaicite:5]{index=5}.  
- **Feature importance:** In our price‐prediction model, **Year** followed by **Odometer** reading emerged as the most influential variables :contentReference[oaicite:6]{index=6}:contentReference[oaicite:7]{index=7}.  
- **Model performance:** We compared Linear Regression vs. XGBoost; XGBoost achieved a lower RMSE of 4,424.40, outperforming the simpler linear approach :contentReference[oaicite:8]{index=8}:contentReference[oaicite:9]{index=9}.  

> _For full context, narrative, tables and figures, please see the HTML report at_ `reports/Phase-3.html`.  


