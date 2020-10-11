# CNDD_and_why_its_study_should_not_be_abandoned
This GitHub repository contains R scripts to reproduce all analyses presented in our 2020 Ecosphere paper, entitled 
"Conspecific negative density dependence and why its study should not be abandoned" by J. LaManna, S. Mangan, and J. Myers

## FILES 

1. LaManna_et_al_2020_Ecosphere_R_code_for_analyses_20201009.R
   - contains R script to perform re-analyses of data from tropical (BCI) and temperate (SERC) forests presented in Fig. 1 of our paper
   - *IMPORTANT*: Before running analyses in "LaManna_et_al_2020_Ecosphere_R_code_for_analyses_20201009.R", please download the data files
     "bci.mat" and "serc.mat", which can be obtained at: https://github.com/mdetto/Bias-in-the-detection-of-negative-density-dependence, and 
     ensure that these data files are in your R console's working directory. The R package 'R.matlab' is also required to load data, and can be found at R CRAN.
   - Additional notes are embedded as comments in the R script. 

2. LaManna_et_al_2020_Ecosphere_CNDD_Model_Benchmark_Tests_20201009.R
   - contains R script to run the benchmark simulation tests presented in Fig. 2 of our paper.
