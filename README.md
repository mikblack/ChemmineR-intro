## ChemmineR: introductory session

This material covers a VERY basic introduction to some of the functionality provided by the `ChemmineR` package for R.

It borrows heavily from: 

 - http://www.bioconductor.org/packages/devel/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html

### R libraries

The main R package used during this session is `ChemmineR`.  You can install this via:

```{r eval=FALSE}
## Source the biocLite.R installation script
source("http://bioconductor.org/biocLite.R") 

## Use biocLite to install the package
biocLite("ChemmineR") 
```

## References

Papers relating to this package and the assocaited "Chemmine" web service:

 - Cao, Y., Charisi, A., Cheng, L.-C., Jiang, T., & Girke, T. (2008). ChemmineR: a compound mining framework for R. Bioinformatics (Oxford, England), 24(15), 1733–1734. http://doi.org/10.1093/bioinformatics/btn307

 - Backman, T. W. H., Cao, Y., & Girke, T. (2011). ChemMine tools: an online service for analyzing and clustering small molecules. Nucleic Acids Research, 39(suppl), W486–W491. http://doi.org/10.1093/nar/gkr320

Bioconductor page:

 - https://www.bioconductor.org/packages/release/bioc/html/ChemmineR.html

The code and instructions for this session are contained in the ChemmineR-intro.Rmd and ChemmineR-intro.html files in this repository. Rendered HTML:

https://rawgit.com/mikblack/ChemmineR-intro/master/ChemmineR-intro.html
