# amyloid-Beta-microglia
Maude code for representing, simulating, and analyzing the cellular and molecular interactions that mediate the reactions of microglia to amyloid-Beta. Additional Maude code represents the effects of multiple drugs on the reactions of microglia to amyloid-Beta, and estimates the abilities of various drug combinations to reduce the inflammatory response of microglia to amyloid-Beta. This work is described in the following two journal articles:  

Anastasio TJ (2015) Temporal-logic analysis of microglial phenotypic conversion with exposure to amyloid-β. Molecular BioSystems. 11:434-453.
Anastasio TJ (2015) Computational identification of potential multi-drug combinations for reduction of microglial inflammation in Alzheimer disease. Frontiers in Pharmacology. 6:116.  

The following Maude files specify and analyze the cellular and molecular interactions that mediate the reactions of microglia to amyloid-Beta. 

admicro.txt -- this module specifies molecular interactions relavant to the amyloid-Beta-microglia model  
mc-admicro.txt -- this module sets up model-checking of the amyloid-Beta-microglia specification  
admicro-check.txt -- this command model-checks the amyloid-Beta-microglia specification  
admicro-rew.txt -- this command initiates rewrites in the amyloid-Beta-microglia specification  
admicro-search.txt -- this command executes searches in the amyloid-Beta-microglia specification  

The following Maude files correspond to the previous ones with the additional specifications of drug effects. 

admicrodrugs.txt -- this module specifies interactions relavant to drug effects on amyloid-Beta-microglia model  
mc-admicrodrugs.txt -- this module sets up model-checking of the amyloid-Beta-microglia-drugs specification  
admicrodrugs-check.txt -- this command model-checks the amyloid-Beta-microglia-drugs specification  
admicrodrugs-rew.txt -- this command initiates rewrites in the amyloid-Beta-microglia-drugs specification  
admicrodrugs-search.txt -- this command executes searches in the amyloid-Beta-microglia-drugs specification  





