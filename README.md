# Autolib-electric-car-sharing-service-company-to-investigate-a-claim-about-the-blue-cars
The dataset from the Autolib Autolib electric car-sharing service company to investigate a claim about the blue cars. The main aim will be manifested on the blue cars returned, taken and the slots freed.
Problem Statement
The dataset from the Autolib Autolib electric car-sharing service company to investigate a claim about the blue cars. The main aim will be manifested on the blue cars returned, taken and the slots freed.
The null and alternate hypothesis will be are varying in the tests conducted as stated in the notebook as follows:

Normal distribution.
Ho = the data is normally distributed
H1 = the data is not normally distributed
 Correlation test
Ho = there is no correlation between the blue cars taken and the slots freed
H1 = there is a correlation between the blue cars taken and the slots freed

Parametric test
T Test
i) One-Sample T-test
Ho = there is no difference between the sample and the population
H1 = there is a difference between the sample and the population
ii) Two-sample T-test
H0 = there is no statistical difference between the sample means and the population
H1 = there is a statistical difference between the sample means and the population
Non parametric test
Chi-squared goodness of fit
H0 = A variable follows a hypothesized distribution.
H1 = A variable does not follow a hypothesized distribution.


Data Description
The data had no duplicated, null values. Outliers were removed to ensure validity of the data is achieved and to avoid extreme cases that may mislead the conclusions. The data after cleaning it remained with 16085 columns and  13 rows.
Hypothesis Testing Procedure
The hypothesis testing procedure will be carried out based on several techniques and methods.


The non parametric part was not done since it couldn't have any statistical importance according to the data. The chi squared test was assumed since the categorical variables didn't have any importance.

The null and the alternative hypothesis majorly came due to the high correlations. For the blue cars taken, returned and space freed had a high correlation thus drawing more attention for the hypothesis.

During the tests the alpha value of 5% percent was used to make decisions on the hypothesis testings. The alpha value was compared with the gotten p-value.

Hypothesis Testing Results
The results obtained from the different tests were as follows:
Normal distribution.
Ho = the data is normally distributed
H1 = the data is not normally distributed

From the shapiro wilk test we have proved that the data is not normally distributed having a very low p-value of 0.000000000136620256774300230518 and hence not a normal distribution. Thus the alternative hypothesis is adopted.
Correlation test
Ho = there is no correlation between the blue cars taken and the slots freed
H1 = there is a correlation between the blue cars taken and the slots freed

The spearman's correlation proves that there is a correlation between the blue cars taken and the slots freed thus adopt the null hypothesis, since the p value is very low 0.000000242460231543382547268951.


Parametric test
T Test
i) One-Sample T-test
Ho = there is no difference between the sample and the population
H1 = there is a difference between the sample and the population

we're going to reject the null hypothesis sice the p value is greater than 0.05. Thus there is a significant difference between the sample and the population mean with a p-value of 0.923813815922726.

ii) Two-sample T-test
H0 = there is no statistical difference between the sample means and the population
H1 = there is a statistical difference between the sample means and the population

From the results obtained there is no statistical difference between the sample mean and the population mean since the p value is greater than 0.05.Thus adopting the alternate hypothesis. with a p-value of 0.8701932846861928

Point Estimation

On the point estimation it was concluded that,  based on a sample of 100 blue cars taken, our estimator underestimates the true mean by -15.338293650793275. We can conclude that we can get a fairly accurate estimate of a large population from a fairly small subset.

Non parametric test
Chi-squared goodness of fit
H0 = A variable follows a hypothesized distribution.
H1 = A variable does not follow a hypothesized distribution.

Since the p-value (0.8128461413277058) is not less than 0.05, we fail to reject the null hypothesis. This means we do not have sufficient evidence to say that the true distribution blue cars taken is different from the distribution of the cars returned.

Discussion of Test Sensitivity
A Chi-Square Goodness of Fit Test is used to determine whether a variable follows a hypothesized distribution.

The test used the entire column as its bin size which lead to the following conclusion:

Since the p-value (0.8128461413277058) is not less than 0.05, we fail to reject the null hypothesis. This means we do not have sufficient evidence to say that the true distribution blue cars taken is different from the distribution of the cars returned.

Summary and Conclusions
The hypothesis process was carried out using several tests which gave conclusions on reference to the P-values.
