---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "FailAmp: Relativization Transformation for Soft Error Detection in Structured Address Generation"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2019_taco_bdbskrg

# conference | journal | poster | workshop
type: journal

# The shortname is used for auto-generated titles
shortname: TACO 2019
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_taco_bdbskrg.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2019_taco_bdbskrg_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Ian Briggs
- Arnab Das
- baranowski
- Vishal Sharma
- Sriram Krishnamoorthy
- rakamaric
- Ganesh Gopalakrishnan

journal-short: TACO
year: 2019

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: ACM Transactions on Architecture and Code Optimimization (TACO)
  series:
  volume: 16
  publisher: ACM
  editor:
  pages: 50:1--50:21
  doi: 10.1145/3369381
  address:
  url:
  number: 4
  month: dec
  note:
  issue_date: January 2020

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:

# The reference to the video entry
video:
# The reference to the preview video entry
#preview-video:

# the preprint
pdf: 2019_taco_bdbskrg.pdf
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
code: https://gitlab.flux.utah.edu/ianbriggsutah/failamp

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
We present FailAmp, a novel LLVM program transformation algorithm that makes
programs employing structured index calculations more robust against
soft-errors. Without FailAmp, an offset error can go undetected; with FailAmp,
all subsequent offsets are relativized, building on the faulty one. FailAmp can
exploit ISAs such as ARM to further reduce overheads. We verify correctness
properties of FailAMP using an SMT solver, and present a thorough evaluation
using many HPC benchmarks under a fault injection campaign. FailAmp provides
full soft-error detection for address calculation while incurring an average
overhead of around 5%.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This research was supported in part by NSF Awards 1817073 and 1704715, and DOE
Contract DE-SC0014096. This material is based upon work supported by the U.S.
Department of Energy, Office of Science, Office of Advanced Scientific
Computing Research under Award Number 66905. Pacific Northwest National
Laboratory is operated by Battelle for DOE under Contract DE-AC05-76RL01830.

