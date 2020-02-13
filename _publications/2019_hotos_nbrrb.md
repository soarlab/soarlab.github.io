---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "RedLeaf: Towards An Operating System for Safe and Verified Firmware"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2019_hotos_nbrrb

# conference | journal | poster | workshop
type: workshop

# The shortname is used for auto-generated titles
shortname: HotOS 2019
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2019_hotos_nbrrb.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2019_hotos_nbrrb_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Vikram Narayanan
- baranowski
- Leonid Ryzhyk
- rakamaric
- Anton Burtsev

journal-short: HotOS
year: 2019

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  title: "RedLeaf: Towards An Operating System for Safe and Verified Firmware"
  year: 2019
  isbn: 9781450367271
  publisher: Association for Computing Machinery
  address: New York, NY, USA
  url: "https://doi.org/10.1145/3317550.3321449"
  doi: 10.1145/3317550.3321449
  booktitle: Proceedings of the Workshop on Hot Topics in Operating Systems
  pages: 37–44
  numpages: 8
  location: Bertinoro, Italy
  series: HotOS '19

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
pdf: 2014_hotos_nbrrb.pdf
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
#https://doi.org/10.1145/3317550.3321449

abstract: "<p>
RedLeaf is a new operating system being developed from scratch to utilize formal verification for implementing provably secure firmware. RedLeaf is developed in a safe language, Rust, and relies on automated reasoning using satisfiability modulo theories (SMT) solvers for formal verification. RedLeaf builds on two premises: (1) Rust’s linear type system enables practical language safety even for systems with tightest performance and resource budgets (e.g., firmware), and (2) a combination of SMT-based reasoning and pointer discipline enforced by linear types provides a unique way to automate and simplify verification effort scaling it to the size of a small OS kernel.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This material is partially based upon work supported by Intel and the National Science Foundation under grants number 1837127 and 1837051.

