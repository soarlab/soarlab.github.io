---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Verifying Heap-Manipulating Programs in an SMT Framework"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2007_atva_rbhc

# conference | journal | poster | workshop
type: conference
redirect_from: /2007/10/verifying-heap-manipulating-programs-in-an-smt-framework

# The shortname is used for auto-generated titles
shortname: ATVA 2007
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2007_atva_rbhc.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2007_atva_rbhc_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- rakamaric
- Roberto Bruttomesso
- Alan J. Hu.
- Alessandro Cimatti

journal-short: ATVA
year: 2007

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 5th International Symposium on
    Automated Technology for Verification and Analysis (ATVA)
  series: Lecture Notes in Computer Science
  volume: 4762
  publisher: Springer
  editor: Kedar S. Namjoshi and Tomohiro Yoneda
  pages: 237--252
  doi: 10.1007/978-3-540-75596-8_18
  address:
  url:
  number:
  month:
  note:

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
pdf: 2007_atva_rbhc.pdf
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
code:

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
Automated software verification has made great progress recently, and a key
enabler of this progress has been the advances in efficient, automated decision
procedures suitable for verification (Boolean satisfiability solvers and
satisfiability-modulo-theories (SMT) solvers). Verifying general software,
however, requires reasoning about unbounded, linked, heap-allocated data
structures, which in turn motivates the need for a logical theory for such
structures that includes unbounded reachability. So far, none of the available
SMT solvers supports such a theory. In this paper, we present our integration
of a decision procedure that supports unbounded heap reachability into an
available SMT solver. Using the extended SMT solver, we can efficiently verify
examples of heap-manipulating programs that we could not verify before.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported by (1) a research grant from the Natural Sciences and Engineering
Research Council of Canada, (2) a University of British Columbia Graduate
Fellowship, (3) ORCHID, a project sponsored by Provincia Autonoma di Trento,
and (4) a research grant from Intel.

