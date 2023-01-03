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
  
  <img width="770" alt="Screen Shot 2023-01-03 at 11 35 19 AM" src="https://user-images.githubusercontent.com/111788394/210400161-a419c66d-6254-49e4-b5e6-f9839fa02e65.png">


### Smooth Oversampling Scores:
  - Balanced accuracy score: 0.662,
  - Precision: 0.99
  - Recall: 0.69
  - F1: 0.81
 
<img width="768" alt="Screen Shot 2023-01-03 at 11 36 30 AM" src="https://user-images.githubusercontent.com/111788394/210400390-04493ef2-d2a1-4d49-8b26-b6af9e465432.png">


### Undersampling Scores:
  - Balanced accuracy score: 0.544,
  - Precision: 0.99
  - Recall: 0.40
  - F1: 0.56
 
<img width="752" alt="Screen Shot 2023-01-03 at 11 37 13 AM" src="https://user-images.githubusercontent.com/111788394/210400502-bfa6a078-9ddf-4846-9a55-2c08ebf6b0ae.png">


### Combination (Over and Under) Sampling Scores:
  - Balanced accuracy score: 0.644,
  - Precision: 0.99
  - Recall: 0.57
  - F1: 0.72

<img width="748" alt="Screen Shot 2023-01-03 at 11 37 53 AM" src="https://user-images.githubusercontent.com/111788394/210400714-5e6e34ed-aebf-425e-8f06-64237c9990b0.png">


### Balanced Random Forest Classifier Scores:
  - Balanced accuracy score: 0.788,
  - Precision: 0.99
  - Recall: 0.87
  - F1: 0.93

<img width="755" alt="Screen Shot 2023-01-03 at 11 39 44 AM" src="https://user-images.githubusercontent.com/111788394/210401051-5f6e7553-6410-4cf9-8fb2-2978a746c039.png">


### Easy Ensemble AdaBoost Classifier Scores:
  - Balanced accuracy score: 0.931,
  - Precision: 0.99
  - Recall: 0.94
  - F1: 0.97

<img width="724" alt="Screen Shot 2023-01-03 at 11 40 57 AM" src="https://user-images.githubusercontent.com/111788394/210401156-323e5709-e9ec-4ee8-b20d-55b3af4fee16.png">


## Summary

We compared Naive Random Oversampling and Smote Oversampling scores, and we found that the balanced accuracy score of the Naive Random Oversampling method is higher than the other. This shows that the first logistic regression model was better regarding balanced accuracy. On the other hand, in Smote Oversampling method, we have found a higher recall score. This means a higher percentage of the correct positive predictions relative to the actual positives was obtained. Then when we compared the F1 score to Smote Oversampling score, the Smote Oversampling score was closer to 1.

When we compared the undersampling algorithm to Naive Random Oversampling and Smote Oversampling, we found that balanced accuracy, recall and F1 scores are lower than both oversampling methods. Furthermore, we have also compared Combination methods with oversampling methods; we find that the Combination method gives a lower score. Therefore, the Naive Random Oversampling method is the most effective among the methods we have compared. 

When we compare two ensemble algorithms (Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier), the latter one has a higher value of balanced accuracy score (0.931), a higher recall score (0.94) and an F1 score (0.97) which is closer to 1. Therefore, this method has better performance. 
