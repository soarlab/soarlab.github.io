---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Floating-Point Mixed-Precision Tuning"
key: 2017_POPL_FPTuner

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2017_POPL_FPTuner

# The shortname is used for auto-generated titels
shortname: FPTuner
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_POPL_FPTuner.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_POPL_FPTuner.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Wei-Fan Chiang
- baranowski
- Ian Briggs
- Alexey Solovyev
- Ganesh Gopalakrishnan
- rakamaric

journal-short: POPL
year: 2017

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 44th ACM SIGPLAN Symposium on Principles of Programming Languages (POPL)
  editor:
  publisher: ACM
  address: 
  doi:
  url: 
  volume:
  number: 
  pages: 300--315
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
pdf: 2017_POPL_FPTuner.pdf
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
code: https://github.com/soarlab/FPTuner
# https://github.com/soarlab/FPTaylor

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Virtually all real-valued computations are carried out using floating-point data types and operations. The precision of these data types must be set with the goals of reducing the overall round-off error, but also emphasizing performance improvements. Often, a mixed-precision allocation achieves this optimum; unfortunately, there are no techniques available to compute such allocations and conservatively meet a given error target across all program inputs. In this work, we present a rigorous approach to precision allocation based on formal analysis via Symbolic Taylor Expansions, and error analysis based on interval functions. This approach is implemented in an automated tool called FPTuner that generates and solves a quadratically constrained quadratic program to obtain a precision-annotated version of the given expression. FPTuner automatically introduces all the requisite precision up and down casting operations. It also allows users to flexibly control precision allocation using constraints to cap the number of high precision operators as well as group operators to allocate the same precision to facilitate vectorization. We evaluate FPTuner by tuning several benchmarks and measuring the proportion of lower precision operators allocated as we increase the error threshold. We also measure the reduction in energy consumption resulting from executing mixed-precision tuned code on a real hardware platform. We observe significant energy savings in response to mixed-precision tuning, but also observe situations where unexpected compiler behaviors thwart intended optimizations.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
