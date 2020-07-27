# Graduate Admission Probabilities

In this dataset, the relevant columns are:
* GRE Scores ( out of 340 )
* TOEFL Scores ( out of 120 )
* University Rating ( out of 5 )
* Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
* Undergraduate GPA ( out of 10 )
* Research Experience ( either 0 or 1 )
* Chance of Admit ( ranging from 0 to 1 )

Project Overview:
* EDA comparing the numerical columns to the university ranking
* Data model that predicts the graduate admission probability with MAE ~4%
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
* This dataset only provides the chance of admission for one university, but I think it would be beneficial for any candidate to know their chances at universities of each rank.

Data Credit: Mohan S Acharya, Asfia Armaan, Aneeta S Antony : A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019
