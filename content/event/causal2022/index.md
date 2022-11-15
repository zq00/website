---
abstract: Severe mental disorders (e.g., schizophrenia, bipolar disorder, and major depressive disorder) are complex diseases that are influenced both by genetic and environmental factors. Psychiatrists are interested in pinpointing single nucleotides polymorphism (SNPs) related to endophenotypes (e.g., psychosis or cognitive functions) in order to identify potential similar and distinct factors underlying different mental disorders. Suppose that the data is collected from a case-control study, i.e., whether a subject is in the study or not depends on their diagnosis, then we cannot use standard approaches to select variables or infer their effect sizes.  As an illustration, suppose one wants to understand the relationship between athletic ability (X) and artistic ability (Y) of high school students and suppose they collect data from students who have been admitted to a college (S). Since the selection event S is related to both X and Y, one cannot directly use this sample to estimate the relationship in the general population. In the genetic study, the collider bias is caused by the fact that endophenotypes are related to both the diagnosis and the genotype. While statisticians have developed several methods to address the collider bias, many of these approaches do not apply to genetic studies because the number of SNPs is high. On the other hand, the knockoff method offers a flexible approach to select relevant variants while at the same time controlling the false discovery rate (FDR). However, we cannot use the standard knockoff approach because the sampling distribution differs from the population distribution under collider bias. In this work, I show how to adjust the knockoff sampling process so that we control the FDR in the presence of collier bias. I demonstrate that we can control the FDR after using the proposed adjustment and discuss challenges when using the modified sampling process.  

address:
  city: Stanford
  country: United States
  postcode: "94305"
  region: CA
all_day: false
authors: 
- admin
date: "2022-11-13T10:00:00Z"
event: Stanford Causal Science Conference 
event_url: https://datascience.stanford.edu/causal/causal-science-conference-2022 
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

location: Koret-Taube Conference Center, SIPER Building 
tags: []
title: Selecting genetic variants using knockoffs under collider bias
url_slides: https://github.com/zq00/Presentations/tree/main/Causal2022
--- 


