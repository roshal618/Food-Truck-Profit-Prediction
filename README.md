# Food-Truck-Profit-Prediction
Food Truck Profit Prediction using Linear Regression.
In this project, we implement linear regression with one variable to predict profits for a food truck. 

## Problem Statement: 
Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities. You would like to use this data to help you select which city to expand to next.

About Dataset: The file ex1data1.txt contains the dataset for our linear regression problem. The first column is the population of a city and the second column is the profit of a food truck in that city. A negative value for profit indicates a loss.

Packages used: pandas, matplotlib, numpy

Note: This problem statement and dataset is from Coursera, Andrew Ng’s machine learning Coursework

### Important points to be noted:
1.	Visualizing the raw data with a Scatter plot in order to understand the data. 

![image](https://user-images.githubusercontent.com/114208254/210974247-87d21f2c-cdf5-4988-ab14-975d296d7c2d.png)

2.	Implementing Gradient Descent to fit the linear regression parameters to the dataset. The objective of linear regression is to minimize the cost function.
-	Initializing the initial parameters to 0 and learning rate alpha to 0.01
-	A good way to verify that gradient descent is working correctly is to look at the value of cost function and check that it is decreasing with each step.
-	Plot the model
 ![image](https://user-images.githubusercontent.com/114208254/210974173-fef7de7f-c583-4a9a-80a4-df8b6ce5ee9b.png)

 
3.	Plot the cost over 2D grid of both parameter values using surface and contour plot commands.

![image](https://user-images.githubusercontent.com/114208254/210974310-4777bd6c-ab30-4ddc-80a4-673276c9a6df.png) 
![image](https://user-images.githubusercontent.com/114208254/210974344-edd57ec9-3338-454a-8166-571f6fb6a749.png)

-	The purpose of these graphs is to show you that how cost function J varies with changes in parameters. 
-	The cost function J is bowl-shaped and has a global minimum. (This is easier to see in the contour plot than in the 3D surface plot). 
-	This minimum is the optimal point for the parameters, and each step of gradient descent moves closer to this point.

