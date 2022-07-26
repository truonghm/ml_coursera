# Classification & Logisitic Regression

## Sigmoid function, log odds and odds

Probabilities range between 0 and 1.

Odds = $P(success)/P(failure)$
Odds range between 0 and infinity.

Log odds = log(odd).
Log odds range between negative infinity and positive infinity. 
-> easier to model unbounded outcomes. Logistic regression is in reality an ordinary regression using the logit as the response variable. The logit transformation allows for a linear relationship between the response variable and the coefficients:

$$log(p) = aX + b$$

This means that the coefficients in a simple logistic regression are in terms of the log odds, that is, the coefficient $a$ implies that a one unit change in $X$ results in $a$ unit change in the log of the odds.

When getting rid of the log, we have:

$$p(X) = \frac{1}{1+e^{aX+b}}$$

## Maximum likelihood function

Watch here: https://www.youtube.com/watch?v=YMJtsYIp4kg