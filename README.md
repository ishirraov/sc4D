# sc4D

Code and data for the paper:  
**sc4D: spatiotemporal single-cell transcriptomics analysis through embedded optimal transport identifies joint glial response to Alzheimer’s disease pathology**  
by *Rao et. al*,

## Abstract

A precise understanding of disease-associated spatiotemporal transcriptional dynamics is critical for nominating therapeutic interventions that drive desired perturbation responses. In disease contexts, pathological processes unfold across diverse cellular states, spatial environments, and timescales; however, current computational approaches have a limited ability to jointly model these complex dynamics to infer cellular trajectories via in silico perturbation experiments. Here, we present sc4D (single-cells in four dimensions), the first biologically interpretable, unified spatiotemporal modeling framework for disease studies, by integrating autoencoder embeddings with optimal transport. Applying sc4D to longitudinal spatial transcriptomics from Alzheimer’s disease mouse models, we report known and novel testable disease mechanisms, including late-stage microglia-astrocyte syncytium near amyloid-β plaques. In silico perturbations predict the restoration of protective, anti-inflammatory microglia through CAMTA1 activation or Donepezil, as validated by the literature. Overall, our work highlights the critical benefits of joint spatiotemporal modeling for elucidating disease mechanisms and nominating interventions to improve cellular responses.

## Files

├── Labeled-13-Disease.csv/                # Input data for 13-month disease sample
├── Labeled-8-Disease.csv/                 # Input data for 8-month disease sample
├── sc4D_Autoencoder.ipynb/                # Code for autoencoder training
├── sc4D_Optimal_Transport_Analysis.ipynb/ # Code for optimal transport analysis (trajectory inference)
├── sc4D_SpatialAnalysis.ipynb/            # Code for spatial analysis + GSEA
└── README.md


