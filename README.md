# MechaCar Statistical Analysis

## Linear Regression to predict MPG
The values of the coefficients is shown below:

> ![image](https://user-images.githubusercontent.com/86074187/136835361-fa2c8a93-21de-4edd-be25-dd808ded9657.png)

The p-values and r-squared values are shown below:

>![image](https://user-images.githubusercontent.com/86074187/136835704-acc51259-7e79-409f-95e6-6c980b21f562.png)

- Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance.
- The slope is not zero because the p-value less than 0.05.
- The R-squared value is 0.71, which means about 71% of the times the mpg values will be predicted correctly.

## Summary Statistics on Suspension Coils
### Total Summary
> ![image](https://user-images.githubusercontent.com/86074187/136836166-42f042ee-b08e-4df2-a556-cd0835048a2a.png)

### Lot Summary
> ![image](https://user-images.githubusercontent.com/86074187/136836223-636b520e-0e16-4273-9700-be173a204c5a.png)

- The current manufacturing data meets this design specification for all manufacturing lots since the variation for all lots is 62.3 which is less than 100.
- The current manufacturing data for Lot 1 and Lot 2 meet the specification because their variance is 0.97 and 7.47 respectively. As for Lot 3 data, the variance is 170.29 which is much higher than 100 and hence does not meet the specifications.

## T-Tests on Suspension Coils
### T-Test for All Manufacturing Lots

>![image](https://user-images.githubusercontent.com/86074187/136837001-73c0bf5d-01b2-4d5c-a324-caeaa43bed32.png)

### T-Test for Lot 1

> ![image](https://user-images.githubusercontent.com/86074187/136837101-d28b699e-b63b-4ef7-b610-ddd442239359.png)

### T-Test for Lot 2

> ![image](https://user-images.githubusercontent.com/86074187/136837133-7466c145-78c5-4b13-8efd-3db8073207b6.png)

### T-Test for Lot 3

> ![image](https://user-images.githubusercontent.com/86074187/136837169-802ad8b8-425c-464a-9ed3-19bd317e4ce7.png)

