---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "SMACK: Decoupling Source Language Details from Verifier Implementations"
key: 2014_CAV_SMACK

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2014_CAV_SMACK

# The shortname is used for auto-generated titels
shortname: 2014_CAV_SMACK
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2014_CAV_SMACK.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2014_CAV_SMACK.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- rakamaric
- Michael Emmi

journal-short: CAV
year: 2014

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 26th International Conference on Computer Aided Verification (CAV)
  editor: Armin Biere and Roderick Bloem
  publisher: Springer
  address: 
  doi:
  url: 
  volume: 8559
  number: 
  pages: 106--113
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project: 
#https://github.com/soarlab/FPTaylor

# The reference to the video entry
video:
# 2018_tvcg_lineage_video
# The reference to the preview viedo entry
#preview-video:

# the prerint
pdf: 2014_CAV_SMACK.pdf
# A supplement PDF
supplement: 
#2018_tvcg_lineage_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "A major obstacle to putting software verification research into practice is the high cost of developing the infrastructure enabling the application of verification algorithms to actual production code, in all of its complexity. Handling an entire programming language is a huge endeavor that few researchers are willing to undertake; even fewer could invest the effort to implement a verification algorithm for many source languages. To decouple the implementations of verification algorithms from the details of source languages, and enable rapid prototyping on production code, we have developed SMACK. At its core, SMACK is a translator from the LLVM intermediate representation (IR) into the Boogie intermediate verification language (IVL). Sourcing LLVM exploits an increasing number of compiler front ends, optimizations, and analyses. Targeting Boogie exploits a canonical platform which simplifies the implementation of algorithms for verification, model checking, and abstract interpretation. Our initial experience in verifying C-language programs is encouraging: SMACK is competitive in SV-COMP benchmarks, is able to translate large programs (100 KLOC), and is being used in several verification research prototypes."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
