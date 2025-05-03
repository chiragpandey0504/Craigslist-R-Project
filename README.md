# Craigslist Cars & Trucks Data Analysis


---

## Table of Contents

1. [Introduction](#introduction)  
2. [Objective](#objective)  
3. [Data Collection & Description](#data-collection--description)  
4. [Exploratory Data Analysis](#exploratory-data-analysis)  
5. [Modeling Approach](#modeling-approach)  
6. [Key Findings & Conclusions](#key-findings--conclusions)  
8. [How to Reproduce](#how-to-reproduce)  
9. [Contact](#contact)  

---

## Introduction

“Craigslist” is one of the largest online classifieds platforms, with sections for jobs, housing, services—and of course, vehicle listings. This project focuses on the **Cars & Trucks** segment to uncover patterns in used-vehicle pricing and help sellers set fair prices.

---

## Objective

Analyze Craigslist vehicle listings (2019–2021) to answer:

- Which U.S. states have the most listings?  
- Which brands have the highest- and lowest-priced vehicles?  
- What is the breakdown of vehicle condition?  
- Which features drive price most strongly?  
- How accurately can we predict a vehicle’s sale price?

---

## Data Collection & Description

- **Source:** [Kaggle: Craigslist Cars & Trucks Data](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)  
- **Format:** CSV, ~1.45 GB  
- **Observations:** 426,880  
- **Variables:** 26 (e.g., `id`, `price`, `year`, `condition`, `odometer`, `region`, …)

---

## Exploratory Data Analysis

- **Geographic Distribution:**  
  California leads in total listings.  
- **Brand Pricing:**  
  - **GMC** has the highest-priced listing.  
  - **Saturn** has the lowest-priced listing.  
- **Condition Breakdown:**  
  - 52.8 % Excellent  
  - 29.4 % Good  
  -  0.4 % Salvage  
- **Feature Importance:**  
  - **Year** and **Odometer** are the strongest predictors of price.

---

## Modeling Approach

- **Type:** Supervised regression  
- **Features:** Year, manufacturer, model, condition, region, odometer, …  
- **Split:** 80 % train / 20 % test  
- **Algorithms:**  
  1. Linear Regression  
  2. XGBoost  
- **Result:** XGBoost outperformed Linear Regression on RMSE.

---

## Key Findings & Conclusions

1. **California** dominates in listing volume.  
2. **GMC** and **Saturn** mark the price extremes.  
3. Over **80 %** of vehicles are in Good or Excellent condition.  
4. **Year** and **Odometer** explain most of the price variation.  
5. **XGBoost** delivers the lowest prediction error.

---


## How to Reproduce

1. **Clone** this repository  
2. **Install** required R packages:  
   ```r
   install.packages(c("tidyverse", "caret", "xgboost", "knitr", "kableExtra"))
3. Open Final_project_file.Rmd in RStudio
4. Knit to HTML or PDF to regenerate Phase-3.html

---

## 📞 Contact

**Chirag Pandey**  
– Email: chiragpandey0504@gmail.com  
– GitHub: [@chiragpandey0504](https://github.com/chiragpandey0504)
