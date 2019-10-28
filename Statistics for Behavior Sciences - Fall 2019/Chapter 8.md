# Chapter 8 -- Statistical Power and Effect Size

## Power, Beta, and Effect Size

To know what power and $\Beta$ come from the alternative hypothesis distribution. We need to plug in numbers to get these values

- $\Beta$ is the probability of doing a Type II error (failure to reject the null when it is false)
- Power is rejecting the null when it's false 🎉
  - Finding a difference when there is a difference there to be found
- The idea is that we want Power to be high, and $\Beta$ to be low. They're both related to each other.

When people try to estimate power they try to estimate it from a few different scenarios. We're going to be doing it under one scenario.

Performing a two-tailed t-test on the weight data shows that men and women have the same average weight. We failed to reject $H_0$ but it should have been rejected, thus a Type II error.

If we reduce alpha, we decrease power. However, if we reduce alpha, we increase $\Beta$. Note the inverse relationship. They always have this inverse relationship property. _Sidenote:_ Who the hell just spoke because that voice did not sound like mine.

$\delta$ is the center of the alternative hypothesis distribution. Your power is always dependent on $\delta$, or some alternative hypothesis distribution. If it equals the critical values, power and $\Beta$ will be the same. $\delta$ is the same as the _expected_ _t_-value. It is the center o the alternative hypothesis distribution. The cutoff point; to the left is $\Beta$ and the other side is power, or $1 - \Beta$.

The standard deviation is the square root of a pooled variance. We use $d$ for population, of course, but use $g$ for calculating from a sample. As the effect size, $\delta$, gets bigger, $\Beta$ gets smaller while power gets bigger. If you decrease the standard deviations, effect size gets bigger which, as we just saw, $\delta$ gets bigger, and power increases.

Effect size: $d = \frac{\mu_1 - \mu_2}{\sigma}$ -- Differences between the means, pooled deviations, sample size... Sample size is within our control largely, and is where we will be able to change power
Therefore: $\delta = d(\sqrt{\frac{n}{2}})$
$g$ and $d$ are interchangeable in formulas, so be careful / keep that in mind!

Calculating effect size. $d = \frac{\mu_1 - \mu_2}{\sigma}$ for population, and for studies $g = \frac{\bar{x}_1 - \bar{x}_2}{S_p}$. $S_p$ is from the pooled variance, which is $S^2_p = \frac{(n_1 - 1)s^2_1 + (n_2-1)s^2_2}{n_1+n_2-2}$. Our pooled variance denominator will always have $- 2$. Effect size is a magnitude of difference; it can be negative and positive. You can think of the difference being surrounded by absolute value bars to get the 'dstiance' between the two.

Thinking of overlap between two distributions:

- The following are $\geq$ until the next interval
- $d = .2$ is considered small effect size
- $d = .5$ is considered medium effect size
- $d = .8$ is considered a large effect size

The larger your select size, the less overlap there is between the two groups (normal distribution of null hypothesis and normal distrbitution of alternative hypothesis). It's largely a measure of whether or not you _care_ about the difference- how big a difference is there between the two groups?

As effect size gets bigger, $\delta$ gets smaller, and power gets smaller as well! (Thus $\Beta$ gets bigger)

Reducing the pooled standard deviation _increases power_. The intermediary step is that decreasing the pooled standard deviation increases effect size, thus power gets bigger

If the means of the group are different / the groups are different, but there is little variability, then the effect size is decently large.

## Interpretation of _t_ Values

A large _t_-value tells you about $\delta$, which is your expected $t$. However, it doesn't tell you about effect size. If _t_ is big, $\delta$ will also likely be big, but effect size and sample size go together.

You can be sure effect size won't be zero, but not too precisely. _p_ values tell us nothing about effect size. With a series of similar tests, smaller _p_ values will be associated with larger estimates of our effect size _but nothing more than an estimate!_

In SPSS, _p_ values are sig values...!

Power is obtained from a table once you're given $\delta$. Look in the $\delta$ column, and then the body of the table is power. Regular rounding rules apply! _**For hypothesis testing, go lower because you're making decisions.**_

## Sample Size Determination

Sometimes we want to determinet he minimum $n$ we need to find a significant effect with a meaning effect size. Thus, we use $n = 2*(\frac{\delta}{d})^2$ in order to solve for $n$. That way, you can find how many participants you need in a given group. You'll want to give this value. To find $d$, you can make an estimate using $.2, .5, .8$ as the level of effet size you want. The larger effect size, the fewer the people thaty ou need. With power and $\alpha$, you can then find $delta$.

[ ] Do the two-sample test from the slides as practice.

- There is another example in the slides. The following bullets are observations fromthe problem done in close.
- I'd really recommend memorizing that t_flowchart document...! Not necessarily the specific equations but just how it works and recognizing those formulas, obviously.
- Another note to self, see how quickly you can answer the questions in class when you have done the practice problems? In this case it was the SPSS assignment, and it was yesterday, but the same point applies!
- Speaking of the assignment, we didn't do the APA format thing properly. If something is not statistically significant, you have to use the proper wording! **This is super important to remember, both for exams and studies you might do in the future!**
- Don't forget your standard error when you're calculating the confident interval. I remember doing _something_ like that on SPSS 2, but I don't remember it being the same thing... I think I may have taken the standard deviation, and not the standard error, from the SPSS output.
- Don't forget- to find $\Beta$ you can find power, then $1 - power = \Beta$!
- Effect size may be big, but power may be bad because the sample size is small. That's the likely reason we didn't find significance.

## Power of a One-Sample Test

We have the two formulas $\delta = d*\sqrt{n}$ and $n = (\frac{\delta}{d})^2$ but the $2$ is missing. _There is more **power** for a one-sample test than for a two-sample test_. This is because there is less variability between the two. For a one-sample test, you are wondering about how much difference there is from one population mean to another. If there are two samples, there is twice as much possible variability. _Less variability means **more power**_.
