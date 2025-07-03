# ISMEM: Intrinsic Semiparametric Mixed Effects Model for Longitudinal Manifold-valued Data

This repository presents the web visualization and downloadable materials for the paper:

"Intrinsic Semiparametric Mixed Effects Model for Longitudinal Manifold-valued Data"

## Abstract
This paper introduces a novel intrinsic semiparametric mixed-effects model (ISMEM) to characterize the complex relationships between manifold-valued responses and Euclidean-valued covariates in the longitudinal setting.
Manifold-valued data, characterized by their inherent nonlinearity,  high dimensionality, and specific geometric structures, present significant challenges for longitudinal analysis. Most existing intrinsic models are developed for cross-sectional data and unsuited for longitudinal studies. 
To address this limitation, we propose ISMEM, an efficient framework designed for longitudinal manifold-valued datasets that capture such relationships at both group and individual levels. 
Key features of ISMEM include (i) the integration of fixed and random effects on Riemannian manifolds, enabling analysis at multiple levels; (ii) a semiparametric structure combining parametric and nonparametric components, enhancing both flexibility and interpretability; (iii) the preservation of the geometric properties of manifold-valued observations, offering improved robustness and interpretability compared to Euclidean-based models. 
In addition, we develop a two-stage iterative estimation procedure and validate our approach through simulations on the symmetric positive definite (SPD) manifold. Finally, we apply ISMEM to longitudinal data from the Alzheimer's Disease Neuroimaging Initiative (ADNI), reconstructing and comparing continuous 3D shape trajectories of the lateral ventricle in Kendall shape space across distinct groups. 

## Real Data Experiment

We apply ISMEM to study shape changes in the left lateral ventricle (LLV) using longitudinal MRI data from the ADNI-GO and ADNI2 cohorts. Surfaces are represented in Kendall shape space after segmentation and parameterization. ISMEM accurately reconstructs both global and subject-level trajectories, outperforming competing methods such as RNLMM and LESA, especially in detecting localized anatomical deformations associated with aging and Alzheimer's disease.

## Website

Visit the project website at:

https://daisyxiong77.github.io/ISMEM/

It contains:

- Visualization of LLV evolution
- Downloadable presentation slides
- A summary of the paper's contributions and experimental results


