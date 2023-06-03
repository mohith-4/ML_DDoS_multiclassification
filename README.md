# ML_DDoS_multiclassification

HI.

In this Repo , you can find the two datasets 1.Dataset that is not preprocessed(Random_combine_final.csv) 2.Preprocessed dataset(cleaned_KnnImputerdata.csv)

If you want to use your own preproseccing techniques, you can download the first dataset and proceed.

Second dataset is preprocessed. I used the KNN Imputer to fill the missing or NaN values.

The python code includes :
1. Oversampling using SMOTE
2. Feature Selection using Random Forest Classifier, we can find the best features from this.
3. Different Classifiers are used to compare the performance__

      'RandomForest' , 'Logistic Regression','Multinomial Naive Bayes','Support Vector Classifer'.'Decision Tree Classifier','K Nearest Neighbour','Gaussian Naive   Bayes', 'XGBClassifier' , 'VotingClassifier' (we can use different combinations of classifiers here).

