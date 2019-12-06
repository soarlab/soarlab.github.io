---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Stochastic Local Search for Solving Floating-Point Constraints"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2019_nsv_hbr
# paper | preprint | poster | workshop
type: workshop
redirect_from:

# The shortname is used for auto-generated titles
shortname: NSV 2019
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_nsv_hbr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2019_nsv_hbr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- he
- baranowski
- rakamaric

journal-short: NSV
year: 2019

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 12th International Workshop on Numerical
    Software Verification (NSV)
  series: Lecture Notes in Computer Science
  volume: 11652
  publisher: Springer
  editor: Majid Zamani and Damien Zufferey
  pages: 76--84
  doi: 10.1007/978-3-030-28423-7_5 
  address:
  url:
  number:
  month:

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
pdf: 2019_nsv_hbr.pdf
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
code: https://github.com/soarlab/OL1V3R

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
We present OL1V3R, a solver for the SMT floating-point theory that is based on
stochastic local search (SLS). We adapt for OL1V3R the key ingredients of
related work on leveraging SLS to solve the SMT fixed-sized bit-vector theory,
and confirm its effectiveness by comparing it with mature solvers. Finally, we
discuss the limitations of OL1V3R and propose solutions to make it more
powerful.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by the National Science Foundation (NSF) awards CCF 1552975
and CCF 1704715.

