---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Formal Analysis of GPU Programs with Atomics via Conflict-Directed Delay-Bounding"
#YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2013_nfm_cglr

# conference | journal | poster | workshop
type: conference
redirect_from: /2013/03/formal-analysis-of-gpu-programs-with-atomics-via-conflict-directed-delay-bounding

# The shortname is used for auto-generated titles
shortname: NFM 2013
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2013_nfm_cglr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2013_nfm_cglr_teaser.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:

- chiang
- Ganesh Gopalakrishnan
- Guodong Li
- rakamaric

journal-short: NFM
year: 2013

#bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 5th NASA Formal Methods Symposium (NFM)
  series: Lecture Notes in Computer Science
  volume: 7871
  publisher: Springer
  editor: Guillaume Brat and Neha Rungta and Arnaud Venet
  pages: 213--228
  doi: 10.1007/978-3-642-38088-4_15
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
pdf: 2013_nfm_cglr.pdf
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
#https://github.com/smackers/smack

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "<p>
GPU based computing has made significant strides in recent years. Unfortunately,
GPU program optimizations can introduce subtle concurrency errors, and so
incisive formal bug-hunting methods are essential. This paper presents a new
formal bug-hunting method for GPU programs that combine barriers and atomics. We
present an algorithm called Conflict-directed Delay-bounded scheduling algorithm
(CD) that exploits the occurrence of conflicts among atomic synchronization
commands to trigger the generation of alternate schedules; these alternate
schedules are executed in a delay-bounded manner. We formally describe CD, and
present two correctness checking methods, one based on final state comparison,
and the other on user assertions. We evaluate our implementation on realistic
GPU benchmarks, with encouraging results.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

Supported by NSF CCF 1255776, OCI 1148127, and the Microsoft SEIF Award.
