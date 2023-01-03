# Simple-Linear-Regression

Linear Regression is a type of predictive analysis algorithm that shows a linear relationship between the dependent variable(x) and independent variable(y).
You can use simple linear regression when you want to know:

1. How strong the relationship is between two variables (e.g., the relationship between House Age and House Price).
2. The value of the dependent variable at a certain value of the independent variable (e.g., the price of a House after few years of building a house).

Based on the given data points, we try to plot a straight line that fits the points the best. The equation of a straight line is shown below:

![image](https://user-images.githubusercontent.com/83088512/210354187-e43f92e4-17d5-4544-9d19-5651535aea2c.png)

where,<br />
  * x : input data points<br />
  * y : predicted value, dependent variable (supervised learning)<br />
  * m : bias or slope of the regression line<br />
  * c : intercept, shows the point where the estimated regression line crosses the 𝑦 axis<br />

Our basic agenda is to implement a whitebox simple linear regression program using numpy and pandas.<br />
Then check the efficiency of the model using the following metrics :<br />
### MEAN SQUARE ERROR : 

  ![image](https://user-images.githubusercontent.com/83088512/210354385-15589a5a-adfd-4940-97fb-171a41b4723a.png)

where,<br />
  * 𝑁 is the total number of observations (data points)<br />
  * yᵢ is the actual value of an observation and y^ is the predicted value<br />
  * J is the cost function which is the mean squared error in this case<br />
  
  ### R-squared value:
  
  ![image](https://user-images.githubusercontent.com/83088512/210355039-e6a5fb91-3ae5-45f8-ab26-161f59f94590.png)

Where,<br />
  * yₚᵣₑ𝒹 is the predicted y value,<br />
  * y̅ is the mean, <br />
  * y is the actual value<br />
