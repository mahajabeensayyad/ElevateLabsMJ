# **Data Analyst Internship - Elevate Labs**
## **Project - 🛒 Retail Business Performance & Profitability Analysis** - Using Python + SQL + Tableau + Excel
### 🧭 Objective:
- Analyze retail transactions to identify profit-draining product categories and sub-categories.
- Optimize inventory turnover through data-driven insights.
- Detect and interpret seasonal product sales trends.
### 🤝 Target Audience: 
- Retail operations managers, category leads, inventory planners, and business analysts.
### 📂 Dataset Overview:
- Dataset file used - Retail_Sales_Data - Copy.csv
- My dataset has following columns:
  
![image](https://github.com/user-attachments/assets/9b4c4f95-ba14-4c51-b7f9-200130f9967d)
- Following are calculated columns using Python:

![image](https://github.com/user-attachments/assets/f2cd5ed7-efae-4579-843d-bdcea846fbc2)

#### **Calculated Fields & Logic**:

- Total_Sales = Unit_Price × Total_Items
- Total_Cost = Cost_Per_Item × Total_Items
- Profit = Total_Sales − Total_Cost
- Profit_Margin_Sales =	(Profit ÷ Total_Sales) × 100
- is_slow_moving	Products in bottom 25% by Total_Items
- is_overstocked	Products in top 25% by quantity & low profit margin
- These were created using Python (Pandas) and thresholds via .quantile().

### 🧰 Tools & Technologies:

- 🐍 Python (Pandas, Seaborn) – Data cleaning, Advanced analysis & visualization
- 🧾 Jupyter Notebook – Python workflow and correlation analysis
- 🗄️ SQL (SQlite) - Data cleaning, aggregation, view creation
- 📊 Tableau - Interactive dashboard for business insights
- 📗 Excel
- 📄.CSV file - Dataset for Retail Business data
  
### 🧑‍💻 Analysis Performed
#### **Python Part:**
- Imported essential Python libraries (pandas, numpy, matplotlib, seaborn, sqlite3)
- Loaded a retail CSV file into a DataFrame.
- Used .head(), .tail() and .describe() to get a sense of the data distribution and quality.
- Converted date strings to proper datetime format.
- Checked data types and dimensions using .dtypes and .shape.
- Calculated columns like Total_Cost, Total_Sales, Total_Profit, Profit_Margin_Sales, Profit_Margin_Cost and Sales Agreegations

#### **SQLite Part:**







### 🔎 Observation:
The average profit margin is healthy, with:
- Total Sales: ~$47,983
- Total Profit: ~$21,664
- Total Cost: ~$26,317
- Average Profit Margin on Sales is ~44.6%, showing effective pricing or cost management.
- Top-performing sales & Profit Margin sales categories include Personal Care, Pantry & Snacks, Cleaning Supplies, Grains & Bakery, and Household Electronics
- Top-Performing sales Custormer Category are Young Adult, Senior Citizen, Middle-Aged
- Personal Care dominates Spring/Fall and Pantry & Snacks peaks in Winter/Summer

### 🧠 Key Stratergic Insights:
### 📦 Final Recommendations:
### 🧾 Deliverables:
- Tableau Dashboard
- SQL queries (.sql file) - I have used SQlite
- PDF Report with key insights

### 📊 Visualization:
### 📚 Report Preview:
