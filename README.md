# MechaCar_Statistical_Analysis

## Overview of the Analysis
The purpose of this analysis is to use variety of metrics that can affect AutoRUs' newest prototype, the MechaCar which is suffering from production troubles. The metrics include vehicle length, weight, spoiler angle, ground clearance, AWD capabilities, MPG, and PSI.

## Linear Regression to Predict MPG
Please see the below screenshot of the linear regression summary.
![Linear Regression Summary](https://github.com/Oysterrr/MechaCar_Statistical_Analysis/blob/main/Resources/linear_regression_summary.PNG)

* Since the variance of a non-random variable is usually 0, we can see from the summary that the intercept, vehicle_length, and ground_clearance coeeficients provide a non-random amount of variance to the mpg values. 
* At a significant level of 0.05, we can reject the null hypothesis due to the small p-value (5.35e-11), which means the slope does not equal to zero.
* As we can see from the summary, the multiple R-squared (0.7149) explains the output results can be highly explained by input value. The adjusted R-squared increases when the new term improves the model more than would be expected by chance and the adjusted R-squared (0.6825) also indicates this linear model predicts the MPG of MecharCar prototypes effectively.

## Summary Statistics on Suspension Coils
Please see the below screenshots of the linear regression summary.
