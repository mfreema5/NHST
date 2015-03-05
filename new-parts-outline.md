# Outline/notes &ndash; new sections only


# Intro
## Purpose of doc

([*hypothetical example here*](./hypothetical-example.md))

## Conventions of the doc

Because of the purpose and context… we'll use some specific terms in place of the general terms used in pure statistics.  dependent →outcome, independent →input, …


## Outline the doc

First we'll look at how a statistically significance result can be either important or trivial, and to further explain what it is that statistical significance measures, we'll discuss Type I and Type II errors, specifically in relation to correlation analyses.

Then, given our renewed understanding of statistical significance, we'll discuss why bigger isn't always better when it comes to data. One of the specific problems covered will be how using big data can obscure important results with trivial ones.  A related issue is the failure of authors to interpret the results of regression analyses of big data, which increases the difficulty of finding the important results among the larger number of trivial ones.

After a brief section on why this distinction between important and trivial effects is particularly important to management studies, we will give some guidelines for both how to read and how to report the correlation analysis results of empirical studies in management.

# Confusing "Significant" and "Important"


## What does “statistical significant” actually mean?

If the cut-off for what qualifies as statistically significant is a variable we can set, why not just set it low enough that everything qualifies?

## What does “important” mean, in relation to “statistical significant”


Correlations and stati





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










## Type I errors – Mistaking shrubs for trees

## Type II errors – Missing forest for trees




----

**(stuff from previous draft here)**

----

# How to read empirical studies in management literature

## How should a manager critically evaluate a research article?

If you are a strategic manager, what questions should you be asking as you read an academic research article that reports statistical results from a regression analysis?  A good place to start is with the questions that Lockett, *et al.*, [CITATION] asked as part of their survey of papers [WHERE? WHEN?].  They asked [WHAT?  {reporting statistical power}, {implying significant means important}, {reporting size of effect}, {interpreting results} {???} ]

In the following sections we'll look in detail at those and other questions, to explain how they are useful, when they apply, and what you can infer about an article based on the answers to them.

### Ask: “Are the authors using the word ‘significant’ to mean ‘important’, and is that use justified?”

This question can be tricky because, of course, the word “significant” often does mean “important”, when it has been uncoupled from “statistically”. So, whenever the term “significant” is used, you should pause and ask yourself, “Are they talking about the statistics, or the effect?”  Are they making a statement about the mere existence of a correlation, or about the relative size of effect of that correlation on outcomes?  In other words, have the authors conceptually decoupled it from “statistical”, or is the word still implicitly there, modifying the “significance” of the result?

In their survey, Lockett, *et al.*, [CITATION], found that a worrisome [PERCENTAGE] of articles were using the term “significant” to imply importance, even though what they were referring to was the statistical significance of the result.

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








