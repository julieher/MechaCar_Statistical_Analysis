# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![linear_regression](/Resources/Images/linear_regression.png)
Linear Regression

The two variables that provide a non-random amount of variance are vehicle length and ground clearance sine they have the most statistical significance.

The p-value of the linear regression analysis is 5.35e-11, which is smaller than the significance level of 0.05%. Therefore, there is *sufficient evidence to reject our null hypothesis*, meaning that the slope of our linear model is not zero.

## Summary Statistics on Suspension Coils

![total_summary](/Resources/Images/total_summary.png)

The weight capacities of suspension coils were tested in order to determine if the manufacturing process is consistent across all the lots.

The image above shows the summary statistics for suspension coils and we can see that the variance is 62.29356.

However, after calculating the summary statistics for each lot individually, we see that lot3 has a very large variance. Therefore, the design specifications lot3 needs to be addressed. (Image below)

![lot_summary](/Resources/Images/lot_summary.png)
Summary statistics for each lot

## T-Tests on Suspension Coils

In order to determine if all manufacturing lots are statistically different from the population mean of 1,500 PSI, t-tests were performed.

The p-value of all the lots is 0.06028 which is larger than the assumed significance level. Therefore, we do not have sufficient evidence to reject our null hypothesis.

Similarly, for lots 1 and 2, the p-value is above the significance level of 5%. Hence, we do not have sufficient evidence to reject our null hypothesis.

For lot 3, we can see that the p-value is below the significance level, therefore, we reject the null hypothesis. 

![ttst_all](/Resources/Images/ttest_all.png)
t-test of all lots

![lot1](/Resources/Images/lot1.png)
Lot 1

![lot2](/Resources/Images/lot2.png)
Lot 2

![lot3](/Resources/Images/lot3.png)
Lot 3

## Study Design: MechaCar vs Competition

I think MechaCar should consider using ANOVA testing in order to compare different categories. Such as cost, highway fuel efficiency, city fuel efficiency, maintenance cost, and safety ratings. 

This test is helpful because it can compare the mean of different samples and determine if they are significantly similar or different. Therefore, it can be used to compare the mean of car in these categories to the mean of MechaCar. The null hypothesis would follow:  If the p-value is greater than the significance level, then MechaCar is similar within these categories (the null hypothesis). On the other hand, If the p-value is less than the significance level, then MechaCar is significantly different.


