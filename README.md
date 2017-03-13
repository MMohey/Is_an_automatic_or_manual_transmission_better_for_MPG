Executive Summary
=================

This project investigates the relationship between MPG (miles per
gallon) and the type of transmission, which could be either Automatic or
Manual. The project starts with exploratory analysis of the data set
mtcars, which belong to 1974 Motor Trend US magazine. Then, statistical
test and regression analysis were performed. T-test showed that Cars
with manual transmission have around 7 MPG more than automatically
transmitted cars. Then, after investigating several linear regression
models, it was found that a model composed of ‘wt’(weight), ‘qsec’ (1/4
mile time), ‘am’(Transmission) and an interaction term of wt and am,
achieved the highest adjusted R-squared value and can explain around 88%
of the variance in MPG. In addition, all the coefficients of the model
are at 0.05 significance level. Using the aforementioned model, car with
manual transmission has 14.079 - 4.141\*wt more MPG than automatic cars,
given that weight (lb/1000) and qsec (1/4 mile time) are constant. For
example, a car with manual ransmission, weighing 1000 lbs, will have
9.938 more MPG than a car with automatic transmission.
