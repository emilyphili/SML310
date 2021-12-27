# Predicting Short-Term Mortgage Delinquencies in New York: A Machine Learning Approach

This project examines the potential of five machine learning models to predict residential mortgage delinquencies between 2008 and 2019, and which factors are most important for making such predictions. The data, provided by CoreLogic Inc., tracks the performance of 13,193 unique mortgages tied to properties in the state of NY. The models tested include Logistic Regression, Naive Bayes, Decision Tree, Random Forest, and Multilayer Perceptron. Various metrics, including accuracy score and true negative rate (TNR), are considered for evaluating model performance. Decision Tree with entropy split criterion and maximum tree depth of ten is found to be the superior model in terms of TNR and training time.

Data_Prep.ipynb is for extraction of CoreLogic's proprietary data. Need access to CoreLogic database.

*12/26 EDIT: Please see Data_Prep_Updated.ipynb instead, which should have faster execution time. Note that the datasets used in Main.ipynb have not been uploaded to this GitHub page because data is proprietary.*

Main.ipynb (Main_Updated.ipynb) is for data pre-processing and preparation, EDA, and running the ML models.
