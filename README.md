# Toxic Comment Classification

This project classifies toxic comments using deep learning and Python. The dataset leveraged is originally from [Kaggle](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/), which provided a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. 
The types of toxicity are:

- `toxic`
- `severe_toxic`
- `obscene`
- `threat`
- `insult`
- `identity_hate`

A model which predicts the probability of each type of toxicity for each comment is created.

## File Descriptions
- `train.csv` - the training set, contains comments with their binary labels
- `test.csv` - the test set, the goal is to predict the toxicity probabilities for these comments
