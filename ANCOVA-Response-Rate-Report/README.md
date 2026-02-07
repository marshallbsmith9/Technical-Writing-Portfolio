# Questionnaire Response Rates: ANCOVA Analysis with Covariates

**Author:** Marshall Smith
**Document Type:** Statistical Analysis Report
**Language Used:** SAS

## Project Overview
This report presents a statistical study examining whether the **color of questionnaire paper** influences response rates, while controlling for a continuous covariate: **parking lot size**. The analysis applies an **Analysis of Covariance (ANCOVA)** framework to isolate treatment effects while accounting for structural differences among experimental units.

The study uses real experimental design principles, regression modeling, and formal hypothesis testing to evaluate treatment effects and model assumptions.

## Study Design

- **Experimental Units:** 15 supermarket parking lots  
- **Treatment Factor:** Questionnaire paper color  
  - Blue  
  - Green  
  - Orange  
- **Covariate:** Number of parking spaces per lot  
- **Response Variable:** Percentage of completed questionnaires returned  

Each paper color was randomly assigned to five parking lots, producing a balanced design.

## Analytical Methods

The report includes the following analyses:

### Descriptive Statistics
- Summary statistics overall and by treatment group  
- Examination of variability in response rates and lot sizes  
- Correlation analysis between response rate and parking spaces  

### Data Visualization
- Scatter plots of response rate versus lot size  
- Color-coded treatment group comparisons  

### Regression Modeling
- Multiple linear regression with dummy-coded treatment variables  
- Mean-centering of covariates to improve interpretability  
- Model fit assessment using ANOVA and R²  

### ANCOVA
- Covariate-adjusted treatment comparisons  
- Type III sums of squares  
- Pairwise adjusted mean comparisons  

### Model Assumption Testing
- Test for homogeneity of regression slopes  
- Interaction analysis between treatment and covariate  
- Visual confirmation using fitted regression lines


## Key Findings

- **Parking lot size** has a strong negative association with questionnaire response rates.  
- **Paper color** demonstrates statistically significant differences in response rates after adjusting for lot size.  
- The ANCOVA model explains nearly all observed variation in the response variable (R² > 0.99).  
- Tests for parallel slopes suggest the assumption of homogeneous regression is reasonably satisfied, though marginal interaction effects are noted.


## Skills Demonstrated

- Experimental design and random assignment  
- ANCOVA and multiple regression modeling  
- Covariate adjustment and interpretation  
- Assumption checking and diagnostic reasoning  
- Statistical reporting and technical writing
- Knowledge and ability to work within SAS
