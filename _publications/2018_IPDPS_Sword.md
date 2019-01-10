---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Sword: A Bounded Memory-Overhead Detector of OpenMP Data Races in Production Runs"
key: 2018_IPDPS_Sword

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2018_IPDPS_Sword

# The shortname is used for auto-generated titels
shortname: Sword
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_IPDPS_Sword.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_IPDPS_Sword.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Simone Atzeni
- Ganesh Gopalakrishnan
- rakamaric
- Ignacio Laguna
- Greg L. Lee
- Dong H. Ahn

journal-short: IPDPS
year: 2018

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 32nd IEEE International Parallel and
    Distributed Processing Symposium (IPDPS)
  editor: Carlo A. Furia and Kirsten Winter
  publisher: IEEE Computer Society
  address: 
  doi: 10.1109/IPDPS.2018.00094
  url: 
  volume: 11023
  number: 
  pages: 845--854
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
pdf: 2018_IPDPS_Sword.pdf
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
Testing is currently the main technique adopted by the industry for improving the quality, reliability, and security of software. In order to lower the cost of manual testing, automatic testing techniques have been devised, such as random and symbolic testing, with their respective trade-offs. For example, random testing excels at fast global exploration of software, while it plateaus when faced with hard-to-hit numerically-intensive execution paths. On the other hand, symbolic testing excels at exploring such paths, while it struggles when faced with complex heap class structures. In this paper, we describe an approach for automatic unit testing of object-oriented software that integrates the two techniques. We leverage feedback-directed unit testing to generate meaningful sequences of constructor+method invocations that create rich heap structures, and we in turn further explore these sequences using dynamic symbolic execution. We implement this approach in a tool called JDoop, which we augment with several parameters for fine-tuning its heuristics; such “knobs” allow for a detailed exploration of the various trade-offs that the proposed integration offers.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
