# Horse_Colic_logistic_regression
Logistic regression is a classic classification method in statistical learning. It belongs to a logarithmic linear model, so it is also called logarithmic probability regression. The model is a classification algorithm, and logistic regression is a linear classifier, targeting linearly separable problems. The main idea of using logistic regression for classification is: the main idea is to use the maximum likelihood probability method to construct an equation. In order to maximize the equation, Newton's gradient ascent is used to solve the equation parameters. The approach when training a logistic classifier is to find the best fitting parameters and use the optimization method.
Experimental task: Use logistic regression to predict the survival of horses with hernia disease (predict the mortality of sick horses from hernia disease)
Source data description: The data contains 368 samples and 28 features. When we use it, we store it as follows
horseColicTraining.txt is used as the training set, containing 300 samples
horseColicTest.txt is used as the test set, containing 68 samples
Original data set download and description:
http://archive.ics.uci.edu/ml/datasets/Horse+Colic
Hernia is a term used to describe gastrointestinal pain in horses. This disease does not necessarily originate from gastrointestinal problems in horses; other problems can cause equine hernia. This data set contains a number of indicators used by hospitals to detect equine hernia disease. Some indicators are subjective and some are difficult to measure, such as the horse's pain level. What we have to do is to train these 300 samples and then test on 68 samples.
In addition to some indicators being subjective and difficult to measure, there is also a problem with this data. 30% of the values ​​in the data set are missing.
First, the missing values in the data set need to be processed.
The processing methods have also been put into the file, and the processing order is:
1.Default data processing.py
2.data replacement.py
3.convert_labels.py
