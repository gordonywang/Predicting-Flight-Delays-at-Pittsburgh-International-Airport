# Predicting-Flight-Delays-at-Pittsburgh-International-Airport
Final Project | 36-462: Data Mining | Fall 2018

•	Forecasted as team of 3 flight delays in 2017 with classification predictive modeling, utilizing Bureau of Transportation Statistics flight data and NOAA weather data from 2015-2016.

•	Implemented one of two machine learning algorithms total required for project by building, training, and validating gradient boosting decision tree (GBDT) ensemble models in R with XGBoost.

•	Achieved 9% increase in performance on hold-out test set as evaluated by area under the ROC curve (AUC) through tuning 6 model hyper-parameters in R via stratified k-fold cross-validation and caret package's random search.



Project instructions are in pdf file: (final_project_description2018.pdf)

My code for XGBoost implementation can be found above conveniently in knitted PDF: (xgboost_tuning.pdf).
For runnable code, download (xgboost_tuning.rmd) (WARNING takes 15-20 minutes to run completely!) 

R environment file with data needed to run the XGBoost code is available above as (temp_env.Rdata)

Explanation of tuning methodology can be found above as XGBoost Tuning Methodology.docx.

The final report is PDF file: (Predicting Flight Delays At Pittsburgh International Airport Write-up.pdf) 
