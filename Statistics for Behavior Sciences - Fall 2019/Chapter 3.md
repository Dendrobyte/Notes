# Chapter 3

## Leftover notes, prior ones on paper

- Standard deviation center, spread, shape
- Deviation score is how far scores are from the mean, and when they all add to zero it is the zero sum score
- Resistant statistics are numbers that are not affected by outliers
- Box and whisker plots
  - Line in the center is the median
  - The top (rep 75th percentile) and bottom (rep 25th percentile) lines of the box are called hinges
  - The difference between the hinges is called the "H-spread", which is also the interquartile range (Q3 - Q1)
  - Inner fences - Not shown on graph, but can still be calculated. Inside those fences is "normal", everything outside those fences is an outlier
    - Lower fence = lower hinge - 1.5(H-spread)
    - Upper fence = upper hinge + 1.5(H-spread)
  - The adjacent values are the scores on the far end of each 'whisker'
    - They are the most extreme scores in a distribution that are not considered outliers
- Dealing with outliers
  - **Trimming:** You choose a specific range of scores, and take off from the top and bottom (i.e. delete 5% of top and 5% of bottom scores)
    - Taking the mean of these 'new' is called the trimmed mean
  - **Winsorizing:** You choose a specific range of scores, and replace them
    - You replace them with the most extreme scores you're willing to assess (i.e. in a range of 1-20, you replace scores of 23 and 27 with 20 and 20)
