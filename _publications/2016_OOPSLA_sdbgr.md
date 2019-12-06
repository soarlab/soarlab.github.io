---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Portable Inter-workgroup Barrier Synchronisation for GPUs"
key: 2016_OOPSLA_sdbgr

#YYYY_CONFSHORTNAME_PAPERSHORTNAME
# paper | preprint | poster
type: conference
redirect_from: /publications/2016_OOPSLA_sdbgr

# The shortname is used for auto-generated titels
shortname: 2016_OOPSLA_sdbgr
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_OOPSLA_sdbgr.png
# 2018_tvcg_lineage.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_OOPSLA_sdbgr.png
#2018_tvcg_lineage_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Tyler Sorensen
- Alastair F. Donaldson
- Mark Batty
- Ganesh Gopalakrishnan
- rakamaric

journal-short: OOPSLA
year: 2016

#bibentry: article | inproceedings | phdthesis | book

bibentry: inproceedings
bib:
  journal:
  booktitle: Proceedings of the ACM SIGPLAN International Conference on
    Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA)
  editor:
  publisher: ACM
  address: 
  doi:
  url: 
  volume:
  number: 
  pages: 39--58
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
pdf: 2017_POPL_FPTuner.pdf
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

# Link to an official preprint server
preprint_server: 
#https://doi.org/10.1101/128579

abstract: "
Despite the growing popularity of GPGPU programming, there is not yet a portable and formally-specified barrier that one can use to synchronise across workgroups. Moreover, the occupancy-bound execution model of GPUs breaks assumptions inherent in traditional software execution barriers, exposing them to deadlock. We present an occupancy discovery protocol that dynamically discovers a safe estimate of the occupancy for a given GPU and kernel, allowing for a starvation-free (and hence, deadlock-free) inter-workgroup barrier by restricting the number of workgroups according to this estimate. We implement this idea by adapting an existing, previously non-portable, GPU inter-workgroup barrier to use OpenCL 2.0 atomic operations, and prove that the barrier meets its natural specification in terms of synchronisation.
We assess the portability of our approach over eight GPUs spanning four vendors, comparing the performance of our method against alternative methods. Our key findings include: (1) the recall of our discovery protocol is nearly 100%; (2) runtime comparisons vary substantially across GPUs and applications; and (3) our method provides portable and safe inter-workgroup synchronisation across the applications we study.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
