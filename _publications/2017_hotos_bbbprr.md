---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "System Programming in Rust: Beyond Safety"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2017_hotos_bbbprr

# conference | journal | poster | workshop
type: workshop
redirect_from: /2017/06/hotos2017-bbbprr

# The shortname is used for auto-generated titles
shortname: HotOS 2017
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2017_hotos_bbbprr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2017_hotos_bbbprr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Abhiram Balasubramanian
- baranowski
- Anton Burtsev
- Aurojit Panda
- rakamaric
- Leonid Ryzhyk

journal-short: HotOS
year: 2017

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 16th Workshop on Hot Topics in Operating Systems (HotOS)
  series:
  volume:
  publisher: ACM
  editor:
  pages: 156--161
  doi: 10.1145/3139645.3139660
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
pdf: 2017_hotos_bbbprr.pdf
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
Rust is a new system programming language that offers a practical and safe
alternative to C. Rust is unique in that it enforces safety without runtime
overhead, most importantly, without the overhead of garbage collection. While
zero-cost safety is remarkable on its own, we argue that the superpowers of
Rust go beyond safety. In particular, Rust's linear type system enables
capabilities that cannot be implemented efficiently in traditional languages,
both safe and unsafe, and that dramatically improve security and reliability of
system software. We show three examples of such capabilities: zero-copy
software fault isolation, efficient static information flow analysis, and
automatic checkpointing. While these capabilities have been in the spotlight of
systems research for a long time, their practical use is hindered by high cost
and complexity. We argue that with the adoption of Rust these mechanisms will
become commoditized.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We thank the anonymous HotOS reviewers. This material is partially based upon
work supported by the National Science Foundation under Grants No. 1319076 and
No. 1527526.

