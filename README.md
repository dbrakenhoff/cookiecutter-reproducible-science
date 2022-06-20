Reproducible Science
====================

A boilerplate for reproducible and transparent science with close resemblances
to the philosophy of [Cookiecutter Data
Science](https://github.com/drivendata/cookiecutter-data-science): *A logical,
reasonably standardized, but flexible project structure for doing and sharing
data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:dbrakenhoff/cookiecutter-reproducible-science`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── bin                <- Your compiled model code can be stored here (not tracked by git)
├── config             <- Configuration files, e.g., for doxygen or for your model if needed
├── data
│   ├── 1-external       <- Data from third party sources.
│   ├── 2-interim        <- Intermediate data that has been transformed.
│   ├── 3-processed      <- The final, canonical data sets for modeling.
│   └── 4-output         <- Model output
├── docs               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── notebooks          <- Ipython notebooks
├── reports            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── src                <- Source code for this project
    ├── 0-setup          <- setup environment etc.
    ├── 1-dataprep       <- Scripts and programs to process data
    ├── 2-model          <- Source code for building and running your own model
    ├── 3-analysis       <- Scripts for post-processing/analysis of your results
    ├── 4-visualization  <- Scripts for visualisation of your results
    └── tools            <- Any helper scripts go here
```

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
