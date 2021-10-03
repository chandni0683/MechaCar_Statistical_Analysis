# MechaCar_Statistical_Analysis
We used the following two datasets to the MechaCar prototypes:
1. MechaCar MPG dataset - The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.
2. Suspension Coil dataset - he MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots. 

## Linear Regression to Predict MPG
A Linear regression was performed using lm() function. The variables that were used to perform the fuction were vehicle length, spoiler angle, weight, ground clearance and AWD. 


<img width="814" alt="Screen Shot 2021-09-23 at 6 28 39 PM" src="https://user-images.githubusercontent.com/85711507/134596785-ba9faafc-e2b6-49d7-b497-8e0ce778dea4.png">

## Summary
The summary statistics for Suspension coil is as follows:

<img width="339" alt="Screen Shot 2021-10-02 at 9 46 27 PM" src="https://user-images.githubusercontent.com/85711507/135737597-514f2481-b29c-4b9e-9a0a-0dacacd0172c.png">

The above result show that the variance is 62.29356. The below result shows that the variance for lot 3 is 170.28 which exceeds the varaince values and also does not fufill the requirement which states that the variance of suspension coils should not exceed 100 PSI.

<img width="491" alt="Screen Shot 2021-10-03 at 2 34 46 PM" src="https://user-images.githubusercontent.com/85711507/135768850-1fde06fd-6e8e-4d64-bdde-6efc72d73772.png">

## T-Test on Suspension coils

