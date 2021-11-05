# AlTaieFarrow1
Code associated with "Bayes linear Bayes networks with an application to prognostic indices" by W.A.J. Al-Taie and M. Farrow

The repository contains the following files.

Offline6BUG.txt

      JAGS model specifications for offline learning: Six-covariate example

Offline10BUG.txt

      JAGS model specifications for offline learning: Ten-covariate example

VarZ-R.txt

      R code to compute the posterior mean of the variance of the latent variables Z from the MCMC samples

indexBLK-R.txt

     R function to compute prognostic index values for patients in the data set (6-covariate example)
     The function was called using the following command.

      indexvaluesBLK<-indexBLK(NHLdata,V0,mu0,musex,muage,cuts)


BLKindex-R.txt

     R function to compute the prognostic index value for an individual patient (6-covariate example)

adjbynorm-R.txt

     R function to compute the update given the normally distributed covariates
