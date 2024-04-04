# EasyVisa
Analyze the data of Visa applicants, build a predictive model to facilitate the process of visa approvals, and based on important factors that significantly influence the Visa status recommend a suitable profile for the applicants for whom the visa should be certified or denied.

Visa classification using Ensemble techniques and EDA to identify the profile of successful applicant

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
