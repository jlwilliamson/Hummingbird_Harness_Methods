# Hummingbird Harness Methods

Code associated with Williamson &amp; Witt, "A lightweight backpack harness for tracking hummingbirds", In Revision. 

Folder `0_raw_data` contains all raw data associated with Giant Hummingbirds described in our paper. 

Folder `1_r_scripts1` contains:
`Harness_Methods.Rmd`: Basic code for running linear mixed effects models with 'lmer' to evaluate the impacts of time of day and month, respectively, on mass. Additionally, this script includes code to produce Figure S1 (mass change between deployment and recapture) and Figure S2 (effect of time of day on mass), reported in the Supplementary Material.

`HarnessMethods_CJS.Rmd`: Code associated with data wrangling, running, and troubleshooting Cormack-Jolly-Seber (CJS) models. Extensive annotations to describe many quirks associated with using a small dataset for these models. This script also includes code to produce plots to compare the sensitivity of survival rate and probability of capture estimates across various test datasets (not report in MS but part of procedural duty), as well as Figure 3, a plot to compare survival rate estimates for hummingbird species described from the literature. Data for this plot were compiled from the literature into Table 2. 

Any figure *not* listed in these scripts was produced in Adobe Illustrator. 