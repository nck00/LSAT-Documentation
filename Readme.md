LSAT-docs
=========

[![DOI](https://zenodo.org/badge/386275172.svg)](https://zenodo.org/badge/latestdoi/386275172)

This repository contains the source files necessary to build the LSAT Documentation.
LSAT is available in its own [repository](https://github.com/BGR-EGHA/LSAT).

## How to build and view the LSAT Documentation as html on Windows

You will need Python (3.10 tested), Sphinx (https://pypi.org/project/Sphinx/) and its dependencies.
Run ".\make.bat clean; .\make.bat html" in the LSAT-docs folder.
The \build\html contains the finished documentation.

## How to add LSAT Documentation to existing LSAT installation

1. Build the documentation, as described above.
2. Copy the html folder into LSAT/docs
