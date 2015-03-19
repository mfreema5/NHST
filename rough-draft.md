# Introduction &ndash; Confusing "Significant" and "Important"

In the management research literature, it is important to understand that in the term &ldquo;statistically significant,&rdquo; the word &ldquo;significant&rdquo; doesn't mean the same thing as &ldquo;important.&rdquo;  When a correlation result from a regression analysis is described as &ldquo;statistically significant&rdquo;, it means that the probablility that the result is an accident of random variation has been precisely determined, and that the chances are lower than some defined minimum.

That defined minimum is identified by &ldquo;alpha;&rdquo;, also called the &ldquo;confidence level.&rdquo;  E.g., a confidence level of 95% is the same as &alpha; = 0.05, or &ldquo;p<.05&rdquo;, and means there is a 5% chance of error.  So, a statistically significant result, at a 95% confidence level, has a 5% or less probablity of being incorrect.

For a regression analysis, reporting that a result is &ldquo;statistically significant&rdquo; means that the proposed correlation can be shown to exist in the data.  However, it says nothing about how important that correlation is.  A correlation which is statistically significant is not necessarily significant in importance.

>Concern about the statistical significance of effects (whether they exist at all) has tended to preempt attention to their magnitude. ... Although not unrelated, the size and statistical significance of effects are logically independent features of data from samples.  Yet many research reports, at least implicitly, confuse the issues of size and statistical significance, using the latter as if it meant the former. (Cohen and Cohen, 1975, p6)

However, another output from a regression analysis, the magnitude of the effect size for the correlation, can often be indicative of that correlation's importance.  And yet, in the papers surveyed by [**CITE**], 92% fail to discuss the magnitude of the coefficients at all.  Instead, 93% used statistical significance as the only criterion for the importance of a result.  And, unsurprisingly, in 97% of the papers, the conclusions are also solely based on statistical significance.

In nearly all of the papers in that survey&mdash;98%&mdash;the term &ldquo;significance&rdquo; is used in an ambiguous manner.  No clear distinction is made between statistical significance and other types of significance.  As Cohen and Cohen described above, in most cases statistical significance is implicitly used to mean &ldquo;important&rdquo;.

## Purpose of doc

If managers are going to be able to use relevant research from academia as part of the process of making strategic decisions, they need to be able to figure out what research actually is relevant.  While all the empirical studies they may find in the management literature will report statistically significant results, they won't necessarily be useful for making management decisions.  While the inputs and outputs analyzed by an empirical study may be relevant, that is not sufficient to establish that a study is relevant to a real-world decision. The way that researchers interpret and present the results may impede, if not completely obscure, the implications of those results for real-world decision-making.  And the results themselves, while statistically significant, may in the end describe too small of an effect to be worth a manger's effort to pursue.

This article aims to address that issue&mdash;identifying the potential utility of academic research in practical application&mdash;from both directions, discussing both how to read research articles and evaluate their potential practical utility, and how to write research articles in a way that increases their potential practical utility.

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

That example may be cartoonish, but it illustrates a real problem: real-world managers don't get the answers they need from management research.  Because, while the PhD candidate in the scenario was probably correct that the result of their analysis was &ldquo;very significant&rdquo; from a statistical point of view, that same result was of no use at all to a manager trying to make a specific decision.

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

And while similar disparate outcomes can always happen at the margin, this bias to larger sample size is not a marginal effect.  For illustration, consider that in the papers surveyed [by Locket **CITE**], sample size ranged from under 50 to over 1500.  Since the ratio of two ‘t’ values is effectively equal to the ratio of the sample sizes, the ‘t’ value for a correlation in a study with 1500 data points would be 30 times larger than the ‘t’ value for an equivalent correlation in a study with 50 data points.  In other words, the size of an effect in the former study could be 30 times smaller than a size of an effect in the latter, but be of equal “statistical significance.”

In an editorial in the *Academy of Management Journal*, Combs proposed that the increasing availability of large data sets coupled with the ease of performing null-hypothesis significance testing afforded by modern computers and software would combine to:

>…mask other shortcomings of our research designs and leave us with itty-bitty effect sizes that limit the relevance of our research. …As management scholars, can we really suggest that managers should change their decision calculus on the basis of knowledge that some new variable explains .0025 percent of the variance in organizational performance? (Combs 2010)

