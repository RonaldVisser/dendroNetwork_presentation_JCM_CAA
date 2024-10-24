# Developing the R package dendroNetwork for dendro-archaeology: lessons learned

Ronald Visser (Saxion University of Applied Sciences)\

Presentation given during the Joint Chapter Meeting CAA-NLFl and CAA-DE in Groningen on 24th of October 2024

## Abstract

Open Science in Archaeology and beyond is growing in the recent years. More and more code related to publications has been made available over the years (e.g. https://github.com/benmarwick/ctv-archaeology). I have also published papers (e.g. Visser 2021; Visser and Vorst 2022b) on network analyses of dendrochronological data from archaeological contexts in order to get an estimate of the provenance of wood used in the Roman period. We have found that the military timber supply was possibly different than the civilian supply and the wood for Roman barges was sometimes moved over long distances and combined with local wood. The related code to these papers was also published (e.g. Visser 2022; Visser and Vorst 2022a). Recently, I combined the code of those papers into a package for R (Visser 2024). Packages have many advantages, such as ease of use, enabling reproducibility and improving transparency. While creating this package (https://docs.ropensci.org/dendroNetwork/), I learned that I probably should have created a package in the first place (see also https://ropensci.org/blog/2024/06/06/from-scripts-to-package/). In this presentation, I will explain what lessons I learned in this process in relation to developing, documentation, continuous integration, packaging, and how open peer review through rOpenSci has benefited the development of a package. This will hopefully enable others to more easily contribute to Open Science in archaeology.

## References

Visser, RM. 2021 Dendrochronological Provenance Patterns. Network Analysis of Tree-Ring Material Reveals Spatial and Economic Relations of Roman Timber in the Continental North-Western Provinces. Journal of Computer Applications in Archaeology 4(1): 230--253. DOI: https://doi.org/10.5334/jcaa.79.

Visser, RM. 2022 Dendrochronological Provenance Patterns. Code and Data of Network Analysis of Tree-Ring Material. DOI: https://doi.org/10.5281/zenodo.10200361.\
Visser, RM. 2024 dendroNetwork: a R-package to create dendrochronological networks. DOI: https://doi.org/10.5281/zenodo.10636310.

Visser, RM and Vorst, Y. 2022a Analyses, data and figures related to: 'Connecting ships: using dendrochronological network analysis to determine the wood provenance of Roman-period river barges found in the Lower Rhine region and to visualise patterns of wood use'. DOI: https://doi.org/10.5281/zenodo.7243539.

Visser, RM and Vorst, Y. 2022b Connecting Ships: Using Dendrochronological Network Analysis to Determine the Wood Provenance of Roman-Period River Barges Found in the Lower Rhine Region and Visualise Wood Use Patterns. International Journal of Wood Culture 3(1--3): 123--151. DOI: https://doi.org/10.1163/27723194-bja10014.
