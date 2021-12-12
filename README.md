# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
![LinearRegressionMPG](https://github.com/James-Harkin/MechaCar_Statistical_Analysis/blob/main/static/images/LinearRegressionMPG?)
* As shown in the data, vehicle_length and ground_clearance provided a non-random amount of variance due to their very low p values.
* The slope of the linear model would not be considered zero because the p value for the model is 5.35e-11 which is very small.
* This model successfully predicts mpg of MechaCar prototypes with an r squared of 0.7149 meaning 71% accuracy.
## Summary Statistics on Suspension Coils
The design specifications state that variance must not exceed 100 PSI.
![total summary](https://github.com/James-Harkin/MechaCar_Statistical_Analysis/blob/main/static/images/total_summary?)
* All lots in total successfully meet the specifications with 62 PSI of variance.
![total summary](https://github.com/James-Harkin/MechaCar_Statistical_Analysis/blob/main/static/images/lot_summary?)
* When broken down into lots we see that lot 3 is not meeting standards with 170 PSI.
* The other two are above standards because their PSI is well below 100.
## T-Tests on Suspension Coils
![total summary](https://github.com/James-Harkin/MechaCar_Statistical_Analysis/blob/main/static/images/t-test?)
* The true mean is 1498.78 which is very close to the population mean of 1500.
![total summary](https://github.com/James-Harkin/MechaCar_Statistical_Analysis/blob/main/static/images/t-testLots?)
* The true mean is very close to 1500 for all three lots.
* Only lot 3 has a p value that falls below the standard 0.05. Meaning there is enough evidence to reject a null hypothesis.