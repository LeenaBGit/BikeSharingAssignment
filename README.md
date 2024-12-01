# Bike sharing Linear Regression Assignment
> BoomBikes is a bike-sharing provider who has recently suffered considerable dips in their revenue due to the ongoing Corona pandemic. The company finds it very difficult to sustain in the current market scenario. So it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end.


## Table of Contents
* [Objective](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## Objective
BoomBikes wants to understand the factors on which the demand for shared bikes depends so they can come up with a mindful business plan to accelerate its revenue. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Conclusions
- The equation for the best fitted line:
  cnt = 0.2366yr + 0.3788atemp - 0.1507windspeed - 0.1179summer + 0.0628winter - 0.2865Clear - 0.0763Light_weather - 0.0641Mar - 0.0640May - 0.0686Oct
- The closeness of R2 and adjusted R2 values between the training and test sets (R2: 0.823 vs. 0.801 and Adjusted R2: 0.819 vs. 0.792) in a linear regression model indicates effective generalization. This similarity suggests the model avoids overfitting to the training data and is likely to perform consistently on new unseen data.
- Bike demand is influenced by features such as yr, atemp, windspeed, summer, winter, clear weather, light weather, March, May and October.
- atemp, yr, and clear weather, exhibit the highest coefficient values, indicating their significant impact.


## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2
- Statsmodels - version 0.14.0
- Scikit-Learn - version 1.3.0


## Acknowledgements
- This project was inspired by live session of UpGrad on Linear Regression Models by Akash Akash
- UpGrad tutorials on Linear Regression on the learning platform


## Contact
Created by @LeenaBGit
