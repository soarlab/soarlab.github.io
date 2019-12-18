---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Verifying Rust Programs with SMACK"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2018_atva_bhr

# conference | journal | poster | workshop
type: conference
redirect_from: /2018/07/atva2018-bhr

# The shortname is used for auto-generated titles
shortname: ATVA 2018
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2018_atva_bhr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2018_atva_bhr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- baranowski
- he
- rakamaric

journal-short: ATVA
year: 2018

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 16th International Symposium on
    Automated Technology for Verification and Analysis (ATVA)
  series: Lecture Notes in Computer Science
  volume: 11138
  publisher: Springer
  editor: Shuvendu K. Lahiri and Chao Wang
  pages: 528--535
  doi: 10.1007/978-3-030-01090-4_32
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
pdf: 2018_atva_bhr.pdf
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
code: https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
Rust is an emerging systems programming language with guaranteed memory safety
and modern language features that has been extensively adopted to build
safety-critical software. However, there is currently a lack of automated
software verifiers for Rust. In this work, we present our experience extending
the SMACK verifier to enable its usage on Rust programs. We evaluate SMACK on a
set of Rust programs to demonstrate a wide spectrum of language features it
supports.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported in part by the National Science Foundation (NSF) award CNS 1527526.

