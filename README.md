# R-notebook-amino-acids

Data and analysis pipelines for amino acid supplementation experiments in Synechocystis.

### Overview

This repository contains data from the analysis of a **CRISPRi repression library**. The experiments were carried out in the model cyanobacterium *Synechocystis sp.* PCC 6803. The repository contains raw data, processed data and R notebooks (`*.Rmd`) for next generation sequencing (NGS) of CRISPRi repression mutants.

All care was taken to adhere to good scientific practice in terms of statistics, reproducibility and code documentation. Please report any errors by filing a [github issue](https://github.com/m-jahn/R-notebook-amino-acids/issues) for this repository, or contact michael.jahn@scilifelab.se.

### How to run the pipeline(s)

The pipelines collected in this repository are self-contained and executable. The code _and_ the documentation are part of one and the same R markdown document for each pipeline. Pipelines can be downloaded and executed from the `pipeline` sub-folders. To simply view the rendered pipelines follow the links to the `*.html` reports at [Contents](#Contents).

To download the repository on your local drive use `git clone` in a (linux) terminal:

``` bash
cd /your-target-folder
git clone https://github.com/m-jahn/R-notebook-amino-acids
```

Open a pipeline with Rstudio and execute code (chunks) with the `Run` button.
Alternatively, open an interactive R session and render the R markdown pipeline:

``` bash
require(rmarkdown)
rmarkdown::render("pipeline.Rmd")
```

### Contents

- [_Synechocystis_ CRISPRi library to investigate the effect of amino cid supplementation](https://m-jahn.github.io/R-notebook-amino-acids/Amino_acid_analysis.nb.html)
