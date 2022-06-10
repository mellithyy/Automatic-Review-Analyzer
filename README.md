# Automatic-Review-Analyzer

## **Introduction**

The goal of this project is to design a classifier to use for sentiment analysis of product reviews. Our training set consists of reviews written by Amazon customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

Below are two example entries from our dataset. Each entry consists of the review and its label. The two reviews were written by different customers describing their experience with a sugar-free candy.

| Review                                                                                                      | Label  |
| :---------------------------------------------------------------------------------------------------------- | ------ |
| Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again        | `-1`   |
| YUMMY! You would never guess that they're sugar-free and it's so great that you can eat them pretty much guilt free! i was so impressed that i've ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT!	                                   | `1`    |

## **Setup Details:**

For this project we will be using Python 3 with some additional libraries such as:
- NumPy
- Matplotlib
- String
- Random

Files in this project:

- **project.py** contains various useful functions and function templates that you will use to implement your learning algorithms.

- **main.py** is a script skeleton where these functions are called and you can run your experiments.

- **utils.py** contains some utility functions.

## The Data
The data consists of several reviews, each of which has been labeled with **+1** or **-1** , corresponding to a negative or positive review, respectively. The original data has been split into three files:

1. reviews_train.tsv (4000 examples)
2. reviews_validation.tsv (500 examples)
3. reviews_test.tsv (500 examples)

## Algorithms Implemented
In this project we will be implementing the following linear classifiers:
1. **Perceprtron Algorithm**
2. **Average Perceptron Algorithm**
3. **Pegasos Algorithm**
with an optimization problem of an objective function balancing between Hinge Loss (Lossh(X)) and Reguralization Loss (Lambda).
