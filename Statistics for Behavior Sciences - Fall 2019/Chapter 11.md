# Chapter 11 - The Matched _t_ Test

_t_ tests look at the difference between means, so we're going back and looking back to those tests. In this chapter, the main difference is that our sets of data are _dependent_. This test can be called the dependent _t_ test, or matched _t_ test (opposite of independent t test). Independent tests are data that don't affect each other, but now we talk about whether or not the two sets of data are related in some way- _if there is some sort of **correlation.**_

_Remember:_ The test can be found under the following names... They are used for when your two sets of data are related in some way.

- Paired t test
- Dependent t test
- Correlated t test
- Matched t test

Repeated measures design - Taking the same people and repeating the same measurement (i.e. cigarettes smoked before and after hypnosis, which is more specifically called a before-after repeated measures design)

Remember, the data have to be related to each other. It is a change in values over time, not a change between two samples. There is a lot of variability between individuals. The individual differences, or the error/variability, hid the impact of individual decreasing scores.

**Direct Difference Method:** You take the sets of scores, and subtract the scores to get one set called _difference scores_. After that, you analyze it like a one-sample _t_ test (see Ch6). Note that the null hypothesis is different, i.e. $\mu_D$; $\mu$ of the difference scores.

The formula is $t_{calc} = \frac{\bar{D}}{\frac{S_D}{\sqrt{n}}}$ where $n$ is the number of difference scores, and the $s_D = s_{\bar{D}}$ is the standard error of the _difference_ scores. $\bar{D}$ can be calculated by taking the difference of the means, or by $\frac{\Sigma D}{n}$.

Keep in mind the degrees of freedom will be $n-1$ since now you are, essentially, doing a one-sample test.

So... what changed? The denominator right before finding the $t_{calc}$ value is much smaller. We are able to extract variability due to individual differences, not the variability due to the independent variable (i.e. we take out the varibility in how many cigarettes someone smokes to begin with, not the variability in hypnosis' effectiveness)

See the slide about _Matched-t test as a Function of Linear Correlation_ for some more info, but **don't use this formula!** Just note that you are subtracting out variance due to the correlation between the two sets of data.

Increasing $r$ decreases the variability of the _difference_ scores. Definitely going to be a PollEV question... Anyway, this allows us to get rid of _extraneous_ variance, and we're left with _treatment_ variance (the important one that we want; the variability that is due to whatever we are manipulating).

There is a disadvantage that lies in the matched _t_ test... it's the reduction in _df_. Matched designs are not usually performed with very large studies, and also there is no control group. The core issue is that you need a placebo, because people could get better by placebo effect. You would want to do something like a treatment that is very similar, but just not any sort of secretive things. You have to have a good design to have good data.

Some other repeated-measures designs! We have _simultaneous measurement_, where we measure each subject twice in two conditions in the same session but presented randomly, and _successive measurement_, where conditions are presented one after the other.

There is also a **Matched Pairs Design:** Comparing two conditions on _different_ subjects.

The two types of successive design are _before-after_ design, which are great but need control groups, and the second is called a _counterbalance_ design.

When people get better at something you're testing, people get better at it. You test until they get better and pleateau, and then if you do it long enough people fatigue and get worse. Practice and fatigue are considered _simple order effects_- these are the reason you might not want things to be in the same order.

Using counterbalancing, you give people conditions in alternating patterns (AB, BA, AB, BA, etc.) for each participant. This helps get rid of the simple order effects, but not all (those are called _carryover effects_ which are essentially more complicated simple order effects; you carry over the effects of one condition into the next condition)

Sometimes, you have to use a matched pairs design, which uses different people. There are _experimental_ designs, having matched the people in some way (what's relevant?), and _natural_ designs (randomly associated)
