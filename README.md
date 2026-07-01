STATISTICAL BUSINESS ANALYSIS 


1. Project Overview
   
Introduction

Statistical analysis plays a vital role in understanding business performance and supporting data-driven decision-making. This project analyzes a sales dataset using various statistical techniques to identify trends, relationships, and patterns within the business data.

The analysis includes descriptive statistics, data distribution analysis, hypothesis testing, confidence interval estimation, correlation analysis, and regression analysis.

The project was implemented using Python in Google Colab with several scientific computing libraries. Visualizations and statistical tests were used to interpret business performance and provide practical recommendations.

Project Goals

The primary goals of this project are:

Analyze sales data using statistical methods.

Calculate descriptive statistics for business variables.

Study the distribution of sales data.

Identify outliers using statistical techniques.

Test the normality of numerical variables.

Analyze relationships among sales variables.

Perform hypothesis testing.

Estimate confidence intervals.

Build a linear regression model.

Generate business insights and recommendations.

Project Objectives

The objectives of this project include:

Calculate mean, median, mode, variance, and standard deviation.

Visualize data using histograms, box plots, density plots, scatter plots, and heatmaps.

Perform Shapiro-Wilk Normality Test.

Compute Pearson Correlation and Covariance.

Conduct three hypothesis tests:

One Sample T-Test

Independent T-Test

One-Way ANOVA

Calculate a 95% confidence interval.

Perform Linear Regression.

Evaluate model performance using the R² Score.

Provide business recommendations based on statistical findings.

2. Methodology and Results Interpretation

The statistical analysis was carried out in seven stages.

Day 1 – Descriptive Statistics

Methodology

Descriptive statistics summarize the main characteristics of the dataset.

The following measures were calculated for the numerical variables:

Mean

Median

Mode

Variance

Standard Deviation

Minimum

Maximum

Range

Quartiles

Skewness

Kurtosis

Results Interpretation

The mean provides the average value of each numerical variable.

The median represents the central value and is less affected by extreme values.

The mode identifies the most frequently occurring value.

Variance and standard deviation indicate how widely the data is spread.

Skewness shows whether the distribution is positively or negatively skewed.

Kurtosis indicates whether the data distribution has heavier or lighter tails than a normal distribution.

These statistics provide an overall understanding of sales performance and variability.

Day 2 – Data Distribution Analysis

Methodology

The distribution of numerical variables was analyzed using:

Histograms

Box Plots

Density Plots

Normal Probability Distribution

Shapiro-Wilk Normality Test

Outliers were detected using the Interquartile Range (IQR) method.

Results Interpretation

Histograms display the frequency distribution of each variable.

Box plots identify unusually high or low observations that may influence statistical analysis.

Density plots provide a smooth representation of the distribution.

The Shapiro-Wilk Test evaluates whether the data follows a normal distribution.

Decision Rule:

p-value > 0.05 → Data is normally distributed.

p-value ≤ 0.05 → Data is not normally distributed.

The normality test determines whether parametric statistical methods are appropriate.

Day 3 – Correlation Analysis

Methodology

Correlation analysis was performed using:

Pearson Correlation Matrix

Covariance Matrix

Correlation Heatmap

Pair Plot

Scatter Plot

Results Interpretation

The Pearson correlation coefficient measures the strength and direction of the relationship between two numerical variables.

Correlation values range from:

+1 → Strong Positive Relationship

0 → No Relationship

-1 → Strong Negative Relationship

The heatmap visually represents correlation values using colors.

Scatter plots illustrate the relationship between Price and Total Sales.

Positive correlation indicates that both variables increase together, while negative correlation indicates an inverse relationship.

Day 4 – Hypothesis Testing

Three hypothesis tests were conducted.

Hypothesis Test 1 – One Sample T-Test

Objective

Determine whether the average Total Sales differs significantly from ₹150000.

Null Hypothesis (H₀)

Mean Total Sales = ₹150000

Alternative Hypothesis (H₁)

Mean Total Sales ≠ ₹150000

Results Interpretation

If the p-value is less than 0.05, the null hypothesis is rejected, indicating that the average Total Sales is significantly different from ₹150000.

Hypothesis Test 2 – Independent T-Test

Objective

Compare the average sales between the North and South regions.

Null Hypothesis (H₀)

Average sales are equal.

Alternative Hypothesis (H₁)

Average sales are different.

Results Interpretation

The test determines whether regional differences in sales are statistically significant.

Hypothesis Test 3 – One-Way ANOVA

Objective

Compare average sales among all regions.

Null Hypothesis (H₀)

All regional averages are equal.

Alternative Hypothesis (H₁)

At least one region has a different average sales value.

Results Interpretation

ANOVA evaluates whether regional sales differ significantly across multiple groups.

Day 5 – Confidence Interval

Methodology

A 95% confidence interval was calculated using the sample mean and standard error.

Margin of Error was also computed.

Results Interpretation

The confidence interval estimates the range in which the true population mean is expected to lie with 95% confidence.

The margin of error represents the maximum expected difference between the sample mean and the population mean.

Day 6 – Regression Analysis

Methodology

Simple Linear Regression was performed.

Independent Variable:

Price

Dependent Variable:

Total Sales

The following metrics were calculated:

Regression Coefficient

Intercept

R² Score

OLS Regression Summary

Results Interpretation

