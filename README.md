# Supplementary Material 

Scripts and data necessary to produce theoretical Figures in **"Differences in vertical and horizontal transmission dynamics shape plasmid distribution in clinical enterobacteria"**, A Alonso-del Valle, L Toribio-Celestino, A Quirant, C Tardio Pi, J DelaFuente, R Canton, E Rocha, C Ubeda, R Peña-Miller and A San Millan.

The supplementary material outlines a model designed to study the plasmid dynamics within bacterial populations under the influence of antibiotic treatment. This exploration is conducted via computational simulations, with a particular emphasis on understanding the behavior of plasmid-bearing populations in response to antibiotics under varied environmental conditions. The goal is to pinpoint the conditions that promote plasmid persistence within the population.

Our model incorporates key elements such as plasmid transfer, segregational loss, and the pressure exerted by antibiotic-induced selection. Through simulation of various scenarios, we study how these factors shape plasmid dynamics and dictate the overall response of bacterial communities to antibiotics.


The repository is organized into a series of Jupyter notebooks, each detailing a different aspect of our research:

[1. Modelling of Bacterial Growth and Plasmid-Driven Antibiotic Resistance](py_pOXA48_SI1_model.ipynb): This notebook provides an overview of our mathematical model, which describes the growth kinetics and plasmid dynamics in clonal bacterial populations.

[2. Model parametrization](py_pOXA48_SI2_parametrization.ipynb): Here, we show how our model was parameterized using empirical data from lab-based experiments.

[3. Modeling plasmid dynamics in multistrain communities](py_pOXA48_SI3_multistrain.ipynb): In this notebook, we extend our model to multi-strain communities and describe the computational methods used to incorporate multiple strains into the model.

[4. Computational Simulations of Pair-wise Interactions](py_pOXA48_SI4_pairwise.ipynb): We present a series of computational simulations that depict the dynamics of pair-wise interactions between different bacterial strains in the presence of plasmid and antibiotic.

[5. Computational Simulations of Multi-Species Bacterial Communities](py_pOXA48_SI5_communities.ipynb): In this notebook we use our model to simulate complex, multi-species bacterial communities and analyze the resulting dynamics under various selective conditions.

[6. Computational Simulations of Multi-Species Bacterial Communities](py_pOXA48_SI6_analysis.ipynb): Finally, here we visualize the results obtained in the numerical experiments.

