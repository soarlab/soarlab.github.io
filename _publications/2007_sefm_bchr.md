---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Proving Termination by Divergence"
# YYYY_CONFSHORTNAME_PAPERSHORTNAME
key: 2007_sefm_bchr

# conference | journal | poster | workshop
type: conference
redirect_from: /2007/09/proving-termination-by-divergence

# The shortname is used for auto-generated titles
shortname: SEFM 2007
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2007_sefm_bchr.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2007_sefm_bchr_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Domagoj Babic
- Byron Cook
- Alan J. Hu
- rakamaric

journal-short: SEFM
year: 2007

# bibentry: article | inproceedings | phdthesis | book
bibentry: inproceedings
bib:
  booktitle: Proceedings of the 5th IEEE International Conference on Software
    Engineering and Formal Methods (SEFM)
  series:
  volume:
  publisher: IEEE Computer Society
  editor:
  pages: 93--102
  doi: 10.1109/SEFM.2007.32
  address:
  url:
  number:
  month:
  note:

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: Invited for special section submission to Formal Aspects of Computing (FAC)

# Use if this paper is linked to an internal project. This will link to the project site
# project: upset

# Use this if you have an external project website
external-project:

# The reference to the video entry
video:
# The reference to the preview video entry
#preview-video:

# the preprint
pdf: 2007_sefm_bchr.pdf
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
We describe a simple and efficient algorithm for proving the termination of a
class of loops with nonlinear assignments to variables. The method is based on
divergence testing for each variable in the cone-of-influence of the loop's
termination condition. The analysis allows us to automatically prove the
termination of loops that cannot be handled using previous techniques. The
paper closes with experimental results using short examples drawn from
industrial code.
</p>"

# After the --- you can put information that you want to appear on the website
# using markdown formatting or HTML. A good example are acknowledgements, extra
# references, an erratum, etc.
---
### Acknowledgements

We would like to thank Richard Fateman, Robert Israel, and Daniel Lichtblau for
useful discussions about the complexity of polynomial factorization, divergence
of the update functions, and multivariate limits. We would also like to thank
the anonymous reviewers for several helpful comments and for pointing out the
special case in the computation of safe RGDs.  This work was supported by an
NSERC Discovery Grant, a Microsoft Graduate Fellowship, and a graduate
fellowship from the University of British Columbia.

