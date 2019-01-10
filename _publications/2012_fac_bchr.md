---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Proving Termination of Nonlinear Command Sequences"
key: 2012_fac_bchr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: preprint
redirect_from: /publications/2012_fac_bchr

# The shortname is used for auto-generated titels
shortname: BCHR_Fac
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2012_fac_bchr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2012_fac_bchr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Domagoj Babic
- Byron Cook
- Alan J. Hu
- rakamaric

journal-short: FAC
year: 2012

bibentry: article
bib:
  journal: Formal Aspects of Computing (FAC)
  booktitle: 
  editor: 
  publisher: Springer
  address: 
  doi: 
  url: 
  volume: 25
  number: 3
  pages: 389--403 
  month: May

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
pdf: 2012_fac_bchr.pdf
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

abstract: "
We describe a simple and efficient algorithm for proving the termination of a class of loops with nonlinear assignments to variables. The method is based on divergence testing for each variable in the cone-of-influence of the loop’s condition. The analysis allows us to automatically prove the termination of loops that cannot be handled using previous techniques. We also describe a method for integrating our nonlinear termination proving technique into a larger termination proving framework that depends on linear reasoning.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
