---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Sword: A Bounded Memory-Overhead Detector of OpenMP Data Races in Production Runs"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2018_ipdps_agrlla

# conference | journal | poster | workshop
type: conference
redirect_from: /2018/02/ipdps2018-agrlla

# The shortname is used for auto-generated titles
shortname: IPDPS 2018
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_ipdps_agrlla.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_ipdps_agrlla_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- atzeni
- Ganesh Gopalakrishnan
- rakamaric
- Ignacio Laguna
- Greg L. Lee
- Dong H. Ahn

journal-short: IPDPS
year: 2018

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 32nd IEEE International Parallel and
    Distributed Processing Symposium (IPDPS)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 845--854
  doi: 10.1109/IPDPS.2018.00094
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
pdf: 2018_ipdps_agrlla.pdf
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
code: https://github.com/PRUNERS/sword

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
The detection and elimination of data races in large-scale OpenMP programs is
of critical importance. Unfortunately, today's state-of-the-art OpenMP race
checkers suffer from high memory overheads and/or miss races. In this paper, we
present Sword, a data race detector that significantly improves upon these
limitations. Sword limits the application slowdown and memory usage by
utilizing only a bounded, user-adjustable memory buffer to collect targeted
memory accesses. When the buffer fills up, the accesses are compressed and
flushed to a file system for later offline analysis. Sword builds on an
operational semantics that formally captures the notion of concurrent accesses
within OpenMP regions. An offline race checker that is driven by these semantic
rules allows Sword to improve upon happens-before techniques that are known to
mask races. To make its offline analysis highly efficient and scalable, Sword
employs effective self-balancing interval-tree-based algorithms. Our
experimental results demonstrate that Sword is capable of detecting races even
within programs that use over 90% of the memory on each compute node. Further,
our evaluation shows that it matches or exceeds the best available dynamic
OpenMP race checker in detection capability while remaining efficient in
execution time.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was performed under the auspices of the U.S. Department of Energy by
LLNL under Contract DE-AC52-07NA27344 (LLNL-CONF740324), NSF OAC 1535032, and
NSF CCF 1704715.

