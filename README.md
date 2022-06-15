# Linear regression assigment
This is the folder for Linear regression assignment submission. 

## Table of Contents
* General information
* Technology used
* Conclusion

## General information
### Business problems
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business objectives
A linear model is required to predict the demand for shared bikes with the available independent variables. The management need to understand the demands vary with different features.

## Technology used
* Programming language: Python v3.
  * numpy and pandas packages are used for data analysis.
  * matplotlib.pyplot and seaborn are used for data visualisation.
  * sklearn.model_selection is used for train test split.
  * sklearn.preprocessing is used for min max scaling.
  * statsmodels.api is used for training linear model.
  * statsmodels.stats.outliers_influence is used for VIF calculation.
  * sklearn.metrics is used for R-squared score.
* IDE: Jupyter-lab

## Conclusion
The final model is: __cnt = 0.1951 + 0.4382 * atemp + 0.2417 * yr - 0.1383 * spring + 0.0579 * Sep__

How to interpret this equation:
* A single unit increase in atemp (feeling temperature in Celsius) results in incrase 0.63 unit in bike sharing demands, given all other factor remain unchanged.
* Assuming all variables increases by 1 unit, the total bike sharing demands increase by 1.3 unit.

## Contact
Duc Le
norton0704@gmail.com
