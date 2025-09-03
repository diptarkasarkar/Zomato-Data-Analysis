# 🍴 Zomato Dataset Analysis

## 📌 Project Overview
Zomato is an Indian multinational restaurant aggregator and food delivery company.  
This project explores and analyzes the **Zomato Dataset** using **SQL Server** to understand restaurant distribution, customer preferences, and business patterns.  

The dataset consists of **9,000+ rows** with attributes such as:  
- `RestaurantId`  
- `RestaurantName`  
- `City`  
- `Location`  
- `Cuisines`  
- `Rating`  
- `Votes`  
- `Currency`  
- `CountryCode`  
and many more...

## 🛠️ Steps in Data Exploration
During the **data exploration phase**, I worked on:  
- Examining table schema (columns, data types, constraints)  
- Checking and removing duplicate values in `RestaurantId`  
- Removing irrelevant/unwanted columns  
- Merging tables & adding `CountryName` column using `CountryCode` as a primary key  
- Identifying and correcting mis-spelled city names  
- Counting restaurants with rolling/moving counts using window functions  
- Checking min, max, avg for `Votes`, `Rating`, and `Currency`  
- Creating new rating categories for better segmentation  


## 📈 Insights from Analysis
Some key findings from the dataset:  

- **90.67%** of the data belongs to restaurants in **India**, followed by the **USA (4.45%)**.  
- Out of 15 countries, **only India and UAE** offer online delivery.  
  - 28.01% of restaurants in India provide online delivery.  
  - 46.67% of restaurants in UAE provide online delivery.  
- **Connaught Place (New Delhi)** has the highest number of restaurants (122), followed by **Rajouri Garden (99)** and **Shahdara (87)**.  
- The most popular cuisine in Connaught Place is **North Indian Food**.  
- Out of 122 restaurants in Connaught Place, only 54 offer **table booking**.  
- ⭐ Average ratings:  
  - Restaurants **with table booking** → **3.9 / 5**  
  - Restaurants **without table booking** → **3.7 / 5**  
- 💡 Best moderately priced restaurant (`cost for two < 1000`, `rating > 4`, `votes > 4`, table booking & online delivery available, Indian cuisines):  
  - **India Restaurant (RestaurantID - 20747)** in **Kolkata, India**  


## 🚀 Tech Stack
- **SQL Server** – Data exploration, cleaning, and analysis  
- **Windows Functions** – For advanced aggregations  
- **Joins & Keys** – For merging datasets  


## 📌 Future Scope
- 🖥️ Build **interactive dashboards** with Power BI / Tableau for visualization  
- 📊 Perform **advanced analytics** using Python (Pandas, Matplotlib, Seaborn)  
- 🔮 Explore **predictive analysis** on ratings & delivery preferences  

---
