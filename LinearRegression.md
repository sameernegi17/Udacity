# Linear Regression

It models the relationship between two variables by fitting a line.

Now suppose you have the following Data.
Data: 
![alt text](./pic_1.jpg)

Now we will plot that data it will look like this
![alt text]("chart_1.png")

In the graph. x axis represents the area of the house while y axis represents the price. The variable is the x axis is also known as independent variable. The variable in the y axis is known as dependent variable. 
If we try to fit a line through this data as below
![alt text]("Linear_line.png")
Now we can found a relationship between the housing area and cost. We can predict the cost of the new house by the housing area.

We know the equation of the lines as 
Y = mx + c where c is intercept and m is the slope
Now to generalize These are some annotation
![alt text]("pic_2.jpg")

![alt text]("pic_5.jpg")

The above equation is the cost function, Our task is to minimize the cost functoion. For that there are two method Gradient Descent and Normal equation

## Gradient Descent
Imagine you are standing on a hill top and you want to take a small step to the direction of the steepest descent which can take you downhill as soon as possible. Gradient descent does the same. You start at a point apply gradient descent and end up at a new point and repeat the same until you reach to the minimum point.

![alt text]("pic_4.jpg")

## Normal Equation
As gradient Descent is iterative apporach. The normal equations find the value of parameters(a) in one go.

![alt text]("pic_6.jpg")

![alt text]("pic_7.jpg")

## Comparison between two approaches

![alt text]("pic_8.jpg")

