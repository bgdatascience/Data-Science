# Predicting Survivors of the Titanic Shipwreck
Keywords: <b>Python, Classification, Pre-Processing, Titanic Shipwreck, Pedicting Survivors</b>

This example is based on a competition on <em>Kaggle.com/c/titanic"</em>. The task is to use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

The data consists of a train and test dataset that are provided from the start. The train dataset has information on whether or not a passenger survived the Titanic shipwreck. The test data does not have this information and thus needs to be predicted. The data will be <em>pre-processed, information will be won from string variables and transformed into numeric form, missing values will be imputed via iterative imputing, variables will be categorized and standardized</em>. 13 classifiers will be applied to solve the problem whereas the best performing classifier will be used to predict the number of survivors for the test dataset.

The submitted result from this example classified <b>78%</b> of the survivors in the test dataset correctly.

The dataset is publicly available on Kaggle under the given link above.

The environment used for this example is <b>Jupyter Notebook</b>

The packages used in this example are: <b>pandas, pandas_profiling, numpy, scipy, fancyimpute, statsmodels, sklearn</b> and <b>matplotlib</b>
