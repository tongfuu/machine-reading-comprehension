# Machine Reading Comprehension on SQUAD 2.0

**More info in the report!**
- introduction
- background
- methods 
- results (sliding window, logistic regression, DistilBERT, RoBERTa, SqueezeBERT)
- error analysis
- conclusion & discussion

## Summary
In this project, we aim to build a model for question answering. We trained the model on Stanford Question Answering Dataset 2.0 (SQuAD 2.0). We have experimented on different models including Sliding Window, Logistic Regression, DistilBERT, RoBERTa, and SqueezeBERT for question-answering tasks. We use the F1 score and exact match as two metrics to evaluate the model. The published baseline Logistic Regression has 0.36 F1 and 0.46 EM on the test set, and the best model SqueezeBERT has 0.67 F1 and 0.71 EM on the test set.
