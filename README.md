# Data-science-Machine-Learning-using-python-3
The dataset is downloaded from https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)
The required library is uploaded in python.
the file is uploaded from the local directory.
the sample information (first column) is removed before uploading into the python kernel.
The dataset consists of 9 attributes (sample information is removed) and one class (2 means benign and 4 means malignant)
the information of data types and missing value is analysed.
we can see bare nuclei contains a question mark that is removed from the dataset using drop function.
Now the analysis is performed with 683 rows.
A heatmap is generated to study the correlation between attributes and it can be seen the uniformity of cell size and cell shape are highly correlated with 0.91.
Since class is a function in python it cannot be used as an attribute name so it is renamed as outcome and the dataset is split into 70% train and 30% test data.
For classification logistic regression nodel is generated.
the training set has a f1-score of 0.98 and 0.96 for benign and malignant.
the test set has a f1-score of 0.97 and 0.94 respectively.
clump thickness and bare nuclei are important features contributing to classification.
