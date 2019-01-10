---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Static and Precise Detection of Concurrency Errors in Systems Code Using SMT Solvers"
key: 2009_CAV_STORM

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2009_CAV_STORM

# The shortname is used for auto-generated titels
shortname: 2009_CAV_STORM
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2009_CAV_STORM.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2009_CAV_STORM.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Shuvendu Lahiri
- Shaz Qadeer
- rakamaric

journal-short: CAV
year: 2009

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 21st International Conference on Computer Aided Verification (CAV 2009)
  editor: Ahmed Bouajjani and Oded Maler
  publisher: Springer
  address: 
  doi: 
  url: 
  volume: 5643
  number: 
  pages: 509--524
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
pdf: 2009_CAV_STORM.pdf
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
code: 
#https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "Context-bounded analysis is an attractive approach to verification of concurrent programs. Bounding the number of contexts executed per thread not only reduces the asymptotic complexity, but also the complexity increases gradually from checking a purely sequential program.
Lal and Reps provided a method for reducing the context-bounded verification of a concurrent boolean program to the verification of a sequential boolean program, thereby allowing sequential reasoning to be employed for verifying concurrent programs. In this work, we adapt the encoding to work for systems programs written in C with the heap and accompanying low-level operations such as pointer arithmetic and casts. Our approach is completely automatic: we use a verification condition generator and SMT solvers, instead of a boolean model checker, in order to avoid manual extraction of boolean programs and false alarms introduced by the abstraction.We demonstrate the use of field slicing for improving the scalability and (in some cases) coverage of our checking.We evaluate our tool STORM on a set of real-world Windows device drivers, and has discovered a bug that could not be detected by extensive application of previous tools."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
