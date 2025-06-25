# **Data Analyst Internship - Elevate Labs**

## **Project - 🛒 Retail Business Performance & Profitability Analysis** - Using Python + SQL + Tableau + Excel

### 🧭 **Objective:**
This project aims to perform a comprehensive analysis of retail sales data from 2020 to 2023 to uncover business performance trends, customer behaviour, and product profitability. Using Python (Pandas, SQLite) for data cleaning and analysis, and Tableau for interactive visualizations, the project highlights key insights such as seasonal demand patterns, top-performing product categories, and inventory optimization strategies.

### 🤝 **Target Audience:**
- Retail operations managers, category leads, inventory planners, and business analysts.

### **🧰 Tools & Technologies used:**

- 🐍 Python (Pandas, Numpy, Seaborn) – Data cleaning, Advanced analysis & visualization
- 🧾 Jupyter Notebook – Python workflow and correlation analysis
- 🗄️ SQL (SQlite) - Data cleaning, aggregation, view creation
- 📊 Tableau - Interactive dashboard for business insights
- 📗 Excel
- 📄.CSV file - Dataset for Retail Business Sales data

### 📂 **Dataset Overview:**
- Dataset file used - Retail_Sales_Data - Copy.csv
- The dataset comprises the following key attributes

  ![image](https://github.com/user-attachments/assets/9b4c4f95-ba14-4c51-b7f9-200130f9967d)

**Calculated Fields & Logic**:

- Total_Sales = Unit_Price × Total_Items
- Total_Cost = Cost_Per_Item × Total_Items
- Profit_Margin_Sales =	(Profit ÷ Total_Sales) × 100
- Profit_Margin_Cost =	(Profit ÷ Total_Cost) × 100
- is_slow_moving	Products in bottom 25% by Total_Items
- is_overstocked	Products in top 25% by quantity & low profit margin
- These were created using Python (Pandas) and thresholds via .quantile().

![image](https://github.com/user-attachments/assets/f2cd5ed7-efae-4579-843d-bdcea846fbc2)

  
### 🧑‍💻 **Analysis Performed:**

#### **Python Part:**
- Imported essential Python libraries (pandas, numpy, matplotlib, seaborn, sqlite3)
- Loaded a retail CSV file into a DataFrame.
- Used .head(), .tail() and .describe() to get a sense of the data distribution and quality.
- Converted date strings to proper datetime format.
- Checked data types and dimensions using .dtypes and .shape.
- Calculated columns like Total_Cost, Total_Sales, Total_Profit, Profit_Margin_Sales, Profit_Margin_Cost and Sales Agreegations

#### **SQLite Part:**

- Loaded data into SQLite in-memory DB for SQL queries.
  
**Key SQL-Based Analytical Queries Executed**

- **Profitability Analysis:**
  - Calculated Profit Margins by Category and Sub_Category to identify the most financially efficient product segments.
- **Seasonal Sales Distribution:**
  - Assessed Total Sales by Season and Category to uncover seasonal trends and high-performing periods.
- **Customer Segment Performance:**
  - Ranked Customer Categories by Sales Volume to determine the most valuable consumer demographics.
- **Payment Method Insights:**
  - Analyzed frequency and share of Payment Methods to reveal the most popular transaction modes across regions.
- **Inventory Performance Flags:**
  - Implemented logic to flag slow-moving products (based on low item turnover) and overstocked items (high inventory with low profitability).

### 🔎 **Observation:**

The average profit margin is healthy, with:
- Total Sales: ~$47,983
- Total Profit: ~$21,664
- Total Cost: ~$26,317
- Average Profit Margin on Sales is ~44.6%, showing effective pricing or cost management.
- Top-performing sales & Profit Margin sales categories include Personal Care, Pantry & Snacks, Cleaning Supplies, Grains & Bakery, and Household Electronics
- Top-Performing sales Custormer Category are Young Adult, Senior Citizen, Middle-Aged
- Personal Care dominates Spring/Fall and Pantry & Snacks peaks in Winter/Summer

### 🧠 **Key Stratergic Insights:**

- Optimize inventory by reducing overstocked items.
- Focus marketing on high-margin categories.
- Deep-dive into underperforming store types or promotions
- Introduce dynamic forecasting and demand planning

### 📊 **Visualizations Built in Tableau:**

- KPI Tiles for quick metrics
- Pie Charts: Sales by Season, Store Type
- Bar Charts: Sales by Customer Category, Category, and Profit Margin
- Side-by-Side Bar: Year-over-Year Sales by City
- Treemap: Slow-Moving Products by Category
- Filters: City, Season, Year, Product Category

### 🧾 **Deliverables:**
- Tableau Dashboard
- SQL queries (.sql file) - I have used SQlite
- PDF Report with key insights
  
### 📚 **Report Preview:**

![Screenshots/Superstores Co Sales Report.jpg](https://github.com/mahajabeensayyad/ElevateLabsMJ/blob/main/Report%20-%20Retail%20Business%20Performance%20%26%20Profitability%20Analysis%20-%202020-23.jpg)


