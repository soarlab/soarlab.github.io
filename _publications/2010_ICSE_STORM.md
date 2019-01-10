---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "STORM: Static Unit Checking of Concurrent Programs"
key: 2010_ICSE_STORM

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2010_ICSE_STORM

# The shortname is used for auto-generated titels
shortname: 2010_ICSE_STORM
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2010_ICSE_STORM.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2010_ICSE_STORM.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- rakamaric

journal-short: ICSE
year: 2010

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 32nd ACM/IEEE International Conference on Software Engineering (ICSE 2010) - Volume 2
  editor: Jeff Kramer and Judith Bishop and Premkumar T. Devanbu and Sebasti{\'a}n Uchitel
  publisher: ACM
  address: 
  doi:
  url: 
  volume:
  number: 
  pages: 519--520
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: Silver Medal Winner in the Competition.

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
pdf: 2010_ICSE_STORM.pdf
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

abstract: "Concurrency is inherent in today’s software. Unexpected interactions between concurrently executing threads often cause subtle bugs in concurrent programs. Such bugs are hard to discover using traditional testing techniques since they require executing a program on a particular unit test (i.e. input) through a particular thread interleaving. A promising solution to this problem is static program analysis since it can simultaneously check a concurrent program on all inputs as well as through all possible thread interleavings. This paper describes a scalable, automatic, and precise approach to static unit checking of concurrent programs implemented in a tool called STORM. STORM has been applied on a number of real-world Windows device drivers, and the tool found a previously undiscovered concurrency bug in a driver from Microsoft’s Driver Development Kit."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
