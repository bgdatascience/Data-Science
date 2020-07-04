# Test of 13 Classifiers for Income Prediction on "Adult" Dataset (Income > 50.000 Dollars)
Keywords: <b>Python, Classification, Pre-Processing, Predicting Income via Demographics</b>

This example tackles a classification problem where 13 classifiers are used to predict whether or not an individual is likely to have a yearly household income of more than 50.000 dollars. The dataset contains cross-sectional data for indviduals. The data will be <em>pre-processed</em>, an initial logistic regression will be applied for <em>feature selection</em> and to interpret the importance of each regressor for the dependent variable "income". After that, <em>classifiers will be fit</em> to training data and <em>tested</em> on a test dataset. The <em>classifiers will be compared</em> regarding their accuracy on both train and test data and <em>income predictions</em> will be made with the best classifier for 3 fictional persons with different demographic backgrounds. The process is described in detail in the notebook.

The dataset is public and available in this repository.

The environment used for this example is <b>Jupyter Notebook</b>

The packages used in this example are: <b>pandas, numpy, statmodels, sklearn</b> and <b>matplotlib</b>
