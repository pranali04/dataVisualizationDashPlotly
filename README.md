
Create Dashboard using Plotly and Dash

Scenario:
The objective of this part of the Final Assignment is to analyze the historical trends in automobile sales during recession periods, as you did in the previous part. The
goal is to provide insights into how the sales of XYZAutomotives, a company specializing in automotive sales, were affected during times of recession.
In this final assignment, you will have the opportunity to demonstrate the Dashboarding skills you have acquired in this course.
This lab aims to assess your abilities in creating various visualizations using Plotly and Dash. As a data scientist, you have been given a task to prepare a report on
your finding from Automobile Sales data analysis.
You decided to develop a dashboard representing two main reports:-
Yearly Automobile Sales Statistics
Recession Period Statistics
NOTE: Year range is between 1980 and 2013.
Components of the report items
1. Yearly Automobile Sales Statistics
This report mainly consists of the following items:
Yearly Automobile Sales Using Line Chart for the Whole Period (line chart):This line chart displays the average automobile sales for each year across the
entire period.
Total Monthly Automobile Sales Using Line Chart (line chart):This line chart displays the total monthly automobile sales for the selected year.
Average Vehicles Sold by Vehicle Type in the Selected Year (bar chart):This bar chart shows the average number of vehicles sold for each vehicle type in
the selected year.
Total Advertisement Expenditure for Each Vehicle Using Pie Chart (pie chart):
This pie chart represents the total advertising expenditure for each vehicle type in the selected year.
2. Recession Period Statistics
Average Automobile Sales Fluctuation Over Recession Period (Year-wise):This line chart shows the average automobile sales for each year during
recession periods.
Average Number of Vehicles Sold by Vehicle Type:This bar chart displays the average number of vehicles sold for each vehicle type during recession
periods.
Total Expenditure Share by Vehicle Type During Recessions:This pie chart represents the total advertising expenditure share by vehicle type during
recession periods.
15/09/2024, 12:13 about:blank
about:blank 1/9
Effect of Unemployment Rate on Vehicle Type and Sales:This bar chart shows the effect of unemployment rate on automobile sales by vehicle type during
recession periods.
NOTE: You have worked creating a dashboard components in Flight Delay Time Statistics Dashboard section. You will be working on the similar lines for this
Dashboard
Dataset Variables:
Dataset Variables for your reference
The dataset includes the following variables
Date: The date of the observation.
Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
Automobile_Sales: The number of vehicles sold during the period.
GDP: The per capita GDP value in USD.
unemployment_rate: The monthly unemployment rate.
Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
Price: The average vehicle price during the period.
Advertising_Expenditure: The advertising expenditure of the company.
Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
Month: Month of the observation extracted from Date.
Year: Year of the observation extracted from Date.
