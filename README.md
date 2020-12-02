
<!-- README.md is generated from README.Rmd. Please edit that file -->

# morphemizer

<!-- badges: start -->

<!-- badges: end -->

The goal of morphemizer is to tokenize text into morphemes (the shortest
word pieces that still bear meaning). For example, “unaffable” should
tokenize to `"un##", "affable"`, since “aff” does not have a meaning in
modern English, while “inescapable” should tokenize to `"in##",
"escape", "##able"`. `"##"` characters are used to indicate breaks in
words. Prefixes are followed by “\#\#” (as in `"in##"`), suffixes are
preceded by “\#\#” (as in `"##able"`), and breaks between roots are
indicated by the special `"##"` token.

## Installation

You can install the released version of morphemizer from
[CRAN](https://CRAN.R-project.org) with:

``` r
# No you can't.
# install.packages("morphemizer")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jonthegeek/morphemizer")
```

## Disclaimer

This is not an officially supported Macmillan Learning product.

## Contact information

Questions or comments should be directed to Jonathan Bratt
(<jonathan.bratt@macmillan.com>) and Jon Harmon
(<jonthegeek@gmail.com>).
