---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "STORM: Static Unit Checking of Concurrent Programs"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2010_icse_r

# conference | journal | poster | workshop
type: conference
redirect_from: /2010/05/storm-static-unit-checking-of-concurrent-programs

# The shortname is used for auto-generated titles
shortname: ICSE 2010
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2010_icse_r.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2010_icse_r_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- rakamaric

journal-short: ICSE
year: 2010

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 32nd ACM/IEEE International Conference on
    Software Engineering (ICSE) - Volume 2
  series:
  volume:
  publisher: ACM
  editor:
  pages: 519--520
  doi: 10.1145/1810295.1810460
  address:
  url:
  number:
  month:
  note: ACM Student Research Competition

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: Silver Medal Winner in the ACM Student Research Competition

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:

# The reference to the video entry
video:
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2010_icse_r.pdf
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
Concurrency is inherent in today's software. Unexpected interactions between
concurrently executing threads often cause subtle bugs in concurrent programs.
Such bugs are hard to discover using traditional testing techniques since they
require executing a program on a particular unit test (i.e. input) through a
particular thread interleaving. A promising solution to this problem is static
program analysis since it can simultaneously check a concurrent program on all
inputs as well as through all possible thread interleavings. This paper
describes a scalable, automatic, and precise approach to static unit checking
of concurrent programs implemented in a tool called STORM. STORM has been
applied on a number of real-world Windows device drivers, and the tool found a
previously undiscovered concurrency bug in a driver from Microsoft's Driver
Development Kit.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This is a joint work with Alan J. Hu, Shuvendu Lahiri, and Shaz Qadeer. It was
supported by a Microsoft Research Graduate Fellowship.

