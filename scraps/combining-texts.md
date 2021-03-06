# Introduction &ndash; Confusing "Significant" and "Important"

In the management research literature, it is important to understand that in the term "statistically significant," the word "significant" doesn't mean the same thing as "important."  When a correlation result from a regression analysis is described as "statistically significant", it means that the probablility that the result is an accident of random variation has been precisely determined, and that the chances are lower than some defined minimum.

That defined minimum is identified by "α", also called the "confidence level."  E.g., a confidence level of 95% is the same as α = 0.05, and means there's a 5% chance of error.  So, a statistically significant result, at a 95% confidence level, has a 5% or less probablity of being incorrect.

For a regression analysis, this means that the proposed correlation can be shown to exist in the data.  However, it says nothing about how important that correlation is.  A correlation which is statistically significant is not necessarily significant in importance.

>Concern about the statistical significance of effects (whether they exist at all) has tended to preempt attention to their magnitude. ... Although not unrelated, the size and statistical significance of effects are logically independent features of data from samples.  Yet many research reports, at least implicitly, confuse the issues of size and statistical significance, using the latter as if it meant the former. (Cohen and Cohen, 1975, p6)

However, another output from a regression analysis, the magnitude of the effect size for the correlation, can often be indicative of that correlation's importance.  And yet, in the papers surveyed in [**CITE**], 92% fail to discuss the magnitude of the coefficients at all.  Instead, 93% used statistical significance as the only criterion for the importance of a result.  And, unsurprisingly, in 97% of the papers, the conclusions are also solely based on statistical significance.

In nearly all of the papers—98%—the term "significance" is used in an ambiguous manner.  No clear distinction is made between statistical significance and other types of significance.  As Cohen and Cohen described above, in most cases statistical significance is implicitly used to mean "important".

## Purpose of doc

If managers are going to be able to use relevant research from academia as part of the process of making strategic decisions, they need to be able to figure out what research actually is relevant.  Considering the inputs and outputs analyzed by an empirical study is not sufficient to decide if a study is relevant to a real-world decision. The way that researchers interpret and present the results, may impede, if not completely obscure, the implications of those results for real-world decision-making.

This article is intended to address that issue&mdash;the potential utility of academic research for practical application&mdash;from both directions, addressing how to evaluate research articles on empirical studies for their practical utility, and also how to write research articles to increase their potential usefulness for practitioners.

### Hypothetical example

How can the statistically valid results of an empirical study be interpreted and presented in such a way as to be of no use to a manager?  Consider the following hypothetical example.

----

Let's assume that you are the manager of a plant that uses 100 gallons of pink paint every month for production.  You pay $10 a gallon for paint, but your vendor makes a proposal: you can instead buy white paint and red paint for $8 a gallon, and blend the two into pink paint.  You would save $200 per month.

But there would be costs from the change.  Additional time, labor, training and equipment.  You have an intern look into it, and it turns out that those cost add up to $100 per month.

However, there is an chance that something could go wrong with using two colors of paint blended together as part of the production process.  The added complexity could potentially cause a non-conformance of the product, requiring reworks (if caught in-house) or replacements (if found by the customer).  All of which can be reduced to a cost.

Your intern calculates that should the two-color process cause a non-conformance, it would cost $200 to remedy.  In any month without a non-conformance you'd still save $100 with the two-color process, but in a month with a non-conformance (we'll assume there's never more than one), you'll lose $100 by using the two-color process.

What you need to know, is the likelihood of a non-conformance.  If it's less than 50% per month, then you should use the two-color process.  If it's more than 50% per month, you should not use the two-color process.

So, you hand the problem over to an academic researcher to whom you've given data in the past.  She passes it on to a PhD candidate, and a year later you get your answer.

The researchers have gathered a lot of data, and run a regression analysis on it.  The candidate tells you that, &ldquo;We are 99-percent confident that using two colors of paint instead of only one will increase the probability of non-conformance in your product.&rdquo;

And after a long pause, you say, &ldquo;Yes, but by how much?&rdquo;

&ldquo;The increase will be greater than zero percent,&rdquo; says the candidate.  &ldquo;We are 99-percent sure of it.&rdquo;

After another long pause, you say, &ldquo;Can you do any better than that?&rdquo;

And the candidate laughs.  &ldquo;Better than 99-percent?  Oh no, I don't think so.  That's a very significant result!&rdquo;

----

This is a cartoonish example, but it illustrates a real problem: real-world managers don't get the answers they need from management research.  Because, while the PhD candidate in the scenario was probably correct that the result of their analysis was &ldquo;very significant&rdquo; from a statistical point of view, that same result was of no use at all to you as a manager trying to make a specific decision.

