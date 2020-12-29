---
title: "Predicting Causes of Drug Side Effects"
---

Why do some drugs cause side effects?

A group of computational led by Peer Bork just published a paper in Molecular Systems Biology describing [how to predict the causes of undesirable drug side effects](http://www.nature.com/msb/journal/v9/n1/full/msb201310.html) by integrating drug-to-target and drug-to-side effect relationships and asking which protein targets are the most likely cause of the side effect:

> For more than half of the investigated side effects, we can predict  which proteins cause the side effects upon perturbation by a marketed  drug. For the majority of these proteins, we also predict whether their  activation or inhibition causes the side effect.

The paper includes a pretty elegant proof of principle using a mouse experiment.

The group predicted that  increased sensisitivity to pain, one side effect of triptan based migraine medications, was likely caused by off-target activation of serotonin receptors, specifically HTR7. They confirmed that treating mice with [zolmitriptan](http://en.wikipedia.org/wiki/Zolmitriptan) (Sold as Zomig or Zomigon by AstraZeneca) increased their pain sensitivity and then showed the effect could be reversed by the [SB-269970](http://en.wikipedia.org/wiki/SB-269,970) serotonin receptor inhibitor.

The next level of prediction would be to know which individuals are sensitive to these side effects and which ones are not, probably based on the variations they carry in the side-effect targets.
