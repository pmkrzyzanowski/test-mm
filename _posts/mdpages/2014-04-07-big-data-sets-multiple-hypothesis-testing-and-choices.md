---
title: "Big Data Sets, Multiple Hypothesis Testing, and Choices"
---

Jason McDermott, at The Mad Scientist's Confectioners Club [writes](http://jasonya.com/wp/the-false-dichotomy-of-multiple-hypothesis-testing/):

> Here’s where the problem of a false dichotomy occurs. Many researchers  who analyze large amounts of data believe that utilizing a  hypothesis-based approach mitigates the effect of multiple hypothesis  testing on their results. That is, they believe that they can focus  their investigation of the data to a subset constrained by a  model/hypothesis and thus reduce the effect that multiple hypothesis  testing has on their analysis. Instead of looking at 10,000 proteins in a  study they now look at only the 25 proteins that are thought to be  present in a particular pathway of interest (where the pathway here  represent the model based on existing knowledge). ... All well and  good EXCEPT for the fact that the actual chance of detecting something  by random chance HASN’T changed.

The article in its entirety is a good read, especially in describing the use of big data sets as a balance between hypothesis-driven projects and discovery-driven ones. The former can loosely be described as "research" in it's <a href="http://www.etymonline.com/index.php?term=research" target="_blank">classical sense</a>, while the latter is sometimes derided as "a fishing expedition". Both approaches can be useful, as long as you're honest with yourself and know what you're dealing with.

But the quote above isn't exactly accurate. In the hypothetical 10,000 protein experiment, the chance of detecting any *one thing *as significant is the same whether you're looking at a subset of 25 or 250. Given that constant random probability, the chance of finding *anything* significant is much greater in the whole set of 10,000 as compared with 25. That 10,000 protein data set is where multiple testing is drastically needed. You still need correction with 25 but you usually simple methods are adequate. Picking the right way to correct your results is tricky, as I've seen large experiments designed as a fishing expeditions fail to detect known, real effects in the data set with statistical significance, even after multiple testing correction is done.

So if you know what you're looking for and have a specific question in mind, you can make multiple hypothesis testing work for you. You won't have your big data set dilute away all your interesting observations.

Having something very specific to act on also means you're less likely to be fooled by chance and drawn down a path that's "significant". You're free to restrict your observations to a more specific set of data and choose to look at any set of measurements based on the question at hand, and not the other way around.

Of course, making the decision to ask a specific question should be made before seeing the data in it's entirety, not after the fact when something "looks good", but that's a whole other issue altogether.
