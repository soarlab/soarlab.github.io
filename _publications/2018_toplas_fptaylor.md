---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Estimation of Floating-Point Round-off Errors with Symbolic Taylor Expansions"
key: 2018_toplas_fptaylor
#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: preprint
redirect_from: /publications/2018_toplas_fptaylor

# The shortname is used for auto-generated titels
shortname: FPtaylorToplas
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_toplas_fptaylor.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_toplas_fptaylor.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Alexey Solovyev
- baranowski
- Ian Briggs
- Charles Jacobsen
- rakamaric
- Ganesh Gopalakrishnan

journal-short: TOPLAS
year: 2018

bibentry: article
bib:
  journal: ACM Transactions on Programming Languages and Systems (TOPLAS), to appear
  booktitle: 
  editor: 
  publisher: ACM
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages: 
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:
#https://github.com/soarlab/FPTaylor

# The reference to the video entry
video:
# 2018_tvcg_lineage_video
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2018_toplas_fptaylor.pdf
# A supplement PDF
supplement: 
#2018_tvcg_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/soarlab/FPTaylor

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Rigorous estimation of maximum floating-point round-off errors is an important capability central to many formal verification tools. Unfortunately, available techniques for this task often provide very pessimistic overestimates, causing unnecessary verification failure. We have developed a new approach called Symbolic Taylor Expansions that avoids these problems, and implemented a new tool called FPTaylor embodying this approach. Key to our approach is the use of rigorous global optimization, instead of the more familiar interval arithmetic, affine arithmetic, and/or SMT solvers. FPTaylor emits per-instance analysis certificates in the form of HOL Light proofs that can be machine checked.
In this paper, we present the basic ideas behind Symbolic Taylor Expansions in detail. We also survey as well as thoroughly evaluate six tool families, namely Gappa (two tool options studied), Fluctuat, PRECiSA, Real2Float, Rosa and FPTaylor (two tool options studied) on 24 examples, running on the same machine, and taking care to find the best options for running each of these tools. This study demonstrates that FPTaylor estimates round-off errors within much tighter bounds compared to other tools on a significant number of case studies. We also release FPTaylor along with our benchmarks, thus contributing to future studies and tool development in this area."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
