# AI Discovery of Unknown Multi-Disease Phenotypes in Longitudinal Electronic Health Records

This research project explores the use of advanced artificial intelligence (AI) techniques to identify novel, previously unknown multi-disease phenotypes from longitudinal Electronic Health Records (EHRs). It aims to uncover hidden patterns and disease clusters that co-occur over time, offering new insights into complex patient journeys and improving predictive medicine.

## Research

Modern healthcare generates vast amounts of EHR data, capturing a timeline of clinical interactions, diagnoses, medications, and laboratory results. Yet, current methods often treat diseases in isolation, ignoring the underlying interconnected nature of chronic and comorbid conditions. This project seeks to leverage temporal data and AI to:

- Discover unknown disease phenotypes and co-morbidity trajectories.
- Enable early detection of high-risk patient clusters.
- Improve disease progression modeling for personalized medicine.

## Methods

The project applies a combination of:

- **Temporal representation learning** on EHR sequences.
- **Autoencoders and deep clustering** to extract latent phenotype embeddings.
- **Contrastive learning** to differentiate patient outcomes.
- **Graph Neural Networks (GNNs)** to model patient similarity and disease co-occurrence networks.
- **Dimensionality reduction and visualization** using t-SNE/UMAP for phenotype interpretation.

### Data Source

- Synthetic MIMIC-IV or real-world longitudinal EHR datasets (HIPAA-compliant).
- Focus on adults with ≥5 years of medical history and multi-disease profiles.

## 💡 Goals & Outcomes

- Identify interpretable latent phenotypes linked to multiple diseases.
- Validate phenotypes using clinical characteristics and known medical knowledge.
- Build a phenotype-aware prediction model for future disease risk.

## 📊 Tools & Frameworks

- Python, PyTorch, scikit-learn, pandas, NumPy
- Hugging Face Transformers (for patient sequence modeling)
- TensorBoard, Weights & Biases (W&B) for experiment tracking
- Jupyter Notebooks & Colab for prototyping
