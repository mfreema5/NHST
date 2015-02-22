# Outline/notes &ndash; new sections only


# Intro
## Purpose of doc

([*hypothetical example here*](./hypothetical-example.md))

## Outline the doc

First we'll look at how a statistically significance result can be either important or trivial, and to further explain what it is that statistical significance measures, we'll discuss Type I and Type II errors, specifically in relation to correlation analyses.

Then, given our renewed understanding of statistical significance, we'll discuss why bigger isn't always better when it comes to data. One of the specific problems covered will be how using big data can obscure important results with trivial ones.  A related issue is the failure of authors to interpret the results of regression analyses of big data, which increases the difficulty of finding the important results among the larger number of trivial ones.

After a brief section on why this distinction between important and trivial effects is particularly important to management studies, we will give some guidelines for both how to read and how to report the correlation analysis results of empirical studies in management.

# Confusing "Significant" and "Important"
## Why/how significant results can be either important or trivial

“Statistical significance” is a mathematically pure characteristic of a correlation.  By which I mean that it doesn't require any interpretation, and also that it is independent of the particular phenomena which the correlation's variables describe.

In other words, it doesn't matter what you are measuring to get the numbers which are the data in your analysis; the resulting statistical significance won't change if you switch units of measure, or even if you change the thing being measured&mdash;as long as you get exactly the same measurements, that is.

Statistical significance comes from the numbers themselves, not the real-world things and events that the numbers represent.

Importance, however, is very dependent on the reality behind the numbers.  It is also dependent on the context of the numbers, and, indeed, the context of the analysis itself.  This is not to say that “importance” is completely subjective, but rather that there is no set formula to calculate it.

So, importance is dependent on what the numbers represent, and significance is not.  How are they related to each other then?  Importance is dependent on statistical significance.  Importance depends on statistical significance because if the numbers themselves fail to meet the criteria to qualify as statistically significant, then it doesn't really matter what they represent.  They're not confirming anything, so how can we say whether they are important or not?

Significance doesn't necessarily depend on importance because it doesn't depend on the what the numbers represent.  Calculations of statistical significance are completely uniformed by what it is being measured and analyzed.

But here's the twist: while the calculation of statistical significance is independent of the importance of the data, the final result&mdash;whether or not a correlation is “statistically significant”&mdash;is dependent on the importance, because the importance determines what the cut-off point for “significance” is.

While the 95% confidence level, a.k.a., “p<.05”, has become a *de facto* standard in the management literature, it's a largely arbitrary one.  We could make the cut-off “p<.01”, “p<.001”, or “p<.10”, or “p<.333” for that matter.  In other words, we could report with whatever level of confidence we think is appropriate, be it 99%, 99.9%, 90% or even 66.7%. **[CONFIDENCE-LEVEL CITES]**

As Cohen explains **[CITE]**, for potentially important results it often makes sense to lower the criteria as to what qualifies as statistically significant.

# What does “statistical significant” actually mean?

If the cut-off for what qualifies as statistically significant is a variable we can set, why not just set it low enough that everything qualifies?







## Type I errors – Mistaking shrubs for trees
## Type II errors – Missing forest for trees




----

**(stuff from previous draft here)**

----

# How to read empirical studies in management literature

## How should a manager critically evaluate a research article?

If you are a strategic manager, what questions should you be asking as you read a research paper that reports statistical results from a regression analysis?  A good place to start is with the questions that Lockett, *et al.*, [CITATION] asked as part of their survey of papers [WHERE? WHEN?].  They asked [WHAT?  {reporting statistical power}, {implying significant means important}, {reporting size of effect}, {interpreting results} {???} ]

The most important question to ask is are the authors using the word “significant” to mean “important”, and is that justified?  This can be tricky because, of course, the word “significant” often does mean “important”, when it has been uncoupled from “statistically”.

So, whenever the term “significant” is used, you should pause and ask yourself, “Are they talking about the statistics, or the effect?”  Are they making a statement about the mere existence of a correlation, or about the relative size of effect of that correlation on outcomes?

In their survey, Lockett, *et al.*, [CITATION], found that a worrisome [PERCENTAGE] of articles were using the term “significant” to imply importance, even though what they were referring to was the statistical significance of the result.

Another easy yet useful question to ask is, “What was the statistical power of the analysis?” Remember that the statistical power is related to the probability of a Type II error&mdash;that is, to the chance of failing to see a correlation that does exist.  However, what makes statistical power a good way to evaluate the overall utility of an empirical study is not the actual value reported for statistical power, but rather whether or not it was reported at all.

Unlike statistical significance, calculating the statistical power of an analysis requires interpretation of, or at least a judgement about, the nature of the effects that the study is examining.  This is because one of the variables you need to calculate statistical power is the minimum correlation that you are interested in.  

There are two ways to decide what size of correlation is too small, and what size is big enough, to be included in the results.  One is to base the minimum on an estimation of what those correlations mean in terms of outcomes.  The other is to base it on the size of effects that previous research has reported.  But, of course, that second method doesn't eliminate the interpretation of, or judgement about, the nature of the effects involved&mdash;it merely lets the researcher use the ones from previous published research.

If the statistical power is reported someone, somewhere, at some point, has indeed considered the potential importance of the results of the analysis, and has drawn a line between the potentially important and the probably trivial sizes of effect.

Lockett, *et al.*, [CITATION], found in their survey that only [PERCENTAGE] of papers reported statistical power.  While the authors of the papers that didn't report statistical power probably did consider the relative importance of the results they were reporting, we can't be as confident about them doing that as we can about the the authors who did report statistical power.

So, in general, the size of the statistical power doesn't matter as much as its having been reported.  The one exception to this is a statistical power of “`50%`”.  A statistical power of `50%` is not a bad value in and of itself, but for you as a reader it should throw back into question the depth of the author's consideration of the potential importance of the results of the analysis.

This is because a statistical power of 50% is the easy answer.  If you have a regression analysis that has produced some statistically significant correlations and you want to calculate the statistical power after the fact, the easiest value to use for the minimum correlation to be included is the smallest correlation you've already found.  In other words, if at a statistical significance of “`p<.05`” the smallest correlation you found has “`r=0.08`”, then you use “`0.05`” and “`0.08`” in your calculation of the statistical power.  And if you do, you'll get a result of `50%`.  [MAYBE SOMETHING LIKE {See the Appendix, “Interaction of alpha and beta in regression analyses” for more details on why this is true.} ?]  

Of course, you can also do the calculations for statistical power the hard way, and end up with a result of 50%.  So, in the spectrum of how confident you as a reader can be about the authors having made a reasoned decision about the importance of the results, authors of papers with a statistical power of 50% should probably rank above papers with no statistical power reported at all, but below papers with a reported statistical power that isn't equal to 50%.









# How to report empirical studies in management literature
## If you think strategic managers should make use of your results…
## (If you think your results are irrelevant to strategic managers, then…)



