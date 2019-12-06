---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Delay-Bounded Scheduling"
key: 2011_POPL_eqr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2011_POPL_eqr

# The shortname is used for auto-generated titels
shortname: 2011_POPL_eqr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2011_POPL_eqr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2011_POPL_eqr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Michael Emmi
- Shaz Qadeer
- rakamaric

journal-short: POPL
year: 2011

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal: Lecture Notes in Computer Science
  booktitle: Proceedings of the 38th ACM SIGPLAN-SIGACT Symposium on Principles of Programming Languages (POPL)
  editor: Thomas Ball and Mooly Sagiv
  publisher: ACM
  address: 
  doi:
  url: 
  volume:
  number: 
  pages: 411--422
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
pdf: 2011_POPL_eqr.pdf
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

abstract: "We provide a new characterization of scheduling nondeterminism by allowing deterministic schedulers to delay their next-scheduled task. In limiting the delays an otherwise-deterministic scheduler is allowed, we discover concurrency bugs efficiently—by exploring few schedules—and robustly—i.e., independent of the number of tasks, context switches, or buffered events. Our characterization elegantly applies to any systematic exploration (e.g., testing, model checking) of concurrent programs with dynamic task-creation. Additionally, we show that certain delaying schedulers admit efficient reductions from concurrent to sequential program analysis."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
