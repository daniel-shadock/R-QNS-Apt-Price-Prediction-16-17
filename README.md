# R Queens Apartment Sales Price Prediction Models 2016-2017
This project applies machine learning and statistical modeling to predict housing sale prices in Mainland Queens, New York, using real-world property data from 2016–2017. It includes full data cleaning, feature engineering, model training, evaluation, and performance comparison across linear and non-linear methods.
Project Highlights
	•	Real Dataset: NYC residential sales data (cleaned and preprocessed)
	•	Target Variable: Final sale price
	•	Models Implemented:
	•	Ordinary Least Squares (OLS)
	•	Regression Tree (via rpart)
	•	Random Forest (via ranger)
	•	Evaluation Metrics:
	•	RMSE (Root Mean Squared Error)
	•	R² (Coefficient of Determination)
	•	Performance evaluated on training and test sets
	•	Cross-validation and hyperparameter tuning using tidymodels

⸻

Tools & Technologies
	•	R Language
	•	tidymodels (cross-validation, modeling pipeline)
	•	dplyr, ggplot2, skimr (data wrangling & visualization)
	•	missForest (missing data imputation)
	•	rpart / ranger (modeling engines)
	•	gt (reporting & table formatting)

⸻

Model Performance Summary

| Model           |   RMSE_Train |   R2_Train |   RMSE_Test |   R2_Test |
|:----------------|-------------:|-----------:|------------:|----------:|
| OLS             |      28616.1 |   0.974198 |     41145.3 |  0.950827 |
| Regression Tree |      23031.6 |   0.983206 |     36854.1 |  0.960549 |
| Random Forest   |      11713.5 |   0.995656 |     35559.2 |  0.963273 |

