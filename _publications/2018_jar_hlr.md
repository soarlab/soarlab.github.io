---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Verifying Relative Safety, Accuracy, and Termination for Program Approximations"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2018_jar_hlr

# conference | journal | poster | workshop
type: journal
redirect_from: /2017/08/jar2018-hlr

# The shortname is used for auto-generated titles
shortname: JAR 2018
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_jar_hlr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_jar_hlr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- he
- Shuvendu K. Lahiri
- rakamaric

journal-short: JAR
year: 2018

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: Journal of Automated Reasoning (JAR)
  series:
  volume: 60
  publisher: Springer
  editor:
  pages: 23--42
  doi: 10.1007/s10817-017-9421-9
  address:
  url:
  number: 1
  month: jan
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
pdf: 2018_jar_hlr.pdf
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
Approximate computing is an emerging area for trading off the accuracy of an
application for improved performance, lower energy costs, and tolerance to
unreliable hardware. However, developers must ensure that the leveraged
approximations do not introduce significant, intolerable divergence from the
reference implementation, as specified by several established robustness
criteria. In this work, we show the application of automated differential
verification towards verifying relative safety, accuracy, and termination
criteria for a class of program approximations. We use mutual summaries to
express relative specifications for approximations, and SMT-based invariant
inference to automate the verification of such specifications. We perform a
detailed feasibility study showing promise of applying automated verification
to the domain of approximate computing in a cost-effective manner.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We thank Adrian Sampson for his feedback and for helping out with benchmark
selection, and Akash Lal for assisting with Houdini. This work was supported in
part by NSF awards 1255776 and 1552975, and SRC contract 2013-TJ-2426.

