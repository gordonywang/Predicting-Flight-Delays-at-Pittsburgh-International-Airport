# Predicting-Flight-Delays-at-Pittsburgh-International-Airport
Final Project | 36-462: Data Mining | Fall 2018

•	Forecasted as team of 3 delays for 1500+ flights in 2017 with classification predictive modeling, using raw, imbalanced Bureau of Transportation Statistics/NOAA data from 2015-2016.

•	Implemented 1 of 2 machine learning algorithms for project by building and validating gradient boosting decision tree (GBDT) ensemble models in R with XGBoost after data preprocessing.

•	Achieved 9.09% increase in performance on test set as evaluated by area under ROC curve (AUC) metric through tuning 6 hyper-parameters with k-fold cross-validation and random search via R’s caret package.



Project instructions are in pdf file: (final_project_description2018.pdf)

My code for XGBoost implementation can be found above conveniently in knitted PDF: (xgboost_tuning.pdf).
For runnable code, download (xgboost_tuning.rmd) (WARNING takes 15-20 minutes to run completely!) 

R environment file with data needed to run the XGBoost code is available above as (temp_env.Rdata)

Explanation of tuning methodology can be found above as XGBoost Tuning Methodology.docx.

The final report is PDF file: (Predicting Flight Delays At Pittsburgh International Airport Write-up.pdf) 
