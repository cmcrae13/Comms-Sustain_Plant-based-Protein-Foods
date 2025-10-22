# The Role of Price and Socioeconomic Status in Advancing an Equitable Sustainability Transition to Plant-Based Proteins — *Communication Sustainability Paper*

This repository contains Stata and Python code used to estimate price responsiveness and identify socioeconomic status (SES) clusters in **Finland** and **Canada**.  

The analyses form part of the *Communication Sustainability* project, examining how **price sensitivity** and **socioeconomic status (SES)** shape transitions toward sustainable, plant-based food consumption.

---

## 🧩 Repository Contents

| File | Description |
|------|--------------|
| **Comms Sustain_STATA code.do** | Stata script for mixed-effects models estimating the relationship between price and demand across SES clusters, product categories, and countries. Includes full and base model specifications. |
| **Comms Sustain_Python_Finland_clustering_individual_survey.ipynb** | Python notebook for individual-level SES clustering in Finland using survey data. Performs preprocessing and K-Modes clustering. |
| **Comms Sustain_Python_Finland_clustering_neighborhood_census.ipynb** | Python notebook for neighborhood-level SES clustering in Finland using census data. Performs preprocessing and K-Means clustering. |
| **Comms Sustain_Python_Canada_clustering_neighborhood_census.ipynb** | Python notebook for neighborhood-level SES clustering in Canada using census data. Performs preprocessing and K-Means clustering. |

---

## 🧠 Overview

This code supports a cross-country comparison of **price elasticity** and **socioeconomic heterogeneity** in consumer food choices, focusing on plant-based and animal-based product categories.  

- The **Python notebooks** prepare and cluster SES data at both individual and neighborhood levels using K-Means or K-modes, guided by the **elbow method** to determine the optimal number of clusters (typically *k = 3*).  
- The **Stata do-file** then estimates **mixed-effects models** (`mixed`) linking log(price) to log(volume) sold, with SES interactions and store/time controls, producing the coefficients used in the final **meta-analysis robustness checks**.

---

## ⚙️ Data

Note that the raw data used for the clustering and regression modelling cannot be shared publically due to non-disclosure agreeements with retailers in Finland and Canada. However, the dataset used for the meta-analysis is available for download at: https://doi.org/10.5281/zenodo.17419417

