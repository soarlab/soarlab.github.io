---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Towards Formal Approaches to System Resilience"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2013_prdc_shrg

# conference | journal | poster | workshop
type: conference
redirect_from: /2013/08/towards-formal-approaches-to-system-resilience

# The shortname is used for auto-generated titles
shortname: PRDC 2013
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2013_prdc_shrg.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2013_prdc_shrg_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Vishal Chandra Sharma
- haran
- rakamaric
- Ganesh Gopalakrishnan

journal-short: PRDC
year: 2013

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 19th IEEE Pacific Rim International Symposium
    on Dependable Computing (PRDC)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 41--50
  doi: 10.1109/PRDC.2013.14
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
pdf: 2013_prdc_shrg.pdf
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
code: https://github.com/soarlab/kulfi

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Technology scaling and techniques such as dynamic voltage/frequency scaling are
predicted to increase the number of transient faults in future processors.
Error detectors implemented in hardware are often energy inefficient, as they
are always on. While software-level error detection can augment
hardware-level detectors, creating detectors in software that are highly
effective remains a challenge. In this paper, we first present a new LLVM-level
fault injector called KULFI that helps simulate faults occurring within CPU
state elements in a versatile manner. Second, using KULFI, we study the
behavior of a family of well-known and simple algorithms under error injection.
(We choose a family of sorting algorithms for this study.) We then propose a
promising way to interpret our empirical results using a formal model that
builds on the idea of predicate state transition diagrams. After introducing
the basic abstraction underlying our predicate transition diagrams, we draw
connections to the level of resilience empirically observed during fault
injection studies. Building on the observed connections, we develop a simple,
and yet effective, predicate-abstraction-based fault detector. While in its
initial stages, ours is believed to be the first study that offers a formal way
to interpret and compare fault injection results obtained from algorithms from
within one family. Given the absolutely unpredictable nature of what a fault
can do to a computation in general, our approach may help designers choose
amongst a class of algorithms one that behaves most resilient of all.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by NSF Award CCF 1255776, SRC Contract 2013- TJ-2426, and
Scientific Discovery through Advanced Computing (SciDAC) program funded by U.S.
Department of Energy, Office of Science, Advanced Scientific Computing Research
(and Basic Energy Sciences/Biological and Environmental Research/High Energy
Physics/Fusion Energy Sciences/Nuclear Physics).
We would like to thank Pedro Diniz, Prabhakar Kudva, Shuvendu Lahiri, and
Karthik Pattabiraman for their insights and feedback on the early drafts of
this paper. We are also grateful to Sui Chen for trying out early versions of
KULFI and providing us with detailed feedback that helped us to improve it.

