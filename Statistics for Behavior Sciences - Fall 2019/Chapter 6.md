# Chapter 6 -- Interval Estimation and the _t_ Distribution

Note that we're missing $\sigma$, the population standard deviation, in the introduction slide. This is much more common than what we went over in Chapter 5. However, we do have the sample standard deviation.

## One-group t-tests

- When $\sigma$ is known, we use the z-test formula.
- If $\sigma$ is unknown and _n_ is large, we can use the estimate $s_{bar{X}}$.
  - If $n \leq 40$, we replace $\sigma_{bar{X}}$ in the z-test formula with $s_{bar{X}}$
- Review note: Know the difference between standard deviation in a population and in a sample
- The new statistic we use is the t-test. However, there's a problem. $s$ is an estimate of $\sigma$, which means there is error surrounding it. The smaller your sample size, the more error there will be.
- When you just subtract/divide by constants, a z-score test remains a normal distribution (linear translation)
  - If you divide by s, however, the distribution will not longer be normal, although it will be otherwise similar.
  - _t_ formula is the same as _z_ formula, but denominator switched out (see the second bullet point)
  - As you move up $n$, the shape gets closer and closer to original distribution, which is why when $n \geq 40$ you can go back to using the _z_ formula
- $\alpha$ is also known as **level of significance**
- To find your significant value, you need to use the _df_
- Sample size is becoming more and more important. See the slides for particular bullets on 'as _n_ increases...'
- As your sample size increases, your calculated _t_ gets more extreme, but your critical values come closer to the center

The denominator of the t-test is the standard error _of the difference betwene the means_

## Estimating the population mean

- Two different types of etimates
  - **Point Estimate:** Select a random sample and measure
  - **Interval estimate:** Use a range of values within which we think that the population parameter lies
- **Confidence Interval**: In terms of interval estimates, it is the interval that allows us to portray how much confidence we have in the _accuracy_ of the chosen interval
  - Good for three general things
    - _Estimation_
    - _Precision_ (The flip side of error- the wider something is the more error we say it has)
    - _Test a Hypothesis_
  - The flipside of hypothesis testing
  - When a confidence interval is an interval that does not contain the population mean, which is a 5% chance (called a miss), is the equivalent of a Type I error.
  - What the confidence interval size/width is based off of is in the slides
  - Also see basic procedures done in the slides
  - Know the _"Formal Sentence"_, which is like, "I am 95% confident that the sample mean is in the interval X to Y"
- To make the 95% confidence interval a 99% confidence interval, you change $.025$ to $.005$, where $z = 2.58$, to change the error bounds on either end. When you do this, your confidence interval expands. You could just use the $\alpha = .01$

## One sample tests

- Not a great design because...
  - No control group
  - Only as good as the sample that you have. It needs to be representative, not biased.
- One sample _confidence intervals_, however, are done all the time.
  - A confidence interval is good for...
    - Estimation
    - Precision (The narrower the confidence interval, the more precise it is)
    - You can test a null hypothesis with a confidence interval
- See example on slides

A pooled variance is a _weighted_ average of the variances. In order to pull variances, you have to make the assumption that there is a homogeneity of variance. When one variance is no more than twice as big as the other, they are the same (5 == 8, 5 != 12).

**Friendly note to do the practice problems _first_!**
