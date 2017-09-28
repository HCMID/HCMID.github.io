---
layout: page
title: How to organize your project
---


All our collaborative work is organized in publicly available repositories hosted on [github](https://github.com/).

Every project editing manuscripts or other documents needs to organize the same kind of information.  This page summarizes some conventions that the HC MID has evolved over several years of work.  Following these conventions will ensure that you don't overlook anything crucial, and that you can easily reuse tools developed for other MID projects.




## Required data sets

All HC MID projects *must* include:

1.  a **cataloged set of citable images** to work from.   Images are cataloged in structured text files in CEX format.  Put these catalogs in a directory named `images`.  Use one file for each collection of images illustrating a different manuscript.  Name the file with some indication of the manuscript + the string `imgs`.  Example:  `eins121imgs.cex`.
2.  **cataloged sequences of physical surfaces** (such as pages in a manuscript).  For each manuscript, the sequence of pages is cataloged in a structured text file in CEX format.  Put these catalogs in a directory named `surfaces`, and name the file with some indication of the manuscript + the string `pages`.  Example:  `eins121pages.cex`
3.  **diplomatic editions of texts**.  Each text should be in a separate TEI-compliant XML file.
4.  **indexes  relating images, surfaces and texts**.  Put these in the `relations` directory.
4.  **scripts to validate and verify your work**.  Put these in the `scripts` directory.  Output from these scripts is written to the `views` directory.

## Other data sets

HC MID projects *should* include:

-   systematically sampled paleographic observations.  Observations are cataloged in structured text files in CEX format.  Put these catalogs in a directory named `paleography`.  Use one file for each manuscript.  Name the file with some indication of the manuscript + the string `paleo`.  Example:  `eins121paleo.cex`.


HC MID projects *may* include:

-  other sets of structured data  (e.g., named entities such as personal names, or geographic names).  These data sets are documented in structured  text files in CEX format.  Name them something appropiate, and put them in the `datasets` directory.


## Summary of HC MID file system layout

Summary of [files in a HC MID repository](../file-layout)
