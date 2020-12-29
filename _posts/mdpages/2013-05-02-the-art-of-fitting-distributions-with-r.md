---
title: "The Art of Fitting Distributions With R"
---

Here's some [good advice on fitting distributions](http://lamages.blogspot.ca/2011/12/fitting-distributions-with-r.html) using R from Marcus Gesmann, a mathematician involved in the analysis of insurance markets. He makes it clear that it's a bit of an art:

> Suppose I have only 50 data points, of which I believe that they follow a log-normal  distribution. How much variance can I expect? Well, let's experiment. I  draw 50 random numbers from a log-normal distribution, fit the  distribution to the sample data and repeat the exercise 50 times and  plot the results using the plot function of the fitdistrplus package.


> I notice quite a big variance in the results. For some samples other  distributions, e.g. logistic, could provide a better fit. You might  argue that 50 data points is not a lot of data, but in real life it  often is, and hence this little example already shows me that fitting a  distribution to data is not just about applying an algorithm, but  requires a sound understanding of the process which generated the data  as well.

He also republished a handy guide for deciding what distribution your data might belong to, taken from *[Probabilistic Approaches to Risk](http://www.stern.nyu.edu/%7Eadamodar/pdfiles/papers/probabilistic.pdf)*by[Aswath Damodaran](http://pages.stern.nyu.edu/%7Eadamodar/). 

