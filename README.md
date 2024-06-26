# pgs-method-compare

A website that describes the performance of PGS development methods across five European biobanks.

## Build notes

To build the website from source you'll need:

-   [Quarto](https://quarto.org) (tested with `v1.3.433`)
-   [R](https://www.r-project.org) (tested with `v4.3.1`)

And an R package:

-   [`renv`](https://rstudio.github.io/renv/articles/renv.html) (tested with `v1.0`)

Then run:

```         
$ git clone https://github.com/intervene-EU-H2020/pgs-method-compare.git
$ cd pgs-method-compare/
$ R
> renv::restore() # installs dependencies
$ quarto preview # builds and opens website in your browser
```

## License

The website is permissively licensed with [Apache 2](https://github.com/intervene-EU-H2020/pgs-method-compare/blob/main/LICENSE).

If you reuse data or code from this website in published work please cite our publication, which is also available as [an open access preprint](https://doi.org/10.1101/2023.11.20.23298215):

> Remo Monti, Lisa Eick, Georgi Hudjashov, Kristi Läll, Stavroula Kanoni, Brooke N. Wolford, Benjamin Wingfield, Oliver Pain, Sophie Wharrie, Bradley Jermy, Aoife McMahon, Tuomo Hartonen, Henrike Heyne, Nina Mars, Samuel Lambert, Kristian Hveem, Michael Inouye, David A. van Heel, Reedik Mägi, Pekka Marttinen, Samuli Ripatti, Andrea Ganna, Christoph Lippert. "Evaluation of polygenic scoring methods in five biobanks shows larger variation between biobanks than methods and finds benefits of ensemble learning" The American Journal of Human Genetics 2024. doi: https://doi.org/10.1016/j.ajhg.2024.06.003
