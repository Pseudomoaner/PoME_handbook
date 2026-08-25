GithubPages can be accessed here: https://pseudomoaner.github.io/PoME_handbook 

Deploy with: 

```
setwd('path/to/github/folder')
library(bookdown)
bookdown::clean_book(TRUE)
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```
