# machine_learning_BCI

This repository include the code use in the Machine Learning project of BCI seminar.
Autors: Guy Klein, Omer Noy & Noam Loya

The code includes the following:
- learn_with_sklearn.py: the main learning pipeline, using the sklearn package. It includes multiple learning algorithmss, and outputs statistics and graphs on the results.
- Estimator.py: Learning pipeline with TensorFlow. Currently includes Logistic Regression, and will easily allow future experiments with Deep Neural Networks.
- DataSet.py: Util class for handling the data. When changing the relevant excel columns, a variablel must be changed there.

To use the code, create an excel files with column names corresponding to the names you add in DataSet list, change the data_path variable into the excel path and simply run.
