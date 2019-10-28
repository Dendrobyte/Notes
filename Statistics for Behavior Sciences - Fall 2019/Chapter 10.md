# Chapter 10 - Linear Regression

Using one variable to predict another variable.

The terminology is _regressing **y** on **x**_. This means that we are using $x$ to _predict_ $y$

Not using $z$-scores for our computation, but it helps to put it in terms of a $z$-score because it gives us a good way to look at it / a known metric to use.

This rule with perfect correlations does not give the best predictions, thus we modify the rule to be $Z_{\hat{y}} = r*z_x$. We see that this remains to fit becuase if $r = 1$ we have the original rule, and if $r = 0$ the best predicito is the mean ($z = 0$ is the mean of scores)

_If there is no relationship, the mean is the best predicter_ - when $r \neq 0$ then you can take that account to your prediction. Regression toward the mean (regression toward mediocrity)

See the slides for our equations, but a 'new' definition of slope: How much $y$ changes every time $x$ changes by 1 unit. Slope will be represented by $b$, or $b_{XY}$ (using X to predict y). The $y$-intercept is referenced by $a$, or $a_{YX}$. The equation we'll be mainly using is $b_{YX} = \frac{\sigma_Y}{\sigma_X}r$

~Definitely should have paid attention to this one... Really focus on the textbook because this is an important topic!~

$\hat{y}$ is your _predicted_ yT

The bigger the variance of your estimate, the more error in your prediction. This variance, $\sigma^2_{estY}$, is the distance of your points from your line. If the correlation increases, error decreases (intuitively).

If $r=0$ then the estimate of the variance will get _smaller_ than the total variance.

**Important** $Y-\bar{Y} = Y - \hat{Y} + \hat{Y} - \bar{Y}$ Could do this for every score in the distribution to find how far y values are from the mean and the prediction. If you did it for every score, which would be $\Sigma{Y-\bar{Y}^2} = \Sigma{Y - \hat{Y}} + \Sigma{\hat{Y} - \bar{Y}} / N$. Note that they are all variances!

- The first term, $\frac{\Sigma{Y-\bar{Y}^2}}{N} = \sigma_{y}^2$, is called  the total variance
- The second term, $\frac{\Sigma{Y - \hat{Y}}}{N} = \sigma_{estY}^2$ is called the variance of estimate, residual variance, and unexplained variance (they all mean the same thing)
- The last one, $\frac{\Sigma{\hat{Y} - \bar{Y}}}{N}$, is called the explained variance. No special notation, also has a different notation in textbook but don't worry about calling it that

_Explained variance_ is a variance that is being 'explained' by your $x$ variable. It tells you how much your $x$ variable is helping understand what is going on in $y$.

_Unexplained variance_ is all the variance that $x$ is _not_ explaining.

Want your unexplained to be small (when your correlation is large), and your explained to be big!

The _coefficient of determination_ represents the _proportion_ of the total variance that is explained by the predictor variable. $r^2$, which is explained varance / total variance. This can be written by $\frac{\sigma_{estY}^2}{\sigma_{Y}^2}$. See the slides. _Note that these are population parameters._

_83% of the variability in the exam two scores, can be explained by performance on exam 1_ -- Note that the specific numbers or scores are not important, it's the wording that is. People use the words _explained by, predicted by, accounted for by_ as alternatives for this (not dependent).

The best fitting line, the best line, is the line with the smallest amount of error. The variance of an estimate is a _measure of the variability around a regression line_. It is one value that gives you an amount representing how far spread out the points are from the regression.

**Homoscedasticity:** This means that the variance, the variability, of the points around the regression line is approximately the same. This lets us calculate an estimate for the sample, see equation for $s_{estY}^2$.

Multiple regression combined two different $x$ scores, and it's in chapter 17 in the book in case you're interested... That's the interesting component/important component for determining things such as human behavior.

See underlying assumptions of and when to use linear regression on the slides and come up with some examples as practice

$k^2$ is the coefficient of non-determination. $k^2 = [Unexplained Variance] over [Total Variance]$- it's a proportion.

$r^2$ is the coefficient of determined variance. $r^2 = [Explained Variance] over [Total Variance]$- tells you how good your regression line is at predicting $y$ from $x$. The larger $r^2$ is, the better your predictio is, and your variance of the estimate goes down (your error is decreasing).

How far your original data point is from the point you predict it to be is called the _residual_. The _least squares regression_ is the smallest amount of squared-and-summed residuals. The line with the smallest amount of error is the best predictor.