If it had been unclear whether or not the two-color paint process would increase the probability of non-conformance, then a result of &ldquo;greater than zero percent&rdquo; might have been a valuable insight.  But the questions facing managers of businesses are rarely about whether or not an effect exists.  What managers need to know is the strength of the effect, so they can balance it against other effects when making their decisions.

This is why managers and researchers in management should be wary of null-hypothesis significance testing.  NHST only looks for non-null effects, for effects with a magnitude greater than zero.  What it doesn't do is distinguish very well between effects with minor or major influences on outcomes.

So, empirical studies that use regression analysis can find statistically significant correlations that have large, important effects on outcomes; and they can find statistically significant correlations that have tiny, trivial effects on outcomes; and they can also find statistically significant correlations at everything level of importance between those two.  The statistical significance of a result in no way assures that it is an important one.

Which is, like much of statistics, completely counterintuitive.  How can a result be both &ldquo;significant&rdquo; and &ldquo;trivial&rdquo;?  The rest of this paper will hopefully explain that, and therefore give some insight into how to critically evaluate empirical research, and how to decide if the &ldquo;significant&rdquo; result reported in that research is an important effect, or merely a trivial factoid.

## Conventions of the doc

Because of the purpose and context… we'll use some specific terms in place of the general terms used in pure statistics.  dependent →outcome, independent →input, …

## Outline the doc

