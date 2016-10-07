# RIGNE2016

Source for the webpage of the conference on [«Documentation,  Standardization  and  Teaching  of  Endangered  Languages  in Northern Eurasia»](https://langdoc.github.io/RIGNE2016/), Murmansk 2016

## Note for writers

The gh-pages branch is most conveniently updated by editing the markdown files and running:

    Rscript build.R

After which the master is committed as usual. In addition, the gh-pages branch can be pushed like this:

    git subtree push --prefix _site origin gh-pages

The compiled HTML files can also be opened locally from the _site folder. 

Note that R is used here to simplify the transformation from Markdown to HTML, therefore the R package [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/rmarkdown.pdf) needs to be installed. You can installed this package with the following R command:

     install.packages("rmarkdown")
