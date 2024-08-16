# Jamboree Education-Linear-Regression
- Jamboree is a renowned education consultancy that has assisted thousands of students in achieving their dreams of studying at top colleges abroad. Specializing in test preparation for GMAT, GRE, and SAT, Jamboree's unique problem-solving methods ensure that students attain maximum scores with minimal effort.
- Recently, Jamboree launched an innovative feature on their website that allows students to check their probability of gaining admission to Ivy League colleges. This feature, tailored specifically for students from India, offers personalized insights into their chances of securing a spot in prestigious graduate programs, further solidifying Jamboree's commitment to supporting students in their academic journeys.
## Objective:
- Identify Key Admission Factors: Determine which variables (e.g. CGPA, GRE Scores, LOR, SOP, Research Experience) significantly impact the probability of admission to Ivy League colleges.
- Understand Interrelationships: Analyze how these factors interact with each other and their combined effect on admission chances.
- Improve Predictive Accuracy: Develop and refine predictive models to accurately estimate a student’s chance of admission based on the identified factors.
## Dataset Information:
### Source:
- Please check the dataset at: "[Dataset Link](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/839/original/Jamboree_Admission.csv)"
  
### Feature Information:
- Serial No. (Unique row ID)
- GRE Scores (out of 340)
- TOEFL Scores (out of 120)
- University Rating (out of 5)
- Statement of Purpose and Letter of Recommendation Strength (out of 5)
- Undergraduate GPA(CGPA) (out of 10)
- Research Experience (either 0 or 1)
- Chance of Admit (ranging from 0 to 1)

# Key Highlights:
## Exploratory Data Analysis (EDA)
- Observations
- Data Shape and Types
- Missing Values
- Statistical Summary
- Univariate Analysis
- Bivariate Analysis
- Duplicate Value Check:
- Outlier Treatment:
## Feature Engineering
## Data Preparation for Modeling
## Model Building
- Linear Regression
- Ridge and Lasso Regression

## Testing Assumptions of Linear Regression:
#### 1. Multicollinearity Check
  - Calculate the Variance Inflation Factor (VIF) and iteratively drop variables with VIF > 5.
#### 2.Mean of Residuals
  - Ensure that the mean of residuals is close to zero.
#### 3.Linearity of Variables
  - Check for patterns in the residual plot to confirm linearity.
#### 4.Homoscedasticity Test
  - Verify that the residuals exhibit constant variance.
#### 5.Normality of Residuals
  - Assess if the residuals follow a normal distribution using Q-Q plots and distribution plots.
    
## Model Performance Evaluation:
#### Performance Metrics
  - Evaluate model performance using metrics such as MAE, RMSE, R^2, and Adjusted R^2.
#### Train and Test Performance
  - Compare performance on training and testing datasets.
## Insights:
#### Significance of Predictor Variables
  - Highlight the most significant predictors
#### Model Improvement
  - Discuss potential improvements based on performance metrics.
## Recommendations:
- Actionable items for implementation of the model in real-world scenarios and the potential business benefits.

