# 🏠 Airbnb Performance Analysis | Power BI

> 📊 An end-to-end Power BI project analyzing Airbnb listings, reviews, market share, ratings, seasonality, and host trust across major global cities.

---

## 📌 Project Overview

This project presents an interactive **Airbnb Performance Analysis Dashboard** built using **Microsoft Power BI**.

The dashboard transforms Airbnb listing and review data into interactive business insights covering:

- 🏙️ City-wise market performance
- 🏡 Property type analysis
- 📈 New listing growth and lifecycle
- ⭐ Rating and service-quality analysis
- 💬 Review frequency and customer behavior
- 🌍 Market share by city
- 📅 Seasonality and monthly trends
- 🤝 Host trust and verification

The goal is to understand **how Airbnb's marketplace performs across cities, property types, customer reviews, and host characteristics**.

---

## 🎯 Business Problem

Airbnb operates across multiple cities with different customer preferences, property types, host characteristics, and market conditions.

Simply looking at raw listing and review data makes it difficult to answer important business questions.

This dashboard helps answer questions such as:

- Which cities contribute the most listings?
- 🏡 Which property types are most common?
- 📈 How has the number of new listings changed over time?
- ⭐ Which cities receive the highest ratings?
- 💬 How frequently do customers leave reviews?
- 📅 Are there seasonal patterns in reviews?
- 🤝 How do host verification and profile characteristics relate to trust?

---

## 🎯 Project Objectives

The main objectives of this project are:

1. 📊 Analyze Airbnb's overall listing performance.
2. 🏙️ Compare marketplace performance across major cities.
3. 🏡 Understand property-type distribution and pricing.
4. ⭐ Evaluate customer ratings and service quality.
5. 💬 Analyze customer review frequency.
6. 📅 Identify seasonal patterns in customer activity.
7. 🤝 Analyze host verification and profile characteristics.
8. 💡 Convert data into meaningful business insights.

---

## 📂 Dataset

The project uses Airbnb listing and review datasets.

### Main Data Sources

- **Listings**
- **Listings Data Dictionary**
- **Reviews**
- **Reviews Data Dictionary**

The datasets contain information related to listings, hosts, properties, reviews, ratings, cities, and other marketplace attributes.

> ⚠️ Raw datasets are not included in this repository unless redistribution rights permit their inclusion.

---

## 🛠️ Data Preparation & Transformation

Data preparation was performed using **Power Query in Power BI**.

The data preparation process focused on making the source data suitable for analysis and dashboard development.

Key activities included:

- 🧹 Data cleaning
- 🔄 Data transformation
- 📝 Data type handling
- 🔍 Preparing fields for analysis
- 📊 Structuring data for Power BI visuals
- ⚙️ Preparing analytical fields and measures

Detailed transformation steps can be documented in:

`documentation/power-query-transformations.md`

---

# 🖼️ Data Model

---

# 📊 Dashboard Overview

---

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| 🏡 Total Listings | 279,712 |
| 🌍 Cities | 10 |
| 👤 Hosts | 182,024 |
| 🏠 Property Types | 144 |
| 💬 Reviews | 5,373K |

These KPIs provide a high-level snapshot of the marketplace covered by the dataset.

---

# 🔎 Analysis Performed

## 1️⃣ 🌍 Global Airbnb Performance

This section focuses on the overall development and performance of Airbnb listings.

### Analysis Includes

- 📈 New listings trend over time
- 🏡 Property type distribution
- 📊 Listing lifecycle analysis
- 🚀 Take-off point identification
- 🏆 Peak point identification
- 🦠 COVID-19 period analysis
- 📉 Pre-COVID new listing analysis
- 🏨 Hotel room growth analysis

### Business Perspective

This analysis helps understand how Airbnb's listing ecosystem developed over time and how major periods affected marketplace growth.

---

## 2️⃣ 🌍 Market Share by City

This section compares Airbnb's marketplace presence across:

- Paris
- New York
- Sydney
- Rome
- Rio de Janeiro
- Istanbul
- Mexico City
- Bangkok
- Cape Town
- Hong Kong

### Analysis Includes

- 🏙️ City-wise listing distribution
- 🤝 Superhost vs Non-Superhost comparison
- 📊 Cumulative market share
- 💰 Average price by property type
- 🌍 City concentration analysis

### Business Perspective

This analysis helps identify cities with stronger marketplace presence and understand how listings are distributed across major markets.

---

## 3️⃣ ⭐ Rating Analysis

This section evaluates Airbnb listing ratings and customer experience.

### Rating Dimensions

- ⭐ Overall rating
- 🎯 Accuracy
- 🧹 Cleanliness
- 💬 Communication
- 📍 Location
- 💰 Value

### Analysis Includes

- City-wise average ratings
- Highest-rated cities
- Lowest-rated cities
- Detailed rating comparison

### Business Perspective

Rating analysis helps identify differences in customer experience across cities and service-quality dimensions.

---

## 4️⃣ 💬 Review Frequency Analysis

This section focuses on customer review behavior.

### Analysis Includes

- 👤 Number of reviews per customer
- 📊 Review frequency distribution
- 📈 Cumulative percentage analysis
- 🔍 Identification of unusually high review frequency

### Business Perspective

Understanding review frequency helps analyze customer engagement patterns and identify users with unusually frequent reviewing behavior.

---

## 5️⃣ 📅 Seasonality Analysis

This section examines how customer review activity changes over time.

### Analysis Includes

- 📆 Monthly review patterns
- 🌍 City-wise review share
- 📈 Seasonal trends
- ☀️ European summer activity
- 🎄 New York holiday-season activity

### Business Perspective

Seasonality analysis can help understand periods of higher or lower customer activity and support marketplace planning.

---

## 6️⃣ 🤝 Host Trust Analysis

This section analyzes host-related trust indicators.

### Analysis Includes

- 👤 Host profile picture availability
- ✅ Identity verification
- 🔐 Verified vs Unverified hosts
- 📊 Host trust segmentation

### Business Perspective

This analysis helps understand how host profile and verification characteristics are distributed across the marketplace.

---

## 7️⃣ 🏡 Property Type & Pricing Analysis

The dashboard also examines the relationship between property types and average pricing.

Property categories include:

- 🛏️ Private Room
- 🏠 Shared Room
- 🏨 Hotel Room
- 🏡 Entire Place

The analysis helps compare property availability and average pricing across different markets.

---

# 💡 Key Insights

The dashboard enables several business-oriented observations, including:

- 🌍 Airbnb's marketplace presence varies significantly across cities.
- 🏡 Property-type availability differs between markets.
- ⭐ Customer ratings provide multiple dimensions for comparing city performance.
- 💬 Review frequency can reveal different patterns of customer engagement.
- 📅 Customer activity shows seasonal patterns across months and cities.
- 🤝 Host verification and profile characteristics provide useful trust-related dimensions.
- 📈 Listing trends provide a view of Airbnb's marketplace lifecycle over time.

> ⚠️ Specific numerical findings should be interpreted directly from the dashboard and underlying dataset. No unsupported performance percentages or financial claims are made in this repository.

---

# 💼 Business Recommendations

Based on the analytical areas covered by the dashboard, potential business actions include:

### 🏙️ 1. City-Specific Strategy

Use city-level performance differences to develop market-specific strategies rather than applying one approach globally.

### 🏡 2. Property Portfolio Strategy

Monitor property-type demand, availability, and pricing differences to understand opportunities across markets.

### ⭐ 3. Improve Customer Experience

Use detailed rating dimensions such as cleanliness, communication, location, and value to identify areas requiring improvement.

### 📅 4. Plan Around Seasonality

Use seasonal customer activity patterns to support planning for high-activity and low-activity periods.

### 🤝 5. Strengthen Host Trust

Encourage complete host profiles and identity verification to support marketplace trust.

### 📈 6. Monitor Marketplace Lifecycle

Track listing trends over time to identify periods of growth, maturity, decline, or recovery.

### 💬 7. Monitor Customer Engagement

Review frequency analysis can help identify different customer engagement patterns and unusual reviewing behavior.

---

# 🧰 Tools & Technologies

### Primary Tools

- 📊 **Microsoft Power BI**
- 🔄 **Power Query**
- 🧮 **DAX**
- 📈 **Power BI Visualizations**

### Analytics Areas

- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Analysis
- Trend Analysis
- Market Share Analysis
- Rating Analysis
- Review Analysis
- Seasonality Analysis
- Host Analysis
- Business Intelligence
- Data Visualization

---

# 🧠 Skills Demonstrated

### 📊 Technical Skills

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Dashboard Development
- KPI Development
- Interactive Data Visualization

### 🔎 Analytical Skills

- Trend Analysis
- Market Share Analysis
- Segmentation
- Time-Series Analysis
- Comparative Analysis
- Rating Analysis
- Review Frequency Analysis
- Seasonality Analysis
- Marketplace Analysis

### 💼 Business Skills

- Business Intelligence
- Data Storytelling
- Insight Generation
- Decision Support
- Marketplace Performance Analysis

---

# 🖼️ Dashboard Screenshots

## 📊 Dashboard Overview
<img width="935" height="557" alt="Screenshot 2026-09-05 135541" src="https://github.com/user-attachments/assets/6f68d10d-bf1e-401b-aa8b-96bc91998168" />

---

## 🌍 Market Share Analysis
<img width="531" height="307" alt="Screenshot 2026-09-05 135616" src="https://github.com/user-attachments/assets/fe5aaff3-1187-4f81-a40c-b7782919665f" />

---

## ⭐ Rating Analysis
<img width="780" height="333" alt="Screenshot 2026-09-05 135709" src="https://github.com/user-attachments/assets/f75ca5f0-3e6a-4c1e-ae01-524972932d3f" />

---

## 💬 Review Frequency Analysis
<img width="465" height="282" alt="Screenshot 2026-09-05 135758" src="https://github.com/user-attachments/assets/0e3a6b2c-57a9-4159-a9cb-0c97b3a9dc44" />

---

## 📅 Seasonality Analysis
<img width="467" height="351" alt="Screenshot 2026-09-05 135819" src="https://github.com/user-attachments/assets/e7017b5a-e7ea-408d-952c-2da1f177749d" />

---

## 🤝 Host Trust Analysis
<img width="457" height="528" alt="Screenshot 2026-09-05 135859" src="https://github.com/user-attachments/assets/743232b1-8f7d-47ff-aa9f-f6d7368ac700" />

---

## 🏡 Property Type & Pricing Analysis
<img width="371" height="185" alt="Screenshot 2026-09-05 140003" src="https://github.com/user-attachments/assets/1fa86829-a3b3-4079-b91e-880d96a02fa4" />

---

# 📚 Data Documentation

The repository can include the following documentation:

- 📖 Listings Data Dictionary
- 📖 Reviews Data Dictionary
- 🔄 Power Query Transformations
- 🧩 Data Model Documentation
- 🧮 DAX Measures
- 💡 Business Insights

Documentation files are maintained inside the `documentation/` folder.

---

# ⚙️ Power BI Documentation

Detailed Power BI documentation can include:

### 🔄 Power Query

- Data cleaning steps
- Data transformation steps
- Column preparation
- Data type changes
- Analytical field preparation

### 🧩 Data Model

- Tables used
- Relationships
- Key fields
- Modeling decisions
