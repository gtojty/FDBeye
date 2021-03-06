---
output: html_document
---

FDBeye [![DOI](https://zenodo.org/badge/38009047.svg)](https://zenodo.org/badge/latestdoi/38009047)
====

This is a collection of tools to ease working with eyetracker
data. I'm slowly migrating stuff from my junkpile of project specific
code into this package. FDBeye is about post-acquisition data
processing. What's here now is focussed on my own workflows involving
data from SRR Eyelink systems, although some stuff may be more
generally useful. Functionality is a bit thin at present. Pitch in and
help if you like (see [Contributing](#contributing)).

Before you try FDBeye, you might want to look at what else is
available. See the list of
[other eye tracking tools](https://github.com/davebraze/FDBeye/wiki)
on the project wiki.

Installing FDBeye
-----------------
First you should install <https://github.com/davebraze/FDButils>.

Then, to get the very latest from *FDBeye*, install it via
devtools::install\_github(). Some people have reported problems with
the installation due to the vignettes failing to build. If that
happens to you, you can try again with `build\_vignettes=FALSE`,
although the vignettes won't be available.

```R
install.packages("devtools")    ## if you don't already have it
library(devtools)
install_github("davebraze/FDBeye", build_vignettes=TRUE)
```

On the other hand, if you want a (possibly) more stable
experience. Download the most current release from here:
<https://github.com/davebraze/FDBeye/releases>. Then install it like
this:

```R
install.packages(pathToFile, repos = NULL)
```

Where pathToFile is the full path and file name for the file you
downloaded.

License
-------

FDBeye is released under the MIT open source license. See the
[LICENSE](https://github.com/davebraze/FDBeye/blob/master/LICENSE)
file for details.

Contributing
------------

Contributions are welcome, but you might want to review the "issues"
page and send me an email before wading in too deep
(<davebraze@gmail.com>). You might also have look at the file
"CONTRIBUTING.md" for pointers on the mechanical details of
contributing to a package on github.

_IMPORTANT_: In opening a pull request to FDBeye, you (a) affirm that
you are the copyright owner for the material contained in the pull
request, and (b) agree to apply the
[MIT license](https://opensource.org/licenses/MIT) to the material
contained in the pull request. Contributors retain copyright to their
own code.

Other Eye Tracking Tools
------------------------

The list of (mostly FOSS) tools has been moved to the
[FDBeye Wiki](https://github.com/davebraze/FDBeye/wiki).
