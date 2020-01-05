---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Leveraging Compiler Intermediate Representation for Multi- and Cross-Language Verification"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2020_vmcai_gbhr

# conference | journal | poster | workshop
type: conference
redirect_from:

# The shortname is used for auto-generated titles
shortname: VMCAI 2020
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2020_vmcai_gbhr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2020_vmcai_gbhr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- garzella
- baranowski 
- he
- rakamaric

journal-short: VMCAI
year: 2020

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 21st International Conference on Verification, Model Checking, and Abstract Interpretation (VMCAI)
  series:
  volume:
  publisher:
  editor:
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
pdf: 2020_vmcai_gbhr.pdf
# A supplement PDF
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements: https://github.com/soarlab/gandalv
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
Developers nowadays regularly use numerous programming languages with different
characteristics and trade-offs. Unfortunately, implementing a software verifier
for a new language from scratch is a large and tedious undertaking, requiring
expert knowledge in multiple domains, such as compilers, verification, and
constraint solving.  Hence, only a tiny fraction of the used languages has
readily available software verifiers to aid in the development of correct
programs.  In the past decade, there has been a trend of leveraging popular
compiler intermediate representations (IRs), such as LLVM IR, when implementing
software verifiers.  Processing IR promises out-of-the-box multi- and
cross-language verification since, at least in theory, a verifier ought to be
able to handle a program in any programming language (and their combination)
that can be compiled into the IR.  In practice though, to the best of our
knowledge, nobody has explored the feasibility and ease of such integration of
new languages.  In this paper, we provide a procedure for adding support for a
new language into an IR-based verification toolflow.  Using our procedure, we
extend the SMACK verifier with prototypical support for 6 additional languages.
We assess the quality of our extensions through several case studies, and we
describe our experience in detail to guide future efforts in this area.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported by funding from the Undergraduate Research Opportunities Program at
the University of Utah awarded to Jack J. Garzella, the National Science
Foundation awards CNS 1527526 and CCF 1837051, and a gift from the VMware's
University Research Fund.
