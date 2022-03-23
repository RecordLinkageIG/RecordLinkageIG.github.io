


[![pages-build-deployment](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/pages/pages-build-deployment) [![render](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io/actions/workflows/R-CMD-check.yaml)

**[recordlinkageig.github.io](https://recordlinkageig.github.io)**

## About

This repository hosts the blog of the American Statistical Association's [Record Linkage Interest Group (RLIG)](https://sites.google.com/view/rlig). 

The blog is open to contributions from anyone with interest in deterministic and probabilistic record linkage, entity resolution, data fusion, and statistical matching. See below for contribution instructions.

<div class="layout-chunk" data-layout="l-body">


</div>


<div class="layout-chunk" data-layout="l-body">


</div>



## Contribute

The blog is based on [Distill for Rmarkdown](https://rstudio.github.io/distill/), an [Rmarkdown](https://rmarkdown.rstudio.com/) extension for scientific and technical writing on the web.

There are two ways to contribute to this blog:

1. Contact [Olivier Binette](https://olivierbinette.github.io/) to get a blog post published from any source. This blog post can be written in text format, markdown format, rmarkdown format, or another format without complicated formatting.
2. If you have familiarity with Rmarkdown and Github, you can follow the steps below to directly contribute to the blog. 

### System configuration

We recommend using [RStudio](https://www.rstudio.com/products/rstudio/) as an IDE for its visual rmarkdown editor and suite of compatible editing features. If you do not have RStudio, you will need to separately install [Pandoc](https://pandoc.org/) to render Rmarkdown documents. You will need R and to install the following R packages:

```r
install.packages(c("rmarkdown", "distill"))
```

### Creating a new post

Follow these steps to create a new post:

1. Fork this repository.
2. Create a new RStudio project from version control, using the forked repository url. Alternatively, clone the forked repository and `cd` into it.
3. Use the following R command to create a new post:

```r
distill::create_post("My Post Title")
```

4. This will create a new folder, named after the current date and provided post title, in the `_posts` directory. This folder contains an Rmarkdown document for you to edit.
5. Edit the Rmarkdown document, referring to [https://rstudio.github.io/distill/](https://rstudio.github.io/distill/) for help with formatting and metadata options. You may also use previous posts as templates.
6. Run the following R command to render your blog post as an html file:

```r
rmarkdown::render_site()
```

7. Commit, push, and create a pull request on [https://github.com/RecordLinkageIG/RecordLinkageIG.github.io](https://github.com/RecordLinkageIG/RecordLinkageIG.github.io).

The pull request will be reviewed before your post is published on RLIG's blog.


### Submission requirements checklist

Make sure to review the following items before submitting your post.

- As part of your article's metadata, you should use the template below to provide:
  - Post title and description
  - Current date
  - Image preview
  - Author information (full name, url/email address, and affiliation)
  
```md
title: "My Post Title"
description: |
  Description of my post.
preview: http://website.com/post-image
author:
  - name: Full Name
    url: url.com
    affiliation: State University
date: 2022-01-01
```

- At the end of your article, as part of the appendix, you should provide as section titled "About the Author(s)" which contains a short bibliography or some information regarding your background and interests. The goal is introduce you to RLIG's members and to help foster a sense of community. You can use the template below:

```md
## About the Author(s) {.appendix}

The author works at State University. They are [...].
```

## Code of Conduct

Please note that the RecordLinkageIG.github.io project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.


*This readme uses code from [https://github.com/shannonpileggi/pipinghotdata_distill](https://github.com/shannonpileggi/pipinghotdata_distill).*


*Updated 2022-03-22 21:19:16*
```{.r .distill-force-highlighting-css}
```
