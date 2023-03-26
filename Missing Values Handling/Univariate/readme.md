A Comparison of Mean, Median, Mode, and Arbitrary Value Imputation Techniques

Handling missing data is a critical step in the data analysis process. there are several techniques that can be used for imputing missing values. In this blog, we will discuss four techniques for univariate missing data imputation: mean, median, mode, and arbitrary value imputation

Univariate missing data handling:

Univariate missing data handling refers to the process of dealing with missing values in a single variable in a dataset. When dealing with missing data in univariate analysis, the goal is to estimate the missing values using statistical techniques that preserve the integrity of the data and minimize bias.

Assumptions of Univariate Missing Data Handling:

1.Missingness at Random (MAR) :   MAR is that the probability of a missing value is not related to the missing value itself but may be related to other variables in the dataset.

2.Missing Completely at Random (MCAR): The assumption of MCAR is that the probability of a missing value is completely random and unrelated to the other variables in the dataset.

3.Normality: Many statistical techniques used for univariate missing data handling assume that the distribution of the variable is normal or close to normal.

4.Independence: The assumption of independence is that the missing values in the dataset are not related to the other variables in the dataset.

5.Linearity: Some statistical techniques used for univariate missing data handling assume that the relationship between the missing variable and the other variables in the dataset is linear.

Advantage:

1.Easy to Implement:Univariate missing data handling is relatively easy to implement and does not require advanced statistical knowledge.

2.Minimizes Bias:By estimating missing values, univariate missing data handling can help to minimize bias and provide more accurate results.

Disadvantage:

1.May Increase Variance: Univariate missing data handling may increase the variance of the variable being imputed, which can decrease the accuracy of the analysis results.

2.Ignores Correlations: Univariate missing data handling assumes that the missing values are not related to any other variable in the dataset. This means that any correlations between the missing variable and other variables in the dataset are ignored, which can lead to biased or inaccurate results.

.

1.Mean Imputation:

Mean imputation involves replacing missing values with the mean of the available values. This technique assumes that the missing values are missing at random and that the distribution of the variable is approximately normal. Mean imputation is simple and easy to apply, but it can introduce bias if the distribution of the variable is skewed or if there are outliers in the data

2.Median Imputation:

Median imputation involves replacing missing values with the median of the available values. This technique is more robust to outliers and skewness than mean imputation. Median imputation is appropriate when the variable is not normally distributed.

3.Mode Imputation:

Mode imputation involves replacing missing values with the mode of the available values. This technique is useful for categorical variables. It assumes that the missing values are missing at random and that the mode is a good representation of the typical value for the variable

Given code, we will demonstrate how to handle missing data in the Titanic dataset using mean, median, mode, and arbitrary value imputation. we will use  all of thing which discuss above and comparison with output:

4.Arbitrary Value Imputation:

Arbitrary value imputation involves replacing missing values with an arbitrary value that is not related to the distribution of the variable. This technique is useful when we want to preserve the sample size and avoid introducing bias. However, it can also introduce noise into the data.
