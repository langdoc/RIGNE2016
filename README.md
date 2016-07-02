# RIGNE2016

Webpage for the conference on «Documentation,  Standardization  and  Teaching  of  Endangered  Languages  in Northern Eurasia», Murmansk 2016

## Note for writers

The gh-pages branch is most conveniently updated by editing markdown files and running:

    Rscript build.R

After which the master is committed as usual, but the gh-pages branch can be pushed like this:

    git subtree push --prefix _site origin gh-pages

Inbetween the website can be viewed in _site folder. R is used to simplify the transformation from Markdown to HTML, so R package [rmarkdown](https://cran.r-project.org/web/packages/rmarkdown/rmarkdown.pdf) has to be installed. It can be installed with following R command:

     install.packages("rmarkdown")
