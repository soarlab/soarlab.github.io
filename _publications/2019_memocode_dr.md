---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "A Timeless Model for The Verification of Quasi-Periodic Distributed Systems"
key: 2019_memocode_dr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2019_memocode_dr

# The shortname is used for auto-generated titels
shortname: 2019_memocode_dr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_memocode_dr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1600px, height: 800px) to the folder /assets/images/papers/
image_large: 2019_memocode_dr_teaser.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- dabaghchian
- rakamaric

journal-short: MEMOCODE
year: 2019

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 17th ACM/IEEE International Conference on Formal Methods and Models for System Design (MEMOCODE)
  series: MEMOCODE '19
  editor: 
  publisher: ACM
  address: New York, NY, USA
  doi: 10.1145/3359986.3361201
  url: http://doi.acm.org/10.1145/3359986.3361201
  volume:
  number: 
  pages: 4:1--4:11
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
pdf: 2019_memocode_dr.pdf
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

abstract: "<p>
A cyber-physical system often consists of distributed multi-rate periodic processes that communicate using message passing; each process owns a local clock not synchronized with others. We call such systems quasi-periodic distributed systems. Traditionally, one would model them using timed automata, thereby having to deal with high-complexity verification problems. Recently, several researchers proposed discrete-time abstractions based on the calendar model to make the verification more tractable. However, even the calendar model contains a notion of time in the form of a global clock. We propose a novel, timeless computation model for quasi-periodic distributed systems to facilitate their verification. The main idea behind our model is to judiciously replace synchronization using a global clock and calendar with synchronization over lengths of message buffers. We introduce a simple domain-specific language for programming of such systems and use it to formalize the semantics of both the calendar and timeless model. Then, we prove that our timeless model is an overapproximation of the calendar model. Finally, we evaluate our timeless model using several benchmarks.
</p>"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
### Acknowledgements
This work was supported in part by the National Science Foundation (NSF) awards CCF 1552975 and CCF 1837051. We thank Ankush Desai for introducing us to the problem of the verification of quasi-periodic distributed systems. We also thank Natarajan Shankar for insightful discussions that helped us to improve this paper.

