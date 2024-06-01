## Problem Statement:

# Objective:

To create a useful tool for Jamboree that helps Indian students predict their chances of getting into Ivy League colleges.

# Key Goals:

# Identify Important Factors:

Find out the key things that affect admissions to Ivy League schools for Indian students. These might include grades, test scores (GMAT, GRE, SAT), activities outside of school, work experience, recommendation letters, and personal essays.

# Understand Relationships:

See how these factors influence each other and how they work together to affect admission chances. Determine the importance of each factor in the admission process.

# Build Predictive Insights:

Develop a model that can predict a student’s chances of getting into an Ivy League school based on their profile. Use past data and statistical methods to make accurate predictions.

# Improve User Experience:

Add this predictive model to Jamboree’s website in a way that’s easy to use. Students should be able to enter their details and see their admission chances, along with tips to improve their profiles.

# Expected Outcomes:

* A clear understanding of the factors affecting Ivy League admissions for Indian students.

* A reliable model that predicts admission chances.


* A user-friendly tool on Jamboree’s website that gives students personalized admission insights and advice.


This will help Jamboree guide their students better, increasing their chances of getting into top colleges.

# Analysis Overview:
- [Jupyter Notebook link : Analysis on DATA](Jamboree_Case_Study.ipynb)

# Based on the model evaluation results and the regression analysis, here are some summarized recommendations:

# Model Performance:

* Mean Absolute Error (MAE): 0.0505



* On average, the predicted values are off by about 0.0505 from the actual values, which is quite low, indicating good prediction accuracy.


* Root Mean Square Error (RMSE): 0.0676


* This measure indicates that the model’s predictions are fairly accurate, with a typical prediction error of about 0.0676.


* R-squared (R²): 0.7595


* Approximately 75.95% of the variance in the "Chance of Admit" can be explained by the model's features. This is a good level of explanatory power.

# OLS Regression Results:
* R-squared (R²): 0.839

* A higher value than the test R², indicating that the model fits the training data well.
* Adjusted R-squared: 0.836
* Consistent with the high R², showing a robust model fit even after accounting for the number of predictors.
* F-statistic: 383.6 (Prob > F: 9.78e-144)
* The very high F-statistic and extremely low p-value indicate that the overall model is statistically significant.

# Understanding the Coefficients:

* Coefficient Interpretation:

* Constant (Intercept): 0.7269

* This is the baseline value of the "Chance of Admit" when all predictors are zero. It serves as the starting point for predictions.
* TOEFL Score: 0.0177

* For each additional point in the TOEFL score, the "Chance of Admit" increases by approximately 0.0177, holding all other factors constant. This indicates that higher TOEFL scores positively impact admission chances.
* GRE Score: 0.0231

* For each additional point in the GRE score, the "Chance of Admit" increases by approximately 0.0231, holding all other factors constant. This shows that GRE scores are an important factor in the admissions process.
* CGPA: 0.0741

* For each additional point in CGPA, the "Chance of Admit" increases by approximately 0.0741, holding all other factors constant. This is the largest coefficient, indicating that CGPA has the strongest impact on admission chances.
* LOR (Letter of Recommendation): 0.0183

* For each additional point in the strength of the letters of recommendation, the "Chance of Admit" increases by approximately 0.0183, holding all other factors constant. Strong recommendations significantly enhance admission prospects.

* Research: 0.0144

* Having research experience increases the "Chance of Admit" by approximately 0.0144, holding all other factors constant. Engaging in research is beneficial for admission chances.

# Statistical Significance:
* P-values for all coefficients are very low (p < 0.05), indicating that all predictors are statistically significant.

# Recommendations for Students:

## Prioritize Academic Scores:

* TOEFL and GRE Scores: Aim for high scores in these exams as they positively 
influence admission chances.
* CGPA: Maintain a high GPA throughout your academic career as it has the strongest impact on admissions.
## Strengthen Letters of Recommendation:

* Work on obtaining strong letters of recommendation from professors or mentors who know you well and can vouch for your abilities and potential.
## Engage in Research:

* Participate in research projects and seek opportunities to gain research experience, as it adds value to your application.
