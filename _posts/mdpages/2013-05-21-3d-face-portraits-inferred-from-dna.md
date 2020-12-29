---
title: "3D Face Portraits Inferred from DNA"
---

Smithsonian Mag writes about Heather Dewey-Hagerborg's work in [facial rendering using genomic infomation](http://blogs.smithsonianmag.com/artscience/2013/05/creepy-or-cool-portraits-derived-from-the-dna-in-hair-and-gum-found-in-public-places/):

> The 30-year-old PhD student, studying electronic arts at Rensselaer  Polytechnic Institute in Troy, New York, extracts DNA from each piece of  evidence she collects, focusing on specific genomic regions from her  samples. She then sequences theseregionsand enters this datainto a  computer program, which churns out a model of the face of the person who  left the hair, fingernail, cigarette or gum behind.


<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody><tr><td style="text-align: center;"><img src="http://deweyhagborg.com/strangervisions/images/_sample2_face_web.jpg" height="266" style="margin-left: auto; margin-right: auto;" width="400" /></td></tr><tr><td class="tr-caption" style="text-align: center;">Image from Dewey-Hagerborg's "Stranger Visions"</td></tr></tbody></table>
The comments in the Smithsonian article are plentiful but fall into a few categories, ranging from those firmly against the approach to many that doubt the program's accuracy. I'm not convinced, either, after seeing the comparison of [Manu Sporny's 3D image](http://deweyhagborg.wordpress.com/2012/07/17/manu-sporny/) (though the image of [Kurt Anderson's 25 year old equivalent](http://www.studio360.org/2013/feb/08/making-portraits-out-of-dna/) is pretty good). Then again, it's portrayed as art, not a highly accurate system to generate faces from DNA.

I was also left wondering about what data her method was based on, as the Smithsonian only mentioned a lab returning "about 400 base pair sequences" (Sanger sequencing?) and "about 40 or 50 different traits" that the artist is currently considering, which I thought to be SNPs. 

In a blog posting last year, Dewey-Hagerborg explained [the method "Stranger Visions" is based on](http://deweyhagborg.wordpress.com/2012/07/09/stranger-visions-software/) in more detail:

> I have worked with facial recognition algorithms in the past and one  technique I had read about was the use of a morphable 3d facial model to  attempt to recognize faces at weird angles. As I have previously  turned systems like this, intended for surveillance, into systems for  creativity, it naturallyoccurredto me that the same system could be  used to generate faces. And if you can determine what correlates certain  types of faces you can then generate faces with those characteristics  using principal components analysis.
It turns out the research group behind the Basel Morphable Model  realized this as well and after much digging I figured out how to use  their matlab model as a starting point for many different types of  parameters. They had already found the primary axes for gender, age and  weight so the main parameter missing was ethnicity.

Further on in that article, she also explains how she expanded the training data set of images to encompass a more diverse set of ethnicities to better reflect the composition of the United States. Nevertheless, it still leaves the following process in my mind: DNA --&gt; SNPs --&gt; Ethnicity --&gt; Facial Features.

Without seeing more of the code used to fit the models, I have to assume that the fairly subjective parameter of 'ethnicity' sits in the middle of the information flow. The method could be dramatically improved by eliminating 'ethnicity' from the workflow by using a bigger and better set of data that correlates SNPs to facial features directly.

I'm not aware of any data sets that offer that, but I wouldn't be surprised to see it done in the next few years. As there are apparently only <a href="http://journals.lww.com/jcraniofacialsurgery/pages/articleviewer.aspx?year=2011&amp;issue=05000&amp;article=00082&amp;type=abstract" target="_blank">14 different kinds of noses</a>, deeper knowledge of genetics would yield a more objective predictor of facial features.
