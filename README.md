# Apache Arrow Experiments

This repository looks at using the [`arrow` R
package](https://arrow.apache.org/docs/r/) to work with data that's larger than
RAM. Daily builds of the arrow package can be installed on macOS and Windows
with:

```r
install.packages("arrow", repos=c("https://dl.bintray.com/ursalabs/arrow-r", "https://cran.rstudio.com"), dependencies = TRUE)
```

This repo uses [`renv`](https://rstudio.github.io/renv/index.html). All
necessary libraries can be installed using `renv::restore()`.
