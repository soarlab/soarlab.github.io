---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Static and Precise Detection of Concurrency Errors in Systems Code Using SMT Solvers"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2009_cav_lqr

# conference | journal | poster | workshop
type: conference

# The shortname is used for auto-generated titles
shortname: CAV 2009
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2009_cav_lqr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2009_cav_lqr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Shuvendu Lahiri
- Shaz Qadeer
- rakamaric

journal-short: CAV
year: 2009

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 21st International Conference on Computer Aided
    Verification (CAV)
  series: Lecture Notes in Computer Science
  volume: 5643
  publisher: Springer
  editor: Ahmed Bouajjani and Oded Maler
  pages: 509--524
  doi: 10.1007/978-3-642-02658-4_38
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
pdf: 2009_cav_lqr.pdf
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
Context-bounded analysis is an attractive approach to verification of
concurrent programs. Bounding the number of contexts executed per thread not
only reduces the asymptotic complexity, but also the complexity increases
gradually from checking a purely sequential program. Lal and Reps provided a
method for reducing the context-bounded verification of a concurrent boolean
program to the verification of a sequential boolean program, thereby allowing
sequential reasoning to be employed for verifying concurrent programs. In this
work, we adapt the encoding to work for systems programs written in C with the
heap and accompanying low-level operations such as pointer arithmetic and
casts. Our approach is completely automatic: we use a verification condition
generator and SMT solvers, instead of a boolean model checker, in order to
avoid manual extraction of boolean programs and false alarms introduced by the
abstraction. We demonstrate the use of field slicing for improving the
scalability and (in some cases) coverage of our checking. We evaluate our tool
STORM on a set of real-world Windows device drivers, and has discovered a bug
that could not be detected by extensive application of previous tools.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

This work was supported by a Microsoft Research Graduate Fellowship.

