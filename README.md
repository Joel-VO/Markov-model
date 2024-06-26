# Markov-model

The poem files used were the ones provided by Lazy programmer Inc in his udemy course on NLP

A simple project of making a Markov model Classifier, during my studies in NLP. This was done as a project that was a part of a udemy course by Lazy programmer Inc.

## Usage

Download the txt files as well and then copy their path to paste in the program

Make sure that the file path is set correctly in the apporpriate list

## Model Performance


- **The average recall is 100.00%.**

- **The average f1 score is 79.80%.**

- **The average precision is 66.42%.**


### Conclusion

The recall value of 100% indicates the model is very capable at capturing true positives,
however the lower value of precision indicates 33.58% of all positives are falsely matched.

The model clearly needs improvement specifically in terms of reducing false positives, which can potentially be 
rectified by improving the training data as the false positives might be arising due to ambiguous text where both 
authors are equally likely.


This was just a learning experience, and the model, as is evident, did'nt fare too well in terms of precision compared to most modern algorithms for classifying text.
