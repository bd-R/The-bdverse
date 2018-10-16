---
layout: default
---

<img src="assets/images/bdclean_bdverse.png" alt="bdclean in the bdverse" width="400"/>
<a href="https://github.com/bd-R/bdclean" target="_blank"><img src="assets/images/github_repo.png" alt="bdclean GitHub repository" title= "Open bdclean repository" width="90"/></a>
   <a href="https://bd-r.github.io/bdclean-guide/" target="_blank"><img src="assets/images/user_guide.png" alt="bdclean user guide" title= "Open the complete user guide" width="120"/></a>

## Overview

`bdclean` is a user-friendly data cleaning Shiny app for the inexperienced R user. It provides features to manage complete workflow for biodiversity data cleaning, from uploading the data; collecting user input - in order to adjust cleaning procedures; cleaning the data; and finally, generating various reports and several versions of the data.
In order for `bdclean` to truly be practical, several unique and challenging R components were developed, such as a questionnaire module and high-quality reports mechanism. Also, since `bdclean` was developed for the inexperienced R user in mind, `bdclean` GUI must be exceptionally intuitive.

## Architecture

[TBA]

## Main challenges

* Continuous Integration (CI) is more challenging for `bdclean` as it highly depended on many R packages outside the `bdvers` and within the `bdverse`. 
* `bdclean` is a complex Shiny app, comprehensive testing techniques for apps are more challenging.

## Future Plans

We invested considerable efforts on make `bdclean` easily customized, with intent to adjust `bdclean` to various research types. Right now the questionnaire and the cleaning procedures are  designed for researchers dealing with species distribution modeling, as biodiversity data is being highly utilized for SDMs. We hope that with the help of the Biodiversity Informatics community, we'll be able to adjust `bdclean` to various research domains, such as (i) alien and invasive species; (ii) collection data; (iii) agrobiodiversity; (iv) marine species; and (v) citizen science.