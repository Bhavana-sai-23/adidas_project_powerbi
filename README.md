# adidas_project_powerbi
# BUSINESS REQUIREMENTS
Through this powerbi -driven analysis , Adidas aims to empowerits decision-makers with data-driven insights, fostering strategic growth and competitiveness in the dynamic sports and athletic industry


->Enhanced understanding of sales dynamic and performance drivers.

->Identification of geographical areas with high and low sales potential

-> Insights into product performance, aiding in inventory and marketing decisions

->Informed pricing and margin stratergies for improved profitability.

->Actionable recommendations for optimizing sales and profit across various dimensions.

# PROBLEM STATEMENT
1.Total sales analysis

2.Probability Analysis

3.Sales volume analysis

4.Pricing strategy

5.Margin Analysis

# CHARTS that I used here are

1.Total sales by month-  Area Chart

2.Total sales by state- Filled Map

3.Total sales by region- Donut Chart

4.Total sales by product- Bar Chart

5.Total sales by region- Bar Chart



Now to create the POWER BI Dashboard

# 1. Prepare the Data

Ensure your dataset contains the following columns:
->Invoice Date

->Region

->State

->Product Category

->Retailer

->Units Sold

->Price per Unit

->Total Sales

->Operating Profit



# 2. Load the Data into Power BI
Open Power BI Desktop.

Go to Home → Get Data → Excel/CSV (depending on your dataset format).

Import your dataset.


# 3. Data Cleaning and Transformation (Optional) 
Check for the null values if it is present then, Go to Transform Data to clean and format the data. Ensure column names and data types are correct.


# 4. Create Measures and Calculations
Use DAX (Data Analysis Expressions) to create custom measures:

->Total Sales: SUM(Data[Total Sales])

->Operating Profit: SUM(Data[Operating Profit])

->Total Units Sold: SUM(Data[Units Sold])

->Average Price Per Unit: DIVIDE([Total Sales], [Total Units Sold])

->Operating Margin: DIVIDE([Operating Profit], [Total Sales])


# 5. Design the Dashboard
# 5.1 Title and Filters

->Insert a Text Box to create the title "ADIDAS SALES ANALYSIS".

->Add a Drop-down Slicer to filter data by Region.

->Add another Date Slicer for Invoice Date.

# 5.2 KPI Cards (Top Summary Metrics)
Use Card Visuals to display:

->Total Sales

->Operating Profit

->Total Units Sold

->Average Price Per Unit

->Operating Margin

# 5.3 Line Chart (Total Sales by Month)

->Use the Line Chart visualization.

->Axis: Invoice Date (Month)

->Values: Total Sales


# 5.4 Pie Chart (Total Sales by Region)

->Use the Pie Chart visualization.

->Legend: Region

->Values: Sum of Total Sales

# 5.5 Bar Chart (Total Sales by Product)

->Use the Bar Chart (Clustered Bar) visualization.

->Axis: Product Category

->Values: Sum of Total Sales


# 5.6 Bar Chart (Total Sales by Retailer)

->Use the Bar Chart (Clustered Bar) visualization.

->Axis: Retailer

->Values: Sum of Total Sales

# 5.7 Map Visualization (State-wise Sales)

->Use the Map visualization.

->Location: State

->Size: Total Sales


# 6. Formatting

->Customize the theme with consistent fonts and colors.

->Add Data Labels to charts.

->Use Legends for better visualization.

->Enable Filters to allow users to interact with the dashboard.


# 7. Interactivity

->Go to Format → Edit Interactions to allow slicers to filter charts.

# 8. Save

-> Save the report
