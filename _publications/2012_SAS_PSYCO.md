---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Symbolic Learning of Component Interfaces"
key: 2012_SAS_PSYCO

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2012_SAS_PSYCO

# The shortname is used for auto-generated titels
shortname: 2012_SAS_PSYCO
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2012_SAS_PSYCO.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2012_SAS_PSYCO.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Dimitra Giannakopoulou
- rakamaric
- Vishwanath Raman

journal-short: SAS
year: 2012

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal: Lecture Notes in Computer Science
  booktitle: Proceedings of the 19th International Static Analysis Symposium (SAS 2012)
  editor: Antoine Min\'e and David Schmidt
  publisher: Springer
  address: 
  doi:
  url: 
  volume: 7460
  number: 
  pages: 248--264
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
pdf: 2012_SAS_PSYCO.pdf
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

abstract: "Given a white-box component C with specified unsafe states, we address the problem of automatically generating an interface that captures safe orderings of invocations of C’s public methods. Method calls in the generated interface are guarded by constraints on their parameters. Unlike previous work, these constraints are generated automatically through an iterative refinement process. Our technique, named PSYCO (Predicate-based SYmbolic COmpositional reasoning), employs a novel combination of the L* automata learning algorithm with symbolic execution. The generated interfaces are three-valued, capturing whether a sequence of method invocations is safe, unsafe, or its effect on the component state is unresolved by the symbolic execution engine. We have implemented PSYCO as a new prototype tool in the JPF open-source software model checking platform, and we have successfully applied it to several examples."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
