# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  
![Screenshot_1](https://user-images.githubusercontent.com/80054925/123557505-be03a000-d756-11eb-800a-0313fb3f96bd.png)

  The ground clearance and vehicle length provide a non-random amount of variance. 

- Is the slope of the linear model considered to be zero? Why or why not?

  The p-value is 5.35e-11. This is less than the significance level of 0.05%. Based on this information, the slope cannot be 0. 

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The R-squared value is 0.7149. This means that about 71% of the mpg predictions will use this model and be correct. This model predicts mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
