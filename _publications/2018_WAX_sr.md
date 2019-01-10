---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Exploring Floating-Point Trade-Offs in ML"
key: 2018_WAX_sr
#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: commentary
redirect_from: /publications/2018_WAX_sr

# The shortname is used for auto-generated titels
shortname: 2018_WAX_sr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_WAX_sr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_WAX_sr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- salvia
- rakamaric

journal-short: WAX
year: 2018

bibentry: article
bib:
  journal:
  booktitle: Informal Proceedings of the Workshop on Approximate Computing Across the Stack (WAX)
  editor: 
  publisher:
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages: 
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project: https://github.com/soarlab/FPML

# The reference to the video entry
video:
# 2018_tvcg_lineage_video
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2018_WAX_sr.pdf
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
code: https://github.com/soarlab/FPML

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "Perceptron and Support Vector Machine (SVM) algorithms are two well-known and widely used linear predictors. They compute a hypothesis function using supervised learning to predict labels of unknown future samples. Both training and testing procedures are typically implemented using double precision floating-points to minimize the error, which often results in overly conservative implementations that waste runtime and/or energy. In this work, we empirically analyze the impact of floating-point precision on these predictors. We assess whether the precision of reading the dataset, training, or testing is the most critical for the overall accuracy. Our analysis in particular focuses on very small floating-point bit-widths (i.e., only several bits of precision), and compares these against the well-known and widely used single and double precision types."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
