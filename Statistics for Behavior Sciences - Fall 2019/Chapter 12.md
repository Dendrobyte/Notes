# Chapter 12 - One-Way Independent ANOVA

And now, we have our test for multiple groups! (groups > 2) called an ANOVA test. The more _t_-tests we do, the higher the chance of making a Type I error.

**ANOVA:** Stands for **an**alysis **o**f **va**riance.

In the **ANOVA** tests we're learning, we deal with indepedent groups- in other words, we are learning the ones for when the groups are unrelated and not matched in any way doing different things. _One way_ means there is only _one independent variable_ but more than two levels. In the contenxt of ANOVA, _an indepedent variable is called a **factor**_.

$s_{p}^2 = MS$, and $MS$ is another name for variance (mean square). lso, $t^2 = F$ (for Fisher).

$F$ is a ration, such that $F = \frac{MS_{between}}{MS_{within}}$. There are more specific descriptions on the slides regarding the components of this ratio, such as relation to $H_0$, but the following notes include what was spoken during that slide's presentation.

For this, your $H_A$ is not that your averages are not equal, but that your null hypothesis is not true. $H_A : H_0$ _is not true_

This is not one distribution, it is a _family_ of distributions that are all based off of degrees of freedom _but_ there are going to be _two sets of degrees of freedom_ because there are degrees of freedom that go into both the numerator and denominator of $F$

If the means are different from each other, that is a _signal_ and that will show up in $MS_{between}$ (if it's there). If the means aren't different, then you have $noise / noise$, which means your $F$ ratio is 1. What you are testing is if your $F$ ratio is different than one. The further apart your means get from each other (could just be one), the greater your signal will be; $MS_{between}$ will be increasingly bigger and thus increasing your $F$ ratio. Then, you get toward significance.

Both $MS$ are estimates of the variance; the same estimates of the population variance _only when $H_0$ is true. $MS_{within}$ estimates using variance, $MS_{between}$ estimates it using means (but only when $H_0$ is true). If $H_0$ is _not_ true, $MS_{between}$ gets bigger, thus not representative of the variance and _no longer an estimate of the population variance because it includes something else_.

The $F$ distribution is positively skewed, and as $n$ gets larger the skew becomes smaller. The $F$ ratio is positively skewed because it can not be 0 because both $MS$ are variances; they are both _squared_ and thus always non-negative.

$df_{between} = k-1$ where $k$ is the number of groups  
$df_{w} = N_T - k$ where $N_T$ is the total number of scores and $k$ is the total number of groups  
$df_{total} = N_T - 1$ - this one isn't necessary, but a great way to check you have the correct $df$  
$df_{between} + df_{w} = df_{total}$ is true, so it's used to double check  

Due to the skew, $\alpha$ is on one end, and thus is one-tailed.

Keep in mind we do three groups for time consideration, but all of this stuff applies to four groups, five groups, six groups, etc.

**Limitation of ANOVA:** It can tell you that there is a difference, but it can not tell you where the difference lies (with which groups the difference lies). By rejecting the null, we know that there is one different groups within there somewhere. Following up on this with multiple tests, we'll see more about it in _Chapter 13_

If you have equal sample sizes, $MS_{within}$ is the average of the variances. If they're not equal, it's just a weighted average- wieghted by $df$

You'll need to know how to fill out the table, so knowing how you get each value from other values is pretty important. Also be aware of the assumptions you can make, such as homogeneity of variance (which you can test for using an $F$ ratio really simply).

If you have bad power, you are likely to say you do have HOV _when you really don't_. That's a big problem with Levene's test- whenever you use small sample sizes anywhere though, your results can be tricky.

**Fixed Effects ANOVA** versus **Random Effects ANOVA**: How you choose the different levels of your factor (i.e. independent variables)

- In **Fixed Effects ANOVA**, you are interested in levels chosen and not concerned with generalizing the results to untested levels
- In **Random Effects ANOVA**, when the levels of your factor (i.e. independent variable) are selected at random from a larger set. In other words, you randomly select a few orders to test from a large pool of possible orders.
- _ANOVA methods are the same, power and effect size differ_. Fixed effects ANOVAs are the main ones in the behavioral sciences, _and are the only ones we are doing in this class._
