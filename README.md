# MechaCar_Statistical_Analysis
## Project Overview



## Deliverable 1: Linear Regression to Predict MPG

The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle. Using my knowledge of R, designed a linear model that predicts the mpg of MechaCar prototypes by using several variables from the MechaCar_mpg.csv file. Then, write a short interpretation of the multiple linear regression results 

## Linear Regression to Predict MPG

![R_Analysisdv1](https://user-images.githubusercontent.com/58860105/143767644-ffe28ee0-5a8d-42ee-844b-7b65e3bafaee.PNG)

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
* Is the slope of the linear model considered to be zero? Why or why not?
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not

## Deliverable 2: Create Visualizations for the Trip Analysis

The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots. Using my knowledge of R, created a summary statistics table to show:


## Summary Statistics on Suspension Coils

### Total_Summary

![total_summary](https://user-images.githubusercontent.com/58860105/143768229-4d50d23a-0c61-479b-b315-9616baa07f61.PNG)


### lot_Summary 

![lot](https://user-images.githubusercontent.com/58860105/143769246-244cca3c-d140-448b-adc1-a3f2f6c85d59.PNG)

MechaCar suspension coils are designed in a manner so that their variance cannot exceed 100 pounds per square inch.
There is a global variance of 62.3 psi across all manufacturing lots.
As far as lot variances go, Lot 1 and Lot 2 both matched. The variance in Lot 3 is 170.3 psi which is way higher than required.



## Deliverable 3: T-Tests on Suspension Coils

Using my knowledge of R, to perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

## T-Tests on Suspension Coils

* Lot 1, The p-value for lot 1 is 1 above the significance level, assuming our significance level is 0.05 percent. As a result, the null hypothesis cannot be rejected, and therefore, they are equivalent.
* Lot 2, The t.test performed in lot 2 shows the p-values of 0.6072 with a mean of 1500.2. Our p-value is greater than 0.05 meaning the null hypothesis is strongly supported. This means we retain the null hypothesis and reject the alternative hypothesis.
* Lot 3, the p-Value is 0.04 less than 0.05, which is statistically significant. It indicates strong evidence against the null hypothesis. 

![T COIL](https://user-images.githubusercontent.com/58860105/143768711-d32b280e-9bf3-4530-b71f-8bf397d3d830.PNG)


## Study Design: MechaCar vs Competition
Using my knowledge of R, designed a statistical study to compare the performance of the MechaCar vehicles against the performance of vehicles from other manufacturers. A statistical study has been designed to determine the performance of MechaCar vehicles in comparison with those produced by other manufacturers. Potential metrics that consumers could find interesting in this study might include cost, city or highway fuel efficiency, horsepower, maintenance cost, or safety rating.


## Hypothesis:
* Null Hypothesis: MecharCar and Competition vehicles perform similarly in terms of average city and highway fuel efficiency.
* Alternative Hypothesis: Competition vehicles and MecharCars have different average city or highway fuel efficiency.

## Statistical Test:
Statistically, we will use a t-test to determine if there are differences in fuel economy between the MecharCar and the competition.
## Data Set Requirements:
* Data set of fuel economy from MechaCar.
* Data set of fuel economy from Competition 
