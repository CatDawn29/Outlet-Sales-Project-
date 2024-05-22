##Analysis of Outlet Sales Performance##

Catherine Tippins

The purpose of this analysis was to identify the factors influencing the sales of  grocery items in select Supermarkets.

#Summary:#
One specific store outperformed others in terms of sales.
The dataset made it challenging to identify additional factors driving sales.
The Machine Learning models used demonstrated limited effectiveness in predicting item sales based on the available data.

#Recommendations:# 
To further boost sales, it is suggested to either reduce the prices of healthier foods slightly or increase the availability of such options. I also recommend increasing healthier products in food stores to increase sales.

Objective: Determine the outlet with the highest sales, focusing on fat content in products.
Findings: Extensive research revealed that outlets selling healthier items, particularly fruits and vegetables, exhibited higher sales compared to those offering low-quality foods.

Data:
Data Dictionary:
Variable Name: -- Description
Item_Identifier: -- Unique product ID
Item_Weight: -- Weight of product
Item_Fat_Content: -- Whether the product is low fat or regular
Item_Visibility: -- The percentage of total display area of all products in a store allocated to the particular product
Item_Type: -- The category to which the product belongs
Item_MRP: -- Maximum Retail Price (list price) of the product
Outlet_Identifier: -- Unique store ID
Outlet_Establishment_Year: -- The year in which store was established
Outlet_Size: -- The size of the store in terms of ground area covered
Outlet_Location_Type: -- The type of area in which the store is located
Outlet_Type: -- Whether the outlet is a grocery store or some sort of supermarket
Item_Outlet_Sales: -- Sales of the product in the particular store. This is the target variable to be predicted.
Methods
The data was first examined, cleaned and then the following steps and processes were performed:
Exploratory Data Analysis
Explanatory Data Analysis
Modeling with 2 Supervised Machine Learning Models:
Linear Regression
Decision Tree Regression
Exploratory Data Analysis
The data was explored using:
Sorting and Filtering with pandas
A seaborn heatmap using correlation(r) values
Histograms, Barcharts, and Boxplots
Boxplot Visualization
This visualization revealed that one specific store was outcompeting the others in terms of sales (OUT027, Supermarket Type3)
Boxplots
Models Used: Linear Regression Model was found to be more suitable for this dataset compared to Decision Tree Regression Model due to lower variance.
Key Visuals:

Sales Comparison by Fat Content:
[Insert Visual Here]
Top Features Impacting Sales:
[Insert Visual Here]
Insights:

Coefficients Analysis: Outlet_Type_Grocery Store had a significant negative impact on sales, while Outlet_Identifier_OUT027 had a positive impact.
SHAP Analysis: Outlet Establishment Year played a crucial role in sales predictions, with higher values increasing the likelihood of success.
LIME Analysis: Outlet Type Grocery emerged as the top earner, suggesting a preference for healthier options.
Conclusion:
By leveraging advanced analytics techniques, we gain valuable insights into sales performance, guiding strategic decisions to optimize revenue and meet evolving consumer preferences.# Which Outlet has the highest sales

If there are any questions, please contact me at catherinetippins1@gmail.com

