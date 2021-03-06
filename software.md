---
layout: default
title: Software - Thomas J. Leeper
permalink: /software.html
---

## R Packages ##

Here are a few of the R packages I've developed on my own, and as part of the [rOpenSci](http://ropensci.org/), [rOpenGov](http://ropengov.github.io/), and [cloudyr](http://cloudyr.github.io) open source projects. [My CV](http://www.thomasleeper.com/cv/cv.pdf) lists all of my software projects and you can find source code for all projects on [GitHub](http://github.com/leeper). The projects below are a few of the more prominent examples.

**cloudyr**
The [cloudyr project](http://cloudyr.github.io) is an effort to connect R to cloud computing applications, starting with Amazon Web Services and continuous integration services for R package development. See the cloudyr website or [GitHub page](https://github.com/cloudyr) for more details.


**Dataverse packages: dataverse (version >= 4.0) and dvn (version < 4.0)**<br/>
These R packages provide access to [The Dataverse Network](http://dataverse.org) APIs. *dataverse* is the current generation package, providing access to the complete functionality of current Dataverse installations (see [GitHub](htts://www.github.com/IQSS/dataverse-client-r)). It is part of the [rOpenSci](http://ropensci.org/) project and is officially supported by Harvard-IQSS, the developers of Dataverse. *dvn* is a legacy package supporting earlier Dataverse installations. <br/>[CRAN](http://cran.r-project.org/web/packages/dvn/index.html) [GitHub](https://github.com/rOpenSci/dvn)


**ghit: Lightweight GitHub Package Installer**
ghit is a lightweight, vectorized drop-in replacement for `devtools::install_github()` that uses native git and R methods to clone and install a package from GitHub. It provides a lighter weight alternative to devtools with a very similar API, slightly different defaults, and completely rebuilt internals.
<br/>[CRAN](https://cran.r-project.org/web/packages/ghit/index.html) [GitHub](https://github.com/leeper/ghit)


**imguR: Imgur API Client Package for R**<br/>
imguR is an R package, initated by Aaron Statham, that binds the imguR API to R, thus enabling the uploading and management of images on imguR. It might be particularly useful for web-based R projects and knitr documents written in R markdown. <br/> [GitHub](https://github.com/leeper/imguR)


**margins: An R port of Stata's margins command**<br/>
margins is a work-in-progress that is meant to be an R port of Stata's margins command. It can be used to calculate marginal effects and their variances from regression models. It is especially helpful for models with power terms, non-linear transformations, and interaction terms, and for generalized linear models. <br/> [GitHub](https://github.com/leeper/margins)


**MTurkR: R Client for the MTurk Requester API**<br/>
MTurkR is a client library providing access to the Amazon Mechanical Turk crowdsourcing platform through R.<br/> [CRAN](http://cran.r-project.org/web/packages/MTurkR/index.html) [GitHub](https://github.com/leeper/MTurkR) [Graphical User Interface](http://cran.r-project.org/web/packages/MTurkRGUI/index.html) [Wiki](https://github.com/leeper/MTurkR/wiki)


**rio: A Swiss-army knife for data I/O**<br/>
The aim of rio is to make data file I/O in R as easy as possible by implementing data import and export for R that relies on file extensions to make a (reasonable) assumption about how to read a file into a data.frame or, conversely, save a data.frame to disk. It greatly simplifies data import and export and offers a function for easily converting between file formats (possibly from the command line). <br/> [GitHub](https://github.com/leeper/rio)


**rite: The Right Editor to Write R**<br/>
A simple, powerful, multi-platform script editor for R, built with tcl/tk, rite provides features typically found in standalone editors and IDEs (e.g., syntax highlighting, command completion, shortcut keys, find and go-to-line commands, one-click access to documentation, etc.) and a helpful color-coded output "sink". It also creates an easy workflow for reproducible research through integration with the [knitr](http://cran.r-project.org/web/packages/knitr/index.html) package. <br/>[CRAN](http://cran.r-project.org/web/packages/rite/index.html) [GitHub](https://github.com/leeper/rite)


**slopegraph: Edward Tufte-inspired Slopegraphs in R**<br/>
A simple, one-function R package to produce Edward Tufte-inspired [slopegraph plots](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0003nk). <br/>[GitHub](https://github.com/leeper/slopegraph)


**sparktex: Generate LaTeX sparklines in R**<br/>
sparktex is an R companion to the LaTeX [sparklines](http://www.ctan.org/pkg/sparklines) package (by Andreas Loeffler and Dan Luecking), which produces Edward Tufte-inspired [sparklines](http://en.wikipedia.org/wiki/Sparkline) and sparkspikes (in-text histograms) natively in LaTeX. <br/>[CRAN](http://cran.r-project.org/web/packages/sparktex/index.html) [GitHub](https://github.com/leeper/sparktex)


**tabulizer: Bindings for Tabula PDF Table Extractor Library**<br/>
tabulizer provides R bindings to the [Tabula java library](https://github.com/tabulapdf/tabula-java/), which extracts tables from PDF documents using a small set of really powerful and accurate algorithms. tabulizer provides a thin client around Tabula, and provides a handy interactive mode to identifying tables in PDFs directly within an R graphics window. <br/>[GitHub](https://github.com/leeper/tabulizer)


**UNF: Tools for creating universal numeric fingerprints for data**<br/>
UNF is an R package for generating variable- and dataset-level universal numeric fingerprint signatures to uniquely identify data. UNF signatures provide a way to uniquely and persistently identify (a version of) a dataset. [The UNF algorithm](http://thedata.org/book/universal-numerical-fingerprint) was created by [Micah Altman](http://micahaltman.com/) and was updated to version 5 of the UNF algorithm in the current package, which I maintain. The UNF package also provides UNF-based functions to identify discrepancies between dataframes and works well with the **dvn** package, listed above, for comparing Dataverse-stored datasets against local copies.<br/>[GitHub](https://github.com/leeper/UNF)
