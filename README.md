# Extended-Length-of-Stays-in-Hospital-A-Predictive-Analysis-Using-Machine-Learning-Model-

This project aims to understand and predict the significant factors influencing extended length of stay in hospitals, defined as stays lasting seven days or more. Utilizing machine learning models, including Logistic Regression, Random Forest and Balanced Random Forest, this study attempts to provide meaningful insights for healthcare professionals to optimize patient care.

We sourced our dataset from Microsoft's repository (https://github.com/microsoft/r-server-hospital-length-of-stay/tree/master/Data), which consists of 100,000 records and encompasses 28 distinct features, including both categorical and continuous variables. The continuous attributes, such as hematocrit, neutrophils, and sodium levels, were directly measured, while categorical features like gender and facility id (‘facid’) were transformed into numerical values to facilitate model compatibility. Furthermore, all binary classification flags were encoded as categorical variables.

A holdout validation( train-validation-test) strategy was employed, partitioning the final dataset into an 80% training and 20% testing set. The dataset was divided into three subsets: a training set for model development, a validation set for hyperparameter tuning and model selection, and a test set held aside for the final evaluation of the trained model's performance on new, unseen data.

