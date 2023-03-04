Log transform, reciprocal transform, square root transform, and custom transform are all mathematical transformations that can be applied to numerical variables in data processing and analysis.

Log transform: Takes the logarithm of a numerical variable. It is commonly used to normalize data that are skewed or have a wide range of values.

Reciprocal transform: Takes the reciprocal of a numerical variable (i.e., 1 divided by the value). It is used to normalize skewed data, particularly when the variable has values close to zero.

Square root transform: Takes the square root of a numerical variable. It is used to normalize data that have a nonlinear relationship between the mean and variance.

Custom transform: Any other mathematical transformation that can be applied to a numerical variable. This can include exponential, power, or trigonometric functions, among others.

All of these transforms can be applied using mathematical functions or programming languages such as Python or R. For example, in Python, the log transform of a variable x can be calculated using the numpy library as:

import numpy as np
log_x = np.log(x)

Similarly, the reciprocal transform of a variable x can be calculated as:

recip_x = 1/x

The square root transform of a variable x can be calculated as:

sqrt_x = np.sqrt(x)

And a custom transform can be defined using a user-specified mathematical function.

In summary, log transform, reciprocal transform, square root transform, and custom transform are all useful techniques in data processing and analysis for normalizing data, reducing the impact of outliers, and addressing nonlinear relationships between variables. The choice of which transformation to use depends on the properties of the data and the specific requirements of the analysis or modeling task.

code:
step1-in this code we performed all transform on titanic dataset.

step2-plot QQplot to undarstand data distribution.

step3-then perforn classification algorithm to predictand and check accuracy score without apply any transform.

step4-apply log transform then perform log transform and check accuracy score improve or not.

step5-draw qqplot to comparision result

step6- use feature engineering to optimize accuracy score

step7 buid a function to perform other transform
 

