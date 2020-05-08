---
layout: publication
title: "Modular Verification of Shared-Memory Concurrent System Software"
key: 2011_thesis_rakamaric
type: thesis

shortname: Thesis-Rakamaric
image: 2011_thesis_rakamaric.png

authors:
- rakamaric
advisors: Alan J. Hu, Kenneth L. McMillan, Mark R. Greenstreet
year: 2011
month: March
institution: University of British Columbia
thesis_type: PhD Thesis

bibentry: phdthesis
bib:
  school: University of British Columbia
  month: March

pdf: 2011_thesis_rakamaric.pdf

abstract: "
<p>Software is large, complex, and error-prone. According to the US National
Institute of Standards and Technology, software bugs cost the US economy an
estimated $60 billion each year. The trend in hardware design of switching to
multi-core architectures makes software development even more complex. Cutting
software development costs and ensuring higher reliability of software is of
global interest and a grand challenge. This is especially true of the system
software that is the foundation beneath all general-purpose application
programs.</p>

<p>The verification of system software poses particular challenges: system
software is typically written in a low-level programming language with dynamic
memory allocation and pointer manipulation, and system software is also highly
concurrent, with shared-memory communication being the main concurrent
programming paradigm. Available verification tools usually perform poorly when
dealing with the aforementioned challenges. This thesis addresses these
problems by enabling precise and scalable verification of low-level,
shared-memory, concurrent programs. The main contributions are about the
interrelated concepts of memory, modularity, and concurrency.</p>

<p>First, because programs use huge amounts of memory, the memory is usually
modeled very imprecisely in order to scale to big programs. This imprecise
modeling renders most tools almost useless in the memory-intensive parts of
code. This thesis describes a scalable, yet precise, memory model that offers
on-demand precision only when necessary.</p>

<p>Second, modularity is the key to scalability, but it often comes with a
price — a user must manually provide module specifications, making the
verification process more tedious. This thesis proposes a light-weight
technique for automatically inferring an important family of specifications to
make the verification process more automatic.</p>

<p>Third, the number of program behaviors explodes in the presence of
concurrency, thereby greatly increasing the complexity of the verification
task. This explosion is especially true of shared-memory concurrency. The
thesis presents a static context-bounded analysis that combines a number of
techniques to successfully solve this problem.</p>

<p>We have implemented the above contributions in the verification tools
developed as a part of this thesis. We have applied the tools on real-life
system software, and we are already finding critical, previously undiscovered
bugs.</p>"

---
