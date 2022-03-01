# Twitter_offensive_language_dataset_classification

Here, I have classified the offensive tweets from the famous olid twitter dataset (https://sites.google.com/site/offensevalsharedtask/olid) using the following top machine learning (ML) algorithms. I used some of the ML models here for my course project as well.
1. Logistic Regression
2. Ridge Regression
3. Support Vector Machine (SVM)
4. K Nearest Neighbors (K-NN)
5. Decision Tree
6. Random Forest

About the data:\
We are provided with the training and test datasets as below:
Training: "olid-training-v1.0.tsv" is the original dataset which contains the tweets and their labels for each subtask. We will be using subtask_a and other columns are discarded here.
Testing: "testset-levela.tsv" is the test set we will be using for testing our model. This dataset contains the tweets to test the model trained on subtask_a. This dataset doesn’t contain the labels for the tweets and is provided in a different file names "labels-levela.csv".


Upon the evaluation, among all the ML models, it was found that SVM and Logistic Regression classify the tweet datasets with higher accuracies of 81% and 80%, respectively.
