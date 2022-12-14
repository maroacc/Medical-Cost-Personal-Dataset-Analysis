# Medical Cost Personal Dataset Analysis

Analysis of the Medical Cost Personal Dataset https://www.kaggle.com/datasets/mirichoi0218/insurance

## 0. Introduction
### 0.1 Explanation of the dataset
- Context e.g what is the dataset about, why is studying this dataset important
- Description of the variables e.g **bmi** : minutes played by the player during that year
### 0.2 Project Scope
- Summary of what we are going to do in the project

## 1. Exploratory Analysis
### 1.1 Description of the dataset
- Variable types e.g qualitative, discrete, continuous (df.info() + insights)
- Variable description (df.describe())

### 1.2 Variable representation
- Plots of continuous and discrete variables (histograms, bar plots, density curves, box plots,  scatter plots etc)
- Identification of outliers

## 2. Statistical Inference & Hypothesis Testing
- Choose a couple of hypothesis to test based on the exploratory analysis
- confidence intervals
- power
- hypothesis test for the mean
- hypothesis test for the variance
- ANOVA

## 3. Modeling
- Correlation Analysis of all variables + pairplot()
- linear regression model (Insurance Forecast)
  - error, p-values and confidence intervales for bo and b1
  - confidence bands
  - prediction band
- Diagnostic plots (to check that a regression can be performed)
  - Residual vs fitted plot
  - Residual QQ-plot
  - Scale-location plot
  - Residual vs leverage plot
- linear regression with 3 parameters (beta0, beta1, beta2)
- linear regression with more than one variable ([BMI, age] --> Charges)

