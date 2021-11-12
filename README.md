# Human-Activity-Recognization
This project is to build a model that predicts the human activities such as Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing or Laying given some time series data.

-  Here we have 2 types of features- one is the raw times data and other is the expert generated features(ie, people with domain knowledge of signal processing engineered useful features for us)
-  Some basic preprocessing and EDA to know if the expert generated features are useful or not and applied T-sne to visualize all the features in combination.
-  Applied classical ML models like logistic regression, linear SVC, kernel SVM, Decision tree, Random forest, GBDT on expert engineered features.
-  Built a simple LSTM based DL model on the raw time series features.
