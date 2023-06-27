# Bernoulli Naive Bayes Implementation from Scratch with Mutual Information, Word Filtering, and Lambda Optimization for Spam Filter
## Introduction
This repository contains an advanced implementation of the Bernoulli Naive Bayes algorithm with mutual information, word filtering, and lambda optimization for building a spam filter. The Bernoulli Naive Bayes algorithm is a simple yet effective probabilistic classifier commonly used for text classification tasks such as spam detection. By incorporating mutual information feature selection, word filtering techniques, and lambda optimization, this implementation maximizes precision and improves the overall performance of the spam filter.
## Features
The advanced Bernoulli Naive Bayes implementation offers the following features:

1. **Scratch Implementation:** The algorithm is implemented from scratch using basic data structures and probability calculations. This allows you to understand the inner workings of the Bernoulli Naive Bayes algorithm, mutual information feature selection, word filtering techniques, and lambda optimization without relying on external libraries or pre-built implementations.

2. **Feature Extraction and Selection:** The code includes methods for feature extraction from text data, specifically designed for spam filtering. It transforms raw email text into a feature vector representation based on the presence or absence of certain words or patterns. The implementation utilizes mutual information to select the most informative features, reducing the feature space and improving training time.

3. **Word Filtering:** The implementation applies word filtering techniques to remove frequent and infrequent words that may introduce noise into the classification process. By eliminating common words and rare words that are less likely to contribute to spam detection, the algorithm focuses on the most relevant features, enhancing classification performance.

4. **Lambda Optimization:** The implementation includes lambda optimization, where different lambda values for the lambda function are tested to maximize precision. By fine-tuning the lambda value, the algorithm aims to achieve higher precision in spam classification, minimizing false positives.

5. **Model Training:** The implementation provides functions to train the Bernoulli Naive Bayes model using labeled training data. During training, the algorithm estimates the conditional probabilities of features given the class (spam or non-spam) using maximum likelihood estimation.

6. **Model Evaluation:** The code includes evaluation metrics such as accuracy, precision, and recall to assess the performance of the trained model on test data. This allows you to measure the effectiveness of the spam filter and fine-tune its parameters if needed.

7. **Spam Classification:** Once trained, the model can be used to classify new email messages as spam or non-spam. By computing the posterior probabilities using Bayes' theorem, the algorithm predicts the most likely class for a given email.
