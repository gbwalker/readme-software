# readme2

This fork corrects line 49 in `readme2_helper_fxns.R` that prevents a proper installation of the package from GitHub. Find the original version [here](https://github.com/iqss-research/readme-software), or download this version with:

`devtools::install_github("gbwalker/readme-software/readme")`

Specifically, I change

  `my_text <- gsub(my_text, pattern = "<3", replace = " ♥ ")`

to

  `my_text <- gsub(my_text, pattern = "<3", replace = " <heart> ")`
