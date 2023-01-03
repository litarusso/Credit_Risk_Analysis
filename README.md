# Credit_Risk_Analysis
## Purpose of The Analysis
We applied two machine learning analyses to evaluate the credit card list. First, we used a credit card dataset; data needed to be more balanced and undersampled. Next, we compared two oversampling algorithms and under-sampling algorithms. Then we compared them to determine which algorithm results in the best performance.

## Results

The related scores of the six machine learning models are below:

### Naive Random Oversampling Scores:
  - Balanced accuracy score:0.655,
  - Precision: 0.99
  - Recall: 0.61
  - F1: 0.75
  
![Screen Shot 2023-01-02 at 5 23 02 PM](https://user-images.githubusercontent.com/111788394/210281756-2055fed8-b14d-4921-9d9c-7e52421c25e1.png)- 

### Smooth Oversampling Scores:
  - Balanced accuracy score: 0.662,
  - Precision: 0.99
  - Recall: 0.69
  - F1: 0.81
 
![Screen Shot 2023-01-02 at 5 27 29 PM](https://user-images.githubusercontent.com/111788394/210281979-07f61edf-f000-47b1-b6e3-551700b1d39c.png)

### Undersampling Scores:
  - Balanced accuracy score: 0.544,
  - Precision: 0.99
  - Recall: 0.40
  - F1: 0.56
 
![Screen Shot 2023-01-02 at 5 31 05 PM](https://user-images.githubusercontent.com/111788394/210282119-6b3c2146-f05b-4c9f-ac9f-1703de982549.png)

### Combination (Over and Under) Sampling Scores:
  - Balanced accuracy score: 0.644,
  - Precision: 0.99
  - Recall: 0.57
  - F1: 0.72

![Screen Shot 2023-01-02 at 5 35 04 PM](https://user-images.githubusercontent.com/111788394/210282303-8b4e9f7b-3b4d-4a7c-94eb-c1258e143c87.png)

### Balanced Random Forest Classifier Scores:
  - Balanced accuracy score: 0.788,
  - Precision: 0.99
  - Recall: 0.87
  - F1: 0.93

![Screen Shot 2023-01-02 at 5 37 22 PM](https://user-images.githubusercontent.com/111788394/210282427-112d68b1-25af-4ffc-9594-7947fada515c.png)

### Easy Ensemble AdaBoost Classifier Scores:
  - Balanced accuracy score: 0.931,
  - Precision: 0.99
  - Recall: 0.94
  - F1: 0.97

![Screen Shot 2023-01-02 at 5 39 38 PM](https://user-images.githubusercontent.com/111788394/210282532-7fa3cfba-c9a3-43f4-9535-a6cf27e4c3f5.png)

## Summary

We compared Naive Random Oversampling and Smote Oversampling scores, and we found that the balanced accuracy score of the Naive Random Oversampling method is higher than the other. This shows that the first logistic regression model was better regarding balanced accuracy. On the other hand, in Smote Oversampling method, we have found a higher recall score. This means a higher percentage of the correct positive predictions relative to the actual positives was obtained. Then when we compared the F1 score to Smote Oversampling score, the Smote Oversampling score was closer to 1.

When we compared the undersampling algorithm to Naive Random Oversampling and Smote Oversampling, we found that balanced accuracy, recall and F1 scores are lower than both oversampling methods. Furthermore, we have also compared Combination methods with oversampling methods; we find that the Combination method gives a lower score. Therefore, the Naive Random Oversampling method is the most effective among the methods we have compared. 

When we compare two ensemble algorithms (Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier), the latter one has a higher value of balanced accuracy score (0.931), a higher recall score (0.94) and an F1 score (0.97) which is closer to 1. Therefore, this method has better performance. 
