# History

-

[![Photograph of statues of Newton and Leibniz](./images/newton_leibniz.jpg) <!-- .element: width="1000px" -->](https://commons.wikimedia.org/wiki/File:Statues_of_Isaac_Newton_and_Gottfried_Leibniz.jpg)

-

![Photograph of the Royal Society's premises in Crane Court](./images/rs.jpg) <!-- .element: width="700px" -->

-

Process $\rightarrow$ Data $\rightarrow$ Analysis $\rightarrow$ Results

-

![Photograph of a supercomputer](./images/supercomputer.jpg) <!-- .element: width="1200px" -->

-

![Screen shot of a lot of code in very small font, filling the screen](./images/lots_of_code.png) <!-- .element: width="1800px" -->

-

<!--Process $\rightarrow$ ⬛ $\rightarrow$ 🪄 $\rightarrow$ ✨Results✨-->

![Process to black box to magic wand to very sparkly results](./images/process-sparkles.png) <!-- .element width="550px" -->

-

_An article about computational science in a scientific publication is **not** the scholarship itself, it is merely **advertising** of the scholarship. The actual scholarship is the complete software development environment and the complete set of instructions which generated the figures._

&mdash;[attributed to Jon Claerbout, around 1995](https://statweb.stanford.edu/~wavelab/Wavelab_850/wavelab.pdf)

-

![Graph showing the exponential growth in publications from 1650 to 2012](./images/publications.png) <!-- .element: width="800px" -->

[Bornmann and  Mutz, 2015, 10.1002/asi.23329](https://doi.org/10.1002/asi.23329)

-

![Screen shot of the access charges for the article linked on the previous slide ($49 for a PDF)](./images/access_charges.png)<!-- .element: width="700px" -->

---

# Definitions

-

## Reproducibility

<span class="fragment fade-in" data-fragment-index="1">Same data</span>
<span class="fragment fade-in" data-fragment-index="2">$+$ same analysis</span>
<span class="fragment fade-in" data-fragment-index="3">$\rightarrow$ Same results</span>

<span class="fragment fade-in" data-fragment-index="4">(from [The Turing Way project](https://the-turing-way.netlify.app/reproducible-research/overview/overview-definitions.html))</span>

-

## Replicability

New data $+$ same analysis $\rightarrow$ Same results

<br>

## Robustness

Same data $+$ new analysis $\rightarrow$ Same results

-

## Open Science

The movement to make all research accessible to all levels of society.

![Papers](images/paper.jpg) <!-- .element width="200px" -->&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Experimental Samples](images/test_tube.jpg) <!-- .element width="200px" -->](https://www.publicdomainpictures.net/en/view-image.php?image=302908&picture=filling-up-the-test-tube)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Code](images/photo_of_code.jpg) <!-- .element width="200px" --> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![Data](images/photo_of_data.jpg) <!-- .element width="200px" -->

-

## FAIR

Data and software should be:

 * **F**indable
 * **A**ccessible
 * **I**nteroperable
 * **R**eusable

---

# Case studies

-

[![Screen shot of the article "the war over supercooled water"](./images/supercooled-water.png) <!-- .element width="1000px" -->](https://physicstoday.scitation.org/do/10.1063/pt.6.1.20180822a/full/)

-

[![Screen shot of the article "FAQ: Reinhart, Rogoff, and the Excel Error That Changed History"](./images/reinhart-rogoff.png) <!-- .element width="700px" -->](https://www.bloomberg.com/news/articles/2013-04-18/faq-reinhart-rogoff-and-the-excel-error-that-changed-history)

-

[![Screen shot of the article "Microsoft Excel blamed for gene study errors"](./images/excel-gene.png) <!-- .element width="700px" -->](https://www.bbc.co.uk/news/technology-37176926)

-

<!--Process $\rightarrow$ ⬛ $\rightarrow$ 🪄 $\rightarrow$ 💩-->

![Process to black box to magic wand to pile of poo](./images/process-poo.png) <!-- .element width="500px" -->

-

[![Image of a tweet reading "Another reminder: reviewers and editors need to insist that software be placed in a permanent repository. Not author's web site. Not GitHub.", quoting a second reading "Anyone know where to find the xenograft read detecting software Xenome? Link on the paper is dead."](images/code_archive_tweet.png) <!-- .element:  width="800px" -->](https://twitter.com/michaelhoffman/status/796103749068529667)

-

[![Graph showing the importance of research software to researchers](./images/hettrick-importance.png) <!-- .element width="600px" --> &nbsp;&nbsp;&nbsp;&nbsp;![Graph showing the estimated expertise of researchers](./images/hettrick-expertise.png) <!-- .element width="600px" -->](https://slides.com/simonhettrick/software-risks-reproducibility-and-sustainability)

(from [Software Survey 2020, Simon Hettrick](https://slides.com/simonhettrick/software-risks-reproducibility-and-sustainability))

---

![Graph showing the exponential growth in publications from 1650 to 2012](./images/publications.png) <!-- .element: width="800px" -->

[Bornmann and  Mutz, 2015, 10.1002/asi.23329](https://doi.org/10.1002/asi.23329)

Script:
Let's talk about publications again briefly.
The number of publications being released has grown incredibly over recent centuries,
and with this,
the costs of subscribing to journals.

-

<div style="margin-top: 400px;">
  <span style="padding-left:500px; padding-top: 500px; background-color: #ddaa22;"></span>
  <span style="padding-left: 200px;"></span>
  <span style="padding-left:500px; padding-top: 500px; background-color: #00aa00;"></span>
</div>

Script:
In the early 2000s, this situation started to become unmaintainable, and alternative models started to emerge. Two such approaches have become codified as the "standard" routes to open access as of 2023. Gold open access is where you publish your work in a journal that makes the article available as open access. Green open access on the other hand is where you make a version of the manuscript available via an archiving service, regardless of whether the version in the journal is locked behind a subscription.

-

<span style="font-family: Helvetica; font-size: 500px">©</span>

Script:
Before we can talk more meaningfully about these two models of open access, we need to understand a little bit about copyright.

-

<!-- .element data-transition="slide-in fade-out" -->

![An image of a copyright holder, and four others who are not allowed to make copies](./images/copyright1.svg)

Script:
Put briefly, first introduced in Great Britain over 300 years ago, copyright gives you as the creator of a piece of work the exclusive right to make copies of it.


-

<!-- .element data-transition="fade-in fade-out" -->

![An image of a copyright holder, two others who are not allowed to make copies, and two others with a license who are](./images/copyright2.svg)

Script:
You can then choose to give others permission to make copies, imposing whatever terms you like&mdash;for example, payment of a royalty for each copy, or limiting copying for non-commercial use. In the illustration, the two people on the right have been given licenses to copy, so are allowed, while everyone else still isn't.

-

<!-- .element data-transition="fade-in slide-out" -->

![An image of a copyright holder being paid to transfer copyright to another, another who is licensed to make copies, and two others who are not allowed to make copies](./images/copyright3.svg)

Script:
You can also sell or otherwise transfer the copyright to someone else; they then have all the rights, and you have none, unless you agreed to retain some. In the illustration, the person at the top right has bought the copyright, and then given the person at top a license to make copies; the others have no right to.

-

![World map showing lengths of copyright terms by country.](./images/World_copyright_terms.svg)

[CC BY 3.0 Balfour Smith, Badseed](https://commons.wikimedia.org/wiki/File:World_copyright_terms.svg)

Script:
The length of time copyright lasts for varies based on many factors, but in most places for most works it is some length of time past the death of the original author.

-

[![Creative Commons logo](https://mirrors.creativecommons.org/presskit/logos/cc.logo.svg) <!-- .element width="800px" -->](https://creativecommons.org)

Script:
I mentioned earlier that nobody has any rights to make copies of your work unless you give them permission. One way you can do this is to pick a standardised copyright license, where you make your work available to anyone willing to follow certain conditions. The Creative Commons defines a number of such licenses; for example, you can choose to share on permission that you are acknowledged as the author, or provided that the person making copies also makes any modifications they make available under the same terms. If you see a series of letters starting with "CC", this frequently refers to a Creative Commons license. For more information, see the Creative Commons website.

-

<table>
<tr>
<td>Open access journal</td>
<td>Hybrid journal</td>
<td>Closed journal</td>
</tr>
<tr>
<td style="text-align: center;"><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="Creative Commons logo"></td>
<td style="text-align: center;"><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="Creative Commons logo"><br><span style="font-size: 72px; font-family: Helvetica; position: relative; top: -25px;">©</span></td>
<td style="text-align: center;"><span style="font-size: 72px; font-family: Helvetica; position: relative; top: -25px;">©</span></td>
</tr>
</table>

Script:
So what does gold open access look like? We submit an article to an open-access journal (or a hybrid journal, which has both open-access and subscription-only articles). Since the journal will not be paid by subscription fees for an open-access article, there is likely an Article Processing Charge to be paid, to cover the journal's costs both in formatting the article and also in making it available for the future. After the review process completes, then the article is made available, most frequently under the Creative Commons Attribution license, which you may see written as CC BY. This means anyone can make a copy of it, provided they acknowledge you as the author and link back to the original.

-

[![SCOAP3 logo](./images/scoap3.png) <!-- .element width="800px" -->](https://scoap3.org/)

Script:
While there is usually an article processing charge to be paid, in some cases this is covered by a broader agreement, rather than you needing to pay out of your own pocket. In particle physics the SCOAP3 agreement pays for the majority of research articles to be gold open access automatically, including in journals like JHEP and Physical Review D. For a full list of journals, see the SCOAP3 website.

-

![Green open access logo](./images/green_oa.svg) <!-- .element width="400px" -->

<p class="fragment" style="italic">For the purposes of open access, the author has applied a Creative Commons Attribution (CC BY) licence to any Author Accepted Manuscript version arising from this submission.</p>

Script:
What about green open access? If you publish without gold open access, then the journal will usually require you to transfer the copyright to them. This may restrict what you can do&mdash;for instance, they may impose an embargo period, or forbid you from sharing the version of the manuscript post-peer review. In response to this, funders have introduced a policy of "rights retention", where you inform the journal at time of submission that the submission is conditional on being able to make the reviewed manuscript open access without embargo. This allows you to upload to the arXiv, as well as any other institutional repositories you might need to upload to, with a Creative Commons license.

---

# Modest proposals

-

![Screen shot of arxiv.org](./images/arxiv.png) <!-- .element width="400px" --> ![Screen shot of biorxiv.org](./images/biorxiv.png) <!-- .element width="400px" --> ![Screen shot of medrxiv.org](./images/medrxiv.png) <!-- .element width="400px" -->

-

![Pipline goes paper to reviewer to journal](./images/no-preprint-process.png)

-

![Pipeline goes paper to both preprint server and reviewer, and from reviewer to both preprint server and journal, and from journal to preprint server](./images/preprint-process.png)

-

![Comic exhorting us to "automate ALL the things"](./images/automate.png)

(with apologies to [Hyperbole and a Half](https://hyperboleandahalf.blogspot.com))

-

## Croucher’s law

*“I am an idiot and I will make mistakes”*

&mdash;[Mike Croucher](https://mikecroucher.github.io/MLPM_talk/)

-

[![Software Carpentry](./images/swc.svg) <!-- .element width="500px" -->](https://software-carpentry.org) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Data Carpentry](./images/dc.svg) <!-- .element width="300px" -->](https://datacarpentry.org)

-

[![Logo of the Data Stewards Network](./images/data-stewards.svg) <!-- .element width="400px" -->](https://datastewards.net/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Logo of the Society of Research Software Engineering](./images/socrse-knockout.png) <!-- .element width="400px" -->](https://society-rse.org)

-

![Papers](./images/paper.jpg) <!-- .element width="100px"  vertical-align="middle" --> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px"  vertical-align="text-middle" --> 

![Code](./images/photo_of_code.jpg) <!-- .element width="100px"  vertical-align="text-middle" --> <span class="fragment fade-in" data-fragment-index="1"> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px" vertical-align="text-middle" --></span>

![Data](./images/photo_of_data.jpg) <!-- .element width="100px"  vertical-align="text-middle" --> <span class="fragment fade-in" data-fragment-index="1"> ![right arrow](./images/arrow.svg) ![DOI](./images/doi.svg) <!-- .element width="100px"  vertical-align="text-middle" --></span>

-

[![Screen shot of zenodo.org](./images/zenodo.png) <!-- .element width="1000px" -->](https://zenodo.org)

---

# Data

from [doi:10.5281/zenodo.6976215](https://doi.org/10.5281/zenodo.6976215)

-

![A 3d lattice of points](./images/lattice.svg) <!-- .element width="600px" -->

-

![Graph showing arXiv submissions to the hep-lat category; the vast majority generate new numerical results](./plots/all_numerical.svg) <!-- .element width="1000px" -->

-

![Graph showing arXiv submissions that acknowledge a high-performance computing facility; the majority do](./plots/acknowledges_compute_resources.svg) <!-- .element width="1000px" -->

-

![Graph showing arXiv submissions that specify any of the software used; the majority do not](./plots/specifies_any_software.svg) <!-- .element width="1000px" -->

-

![Graph showing arXiv submissions that publish any of the data they generate; the vast majority do not](./plots/publish_any_data.svg) <!-- .element width="1000px" -->

-

<!-- Yeah, I'm using tables for layout. The talk's in less than 90 minutes, I don't have time to recreate figures or work out how to use flex boxes, sorry. -->
<table width="100%" style="margin-bottom: -60px;"><tr><td width="20px"></td><td align="center"><img src="./images/photo_of_data.jpg" width="100px" alt="Data"></td><td align="center"><img src="./images/photo_of_code.jpg" width="100px" alt="Code"></td></table>

![Graph showing where data were hosted for submissions that did publish data](./plots/used_data_repositories.svg) <!-- .element width="670px" --> ![Graph showing where software was hosted for submissions that did specify software](./plots/all_software_locations.svg) <!-- .element width="670px" -->

-

![Graph showing arXiv submissions that specify the software used specifically for data analysis; the vast majority do not](./plots/specifies_analysis_software.svg) <!-- .element width="1000px" -->

-

![Graph showing arXiv submissions that publish the analysis workflow for the results they present; almost all do not](./plots/publish_analysis_workflow.svg) <!-- .element width="1000px" -->

---

# Summary
