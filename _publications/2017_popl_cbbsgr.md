---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Floating-Point Mixed-Precision Tuning"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2017_popl_cbbsgr

# conference | journal | poster | workshop
type: conference
redirect_from: /2016/11/popl2017-cbbsgr

# The shortname is used for auto-generated titles
shortname: POPL 2017
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_popl_cbbsgr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_popl_cbbsgr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- chiang
- baranowski
- Ian Briggs
- solovyev
- Ganesh Gopalakrishnan
- rakamaric

journal-short: POPL
year: 2017

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 44th ACM SIGPLAN Symposium on Principles of
    Programming Languages (POPL)
  series:
  volume:
  publisher: ACM
  editor:
  pages: 300--315
  doi: 10.1145/3009837.3009846
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
pdf: 2017_popl_cbbsgr.pdf
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
code: https://github.com/soarlab/FPTuner

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Virtually all real-valued computations are carried out using floating-point
data types and operations. The precision of these data types must be set with
the goals of reducing the overall round-off error, but also emphasizing
performance improvements. Often, a mixed-precision allocation achieves this
optimum; unfortunately, there are no techniques available to compute such
allocations and conservatively meet a given error target across all program
inputs. In this work, we present a rigorous approach to precision allocation
based on formal analysis via Symbolic Taylor Expansions, and error analysis
based on interval functions. This approach is implemented in an automated tool
called FPTuner that generates and solves a quadratically constrained quadratic
program to obtain a precision-annotated version of the given expression.
FPTuner automatically introduces all the requisite precision up and down
casting operations. It also allows users to flexibly control precision
allocation using constraints to cap the number of high precision operators as
well as group operators to allocate the same precision to facilitate
vectorization. We evaluate FPTuner by tuning several benchmarks and measuring
the proportion of lower precision operators allocated as we increase the error
threshold. We also measure the reduction in energy consumption resulting from
executing mixed-precision tuned code on a real hardware platform. We observe
significant energy savings in response to mixed-precision tuning, but also
observe situations where unexpected compiler behaviors thwart intended
optimizations.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We thank Hari Sundar for helping out with the energy measurements, Cindy
Rubio-Gonzalez for providing support with Precimonious, Eva Darulova for
distributing Rosa and its valuable benchmarks, and the anonymous reviewers for
their numerous comments and suggestions. This work was supported in part by NSF
awards CCF 1531140, CCF 1643056, and CCF 1552975.

