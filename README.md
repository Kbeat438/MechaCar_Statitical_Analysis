# MechaCar_Statitical_Analysis

## Linear Regression to Predict MPG

 1. The variables that provide a non-random amount of variance to the mpg values in the dataset are mpg, vehicle_length, and ground_clearance. You can see this from the data due to the P-values being below 0.05 which is our 95% confidence level of significance
 2. The slope of the linear model is considered to be non-zero. There are only two values near zero, vehicle_weight and spoiler_angle which are .001 and .069 respectively. The other values are greater than or less than one, which can not lead to a slope of zero.
 3. According to the data that we are aloted, this data set is an effective Linear model for predicting MPG of MechaCar protoypes. The R squared value is .71 which is a good output for our data. There could however be more relevant data and this could very well be a case of overfitting. 

(https://raw.githubusercontent.com/Kbeat438/MechaCar_Statitical_Analysis/main/Images/linear%20regression.png)
(https://raw.githubusercontent.com/Kbeat438/MechaCar_Statitical_Analysis/main/Images/Summary%20linear%20regression.png)


## Summary Statistics on Suspension Coils
 1. The design specifications for the MEchaCar susprension coils variance required to not exceed 100 pounds per square inch. The manufacturing data meets these specifications for all manufactorings lots in total, but does not meet for each lot individually. Specifically, lot 3 is producing a variance of 170.2
(https://raw.githubusercontent.com/Kbeat438/MechaCar_Statitical_Analysis/main/Images/Summary%20of%20PSI%20suspension%20coil%20data%20.png)
(https://github.com/Kbeat438/MechaCar_Statitical_Analysis/blob/main/Images/Summary%20of%20PSI%20grouped%20by%20manufactoring%20lot%20.png)

## T-Tests on Suspension Coils

#Summary 
The P value for all manufactoring lots is 1, meaning that our data does not support a rejection of the null hypothesis. The same is true for lot 3 with a p-value of .16. 
Both lot 1 and 2 however have a P-Value extremely close to zero so we can infer that the differnce is unlikely to be due to chance. All 4 p-values, however, are within the 95% confidence interval for their mean

(https://github.com/Kbeat438/MechaCar_Statitical_Analysis/blob/main/Images/T-test%20across%20all%20manufactoring%20lots.png)
(https://github.com/Kbeat438/MechaCar_Statitical_Analysis/blob/main/Images/lot%201%20t-test.png)
(https://github.com/Kbeat438/MechaCar_Statitical_Analysis/blob/main/Images/lot%202%20t-test.png)
(https://github.com/Kbeat438/MechaCar_Statitical_Analysis/blob/main/Images/lot%203%20t-test.png)

## Study Design: MechaCar vs Competition
1. A statistical study we can perform to quantify how the MechaCar performs against the competition is by comparing MPG, highway fuel efficency, and horse power.
2. The hypothesis is that with a higher MPG and horse power rating the highway fuel efficency will by higher. The Alternative hypothesis is that a higher mpg and horse power will have a lower highway fuel efficency.
3. Comparing the three based off a multiple linear regression would show how the variables influence highway fuel efficency and would show us how much they depend on one another. 
4. The data needed to run this test is mpg, highway fuel efficency ratings, and horsepower of a list of cars produced by MechaCar and their competitors. 


