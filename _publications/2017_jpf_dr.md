---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Consistency-Aware Scheduling for Weakly Consistent Programs"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2017_jpf_dr

# conference | journal | poster | workshop
type: workshop
redirect_from: /2017/09/jpf2017-dromt

# The shortname is used for auto-generated titles
shortname: JPF 2017
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_jpf_dr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1600px, height: 800px) to the folder /assets/images/papers/
image_large: 2017_jpf_dr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- dabaghchian
- rakamaric

journal-short: JPF
year: 2017

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: ACM SIGSOFT Software Engineering Notes
  series:
  volume: 42
  publisher: ACM
  editor:
  pages: 1--5
  doi: 10.1145/3149485.3149493
  address:
  url: 
  number: 4
  month: October
  note: Proceedings of the 2017 Java Pathfinder Workshop (JPF)

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project: https://pages.lip6.fr/syncfree/index.html

# The reference to the video entry
video:
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2017_jpf_dr.pdf
# A supplement PDF
supplement: 2017_techrep_dr.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code: https://github.com/Maryam81609/commander

# Link to an official preprint server
preprint_server: https://doi.org/10.1145/3149485.3149493
#https://doi.org/10.1145/3149485.3149493

abstract: "<p>
Modern geo-replicated data stores provide high availability by relaxing the underlying consistency requirements. Programs layered over such data stores are called weakly consistent programs. Due to the reduced consistency requirements, they exhibit highly nondeterministic behaviors, some of which might violate program invariants. Therefore, implementing correct weakly consistent programs and reasoning about them is challenging. In this paper, we present a systematic scheduling approach that is aware of the underlying consistency model. Our approach dynamically explores all possible program behaviors allowed by the used data store consistency model, and it evaluates program invariants during the exploration. We implement the approach in a prototype model checker for Antidote, which is a causally consistent key-value data store with convergent conflict handling. We evaluate our tool on several benchmarks. The results show that our approach is effective in detecting buggy behaviors in weakly consistent programs.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This research is supported in part by European FP7 project 609 551 SyncFree (2013–2016).

