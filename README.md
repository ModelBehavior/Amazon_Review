# [Amazon Review Data](https://github.com/ModelBehavior/Amazon_Review/blob/main/Amazon_Analysis.Rmd)
### Data Description
The Amazon reviews polarity [Data](https://www.kaggle.com/kritanjalijain/amazon-reviews?select=train.csv) is constructed by taking review score 1 and 2 as negative, 4 and 5 as positive. Samples of score 3 are ignored. In the dataset, class 1 is the negative and class 2 is the positive. the training set has 3.6 million observations and test set has 400,000 observations

### Goals of Analysis
The goal of this analysis is to fit a logistic regression model to classify if a review is negative based on the text of the review.

### Methodology
The data was split into a training and testing set. Term frequency inverse document frequency was used to convert words into weights. 10-fold cross-validation was used to tune the lasso model. The model had a cross validation accuracy above 80%. A presentation of the analysis was made and likned above.

### Results 
Using the model on unseen data, the model achieved an accuracy of 83%, recall of 83%, and precision of 82%.
