# Task8_Sales_Dashboard
Simple Power BI dashboard showing sales trends by month, region, and category.  Includes cleaned dataset, visuals, and key insights for Task 8 of the Data Analyst Internship.
# Task 8 – Simple Sales Dashboard (Power BI)

## 📌 Objective
To create a clean and interactive dashboard showing sales performance by:
- Month
- Region
- Category

## 📁 Dataset Used
Superstore_Sales.csv  
(Columns: Order Date, Region, Category, Sales, Profit, etc.)

## 🧹 Data Cleaning
Data cleaning was done in Python (Pandas):
- Checked for missing values
- Found one unwanted column (`Unnamed: 21`) → removed
- Verified no null values in important columns
- Converted `Order Date` into Month–Year format for charts

## 📊 Visuals Created
1. **Line Chart – Monthly Sales Trend**  
   Shows how sales changed over time using a Month-Year column.

2. **Donut Chart – Category-wise Sales**  
   Displays the contribution of Furniture, Office Supplies, and Technology.

3. **Bar Chart – Region-wise Sales**  
   Helps identify the highest & lowest performing regions.

4. **Slicers / Filters**
   - Region Filter
   - Category Filter  
   (Makes the dashboard interactive)

5. **KPIs**
   - Total Quantity  
   - Total Profit  
   - First Sales Value

## 🖥 Tools Used
- Power BI Desktop
- Python (Pandas) for data validation

## 📌 Files Included
- `Dashboard_Screenshot.png`
- `Superstore_Sales.csv`
- `Task8_Report.txt` (Insights)
- `.pbix` file 
## 📝 Steps Followed
- Imported dataset into Power BI
- Cleaned data in Python
- Added Month-Year column using DAX:
