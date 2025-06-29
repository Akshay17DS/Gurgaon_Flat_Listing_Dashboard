# 🏡 Gurgaon Flat Listing Analysis

This Power BI dashboard presents a comprehensive analysis of residential flat listings in Gurgaon. It provides insights into pricing trends, area distribution, furnishing types, feature categories, and other key factors to support informed property buying decisions.
---

## 📌 Objective

The objective of this project is to analyze residential flat listings in Gurgaon using Power BI, providing actionable insights into property characteristics such as pricing, area, furnishing status, features, and location trends. The dashboard aims to support prospective homebuyers, real estate professionals, and investors in making data-driven decisions by visualizing key metrics and patterns in the Gurgaon real estate market.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX (Data Analysis Expressions)**
- **CSV / Excel Data Sources**

---

## 🧹 Data Cleaning & Transformation

Performed in **Power Query**, the dataset underwent the following transformations:

- ✅ Removed irrelevant fields (`Property ID`, `Link`, `Nearby Locations`, etc.)
- ✅ Cleaned and standardized `Society_Name` and `furnishDetails`
- ✅ Extracted & classified `features` into: **Basic / Mid / Premium**
- ✅ Parsed complex `rating` strings to numeric values
- ✅ Derived new columns:
  - `Average Rating`
  - `Price per Square Foot`
- ✅ Handled missing values using:
  - **Mode** for ratings
  - Default values (0) where applicable

---

## 📊 Dashboard Highlights

An interactive and minimalist dashboard designed for clarity. Key visuals include:

### 📈 Visuals

| Chart Type | Description |
|------------|-------------|
| Histogram | Price & Area Distribution |
| Bar Chart | Avg Price by BHK / Furnishing / Property Age |
| Donut & Pie | Feature Category, Furnishing Split |
| Treemap | Distribution by Facing Direction |
| KPI Cards | Total Properties, Avg Price, Avg Area |
| Slicers | Furnishing, Bedrooms, Feature Category, Property Age |

---

## 🧾 Final Dataset Fields

- `property_name`
- `society_Name`
- `price_in_lakhs`
- `area_sqft`
- `bedrooms_num`, `bathroom_num`, `balcony_count`
- `address`
- `floor_num`
- `facing`
- `Proprty_age_in_year`
- `furnishDetails`
- `average Rating`
- `feature_category` *(Basic / Mid / Premium)*

---

## 📌 Insights Uncovered

- 📌 **How does price vary with BHK size and furnishing?**
- 📌 **Which property features are most common in Premium homes?**
- 📌 **What is the average price and area of listed properties?**
- 📌 **Which property facing directions are most popular?**
- 📌 **How do ratings correlate with price and features?**

---

## 🧠 Future Scope

- 🌍 Geo-spatial analysis using location coordinates
- 🧮 Predictive pricing models with machine learning
- 🏘️ Drill-through for society-wise comparisons
- 🗃️ Multi-city dashboard expansion

---

## 📷 Dashboard Preview



---

## 👤 Author

**D Akshaykumar**  
🔗 LinkedIn
🔗 GitHub

---