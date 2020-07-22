RStudio: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=rstudio)

RShiny: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=shiny/bus-dashboard/)

# R, RStudio, and RShiny

Example with R, RStudio, and RShiny using the [MRAN packages]([MRAN](https://mran.microsoft.com/documents/rro/reproducibility).
).

## Specify R Environment

To specify an **R environment** use the runtime.txt file with the following format:

```
r-<YYYY>-<MM>-<DD>
```

## Install R Libraries

To install R libraries (or packages) you can add an [`install.R`](install.R) file that specifies one library to install per line.

## Related

This repo provides an example of [installing and managing R packages with conda](https://github.com/illumidesk/r-conda).