# EasyVisa
Visa classification using ML and EDA to identify the profile of successful applicant

ML Algorithims used:
- Decision Trees
- Random Forest
- Bagging Classifer
- Ada Boost
- Gradient Boost
- XGBoost

**Results:**
- We achieved top F1-scores of 0.8209 on the test data. Almost all the models performed similarly, but the top three models were XGboost tuned, RF tuned, and Stacking classifiers.
- 
- Top three features are
- 1) education_of_employee
  2) prevaling wage,
  3) has_job_experience,
  Other variables of importance are continent_Europe and hourly_wage.

**Final selected model**
Random Forest Tuned
