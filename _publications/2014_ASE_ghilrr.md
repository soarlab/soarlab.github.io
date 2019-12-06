---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Taming Test Inputs for Separation Assurance"
key: 2014_ASE_ghilrr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2014_ASE_ghilrr

# The shortname is used for auto-generated titels
shortname: 2014_ASE_ghilrr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2014_ASE_ghilrr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2014_ASE_ghilrr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Dimitra Giannakopoulou
- Falk Howar
- Malte Isberner
- Todd Lauderdale
- rakamaric
- Vishwanath Raman

journal-short: ASE
year: 2014

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 29th IEEE/ACM International Conference on Automated Software Engineering (ASE)
  editor: Christel Baier and Cesare Tinelli
  publisher: ACM
  address: 
  doi:
  url: 
  volume:
  number: 
  pages: 373--384
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
pdf: 2014_ASE_ghilrr.pdf
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
code: 

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "The Next Generation Air Transportation System (NextGen) advocates the use of innovative algorithms and software to address the increasing load on air-traffic control. AutoResolver is a large, complex NextGen component that provides separation assurance between multiple airplanes up to 20 minutes ahead of time. Our work targets the development of a light-weight, automated testing environment for AutoResolver. The input space of AutoResolver consists of airplane trajectories, each trajectory being a sequence of hundreds of points in the three-dimensional space. Generating meaningful test cases for AutoResolver that cover its behavioral space to a satisfactory degree is a major challenge. We discuss how we tamed this input space to make it amenable to test case generation techniques, as well as how we developed and validated an extensible testing environment around AutoResolver."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