[**FIX** This order doesn't work with the text.  Or maybe the text needs to be forced into this order?]

First we'll look at how a statistically significance result can be either important or trivial, and to further explain what it is that statistical significance measures, we'll discuss Type I and Type II errors, specifically in relation to correlation analyses. 

Then, given our renewed understanding of statistical significance, we'll discuss why bigger isn't always better when it comes to data. One of the specific problems covered will be how using big data can obscure important results with trivial ones.  A related issue is the failure of authors to interpret the results of regression analyses of big data, which increases the difficulty of finding the important results among the larger number of trivial ones.

After a brief section on why this distinction between important and trivial effects is particularly important to management studies, we will give some guidelines for both how to read and how to report the correlation analysis results of empirical studies in management.

# "Significant" or "Important"

## What does “statistical significant” actually mean?

If the cut-off for what qualifies as statistically significant is a variable we can set, why not just set it low enough that everything qualifies?

???

## What does “important” mean, in relation to “statistical significant”

???

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

### The loophole in statistical significance

The difference between statistical significance and actual importance is most important when there are large data sets being used.  Because no matter how small, no matter how trivial a correlation is, with a large enough data set, it will become statistically significant.

Statistical significance is calculated using Student's T-test or an equivalent method.  For Student's, the value of "t" is calculated by:

  r*SQRT(n-2)     r = coefficient of correlation
t = -----------     n = number of data points in sample
  SQRT(1-r^2)     degrees of freedom = ( n - 2 )

A result is statistically significant if "t" exceeds the value in a standard table, based on the desired error-level and the degrees of freedom in the regression.

As "n" increases "t" will increase.  With a large enough sample, you will get a sufficiently large value for "t" for almost any value of "r".  In other words, no matter how weak a correlation is, with enough data points, that correlation becomes statistically significant.
For example, consider two sets of data that contain correlations for which the coefficients are identical in value—meaning, the value of "r" is the same for both.  The correlation from the larger data set will have the higher "t" value, so, while neither correlation is necessarily more important than the other, the result from the larger data set can be statistically significant while the one from the smaller data set is not.  The only difference required between these two studies to get this outcome is in the sample size.

And while similar disparate outcomes can always happen at the margin, this bias to larger sample size is not a marginal effect.  For illustration, consider that in the papers surveyed [by Locket **CITE**], sample size ranged from under 50 to over 1500.  Since the ratio of two "t" values is effectively equal to the ratio of the sample sizes, the "t" value for a correlation in a study with 1500 data points would be 30 times larger than the "t" value for an equivalent correlation in a study with 50 data points.

[[*CITE** the growth in samples sizes in AMR]]

### The hidden bias against importance

As an added difficulty to finding research that is relevant for real-world decisions by strategic managers, the shift toward larger and larger data sets in research quietly introduces a bias against important results&mdash;which are the results in which strategic mangers are interested.

While correlations of large magnitude will be statistically significant when studied through both large and small data sets, correlations of small magnitude will only be significant when studied through large data sets.  So, while a move to larger data sets doesn't increase the number of correlations of large magnitude that are published, it does increase the number of correlations of small magnitude that are published.  Therefore, the ratio of large magnitude correlations to small ones will decrease. Since the importance of a correlation is often indicated by its magnitude, and is not really tied to its statistical significance, the ratio of important to trivial correlations will also decrease.

As the literature becomes saturated with more and more empirical studies of large data sets, it becomes more and more valuable to be able to be able to separate the important results from the general pool of published results.

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

----

# How to read empirical studies in management literature

## How should a manager critically evaluate a research article?

If you are a strategic manager, what questions should you be asking as you read an academic research article that reports statistical results from a regression analysis?  A good place to start is with the questions that Lockett, *et al.*, [CITATION] asked as part of their survey of papers [WHERE? WHEN?].  They asked [WHAT?  {reporting statistical power}, {implying significant means important}, {reporting size of effect}, {interpreting results} {???} ]

In the following sections we'll look in detail at those and other questions, to explain how they are useful, when they apply, and what you can infer about an article based on the answers to them.

### Ask: “Are the authors using the word ‘significant’ to mean ‘important’, and is that use justified?”

This question can be tricky because, of course, the word “significant” often does mean “important”, when it has been uncoupled from “statistically”. So, whenever the term “significant” is used, you should pause and ask yourself, “Are they talking about the statistics, or the effect?”  Are they making a statement about the mere existence of a correlation, or about the relative size of effect of that correlation on outcomes?  In other words, have the authors conceptually decoupled it from “statistical”, or is the word still implicitly there, modifying the “significance” of the result?

In their survey, Lockett, *et al.*, [**CITATION**], only 5% of the studies surveyed correctly interpreted the magnitude of effect size of the identified correlations.  In the other 95% of papers, while the value of "r" for each correlation was reported, it was not interpreted as to the importance of that correlation.  All the correlations are either implicitly of equal importance, or the reader is left to erroneously infer their importance from the statistical significance.

### Ask: “What was the statistical power of the analysis?”

Remember that the statistical power is related to the probability of a Type II error&mdash;that is, to the chance of failing to see a correlation that does exist.  However, what makes statistical power a good way to evaluate the overall utility of an empirical study is not the actual value reported for statistical power, but rather whether or not it was reported at all.

Unlike statistical significance, calculating the statistical power of an analysis requires interpretation of, or at least a judgement about, the nature of the effects that the study is examining.  This is because one of the variables you need to calculate statistical power is the minimum correlation that you are interested in.  

There are two ways to decide what size of correlation is too small, and what size is big enough, to be included in the results.  One is to base the minimum on an estimation of what those correlations mean in terms of outcomes.  The other is to base it on the size of effects that previous research has reported.  But, of course, that second method doesn't eliminate the interpretation of, or judgement about, the nature of the effects involved&mdash;it merely lets the researcher use the ones from previous published research.

If the statistical power is reported someone, somewhere, at some point, has indeed considered the potential importance of the results of the analysis, and has drawn a line between the potentially important and the probably trivial sizes of effect.

Lockett, *et al.*, [CITATION], found in their survey that only [PERCENTAGE] of papers reported statistical power.  While the authors of the papers that didn't report statistical power probably did consider the relative importance of the results they were reporting, we can't be as confident about them doing that as we can about the the authors who did report statistical power.

So, in general, the size of the statistical power doesn't matter as much as its having been reported.  The one exception to this is a statistical power of “`50%`”.  A statistical power of `50%` is not a bad value in and of itself, but for you as a reader it should throw back into question the depth of the author's consideration of the potential importance of the results of the analysis.

This is because a statistical power of 50% is the easy answer.  If you have a regression analysis that has produced some statistically significant correlations and you want to calculate the statistical power after the fact, the easiest value to use for the minimum correlation to be included is the smallest correlation you've already found.  In other words, if at a statistical significance of “`p<.05`” the smallest correlation you found has “`r=0.08`”, then you use “`0.05`” and “`0.08`” in your calculation of the statistical power.  And if you do, you'll get a result of `50%`.  [MAYBE SOMETHING LIKE {See the Appendix, “Interaction of alpha and beta in regression analyses” for more details on why this is true.} ?]  

Of course, you can also do the calculations for statistical power the hard way, and end up with a result of 50%.  So, in the spectrum of how confident you as a reader can be about the authors having made a reasoned decision about the importance of the results, authors of papers with a statistical power of 50% should probably rank above papers with no statistical power reported at all, but below papers with a reported statistical power that isn't equal to 50%.

### Ask: “Have the authors interpreted the statistics in a meaningful way?”

One of the reasons that regression analysis is so ubiquitous is that the quantitative results of the regression, the correlations, are unitless values.  They describe ratios, not measurements, so they don't need the descriptive units that measurements require, like meters, or dollars, or preference ratings, etc.  This lack of units makes is easier to compare results from two experiments, because as long as the experiments measured the same fundamental construct, it doesn't matter how it was measured.  In other words, if two experiments both measured, say, length as one of the variables, it doesn't matter if one reported “meters” and the other reported “hands”.  The results of the respective regressions will be unitless, and therefore you could directly compare them.

But, the lack of units becomes a problem when you want to make precise comments about outcomes.  It's not helpful to know what the relationship of two regressions is, if what you want to know is the size of effect that either, or both, of the independent variables in those  two respective regressions will have on some outcome.  A simplistic analogy is: If you don't know how much an apple cost, and you don't know how much an orange cost, it's of no use when planning your budget to know that an apple costs less than an orange.

If the results in a paper are never discussed in terms of practical application, if the numbers are never tied to units that measure real-world objects/phenomena, then as a manager you can really only apply the results in a qualitative, not a quantitative, way.

### Ask: “What is the size of variation in the outcome?”

The inputs can never explain more than 100-percent of the variation in the outcome.  If the complete range of variation in the outcome doesn't comprise an important amount of change, than you can't directly report that the correlation is an important one.  Even if the correlation is very strong, in order to interpret it as being important, the researcher must make the case that there is good reason to believe that the correlation is linear from the studied range out across a range of variation in outcome that would important. 

# How to report empirical studies in management literature

## A research article should include the answers to the questions that managers will ask

If you are a researcher writing an article that reports the results of a regression analysis of empirical data, what information should you include if you want your article to be relevant to managers?  You should, at a minimum, include the information a manager would need to answer the questions outlined in the previous section.  So, the recommendations here are answers to the recommend questions in that section.

### For the question: “Are the authors using the word ‘significant’ to mean ‘important’, and is that use justified?”

In all but the final draft of a paper, never the word “significant” or “significance” without attaching the word “statistically” or “statistically” to it.  When you're revising a paper, highlight every use of “significant” or “significance” and the associated use of “statistically” or “statistically”.  That may sound like a ridiculous, elementary-school-like exercise, but if you want to avoid ambiguity in the understanding of managers who may read the paper, it is important to avoid any possible confusing between statistical significance and practical importance.

### For the question: “What was the statistical power of the analysis?”

If you didn't target a specific statistical power in the design of your statistical analysis, it's often easier to address this question after you have dealt with the following one, in which you will interpret the results of the analysis into practical terms.  Because once you understand the results in practical terms, you can establish a cut-off for the size of effect that should be included in your analysis.

Then, the value for the correlation that you use when calculating the statistical power, is not the correlation you found, or the one you expected to find, but rather that cut-off value, representing the smallest correlation that would be included as important enough to report on.

(In terms of the splayed probability graph, setting the cut-off is like setting the population curve?)

### For the question: “Have the authors interpreted the statistics in a meaningful way?”

Remember that this question is being asked by a practitioner, by an actual manager of a firm.  So, a meaningful interpretation is this context is one that would help a manager to either make a decision, or to understand what the manager observes happening.

The first step in this is to convert the regression results into terms that a manger can understand and use, often in one of two ways.  The first way is quantitative, where you translate the regression analysis results from unitless values into values with units with which a manager would be accustomed e.g., US dollars.  The second way is qualitative, where the results are explained in a binary way, e.g., “increasing” vs. “decreasing”, “success” vs. “failure”, [[ETCETCETC]]

From there you can establish some context for the results, explain the size of effect that your regression results represent in terms of strategic management, and justify the cut-off for importance that you applied to determine the statistical power of your analysis, or that you used to design your experiment.

### For the question: “What is the size of variation in the outcome?”

If you interpret the result in a qualitative way, this question becomes trivial.  But if your meaningful interpretation of the results was quantitative, then considering the range of outcome variation becomes important, yet easy to overlok.  If you normalize your data, it becomes especially easy to forget to consider the range of outcomes in your data in regard to the range of all possible outcomes, because you are artificially setting that entire range of possible variation approximately equal to the variation in your data.

Part of the process of meaningful interpretations will remove that artifice, denormalizing the data.  Then you can put the outcomes back into context, and discuss the range of outcomes in the data in relation to the outcomes that a manager might encounter in actual practice.









