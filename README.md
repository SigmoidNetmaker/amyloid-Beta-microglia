# amyloid-Beta-microglia
MATLAB and Maude code for representing, simulating, and analyzing the cellular and molecular interactions that mediate the reactions of microglia to amyloid-Beta. Additional MATLAB code compares estimates of the efficacy of various drug combinations from the model with those derived from a human Alzheimer's database. This work is described in the following three journal articles:  

Anastasio TJ (2015) Temporal-logic analysis of microglial phenotypic conversion with exposure to amyloid-β. Molecular BioSystems. 11:434-453.
Anastasio TJ (2015) Computational identification of potential multi-drug combinations for reduction of microglial inflammation in Alzheimer disease. Frontiers in Pharmacology. 6:116.  
Anastasio TJ (2019) Exploring the correlation between the cognitive benefits of drug combinations in a clinical database and the efficacies of the same drug combinations predicted from a computational model. Journal of Alzheimer's Disease. 70:287-302.  

The following Maude files specify and analyze the cellular and molecular interactions that mediate the reactions of microglia to amyloid-Beta. To a relativey large set of declarations were later added additional specifications of drug effects. 

admicro.txt -- this module specifies molecular interactions relavant to the amyloid-Beta-microglia model  
mc-admicro.txt -- this module sets up model-checking of the amyloid-Beta-microglia specification  
admicro-check.txt -- this command model-checks the amyloid-Beta-microglia specification  
admicro-rew.txt -- this command initiates rewrites in the amyloid-Beta-microglia specification  
admicro-search.txt -- this command executes searches in the amyloid-Beta-microglia specification  







