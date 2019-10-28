# Chapter 4

## Z-Scores

- Talking about the location of a score in terms of its distribution
  - You would want to know where you fall in that distribution, the location of your own score (in a sense of application)
- The z-score, or a standard score, is a measure of how many standard deviations above or below the mean your score is
  - $z = \frac{x-\mu}{\sigma}$
  - If the z-score is positive it is above the mean, if the z-score is negative it is below the mean
  - Useful for comparisons of different raw data on two different scales
  - See slides for formulas, incl. z-score from raw score and raw score from z-score
    - $x$ = score
    - $\mu$ = mean
    - $\sigma$ = points per standard deviation
  - See properties on slides as well
- A linear transformation is if you add/subtract/multiply/divide every score in the distribution by a constant
  - A linear transformation does not change the shape of a distribution (constant; mult/div change distance but still not shape)
- In a normal distribution is really a family of distributions.
  - They are normally distributed, but the means and medians are different.
  - The area under the curve within a given z-score range is probability
  - Working with continuous variables implies working with a range of possible probabilities
- The standard normal distribution has a men of zero and a standard deviation of 1 -- It's in terms of z-score
  - This table (in resources folder) is also known as the z-score table, and is used to get precise measurements
  - See additional details on slides
- Percentile Range -- Percent of scores at or below a certain value (all the way to zero, not just to the mean)
  - Find z-score, then check the z-score chart (in resources folder)
  - When calculating, you can take an entire previous area (i.e. before the mean will be .5) and add it to the smaller region beyond the mean.
  - Don't forget to put it into a percentage! (Unless the questions asks for proportions, then you can leave it)

- Should your z-score, i.e. the cutoff for top and bottom 5% of scores, be not exact, either table value on either side are acceteptable
  - In order to return to that, you just plug and chug
- You were pretty distracted sorting this markdown out today... Really review chapter 4 in the textbook because this stuff is definitely new

## Means and z-scores in a sample distribution

- In behavioral sciences, especially psychology, we are interested in a group as opposed to an individual.
- **Sampling Distribution of the Mean:** The probability distribution of the mean. It tells us how likely the mean is.
- **Central Limit Theorem:** The Sampling distribution of the mean is a distribution of means.
  - It's the distribution of mean of a particular sample size. Changing the sampling size changes the distribution
- $\mu_{\bar{x}}$ = mean of the means
  - The mean of the sampling distribution of the mean *is equal to* the ~~(distribution of?)~~ population mean.
- $\sigma_{\bar{x}}$ = the standard error of the mean
  - $\sigma_{\bar{x}} = \frac{\sigma}{\sqrt{n}}$ _Standard deviation divided by the square root of n_
  - The standard deviation of the sampling distribution of the mean
  - Tells you how far means are spread out from the population mean
  - Gives you a certain amount of how far different those sample means are from the population
  - A standard error is always going to be smaller than the standard deviation
    - This is because, mathematically, you are dividing it by another number, thus making it smaller
    - Conceptually, _means are less variable than scores_. It's not unusual to have extreme scores, but it is unusual to have people with a mean of those extreme scores. Means tend to be less variable than the extreme scores.
- _As n increases, the standard error decreases._
  - As your sample size increases, the variability of those means gets narrower and narrower. It becomes more precise, there is less error involved.

## Sampling Distribution of the Mean

- In order to get the shape, we need the <?>
- The shape of the sample distribution of the mean will be normal _if:_
  - The population distribution was normal _or_
  - The population distribution is not normal _but_ the sample size is big enough **Center Limit Theorem**
    - The main idea that the score by itself is one thing, but a mean is an aggregate of a lot of things. The more things that you are aggregating, the more and more normal it will get.
    - _How do you know if your sample size is big enough? / What's big enough?_ Between 30 and 40 for right now is considered "enough", but that will change depending on what we are looking at.
- _Why care about if it's normal?_ We use the distribution to find the probability of events.
  - When it's normal, we can use the z-score table to find the probability of the mean.

## Describing Groups

- You can use the _sampling distribution_ of the mean to find the location of one group in relation to other groups
- Determine z-score, then find the area (the **p**roportion)
- $z = \frac{\bar{X}-\mu}{\sigma_{\bar{x}}}$
  - Useful to note what the standard error is, so no harm in doing it outside of the formula. Standard error is a narrower distribution
- You take the probability, the _p-value_, from the z-score table. If/when asked for a probablility, you multiply by 100.
- As n increases, standard error ($\sigma_{\bar{x}}$), decreases, and the probability decreases as well.
- You need to go over the questions in the slides. _Individuals vs group- are you given a mean, a sample size?_]
  - Normal $z = \frac{X-\mu}{\sigma}$ vs. $z = \frac{\bar{X}-\mu}{\sigma_{\bar{x}}}$
  - **First one:** $z = .73$, $p = .2327$ -- Normal z-score formula.
  - **Second one:** $z$ comes from first part, but still separate questions. $\sigma_{\bar{x}} = .24$,  $z = 3.25$, $p = .0007$

## Assumptions

- If your sample is going to be big enough (30 - 40 for this class), and the variable follows a normal distribution, we have the Central Limit Theorem.
- The samples are selected randomly (simple random sampling; sometimes called independent random sampling)
  - If sample size is equal to _n_, every possible sample of size _n_ that could be formed from the given population must have the same probability of being selected
  - Each selection must be independent, which means that each selection is in now way related to the other
  - Every item in a sample must have an equal chance of being selected
