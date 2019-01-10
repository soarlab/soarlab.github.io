---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Efficient Search for Inputs Causing High Floating-point Errors"
key: 2014_PPoPP_BGRT

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2014_PPoPP_BGRT

# The shortname is used for auto-generated titels
shortname: 2014_PPoPP_BGRT
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2014_PPoPP_BGRT.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2014_PPoPP_BGRT.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Wei-Fan Chiang
- Ganesh Gopalakrishnan
- rakamaric
- Alexey Solovyev

journal-short: PPoPP
year: 2014

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal: 
  booktitle: Proceedings of the 19th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming (PPoPP)
  editor: Armin Biere and Roderick Bloem
  publisher: ACM
  address: 
  doi: 
  url: 
  volume: 
  number: 
  pages: 43--52
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
pdf: 2014_PPoPP_BGRT.pdf
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
#https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "Tools for floating-point error estimation are fundamental to program understanding and optimization. In this paper, we focus on tools for determining the input settings to a floating point routine that maximizes its result error. Such tools can help support activities such as precision allocation, performance optimization, and auto-tuning. We benchmark current abstraction-based precision analysis methods, and show that they often do not work at scale, or generate highly pessimistic error estimates, often caused by non-linear operators or complex input constraints that define the set of legal inputs. We show that while concrete-testing-based error estimation methods based on maintaining shadow values at higher precision can search out higher error-inducing inputs, suitable heuristic search guidance is key to finding higher errors. We develop a heuristic search algorithm called Binary Guided Random Testing (BGRT). In 45 of the 48 total benchmarks, including many real-world routines, BGRT returns higher guaranteed errors. We also evaluate BGRT against two other heuristic search methods called ILS and PSO, obtaining better results."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
