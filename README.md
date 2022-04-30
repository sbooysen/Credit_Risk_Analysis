
## Credit Analysis Overview
### By: Stacey Booysen

In this analysis we were tasked with creating a machine learning model that would help to identify potential credit card risks. Since credit risk is an unbalanced classification, we worked to organize and sort the data in a way that was as accurate as possible. 

We used several different models to get varied results. With these examples, we should be able to figure out the best method to use for this data. Looking at the scores, such as the recall and precision factors as well as the accuracy scores, the model we need should become clear. All of the following methods were used in order to analyze our data:

* Oversampling
  * Comparison

Naïve Random Sampling shows -

Balance accuracy score of: 65%

Precision score of: 1% high-risk, 100% low-risk, and 99% average/total

Recall score of: 63% high-risk, 66% low-risk, and 66% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Naive%20Random%20Oversampling.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Naive%20Random%20Oversampling%20-%20Accuracy.png)

The SMOTE Model shows -

Balance accuracy score of: 62%

Precision score of: 1% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 62% high-risk, 63% low-risk, and 63% average/total. 

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/SMOTE%20Oversampling.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/SMOTE%20Oversampling%20-%20Accuracy.png)


* Undersampling
  * Comparison

Undersampling Model shows -

Balance accuracy score of: 62%

Precision score of: 1% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 62% high-risk, 63% low-risk, and 63% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Undersampling.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Undersampling%20-%20Accuracy.png)


* Ensemble 
  * Comparison

Easy Ensemble AdaBoost Classifier shows -

Balance accuracy score of: 93%

Precision score of: 7% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 91% high-risk, 94% low-risk, and 94% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Easy%20Ensemble%20AdaBoost%20Classifier%20-%20Accuracy.png)


Balanced Random Forest Classifier shows -

Balance accuracy score of: 79%

Precision score of: 4% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 67% high-risk, 91% low-risk, and 91% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Balanced%20Random%20Forest%20Classifier.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Balanced%20Random%20Forest%20Classifier%20-%20Accuracy.png)


* Combinations/SMOTEENN
  * Comparison 

Cluster Centroids Model shows -

Balance accuracy score of: 53%	

Precision score of: 1% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 61% high-risk, 45% low-risk, and 45% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Cluster%20Centroids.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/Cluster%20Centroids%20-Accuracy.png)



SMOTEENN Model shows -

Balance accuracy score of: 62%

Precision score of: 1% high-risk, 100% low-risk, and 99% average/total.

Recall score of: 70% high-risk, 54% low-risk, and 54% average/total.

![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/SMOTEENN.png)
![alt text](https://github.com/sbooysen/Credit_Risk_Analysis/blob/main/Credit_Risk_Analysis/Resources/SMOTEENN%20-%20Accuracy.png)


___


The Easy Ensemble AdaBoost Classifier Method seems to have the highest balance accuracy score out of all the models used. This model is less prone to overfitting and inspires a lot more confidence than the others in this set. Due to the fact that the Easy Ensemble AdaBoost Classifier had a very high accuracy score, I would suggest using that method in order to calculate further credit risks. 
