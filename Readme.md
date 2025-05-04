## 🎯 Overall Project Goal
<h1>Analyze food delivery data to extract business insights on customer behavior, restaurant performance, delivery efficiency, and promotional effectiveness — and present this via Python visualizations, Excel dashboard, and Power BI (optional/advanced).</h1>


# 🍽️ Swiggy-style Food Delivery Data Analysis Project

## 📦 Dataset Structure Overview

### 1. Order Information
- `Order ID`
- `Order Amount (INR)`
- `Delivery Time (mins)`
- `Order Date`
- `Order Status`
- `Number of Items`
- `Delivery Distance (km)`

### 2. Customer Feedback
- `Rating`
- `Tip Amount (INR)`
- `Votes`
- `Aggregate Rating`
- `Photo Count`

### 3. Restaurant Info
- `res_id`
- `name`
- `type`
- `average_cost_for_two`
- `price_range`
- `highlights`
- `cuisines`

### 4. Location
- `address`
- `city`
- `state`
- `area`
- `latitude`
- `longitude`
- `locality`

### 5. Delivery Agent Info
- `Delivery Agent ID`

### 6. Order Preferences & Promo
- `Payment Method`
- `Promo Code Applied`
- `Has Free Delivery`
- `opentable_support`
- `timings`
- `delivery`

---

## 🧩 Project Modules

### ✅ Module 1: Data Collection
**Objective**: Load and explore the dataset  
**Tools**: Python (Pandas, NumPy), Jupyter Notebook  

**Steps**:
- Import the dataset using `pd.read_csv()`
- Display top rows using `.head()`
- Check structure with `.info()`
- View summary statistics with `.describe()`

---

### ✅ Module 2: Data Cleaning & Transformation
**Objective**: Prepare the dataset for analysis  
**Tools**: Python (Pandas, NumPy)

**Tasks**:
- Handle missing values (e.g., Ratings, Tip Amount, etc.)
- Convert `Order Date` to datetime format

**Feature Engineering**:
- Extract `month`, `day`, `weekday`, `hour` from `Order Date`
- Create `is_peak_hour` based on delivery time
- Create `order_value_per_item = Order Amount / Number of Items`
- Create `is_discounted` from `Promo Code Applied`
- Encode categorical columns like `Order Status`, `Payment Method`, `Has Free Delivery` if needed

---

### ✅ Module 3: Exploratory Data Analysis (EDA)
**Objective**: Discover insights using visualizations  
**Tools**: Python (Matplotlib, Seaborn)

**Key Questions**:
- What are the top cities by number of orders?
- How does delivery time vary by city, time of day, or area?
- Do customers tip more during specific times/days?
- What kind of restaurants get better ratings?
- How does the use of promo codes affect the order amount or rating?

**Visuals**:
- Histogram of `Order Amount`
- Boxplot of `Delivery Time`
- Heatmap of `Order Volume` by Day vs Hour
- Bar chart of Top Cities, Top Cuisines
- Scatter plot: `Delivery Distance` vs `Delivery Time`
- Pie chart of `Payment Methods`, `Order Statuses`

---

### ✅ Module 4: Business Insights
**Objective**: Extract useful insights for Swiggy-style decision-making

#### Customer Behavior
- Frequency of ratings and influencing factors (e.g., delivery time, distance, promo use)
- Areas or cities with the highest tip amounts

#### Restaurant Performance
- Top restaurants by number of orders, ratings, or average cost
- Are expensive restaurants rated better?

#### Delivery Logistics
- Which delivery agents handle the most orders?
- Correlation between `Delivery Time` and `Distance`

#### Marketing Analytics
- Impact of promo codes and free delivery on `Order Amount` and `Customer Ratings`
- Top payment methods and preferred cuisines


✅ Module 5: Excel Dashboard
Objective: Showcase your ability to build dashboards in Excel.

Steps:
<ol>
<li>Import cleaned CSV to Excel.</li>
<li>Use Pivot Tables to summarize:</li>
    <ul>
        <li>Orders by city, delivery time trends</li>
        <li>Ratings vs order amount</li>
        <li>Promo code usage</li>
    </ul>
<li>Add:</li>
    <ul>
        <li>Slicers (city, month, status)</li>
        <li>Bar charts, Pie charts, Line charts</li>
    </ul>
</ol>

✅ Module 6: Power BI Dashboard (Optional for Later)
Objective: Create an interactive business dashboard for storytelling.

Sections to build:
<ol>
    <li>Map view of orders by location (latitude, longitude)</li>
    <li>Time-series trends for Order Volume and Tip Amount</li>
    <li>Donut chart for Payment Methods</li>
    <li>Filters: city, status, date range</li>
</ol>

✅ Module 7: SQL Use (Optional, if you create a database from this)
<ol>
    <li>If you upload this dataset to a local SQL database (like MySQL, PostgreSQL, or SQLite), you can practice:
    </li>
        <li>Grouping and filtering orders by time</li>
    <li>Finding top-rated restaurants</li>
    <li>Calculating average order value per city</li>
    <li>Joining customer and restaurant tables (if split)</li>
</ol>

✅ Module 8: Final Report & Resume Summary
Objective: Summarize insights and prepare a resume bullet.

What to include:
<ol>
    <li>Top 5 insights in a report.</li>
    <li>Screenshots of Excel/Power BI dashboards.</li>
    <li>Cleaned and documented code notebook on GitHub.</li>
</ol>
    


## 📈 Outcome
This project will help uncover key insights around customer behavior, restaurant performance, delivery logistics, and marketing strategy that a Swiggy-like platform can use to optimize its services.
    

## Resume line:
    "Performed end-to-end analysis on a real-world food delivery dataset using Python, SQL, Excel, and visualization tools to derive insights on customer behavior, delivery efficiency, and restaurant performance; built interactive dashboards to guide business decisions."