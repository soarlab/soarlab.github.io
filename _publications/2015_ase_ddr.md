---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Fast and Precise Symbolic Analysis of Concurrency Bugs in Device Drivers"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2015_ase_ddr

# conference | journal | poster | workshop
type: conference
redirect_from: /2015/08/ase2015-ddr

# The shortname is used for auto-generated titles
shortname: ASE 2015
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2015_ase_ddr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2015_ase_ddr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Pantazis Deligiannis
- Alastair F. Donaldson
- rakamaric

journal-short: ASE
year: 2015

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 30th IEEE/ACM International Conference on
    Automated Software Engineering (ASE)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 166--177
  doi: 10.1109/ASE.2015.30
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
pdf: 2015_ase_ddr.pdf
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
code: https://github.com/smackers/whoop

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Concurrency errors, such as data races, make device drivers notoriously hard to
develop and debug without automated tool support. We present Whoop, a new
automated approach that statically analyzes drivers for data races. Whoop is
empowered by symbolic pairwise lockset analysis, a novel analysis that can
soundly detect all potential races in a driver. Our analysis avoids reasoning
about thread interleavings and thus scales well. Exploiting the race-freedom
guarantees provided by Whoop, we achieve a sound partial-order reduction that
significantly accelerates Corral, an industrial-strength bug-finder for
concurrent programs. Using the combination of Whoop and Corral, we analyzed 16
drivers from the Linux 4.0 kernel, achieving 1.5-20x speedups over standalone
Corral.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We thank Akash Lal for his input and for helping us with Corral issues, and
Montgomery Carter for modeling Linux locks. Thanks to Jeroen Ketema, Tyler
Sorensen, Anton Burtsev, and Charlie Jacobsen for discussions and feedback in
various stages of this work. This work is part of the project "Automatic
Synthesis of High-Assurance Device Drivers" and was generously funded by a gift
from Intel Corporation; it was also supported in part by NSF CCF 1346756.

