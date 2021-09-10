# Customer-churn-analysis

In this repository, I used Python to analyze telcom customer churn.

On jupyter notebook, I went through the telcom data. My focus was to process the data for modelling, and try different algorithms to evaluate their performance.

First I analized the features, to try to understand them, and have some insights.

Second, I started to prepare the data for the modelling.

Applied a one-hot-encoding over the cathegorical features.
Splitted the data into the train and test sets
Standardazing the features on each set.

With the complete train data.
I used PCA to also use important features in the dataset.
For each part I test the same models and algorithms:

Logistic Regression (Scikit-Learn)
Multi-Layer Perceptron (Scikit-Learn)
Gradient Boosting (Scikit-Learn)
Extreme Gradient Boosting (XGBoost)
Light Gradient Boosting Machine (LightGBM)
Support Vector Machines (SVM)
Initially, I tested the models performance on the validation set.

By looking at the score metrics and speed performance, the model I would chose is the Gradient Boosting Classifier from the LightGBM package. But the XGBoost is close behind.

However, I still believe I can improve the accuracy by applying feature engineering on the data, as well trying other models, even doing an ensemble model over all the tested models.
