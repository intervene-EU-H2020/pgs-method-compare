# prs-method-compare

A website that describes the performance of PRS development methods across five European biobanks.

🚨 This repository is in under active development with no stable releases available yet 🚨

## Build notes

To build the website from source you'll need:

* [Quarto](https://quarto.org) (tested with `v1.3.433`)
* [R](https://www.r-project.org) (tested with `v4.3.1`)

And an R package:

* [`renv`](https://rstudio.github.io/renv/articles/renv.html) (tested with `v1.0`)

Then run:

```
$ git clone https://github.com/intervene-EU-H2020/prs-method-compare.git
$ cd prs-method-compare/
$ R
> renv::restore() # installs dependencies
$ quarto preview # builds and opens website in your browser
```
