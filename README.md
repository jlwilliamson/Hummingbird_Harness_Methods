# Hummingbird Harness Methods

Quick code associated with Williamson &amp; Witt, "A lightweight backpack harness for tracking hummingbirds", In Revision. 

Folder `0_raw_data` contains all raw data associated with Giant Hummingbirds described in our paper. 

Folder `1_r_scripts1` contains:
`Harness_Methods.Rmd`: Simple code for running linear mixed effects models (lmer) to evaluate the impacts of time of day and month, respectively, on mass. And, code to produce Figure S1 (mass change between deployment and recapture, reported in Supplementary Material. 

`HarnessMethods_CJS.Rmd`: Code associated with data wrangling, running, and troubleshooting Cormack-Jolly-Seber (CJS) models. Extensive annotations to describe many quirks associated with using a small dataset for these models. This script also includes code to produce plots comparison the sensitivity of survival rate and probability of capture estimates across various test datasets, as well as a plot to compare survival rate estimates for hummingbird species described in the literature. 

Any figure *not* listed in these scripts was produced in Adobe Illustrator. 