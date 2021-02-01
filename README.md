#Imprementing GBLUP with numpy

Genomic best linear unbiased prediction (GBLUP) is the most widely used genomic prediction technique for quantitative trait prediction. GBLUP is applied the best linear unbiased prediction (BLUP) method, which is used to estimate random effects in statistics, to genomic prediction. It is an elegant method that simply uses a genomic relationship matrix (GRM) built from the genotypes instead of a variance-co-variance matrix in BLUP. This code implements the process of calculating GRM from DNA information and applying them to the BLUP model for predicting genetic ability of individuals.

A detailed description of the code can be found at https://gywns6287.github.io/posts/GBLUP/.