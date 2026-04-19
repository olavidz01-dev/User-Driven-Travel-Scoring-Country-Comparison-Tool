# 🌍 TripLens: Interactive Travel Comparison & Scoring Dashboard

## 📌 Overview

TripLens is an interactive Power BI dashboard designed to help users compare countries based on travel-relevant factors such as population density, UN membership, independence, and more.

The project transforms raw country-level data into a dynamic, user-driven decision tool — allowing users to select preferences and instantly see the best travel options.

---

## 🎯 Key Features

### 🔄 Dynamic Country Comparison

* Compare up to 3 countries simultaneously
* View key attributes like capital, currency, population density, language, sub-region, UN membership, and Independent status.

### 🧠 Intelligent Scoring System

* Custom DAX-based scoring engine
* Weighted logic using conditional rules
* Real-time recalculation

### 🌍 Language Matching Engine

* Identifies:

  * Languages shared across all countries
  * Languages shared by at least 2 countries
* Handles multi-language countries

### 🏆 Best Country Recommendation

* Automatically selects the best country based on score
* Handles tie scenarios intelligently

### 🎨 Enhanced UX/UI

* Dynamic flags (API-driven)
* Icon-based indicators (✅ ❌ 🟢 🔴)
* Clean, modern layout for storytelling

---

## 🛠️ Tech Stack

* **Power BI**
* **DAX (Data Analysis Expressions)**
* **Power Query (ETL)**
* **REST Countries API**
* Data modeling (Star Schema principles)

---

## 📊 Data Sources

* REST Countries API
* Open-source country datasets

---

## 🧱 Data Modeling Approach

* Created a normalized country dataset
* Handled:

  * Multi-language fields
  * Country code standardization (ISO)
* Built reusable dimension tables

---

## ⚡ Key DAX Concepts Used

* CALCULATE / FILTER
* SELECTEDVALUE
* SWITCH(TRUE())
* INTERSECT / UNION
* CONCATENATEX
* Dynamic measures
* Table constructors

---

## 🚀 Challenges & Solutions

| Challenge                    | Solution                          |
| ---------------------------- | --------------------------------- |
| Multi-language in one column | Split into rows using Power Query |
| Country name mismatches      | Created normalized keys           |
| Dynamic flag rendering       | Used URL-based images             |
| Flexible scoring             | Built user-driven toggle system   |

---

## 📈 Business Value

This dashboard simulates a real-world decision tool by:

* Enabling personalized travel insights
* Supporting data-driven recommendations
* Demonstrating scalable analytics design

---

## 📸 Screenshots

*(Add your dashboard screenshots here)*

---

## 🔮 Future Improvements

* Add cost-of-living and safety metrics
* Integrate weather/climate data
* Expand scoring model with weights
* Deploy as a web app
* Travel preference toggle
  * where users can choose what matters most:
    * 🌿 Low Population Density
    * 🏛 UN Membership
    * 🏳 Independence
* Scores update dynamically based on selected preferences
---

## 🧠 Key Learnings
- Importance of proper data modeling (atomic columns)
- Building dynamic user-driven metrics using DAX
- Handling real-world data inconsistencies
- Designing dashboards for decision-making, not just visuals



## 👨‍💻 Author

**Your Name**

---

## ⭐ If you found this useful

Give it a star ⭐ and feel free to fork!
