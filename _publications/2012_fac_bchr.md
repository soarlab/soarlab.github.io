---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Proving Termination of Nonlinear Command Sequences"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2012_fac_bchr

# conference | journal | poster | workshop
type: journal
redirect_from: /2012/06/proving-termination-of-nonlinear-command-sequences

# The shortname is used for auto-generated titles
shortname: FAC 2012
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2012_fac_bchr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2012_fac_bchr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Domagoj Babic
- Byron Cook
- Alan J. Hu
- rakamaric

journal-short: FAC
year: 2012

# bibentry: article | inproceedings | phdthesis | book
bibentry: article
bib:
  journal: Formal Aspects of Computing (FAC)
  series:
  volume: 25
  publisher: Springer
  editor:
  pages: 389--403
  doi: 10.1007/s00165-012-0252-5
  address:
  url:
  number: 3
  month: may
  note:
  issue_date:

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
pdf: 2012_fac_bchr.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Conference Version
  link: /publications/2007_sefm_bchr
  linksym: true
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
We describe a simple and efficient algorithm for proving the termination of a
class of loops with nonlinear assignments to variables. The method is based on
divergence testing for each variable in the cone-of-influence of the loop's
condition. The analysis allows us to automatically prove the termination of
loops that cannot be handled using previous techniques. We also describe a
method for integrating our nonlinear termination proving technique into a
larger termination proving framework that depends on linear reasoning.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank Richard Fateman, Robert Israel, and Daniel Lichtblau for
useful discussions about the complexity of polynomial factorization, divergence
of the update functions, and multivariate limits, and Josh Berdine and Jacopo
Mantovani for their comments on Section 3. We would also like to thank the
anonymous reviewers for many helpful comments and for pointing out the special
case in the computation of safe RGDs.

