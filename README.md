#  Blinkit Sales Data Analysis – Python EDA Project

##  Project Summary
This project performs **Exploratory Data Analysis (EDA)** on Blinkit’s sales dataset to uncover key factors influencing sales across product types and outlets. Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, it identifies trends, patterns, and insights to support data-driven business decisions and improve sales strategies.

---

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Blinkit’s sales dataset using Python.  
The objective is to understand sales performance, customer behavior, and key business insights from the data.

---

##  Dataset
The dataset (`blinkit_data.csv`) contains details about products, item fat content, outlet information, and sales.

| Column Name | Description |
|--------------|-------------|
| Item Fat Content | Type of product (Low Fat / Regular) |
| Item Type | Category of the item sold |
| Outlet Location Type | Outlet tier (Tier 1, 2, 3, etc.) |
| Outlet Size | Outlet store size |
| Outlet Establishment Year | Year when the outlet was established |
| Sales | Total sales value for the item |

---

##  Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical analysis  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook / Google Colab** – Development environment  

---

##  Data Preprocessing
- Cleaned inconsistent values in `Item Fat Content`.  
- Checked data types and missing values.  
- Standardized categorical fields for consistency.  

---

##  Key Performance Indicators (KPIs)
1. **Total Sales** – Overall revenue generated.  
2. **Average Sales** – Mean sales across all items.  
3. **Number of Items Sold** – Total number of transactions.  
4. **Sales by Category** – Distribution of total sales by item type.  
5. **Sales by Outlet Tier & Size** – Performance comparison across outlet categories.  

---

##  Visual Analysis
### 🔹 Sales by Fat Content
Pie chart showing the share of total sales between Low Fat and Regular products.

### 🔹 Total Sales by Item Type
Bar chart visualizing which item types contribute most to total sales.

### 🔹 Fat Content by Outlet Type
Stacked bar chart comparing total sales for different fat contents across outlet tiers.

### 🔹 Total Sales by Establishment Year
Line plot showing sales trends across outlet establishment years.

### 🔹 Sales by Outlet Size
Pie chart displaying contribution of small, medium, and large outlets to total sales.

---

##  Insights & Findings
- **Regular** items contribute more to total sales than **Low Fat** ones.  
- Certain item categories (e.g., Fruits, Snacks) dominate total sales.  
- **Tier 3** outlets often have higher sales due to volume and accessibility.  
- Older outlets (established earlier) tend to perform better due to customer loyalty.  
- Medium-sized outlets show a balanced performance across categories.  

---

##  How to Run the Project
1. Download or clone this repository:
   ```bash
   git clone https://github.com/Hemashrie/blinkit-sales-analysis.git
   ```
2. Place `blinkit_data.csv` in the same directory as `blinkit_project.py`.
3. Run the Python script:
   ```bash
   python blinkit_project.py
   ```
4. Visualizations will appear for each analysis section.

---

## Skills Demonstrated
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Statistical Insight Generation  
- Data Visualization (Matplotlib / Seaborn)  
- Business Intelligence Reporting  
- Analytical Thinking  

---

## Author
Created by: Hema Shrie  
Email: rhemashrie156@gmail.com

---
