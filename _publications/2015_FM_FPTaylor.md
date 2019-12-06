---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Estimation of Floating-Point Round-off Errors with Symbolic Taylor Expansions"
key: 2015_FM_FPTaylor

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2015_FM_FPTaylor

# The shortname is used for auto-generated titels
shortname: 2015_FM_FPTaylor
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2015_FM_FPTaylor.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2015_FM_FPTaylor.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Alexey Solovyev
- Charles Jacobsen
- rakamaric
- Ganesh Gopalakrishnan

journal-short: FM
year: 2015

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 20th International Symposium on Formal Methods (FM)
  editor: Nikolaj Bj{\o}rner and Frank de Boer
  publisher: Springer
  address: 
  doi:
  url: 
  volume: 9109
  number: 
  pages: 532--550
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
pdf: 2015_FM_FPTaylor.pdf
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
code: https://github.com/soarlab/FPTaylor
#https://github.com/psycopaths/jdart

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Rigorous estimation of maximum floating-point round-off errors is an important capability central to many formal verification tools. Unfortunately, available techniques for this task often provide overestimates. Also, there are no available rigorous approaches that handle transcendental functions. We have developed a new approach called Symbolic Taylor Expansions that avoids this difficulty, and implemented a new tool called FPTaylor embodying this approach. Key to our approach is the use of rigorous global optimization, instead of the more familiar interval arithmetic, affine arithmetic, and/or SMT solvers. In addition to providing far tighter upper bounds of round-off error in a vast majority of cases, FPTaylor also emits analysis certificates in the form of HOL Light proofs. We release FPTaylor along with our benchmarks for evaluation.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
