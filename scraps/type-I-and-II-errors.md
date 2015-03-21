## Type I errors – Mistaking shrubs for trees

A more technical way to view statistical significance is that it sets an upper bound to the probability of a Type I error.  So, if a correlation is statistically significant at &rdquo;p<.05&ldquo;, the probability of the result being a Type I error is 5-percent or less.  However, while that explains the relationship between Type I errors and statistical significance, it doesn't explain what a Type I error actually is.

In a very broad sense, a Type I error is when the correlation found by a regression analysis does not actually exists in the population data.

A more precise, but less clear, definition is that a Type I error is when the size of effect of a correlation detected in a sample differs by an important amount from the size of effect of the correlation in the population.  It's easier to think, and talk, about a correlation either &rdquo;existing&ldquo; or &rdquo;not existing&ldquo;, but the reality is that any two things that might be correlated nearly always are correlated.  What's important is the strength of the correlation, in other words, the size of effect of the correlation.

That distinction helps moves us toward understanding why Type I errors can happen.  Since everything is correlated to everything, any sample drawn from the population will contain all the correlations that are in the population.  The set of existing correlation doesn't vary between any samples we might take.

What can, and does, vary between different samples is the size of effects of those correlations.  If you draw a sample, and it happens to contain a large number of cases which indicate a size of effect for some correlation that is quite a bit higher than the average size of effect for the population, the sample will also indicate a size of effect for that correlation that is above the average for the population.

If that sample's correlation size of effect is far enough above the population's average, the sample will indicate that the correlation is large enough to be considered important, when, in fact, in the overall population the correlation is not important.

The reason that a Type I error can happen is that the mean values for the data in any sample will vary from the mean values for the data in the population.  If the sample means vary far enough from the population means, the results of a regression analysis will be in error.

The tests which are used to confer “statistical significance” on a correlation are, in fact, determining the likelihood of having made a Type I error.

[[Put something here about how sample size and variation affect the errors in means, and therefore statistical significance calculations?]]

## Type II errors – Missing forest for trees

A Type I error is when you find in a sample a size of effect for a correlation that is larger than in the population, and the difference is enough to make an unimportant correlation seem important.

In other words, with a Type I error, an unimportant correlation seems important.  You get the inverse with a Type II error, which is when an important correlation seems unimportant.

The reasons that a Type II error can occur are similar to those that cause Type I errors.  However, instead of having a sample that over-represents cases with particularly strong correlations (compared to the rest of the population), a Type II error can happen when a sample over-represents cases with particularly weak correlations (compared to the rest of the population).

And while the statistical significance of a result describes the probability of a Type I error, the statistical power of an experiment describes the probability of a Type II error.

It's much more common in to read in articles in academic journals about statistical significance than about statistical power.  Why?  For two reasons: 1 &ndash; academic journals typically only publish the results of experiments that have been completed, and not descriptions of planned experiments with as-yet unknown results; and, 2 &ndash; academic journals typically only publish results that have positive findings, meaning, results were a correlation was found and determined to be statistically significant.  It's rare to see an article about an regression analysis which produced no statistically significant results.

If experimental designs were published independently, statistical power would presumably be a prominent feature of those articles. Statistical power is important when designing and planning research, since you don't know for sure before-hand if you are going to get any statistically significant results, and statistical power helps you at least understand, if not control, that uncertainty.

Statistical power is the probability of a Type II error, which means that it estimates the chance of failing to detect an important correlation.  However, statistical power is reported in terms of the chances of positively detecting important correlations.  So, a statistical power of 60-percent means that there is a 60-percent probability that an important correlation will be detected, and a 40-percent chance that it will be missed.

Just like statistical significance, statistical power is a function of the size of effect of a correlation, the level of confidence you want in the result, and the number of cases in the sample.  So, for statistical power, sample size, confidence level, and magnitude of correlation &ldquo;any one of these parameters is determined by the other three&rdquo; (Cohen *et al.*, 2013).

Before an experiment is run, you can use statistical power calculations to determine how large of a sample size you'll need, using an estimate of the correlation you expect to find, the level of confidence you need, and how high of a probably of find the correlation you want.

Statistical power can also be useful for explaining why the lack of statistically significant results from a regression analysis can actually be an important result.  If the statistical power of an experiment is high, that means that the probability of detecting any existing correlations is also high.  If that experiment is looking for correlations that should exist&mdash;either because they have previously been reported, or because they are integral to a particular theory&mdash;but it does not detect them, the high statistical power becomes an estimate of how high the probability is that those correlations do not actually exists.

### Type I vs. Type II errors

The difference between the two types of error is that while statistical significance considers the error that comes with extrapolation from a sample to a population, statistical power considers the possible deviation introduced by sampling from a population.  Statistical significance says, &ldquo;Given the variation in our measurements of the sample, and of the sample from the population, what can we say about the population?&rdquo;  Statistical power says, &ldquo;Given the variations in the population, how much can we expect any given sample to deviate from that population?&rdquo;

If those seem somewhat circular, that just means you're paying attention.  Remember that statistical power, statistical significance, sample size, and effect size are all deterministically related.  Meaning, given any three, you can determine the fourth.  So, for a given a sample size and effect size, the statistical significance and statistical power are in a determined, inverse relationship to each other.  To raise one, you must lower the other.  They can both be high, but further elevating either one will necessarily drop the other.

