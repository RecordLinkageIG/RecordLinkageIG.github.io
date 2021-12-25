
[![pages-build-deployment](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/pages/pages-build-deployment) [![render](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/R-CMD-check.yaml)

**[recordlinkageig.github.io](https://recordlinkageig.github.io)**

This repository hosts the blog of the American Statistical Association's [Record Linkage Interest Group (RLIG)](https://sites.google.com/view/rlig). The blog is open to contributions from anyone with interest in deterministic and probabilistic record linkage, entity resolution, data fusion, and statistical matching. Contributions are subject to review. Contact [Olivier Binette](https://olivierbinette.github.io/) for support.

## Contribute

The blog is based on [Distill for Rmarkdown](https://rstudio.github.io/distill/), an [Rmarkdown](https://rmarkdown.rstudio.com/) extension for scientific and technical writing on the web.

In order to contribute a post to this blog, you will need basic familiarity with git, github, R and Rmarkdown. We recommend using [RStudio](https://www.rstudio.com/products/rstudio/) as an IDE for its visual rmarkdown editor and suite of compatible editing features. If you do not have RStudio, you will need to separately install [Pandoc](https://pandoc.org/) to render Rmarkdown documents.

### System configuration

Make sure you have [R](https://www.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/) installed (you can separately install [Pandoc](https://pandoc.org/) instead of RStudio). You will also need to install the following packages in R:
```r
install.packages(c("rmarkdown", "distill"))
```

### Creating a new post

Follow these steps to create a new post:

1. Fork this repository.
2. Create a new RStudio project from version control, using git and the forked repository url. Alternatively, clone the forked repository and `cd` into it.
3. Use the following R command to create a new post:
```r
distill::create_post("My Post Title")
```
4. This will create a new folder, named after the current date and provided post title, in the `_posts` directory. This folder contains an Rmarkdown document for you to edit.
5. Edit the Rmarkdown document, referring to [https://rstudio.github.io/distill/](https://rstudio.github.io/distill/) for help with formatting and metadata options. You may also use previous posts as templates.
6. Once you are done preparing your post, then commit, push, and create a pull request on [https://github.com/RecordLinkageIG/RecordLinkageIG.github.io](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io).

The pull request will be reviewed before your post is published on RLIG's blog.


### Submission requirements checklist

Make sure to review the following items before submitting your post:

- 



## Code of Conduct

Please note that the RecordLinkageIG.github.io project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.
