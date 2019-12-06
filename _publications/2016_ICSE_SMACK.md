---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "SMACK Software Verification Toolchain"
key: 2016_ICSE_SMACK

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2016_ICSE_SMACK

# The shortname is used for auto-generated titels
shortname: 2016_ICSE_SMACK
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_ICSE_SMACK.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_ICSE_SMACK.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Montgomery Carter
- he
- Jonathan Whitaker
- rakamaric
- Michael Emmi

journal-short: ICSE
year: 2016

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 38th IEEE/ACM International Conference on Software Engineering (ICSE) Companion
  editor: Willem Visser and Laurie Williams
  publisher: ACM
  address: 
  doi: 10.1109/IPDPS.2016.68
  url: 
  volume:
  number: 
  pages: 589--592
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:
#https://github.com/soarlab/FPTaylor

# The reference to the video entry
video:
# 2018_tvcg_lineage_video
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2016_ICSE_SMACK.pdf
# A supplement PDF
supplement: 
#2018_tvcg_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Tool prototyping is an essential step in developing novel software verification algorithms and techniques. However, implementing a verifier prototype that can handle real-world programs is a huge endeavor, which hinders researchers by forcing them to spend more time engineering tools, and less time innovating. In this paper, we present the SMACK software verification toolchain. The toolchain provides a modular and extensible software verification ecosystem that decouples the front-end source language details from back-end verification algorithms. It achieves that by translating from the LLVM compiler intermediate representation into the Boogie intermediate verification language. SMACK benefits the software verification community in several ways: (i) it can be used as an off-the-shelf software verifier in an applied software verification project, (ii) it enables researchers to rapidly develop and release new verification algorithms, (iii) it allows for adding support for new languages in its front-end. We have used SMACK to verify numerous C/C++ programs, including industry examples, showing it is mature and competitive. Likewise, SMACK is already being used in several existing verification research prototypes. Our demonstration of SMACK can be found on YouTube at the following address: https://youtu.be/SPPSC1KdRzs
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
