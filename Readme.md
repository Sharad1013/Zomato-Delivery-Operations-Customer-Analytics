# 🍽️ Zomato-style Food Delivery Data Analysis Project

## 🎯 Project Goal
Analyze Zomato food delivery data to uncover business insights related to customer behavior, restaurant performance, delivery efficiency, and marketing effectiveness. The results are presented using Python visualizations, Excel dashboards, and optionally Power BI.

---

## 📦 Dataset Structure Overview

### 1. Order Information
- `Order ID`, `Order Amount (INR)`, `Delivery Time (mins)`, `Order Date`, `Order Status`
- `Number of Items`, `Delivery Distance (km)`

### 2. Customer Feedback
- `Rating`, `Tip Amount (INR)`, `Votes`, `Aggregate Rating`, `Photo Count`

### 3. Restaurant Info
- `res_id`, `name`, `type`, `average_cost_for_two`, `price_range`, `highlights`, `cuisines`

### 4. Location
- `address`, `city`, `state`, `area`, `latitude`, `longitude`, `locality`

### 5. Delivery Agent Info
- `Delivery Agent ID`

### 6. Order Preferences & Promo
- `Payment Method`, `Promo Code Applied`, `Has Free Delivery`, `opentable_support`, `timings`, `delivery`

---

## 🧩 Project Modules

### ✅ Module 1: Data Collection
**Tools**: Python (Pandas, NumPy), Jupyter Notebook  
**Tasks**:
- Load dataset (`pd.read_excel`)
- Inspect structure with `.info()` and `.describe()`

---

### ✅ Module 2: Data Cleaning & Transformation
**Tasks**:
- Handle missing values
- Convert `Order Date` to datetime
- Feature Engineering:
  - Extract time components
  - `order_value_per_item = Order Amount / Number of Items`
  - `is_discounted` from `Promo Code Applied`

---

### ✅ Module 3: Exploratory Data Analysis (EDA)
**Tools**: Matplotlib, Seaborn  
**Key Questions**:
- Top cities by order volume
- Delivery trends by time, distance, city
- Tipping behavior and peak times
- Promo code impact on spending and rating

**Visuals**:
- Histograms, boxplots, heatmaps, bar charts, pie charts, scatter plots

---

### ✅ Module 4: Business Insights
**Themes**:
- **Customer Behavior**: Ratings vs delivery time, tip patterns  
- **Restaurant Performance**: Orders, cost, rating correlation  
- **Delivery Logistics**: Agent efficiency, distance vs time  
- **Marketing**: Promo code and free delivery impact

---

### ✅ Module 5: Excel Dashboard
**Steps**:
- Import cleaned xlsx
- Use Pivot Tables + Slicers (e.g., city, month)
- Include charts: bar, pie, line

---

### ✅ Module 6: Power BI Dashboard (Optional)
**Sections**:
- Map of orders by coordinates  
- Time-series for orders and tips  
- Donut chart: payment methods  
- Filters: city, date, status

---

### ✅ Module 7: SQL Usage (Optional)
If data is stored in SQL:
- Average order value by city
- Top-rated restaurants
- Group orders by time
- Practice filtering, joining, grouping

---

### ✅ Module 8: Final Report & Resume Summary
- Top 5 insights (business value focused)
- Screenshots of dashboards
- Final cleaned notebook
- Final insights report ➡️ [View Final Business Insights Report](final_insights.md)

---

## 📈 Outcome
This project provides actionable insights for a Swiggy-style platform to improve customer experience, optimize delivery operations, and boost marketing performance.

---

## 📘 Project Deliverables

- 📊 [Excel Dashboard](Dashboards/Zomato_Business_Insights_ex.png)
- 📈 [Power BI Dashboard](Dashboards/Zomato_Business_Insights_bi.png)
- 📄 [View Final Business Insights Report](final_insights.md)

---
