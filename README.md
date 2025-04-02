# Rainfall-prediction-ML
Goal: is to predict rainfall for each day of the year.
Binary Prediction with a Rainfall Dataset
# ✅ Result of competition: top 320 OUT OF 4380
MY BEST SCORE: 0.89982
BEST SCORE IN COMPETITION: 0.90654

# Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Rainfall Prediction using Machine Learning dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.
Files
train.csv - the training dataset; rainfall is the binary target
test.csv - the test dataset; your objective is to predict the probability of rainfall for each row
sample_submission.csv - a sample submission file in the correct format.

# Participation
8,849 Entrants
4,404 Participants

# Evaluation
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

Submission File
For each id in the test set, you must predict a probability for the target rainfall. The file should contain a header and have the following format:
