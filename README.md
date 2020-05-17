# Cat_in_the_Dat_2
## Categorical Feature Encoding Challenge II
Binary classification, with every feature a categorical (and interactions!)

### ***Content***

![Categories](https://2.bp.blogspot.com/-gNMIOHboLMo/T1Dlp5pi3uI/AAAAAAAAAVc/80O8Ao9rrfQ/s1600/Categories+Excel.jpg)

In this [competition](https://www.kaggle.com/c/cat-in-the-dat-ii), we will be predicting the probability [0, 1] of a binary target column.

The data contains:
- binary features (bin_*),
- nominal features (nom_*),
- ordinal features (ord_*),
- potentially cyclical - day (of the week) and month features.

The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.

Since the purpose of this competition is to explore various encoding strategies, the data for this challenge has missing values and feature interactions.

### ***Files***
- *train.csv* - the training set,
- *test.csv* - the test set; you must make predictions against this data,
- *sample_submission.csv* - a sample submission file in the correct format.

### ***Evaluation***
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.
