---
title: "On the details of storing data in DNA"
---

This Economist article explains the DNA data storage scheme from [this paper](http://www.nature.com/nature/journal/vaop/ncurrent/full/nature11875.html):

> Previous approaches have often mapped the binary 1s and 0s used by  computers directly onto these bases. For instance, A and C might  represent 0, while G and T signify 1. The problem is that sequences of  1s or 0s in the source code can generate repetition of a single base in  the DNA (say, TTTT). Such repetitions are more likely to be misread by  DNA-sequencing machines, leading to errors when reading the information  back. The team’s solution was to translate the binary computer information  into ternary (a system that uses three numerals: 0, 1 and 2) and then  encode that information into the DNA. Instead of a direct link between a  given number and a particular base, the encoding scheme depends on  which base has been used most recently.

Very clever. Besides the 17 bases of indexing and parity check information per fragment, the dependence on the previous base is supposed to work like that [damned SoLiD colourspace](http://marketing.appliedbiosystems.com/images/Product_Microsites/Solid_Knowledge_MS/pdf/CSHL_Fu.pdf) sequencing format. Anyone who's had the pleasure of working in colourspace knows how frustrating it is to read.

But the difficulty in decoding this information yields a problem that actually works for you: if an alteration or misread of a base is encountered when recovering information in this format, you can't decode beyond it. It also means that if you can read the sequence completely, you're more confident that the data is accurate. When reading data from DNA, I suspect you'd have to throw away this misread DNA fragment, which doesn't really matter since you've sequenced many redundant fragments in the first place.





