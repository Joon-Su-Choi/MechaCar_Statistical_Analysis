# MechaCar_Statistical_Analysis

## Overview of Project

AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. Our purpose is to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG

![mech_1](https://user-images.githubusercontent.com/95505596/162512328-8d723986-f9ef-428e-be6c-ebcb5f886ce8.png)

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

The vehicle weight, spoiler angle, and AWD provide a non-random amount of variance. The vehicle length and ground clearance provide a random amount of variance according to the size pf their p-values.

---------------------------------------
**Is the slope of the linear model considered to be zero? Why or why not?**

The p-value of 5.35e-11 is smaller than the signifigance level of 0.05% which indicates that there is sufficient evidence to reject our null hypothesis. So we can state the slope of the linear model is not zero.

---------------------------------------
**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

The R-square value is 0.7149, which means that about 71% of all mpg predictions will be determined by this model. This linear model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

**Total Manufacturing Lot**

![mech_2](https://user-images.githubusercontent.com/95505596/162517478-182a6619-ca8d-4b3d-9317-18ac4436a6ac.png)

**Manufacturing Lots**

![mech_3](https://user-images.githubusercontent.com/95505596/162517722-6337a7bc-9485-411c-8816-ec11b2c6ea1a.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data that meet this design specification are Lot 1 and Lot 2. Lot 3 has a high variance of 170.29 which tells us it exceeds the design specifications.

## T-Tests on Suspension Coils

**All Lots**

![mech_8](https://user-images.githubusercontent.com/95505596/162580568-dd49e116-f9ff-43cc-9759-efd8f3d01e28.png)

- The sample mean is 1498.78. The p-value of 0.06 is higher than the significance level of 0.05, which indicates that we fail to reject the null hypothesis.

--------------------------------------------------------------------

**Lot 1**

![mech_5](https://user-images.githubusercontent.com/95505596/162520610-a30c9c7a-f023-4d55-b162-7991e2b4c9bb.png)

- The sample mean is 1500. The p-value of 1.00 is higher than the significance level of 0.05, which indicates that we fail to reject the null hypothesis.

--------------------------------------------------------------------

**Lot 2**

![mech_6](https://user-images.githubusercontent.com/95505596/162520838-c9744035-aa12-453d-83cf-1f701d98f5f1.png)

- The sample mean is 1500.2. The p-value of 0.06 is higher than the significance level of 0.05, which indicates that we fail to reject the null hypothesis.

--------------------------------------------------------------------

**Lot 3**

![mech_7](https://user-images.githubusercontent.com/95505596/162521108-4235e278-0a91-4637-886a-1d6f8a8624bf.png)

- The sample mean is 1496.14 The p-value of 0.04 is lower than the significance level of 0.05, which indicates that we reject the null hypothesis.

--------------------------------------------------------------------

## Study Design: MechaCar vs Competition

There are many ways to quantify how the MechaCar performs against the competition. To figure out what metrics we are looking for we need to deduce what is a deciding factor for the consumer when they are picking cars. Assuming the average consumer is looking for fast cars with high acceleration we can see where our journey begins.

The metrics we will test for are the following:

- Horsepower
- MPG
- Engine Size

Null Hypothesis: The performance of MechaCars are similar to the compeition.
Alternative Hypothesis: The performance of MechaCars are not similar to the competition.

To test this hypothesis we will be using a one sample t-test. The t-test will be comparing the population of all types of vehicles across multiple lots.

To be able to run this statistical test we will need a sample size that is large enough to approximate the true distribution of the population.
