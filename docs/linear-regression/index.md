# Linear Regression and Predictions ~ SLR and MLR)

Topics:
* Linear Regression
* Features
* Single vs Multiple
* Restrictions




## Linear Regression
 * tries to approximate dataset with a straight line
 * this line is built in a way that minimises residuals (aka errors)
 * once built, this line can then be used to
   predict output based for known input(s)

## Features of Linear Regression
- applied to numeric variables only
- used in conjunction with correlation coefficient
- LR always produces a straight line
- LR is very simple - and yet extremely powerful, don't underestimate it
- LR is used for predicting of ONE output variable based on input variable or variables

## Single vs Multiple - it's all about input:
  - SLR: one output depends on one input variable
  - MLR: one output depends on more than one input variable

### Notes:
Do not confuse MLR with non-linear regression:
- with MLR, you multiply several variables
- by their own coefficients (m1*x1, m2*x2, m3*x3)
- with non-linear regression, variables
- are multiplied by themselves (m1*x1^2, m2*x2^3, m3*x1*x2)

- predicting values within the data range is called interpolation;
- predicting values outside of the data range is called extrapolation

!!! warn "Be extremely careful with extrapolation!"

- to "build LR model" means to draw best fit line
- to draw best fit line, you need to calculate coefficients
- equation for SLR:
- y = mx + c
- y = ax + b
- equation for MLR: y = m1*x1 + m2*x2 + m3*x3 + m0

### meaning of coefficients:
- multiplier  (aka slope): m or a - shows how steep the straight line is
- intercept (with Y axis): c or b - shifts (offsets) line up or down

- To build MLR, you need to calculate m1, m2, m3,..., m0
- in R, both models (SLR and MLR) are built using the same function lm()

 ## Restrictions:
 LR modelling can be applied if you:
 - make sure that the dependency is linear (so that it doesn't look like a curve)
 - make sure that the dependency is monotonic (graph doesn't change direction)
 - for some scenarios, time series is more appropriate than LR
 - linear modelling does not allow you to determine which variable is dependent, which one is independent
 - your dataset might contain lots of variables (50 or more), however when you build model you can only use reasonable amount of variables
