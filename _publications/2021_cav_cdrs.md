---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Rigorous Roundoff Error Analysis of Probabilistic Floating-Point Computations"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2021_cav_cdrs

# conference | journal | poster | workshop
type: conference

# The shortname is used for auto-generated titles
shortname: CAV 2021
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2020_vmcai_gbhr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2021_cav_cdrs_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- George Constantinides
- Fredrik Dahlqvist 
- rakamaric
- salvia

journal-short: CAV
year: 2021

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 33rd International Conference on Computer-Aided Verification (CAV)
  series: Lecture Notes in Computer Science
  publisher: Springer
  volume:
  editor: Rustan Leino and Alexandra Silva
  pages:
  doi:
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
pdf: 2021_cav_cdrs.pdf

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
code: https://github.com/soarlab/paf

# Link to an official preprint server
preprint_server: https://arxiv.org/pdf/2105.13217.pdf

abstract: "<p>
We present a detailed study of roundoff errors in probabilistic
floating-point computations. We derive closed-form expressions for the
distribution of roundoff errors associated with a random variable, and
we prove that roundoff errors are generally close to being uncorrelated
with their generating distribution. Based on these theoretical advances,
we propose a model of IEEE floating-point arithmetic for numerical ex-
pressions with probabilistic inputs and an algorithm for evaluating this
model. Our algorithm provides rigorous bounds to the output and error
distributions of arithmetic expressions over random variables, evaluated
in the presence of roundoff errors. It keeps track of complex dependen-
cies between random variables using an SMT solver, and is capable of
providing sound but tight probabilistic bounds to roundoff errors using
symbolic affine arithmetic. We implemented the algorithm in the PAF
tool, and evaluated it on FPBench, a standard benchmark suite for the
analysis of roundoff errors. Our evaluation shows that PAF computes
tighter bounds than current state-of-the-art on almost all benchmarks.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

PAF is supported in part by the National Science Foundation awards CCF 1552975, 
1704715, the Engineering and Physical Sciences Research Council (EP/P010040/1), 
and the Leverhulme Project Grant ''Verification of Machine Learning Algorithms''.
