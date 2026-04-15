#  Travel Triangle – Exploratory Data Analysis (EDA)

A complete end-to-end data analytics project including **web scraping, data cleaning, visualization, and insights extraction** based on TravelTriangle holiday packages.

#  Introduction

**TravelTriangle** is an online travel marketplace that provides customizable holiday packages through verified travel agents.

This project focuses on:

- Web Scraping  
- Data Cleaning  
- Exploratory Data Analysis  
- Identifying travel trends  
- Visualizing actionable insights  

---

#  Business Problem

TravelTriangle hosts thousands of travel packages online, but raw data from the website lacks:

- Clear visibility of travel trends  
- Price pattern understanding  
- Insight into customer preferences  
- Seasonal booking behavior  

We solve this using **Web Scraping + Data Analysis**.

---

#  Project Objectives

- Extract package information using **web scraping**
- Structure raw HTML into tabular format (DataFrame)
- Clean and preprocess the scraped data
- Perform **Exploratory Data Analysis (EDA)**
- Visualize price trends, durations, discounts, hotel types, etc.
- Generate insights to help improve business decisions

---

#  Web Scraping Overview

We scraped real-time travel package data:

- Destination  
- Price  
- Final Price  
- Discount  
- Duration  
- Agent Details  
- Description  
- Hotel Category  

**Tools Used:**  
- `requests`  
- `BeautifulSoup`  
- `pandas`  

**Workflow:**
1. Load webpage HTML  
2. Parse using BeautifulSoup  
3. Extract required fields  
4. Store into Python lists  
5. Convert into a DataFrame  
6. Save cleaned data for analysis  

---

# Data Cleaning Steps

- Handle missing values  
- Fix inconsistent formats  
- Remove duplicate rows  
- Clean price values  
- Standardize durations & hotel categories  
- Correct data types  
- Remove irrelevant columns  

---

#  Key Visualizations & Insights

## 1️ Discount Distribution
- Most packages offer **7%–12% discounts**
- Discounts peak around **9–10%**
- A few outliers above **15%**
- Slight right-skew observed

➡ Indicates stable mid-level discounting strategy.

---

## 2️ Trip Duration Distribution
- Most trips are between **3 to 6 days**
- **4-day trips** are the most common
- Very few packages offer long-term vacations (10+ days)

➡ Customers prefer short, budget-friendly trips.

---

