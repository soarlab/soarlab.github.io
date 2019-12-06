---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Systematic Debugging Methods for Large Scale HPC Computational Frameworks"
key: 2014_CiSE_hmbcrg

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: journal
redirect_from: /publications/2014_CiSE_hmbcrg

# The shortname is used for auto-generated titels
shortname: HMBCRG_CiSE
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2014_cise_hmbcrg.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2014_cise_hmbcrg.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Alan Humphrey
- Qingyu Meng
- Martin Berzins
- Diego Caminha B. de Oliveira
- rakamaric
- Ganesh Gopalakrishnan

journal-short: CiSE
year: 2014

bibentry: article
bib:
  journal: Computing in Science and Engineering (CiSE)
  booktitle: 
  editor: 
  publisher: IEEE
  address: 
  doi: 
  url: 
  volume: 16
  number: 3
  pages: 48--56
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
pdf: 2014_CiSE_hmbcrg.pdf
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
Parallel computational frameworks for high performance computing (HPC) are central to the advancement of simulation based studies in science and engineering. Unfortunately, finding and fixing bugs in these frameworks can be extremely time consuming. Left unchecked, these bugs can drastically diminish the amount of new science that can be performed. This paper presents our systematic study of the Uintah computational framework, and our approaches to debug it more incisively. Our key insight is to leverage the modular structure of Uintah which lends itself to systematic debugging. In particular, we have developed a new approach based on Coalesced Stack Trace Graphs (CSTGs) that summarize the system behavior in terms of key control flows manifested through function invocation chains. We illustrate several scenarios how CSTGs could help efficiently localize bugs, and present a case study of how we found and fixed a real Uintah bug using CSTGs
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
