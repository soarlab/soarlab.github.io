---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Asynchronously Communicating Visibly Pushdown Systems"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2013_forte_br

# conference | journal | poster | workshop
type: conference
redirect_from: /2013/03/asynchronously-communicating-visibly-pushdown-systems

# The shortname is used for auto-generated titles
shortname: FORTE/FMOODS 2013
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2013_forte_br.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2013_forte_br_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Domagoj Babic
- rakamaric

journal-short: FORTE/FMOODS
year: 2013

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the IFIP Joint International Conference on
    Formal Techniques for Distributed Systems (33rd FORTE/15th FMOODS)
  series: Lecture Notes in Computer Science
  volume: 7892
  publisher: Springer
  editor: Dirk Beyer and Michele Boreale
  pages: 225--241
  doi: 10.1007/978-3-642-38592-6_16
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
# The reference to the preview video entry
#preview-video:

# the preprint
pdf: 2013_forte_br.pdf
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
We introduce an automata-based formal model suitable for specifying, modeling,
analyzing, and verifying asynchronous task-based and message-passing programs.
Our model consists of visibly pushdown automata communicating over unbounded
reliable point-to-point first-in-first-out queues. Such a combination unifies
two branches of research, one focused on task-based models, and the other on
models of message-passing programs. Our model generalizes previously proposed
models that have decidable reachability in several ways. Unlike task-based
models of asynchronous programs, our model allows sending and receiving of
messages even when stacks are not empty, without imposing restrictions on the
number of context-switches or communication topology. Our model also
generalizes the well-known communicating finite-state machines with
recognizable channel property allowing (1) individual components to be visibly
pushdown automata, which are more suitable for modeling (possibly recursive)
programs, (2) the set of words (i.e., languages) of messages on queues to form
a visibly pushdown language, which permits modeling of remote procedure calls
and simple forms of counting, and (3) the relations formed by tuples of such
languages to be synchronized, which permits modeling of complex interactions
among processes. In spite of these generalizations, we prove that the composite
configuration and control-state reachability are still decidable for our model.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank Brad Bingham, Jesse Bingham, Matko Botincan, Steven
McCamant, Jan Pachl, Shaz Qadeer, and Serdar Tasiran for their feedback on the
early drafts of this document. The first author did this work while he was at
UC Berkeley, where his research was sponsored by LLNL.

