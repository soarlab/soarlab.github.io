---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Estimation of Floating-Point Round-off Errors with Symbolic Taylor Expansions"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2018_toplas_sbbjrg

# conference | journal | poster | workshop
type: journal
redirect_from: /2018/06/toplas2018-sbbjrg

# The shortname is used for auto-generated titles
shortname: TOPLAS 2018
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_toplas_sbbjrg.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_toplas_sbbjrg.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- solovyev
- baranowski
- Ian Briggs
- Charles Jacobsen
- rakamaric
- Ganesh Gopalakrishnan

journal-short: TOPLAS
year: 2018

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: ACM Transactions on Programming Languages and Systems (TOPLAS)
  series:
  volume: 41
  publisher: ACM
  editor:
  pages: 2:1--2:39
  doi: 10.1145/3230733
  address:
  url:
  number: 1
  month: December
  note:
  issue_date: March 2019

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:

# The reference to the video entry
video:
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2018_toplas_sbbjrg.pdf
# A supplement PDF
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code: https://github.com/soarlab/FPTaylor

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
Rigorous estimation of maximum floating-point round-off errors is an important
capability central to many formal verification tools. Unfortunately, available
techniques for this task often provide very pessimistic overestimates, causing
unnecessary verification failure. We have developed a new approach called
Symbolic Taylor Expansions that avoids these problems, and implemented a new
tool called FPTaylor embodying this approach. Key to our approach is the use of
rigorous global optimization, instead of the more familiar interval arithmetic,
affine arithmetic, and/or SMT solvers. FPTaylor emits per-instance analysis
certificates in the form of HOL Light proofs that can be machine checked.  In
this paper, we present the basic ideas behind Symbolic Taylor Expansions in
detail. We also survey as well as thoroughly evaluate six tool families, namely
Gappa (two tool options studied), Fluctuat, PRECiSA, Real2Float, Rosa and
FPTaylor (two tool options studied) on 24 examples, running on the same
machine, and taking care to find the best options for running each of these
tools. This study demonstrates that FPTaylor estimates round-off errors within
much tighter bounds compared to other tools on a significant number of case
studies. We also release FPTaylor along with our benchmarks, thus contributing
to future studies and tool development in this area.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was supported by the National Science Foundation awards CCF 1535032,
1552975, 1643056, and 1704715.  We would like to thank Nelson Beebe, Wei-Fan
Chiang, and John Harrison for their feedback and encouragement.

