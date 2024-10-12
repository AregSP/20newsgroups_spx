# 20 Newsgroups

This project focuses on text classification using the well-known 20 Newsgroups dataset.

# Model Description
An ensemble model was trained to achieve high accuracy in predicting the topic of a document within the 20 Newsgroups dataset.

# Goal
The goal is to efficiently classify documents into their respective topics using advanced machine learning techniques.

# Models Used
Multinomial Naive Bayes, Logistic Regression and SVM trained with Stochastic Gradient Descent (scikit-learn's MultinomialNB, SGDClassifier with hinge loss and SGDClassifier with log_loss respectively).

# Results
The ensemble model of these 3 achieved an impressive 92% F1 score in predicting the topics of documents, demonstrating its effectiveness in text classification tasks.

### Citation

If you use the 20 Newsgroups dataset in your work, please cite it as follows:

> Lang, Ken. "Newsweeder: Learning to filter netnews." Machine Learning Proceedings 1995. Morgan Kaufmann, 1995. 331-339.
