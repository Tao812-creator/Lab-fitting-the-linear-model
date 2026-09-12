# Lab-fitting-the-linear-model
Scenario: Analyzing Housing Prices for Market Predictions
In the real estate industry, understanding the factors that influence housing prices is essential for accurate market predictions and investment decisions. Junior data scientists working in real estate analytics firms or financial institutions often need to build predictive models to estimate housing prices based on economic and demographic factors. One key variable that significantly impacts home values is median income: households with higher incomes are more likely to afford higher-priced homes.

In this lab, you will step into the role of a data scientist at a real estate investment firm. Your team is analyzing housing prices in California to help investors make data-driven decisions. The goal is to develop a simple linear regression model to determine how median household income affects median house value in different regions. By identifying influential data points and examining model residuals, you will assess the reliability of your predictions and refine your approach.

Your company’s analysts have noticed inconsistencies in previous housing price predictions, potentially due to outlier effects. If these influential points are not identified and managed properly, they could skew investment decisions, leading to financial losses. Your task is to investigate whether certain neighborhoods or price anomalies are distorting the model’s accuracy and provide a data-driven recommendation for improving prediction reliability.

By the end of this lab, you will gain hands-on experience in regression modeling, residual analysis, and outlier detection, which are all valuable skills that apply across multiple industries, including finance, healthcare, and fraud detection.

Problem-Solving Process
To tackle this problem, you will follow a structured approach:

Load and Prepare the Data: You will bring in the California Housing dataset and select key variables for analysis.
Fit a Linear Model: Using the statsmodels library, you will create a simple regression model to quantify the relationship between median income and housing prices.
Analyze Residuals: Residuals (the difference between predicted and actual values) help assess model accuracy. You will investigate whether your model systematically underestimates or overestimates housing prices.
Detect Influential Data Points: Not all data points contribute equally to model accuracy. Some outliers or high-leverage points may disproportionately affect predictions. You will compute Cook’s distance to detect these influential points.
