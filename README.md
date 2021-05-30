# SARS-CoV-2_EUR_PHYLOGEOGRAPHY
repo associated with a manuscript on SARS-CoV-2 phylogeographic spread in western Europe.

The XMLs can be run using the hmc-develop branch of the BEAST codebase available at https://github.com/beast-dev/beast-mcmc.
- SC2eur_thGLM3cov.xml: requires the genome data from GISAID.org. Joint sequence and location inference using a discrete trait GLM with three time-homogeneous covariates
- SC2eur_epoch3covHomoCoeff.xml: uses empirical.trees and includes three time-inhomogeneous covariates
- SC2eur_epoch3covHierarchIncl.xml: uses empirical.trees and includes three time-inhomogeneous covariates along with time-inhomogeneous inclusion probabilities with a hierarchical graph prior
- SC2eur_epochTHREs.xml: uses empirical.trees and includes three time-inhomogeneous covariates, time-homogeneous random effects, and epoch rate scalars that are a function of the overall mobility data.