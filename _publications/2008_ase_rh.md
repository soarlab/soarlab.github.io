---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Automatic Inference of Frame Axioms Using Static Analysis"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2008_ase_rh

# conference | journal | poster | workshop
type: conference
redirect_from: /2008/09/automatic-inference-of-frame-axioms-using-static-analysis

# The shortname is used for auto-generated titles
shortname: ASE 2008
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2008_ase_rh.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2008_ase_rh_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- rakamaric
- Alan J. Hu

journal-short: ASE
year: 2008

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 23rd IEEE/ACM International Conference on
    Automated Software Engineering (ASE)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 89--98
  doi: 10.1109/ASE.2008.19
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
pdf: 2008_ase_rh.pdf
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
code: https://github.com/smackers/smack

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Many approaches to software verification are currently semi-automatic: a human
must provide key logical insights - e.g., loop invariants, class invariants,
and frame axioms that limit the scope of changes that must be analyzed.  This
paper describes a technique for automatically inferring frame axioms of
procedures and loops using static analysis. The technique builds on a pointer
analysis that generates limited information about all data structures in the
heap. Our technique uses that information to over-approximate a potentially
unbounded set of memory locations modified by each procedure/loop; this
over-approximation is a candidate frame axiom.  We have tested this approach on
the buffer-overflow benchmarks from ASE 2007. With manually provided
specifications and invariants/axioms, our tool could verify/falsify 226 of the
289 benchmarks. With our automatically inferred frame axioms, the tool could
verify/falsify 203 of the 289, demonstrating the effectiveness of our approach.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was supported by the Natural Sciences and Engineering Research
Council of Canada and a University of British Columbia Graduate Fellowship.

