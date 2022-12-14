
democodetools
==========

This is 'yet another doc/docx/doc3' package for LaTeX code documetation.
It is designed to be 'as class independent as possible',
no assumption about underline macros is made.
Furthermore, it's assumed that *\maketitle* and the *abstract* environment
were modified by the underline class, so alternatives (based on the article class) are provided.

For more details,  see the documentation,
[democodetools.pdf](http://mirrors.ctan.org/macros/latex/contrib/democodetools/doc/democodetools.pdf)

--------------

## Requirements
* none besides a fairly recent LaTeX distribution as recent as 2022/06/01
(with the new in kernel *\ProcessKeyOptions* and *\NewDocumentCommand*)

## Installation
The stable version is available at [CTAN](https://ctan.org/pkg/democodetools).

## Usage
### Stable version
Just place
```latex
  \usepackage{democodetools}
```

in the preamble and compile away.


Be aware that options might change between versions, so you have to check them manually.

## More Information and documentation
More Information can be found in the documentation; you can find a  "bleeding edge" version
at [the github page](http://github.com/alceu-frigeri/democodetools)

## Contacting Author

For bug reports and enhacement suggestions, the preferred way is to use
[the project's issue page](https://github.com/alceu-frigeri/democodetools/issues).
Please be ready to provide an example code showing the bug, if any.

Please do not use the issue page for generic help on how to use the package.

* git: https://github.com/alceu-frigeri/democodetools

-------------
Copyright 2022 by Alceu Frigeri

 This work may be distributed and/or modified under the
 conditions of

 * The [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), version 1.3c (or later), and/or
 * The [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html), version 3 (or later)

This work has the LPPL maintenance status *maintained*.

The Current Maintainer of this work is Alceu Frigeri

-------------
## This work consists of the files

* democodelisting.sty
    - set of macros to typeset and demonstrate LaTeX code

* democodetools.sty
    - set of macros to document LaTeX packages

* README.md (this file)
    - quick introduction

* democode.tex
    - package documentation

* democode.pdf
    - documentation in PDF format

-------------

## Changelog

* Version 1.0.1beta (this)
    - readme file cleanup (switch to markdown)
    - text files CRLF / LF 'corrected' (hopefully)
	- copyright cleanup

* Version 1.0beta
    - Initial release  by CTAN.
