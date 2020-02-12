---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "SMACK Software Verification Toolchain"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2016_icse_chwre

# conference | journal | poster | workshop
type: conference
redirect_from: /2016/02/icse2016-chwre

# The shortname is used for auto-generated titles
shortname: ICSE 2016
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_icse_chwre.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_icse_chwre_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- carter
- he
- whitaker
- rakamaric
- Michael Emmi

journal-short: ICSE
year: 2016

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 38th IEEE/ACM International Conference on
    Software Engineering (ICSE) Companion
  series:
  volume:
  publisher: ACM
  editor: Willem Visser and Laurie Williams
  pages: 589--592
  doi: 10.1145/2889160.2889163
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
video: https://youtu.be/SPPSC1KdRzs
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2016_icse_chwre.pdf
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
Tool prototyping is an essential step in developing novel software verification
algorithms and techniques. However, implementing a verifier prototype that can
handle real-world programs is a huge endeavor, which hinders researchers by
forcing them to spend more time engineering tools, and less time innovating. In
this paper, we present the SMACK software verification toolchain. The toolchain
provides a modular and extensible software verification ecosystem that
decouples the front-end source language details from back-end verification
algorithms. It achieves that by translating from the LLVM compiler intermediate
representation into the Boogie intermediate verification language. SMACK
benefits the software verification community in several ways: (i) it can be
used as an off-the-shelf software verifier in an applied software verification
project, (ii) it enables researchers to rapidly develop and release new
verification algorithms, (iii) it allows for adding support for new languages
in its front-end. We have used SMACK to verify numerous C/C++ programs,
including industry examples, showing it is mature and competitive. Likewise,
SMACK is already being used in several existing verification research
prototypes.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by the University of Utah Office of Undergraduate Research
and NSF CCF 1346756/1421678.

