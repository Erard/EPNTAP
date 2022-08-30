[![EPNTAP version](https://img.shields.io/badge/EPNTAP-REC--2.0-yellow.svg)](https://ivoa.net/documents/EPNTAP/)
[![PDF-Preview](https://img.shields.io/badge/Preview-PDF-blue)](../../releases/download/auto-pdf-preview/epntap-draft.pdf)

# EPNTAP: Publishing Solar System Data to the Virtual Observatory


## What is it?

EPN-TAP: Europlanet (**EPN**) **T**able **A**ccess **P**rotocol

This document defines the EPN-TAP framework, which is using 
[TAP](http://www.ivoa.net/documents/TAP/) with the **EPNcore** 
metadata dictionary. The EPNcore metadata dictionary defines 
the core components that are necessary to perform data discovery 
in the Solar System related science fields. 

It includes keywords to describe data products coverage 
(temporal, spectral, spatial, photometric), origin (instrument, facility), 
content (target, physical parameters), access, references, etc. 
Its implementation with TAP is presented here, including service 
registration guidelines. Topical extension metadata dictionaries 
are also presented.

## Status?

This is the first release of EPN-TAP as an IVOA recommandation. 

The current IVOA Recommendation is [REC-2.0](https://ivoa.net/documents/EPNTAP/). Prior versions are available on the [IVOA Documents page](https://www.ivoa.net/documents/index.html).

See also the section
[Releases](https://github.com/ivoa-std/EPNTAP/releases) of this GitHub Repository.

## What about this repository?

This GitHub repository contains the sources of the IVOA document describing
EPNTAP.

Only the LaTeX version is available here. No output version (e.g. PDF, HTML,
DOC) should be stored in this repository.

A PDF preview is automatically generated by a GitHub workflow. It is accessible
either by clicking of the above "Preview" badge or by looking at the
pre-release
["Auto updated PDF"](../../releases/tag/auto-pdf-preview).

## Want to contribute?

1. [Raise a GitHub Issue](https://github.com/ivoa-std/EPNTAP/issues/new) on this
   repository

2. Fork this repository _(eventually clone it on your machine if you want to)_

3. Create a branch in your forked repository ; this branch should be named 
   after the issue(s) to fix (for instance: `issue-7-add-license`)

4. Commit suggested changes inside this branch

5. Create a Pull Request on the official repository _(note: a `git push` is 
   needed first, if you are working on a clone)_

6. Wait for someone to review your Pull Request and accept it

_This process has been described and demonstrated during the IVOA 
Interoperability Meeting of Oct. 2019 in Groningen ; see 
[slides](https://wiki.ivoa.net/internal/IVOA/InterOpOct2019GitHub/IVOA_Github.pdf))_

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
  
