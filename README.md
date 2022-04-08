# MechaCar_Statistical_Analysis

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

![mech_4](https://user-images.githubusercontent.com/95505596/162520022-7cec805a-c192-4cb1-be38-6a1633141cd3.png)

**Lot 1**

![mech_5](https://user-images.githubusercontent.com/95505596/162520610-a30c9c7a-f023-4d55-b162-7991e2b4c9bb.png)

**Lot 2**

![mech_6](https://user-images.githubusercontent.com/95505596/162520838-c9744035-aa12-453d-83cf-1f701d98f5f1.png)

**Lot 3**

![mech_7](https://user-images.githubusercontent.com/95505596/162521108-4235e278-0a91-4637-886a-1d6f8a8624bf.png)




