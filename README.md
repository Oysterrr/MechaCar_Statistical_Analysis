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
Please see the below screenshots of the statistical summary of multiple production lots in AutoRUs.
![Lot Total Summary](https://github.com/Oysterrr/MechaCar_Statistical_Analysis/blob/main/Resources/total_summary_table.PNG)
![Lot Individual Summary](https://github.com/Oysterrr/MechaCar_Statistical_Analysis/blob/main/Resources/lot_summary_table.PNG)

The overall variance for the entire dataset indicates that the current manufacturing data meets the 100 pounds per square inch variance limitation. However, when separated into three lots, the third lot demonstrates a much higher variance. Because the lots are chosen randomly, there is a possiblity that a third of the lot does not meet the necessary suspension coils requirement.

## T-Tests on Suspension Coils
### T-Test of the Entire Lot
Please see the below screenshot of the T-test of the entire production lot in AutoRUs.
![Entire Lot T-Test](https://github.com/Oysterrr/MechaCar_Statistical_Analysis/blob/main/Resources/t-test.PNG)

At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 0.06. Therefore, we cannot reject the fact that the sample mean may be equivalent to the true population mean.

### T-Test of Three Individual Lots
Please see the below screenshot of the T-tests of three individual production lots in AutoRUs.
![Individual Lot T-Test](https://github.com/Oysterrr/MechaCar_Statistical_Analysis/blob/main/Resources/lots_t_test.PNG)

* Lot 1 - At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 1.
* Lot 2 - At a significance level of 0.05, we fail to reject the null hypthesis again since the p-value equals 0.6072.
* Lot 3 - At a significance level of 0.05, we can reject the null hypothesis since the p-value equals 0.04168.

## Study Design: MechaCar vs Competition
Another statistical study that can be performed to determine MechaCar's standing against its competition is a linear regression on city and highway fuel efficiency. The metrics that can be included in this analysis are:
* City and highway fuel efficiency: dependent variable
* Vehicle weight: independent variable
* AWD capabilities: independent variable
* MPG: independent variable

Null hypothesis: The weight, AWD capabilities, and MPG of the vehicle do not impact the city and highway fuel efficiency.


