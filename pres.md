Developing Data Products Course Project Presentation
========================================================
author: Dmitry Polinichenko
date: 20-06-2015
transition: rotate

Introduction
========================================================

The course projects aims to present a simple shiny application.
The Linear Regression app shows a set of points and a regression line 
calculated according to these points. You can see it at: https://dpol2000.shinyapps.io/regression

The presentation was made with Rstudio Presenter.

What the app does
========================================================

You can model a sequence of points distributed according to a linear model,
but with some noise. Then, a linear regression analysis is being done and the results are presented.

With the help of user input the app gets all the parameters:

- the number of points
- the actual intercept
- the actual slope
- the lower limit of the noise factor
- the higher limit of the noise factor


The results
========================================================

After the regression analysis the result is shown on the plot. The actual points
are shown in green and predicted ones together with the regression line in blue.
The app also shows the intercept, the slope, and the mean squared error of the model.

![plot of chunk unnamed-chunk-1](pres-figure/unnamed-chunk-1-1.png) 


The end
========================================================

I hope you enjoyed this simple presentation :)

Thank you for your attention!


