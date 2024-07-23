# Credit Risk Analysis
This project demonstrates various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
We noticed good precision and call values for both healthy and high risk loans. The model was highly able to predict correctly.
<br>
## Overall Performance:
<br>
Accuracy: 0.99
This means that 99% of the total predictions are correct.
Macro Avg (F1-Score): 0.94
This is the average of the F1-scores for both classes, giving equal weight to each class.
Weighted Avg (F1-Score): 0.99
This is the average of the F1-scores for both classes, weighted by the number of instances in each class.
<br>
## Interpretation:
<br>
The model performs very well in predicting healthy loans (0), with very high precision, recall, and F1-score.
For high-risk loans (1), the performance is good but not perfect. The precision and recall are slightly lower, indicating some room for improvement in reducing false positives and false negatives.
The high overall accuracy and weighted average F1-score suggest that the model is highly effective, especially given the imbalanced nature of the dataset (with many more healthy loans than high-risk loans).
