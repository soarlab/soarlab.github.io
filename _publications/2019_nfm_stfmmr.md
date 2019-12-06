---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "A Mixed Real and Floating-Point Solver"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2019_nfm_stfmmr

# paper | preprint | poster
type: paper
redirect_from: /2019/05/nfm2019-stfmmr

# The shortname is used for auto-generated titles
shortname: NFM 2019
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_nfm_stfmmr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2019_nfm_stfmmr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- salvia
- Laura Titolo
- Marco A. Feliú
- Mariano M. Moscato
- César A. Muñoz
- rakamaric

journal-short: NFM
year: 2019

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 11th Annual NASA Formal Methods Symposium (NFM)
  series: Lecture Notes in Computer Science
  volume: 11460
  publisher: Springer
  editor: Julia Badger and Kristin Yvonne Rozier
  pages: 363--370
  doi: 10.1007/978-3-030-20652-9_25
  address:
  url:
  number:
  month:

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
pdf: 2019_nfm_stfmmr.pdf
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
code: https://github.com/nasa/FPRoCK 

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
Reasoning about mixed real and floating-point constraints is essential for
developing accurate analysis tools for floating-point programs. This paper
presents FPRoCK, a prototype tool for solving mixed real and floating-point
formulas. FPRoCK transforms a mixed formula into an equisatisfiable one over the
reals. This formula is then solved using an off-the-shelf SMT solver. FPRoCK is
also integrated with the PRECiSA static analyzer, which computes a sound
estimation of the round-off error of a floating-point program. It is used to
detect infeasible computational paths, thereby improving the accuracy of
PRECiSA.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Partially supported by NSF awards CCF 1346756 and CCF 1704715.

Research by the first four authors was supported by the National Aeronautics and
Space Administration under NASA/NIA Cooperative Agreement NNL09AA00A.
