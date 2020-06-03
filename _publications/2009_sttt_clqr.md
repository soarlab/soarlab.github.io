---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "A Low-Level Memory Model and an Accompanying Reachability Predicate"
key: 2009_sttt_clqr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: journal
redirect_from: /publications/2009_sttt_clqr

# The shortname is used for auto-generated titels
shortname: CLQR_STTT
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2009_sttt_clqr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2009_sttt_clqr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Shaunak Chatterjee
- Shuvendu Lahiri
- Shaz Qadeer
- rakamaric

journal-short: STTT
year: 2009

bibentry: article
bib:
  journal: International Journal on Software Tools for Technology Transfer (STTT)
  booktitle: 
  editor: 
  publisher: Springer
  address: 
  doi: 
  url: 
  volume: 11
  number: 2
  pages: 105-116
  month: February

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
# The reference to the preview video entry
#preview-video:

# the prerint
pdf: 2009_sttt_clqr.pdf
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

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Reasoning about program heap, especially if it involves handling unbounded, dynamically heap-allocated data structures such as linked lists and arrays, is challenging. Furthermore, sound analysis that precisely models heap becomes significantly more challenging in the presence of low-level pointer manipulation that is prevalent in systems software.
The reachability predicate has already proved to be useful for reasoning about the heap in type-safe languages where memory is manipulated by dereferencing object fields. In this paper, we present a memory model suitable for reasoning about low-level pointer operations that is accompanied by a formalization of the reachability predicate in the presence of internal pointers and pointer arithmetic. We have designed an annotation language for C programs that makes use of the new predicate. This language enables us to specify properties of many interesting data structures present in the Windows kernel. We present our experience with a prototype verifier on a set of illustrative C benchmarks.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
