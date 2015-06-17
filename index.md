---
title: Style guide
layout: default
---

# Reich Lab Style Guide for R

### File names
 
 - All scripts should end in .R 
 - Files should have descriptive names, with words separated by hyphens. E.g. `get-past-counts.R`
 
### Spacing

 - Indents should be 4 spaces. 
 - Include spaces around operators (=, +, -, <-). Exception: do not include spaces around function arguments e.g. `qplot(x=age, y=height, data=mydat)`. 

### Line length
Avoid having lines in code greater than 80 characters.

### Writing Functions

 - Always use [Roxygen](http://cran.r-project.org/web/packages/roxygen2/vignettes/roxygen2.html) syntax for documenting every function.
 - Always use `return()` at the end of functions.

### Comments

Commenting style should follow these conventions
 - `###`: used for a comment that you want flush left no matter what (i.e. section beginning)
 - `##`: used for a comment that you want to keep appropriate tab alignment
 - `#`: for a short comment after code, used sparingly, e.g.
 
`x <- rnorm(100)  # assigning random numbers`

### References
Based in part on Hadley's [Style page](https://raw.githubusercontent.com/hadley/adv-r/master/Style.rmd) and [Google's R Style Guide](http://google-styleguide.googlecode.com/svn/trunk/Rguide.xml).
