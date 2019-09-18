# genetic-mapping

Genetic mapping using the Collaborative Cross founder probability files for a simple trait. This example uses publicially available genotype data found on http://csbio.unc.edu/CCstatus/index.py?run=FounderProbs and publically available phenotype data found on http://csbio.unc.edu/CCstatus/index.py?run=availableLines as of September 2019. 

The file CC_mapping_example.Rmd contain the R code for a QTL analysis, as well as steps for building a probability array, estimating heritability, and doing an association analysis. 

The phenotype file is CC_color.csv

The map file is fixedmap.csv

The files MRCAlist.csv and MRCAlist2.csv are the samples that I used to build the 36-state probability array and collapse into an 8-state for the QTL analysis. These names and CC mice may change over time.