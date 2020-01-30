---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "JDart: A Dynamic Symbolic Analysis Framework"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2016_tacas_ldghikrr

# conference | journal | poster | workshop
type: conference
redirect_from: /2016/01/tacas2016-ldghikrr

# The shortname is used for auto-generated titles
shortname: TACAS 2016
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_tacas_ldghikrr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_tacas_ldghikrr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Kasper Luckow
- dimjasevic
- Dimitra Giannakopoulou
- Falk Howar
- Malte Isberner
- Temesghen Kahsai
- rakamaric
- Vishwanath Raman

journal-short: TACAS
year: 2016

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 22nd International Conference on Tools and
    Algorithms for the Construction and Analysis of Systems (TACAS)
  series: Lecture Notes in Computer Science
  volume: 9636
  publisher: Springer
  editor: Marsha Chechik and Jean-Fran{\c{c}}ois Raskin
  pages: 442--459
  doi: 10.1007/978-3-662-49674-9_26
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
pdf: 2016_tacas_ldghikrr.pdf
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
code: https://github.com/psycopaths/jdart

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
We describe JDart, a dynamic symbolic analysis framework for Java. A
distinguishing feature of JDart is its modular architecture: the main component
that performs dynamic exploration communicates with a component that
efficiently constructs constraints and that interfaces with constraint solvers.
These components can easily be extended or modified to support multiple
constraint solvers or different exploration strategies. Moreover, JDart has
been engineered for robustness, driven by the need to handle complex NASA
software. These characteristics, together with its recent open sourcing, make
JDart an ideal platform for research and experimentation. In the current
release, JDart supports the CORAL, SMTInterpol, and Z3 solvers, and is able to
handle NASA software with constraints containing bit operations, floating point
arithmetic, and complex arithmetic operations (e.g., trigonometric and
nonlinear). We illustrate how JDart has been used to support other analysis
techniques, such as automated interface generation and testing of libraries.
Finally, we demonstrate the versatility and effectiveness of JDart, and compare
it with state-of-the-art dynamic or pure symbolic execution engines through an
extensive experimental evaluation.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by NASA Contr. NNX14AI09G and NSF CCF 1421678/1422705.

