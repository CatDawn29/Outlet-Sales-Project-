# Analysis of Outlet Sales Performance:

Catherine Tippins

The purpose of this analysis was to identify the factors influencing the sales of  grocery items in select Supermarkets.

# Summary:
One specific store outperformed others in terms of sales.
The dataset made it challenging to identify additional factors driving sales.
The Machine Learning models used demonstrated limited effectiveness in predicting item sales based on the available data.

# Recommendations: 
To further boost sales, it is suggested to either reduce the prices of healthier foods slightly or increase the availability of such options. I also recommend increasing healthier products in food stores to increase sales.

# Objective: 
Determine the outlet with the highest sales, focusing on fat content in products.
Findings: Extensive research revealed that outlets selling healthier items, particularly fruits and vegetables, exhibited higher sales compared to those offering low-quality foods.

Data: The dataset from the grocery store chain Big Mart included information on all grocery store items.

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

# Methods:
- The data was first examined, cleaned and then the following steps were performed:
Exploratory Data Analysis
Explanatory Data Analysis
Modeling with 2 Supervised Machine Learning Models:
Linear Regression
Decision Tree Regression

# Exploratory Data Analysis:
- The data was explored using:
Sorting and Filtering with pandas
A seaborn heatmap using correlation(r) values
Histograms, Barcharts, and Boxplots

Key Visuals:
Two Bar Graphs
<img width="320" alt="Screen Shot 2023-02-03 at 7 24 56 PM" src="https://user-images.githubusercontent.com/120760480/216741584-17863767-6b14-4126-9d03-6a6509c66fdf.png"> 

<img width="320" alt="Screen Shot 2023-02-03 at 7 25 47 PM" src="https://user-images.githubusercontent.com/120760480/216741617-6b7f3af6-d8a5-42d9-a90d-5c2dc0df9db5.png">


Models Used- For this project, I selected two models: the Linear Regression Model and the Decision Tree Regression Model. The Linear Regression Model proved to be more effective for this dataset, as it produced results closer to 1. In contrast, the Decision Tree Regression Model exhibited high variance, making it less suitable for this analysis.


Coefficients Analysis: Outlet_Type_Grocery Store significantly negatively impacted sales, while Outlet_Identifier_OUT027 positively impacted sales.

SHAP Analysis: Outlet Establishment Year was crucial in sales predictions, with higher values increasing the likelihood of success.

LIME Analysis: Outlet Type Grocery emerged as the top earner, indicating a preference for healthier options.

Conclusion: Utilizing advanced analytics techniques provides valuable insights into sales performance, guiding strategic decisions to optimize revenue and address evolving consumer preferences.

If there are any questions, please contact me at catherinetippins1@gmail.com

