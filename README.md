# Which Outlet has the highest sales
- # Here I was researching which Outlet store has the highest sales with the focus on Fat Content
- Author: Catherine Tippins
## Two Visuals representing my findings

<img width="320" alt="Screen Shot 2023-02-03 at 7 24 56 PM" src="https://user-images.githubusercontent.com/120760480/216741584-17863767-6b14-4126-9d03-6a6509c66fdf.png">

<img width="320" alt="Screen Shot 2023-02-03 at 7 25 47 PM" src="https://user-images.githubusercontent.com/120760480/216741617-6b7f3af6-d8a5-42d9-a90d-5c2dc0df9db5.png">

## Model Explanation 
- In these two graphs, I wanted to exhibit what type of items are being sold more in grocery stores. Due to the recent health concerns in the past four years, I wanted to see if the overall population would buy more healthier items or if they would continue buying low-quality food. Depending on what is being sold, I would recommended lowering the prices of the items in order to increase sales. 
- As you can see in the first graph, the low fat content sales were higher than the regular fat content. In the second graph, it shows how fruits and vegetables sold more than any other items. These graphs show us that the population have been making more of an effort to chose the healthier items vs the low quality food.

## Predictive Models
- I chose two models in this project, Linear Regression Model and the Decision Tree Regression Model. As you can see, the Linear Regression Model is the better model for this this data because the numbers are closer to 1. Decision Tree Regression Model is not the best because there is too high of a variance of the data.

## Recommendations
- I would recommend lowering the prices of healthier foods by a slight amount or having more healthier options instead of the low-quality foods to increase sales.

## Coefficients 
![Coefficients](https://github.com/CatDawn29/Catherine-Project/assets/120760480/d8f2db0a-c6d2-437d-a857-139770a0ef9e)

- Top three Coefficients

For the Outlet_Type_Grocery Store, every food sold, there will be a negative 1,104  on it. 

For the Outlet_Identifier_OUT010, every sample sold, there will be a negative 629 on it.

For the Outlet_Identifier_OUT027, every sample sold, there will be a positive 688 on it.

## Features
![Features Graph](https://github.com/CatDawn29/Catherine-Project/assets/120760480/208593d7-584a-47f4-a5f4-ca020857bcca)

-Top 5 Features
Item_MRP
Outlet_Type_Grocery Store
Outlet_Identifier_OUT027
Item_Visibility
Outlet_Establishment_Year

## Shap Bar Graph
![Shap Graph](https://github.com/CatDawn29/Catherine-Project/assets/120760480/2313fc17-686c-4451-9e4b-25e71950518e)
We can also see in this graph, that the top columns of this graph are Outlet Establishment Year, Outlet Location Type Tier 2, Outlet Type Supermarket Type 1, Outlet Size Small, and Outlet Identifier OUT046. 

## Shap Plot Graph
![Shap Summary Plot](https://github.com/CatDawn29/Catherine-Project/assets/120760480/21882b66-b894-4c95-ba12-af2479021af5)
As we can see for the column OutLet Establishment year, since it is at the top, it has the largest effect on the model's predictions. We can also see that most of the dots are near the right of the graph, which tells me that the higher values of this column will increase the chance the prediction will fail.

## Lime Graph
![Lime Graph ](https://github.com/CatDawn29/Catherine-Project/assets/120760480/7ddccc22-1499-4680-9332-7ae6df6123eb)
In this graph, we can see how the Outlet Type Grocery earns more overall.

## Local Lime Graph
![Local LIME Graph Bar](https://github.com/CatDawn29/Catherine-Project/assets/120760480/8fda1c5c-66a3-403b-b9d9-599276ff2e62)
In this graph, we can see how the Outlet Type Grocery earns more overall. We can also see how two different Outlet Identifiers earn less than anyone else.

## Global Graph
![Global Graph](https://github.com/CatDawn29/Catherine-Project/assets/120760480/7bc6e053-0c6f-4d0a-9d5a-57096fabcc98)
As we can see in this graph, the most effective column that will effect any predictions is the Outlet Establishment Year.






