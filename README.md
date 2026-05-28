# POWER-BI-PROJECT-Beginner_Sales_Data
I imported a sales dataset into Power BI, cleaned it using Power Query, created KPIs using DAX such as total sales and profit, and built an interactive dashboard with charts and slicers to analyze sales performance across categories, regions, and time.
STEP 1: Open Power BI & Load Dataset
Steps
1.	Open Power BI Desktop
2.	Click Get Data
3.	Select Excel
4.	Choose your file: Beginner_Sales_Data.xlsx
5.	Click Open
6.	Select the sheet → Click Load
✅ Data will appear in Data View

Power BI is a business intelligence tool used to analyze data and create interactive dashboards. Data can be imported from Excel, SQL, CSV, and other sources using the Get Data option.
________________________________________
🔹 STEP 2: Understand the Dataset (Very Important)
Common columns in Sales dataset:
•	Order Date
•	Sales
•	Profit
•	Quantity
•	Category
•	Sub-Category
•	Region
•	Customer Name
👉 This understanding helps in KPI selection.

Understanding the dataset helps in identifying key metrics, dimensions, and relationships required for accurate analysis and dashboard creation.
________________________________________
🔹 STEP 3: Data Cleaning using Power Query
Steps
1.	Click Transform Data
2.	Power Query Editor opens
3.	Perform basic cleaning:
o	Remove null values
o	Change data types (Date, Decimal, Text)
o	Rename columns if needed
4.	Click Close & Apply
📌 Why this step?
Clean data = correct analysis

Power Query is used for data cleaning and transformation in Power BI. It allows removing null values, changing data types, filtering rows, and preparing data before analysis.
________________________________________
🔹 STEP 4: Create Measures (DAX Formulas)
Go to Report View → Modeling → New Measure
✅ 1. Total Sales
Total Sales = SUM(Sales[Sales])
✅ 2. Total Profit
Total Profit = SUM(Sales[Profit])
✅ 3. Total Quantity
Total Quantity = SUM(Sales[Quantity])
✅ 4. Average Sales
Average Sales = AVERAGE(Sales[Sales])

DAX (Data Analysis Expressions) is used to create calculated measures in Power BI. Measures like Total Sales and Total Profit help in aggregating data dynamically based on filters and visuals.
________________________________________
🔹 STEP 5: Create KPI Cards
Steps
1.	Select Card Visual
2.	Drag:
o	Total Sales
o	Total Profit
o	Total Quantity
o	Average Sales
3.	Format:
o	Increase font size
o	Add titles
📊 These are KPI indicators

KPI cards display key business metrics such as total sales and profit, helping stakeholders quickly understand performance.
________________________________________
🔹 STEP 6: Category-wise Sales (Bar Chart)
Steps
1.	Select Clustered Bar Chart
2.	Axis → Category
3.	Values → Total Sales
4.	Enable data labels
📌 Insight Example
Technology category has the highest sales.

Bar charts are used to compare values across categories and identify high-performing segments.
________________________________________
🔹 STEP 7: Time-based Analysis (Line Chart)
Steps
1.	Select Line Chart
2.	Axis → Order Date (Year / Month)
3.	Values → Total Sales
📌 Insight
Sales trend shows growth/decline over time.

Line charts help analyze trends and patterns over time, useful for forecasting and performance evaluation.
________________________________________
🔹 STEP 8: Region-wise or Segment-wise Sales (Pie Chart)
Steps
1.	Select Pie / Donut Chart
2.	Legend → Region / Segment
3.	Values → Total Sales

Pie charts show proportional distribution of sales across regions or segments.
________________________________________
🔹 STEP 9: Add Slicers (Filters)
Steps
1.	Select Slicer
2.	Add:
o	Year
o	Category
o	Region
👉 Makes dashboard interactive

Slicers allow users to filter data dynamically and interact with dashboards for better insights.
________________________________________
🔹 STEP 10: Final Dashboard Design
Arrange:
•	Top → KPI Cards
•	Middle → Line & Bar Charts
•	Side → Pie chart & slicers
🎯 Clean, readable, professional layout
________________________________________

<img width="1304" height="710" alt="Screenshot 2026-05-28 230611" src="https://github.com/user-attachments/assets/d10ba48f-0d5a-4521-bb42-035851e9638d" />
<img width="1256" height="435" alt="Screenshot 2026-05-28 230649" src="https://github.com/user-attachments/assets/361bdcfc-601f-45e4-b63a-cc94b635c07a" />
<img width="1303" height="733" alt="Screenshot 2026-05-28 230820" src="https://github.com/user-attachments/assets/7129458a-f231-4d13-b774-b700a3354a5d" />

Power BI dashboards can be shared through Power BI Service, enabling collaboration and real-time insights.
________________________________________

“Explain your Power BI project”

I imported a sales dataset into Power BI, cleaned it using Power Query, created KPIs using DAX such as total sales and profit, and built an interactive dashboard with charts and slicers to analyze sales performance across categories, regions, and time.

