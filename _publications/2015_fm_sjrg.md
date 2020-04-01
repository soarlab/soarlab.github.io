---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Estimation of Floating-Point Round-off Errors with Symbolic Taylor Expansions"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2015_fm_sjrg

# conference | journal | poster | workshop
type: conference
redirect_from: /2015/04/fm2015-sjrg

# The shortname is used for auto-generated titles
shortname: FM 2015
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2015_fm_sjrg.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2015_fm_sjrg_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- solovyev
- Charles Jacobsen
- rakamaric
- Ganesh Gopalakrishnan

journal-short: FM
year: 2015

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 20th International Symposium on Formal Methods (FM)
  series: Lecture Notes in Computer Science
  volume: 9109
  publisher: Springer
  editor: Nikolaj Bj{\o}rner and Frank de Boer
  pages: 532--550
  doi: 10.1007/978-3-319-19249-9_33
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
pdf: 2015_fm_sjrg.pdf
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
code: https://github.com/soarlab/FPTaylor

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Rigorous estimation of maximum floating-point round-off errors is an important
capability central to many formal verification tools. Unfortunately, available
techniques for this task often provide overestimates. Also, there are no
available rigorous approaches that handle transcendental functions. We have
developed a new approach called Symbolic Taylor Expansions that avoids this
difficulty, and implemented a new tool called FPTaylor embodying this approach.
Key to our approach is the use of rigorous global optimization, instead of the
more familiar interval arithmetic, affine arithmetic, and/or SMT solvers. In
addition to providing far tighter upper bounds of round-off error in a vast
majority of cases, FPTaylor also emits analysis certificates in the form of HOL
Light proofs. We release FPTaylor along with our benchmarks for evaluation.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank Nelson Beebe, Wei-Fan Chiang, John Harrison, and Madan
Musuvathi for their feedback and encouragement.  This work is supported in part
by NSF CCF 1421726.

