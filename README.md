# AlTaieFarrow1
Code associated with "Bayes linear Bayes networks with an application to prognostic indices" by W.A.J. Al-Taie and M. Farrow

The repository contains the following files.

Offline6BUG.txt

      JAGS model specifications for offline learning: Six-covariate example

Offline10BUG.txt

      JAGS model specifications for offline learning: Ten-covariate example

VarZ-R.txt

      R code to compute the posterior mean of the variance of the latent variables Z from the MCMC 
      samples

indexBLK-R.txt

     R function to compute prognostic index values for patients in the data set (6-covariate example)
     The function was called using the following command.

      indexvaluesBLK<-indexBLK(NHLdata,V0,mu0,musex,muage,cuts)


BLKindex-R.txt

     R function to compute the prognostic index value for an individual patient (6-covariate example)

adjbynorm-R.txt

     R function to compute the update given the normally distributed covariates

adjbynormnew-R.txt

     More general version of the R function to compute the update given the normally distributed 
     covariates

adjbynoncon-R.txt

      R function to compute the update given a binary or ordinal covariate.
      Note that binary and ordinal variables were coded with the first category labelled 0. 
      The binary variables had class labels 0, 1. Stage has class labels 0, 1, 2, 3 and ECOG has 
      class labels 0, 1, 2, 3, 4. 
      So the function adds 1 to the values for the index of the cut-points. In the case of an 
      interval-censored value of LDH, the class labels 
      are 0, 1, 2 but the observed class is always 1.
