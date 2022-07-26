# Week 1

## Supervised vs. Unsupervised Learning

## Linear Regression Model

- Training set includes both features and targets
- Training set is fed to a learning algorithm.
- The learning algorithm produces a function, called a model.
- The input of the learning algorithm is called feature, or $x$.
- The output is call prediction (estimated $y$, or $hat{y}$).

To represent the function $f$:

$$f_{w,b}(X) = wx + b$$

Or: 

$$f(x) = wx + b$$

## Cost function

Formula:

$$J(w,b) = \frac{1}{2m} \sum^{m}_{i=1}(\hat{y}^{(i)} - y^{(i)})^2$$

Intuition:

model: $f_{w,b}(x) = wx + b$

parameters: $w,b$

cost function: 
$$J(w,b) = \frac{1}{2m} \sum^{m}_{i=1}(\hat{y}^{(i)} - y^{(i)})^2$$

goal: $
