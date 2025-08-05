# AI Discovery of Novel Longitudinal Disease Phenotypes in Electronic Health Records

This research project explores the use of advanced artificial intelligence (AI) techniques to identify novel, previously unknown longitudinal disease phenotypes from Electronic Health Records (EHRs). It aims to uncover hidden patterns and disease clusters that occur over time, offering new insights into complex patient journeys and improving predictive medicine.

## Research

Modern healthcare generates vast amounts of EHR data, capturing a timeline of clinical interactions, diagnoses, medications, and laboratory results. Yet, current methods often treat diseases in isolation, ignoring the underlying interconnected nature of chronic and comorbid conditions. This project seeks to leverage temporal data and AI to:

- Discover longitudinal disease phenotypes and co-morbidity trajectories.
- Enable early detection of high-risk patient clusters.
- Improve disease progression modeling for personalized medicine.

## Methods

The project applies a combination of:

- **Temporal representation learning** on EHR sequences.
- **Autoencoders and deep clustering** to extract latent phenotype embeddings using **TS2VEC**.
- **Dimensionality reduction and visualization** using UMAP for phenotype interpretation.

### Data Source

- MIMIC IV Dataset.
- Focus on adults with ≥5 years of medical history and multi-disease profiles.

## Goals & Outcomes

- Identify interpretable latent phenotypes linked together over time.
- Validate phenotypes using clinical characteristics and known medical knowledge.
- Build a phenotype-aware prediction model for future disease risk.

## Tools & Frameworks

- Python, scikit-learn, pandas, NumPy
- Jupyter Notebooks & Colab for prototyping
