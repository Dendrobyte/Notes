# Chapter 9 -- Linear Correlation

Is there relationship? If so, how strong is it? We'll dive into one variable predicting the other variable in chapter 10. _This is called regression_.

Pearson's R or Pearson's correlation coefficient. This is $r$, which gives you a measurement that is a statistic showing how strongly two variables are related.

Correlations are plotted together- one value on the x-axis and one value on the y-axes. A perfect correlation essentially says that you can know the value of one variable given the other.

By drawing an 'envelope' around your plotted points, the more oblong it is the stronger the relationship. The more circular, the weaker the relationship.

A straight line to estimate correlations are not always helpful. If the data is not linear, it is curving linear data (using a curved line). If it is this kind of data, _you never use a Pearson's R_.

By truncating- or restricting- your range, you can mess up your correlation overall.

An outlier is an unusual score, a bi-varied outlier is an unusual correlation.

## New formulae

### Formula for population

- $N$ is the number of pairs of scores
- $\mu_1 * \mu_2$ is the covariance
  - It's a measure of how strongly the variables are varying together, systematically
  - In the same direction or opposite direction, are they moving together?
- $\sigma_x * \sigma_y$ standardizes things

### Formula for sample

Note the difference between the two! The $\frac{1}{n-1}$ and the multiplication factor not being $\mu$

To figure out if a correlation is strong...

- $.1 - .29$ is considered small
- $.3 - .49$ is considered medium
- $.5+$ is considered large
- These all apply in the negative direction as well.

## Testing Pearsons' _r_ for significance

$r$ is for sample, $\rho$ is for population. All you hae to do, is look up the $r$ critical value on the chart! Easy mode.

It is the correlation coefficient! It can range between [-1, 1]

The null hypothesis would be $H_0 : \rho = 0$

When you increase sample size, $r$ becomes more like $\rho$ - Your sample correlation becomes more like your population correlation

Only as $n$ gets large does $r$ begin to accurately represent $\rho$ (see above). Using degrees of freedom, we see that $n=2$ gives no info.

If we have one variable, we can see if they're normally distributed. If we have two variables, then probability will be found on the third dimension. This is called a _bivariate normal_, but we don't worry about that.

A Spearman $r$ is used if you don't have a bivariate distribution (if your data are curvolinear), or if there is ordinal level data. It just invovles putting things in ranks, then putting ranks into Pearson's formula. _We don't do it, but SPSS does do it._ If you don't have a bivariate normal distribution, you can use this Spearman's r to assess the relationship between two variables.

Three different types of liability, and you can use Pearson's $r$ to measure them.

- Test-retest reliability
  - If you do a test again, you'll get the same results.
  - If you're measuring something stable, and measure it now/later (for example) then the numbers should be reasonably similar
- Split-half reliability
  - Dividing a test in half, then the correlation between the two halves should be relatively high
  - Measures _internal consistency_
- Inter-rater reliability
  - Listen :(

For measures of reliability, your correlation should not be less than .7

When we say something is valid, we say that _it measures what we think it measures_. It is measuring data that is close to the target data.

**Listen!** If we have a Pearson's correlation coefficient that is close to zero this means that _there is no **linear** relationship between the two variables_. You can't conclude they have no relationship at all.

See practice problem on slides. If it's a sample, you use $r = \frac{\frac{1}{n-1}[\Sigma xy - n\bar{x}\bar{y}]}{S_xS_y}$

Then, you find the $r$ critical value. You look for $r_{cv}$ in the table using $\alpha$, number of tails, and degrees of freedom ($n-2$).
