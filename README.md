*Project Overview*

This project involves analyzing manufacturing data using MySQL, Excel, Tableau, and Power BI to derive insights and visualize key production metrics.
The main objectives are to identify process trends, track manufactured vs. rejected quantities, and provide a comprehensive overview of production efficiency.

*Tools and Technologies*

*Excel:*

Used to create pivot charts and KPIs for understanding product-wise and month-wise production performance.

*Power BI:*

Used to build interactive dashboards for analyzing production, rejection trends, and efficiency metrics.

*Tableau:*

Used for storytelling dashboards to highlight rejection patterns and comparative analysis.

*MySQL:*

Used for querying the manufacturing database to extract KPIs such as Produced Qty, Rejected Qty, Wastage %, and Processed Qty.

*Data Sources*

*Manufacturing Database*

Contains tables such as:

•	Production

•	Rejection

•	Products

•	Machines / Lines

•	Work Orders


*Excel Analysis*

*Pivot Charts created for:*

•	Manufactured vs. Rejected Qty

•	Product-wise Rejection %

•	Monthly Trend of Production

•	Machine/Line-wise Performance

•	Wastage % Comparison

•	Top Rejected Products

•	Processed Qty Overview

Excel also includes slicers for Year, Product, and Machine to interactively filter insights.


*Power BI Dashboards*

*Visuals Included:*

•	*Clustered Bar Chart:* Manufactured Qty and Rejected Qty by Product.

•	*Stacked Column Chart:* Production and rejection comparison by Month.

•	*Donut Chart:* Rejection % by Machine / Line.

•	*Scatter Chart:* Relationship between Manufactured Qty and Wastage %.

•	*Cards:*

o	Total Manufactured Qty

o	Total Rejected Qty

o	Average Wastage %

•	*Trend Lines:* Monthly performance trend for production and rejection.

*Slicers:*

•	Product Slicer

•	Machine / Line Slicer

•	Month Slicer

*Toggle Buttons:*

Switch between Production View and Rejection View in visuals.


*Tableau Dashboards*

*Visuals Included:*

•	*Decomposition Tree:*

Breaking down Wastage % by Product → Machine → Month.

•*Table:*

*Includes columns such as:*

o	Month

o	Manufactured Qty

o	Rejected Qty

o	Wastage %

o	MoM Change %

o	YTD Production

*Toggle Buttons:*

Switch between the two dashboards for quick navigation.


*SQL / MySQL Queries*

*Overall Production KPIs:*

Calculating Manufactured Qty, Rejected Qty, Processed Qty, and Wastage %.

*Machine-Level Rejection Analysis:*

Identifying machines or production lines with the highest rejection rate.

*Product-Level Comparison:*

Finding which products have higher wastage and require process improvement.

*Monthly Production Trend:*

Summarizing monthly Manufactured Qty vs. Rejected Qty.

*Top Defective Products:*

Listing products contributing the most to overall rejection.

*Processed Output Efficiency:*

Calculating the percentage of usable production output.


*How to Run the Project*

*1. Database Setup:*

*Instructions for running the queries:*

1.	Open MySQL Workbench
    
2.	Go to your schema list and create a new schema
   
3.	Right-click the schema you created → Table Data Import Wizard →name the table manufacturing_data.
   
4.	 Select your .csv file → Select the attached manufacturing_data.csv file
   
5.	Name the table manufacturing_data
   
*2. Excel Analysis:*

Import data into Excel and build pivot tables and charts.

*3. Power BI Dashboards:*

Load data into Power BI, create visuals, add slicers, and implement toggle buttons.

*4. Tableau Dashboards:*

Load data and create interactive visual storytelling dashboards.

*5. Interact with Dashboards:*

Use slicers and filters to explore production performance and identify improvement areas.

*Conclusion*

This project demonstrates how MySQL, Excel, Power BI, and Tableau can be used together to analyze and visualize manufacturing performance.
The insights help identify high-rejection areas, improve production efficiency, and support data-driven decisions.
Future enhancements may include real-time dashboards and predictive maintenance analytics.
