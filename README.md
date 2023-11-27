CodeMeta2CFF
=====================================================

A GitHub action to convert a codemeta.json file to CITATION.cff. This allows
users to avoid updating multiple files.

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg?style=flat-square)](https://choosealicense.com/licenses/bsd-3-clause)
[![Latest release](https://img.shields.io/github/v/release/caltechlibrary/codemeta2cff.svg?style=flat-square&color=b44e88)](https://github.com/caltechlibrary/codemeta2cff/releases)
[![DOI](https://data.caltech.edu/badge/DOI/10.22002/17jew-b7x11.svg)](https://doi.org/10.22002/17jew-b7x11)


Table of contents
-----------------

* [Introduction](#introduction)
* [Known issues and limitations](#known-issues-and-limitations)
* [Getting help](#getting-help)
* [License](#license)
* [Authors and history](#authors-and-history)
* [Acknowledgments](#authors-and-acknowledgments)


Introduction
------------

If you have a [CodeMeta](https://codemeta.github.io) file in your repository,
you can use this action to automatically convert it into a [Citation File Format
(cff)](https://citation-file-format.github.io) file. Add the
following to your workflow

```
      - name: Convert to CFF
        uses: caltechlibrary/codemeta2cff@main
```

A full workflow for converting on a release is available at https://github.com/caltechlibrary/codemeta2cff/blob/main/.github/workflows/codemeta2cff.yml


Known issues and limitations
----------------------------

Only a limited subset of CodeMeta and CFF fields have been mapped. You can
contribute by improving the codemeta2cff application at https://github.com/caltechlibrary/datatools

Getting help
------------

If you encounter any problems, please raise them in the issue tracker.


License
-------

Software produced by the Caltech Library is Copyright © 2021 California Institute of Technology.  This software is freely distributed under a BSD/MIT type license.  Please see the [LICENSE](LICENSE) file for more information.


Authors and history
---------------------------

This action was developed by Tom Morrell, using the codemeta2cff Go application
written by Robert Doiel

Acknowledgments
---------------

This work was funded by the California Institute of Technology Library.

<div align="center">
  <br>
  <a href="https://www.caltech.edu">
    <img width="100" height="100" src="https://raw.githubusercontent.com/caltechlibrary/template/main/.graphics/caltech-round.png">
  </a>
</div>
