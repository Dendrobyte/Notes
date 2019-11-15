# Multiple Comparisons

A **comparison** is when you are comparing two _things_ at a time (purposely vague)

**Experimentwise Alpha** ($\alpha_{EW}$) vs **Testwise Alpha/Alpha Per Comparison** ($\alpha_{PC}$)

To determine the number of _t_-tests you perform, you could say $\frac{K(K-1)}{2}$ (duh). However, the problem is that the alpha for each test is going to be different. To find out the alpha for the entire experiment, you work backwards and find the probability of making _no_ Type I errors (instead of finding the probability a Type I error). So, opposite of alpha (0.95) raised to the number of tests,$j$, ($.95^{j}$) gets you the probability of not making the Type I error. Then subtract it from 1. Notice how wild that is... The likelihood of finding significant results is very high, but that's just by chance- it's not a real fact.

Instead of doing all that, you can calculate alpha for the entire experiment properly. $\alpha_{EW} = 1 - (1-\alpha)^j$ where $j$ is the number of tests you are performing. This remains an estimate, of course, assuming that all the tests are independent. This is why there are limitations to doing a lot of _t_-tests for one study.

## Some more comparison definitions

**Pairwise Comparison:** Comparison involves only 2 groups; another way of referring to a 2 sample _t_-test
**Complex Comparison:** Involves more than two means; comparing two means of sets, where each set might have different means.
**Alpha per comparison ($\alpha_{PC}$):** Alpha used for each test that follows an ANOVA. Adjusting $\alpha_{PC}$ is one way to reduce $\alpha_{EW}$

## Types of comparisons

**A priori comparisons:** Comparisons planned in advance (planned comparisons) [before the fact]
**A posteriori (post hoc) comparisons:** Comparisons decided on after inspecting various sample means
The difference here is that there would be some bias based on when you compare. You'll have to be stricter after the fact than before.

Once you do an ANOVA, and you weed out outliers (you get a significant _F_),  you can use Fisher's Protected _t_ Tests where you use $MS_{W}$ instead of the pooled variance- it just has all of the groups instead of two of the groups. We will also be using **Fisher's LSD test**, and the LSD [Least Significant Difference] is the amount by which two groups have to be different for us to say they are _significantly_ different.

Regarding the LSD, the only case where we don't worry about this is when we don't have three groups... Even if placebo, we don't worry about it.

But of course... there are always issues with these tests. Thus we have _complete_ vs _partial_ null hypotheses.

**Partial Null Hypothesis:** You know going in to the experiment that one of the groups is different. For example, if you are doing a test on several types of drugs and introduce a placebo drug, then you know the placebo will be different and thus not a full hypothesis.

- This means the ANOVA will already be significant, and then you lose the protection (see above).
- Now, the LSD is not legitimate.

**Complete Hypothesis:** Hypothesis of equality of all the population means- where you really don't know if any of them are different or not.

Can't do the LSD? Try the HSD [Honestly Significant Difference]! This provides more protection, since you are just looking at the two most extreme means. More than two means leads to more variability, and the chances of having bigger differences gets higher just by chance. Tukey came along and developed the _Studentized range statistic_, denoted by $q$. This allows use to find critical values, adjusted for the number of samples. Note that this **assumes equal n's**. Also notice that we use a $q_{cv}$!

The advantage of the HSD over the LSD is that it doesn't matter how many groups you have, how many tests you're doing, or whether you have a partial/complete null hypothesis... _It won't inflate the alpha ($\alpha$) for the entire experiment_, no matter how many groups are tested. However, it has _less power_. Also, HSD does not require a significant omnibus $F$.

HSD is a more conservative test (less power, same alpha). LSD is a more liberal test (more power. higher alpha).

## Some other types we might come across

We don't need to use all of these, and they're on the slides, but I will denote the key things said here.

**Newman-Keuls Test:** Don't worry too much about it, uses $q$
**Dunnett's Test:** For a specific test, don't worry about it
**REGWQ:** Modifies HSD to be more powerful without allowing ALPHA to rise, also based on $q$
**Modified LSD:** Evaluate significance of one-way ANOVA, and if significant it is easier to do than the LSD and better than both the LSD and HSD

Your experiments/studies should be designed in such a way that they actually help you find a result for your test.

LSD vs HSD - 3 groups? LSD. More than 3 groups? HSD.

HSD can be used to create confidence intervals because it is considered a _simultaneous comparison method_.

To find the $q_{cv}$ for HSD, you look for $k$ and $df_{w}$. For the modified LSD, you look for $k-1$ and $df_{w}$. The modified LSD requires a significant ANOVA.

**A priori test:** Bonferroni _t_ or Dunn's test. You adjust $\alpha{EW}$ to gain a new comparable alpha.

In _complex comparisons_, you want to compare the averages of different groups. It ends up becoming a lienar combination of population means.
