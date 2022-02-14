# MechaCar_Statistical_Analysis
## Overview of the Project
Mechacar, an AutorUs’s newest prototype is suffering from production troubles that are blocking the manufacturing team’s progress. The analysis below focuses on reviewing the production data for insights that may help the manufacturing team in determining the production issues!

## Purpose
The analysis focus on the following:
A. Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
B. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
C. Run t-tests to determine if the manufacturing lots are statistically different from the mean population
D. Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Design Summary
## Linear Regression to Predict MPG
The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle. using the linear regression, I have addressed the following:

![image](https://user-images.githubusercontent.com/92557075/153796666-d2e6c74b-67b5-4128-95d0-c7ea6880168e.png)

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The AWD and Spoiler angle provided the non random amount of variance.

* Is the slope of the linear model considered to be zero? Why or why not?
The slope encountered for this analysis is not considered to be zero.
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, because the adjusted R squared is 0.6825

## Summary statistics on suspension coil
The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots. 
![image](https://user-images.githubusercontent.com/92557075/153797188-cde6f96a-ab21-4a41-a3e0-451321a4e51e.png)
![image](https://user-images.githubusercontent.com/92557075/153797198-78ab1ab3-badc-443a-9f8a-fd30b7de1732.png)
According to the analysis, LOT 3 does not meet the design specification as the variance is well above 100. 

## T-Tests on Suspension Coils
![image](https://user-images.githubusercontent.com/92557075/153797362-ce8d4422-7875-436a-bf44-837d9ad55bbe.png)
1. Metric to test - highway fuel efficiency and vehicle weight
2. Null hypothesis or alternative hypothesis - Can perform multiple linear regression to analyse if both vehicle weight and horsepower effect fuel efficiency across manufacturers.
3. What statistical test would you use to test the hypothesis? And why? - multiple linear regression to analyse if both vehicle weight and horsepower effect fuel efficiency across manufacturers.
4. What data is needed to run the statistical test? Data from multiple manufactures for various models and specifications of cars. 
