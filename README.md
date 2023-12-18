# Supplementary Material 

Scripts and data necessary to produce theoretical Figures in **"Antimicrobial resistance level and conjugation permissiveness shape plasmid distribution in clinical enterobacteria"**\ 
A Alonso-del Valle, L Toribio-Celestino, A Quirant, C Tardio Pi, J DelaFuente, R Canton, E Rocha, C Ubeda, R Peña-Miller and A San Millan.\
_Proceedings of the National Academy of Sciences_, 120: 51 (2023)\
[DOI: 10.1073/pnas.2314135120](https://doi.org/10.1073/pnas.2314135120)

## Overview

This supplementary material outlines a mathematical model designed to study the plasmid dynamics within bacterial populations under the influence of antibiotic treatment. This exploration is conducted via computational simulations, designed to understand the behavior of plasmid-bearing populations in response to antibiotics under varied environmental conditions.

Our model incorporates key elements such as resource-limited growth, antibiotic-induced killing, plasmid transfer and segregational loss. Through simulation of different population structures and environmental regimes, we study how these factors modulate the distribution of plasmids within the community and identify successful plasmid-host associations.

## Documentation

The repository is organized into a series of Jupyter notebooks, each detailing a different aspect of our research:

[1. Modelling of Bacterial Growth and Plasmid-Driven Antibiotic Resistance](py_pOXA48_SI1_model.ipynb): This notebook provides an overview of the mathematical model, which describes the growth kinetics and plasmid dynamics in clonal bacterial populations.

[2. Model parametrization](py_pOXA48_SI2_parametrization.ipynb): Here we show how our model was parameterized using empirical data from lab-based experiments.

[3. Modeling plasmid dynamics in multistrain communities](py_pOXA48_SI3_multistrain.ipynb): In this notebook we extend our model to multi-strain communities and describe the computational methods used to simulate a serial transfer experiment of a mixed population invaded by a conjugative plasmid.

[4. Computational Simulations of Pair-wise Interactions](py_pOXA48_SI4_pairwise.ipynb): We present a series of computational simulations that depict the dynamics of pair-wise interactions between different bacterial strains in the presence of plasmid and a range of antibiotic concentrations.

[5. Computer experiments: multistrain dose-response assays](py_pOXA48_SI5_dose-response.ipynb): In this notebook we use our model to evaluate how selective pressures shape plasmid distribution in multistrain populations.

[6. Computational Simulations of Multi-Species Bacterial Communities](py_pOXA48_SI6_knockout_simulation.ipynb): This notebook documents the implementation of the iterative knock-out simulations used in our study. The main goal here is to evaluate the stability of the plasmid following the sequential removal of strains, in order to identify strains that have a significant impact on plasmid stability within the community.

[7. Computer experiments: Analyzing results of iterative knock-out simulations](py_pOXA48_SI7_knockout_analysis.ipynb): Finally, here we visualize the results obtained from the iterative knock-out simulations. 
