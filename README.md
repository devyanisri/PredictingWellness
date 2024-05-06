

**Project Title: Predicting Body Fat Percentage**

**Introduction:**

Understanding body fat percentage is crucial for assessing individual health status and developing effective fitness regimes. Traditional methods for measuring body fat can be expensive and inaccessible. This project aims to explore a dataset containing measurements relevant to body composition, including density determined through underwater weighing, circumference measurements, age, weight, and height data. The dataset is valuable for researchers and practitioners interested in understanding the relationship between various factors and body fat percentage.

**Background Research:**

To understand the theoretical background and methodologies used in this project, researchers can refer to the following sources:

- Bailey, Covert (1994). Smart Exercise: Burning Fat, Getting Fit.
- Behnke, A.R. and Wilmore, J.H. (1974). Evaluation and Regulation of Body Build and Composition.
- Siri, W.E. (1956). "Gross composition of the body".

These sources provide insights into Siri's equation, which is utilized for estimating body fat percentage.

**Data Source:**

The dataset used in this project was obtained from Kaggle as part of the ML Olympiad Competition: Predicting Wellness. It consists of observational data for 168 men, with measurements obtained through underwater weighing methods and circumference measurements.

**Methods/Results:**

- Exploratory Data Analysis (EDA) was conducted, including histograms of all features and correlation plots, to understand associations between variables and evaluate multicollinearity.
- Hypothesis testing, Pearson correlation tests, t-tests, and bootstrapping were performed to analyze differences in body fat percentage between age groups and correlations between height and body fat percentage.
- Linear regression modeling was employed, and diagnostic analyses of the model, ANOVA, and model selection techniques were utilized.
- Multilinear regression assumptions were considered, including linear relationship, multivariate normality, no multicollinearity, and homoscedasticity.
- The final model, a linear regression with predictors including height, abdomen circumference, and wrist circumference, achieved an R² value of 71%.

**Conclusions:**

The analysis demonstrated that a linear regression model with specific predictors accurately estimates body fat percentage. Other regression models such as xgboost, Gradient boosting, Lasso, and Ridge models can be explored for potentially higher R² values.
