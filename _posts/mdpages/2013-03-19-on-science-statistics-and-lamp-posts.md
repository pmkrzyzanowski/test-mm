---
title: "On Science, Statistics, and Lamp-posts"
---


> "An unsophisticated forecaster uses statistics as a drunken man uses lamp-posts - for support rather than for illumination." - Andrew Lang

 I first heard this quote a few weeks ago at AGBT, describing an unsophisticated scientist for the sake of the audience.

The gist of the talk was to explore how high-throughput sequencing of RNA can help discover alternative forms of a gene that happens to be a drug target - this is particularly important as the alternative forms might bind the drug target poorly, or not at all. The speaker emphasized that statistics, particularly when dealing with big data like genomic sequencing, should be designed and used very carefully and that users need to be aware of what stats can tell you, what they can't, and when obsessing about the right statistics to use isn't worthwhile. 

Most importantly, she criticized the use of stats used to lend significance to an already obvious conclusion. If two observations are really that different, a t-test to hammer home the message with a P-value of 10<sup>-167</sup> is overkill, especially if it's part of a series of experiments that close the book on the statistical question in the next figure.

Using stats for the wrong purposes can also raise a red flag for people reviewing your work, for if the test you've used isn't appropriate for your data, it can mean two things: you weren't aware of the right test to use (which is ok), or you don't really care and your stats are just for show (which is not).

In the end, it's better to use rely on statistics to help guide questions than to 'prove' something that's already self evident in the data you're communicating.
