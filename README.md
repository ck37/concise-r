# A Concise Introduction to R

The goal of this material is to provide a concise introduction to R & RStudio with sufficient training on fundamentals that students can understand R syntax, resolve common R errors, and complete basic data analysis. No prior knowledge of R is assumed, nor other programming experience. Each session is intended to take about 3 hours. After completion students should be familiar with R and able to teach themselves more advanced techniques using online resources.

Prepared for Public Policy 290 "Analytics for Government Policy" by Avi Feller, Spring 2016.

## Day 1

[R Markdown file](https://github.com/ck37/r-intro-2016/blob/master/r-day1.Rmd). Topics covered:

* Overview of RStudio and RMarkdown
* Math functions
* Assignment operator `<-` and `=`
* Environmental variables: `ls()` and `rm()`
* Sequences: colon operator `:` and `seq()`
* Vectors, vector functions `length()`, `sum()`, `mean()`, `max()`, `min()`, `summary()`
* Random numbers: `set.seed()` and `runif()`
* Getting help: `?`, `help()`, `help(package=)`
* Calling functions
* Creating vectors: `c()`, `rep()`
* Subsetting vectors with bracket notation `[]`
* Data frames: `data.frame()`, `nrow()`, `ncol()`, `dim()`, `names()`, `str()`
* Subsetting data frames: bracket notation `[]`, `$`, `subset()`
* Factors: `levels()`, `as.character()`
* Object types: `class()`, `str()`
* Data analysis: `table()`, `prop.table()`
* Visualization: `qplot()` from `ggplot2`.
* Importing data: `getwd()`, haven `read_dta()`, and readr `read_csv()`, `read_tsv()`

## Day 2

[R Markdown file](https://github.com/ck37/r-intro-2016/blob/master/r-day2.Rmd). Topics covered:

* Missing values: `is.na()`, `na.rm` option
* More data frames: `cbind()`, `rbind()`, `colMeans()`, `rowMeans()`
* More `ggplot2`: custom labeling, themes, colors, sizes; `ggplot()`, `geom_point()`, `geom_density()`, `geom_path()`, `geom_line()`, `ggtitle()`, `geom_text()`, `geom_label()`, `labs()`, `ggsave()`
* Flow control: `for` loops, `if else` blocks
* More vectors: `ifelse()`, `%in%`
* Cleaner text output with `cat()`
* Creating functions: basic functions, function arguments, returning results, argument defaults

Future content: day 3 would focus on data analysis using regression, apply and replicate, and merging files.

## Resources

* Books
    * [R for Data Science](http://r4ds.had.co.nz/)
    * [Advanced R](http://adv-r.had.co.nz/)
    * [Efficient R](https://csgillespie.github.io/efficientR/)
* Trainings
    * [R Bootcamp](https://github.com/berkeley-scf/r-bootcamp-2017) by Chris Paciorek
    * D-Lab's [R Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals)
* Courses
    * Stat 133
    * Stat 243 by Chris Paciorek