Combs went beyond merely speculating about a shift toward larger data sets with smaller effects, and did some comparisons between studies published in the 1987-89 volumes and in the 2007-8 volumes of the *Academy of Management Journal*.  During that 20-year period, the mean sample size rose from 300 to 3,423 (excluding the three largest samples from the later period that, if included, would raise the latter mean to a whopping 7,578).  At the same time, the mean correlations fell from `.22`, to `.17` (Combs 2010).  So, as expected, the ever larger sample sizes made ever smaller correlations statistically significant.

### How significance obscures importance

As an added difficulty to finding research that is relevant for real-world decisions by strategic managers, the shift toward larger and larger data sets in research quietly introduces a bias against important results&mdash;which are the results in which strategic mangers are interested.

While correlations of large magnitude will be statistically significant when studied through both large and small data sets, correlations of small magnitude will only be significant when studied through large data sets.  So, while a move to larger data sets doesn't increase the number of correlations of large magnitude that are published, it does increase the number of correlations of small magnitude that are published.  Therefore, the ratio of large magnitude correlations to small ones will decrease. Since the importance of a correlation is often indicated by its magnitude, and is not really tied to its statistical significance, the ratio of important to trivial correlations will also decrease.

As the literature becomes saturated with more and more empirical studies of large data sets, it becomes more and more valuable to be able to be able to separate the important results from the general pool of published results.

# How to read empirical studies in management literature

## What questions should a manager asks while reading a research article?

If you are a strategic manager, what questions should you be asking as you read an academic research article that reports statistical results from a regression analysis?  A good place to start is with the questions that Lockett, *et al.*, [CITATION] asked as part of their survey of papers [WHERE? WHEN?].  They asked [WHAT?  {reporting statistical power}, {implying significant means important}, {reporting size of effect}, {interpreting results} {???} ]

In the following sections we'll look in detail at those and other questions, to explain how they are useful, when they apply, and what you can infer about an article based on the answers to them.

### Ask: “Are the authors using the word ‘significant’ to mean ‘important’, and is that use justified?”

This question can be tricky because, of course, the word “significant” often does mean “important”, when it has been uncoupled from “statistically”. So, whenever the term “significant” is used, you should pause and ask yourself, “Are they talking about the statistics, or the effect?”  Are they making a statement about the mere existence of a correlation, or about the relative size of effect of that correlation on outcomes?  In other words, have the authors conceptually decoupled it from “statistical”, or is the word still implicitly there, modifying the “significance” of the result?

In their survey, Lockett, *et al.*, [**CITATION**], only 5% of the studies surveyed correctly interpreted the magnitude of effect size of the identified correlations.  In the other 95% of papers, while the value of "r" for each correlation was reported, it was not interpreted as to the importance of that correlation.  All the correlations are either implicitly of equal importance, or the reader is left to erroneously infer their importance from the statistical significance.

### Ask: “What was the statistical power of the analysis?”

Statistical power is related to the probability of a Type II error&mdash;that is, to the chance of failing to see a correlation that does exist.  However, what makes statistical power a good way to evaluate the overall utility of an empirical study is not the actual value reported for statistical power, but rather whether or not it was reported at all.

Unlike statistical significance, calculating the statistical power of an analysis often requires interpretation of, or at least a judgement about, the nature of the effects that the study is examining.  This is because one of the variables you need to calculate statistical power is the minimum correlation that you are interested in.  

There are two ways to decide what size of correlation is too small, and what size is big enough, to be included in the results.  One is to base the minimum on an estimation of what those correlations mean in terms of outcomes.  The other is to base it on the size of effects that previous research has reported.  But, of course, that second method doesn't eliminate the interpretation of, or judgement about, the nature of the effects involved&mdash;it merely shifts the task onto the researchers behind the previously published research.

So, if the statistical power is reported someone, somewhere, at some point, has indeed considered the potential importance of the results of the analysis, and has drawn a line between the potentially important and the probably trivial sizes of effect.

Lockett, *et al.*, [CITATION], found in their survey that only [PERCENTAGE] of papers reported statistical power.  While the authors of the papers that didn't report statistical power probably did consider the relative importance of the results they were reporting, we can't be as confident about them doing that as we can about the the authors who did report statistical power.

### Ask: “Have the authors interpreted the statistics in a meaningful way?”

One of the reasons that regression analysis is so ubiquitous is that the quantitative results of the regression, the correlations, are unitless values.  They describe ratios, not measurements, so they don't need the descriptive units that measurements require, like meters, or dollars, or preference ratings, etc.  This lack of units makes is easier to compare results from two experiments, because as long as the experiments measured the same fundamental construct, it doesn't matter how it was measured.  In other words, if two experiments both measured, say, length as one of the variables, it doesn't matter if one reported “meters” and the other reported “hands”.  The results of the respective regressions will be unitless, and therefore you could directly compare them.

