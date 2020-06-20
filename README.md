# A tutorial for litsearchr

The R package `litsearchr` provides various functions to help with planning a systematic search of the scientific literature on a given topic. This short tutorial gives an example of how to use `litsearchr`, along with some brief explanations of its workings. `litsearchr` was created by the amazing [Eliza Grames](https://elizagrames.github.io), and a lot of this tutorial is an elaboration of the existing [vignette](https://elizagrames.github.io/litsearchr/litsearchr_vignette_v041.html) for the package.

Head [here](litsearchr_tutorial.html) for the main tutorial page.

## Additional files

* [litsearchr_tutorial.Rmd](litsearchr_tutorial.Rmd): R markdown source for the tutorial page.
* [pubmed-medication-set.nbib](pubmed-medication-set.nbib): Example *nbib* file of search results retrieved from [PubMed](https://pubmed.ncbi.nlm.nih.gov/advanced).
* [clin_psy_stopwords.txt](clin_psy_stopwords.txt): Example file of stopwords related to the search topic used in the tutorial.
* [search-inEnglish.txt](search-inEnglish.txt): Example search query produced by the `write_search()` function.

## R packages

You will need the following R packages to run the code from the tutorial yourself:

* `dplyr`
* `ggplot2`
* `ggraph`
* `igraph`
* `readr`

Instructions for installing `litsearchr` are provided in the tutorial.
