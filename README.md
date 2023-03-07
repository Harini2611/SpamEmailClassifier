# SpamEmailClassifier
The goal of this project is to build a spam email classifier using machine learning. The classifier is trained on a dataset of emails labeled as spam or not spam (ham), and then it can predict whether a new email is spam or not.

It reads a CSV file containing email messages and their labels, preprocesses the text data by removing punctuation, converting to lowercase, and removing stop words using NLTK's stopwords corpus.

 It vectorizes the text data using the TfidfVectorizer, converts the labels to binary values, and splits the data into training and testing sets using stratified k-fold cross-validation. It then tunes the hyperparameters and fits the Multinomial Naive Bayes model using GridSearchCV. 

Finally, it tests the model and evaluates its performance using multiple metrics including accuracy, precision, recall, f1 score, and AUC ROC score. This script can be used for email filtering to identify spam messages with high accuracy.