But, the lack of units becomes a problem when you want to make precise comments about outcomes.  It's not helpful to only know what the relationship of two regressions is, if what you need to know is the size of effect that either, or both, of the independent variables in those two respective regressions will have on some outcome.  A simplistic analogy is: If you don't know how much an apple cost, and you don't know how much an orange cost, it's of no use for planning a budget to know that an apple costs less than an orange.

If the results in a paper are never discussed in terms of practical application, if the numbers are never tied to units that measure real-world objects/phenomena, then as a manager you can at best apply the results in a qualitative, and not in a quantitative, way.

### Ask: “What is the size of variation in the outcome?”

The inputs can never explain more than 100-percent of the variation in the outcome.  If the complete range of variation in the outcome doesn't comprise an important amount of change, than you can't directly report that the correlation is an important one.  

It is possible to extrapolate, for example, a very strong correlation from a small to a large range of variation in outcome, and make the case that the correlation is therefore an important one.  But researchers should be clear about when they are doing this, and should address some of the pitfalls in doing so, e.g., they should discuss how the error in the result increases the farther it is extrapolated from the data.

# How to report empirical studies in management literature

## A research article should include the answers to the questions that managers will ask

If you are a management researcher reporting the results of a regression analysis, what information should you include if you want your article to be relevant to managers?  You should, at a minimum, include the information a manager would need to answer the questions outlined in the previous section.  So, the recommendations here are some of the ways you might answer the recommend questions in that section.

### For the question: “Are the authors using the word ‘significant’ to mean ‘important’, and is that use justified?”

In general, **never** the word “significant” or “significance” without attaching the word “statistically” or “statistically” to it.  When you're revising a paper, highlight every use of “significant” or “significance” and the associated use of “statistically” or “statistically”.  That may sound like a ridiculous, elementary-school-like exercise, but if you want to avoid ambiguity in the minds of managers who read the paper, it is important to avoid any possible confusion between statistical significance and practical importance.

When you use “important” you should be able to justify that use, with something other than a estimate of error.  A lack of error does not bestow importance.  You needn't couch every implication or use of “important” in a justification, but the importance of a result should be  explicitly explained somewhere in the paper.

### For the question: “What was the statistical power of the analysis?”

If you designed your statistical experiment from the ground up, you probably already know what the statistical power was, because that was something you used to do the design.  Just be sure to report it, and to report it as having been part of the initial design.

If you didn't target a specific statistical power in the design of your statistical analysis, then it will likely be easier to address this question after you have dealt with the following one in which you will interpret the results of the analysis in practical terms.  You can, once you understand the results in practical terms, establish a cut-off for the size of effect that would be worth finding, and use that as the effect size&mdash;along with the confidence level, and the sample size&mdash;to calculate the statistical power.

Avoid simply using the smallest correlation you found, or the size of effect that you expected to find.  The latter is typically used when designing an experiment, the former is often used when a researcher can't be bothered to determine if the result is or isn't trivial.

### For the question: “Have the authors interpreted the statistics in a meaningful way?”

Remember that this question will be asked by a practitioner, by an actual manager of a firm.  So, a meaningful interpretation is this context is one that would help a manager either to make a decision, or to understand what the manager observes happening.

The first step in this is to convert the regression results into terms that a manger can understand and use, typically in one of two ways.  The first way is quantitative, where you translate the regression analysis results from unitless values into values with units with which a manager would be accustomed e.g., US dollars.  The second way is qualitative, where the results are explained in a binary way, e.g., “increasing” vs. “decreasing”, “success” vs. “failure”, [[ETCETCETC]]

From there you can establish some context for the results, explain the size of effect that your regression results represent in terms of strategic management, and justify the cut-off for importance that you applied to determine the statistical power of your analysis, or that you used to design your experiment.

### For the question: “What is the size of variation in the outcome?”

If you interpret the result in a qualitative way, this question isn't really applicable.  But if your meaningful interpretation of the results was quantitative, then considering the range of outcome variation becomes important, yet easy to overlook.  If you normalize your data, it becomes especially easy to forget to consider the range of outcomes in your data in regard to the range of all possible outcomes, because you are artificially setting that entire range of possible variation essentially equal to the variation in your data.

Part of the process of meaningful interpretations will remove that artifice, denormalizing the data.  Then you can put the outcomes back into context, and discuss the range of outcomes in the data in relation to the outcomes that a manager might encounter in actual practice.









