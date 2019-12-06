---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Study of Integrating Random and Symbolic Testing for Object-Oriented Software"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2018_ifm_dhlr

# paper | preprint | poster
type: paper
redirect_from: /2018/06/ifm2018-dhlr

# The shortname is used for auto-generated titles
shortname: IFM 2018
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_ifm_dhlr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_ifm_dhlr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- dimjasevic
- Falk Howar
- Kasper Luckow
- rakamaric

journal-short: IFM
year: 2018

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 14th International Conference on
    Integrated Formal Methods (IFM)
  series: Lecture Notes in Computer Science
  volume: 11023
  publisher: Springer
  editor: Carlo A. Furia and Kirsten Winter
  pages: 89--109
  doi: 10.1007/978-3-319-98938-9_6
  address:
  url:
  number:
  month:

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
pdf: 2018_ifm_dhlr.pdf
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
code: https://github.com/psycopaths/jdoop

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
Testing is currently the main technique adopted by the industry for improving
the quality, reliability, and security of software. In order to lower the cost
of manual testing, automatic testing techniques have been devised, such as
random and symbolic testing, with their respective trade-offs. For example,
random testing excels at fast global exploration of software, while it plateaus
when faced with hard-to-hit numerically-intensive execution paths. On the other
hand, symbolic testing excels at exploring such paths, while it struggles when
faced with complex heap class structures. In this paper, we describe an
approach for automatic unit testing of object-oriented software that integrates
the two techniques. We leverage feedback-directed unit testing to generate
meaningful sequences of constructor+method invocations that create rich heap
structures, and we in turn further explore these sequences using dynamic
symbolic execution. We implement this approach in a tool called JDoop, which we
augment with several parameters for fine-tuning its heuristics; such knobs
allow for a detailed exploration of the various trade-offs that the proposed
integration offers.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by the National Science Foundation (NSF) award CCF 1421678.

