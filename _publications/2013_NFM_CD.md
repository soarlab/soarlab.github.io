---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Formal Analysis of GPU Programs with Atomics via Conflict-Directed Delay-Bounding"
key: 2013_NFM_CD

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: paper
redirect_from: /publications/2013_NFM_CD

# The shortname is used for auto-generated titels
shortname: 2013_NFM_CD
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2013_NFM_CD.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2013_NFM_CD.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- Wei-Fan Chiang
- Ganesh Gopalakrishnan
- Guodong Li
- rakamaric

journal-short: NFM
year: 2013

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the 5th NASA Formal Methods Symposium (NFM 2013)
  editor: Guillaume Brat and Neha Rungta and Arnaud Venet
  publisher: Springer
  address: 
  doi:
  url: 
  volume: 7871
  number: 
  pages: 213--228
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
pdf: 2013_NFM_CD.pdf
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

abstract: "GPU based computing has made significant strides in recent years. Unfortunately, GPU program optimizations can introduce subtle concurrency errors, and so incisive formal bug-hunting methods are essential. This paper presents a new formal bug-hunting method for GPU programs that combine barriers and atomics. We present an algorithm called Conflict-directed Delay-bounded scheduling algorithm (CD) that exploits the occurrence of conflicts among atomic synchronization commands to trigger the generation of alternate schedules; these alternate schedules are executed in a delay-bounded manner. We formally describe CD, and present two correctness checking methods, one based on final state comparison, and the other on user assertions. We evaluate our implementation on realistic GPU benchmarks, with encouraging results."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
