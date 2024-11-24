the study aimed at predicting driver behavior using smartphone motion sensors and machine learning methods has yielded valuable insights. The dataset was preprocessed by extracting relevant features, and two powerful classification algorithms, Support Vector Machine (SVM) and Random Forest, were employed for predictive modeling.
The evaluation process involved thorough testing of both SVM and Random Forest models. With a polynomial kernel of degree 4, SVM exhibited promising results in identifying patterns in driver behavior. However, as the dataset underwent feature reduction through iterative column dropping, the SVM's performance fluctuated, suggesting sensitivity to feature selection.
On the other hand, Random Forest consistently demonstrated robust performance across various feature subsets. Its ability to handle a diverse range of features and capture complex relationships within the data contributed to its superiority in predicting normal, slow, and aggressive driving patterns. The ensemble nature of Random Forest, combining multiple decision trees, provided resilience against overfitting and improved generalization.
Results obtained from this approach showed that RF had the highest performance when compared to SVM. This superiority of the RF model can be attributed to the fact that the RF model can handle large datasets efficiently. It's based on the bagging algorithm and uses the Ensemble Learning technique 