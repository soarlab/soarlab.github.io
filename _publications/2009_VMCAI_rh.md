---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "A Scalable Memory Model for Low-Level Code"
key: 2009_VMCAI_rh

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2009_VMCAI_rh

# The shortname is used for auto-generated titels
shortname: 2009_VMCAI_rh
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2009_VMCAI_rh.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2009_VMCAI_rh.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- rakamaric
- Alan J. Hu.

journal-short: VMCAI
year: 2009

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 10th International Conference on Verification, Model Checking and Abstract Interpretation (VMCAI 2009)
  editor: Neil D. Jones and Markus M{\"u}ller-Olm
  publisher: Springer
  address: 
  doi: 
  url: 
  volume: 5403
  number: 
  pages: 290--304
  month: January

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
pdf: 2009_VMCAI_rh.pdf
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

abstract: "Because of its critical importance underlying all other software, low-level system software is among the most important targets for formal verification. Low-level systems software must sometimes make type-unsafe memory accesses, but because of the vast size of available heap memory in today’s computer systems, faithfully representing each memory allocation and access does not scale when analyzing large programs. Instead, verification tools rely on abstract memory models to represent the program heap. This paper reports on two related investigations to develop an accurate (i.e., providing a useful level of soundness and precision) and scalable memory model: First, we compare a recently introduced memory model, specifically designed to more accurately model low-level memory accesses in systems code, to an older, widely adopted memory model. Unfortunately, we find that the newer memory model scales poorly compared to the earlier, less accurate model. Next, we investigate how to improve the soundness of the less accurate model. A direct approach is to add assertions to the code that each memory access does not break the assumptions of the memory model, but this causes verification complexity to blow-up. Instead, we develop a novel, extremely lightweight static analysis that quickly and conservatively guarantees that most memory accesses safely respect the assumptions of the memory model, thereby eliminating almost all of these extra type-checking assertions. Furthermore, this analysis allows us to create automatically memory models that flexibly use the more scalable memory model for most of memory, but resorting to a more accurate model for memory accesses that might need it."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
