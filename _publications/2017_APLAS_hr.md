---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Counterexample-Guided Bit-Precision Selection"
key: 2017_APLAS_hr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2017_APLAS_hr

# The shortname is used for auto-generated titels
shortname: APLAS_hr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_APLAS_hr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_APLAS_hr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- he
- rakamaric

journal-short: APLAS
year: 2017

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 15th Asian Symposium on Programming
    Languages and Systems (APLAS)
  editor: Bor-Yuh Evan Chang
  publisher: Springer
  address: 
  doi: 10.1007/978-3-319-71237-6_26
  url: 
  volume: 10695
  number: 
  pages: 534--553
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
pdf: 2017_APLAS_hr.pdf
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
# https://github.com/soarlab/FPTaylor

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Static program verifiers based on satisfiability modulo theories (SMT) solvers often trade precision for scalability to be able to handle large programs. A popular trade-off is to model bitwise operations, which are expensive for SMT solving, using uninterpreted functions over integers. Such an over-approximation improves scalability, but can introduce undesirable false alarms in the presence of bitwise operations that are common in, for example, low-level systems software. In this paper, we present our approach to diagnose the spurious counterexamples caused by this trade-off, and leverage the learned information to lazily and gradually refine the precision of reasoning about bitwise operations in the whole program. Our main insight is to employ a simple and fast type analysis to transform both a counterexample and program into their more precise versions that block the diagnosed spurious counterexample. We implement our approach in the SMACK software verifier, and evaluate it on the benchmark suite from the International Competition on Software Verification (SV-COMP). The evaluation shows that we significantly reduce the number of false alarms while maintaining scalability.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
