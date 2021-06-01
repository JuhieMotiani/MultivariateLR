# MultivariateLR
A short example on gradient descent for multivariate linear regression

### Multivariate Linear Regression
A Multivariate Linear Regression is a linear regression with more than one variable or in machine learning jargon more than one “feature”.

This type of model is used when the relation between the dependent and independent variables is linear, but there are more than one predictors (independent variables).

A hypothesis for multivariate linear regression with two looks like this:

h⍬(x) = ⍬0 + ⍬1x1 + ⍬2x2


There are many models available for us to use. It’s very crucial to decide which particular model will fit our dataset most efficiently. The best way to identify the model is to look at our dataset graphically.

For example, the figure shown below is a self-generated dataset of 100 samples and 2 features. If our dataset looks somewhat like this, we can estimate that the relationship between the features and the target variable is roughly linear.

<img width="375" alt="image" src="https://user-images.githubusercontent.com/66436217/120198898-42d6c900-c240-11eb-97aa-693dbc7f6cfb.png">

Now, we need to figure out the line which best represents the above dataset. We can do that with the help of gradient descent, which is famously known for optimisation.

### Cost Function

A cost function is used to determine how wrong our hypothesis or prediction is from the actual data. The cost for an accurate model is always low.

The cost is calculated as the mean squared difference between the hypothesis and the actual output ‘y’.

The cost function used for multivariate linear regression is as follows:
 
 <img width="482" alt="image" src="https://user-images.githubusercontent.com/66436217/120197626-cc859700-c23e-11eb-940f-b32ce55db617.png">
 
Here, ‘m’ is the number of samples.

### Gradient Descent

In very simple terms gradient descent is used to find the most optimum values of ⍬0, ⍬1, ⍬2 so that the cost function returns a minimum value.

<img width="335" alt="image" src="https://user-images.githubusercontent.com/66436217/120198970-54b86c00-c240-11eb-801d-2a87022e33d7.png">

