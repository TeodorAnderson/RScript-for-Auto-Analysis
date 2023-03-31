# RScript-for-Auto-Analysis

## Linear Regression to Predict MPG

![Screenshot 2023-03-30 192646](https://user-images.githubusercontent.com/116928193/229011434-8049e1dc-3106-4064-a01f-e772fc7b0be8.png)
As seen in the screenshot above, when using linear regression to analyize which variables provide the non-random amount of variance to mpg, vehicle length and ground clearance, respectively, have the most impact.

Furthermore, with a p-value of 5.35e-11, far less than the significance level of 0.05, we can conclude that the slope will not be zero

In conclusion, by using this linear model and achieving multiple R-squared value of 0.7149, we can declare that the variables given today have a good chance of prediciting miles per gallon

## Summary Statistics on Suspension Coils
![Screenshot 2023-03-30 235030](https://user-images.githubusercontent.com/116928193/229045471-fb2c3b92-dac8-4151-b7c5-53d00871fdf1.png)
![Screenshot 2023-03-30 235023](https://user-images.githubusercontent.com/116928193/229045508-699205ac-f0ae-4ceb-bb50-05fa0e01b8cb.png)

The total variance of all lots is safely below 100psi for suspension coils, but when grouping by lots, we noticed that lot 3 was not maintaining safety standards

## T-Tests on Suspension Coils

![Screenshot 2023-03-30 235900](https://user-images.githubusercontent.com/116928193/229046936-ffb0a2b7-1036-4083-af66-00e469c95532.png)
The t-test run on all lots show that with a p value of 0.06, the null hypothesis cannot be rejected
![image](https://user-images.githubusercontent.com/116928193/229047275-79eff50c-0a39-4233-9e91-fefa0ef03c48.png)
However, when running t-tests on all lots, lot 3 has a p value low enough to reject the null hypothesis 
