---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Archer: Effectively Spotting Data Races in Large OpenMP Applications"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2016_ipdps_agralslpm

# conference | journal | poster | workshop
type: conference
redirect_from: /2016/02/ipdps2016-agralslpm

# The shortname is used for auto-generated titles
shortname: IPDPS 2016
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_ipdps_agralslpm.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_ipdps_agralslpm_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- atzeni
- Ganesh Gopalakrishnan
- rakamaric
- Dong H. Ahn
- Ignacio Laguna
- Martin Schulz
- Greg L. Lee
- Joachim Protze
- Matthias S. Muller

journal-short: IPDPS
year: 2016

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 30th IEEE International Parallel and
    Distributed Processing Symposium (IPDPS)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 53--62
  doi: 10.1109/IPDPS.2016.68
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
pdf: 2016_ipdps_agralslpm.pdf
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
code: https://github.com/PRUNERS/archer

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
OpenMP plays a growing role as a portable programming model to harness on-node
parallelism; yet, existing data race checkers for OpenMP have high overheads
and generate many false positives. In this paper, we propose the first OpenMP
data race checker, Archer, that achieves high accuracy, low overheads on large
applications, and portability. Archer incorporates scalable happens-before
tracking, exploits structured parallelism via combined static and dynamic
analysis, and modularly interfaces with OpenMP runtimes. Archer significantly
outperforms TSan and Intel Inspector XE, while providing the same or better
precision. It has helped detect critical data races in the Hypre library that
is central to many projects at Lawrence Livermore National Laboratory and
elsewhere.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank the anonymous reviewers for their constructive comments.
This work was performed under the auspices of the U.S. Department of Energy by
Lawrence Livermore National Laboratory under Contract DE-AC52-07NA27344
(LLNL-PROC-679754). Support is gratefully acknowledged from the National
Science Foundation under grants ACI-1535032 and CCF-7298529.

