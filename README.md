# MechaCar_Statistical_Analysis


# Deliverable 1
## Linear Regression to Predict MPG
<img width="1440" alt="Screen Shot 2022-03-21 at 8 02 22 PM" src="https://user-images.githubusercontent.com/91028094/159382174-c59b9f82-eadb-47c3-b53c-b8de18d8beb9.png">


1. The the p-value of our linear regression analysis is 5.35 x 10'-11, which is much smaller than our assumed significance level of 0.05%
Therefore there is sufficient evidence to reject our null hypothesis which means slope != 0.
2. According to our results, vehicle length and ground clearence (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words the vehicle length and ground clearance have a significant impact on mpg.
3. The r-squared value is 0.71 which means that 71% of the variability of our dependent variable (mpg) is explained using our Linear regression model.
# Deliverable 2
## Summary Statistics on Suspension Coils
<img width="418" alt="Screen Shot 2022-03-21 at 8 28 17 PM" src="https://user-images.githubusercontent.com/91028094/159384626-61b56951-1dce-4894-922a-ed594c22ded4.png">
<img width="490" alt="Screen Shot 2022-03-21 at 8 28 13 PM" src="https://user-images.githubusercontent.com/91028094/159384627-f9aa1844-9655-4814-b2c6-982b939ca62d.png">

The overall variance for the entire dataset indicates that the current manufacturing data meets the 1500 pounds per square inch variance limitation. However, when separated into three lots, the third lot demonstrates a much higher variance, probably because the lots are chosen randomly, there is a possiblity that a third of the lot does not meet the necessary suspension coils requirement.

# Deliverable 3
## T-Tests on Suspension Coils
<img width="412" alt="Screen Shot 2022-03-21 at 9 35 04 PM" src="https://user-images.githubusercontent.com/91028094/159389946-1feb393c-1ca0-4060-b940-f83c1afbcc4b.png">
p-value is 0.06 which is > than 0.05 p-value, which is considered as statistically significant so, we fail to reject the null hypothesis in this case. Another thing is the narrow confidence level which implies that there is a smaller chance of obtaining an observation within that interval, it provides greater accuracy than a wider interval.



<img width="407" alt="Screen Shot 2022-03-21 at 9 40 29 PM" src="https://user-images.githubusercontent.com/91028094/159390393-baaa8215-8e32-4d4a-8b6e-bc90dc278902.png">

Lot 1 -
At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 1. An interesting correlation between p-value and confidence intervals is that as the p-values get larger, the confidence interval becomes smaller, implying more precision in predicting the true population mean.

Lot 2 -
At a significance level of 0.05, we fail to reject the null hypthesis again since the p-value equals 0.6072. The second lot also has a relatively small confidence interval.

Lot 3 -
At a significance level of 0.05, we can reject the null hypothesis since the p-value equals 0.04168. The mean of this sample is also significantly smaller in comparison to the previous two lots. More importantly, unlike the previous two lots, the confidence interval for the third lot does not include the predicted population mean.

# Deliverable 4
## Study Design: MechaCar vs Competition
Due to increasing high prices of Gasoline due to war in Ukraine and Russia. Consumers like me would be really interested in statistical analysis using Linear regression based on a car efficiency.

Metrics we could use.

Fuel efficiency: independent variable

MPG: dependent variable

Horsepower: dependent variable

