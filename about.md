---
# feel free to add any field or other data point
# title: ${ProjName} # this will override the site level title for the about/landing page
# bio: ... # this will override the site level bio felid for the about/landing page
# description: ... # this will override the site level description felid for the about/landing page
# Do not change any value under thisL:
layout: landing
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
permalink: index.html
---
<hr>
RESEARCH TEAM
<div class="box">
  <p>
* University of Utah: PI: Ganesh Gopalakrishnan, Co-PI: Pavel Panchekha <br>
* University of California, Davis: PI: Cindy Rubio-Gonzalez <br>
* University of Washington, Seattle: PI: Zachary Tatlock <br>
* Lawrence Livermore National Laboratory: PI: Ignacio Laguna <br>
* Pacific Northwest National Laboratory: PI: Ang Li
  </p>
</div>
<hr>
RESEARCH SUMMARY
As part of the recently announced DOE-investment in Research on
Adapting Scientific Software to Run on Next-Generation Supercomputers,
the ComPort project develops Rigorous Testing Methods to Safeguard
Software Porting.\
Modern research is crucially based on the use of high-performance
computing (HPC) working in tandem with machine learning (ML). With
growing heterogeneity of hardware (CPUs, GPUs, accelerators) and
software (various parallelism models), the overall numerical integrity
of code can be affected by a variety of causes, not all of which are
fully understood or even have been encountered in existing HPC
systems. Problems such as innocuous-looking changes to compiler
optimization flags leading to aberrant climatic predictions are
already being faced by researchers. Similar variations can cause ML
systems to misclassify data or program states, leading to incorrect
HPC software behaviors in combined HPC/ML systems already in use, such
as for characterizing the Sars COV-2 virus.\
The ComPort project develops rigorous methods to verify -- after each
software upgrade or port -- whether computational results agree with
expected answers (say, as delivered by prior versions that have stood
the test of time). It empowers the user to define how to rigorously
test the numerical behavior of hardware and software, and also specify
what results to accept. The ComPort software tool suite will support
all this while also providing a high degree of automation and
high-level user feedback to diagnose and repair software applications
to facilitate software numerical correctness maintenance despite
changing hardware and compilers.
<hr>
<span class="image left"><img src="{{ "/images/cesm-coupling.png" | absolute_url }}" alt="" /></span>
This diagram from CACM February 2021, ``Keeping Science on Keel when Software Moves,'' is one example of several that might be produced to characterize
large codebases. This visual shows how a climate simulation code called
CESM was analyzed and portrayed by Dan Millroy (LLNL postdoc) during his
PhD (visualization credit: Liam Krauss of LLNL).
This figure shows a three-dimensional, undirected representation of
the example from Figure 6 in the CACM paper.
Nodes are colored by community membership
and sized based on a threshold centrality value. The red nodes
represent model variables sensitive to specific CPU instructions. All
nodes with eigenvector centrality ≤ 0.4 have a constant size, and
those above the threshold are scaled and highlighted by increased
reflectance.

