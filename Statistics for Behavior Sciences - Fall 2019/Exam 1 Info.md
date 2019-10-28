# Information about Exam 1

## Overall info

- It's only on Chapters 1 through 4 (no chapter 5)
- Show work on computational problems
- You can beinrg one 8.5x11 sheet, handwritten, of notes
- Formulas and whatnot will be provided
  - You still need to
- Multiple choice, fill-in, maybe T/F here and there, and some computational questions
  - Computational questions are just interpretations and doing problems
- Short responses
  - Be careful of your time
- Do problems from a blank page **(recall!)**
  - Time yourself, find out what you don't know

## What you need to know

- Multiple choice / fill-in topics
  - Independent/dependent variables
  - Levels of measurement
  - Parameter vs statistic
  - Continuous vs discrete
  - Frequency distribution and charts (box plots, stem and leaf plots, histograms, etc.)
  - Definition of percentile and percentile rank
  - Skew
  - Floor and ceiling effects
  - Measures of central tendency and dispersion
  - Causality
  - Sampling distribution (center, spread, shape)
    - Central Limit Theorem (!)
  - z-scores and the z-score distribution
  - Properties of means and standard deviations
  - Basic components of a distribution (center, spread, shape)
- Computations
  - Anything from an exam _will have been seen before from class or recitation_
  - Calculate mean, median, SS, standard deviation, etc.
  - Need to know if you're dealing with a sample or a population
  - Getting scores from percentages
  - Getting a percentile rank
  - Getting the probability from a group of means
    - Need to remember which z-score form you're using (if it's the sample or the population one)

## Checklist of things to review from slides

- [x] Chapter 1
  - [x] Descriptive vs inferential statistics
  - [x] Parametric vs nonparametric
  - [x] Parameters versus Statistics
- [x] Chapter 2
  - [x] Analyzing table of frequencies
  - [x] Frequency graphs
  - [x] Grouped frequency distributions, specifically real vs apparent limits and interval going over
    - Real limits are .5 above/below real limits because rounding (i.e. 7.5 counted in an interval of 8.0 - X)
    - Your intervals should be the range divided by a convient interval width (3 - 5 usually). To avoid too low frequencies in each interval, don't go above $\sqrt(N)$
- [x] Chapter 3
  - Dispersion = differences in variability
  - $\bar{X} = \mu$ -- The difference is in sample vs population statistics
  - The mean deviation is the average of each score's difference from the mean, but take the absolute value of it.
  - [x] Weighted mean (why to use it)
    - Applied to get a better understanding of an entire population if two sample are different sizes.
    - You multiply each $X_i$ by $n$ when calculating the mean
    - All you need to do to create a computational formula for the population variance $\sigma^2$ is to divide any formula for $SS$ by $N$
  - [x] Differences in reliability of mean, median, and mode
    - All the same in a unimodal distribution. Median best one to use for skewed data.
    - Mean is most useful for central tendency for use with inferential statistics.
  - [x] SIQR and finding it
    - $\frac{Q3-Q1}{2}$
    - Gives a good description of the spread of the main part of your distribution, even if it is very skewed, because unaffected by extreme scores
  - [x] Knowing formulas, specifically...
    - [x] When to use which one
    - [x] How to get the components of diff formulas
  - [x] Finding degrees of freedom
    - Due to the zero sum principle, it's usually $n-1$
    - Used when you do not know the population, $s$ and $s^2$ versus when you do know the population, $\sigma$ and $\sigma^2$
  - [x] Go over the idea of how mean/std dev are affected by changes (constant added vs mutiplied)
    - Constant added --> No effect
    - Constant multiplied --> std dev multiplied by same constant
  - [x] Go over components of box-and-whisker plots
    - Calculating hinges
      - Lower fence = lower hinge - 1.5(H-spread)
      - Upper fence = upper hinge + 1.5(H-spread)
      - H-spread = IQR
  - [x] Winsorizing and Trimming
    - **Trimming:** You choose a specific range of scores, and take off from the top and bottom (i.e. delete 5% of top and 5% of bottom scores)
      - Taking the mean of these 'new' is called the trimmed mean
    - **Winsorizing:** You choose a specific range of scores, and replace them
      - You replace them with the most extreme scores you're willing to assess (i.e. in a range of 1-20, you replace scores of 23 and 27 with 20 and 20)
  - **This chapter's summary is on page 73**
- [x] Chapter 4
  - [x] z score formula, knowing how to find each component, raw score formula
  - [x] Solidify the principles of a normal distribution! Know them abstractly, not just by memory, so you can apply them
    - The standard error of the mean is the std dev of the sampling distribution
  - [x] Know proportions of the curve
  - [x] Area btwn z-scores (prac questions on slides)
  - [x] Identifying reverse formulas for things like standard error and sampling distribution
  - [x] C e n t r a l L i m i t T h e o r e m

### Feynman technique [from Ultralearning] the heck outta these

- [ ] Rework _all_ problems from the slides (this honestly shouldn't be too bad, and I think as a first step would be good for learning).
  - The key idea here is to find out what you don't know, so you can know what you don't know- or at least start on knowing that.
  - [x] Chapter 1
  - [ ] Chapter 2
  - [ ] Chapter 3
  - [ ] Chapter 4
  - Give yourself 10 minutes per problem, no matter how long it takes to 'struggle' through. You can look up formulas, but no answers or hints on how to do it until that 10 minute timer goes off.
- [ ] Go over problems in slides
- [x] Look over some practice problems
- [ ] Go and find out what you don't know
- [ ] Knowing when to look at the table, specifically what types of values to find (z table and t table)

## After we prep for this exam

I'd love to catch up on textbook reading or, if I don't do that (which I won't), it's important to go over the slides maybe the day after class such that I can further understand the material we just learned. However, I might read it because it is actually very well written.

## For the next exam

Having read the chapters up until it or not (and you should! they're super useful!) try and do the practice problems, don't be so passive.
