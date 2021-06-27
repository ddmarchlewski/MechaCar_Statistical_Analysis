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
- 
This first image shows data for all the manufacturing lots.

![total_summary](https://user-images.githubusercontent.com/80054925/123559120-bb597880-d75f-11eb-871b-e5dd2266cbe5.png)

The second image shows data for the three lots individually.

![lot_summary](https://user-images.githubusercontent.com/80054925/123559123-c01e2c80-d75f-11eb-8d17-a32824c78b8d.png)

The variance of the coils is 62.29 PSI for all manufacturing lots. When looking at lots 1 and 2 individually, they have variances of 0.98 and 7.47 respectively. Lot 3 shows a much higher variance of performance of 170.29. The boxplot below shoes the differences of the lots. 

![Screenshot_2](https://user-images.githubusercontent.com/80054925/123559436-9ebe4000-d761-11eb-8fc5-cf794ecfebc8.png)

## T-Tests on Suspension Coils

The image below shows the t-test for all the lots. 

![All_lots](https://user-images.githubusercontent.com/80054925/123559683-1a6cbc80-d763-11eb-9749-9177f12fa91b.png)


Lots 1 sample mean is 1500 and a p-value of 1. There is no statistical difference between the observed sample mean and the presumed population mean. The image below shows the t-test for lot 1.

![Lot1](https://user-images.githubusercontent.com/80054925/123559632-d5e12100-d762-11eb-8dcf-052efa7bde70.png)

Lot 2's results are not drastically different with a sample mean of 1500.2 and a p-value of 0.6072. The sample mean and population mean are also 1500. Therefore, we cannot reject the null hypothesis. The image below shows the t-test for lot 2. 

![Lot2](https://user-images.githubusercontent.com/80054925/123559752-a1219980-d763-11eb-9568-498602ddc2d1.png)

Lot 3 has very difference results with a sample mean of 1496.14 and a p-value of 0.04. This is lower than the common significance level of 0.05 and that the null hypothesis can be rejected. The image below shows the t-test for lot 3. 

![Lot3](https://user-images.githubusercontent.com/80054925/123559847-2e64ee00-d764-11eb-96ea-982b75286ddc.png)
