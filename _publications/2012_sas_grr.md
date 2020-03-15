---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Symbolic Learning of Component Interfaces"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2012_sas_grr

# conference | journal | poster | workshop
type: conference

# The shortname is used for auto-generated titles
shortname: SAS 2012
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2012_sas_grr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2012_sas_grr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Dimitra Giannakopoulou
- rakamaric
- Vishwanath Raman

journal-short: SAS
year: 2012

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 19th International Static Analysis Symposium (SAS)
  series: Lecture Notes in Computer Science
  volume: 7460
  publisher: Springer
  editor: Antoine Min\'e and David Schmidt
  pages: 248--264
  doi: 10.1007/978-3-642-33125-1_18
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
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2012_sas_grr.pdf
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
code: https://github.com/psycopaths/psyco

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Given a white-box component C with specified unsafe states, we address the
problem of automatically generating an interface that captures safe orderings
of invocations of C's public methods. Method calls in the generated interface
are guarded by constraints on their parameters. Unlike previous work, these
constraints are generated automatically through an iterative refinement
process. Our technique, named PSYCO (Predicate-based SYmbolic COmpositional
reasoning), employs a novel combination of the L* automata learning algorithm
with symbolic execution. The generated interfaces are three-valued, capturing
whether a sequence of method invocations is safe, unsafe, or its effect on the
component state is unresolved by the symbolic execution engine. We have
implemented PSYCO as a new prototype tool in the JPF open-source software model
checking platform, and we have successfully applied it to several examples.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This research was supported by the NASA CMU grant NNA10DE60C.  We would like to
thank Peter Mehlitz for his help with Java PathFinder and Neha Rungta for
reviewing a version of this paper.

