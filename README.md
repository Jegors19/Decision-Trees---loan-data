# Decision-Trees---loan-data
max depth, n estimators, performance, interpretability



The project involved analyzing loan data using machine learning techniques. 
The data was loaded from a CSV file and encoded to handle categorical values. 
The dataset was split into training, validation, and test sets.

A benchmark model was created using a DummyClassifier with the strategy of predicting the most frequent class label. 
The benchmark accuracy score was calculated, and it was found to be 76.07%.

A decision tree classifier was trained with varying maximum depths to determine the best performance. 
The accuracy scores on the training, validation, and test sets were recorded for each depth. 
A plot was generated to visualize the accuracy versus the maximum depth. 
The results showed that a maximum depth of 3 achieved the highest accuracy on the validation set, around 86%.

A random forest classifier was trained with different numbers of estimators to compare performance. 
The accuracy scores on the training and validation sets, as well as the training time, were recorded for each number of estimators. 
A plot was created to show the accuracy and training time versus the number of estimators. 
The results indicated that the performance peaked around 85% accuracy with approximately 20 estimators.

A comparison was made between the benchmark model, decision tree model with a maximum depth of 3, and random forest model with a maximum depth of 20+. 
The benchmark accuracy score was 76.07%, the decision tree accuracy score was 85.97%, and the random forest accuracy score was 84.48%.

Based on the analysis, it was concluded that the decision tree model with a maximum depth of 3 was the most suitable choice. 
The decision tree model outperformed the benchmark model, had better computational performance, and was easier to interpret. 
The decision tree model took around 2 milliseconds for training, while the random forest model with 20+ estimators took approximately 20 milliseconds. Additionally, a visualization of the decision tree was provided to enhance interpretability.
