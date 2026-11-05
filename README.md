# `modelfree`: Model-free estimation of psychometric and stimulus-response functions

**Website:** https://drdhfoster.github.io/model-free/

`modelfree` estimates a psychometric or stimulus-response function without assuming a parametric model such as the Gaussian, Weibull or logistic. It uses local linear fitting, which assumes only that the underlying function is smooth. It also estimates a derived threshold and slope, together with their bootstrap standard deviations and confidence intervals.

Two implementations are available:

- **MATLAB:** download [`software/MatLab/modelfree.zip`](software/MatLab/modelfree.zip), unzip it, and add all its folders to the MATLAB path. Requires the Statistics Toolbox.
- **R:** install from CRAN, at https://CRAN.R-project.org/package=modelfree, with:

  ```r
  install.packages("modelfree")
  ```

The website has an overview of the method, a worked demonstration, documentation for every function, and seven examples in both MATLAB and R. The example datasets can be downloaded in MATLAB, plain-text and Excel formats from [`software/testData/`](software/testData/).

## How to cite

If you use this software, please cite:

> Żychaluk, K. and Foster, D. H. (2009). Model-free estimation of the psychometric function. *Attention, Perception, & Psychophysics*, 71(6), 1414–1425. https://doi.org/10.3758/APP.71.6.1414

Further background:

> Foster, D. H. and Żychaluk, K. (2007). Nonparametric estimates of biological transducer functions. *IEEE Signal Processing Magazine*, 24(4), 49–58. https://doi.org/10.1109/MSP.2007.4286564

## Contents of this repository

| Path | Contents |
|---|---|
| `index.html` and other top-level `.html` pages | Website pages (Home, Downloads, Demonstration, Documentation, Examples, Functions, Contacts) |
| `examples/` | The seven worked examples, each in a MATLAB and an R version |
| `functions/` | One documentation page per function |
| `pictures/` | Figures used on the website |
| `software/MatLab/` | MATLAB package |
| `software/testData/` | Example datasets in three formats |
| `software/papers/` | The two articles above, for personal research use only |

## Authors

Iván Marín-Franch, Kamila Żychaluk and David H. Foster. The website was developed by Iván Marín-Franch.

## Funding

This work was supported by the EPSRC (grant no. EP/C003470/1) and the BBSRC (grant no. S08656).

## Licence

The MATLAB package (`software/MatLab/`) is licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE). It is free for noncommercial use, including academic research, teaching and personal study, but not for commercial use. For commercial use, please contact the authors.

The R package is distributed separately on CRAN under the GNU Lesser General Public License, version 3 or later (LGPL-3.0-or-later).

These licences cover the software only. The two articles in `software/papers/` remain under their publishers' copyright and are provided for personal research use only. The example datasets come from the studies cited on each example page.

## Contact

Kamila Żychaluk (kamila.zychaluk@liverpool.ac.uk) or David H. Foster (d.h.foster@manchester.ac.uk). Please let us know about any errors, missing links or suggestions for the site.
