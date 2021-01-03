# CS105-Final-Project

Our final project report employs numeric estimation data mining techniques, namely the M5P
regression tree, simple and multiple linear regression, to build models that estimate the mean earnings of
working students 10 years after entry into an institution based on the institution’s characteristics. The
baseline model of simple linear regression bases its predictions on the input attribute which explains the
greatest variation in mean earnings of working students 10 years after entry into an institution, which
happens to be average faculty salary. The correlation coefficient, for the single regressor R, linear model
through cross-validation was found to be 0.78. In addition, the M5P regression tree algorithm generated a
regression tree with 18 leaf nodes, each leaf node containing the average output value for the training
examples in that subgroup. The correlation coefficient, R, for the M5P regression tree through
cross-validation was found to be 0.80.

Finally, the multiple regressor linear model was formulated through the linear regression
algorithm with noAttributeSelection set to False, resulting in the linear model model being forced to base
its predictions on all input attributes. The correlation coefficient, R, of the multiple regressor linear model
through cross-validation was found to be 0.83. Therefore, the addition of input attributes resulted in
predictive models which progressively generalized better, culminating in the multiple regressor linear
model with all input attributes explaining approximately 69 percent of the variation in mean earnings of
students working and not enrolled 10 years after entry into an institution.
