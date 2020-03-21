---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Delay-Bounded Scheduling"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2011_popl_eqr

# conference | journal | poster | workshop
type: conference
redirect_from: /2011/01/delay-bounded-scheduling

# The shortname is used for auto-generated titles
shortname: POPL 2011
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2011_popl_eqr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2011_popl_eqr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Michael Emmi
- Shaz Qadeer
- rakamaric

journal-short: POPL
year: 2011

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 38th ACM SIGPLAN Symposium on Principles of
    Programming Languages (POPL)
  series:
  volume:
  publisher: ACM
  editor:
  pages: 411--422
  doi: 10.1145/1926385.1926432
  address:
  url:
  number:
  month:
  note:

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:

# The reference to the video entry
video:
# The reference to the preview viedo entry
#preview-video:

# the preprint
pdf: 2011_popl_eqr.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code:

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
We provide a new characterization of scheduling nondeterminism by allowing
deterministic schedulers to delay their next-scheduled task. In limiting the
delays an otherwise-deterministic scheduler is allowed, we discover concurrency
bugs efficiently — by exploring few schedules — and robustly — i.e.,
independent of the number of tasks, context switches, or buffered events. Our
characterization elegantly applies to any systematic exploration (e.g.,
testing, model checking) of concurrent programs with dynamic task-creation.
Additionally, we show that certain delaying schedulers admit efficient
reductions from concurrent to sequential program analysis.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We thank Ahmed Bouajjani, Pierre Ganty, Rupak Majumdar, and Gennaro Parlato for
providing helpful insight, and the anonymous reviewers for their numerous
comments and suggestions.

