---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "An SMT Theory of Fixed-Point Arithmetic"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2020_ijcar_bhlnr

# conference | journal | poster | workshop
type: conference

# The shortname is used for auto-generated titles
shortname: IJCAR 2020
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2020_ijcar_bhlnr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2020_ijcar_bhlnr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- baranowski 
- he
- Mathias Lechner
- nguyen
- rakamaric

journal-short: IJCAR
year: 2020

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 10th International Joint Conference on Automated Reasoning (IJCAR)
  series: Lecture Notes in Computer Science
  volume:
  publisher: Springer
  editor: Nicolas Peltier and Viorica Sofronie-Stokkermans
  pages:
  doi:
  address:
  url:
  number:
  month:
  note: to appear

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
pdf: 2020_ijcar_bhlnr.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: QF_FXP Benchmarks
  abslink: https://github.com/soarlab/QF_FXP
  linksym: true
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hosted
code: https://github.com/soarlab/pysmt

# Link to an official preprint server
preprint_server:
#https://doi.org/10.1101/128579

abstract: "<p>
Fixed-point arithmetic is a popular alternative to floating-point arithmetic on
embedded systems. Existing work on the verification of fixed-point programs
relies on custom formalizations of fixed-point arithmetic, which makes it hard
to compare the described techniques or reuse the implementations. In this paper,
we address this issue by proposing and formalizing an SMT theory of fixed-point
arithmetic. We present an intuitive yet comprehensive syntax of the fixed-point
theory, and provide formal semantics for it based on rational arithmetic. We
also describe two decision procedures for this theory: one based on the theory
of bit-vectors and the other on the theory of reals. We implement the two
decision procedures, and evaluate our implementations using existing mature SMT
solvers on a benchmark suite we created. Finally, we perform a case study of
using the theory we propose to verify properties of quantized neural networks.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was supported in part by NSF awards CCF 1552975, CCF 1704715, and the
Austrian Science Fund (FWF) under grant Z211-N23 (Wittgenstein Award).
