---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Hybrid Learning: Interface Generation through Static, Dynamic, and Symbolic Analysis"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2013_issta_hgr

# conference | journal | poster | workshop
type: conference
redirect_from: /2013/06/hybrid-learning-interface-generation-through-static-dynamic-and-symbolic-analysis

# The shortname is used for auto-generated titles
shortname: ISSTA 2013
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2013_issta_hgr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2013_issta_hgr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Falk Howar
- Dimitra Giannakopoulou
- rakamaric

journal-short: ISSTA
year: 2013

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the International Symposium on Software Testing and
    Analysis (ISSTA)
  series:
  volume:
  publisher: ACM
  editor:
  pages: 268--279
  doi: 10.1145/2483760.2483783
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
pdf: 2013_issta_hgr.pdf
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
This paper addresses the problem of efficient generation of component
interfaces through learning. Given a white-box component C with specified
unsafe states, an interface captures safe orderings of invocations of C's
public methods. In previous work we presented PSYCO, an interface generation
framework that combines automata learning with symbolic component analysis:
learning drives the framework in exploring different combinations of method
invocations, and symbolic analysis computes method guards corresponding to
constraints on the method parameters for safe execution. In this work we
propose solutions to the two main bottlenecks of PSYCO. The explosion of method
sequences that learning generates to validate its computed interfaces is
reduced through partial order reduction resulting from a static analysis of the
component. To avoid scalability issues associated with symbolic analysis, we
propose novel algorithms that are primarily based on dynamic, concrete
component execution, while resorting to symbolic analysis on a limited, as
needed, basis. Dynamic execution enables the introduction of a concept of state
matching, based on which our proposed approach detects, in some cases, that it
has exhausted the exploration of all component behaviors. On the other hand,
symbolic analysis is enhanced with symbolic summaries. Our new approach,
X-PSYCO, has been implemented in the Java Pathfinder (JPF) software
verification platform. We demonstrated the effectiveness of X-PSYCO on a number
of realistic software components by generating more complete and precise
interfaces than was previously possible.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank Vishwanath Raman for many fruitful discussions and his
help with jpf-jdart, Peter Mehlitz for the suggested improvements concerning
the integration with JPF, Oksana Tkachuk for providing support for the static
analysis engine in OCSEGen, and Malte Isberner and Marko Dimjasevic for their
helpful feedback. This research was partly sponsored by United States National
Aeronautics and Space Administration (NASA) under Prime Contract No.
NNA10DE60C.

