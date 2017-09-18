---
layout: page
title: How to organize your project
---


Every project editing manuscripts or other documents needs to organize the same kind of information.  This page summarizes some conventions that the HC MID has evolved over several years of work.  Following these conventions will ensure that you don't overlook anything crucial, and that you can easily reuse tools developed for other MID projects.


## Basic data sets

All HC MID projects need:

1.  a cataloged set of citable images to work.  In th
2.  documentation of the physical artifact.



##



All our collaborative work is organized in publicly available repositories hosted on [github](https://github.com/).


## Summary of file system organization

- `datasets`: catalogs of other sets of structured data (e.g., named entities such as personal names, or geographic names).
- `images`:  catalogs of images.  Each collection of images (e.g., one per manuscript) should be in a separate `.cex` file.
- `surfaces`: catalogs of text-bearing surfaces.   Each collection of surfaces ( e.g., pages of a single manuscript, columns of a single papyrus) should be in a separate `.cex` file.
- `editions`:  diplomatic editions.  Each text should be in a separate TEI-compliant XML file.
- `paleography` :  systematically sampled paleographic observations.
- `relations`:
- `scripts`:  short scripts that validate or analyze data from your editorial work
- `views`:  output of scripts that report on or visualize your data
