# FWS ESA Work Plan Species Evaluation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/usgs-bcb/FWS-ESA-WorkPlanSpecies/master)

This repository contains code for processing a list of 363 species that the USFWS has on their workplan as candidate species in the petition process through the Taxa Information Registry, a set of data processing algorithms we are developing under the Biogeographic Information System. This is all very experimental at this stage and should not be used beyond internal evaluation and discussions. The purpose of this exercise is to examine what all information we can bring together from across various available public data sources to aid in the work of evaluating the current state of scientific knowledge about these species.

This is still very much a work in progress, but I've got it to a basic starting point. There are now just two main notebooks to look over here:

* ESA WP Species TIR Processing.ipynb - This has all of the core algorithms for processing the data into our DataDistillery database and running through all the Taxa Information Registry functions. It shows what it's doing along the way and can be viewed in raw form in GitHub to gain a basic understanding of the data being assembled.
* ESA Work Plan Species Reports.ipynb - This is just a basic start at the types of analyses and reporting we might be able to do with the assembled information. I have not yet gone through all the different pieces of information to explore possibilities for reporting and will come back to this soon.
