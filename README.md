Biomechanical Analysis Linear Regression and Visualization
This repository contains tools for the analysis and visualization of biomechanical data. The project focuses on predicting forces and studying delays in peak movement using Linear Regression models.

Repository Content
LR_January_Results_January.ipynb: Main notebook containing Linear Regression model training, evaluation metrics such as R2 and RMSE, and the generation of predictive equations based on condition and slope.

LR_Visualization_per_participant.ipynb: Visualization script that analyzes performance and individual metrics for each participant.

LR_Visualization_per_participant_final.html: Exported interactive report for quick viewing of results without the need to run the code.

Technologies Used
Python 3.x

Pandas and NumPy: Data processing and dataframe management.

Scikit-Learn: Implementation of Linear Regression models.

Matplotlib and Seaborn: Generation of scatter plots and residual analysis.

Analysis Summary
The project segments data by:

Conditions: Different test scenarios.

Slopes: Impact analysis according to inclination.

Error Metrics: Calculation of relative RMSE and coefficients of determination to validate model accuracy in predicting biomechanical peaks.
