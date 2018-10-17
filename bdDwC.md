---
layout: default
---
## bdDwC: user level standardization of biodiversity data 

 <img src="assets/images/bdDwC_bdverse.png" alt="bdDwC in the bdverse" width="450"/>
<a href="https://github.com/bd-R/bdDwC" target="_blank"><img src="assets/images/github_repo.png" alt="bdDwC GitHub repository" title= "Open repository" width="90"/></a>
   <a href="https://bd-r.github.io/bdDwC-guide/" target="_blank"><img src="assets/images/user_guide.png" alt="bdDwC user guide" title= "Open the complete user guide" width="120"/></a>


`bdDwC` is an R package that provides an interactive Shiny app and a set of functions for standardizing field names in compliance with the Darwin Core (DwC) format. Running bdDwC enables you to carefully standardize all field names in your dataset – which allows the `bdverse` to handle data from various biodiversity portals seamlessly, and lets you enjoy all of its features, regardless of publishers' variation in field names.
The development of bdDwC was inspired by the <a href="http://kurator.acis.ufl.edu/kurator-web/" target="_blank">Kurator project</a> <a href="https://github.com/kurator-org/kurator-validation/wiki/CSV-File-Darwinizer" target="_blank">'Darwinizer tool'</a>. `bdDwC` utilizes Darwin Cloud dictionary <a href="https://doi.org/10.3897/tdwgproceedings.1.20486" target="_blank">(Wieczorek et al. 2017)</a>, which is a lookup table that accumulates different variations in DwC field names, maintained by the Kurator team. It's also possible to add your own dictionary by creating a CSV file with two columns, one for the Field Names and one for the Standard Names.


## Architecture overview
![](assets/images/bdDwC_architecture_overview.png)


## Major challenges ahead

* Establishing and maintaining a robust workflow for feeding the Darwin Cloud - to address this issue, we'll consult key members of the biodiversity informatics community.
* "Darwinizing" a dataset is a basic task for all `bdverse` tools and workflows, thus developing an intensive QA shell is in order.

## Future plans

* Enhance the UI.
* Explore the idea of creating and maintaining a specific dictionary for each data publisher.
* Experiment with fuzzy matching techniques, to generate suggestions for matching fields.
* Explore techniques for enforcing recommended DwC vocabulary.
