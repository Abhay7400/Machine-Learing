Missing values are a common problem in real-world datasets, and handling them is a crucial step in data preprocessing. In the case of categorical data, missing values can be imputed using various techniques such as frequent-value imputation and missing-category imputation.

Univariate categorical data refers to a single categorical variable that has missing values. In this blog, we will explore two methods of handling missing values in univariate categorical data - frequent-value imputation and missing-category imputation.

Frequent-value imputation:

Frequent-value imputation is a method of handling missing values in categorical data. In this method, the missing values are imputed with the most frequent value of the variable. This is a simple and commonly used technique for handling missing values in categorical data when the missing values are assumed to be missing at random and not related to the underlying data

2. Missing-Category imputation

Missing-Category imputation is a method used to handle missing values in categorical variables by creating a new category specifically for the missing values. This technique is useful when the missing data is believed to be missing at random, meaning that the missingness is unrelated to the underlying data.

To implement Missing-Category Imputation, we replace all missing values with a new category label (e.g., "Missing" or "Unknown"). This new category label indicates that the data is missing and allows us to retain the information that the data is missing while still allowing us to use the other information in the dataset
