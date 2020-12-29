---
title: "From Gene Symbols To Financial Crises, Excel is There"
---

Here's a thing that economists could have learned from computational biologists: Silly mistakes with Microsoft Excel can have a serious impact on your work.

In an op-ed at The New York Times, Paul Krugman shares the story of how a [flawed Excel formula ](http://www.nytimes.com/2013/04/19/opinion/krugman-the-excel-depression.html)contributed to a paper being published by Carmen Reinhart and Kenneth Rogoff stating that debt-to-GDP ratios above 90% contribute to <a href="http://www.nber.org/papers/w15639.pdf?new_window=1" target="_blank">much slower economic growth</a> and became ammunition for anyone ideologically bent on cutting government spending, for whatever reason. Krugman, to his credit, is an author of popular books on economics like '<a href="http://www.amazon.com/gp/product/0393345084/ref=as_li_ss_tl?ie=UTF8&amp;camp=1789&amp;creative=390957&amp;creativeASIN=0393345084&amp;linkCode=as2&amp;tag=thechecscie0c-20">End This Depression Now!</a>'<img alt="" border="0" src="http://www.assoc-amazon.com/e/ir?t=thechecscie0c-20&amp;l=as2&amp;o=1&amp;a=0393345084" height="1" style="border: none !important; margin: 0px !important;" width="1" /> and '<a href="http://www.amazon.com/gp/product/B004J8HXGS/ref=as_li_ss_tl?ie=UTF8&amp;camp=1789&amp;creative=390957&amp;creativeASIN=B004J8HXGS&amp;linkCode=as2&amp;tag=thechecscie0c-20">The Conscience of a Liberal'</a>, which you may have read if you follow him.

Krugman points out that the problem with the Reinhart-Rogoff paper didn't really surface until the financial research community attempted to replicate the results, but couldn't manage to do: 

> Other researchers, using seemingly comparable data on debt and growth, couldn’t replicate the Reinhart-Rogoff results. They typically found some correlation between high debt and slow growth — but nothing that looked like a tipping point at 90 percent or, indeed, any particular level of debt. 


> Finally, Ms. Reinhart and Mr. Rogoff allowed researchers at the University of Massachusetts to look at their original spreadsheet — and the mystery of the irreproducible results was solved. First, they omitted some data; second, they used unusual and highly questionable statistical procedures; and finally, yes, they made an Excel coding error. 

Whether or not their intentions to omit data or use unusual statitstical procedures is another subject, but it's clear that misuse of Excel was clearly found to be one of the culprits.

Which brings me back to biology. Why does Excel change gene symbols to dates?

During my PhD, my group sometimes used Excel to format tables for presentations or reports, and we quickly found gene symbols that were automatically converted into dates or scientific notations. The solution at that point was to fix them by manually escaping the field with an apostrophe as a prefix to that Excel would know to treat the cell as text. So "DEC1" became "'DEC1" prior to importing the data. Shortly after we realized that this was a prevalent problem in the field, we considered writing a short paper on it but deemed it too trivial for a paper.

[Behold](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC459209/), a few months later, someone publishes a paper on the very same topic in *BMC Bioinformatics*. "[Mistaken Identifiers](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC459209/): Gene name errors can be introduced inadvertently when using Excel in bioinformatics" summarizes the problems nicely with Table 1 in the paper:

<div class="separator" style="clear: both; text-align: center;">[](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC459209/bin/1471-2105-5-80-1.jpg)</div>
You can see that the Septins, the OCTs (Octamer-binding transcription factors), Deleted in Esophageal Cancer (DEC1 and DEC2) genes, and a few others are affected when converted to date format.

Symbol changes generally don't become a huge problem <b>as long as the data isn't being exported</b> and run through software that uses the gene symbols, but you can appreciate how manipulating biological spreadsheets in Excel can be a pain, especially if one isn't aware that escape characters can be used, or let alone what escape characters are.

Moral of the story: It's important to double and triple check your work at each step of the way, otherwise minor coding errors might affect important things like gene lists or government policies!



