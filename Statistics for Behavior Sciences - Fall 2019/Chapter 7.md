# Chapter 7 -- The _t_ Test for Two Independant Sample Means

## The _t_ test for two independent sample means

- We're talking about two sets of data that have no relation to each other
- The basic idea is transforming things into a new _t_ test
- We now need the sampling distribution of the difference between the two means.
  - Imagine you have one population. You take one sample you get the mean you write it down. You take another sample find the mean and throw it back in. Now you have two means. You take the diff between two means. That becomes first point on the sampling distribution. Do it again, again, and again... an infinite number of times. Now you have a _distribution of differences_ (a probability distribution of the difference between two means).
  - It will differ, similar to one sample tests, in sample size.
  - It's just a sample of the spread.
  - _Note:_ The formula on the first slide, with the sigma, is not going to be used by us (it uses population parameters).
  - We don't have sigma so we'll be using _t_ tests fairly often,

## Pooled variance estimate

Two sample variances can be pooled together to form a single _estimate of the population variance. It's just a weighted average of two variances, that's all it is.

- The use of this is based on the assumption that the two populations have the same variance
- This is not the _t_ test! This just makes sure you can put the two samples together.
- When one variance is no magnitude (?) larger than the other, we say the variances are the same.
- The _t_ test formulas are on the slides. The three on there are basically all the same. They are all the (estimated) standard error of the difference between the means.
- The denominator of the _t_ test is the confidence interval.
- The confidence interval is the denominator of the _t_ test.

The flow chart on the slides are very useful. Memorize that and/or write that on your 'cheat sheet' because it'll tell you what to do.

Degrees of freedom, and its relation to standard deviation, will continue to come back for you!

If you have a quasi experiment, you could still do the analysis, you just couldnt' say it was caused by anything.

It's all plug and chug, Mark, but you have to know where to plug and when to chug.

"How do I use the confidence interval to test the error?" You compare you null hypothesis value to the interval

This morning was an off morning, so it's okay, _but please try to pay more attention next class :)_

## Next day, back on the grind

Still sort of going back and forth to Horace GitHub repo, but will pay more attention. Especially after 10, hehe.

Assumptions: (Remember the flow chart!)

- Independent random samples
- Normal Distributions
  - Central Limit THeorem
  - We look at the samples to see if it's justified in saying the two pop variances are the same
- Homogeneity of variance -- don't have to worry about it if...
  - Both samples are quite large (100 per group)
  - Two samples are the same size
  - When your sample variances are very similar
  - If one variance is no more than twice as large as the other, you assume homogeneity

### HOV Tests and the Separate-Variances t Test

- HOV is a camparison of variances
- F test is the simplest but will come back during chapter 12
- Levene's test is much simpler. We won't be calculating it, just how to read it in SPSS.

## When to use Two-Sample Test

- Used to analyze a quasi or true experiment
- Appropriate only when the dependent variable is interval or ratio
  - if ordinal or categorical, use nonparametric stats
- Ind variable is usually measured on a categorical scale
  - Sometimes it might be on an interval or ratio scale
  - "dichotomized" -- we're not going to use it
- Finding degrees of freedom is key

Now going to pay attention to the sample problem. The textbook is actually super hepful relative to this... Practice problems and reading is the way to go 😎

### The three key things for two sample tests

1. Estimation
2. Precision
3. Hypothesis testing

## Some textbook notes

- If you have enough information to find the variance for a population, you have enough information to find the mean.
- A quasi-experiment is essentially an observational study. For an actual experiment, you assign X people to different groups to test two conditions.
  - The participants chose which activity to do, it was not randomly assigned
