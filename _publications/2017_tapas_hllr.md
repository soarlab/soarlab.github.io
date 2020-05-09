---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Static Assertion Checking of Production Software with Angelic Verification"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2017_tapas_hllr

# conference | journal | poster | workshop
type: workshop
redirect_from: /2017/09/tapas2017-hllr

# The shortname is used for auto-generated titles
shortname: TAPAS 2017
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_tapas_hllr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_tapas_hllr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- he
- Shuvendu Lahiri
- Akash Lal
- rakamaric

journal-short: TAPAS
year: 2017

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: 8th Workshop on Tools for Automatic Program Analysis (TAPAS)
  series:
  volume:
  publisher:
  editor:
  pages:
  doi:
  address:
  url:
  number:
  month:
  note: Extended abstract

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
pdf: 2017_tapas_hllr.pdf
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

abstract: "
<p>The ability to statically detect violations of assertions can add great
value to developers. However, in spite of decades of progress in program
verification, static assertion checking is far from being cost-effective for
production software. The two main obstacles to finding high-quality defects are
(a) false alarms due to under-constrained environment, and (b) finding
violations to deeply nested procedures.</p>

<p>In this talk, we will describe our experience with the angelic verification
(AV) tool for statically finding assertion violations in real-world software.
The basic idea of AV is to pair an interprocedural assertion verifier with a
framework for automatic inference of likely specifications on unknown values
from the environment. We will summarize the approach, and will focus on design
choices required to find high-quality violations of memory-safety violations
with low false alarms.  We discuss some results on Microsoft codebases and open
source software, and challenges ahead.</p>"

---
