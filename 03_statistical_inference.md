# Statistical Inference

Statistical inference is the process of using data analysis to deduce properties of an underlying probability distribution. It is a fundamental aspect of data analysis that allows us to draw conclusions about a population based on a sample.

## 1. Descriptive Statistics

Before diving into inferential methods, it's crucial to understand descriptive statistics, which summarize and describe the main features of a dataset.

### 1.1 Measures of Central Tendency
- **Mean**: The average of a set of values
- **Median**: The middle value when the data is ordered
- **Mode**: The most frequent value in the dataset

### 1.2 Measures of Variability
- **Range**: The difference between the maximum and minimum values
- **Variance**: The average squared deviation from the mean
- **Standard Deviation**: The square root of the variance
- **Interquartile Range (IQR)**: The range between the first and third quartiles

### 1.3 Measures of Shape
- **Skewness**: Asymmetry of the probability distribution
- **Kurtosis**: The "tailedness" of the probability distribution

## 2. Inferential Statistics

Inferential statistics uses sample data to make estimates, predictions, or decisions about a larger population.

### 2.1 Point Estimation
- Estimating a single value for a population parameter
- Common estimators: sample mean, sample proportion, sample variance

### 2.2 Interval Estimation
- Providing a range of values likely to contain the population parameter
- Confidence intervals quantify the uncertainty in point estimates

## 3. Hypothesis Testing

Hypothesis testing is a method for testing a claim or hypothesis about a parameter in a population using data measured in a sample.

### 3.1 Steps in Hypothesis Testing
1. State the null (H₀) and alternative (H₁) hypotheses
2. Choose a significance level (α)
3. Collect sample data and calculate test statistic
4. Determine the p-value
5. Make a decision to reject or fail to reject the null hypothesis

### 3.2 Common Hypothesis Tests
- **Z-test**: For large samples with known population standard deviation
- **T-test**: For small samples or unknown population standard deviation
- **Chi-square test**: For categorical data
- **F-test**: For comparing variances or in ANOVA
- **ANOVA (Analysis of Variance)**: For comparing means of multiple groups

### 3.3 Type I and Type II Errors
- **Type I Error (False Positive)**: Rejecting a true null hypothesis (probability = α)
- **Type II Error (False Negative)**: Failing to reject a false null hypothesis (probability = β)
- **Power of a Test**: Probability of correctly rejecting a false null hypothesis (1 - β)

## 4. Confidence Intervals

A confidence interval provides a range of values that is likely to contain the population parameter with a certain level of confidence.

### 4.1 Interpreting Confidence Intervals
- A 95% confidence interval means that if we repeated the sampling process many times, about 95% of the intervals would contain the true population parameter.

### 4.2 Factors Affecting Confidence Interval Width
- Sample size
- Variability in the population
- Confidence level

## 5. Bayesian Inference

Bayesian inference is an approach to statistical inference that is distinct from the frequentist methods described above.

### 5.1 Key Concepts
- **Prior Distribution**: Initial belief about the parameter
- **Likelihood**: How probable the data is given the parameter
- **Posterior Distribution**: Updated belief about the parameter after observing the data

### 5.2 Advantages of Bayesian Inference
- Incorporates prior knowledge
- Provides direct probabilistic interpretations
- Handles small sample sizes well

## 6. Resampling Methods

Resampling methods use the observed data to estimate the sampling distribution of a statistic.

### 6.1 Bootstrap
- Randomly resampling with replacement from the original dataset
- Used for estimating standard errors and constructing confidence intervals

### 6.2 Permutation Tests
- Randomly shuffling labels to assess the significance of relationships in the data
- Used for hypothesis testing, especially with small sample sizes

## 7. Practical Considerations in Statistical Inference

- **Assumptions**: Be aware of the assumptions underlying statistical methods (e.g., normality, independence)
- **Sample Size**: Larger samples generally lead to more precise estimates and more powerful tests
- **Multiple Testing**: Be cautious when performing multiple tests, as it increases the chance of false positives
- **Effect Size**: Consider practical significance in addition to statistical significance
- **Reproducibility**: Ensure your analysis is reproducible and robust

Statistical inference is a powerful tool for understanding populations based on sample data. However, it's crucial to use these methods carefully, understanding their assumptions and limitations. Always consider the context of your data and the practical implications of your findings.

In the next section, we'll explore [Experimental Design & A/B Testing](04_experimental_design.md), where we'll see how these inferential concepts are applied in designing and analyzing experiments.

[Main Page](README.md)