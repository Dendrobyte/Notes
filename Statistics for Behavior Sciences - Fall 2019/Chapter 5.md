# Chapter 5

## Review Things

- Central Limit Theorem
- The standard error is the standard distribution of the sampling of the mean (!)
- Standard error gets smaller upon increasing the sample size- it becomes more precise
- If the population distribution is not big enough but your sample size is big enough, your curve gets more and more normal

## Sample _z_ Test

- _Null Hypothesis Testing_ - This is an indirect way of proving your case
  - We don't really prove anything in statistics, so it's "proving" your case
  - Not trying to prove one of the possibilities, but trying to _disprove where everyone else is coming from_ since we only have one number to work with ($\mu = 100$). Since you are disproving, that's why it is indirect.
  - Take worst case scenario, i.e. your hypothesis is false, and assume it is true.
  - You then attempt to show that this idea leads to "ridiculous consequences", then reject the assumption.
  - Since you are proving the opposite of this assumption, you are proving the original hypothesis, and thus rejecting the above is a good thing

## Logic of Null Hypothesis Testing

- One hypothesis, the **null hypothesis**, states that experimental results merely come from sampling the original population at random (not a different population)
- _The Null Hypothesis Distribution_ - What would be the distribution of scores, should the null hypothesis be true
- We either want to be wrong _.05_ (or _.01_) times, represented by $\alpha$
  - If $\text{p-value} < alpha$ then we reject the null hypothesis and say that we don't think our result is due to chance and thus proving the original hypothesis
- The $\alpha$ level is set before getting numbers. By default, or if nothing is said, $\alpha = .05$, otherwise you may be told $\alpha = .01$
  - $\alpha$ used for only null hypothesis testing (in our context/for our needs)
- _If the null hypothesis is rejected, where $\text{p-value} < \alpha$, the result is **statistically significant**
  - Significance --> The probability of our result is so small we do _not_ think it is _due to chance_
  - If p-value $> \alpha$ then we "fail to reject" the null hypothesis (no one says they accept it). There is insufficient evidence to reject it.

## Type I and Type II errors

- See the matrix/table about **actual situation** on the slides. Either the null is true, or it's false.
- _Type I Error_ (false positive) - Rejecting the null hypothesis when it is true. Saying there _is_ a difference when there is none
- _Type II Error_ (false negative) - Failing to reject the null hypothesis when it is false. Saying that is _not_ difference when there is one
- To reduce Type I and Type II Errors...
  - You could lower $\alpha$ value, i.e. _.05_ to _.01_ to avoid Type I errors
  - You could reduce Type II errors by performing a _one-tailed_, rather than a _two-tailed_, test
- You don't know if you get a Type I error unless people replicate your work
- _Directional Hypothesis_ - A hypothesis made up of words that specify a direction, not a specific value.
  - You are then specified that you are performing a _one-tailed test_, so you're putting your $\alpha$ all in one spot (on your distribution)
- _Non-directional Hypothesis_ - A hypthesis that does not make a large difference
  - This manes you are performing a _two-tailed test_, so you're putting half of $\alpha$ on one side, and half of $\alpha$ on the other side (of your distribution)
- The size of rejection is bigger than on a two-tailed test. If you have a bigger rejection reason, it is easier to reject the null hypothesis.
- By making the rejection area larger in a one-tail test you have lessened the probability of making a Type II error
- Why not always perform a one-tail test?
  - If you change from one-tail to two-tail test, then you can increase your $\alpha$ and not telling anyone.
  - This leads researchers to not trust you, and thus by doing a two-tailed test and a non-directional hypotheses, you are more trusted. No increasing the $\alpha$
  - **In this class, we are going to be sticking with non-directional hypotheses and two-tailed tests**
- The z-score we've been calculating is called a _test statistic_, and we'll be finding different test statistics throughout the semester.
  - You're turning components of raw data into a z-score.
- **Alternative hypothesis**/research hypothesis/full hypothesis = $H_1$
  - $H_0 \neq H_1$
- You get **p-level from the z-score table** based off of z-score
- _Critical values_ or _z critical values_, $z_{cv}$, is comparing p-level to $\alpha$.
  - To find signiifance with critical values, you're seeing if your populated value is more extreme than your critical value. **If it is, then you also have significance**
- The p-level is the _probability of your result being due to chance_ provided that the null hypothesis is true is called (_sig_ in SPSS)
  - The $\alpha$ is also a probability, but is the _probability of rejecting the null hypothesis when it is actually true_.
- _Rejecting the null hypothesis when it is false is called **power**_
- $\beta$ is the probability of making a Type II error
- Essentially, when p-value $< \alpha$, we reject the possibility of chance being the cause of our result

## Assumptions for one-sample z test

- DV was interval or ratio scale
- The sample was drawn randomly
- The variable mueasured has a _normal_ distribution in the population.
  - Central Limit Theorem makes this assumption not critical if the sample is > 30
- The standard deviation for the samples population is the same as that of the comparison population
- You can't get a correlation if there is a group pre-existing.
- This one-sample z test is a _bad design_. It is taught to illustrate the ideas
  - You don't have a control group _(I don't know who was just speaking but nice job)_
  - If the sample is not representative, your results become totally useless. It's only as good as the sample you have.

## More about Type I and Type II Errors

- Alpha can be defined as the precentage of those experiments that a researcher declares to be statistically signiifcant.
  - If $\alpha = 5$%, it means that only $5$% of the null experiments are declared statisically significant
- Effective or ineffective refers to reality, or truth, and you never know if what you're looking at is indeed the truth
- We can't know how many Type I errors were made (even though it would technically be 5% but you don't know because) you don't know how many were null or ineffective.
  - The 5% experiments would apply only to the ineffective experiments
- There is no real way to estimate precentage of ineffective experiments, and _it does not depend upon $\alpha$_
- File drawer problem -- Someone does a study, they don't get significant results, and thus the research is put away
- We don't do _Bayes' Theorem_, :tada:
- If the researcher rejects the null you can only possibly make a Type I error
- If the reearcher fails to reject the null you can only possibly make a Type II error

## 6 Steps to Null Hypothesis Testing

1. State the Hypotheses ($H_0$ and $H_A$)
2. Select the Statistical Test and the Significance Level
3. Select the Sample and Collect the Data
4. Find the Region of Rejection
5. Calculate the Test Statistic
6. Make the Statistical Decision

### Example problem

1. The hypothesis is nondirectional because it is not specifically meant for advancement, just for change
2. The test would be two tailed since it's nondirectional
3. The null hypothesis $H_{0} : \mu_{new} = 50$, such that the new teaching method does nothing to the scores. $H_{1} : \mu_{new} \neq 50$
$\sigma_{\bar{x}} = \frac{10.5}{\sqrt{n}} = 2.3479$
$z = \frac{55.5-50}{2.3479} = 2.34$
To get the critical values, you take the alpha, .05, divide by 2 for .025, and then get the corresponding value from the z-table
$p < .05$, 2 tailed
4. see above