The regression equation predicts Total Sales based on Price.

The regression coefficient indicates how Total Sales changes with Price.

The intercept represents the predicted sales when Price equals zero.

The R² Score measures how well the regression model explains the variation in Total Sales.

OLS regression provides detailed statistical information, including coefficient significance, confidence intervals, and model accuracy.

Day 7 – Business Insights

Key Findings

The descriptive statistics summarize business performance.

Distribution analysis identifies variability and outliers.

Correlation analysis reveals relationships among variables.

Hypothesis testing validates statistical assumptions.

Confidence intervals estimate future average sales.

Regression analysis predicts Total Sales based on Price.

Business Recommendations

Increase inventory for high-demand products.

Focus promotional activities in high-performing regions.

Optimize pricing strategies using regression analysis.

Improve sales in low-performing regions through targeted marketing.

Continue monitoring sales trends using statistical techniques.

3. Setup Instructions
   
Step 1

Install Python 3.

Step 2

Install the required libraries.

pip install pandas

pip install numpy

pip install matplotlib

pip install seaborn

pip install scipy

pip install scikit-learn

pip install statsmodels

Step 3

Open Google Colab.

Step 4

Upload the following file:

sales_data.csv

Step 5

Run all notebook cells sequentially.

Step 6

Review generated visualizations and statistical outputs.

4. Code Structure

Statistical_Business_Analysis/

│

├── statistical_analysis.ipynb

├── business_data.csv

├── statistical_report.pdf

├── hypothesis_tests_results.txt

├── requirements.txt

├── README.md

│

└── visualizations/

     ├── histogram.png

     ├── boxplot.png

     ├── density_plot.png

     ├── heatmap.png

     ├── scatter_plot.png

     └── regression_plot.png

5. Visual Documentation

Include screenshots of the following outputs in the report:

Dataset Preview

Dataset Information

Descriptive Statistics Output

Histogram of Quantity,Price and Total Sales

Box Plots of Quantity,Price and Total Sales



Density Plots

Normal probability distribution


Correlation Heatmap


Pair Plot

Scatter Plot 


OLS Regression Summary

Regression Plot

Final Business Insights Output


6. Technical Details

Programming Language

Python 3


Development Environment

Google Colab

Libraries Used

Pandas

NumPy

Matplotlib

Seaborn

SciPy

Scikit-learn

Statsmodels

Algorithms Used

Descriptive Statistics

Calculates central tendency and dispersion measures.

IQR Outlier Detection

Identifies extreme observations using quartiles.

Shapiro-Wilk Test

Tests whether numerical variables follow a normal distribution.

Pearson Correlation

Measures the linear relationship between numerical variables.

Covariance Matrix

Measures how two variables vary together.

One Sample T-Test

Compares the sample mean against a known value.

Independent T-Test

Compares the means of two independent groups.

One-Way ANOVA

Compares the means of more than two groups.

Confidence Interval

Estimates the population mean with a specified confidence level.

Linear Regression

Models the relationship between Price and Total Sales.

OLS Regression

Provides a detailed statistical summary of the regression model.

Data Structures

The project primarily uses Pandas DataFrames to store and manipulate the sales dataset. Numerical columns are processed using NumPy arrays during statistical computations, while dictionaries and lists are used internally for grouping data (for example, grouping sales by region for ANOVA).

Architecture

The project follows a sequential data analysis workflow:

Data Loading

Data Inspection and Cleaning

Descriptive Statistics

Data Visualization

Outlier Detection

Normality Testing

Correlation Analysis

Hypothesis Testing

Confidence Interval Estimation

Regression Analysis

Business Insights and Recommendations

This modular structure ensures each analysis stage builds logically on the previous one.

7. Testing Evidence

Test Case

Expected Result

Actual Result

Status

Dataset Loading

Dataset loads successfully

Dataset loaded successfully

 Pass
 
Missing Value Check

Missing values identified correctly

Correct output displayed

Pass

Descriptive Statistics

Statistical measures calculated

Mean, median, mode, variance, and standard deviation displayed

 Pass
 
Histogram Generation

Histograms created

Histograms generated successfully

Pass

Box Plot Generation

Outliers visualized

Box plots displayed correctly

Pass

Shapiro-Wilk Test

Test statistic and p-value returned

Normality test completed

 Pass
 
Correlation Analysis

Correlation matrix generated

Pearson correlation matrix displayed

 Pass
 
Heatmap

Heatmap created

Heatmap generated successfully

 Pass
 
Hypothesis Tests

Test statistics and p-values calculated

One Sample T-Test, Independent T-Test, and ANOVA completed

 Pass
 
Confidence Interval

95% confidence interval calculated

Confidence interval and margin of error displayed

 Pass
 
Regression Analysis

Regression model fitted

Slope, intercept, R² score, and OLS summary generated

 Pass
 
Business Insights

Recommendations generated

Business insights displayed successfully

 Pass


8. Conclusion

This project successfully demonstrates the application of statistical techniques to business sales data. Descriptive statistics provided a clear summary of the dataset, distribution analysis identified patterns and potential outliers, and correlation analysis highlighted relationships among key variables. Hypothesis testing validated statistical assumptions, confidence intervals estimated population parameters, and regression analysis modeled the relationship between price and total sales. The findings were translated into practical business recommendations, illustrating how statistical analysis can support informed business decisions and future sales planning.

