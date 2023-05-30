# Credit-Score_Classifier

This is an ML project that classifies credit scores to "Good", "Bad", "Poor". The first phase is mining the dataframes from kaggle and data exploration to check usability of features. 
The second phase is preprocessing, followed by declaring models to use. SVM was heavy on RAM and needy on time to run hence not worth the expense.
Random Forest ended up being the best model and was what was used as the final model. See "classifier_report_func()" as the function used recursively across all listed models.

The test data was inadequate in the sense that it missed important columns making it unworkable in testing but the models performed well in the train test split. 
