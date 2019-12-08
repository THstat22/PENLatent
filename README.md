# PENLatent

Input for PENLatent: a penalized structural equation modeling to incorporate multiple secondary phenotypes, case-control status and gene expression variables.

D, Case-control status for a studied disease. A vector with (0,1) entries for N samples.

X, Continuous variables such as the gene expression variables. A matrix with dimension N x P for P genes and N samples. 

Y, Continuous secondary traits for the studied disease. A matrix with dimension N x Q for Q secondary traits and N samples. 

penalty, Penalty function, it can be Lasso or Log penalty.

lambda_vec, A vector of tuning values for lambda of Lasso or Log penalty.

tau_vec, A vector of tuning values for tau of Log penalty.

dfmax, the upper bound of the number of non-zero estimates of coefficients for X.

NumIter, The number of maximum iterations for the estimation procedure.


Usage:
The current version only work on Unix, Linux and Mac System, R(>=3.4.3), R package "psyche" and GCC(>=4.4.7) are required.

Modify the parameters in the PENLatent.R, and execute it.

Example
Please find it in the R package.

Future extensions
Contact

Ting-huei Chen, ting-huei.chen@mat.ulaval.ca
