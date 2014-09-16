Vision of the future

- Standard journal paper
- Interactive plots
- Download the data
- Too many n=1 papers
- Too much data horded and only used once.
- Software and data have a magic property: infinitely copiable with virtually
  zero cost per copy.
- Stand on the shoulders of giants
- We spend gobs of time getting results and once we get the result we make a
  plot an all the work we've done is lost. No one can actually build upon it.
- Show software used to extract data from publication plots.

What is reproducibility?

- Who has ever found a bug in their program or a mistake in their work? Do you
  have work that you think is bug free, mistake free?
- Show stats of how many psy expriments can't be reproduced.
- Show stats on how many computer code with papers can acutally be run.
- OS vm image with working software.
- cite the greg wilson paper in plos biology:
  http://www.plosbiology.org/article/info%3Adoi%2F10.1371%2Fjournal.pbio.1001745
- read this: http://web.stanford.edu/~vcs/papers/CiSE2012-LMS.pdf
- http://johncarlosbaez.wordpress.com/2011/10/15/the-science-code-manifesto/

Citations

- NSF Data Managment Plan added in 2011
- PLoS One Data Policy
- WHite House Open Access:
  http://www.whitehouse.gov/blog/2013/02/22/expanding-public-access-results-federally-funded-research
  That’s why, in a policy memorandum released today, OSTP Director John Holdren
  has directed Federal agencies with more than $100M in R&D expenditures to
  develop plans to make the published results of federally funded research
  freely available to the public within one year of publication and requiring
  researchers to better account for and manage the digital data resulting from
  federally funded scientific research.
- TU Delft mandates open access
- Climate data
- http://www.jove.com/blog/2012/05/03/studies-show-only-10-of-published-science-articles-are-reproducible-what-is-happening
- http://sciencecodemanifesto.org/


http://web.stanford.edu/~vcs/papers/CiSE2012-LMS.pdf
----------------------------------------------------

  An article about computational science in a sci-
  entific publication is not the scholarship itself,
  it is merely advertising of the scholarship. The
  actual scholarship is the complete software de-
  velopment environment and the complete set
  of instructions which generated the figures.”
  —
  Jonathan Buckheit and David Donoho,
  paraphrasing Jon Claerbout 1995

Review of Omics-Based Tests for Pre-
dicting Patient Outcomes in Clinical Trials” to
examine publication standards for computational
work that leads to clinical trials. In March of 2012
the committee released a report recommending the
release of the software and data underlying the find-
ings (see http://iom.edu/Activities/Research/
OmicsBasedTests.aspx)

Science
4
and the
Proceedings of the National Academy of Sci-
ences
(PNAS) have made data and code disclosure
a requirement for publication

respondents reported
that the single biggest barrier to sharing code
and data was the time it takes to clean up and
document the work to prepare it for release and
reuse (56 percent of respondents cited this reason
for not sharing data and 78 percent cited this rea-
son for not sharing code

 Keep in mind during
 this process that reproducibility is not an all-or-nothing
 affair, but rather a social construct with a spectrum of
 meanings that supports a gradual learning curve

he principal goal of these discussions
and workshops is to develop publica-
tion standards akin to both the proof
in mathematics and the deductive
sciences, and the detailed descriptive protocols
in the empirical sciences (the “methods” section
of a paper describing the mechanics of the con-
trolled experiment and hypothesis test). Compu-
tational science is only a few decades old and must
develop similar standards, so that other research-
ers in the field can independently verify pub-
lished results

this
----
http://sepwww.stanford.edu/sep/jon/reproducible.html

iInteractive programs should always be able to save their state so they can
restart. Otherwise, dependence on an interactive program can be a form of
slavery (nonreproducible research)

this one
--------

Roger D. Peng, Reproducible Research in Computational Science, Science 2
December 2011, Vol. 334 no. 6060 pp. 1226-1227, DOI: 10.1126/science.1213847

"The journal Biostatistics, for which I am an associate editor, has implemented
a policy for encouraging authors of accepted papers to make their work
reproducible by others."

Ten Simple Rules for Reproducible Computational Research
--------------------------------------------------------
Rule 1: For Every Result, Keep Track of How It Was Produced
Rule 2: Avoid Manual Data Manipulation Steps
Rule 3: Archive the Exact Versions of All External Programs Used
Rule 4: Version Control All Custom Scripts
Rule 5: Record All Intermediate Results, When Possible in Standardized Formats
Rule 6: For Analyses That Include Randomness, Note Underlying Random Seeds
Rule 7: Always Store Raw Data behind Plots
Rule 8: Generate Hierarchical Analysis Output, Allowing Layers of Increasing
Detail to Be Inspected
Rule 9: Connect Textual Statements to Underlying Results
Rule 10: Provide Public Access to Scripts, Runs, and Results

Big blunders:

- arsenic
- latest thing where guy killed himself
- japanese lady who had fraud
- Spreadsheet errors cost billions: http://www.cnbc.com/id/100923538

Why is computational reproducibilty important?

What we need

- Data must be shared and machine readable
- Source code must be shared and reproducible, open source ensures that others
  can run it.

Open Source Software

- No vendor lock in

Open Data

- CC0: Can data be copyrighted? Isn't it just fact?

How do we do this?

- data: figshare, zenodo, dryad, genbank
- source code: github, bitbucket
- create libraries instead of scripts

Python

- NumPy
- SciPy
- Pandas
- SymPy
- IPython
- Spyder
- Dexy

R

- statistics, machine learning, "machine learning is rebranded stats"
- ggplot
- weaving R code with text (knitr)

Julia

- Speed comparisons

Octave/Scilab

- Matlab clone
- xcos: simulink clone

Modelica

GSL
