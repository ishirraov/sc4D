# sc4D

Code and data for the manuscript:  
**sc4D: spatiotemporal single-cell transcriptomics analysis through embedded optimal transport identifies joint glial response to Alzheimer’s disease pathology**  
by *Rao et. al*,

## Abstract

A precise understanding of disease-associated spatio-temporal transcriptional dynamics is critical for nominating therapeutic interventions that drive desired perturbation responses. In disease contexts, pathological processes unfold across diverse cellular states, spatial environments, and timescales; however, current computational approaches have a limited ability to jointly model these complex dynamics or infer cellular trajectories from in silico perturbation experiments. Here, we present sc4D, a biologically-interpretable spatio-temporal (4D) analysis framework for single-cell transcriptomics in disease studies, integrating autoencoder embeddings with optimal transport. Applying sc4D to longitudinal spatial transcriptomics samples from Alzheimer’s disease mouse models, we report known disease biology and novel, testable mechanisms, including late-stage microglia-astrocyte syncytium near amyloid-β plaques. In silico perturbations predict the restoration of protective, anti-inflammatory microglia through CAMTA1 activation or Donepezil, as validated by independent experimental findings. Overall, our work highlights the critical benefits of joint spatio-temporal modeling for elucidating disease mechanisms and predicting candidate interventions to improve cellular response.

## Files

Labeled-8-Disease.csv (Input data for 8-month disease sample),
Labeled-13-Disease.csv (Input data for 13-month disease sample),
sc4D_Autoencoder.ipynb (Code for autoencoder training),
sc4D_Optimal_Transport_Analysis.ipynb (Code for optimal transport and trajectory inference),
sc4D_SpatialAnalysis.ipynb (Code for spatial analysis and GSEA),
README.md (Project overview and usage instructions)


