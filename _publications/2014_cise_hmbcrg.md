---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Systematic Debugging Methods for Large Scale HPC Computational Frameworks"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2014_cise_hmbcrg

# conference | journal | poster | workshop
type: journal
redirect_from: /2014/05/systematic-debugging-methods-for-large-scale-hpc-computational-frameworks

# The shortname is used for auto-generated titles
shortname: CiSE 2014
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2014_cise_hmbcrg.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2014_cise_hmbcrg_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Alan Humphrey
- Qingyu Meng
- Martin Berzins
- Diego Caminha B. de Oliveira
- rakamaric
- Ganesh Gopalakrishnan

journal-short: CiSE
year: 2014

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: Computing in Science and Engineering (CiSE)
  series:
  volume: 16
  publisher: IEEE
  editor:
  pages: 48--56
  doi: 10.1109/MCSE.2014.11
  address:
  url:
  number: 3
  month: may
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
# The reference to the preview video entry
#preview-video:

# the preprint
pdf: 2014_cise_hmbcrg.pdf
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
Parallel computational frameworks for high performance computing (HPC) are
central to the advancement of simulation based studies in science and
engineering. Unfortunately, finding and fixing bugs in these frameworks can be
extremely time consuming. Left unchecked, these bugs can drastically diminish
the amount of new science that can be performed. This paper presents our
systematic study of the Uintah computational framework, and our approaches to
debug it more incisively. Our key insight is to leverage the modular structure
of Uintah which lends itself to systematic debugging. In particular, we have
developed a new approach based on Coalesced Stack Trace Graphs (CSTGs) that
summarize the system behavior in terms of key control flows manifested through
function invocation chains. We illustrate several scenarios how CSTGs could
help efficiently localize bugs, and present a case study of how we found and
fixed a real Uintah bug using CSTGs.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

The authors wish to thank the referees for their insightful comments. This work
was supported by the National Science Foundation under grants OCI-0721659, the
NSF OCI PetaApps program, through award OCI 0905068 and DOE NETL for funding
under NET DE-EE0004449. This project used the University of Delaware's Chimera
computer which was funded by the U.S. National Science Foundation Award
CNS-0958512.

