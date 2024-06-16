# Email/SMS Spam Classifier

## Introduction

This project is a spam classifier that uses the Naive Bayes algorithm to classify emails and SMS messages as spam or not spam. The dataset used for this project is the [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) from Kaggle. The dataset contains 5,572 SMS messages that are labeled as spam or not spam. The dataset is split into two columns: `label` and `message`. The `label` column contains the label of the SMS message, which is either `spam` or `ham` (not spam). The `message` column contains the text of the SMS message.

## Naive Bayes Algorithm

The Naive Bayes algorithm is a probabilistic classifier that is based on Bayes' theorem. It is called "naive" because it makes the assumption that the features are conditionally independent given the class label. Despite this simplifying assumption, Naive Bayes has been shown to be effective in practice for a wide range of classification tasks.

## Implementation

The implementation of the spam classifier is done using Python and the scikit-learn library. The scikit-learn library provides a Naive Bayes classifier that can be used to train a model on the SMS dataset. The model is trained on the `message` column of the dataset and the `label` column is used as the target variable. Once the model is trained, it can be used to predict whether a new SMS message is spam or not spam.

## Conclusion

The spam classifier is a simple yet effective way to classify SMS messages as spam or not spam. The Naive Bayes algorithm is well-suited for this task and can achieve high accuracy on the SMS Spam Collection Dataset. The classifier can be used to filter out unwanted spam messages and improve the user experience of SMS applications.

## References

1. [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
2. [scikit-learn Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)
3. [Naive Bayes Classifier](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)
4. [Bayes' Theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem)
5. [Python Programming Language](https://www.python.org/)
6. [scikit-learn Library](https://scikit-learn.org/)
7. [Kaggle](https://www.kaggle.com/)

## Author

- [Deva Vinoth](https://deva-vinoth.web.app/)
- [LinkedIn](https://www.linkedin.com/in/devavinoth/)
- [GitHub](https://github.com/devavinothm)
- [Instagram](https://www.instagram.com/devavinoth_/)

## Thanks for Reading! 🙏 Have a great day!