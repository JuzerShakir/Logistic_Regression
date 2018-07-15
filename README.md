# Logistic Regression

## Table of Contents
- [Prerequisite](#prerequisite)
- [Description](#description)
- [Notations](#notations)

## Prerequisite
 - [Standard equation of a Circle](https://www.khanacademy.org/math/algebra2/intro-to-conics-alg2/modal/v/writing-standard-equation-of-circle)
- [Dividing by Zero](https://youtu.be/J2z5uzqxJNU)
- [Logarithm](https://www.khanacademy.org/math/algebra2/exponential-and-logarithmic-functions/introduction-to-logarithms/v/logarithms)
- [Dependent Probability](https://www.khanacademy.org/math/statistics-probability/probability-library/modal/v/analyzing-dependent-probability)


## Definition
`Logisitic Regression` is a classification algorithm where a dependent variable `'y'` that we want to predict takes on discrete values, for example `y ϵ {0,1}`. It is the most popular and widely used.

<br>

### Example of Classification Problem
| Subject | Negative | Positive |
| :-----: | :------: | :------: |
| Email | Not-Spam | Spam |
| Online Transaction (Fradulent) | No | Yes |
| Tumor | Benign | Malignant |

<br>

These are some of the area where `Logistic Regression` is used. Where we want to know whether an email recieved is `'Spam'` or `'Not-Spam'` and then place them to their predicted category. Whether the transaction is fradulent or not and whether the tumor is `'Benign'` or `'Malignant'`.
<br>
The way we approach to these type of classification problems where the prediction variable `'y'` does not take on continous value is we set `'y'` to take on `'discrete values'`, for example:<br>
<pre align = center>y ϵ {0,1}          0 : 'Nagative Class'
                    1 :  'Positive Class' </pre>

<br>

We can think of predicting value `'y'` taking on two value either `'0'` or `'1'`, either `'Not-Spam'` or `'Spam'`, either `'Benign'` or `'Malignant'` etc.

<br>

Another name for the class that we denote with `'0'` is the `'negative class'` and another name for the class that we denote with `'1'` is `'positive class'`. So `'0'` we denote as `'Not-Spam'` and `'1'` as `'Spam'`. The assignment of these classes is arbitrary and it doesn't really matter but often there is an intuition that a `'negative class' '0'` is conveying the absence of something.

<br>

Classification probelms like these are also called `'Binary Classification'` problem where we have only two outputs, either `'0'` or `'1'`.