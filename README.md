# Overview
1. A machine learning system which can identify the nature and category of the complaint posted by the user.
2. This system is needed by a non-profit organization to improve their existing system where they were manually categorizing the complaints posted by the user. 

# Methodology
1. First I applied feature engineering. Feature engineering is the process of extracting features from raw data via data mining techniques. 
2. These features can be used to improve the performance of machine learning algorithms.
3. Using graphs, studied the data which turned out to an imbalanced data, To have imbalanced data in our case is of our great interest since it is desirable to have a classifier that gives high prediction accuracy over the majority class while maintaining reasonable accuracy for the minority classes.
4. Used different machine learning models and evaluated their accuracy and then chose the model with the highest accuracy:-
   - LinearSVC 0.947462 
   - LogisticRegression 0.947942 
   - MultinomialNB 0.936428 
   - RandomForestClassifier 0.788532


