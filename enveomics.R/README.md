# enveomics.R

## Installing `enveomics.R`
To install the latest version of `enveomics.R` uploaded to CRAN, execute in R:

```R
install.packages('enveomics.R')
```

To install the current developer version of `enveomics.R`, execute in R:

```R
install.packages('devtools')
library('devtools')
install_github('lmrodriguezr/enveomics', subdir='enveomics.R')
```

## Using `enveomics.R`
To load enveomics.R, simply execute:

```R
library(enveomics.R);
```

And open help messages using any of the following commands:

```R
?enveomics.R
?enve.barplot
?enve.recplot2
?enve.recplot2.compareIdentities
?enve.recplot2.changeCutoff
?enve.recplot2.findPeaks
?enve.recplot2.corePeak
?enve.recplot2.extractWindows
?enve.recplot2.coordinates
?enve.recplot2.seqdepth
?enve.recplot2.ANIr
?enve.prune.dist
?enve.tribs
?enve.tribs.test
?enve.growthcurve
?enve.col.alpha
?enve.truncate
```

You can run some examples using these libraries in the
[enveomics-GUI](https://github.com/lmrodriguezr/enveomics-gui).

For additional information on recruitment plots, see the
[Recruitment plots working document](https://github.com/lmrodriguezr/enveomics/blob/master/Docs/recplot2.md).

## Changelog
* 1.3.2: New option `panel.fun` for `plot.enve.RecPlot2`.
* 1.3.1: New function enve.truncate.
* 1.3: Several bug fixes and new utilities for recruitment plots (recplot2).
* 1.1.0: New function enve.growthcurve and related class enve.GrowthCurve
  with S3 methods plot and summary.
* 1.0.2: Fine-tuned default parameters in enve.recplot2.findPeaks and
  solved a minor bug in enve.recplot2 that caused failures in low-coverage
  datasets when using too many threads.
* 1.0.1: enve.recplot2 now supports pos.breaks=0 to define a
  bin per subject sequence.

