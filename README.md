##  Spam Email Filter using Naive Bayes Theorem

### Introduction
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research which contains one set of SMS messages in English of 5,574 messages, tagged according being ham (legitimate) or spam.
The files contain one message per line. Each line is composed by two columns: v1 contains the label (ham or spam) and v2 contains the raw text.

### Naive Bayes Theorem
The Naive Bayes theorem is used to implement a classifier that is based on the Bayes theorem of conditional probability. In comparison with the other algorithms, computation is relatively more simple, easier to implement and less training data is required. 
It is an application of supervised learning where the predictions are represented in the outcome class. This outcome is  based on conditional probabilities which are dependent on the frequency of its occurrences in the training data.
The Bayesian theorem is dependent on two probabilities which are called the “Prior Probability” and the “Posterior Probability” respectively. Prior Probability can be defined as the probability distribution of data sampling without considering relevant feature variables whereas the Posterior Probability is defined as the probability distribution of data sampling considering relevant feature variables.

Based on these principles of the Bayesian theorem, the Naive bayes algorithm can be represented as:
```
P(c|x) = P(x|c) * P(c)/p(x) 
```
Where :
P(C) - prior probability of class variable;
P(x)  - prior probability of predictor variable
P(x|c)  - probability of predictor for given class variable
P(clx) - posterior probability of class variable (c, target) for given predictor variable(x, attributes)




