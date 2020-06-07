# GitHub Pages website source code

[![Website remlapmot.github.io](https://img.shields.io/website-up-down-green-red/https/remlapmot.github.io.svg)](https://remlapmot.github.io/)

This repo contains the source files for [my GitHub Pages website](https://remlapmot.github.io) made with the [blogdown package](https://bookdown.org/yihui/blogdown/) in R.

To build the site

* Install the **blogdown** package
    ``` r
    install.packages("blogdown")
    ```
* Install Hugo
    ``` r
    blogdown::install_hugo()
    ```
* Install Academic theme
    ``` r
    blogdown::install_theme("gcushen/hugo-academic")
    ```
* Build the site
    ``` r
    blogdown::build_site()
    ```
* This will create a directory called public which is my [remlapmot.github.io](https://github.com/remlapmot/remlapmot.github.io) repo on GitHub.