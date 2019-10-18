# Predicting-Flight-Delays-at-Pittsburgh-International-Airport
Final Project | 36-462: Data Mining | Fall 2018

•	Forecasted as team of 3 flight departure delays in 2017 at Pittsburgh International Airport with classification predictive modeling, utilizing combination of Bureau of Transportation Statistics commercial flight data and NOAA weather data from 2015-2016. 

•	Built and validated one of two machine learning algorithms required for project by implementing gradient boosting decision tree ensemble models in R with XGBoost. 

• Achieved augmented performance of 0.7027 on hold-out test set as measured by AUC through carefully tuning 6 sensitive parameters via stratified k-fold cross-validation and random grid search with R's caret package.


Project instructions are in pdf file: (final_project_description2018.pdf)

My code for XGBoost implementation can be found above conveniently in knitted PDF: (xgboost_tuning.pdf).
For code that you can run, download (xgboost_tuning.rmd) (WARNING takes 11-15 minutes to run!) 

The R environment file needed to run the XGBoost code is available above as (temp_env.Rdata)

Detailed explanation of tuning methodology will be uploaded soon.

The final report is PDF file: (Predicting Flight Delays At Pittsburgh International Airport Write-up.pdf)
