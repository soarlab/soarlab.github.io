---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "PRUNERS: Providing Reproducibility for Uncovering Non-Deterministic Errors in Runs on Supercomputers"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2019_ijhpca_sllscabgrspa

# conference | journal | poster | workshop
type: journal
redirect_from:

# The shortname is used for auto-generated titles
shortname: IJHPCA 2019
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_ijhpca_sllscabgrspa.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2019_ijhpca_sllscabgrspa_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Kento Sato
- Ignacio Laguna
- Gregory L. Lee
- Martin Schulz
- Christopher M. Chambreau
- atzeni
- Michael Bentley
- Ganesh Gopalakrishnan
- rakamaric
- Geof Sawaya
- Joachim Protze
- Dong H. Ahn

journal-short: IJHPCA
year: 2019

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: International Journal of High Performance Computing Applications (IJHPCA)
  series:
  volume: 33
  publisher: SAGE
  editor:
  pages: 777--783
  doi: 10.1177/1094342019834621
  address:
  url:
  number: 5
  month: sep
  note:
  issue_date:

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
pdf: 2019_ijhpca_sllscabgrspa.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: PRUNERS Project Website
  abslink: https://pruners.github.io
  linksym: true
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code:

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Large scientific simulations must be able to achieve the full-system
potential of supercomputers. When they tap into high-performance features,
however, a phenomenon known as non-determinism may be introduced in their
program execution, which significantly hampers application development.
PRUNERS is a new toolset to detect and remedy non-deterministic bugs and
errors in large parallel applications. To show the capabilities of PRUNERS
for large application development, we also demonstrate their early usage on
real-world production applications.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was performed under the auspices of the US Department of Energy by
LLNL under contract DE-AC52-07NA27344 (LLNL-JRNL-747183).

