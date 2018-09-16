### Area Under a Curve (AUC) 

#### NOTES 1
##### During evaluation, Amazon ML computed an industry-standard quality metric, called the Area Under a Curve (AUC) metric, that expresses the performance quality of your ML model. Amazon ML also interprets the AUC metric to tell you if the quality of the ML model is adequate for most machine learning applications.
#### https://docs.aws.amazon.com/machine-learning/latest/dg/step-4-review-model-and-set-cutoff.html

#### NOTES 2
#### Measuring ML Model Accuracy
##### https://docs.aws.amazon.com/machine-learning/latest/dg/binary-model-insights.html#measuring-ml-model-accuracy
#### EXCERPTS (as accessed September 15, 2018)

```Amazon ML provides an industry-standard accuracy metric for binary classification models called Area Under the (Receiver Operating Characteristic) Curve (AUC). AUC measures the ability of the model to predict a higher score for positive examples as compared to negative examples. Because it is independent of the score cut-off, you can get a sense of the prediction accuracy of your model from the AUC metric without picking a threshold.```

```The AUC metric returns a decimal value from 0 to 1. AUC values near 1 indicate an ML model that is highly accurate. Values near 0.5 indicate an ML model that is no better than guessing at random. Values near 0 are unusual to see, and typically indicate a problem with the data. Essentially, an AUC near 0 says that the ML model has learned the correct patterns, but is using them to make predictions that are flipped from reality ('0's are predicted as '1's and vice versa).```


