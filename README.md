# AutosRUs' MechaCar
## The purpose of this project:
The purpose of this project is to analyze production data for AutosRUs' MechaCar prototypes and provide insights that can help the manufacturing team. It involves performing multiple linear regression analyses to predict the mpg of MechaCar prototypes, collecting summary statistics on the suspension coils' PSI from manufacturing lots, running t-tests to determine if the lots are statistically different from the mean population, and designing a statistical study to compare the MechaCar's vehicle performance against vehicles from other manufacturers.

![data-16-manufacturing-lot](https://user-images.githubusercontent.com/111480084/225206941-e3d82267-653c-4487-b4c2-8679612e4406.png)

![data-16-total-summary-data-mean-median-variance-sd](https://user-images.githubusercontent.com/111480084/225206952-65d750cc-05bc-4fe8-b85f-65bb4e7929c8.png)

Linear Regression to Predict MPG:

1. The mpg variable is the only predictor variable in the model, so it is the only variable that could contribute a non-random amount of variance to the response variable. Based on the coefficients table, the mpg variable has a p-value of 2.63e-06, which suggests that it is significantly different from zero. This means that it is likely that the mpg variable is contributing a non-random amount of variance to the response variable.

3. The slope of the linear model is not necessarily considered to be zero. In this particular model, the coefficient for mpg is significantly different from zero (p-value = 2.63e-06), which suggests that the slope is not zero.

4. It is not clear from the output provided whether the linear model effectively predicts mpg values for MechaCar prototypes. To determine the effectiveness of the model, I would need to evaluate the model's performance on a test set of data or use cross-validation to estimate the model's generalization error. I would also need to consider whether the model's assumptions are reasonable for the data and whether the model is appropriate for the problem at hand.

Visualizations for the Trip Analysis:
Based on this summary, it seems that the values in the Manufacturing_Lot column are relatively close to each other for Lot1 and Lot2, but there is more variation in the values for Lot3. The standard deviation for Lot3 is much larger than for the other two lots, which suggests that the values are more spread out.

T-Tests on Suspension Coils:

The t-value of -1.8931 indicates the difference between the sample mean (1498.78) and the specified value (1500) in units of the standard error of the mean.

The df (degrees of freedom) value of 149 is the number of observations in the sample minus 1.

The p-value of 0.06028 is the probability of obtaining a t-value as extreme as the one observed, given that the null hypothesis (the mean is equal to 1500) is true. A p-value less than the significance level (often set at 0.05) suggests that the null hypothesis can be rejected. In this case, the p-value is not less than 0.05, so we cannot reject the null hypothesis.

Overall, the results of the t-test suggest that the mean of the PSI column is not significantly different from 1500, but it is close to that value. The 95% confidence interval includes the value of 1500, which supports this conclusion.

Study Design: MechaCar vs Competition:

Fuel costs are a top concern for many consumers. These costs vary based on the type of vehicle, with luxury cars requiring more expensive fuel. When purchasing a car, individuals consider their budget and fuel consumption needs. The focus of this experiment is to evaluate fuel efficiency. Market prices for fuel can fluctuate, but fuel efficiency ultimately affects the amount of gasoline consumed. The experiment will test fuel efficiency in two ways: first, by measuring fuel efficiency on both highways and local roads with a full tank of fuel; and second, by testing fuel efficiency in different weather conditions, such as summer and winter, with a full tank of fuel. The T-test will be used to compare the average results of the experiment to the population average to determine fuel efficiency.







