# prs-method-compare

A website that describes the performance of PRS development methods across five European biobanks.

The website is currently hosted at:

https://intervene-eu-h2020.github.io/prs-method-compare/

🚨 This repository is in under active development with no stable releases available yet 🚨

## Build notes

To build the website from source you'll need the software installed on your system:

* [Quarto](https://quarto.org)
* [R](https://www.r-project.org)

And an R package:

* [`renv`](https://rstudio.github.io/renv/articles/renv.html)

Then run:

```
$ git clone https://github.com/intervene-EU-H2020/prs-method-compare.git
$ cd prs-method-compare/
$ R
> renv::restore() # installs dependencies
$ quarto preview # builds and opens website in your browser
```