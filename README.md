# Anemia Prediction

Anemia is a blood disorder in which the blood has a reduced ability to carry oxygen due to a lower than normal number of red blood cells, or a reduction in the amount of hemoglobin [^1].

The purpose of this study is to predict if a patient suffers from anemia or not based on some blood attributes provided in the sample [dataset](https://github.com/muscak/anemia-prediction/tree/master/Data).

Followed basic steps such as:
1. Summarize Data
2. Prepare Data
3. Evaluate Algorithms
4. Improve Accuracy

The below linear and non-linear algorithms are evaluated using 10 fold corss validation in this study:
- Logistic Regression (LR)
- Linear Discriminant Analysis (LDA)
- $k$-Neighbors Classifier (KNN)
- Decision Tree Classifier (CART)
- Gaussian Naive Bayes (NB)
- Support Vector Classifier (SVM)

CART provided the best mean training score with the least standard deviation. The same algorithm provided **100%** accuracy score on test dataset with the default hyper parameters. 

- [ ] Deneme
- [x] Deneme







[^1]: [Anemia](https://en.wikipedia.org/wiki/Anemia)
