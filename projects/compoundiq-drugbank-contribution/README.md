# CompoundIQ - DrugBank Data Engineering Contribution

## Project Type

CompoundIQ was a **group capstone project** for ITAI 2277. The full project explored an AI-powered system for evaluating safe three-drug combinations by connecting biomedical NLP, molecular generation, engineered drug features, and graph-based interaction prediction.

This folder highlights **my individual contribution** to the project: DrugBank data preprocessing, feature engineering, EDA support, and portfolio-ready documentation.

## What I Personally Worked On

My main responsibility was the DrugBank component. I worked on turning raw biomedical drug data into structured features that could support downstream model training and interaction prediction.

Key tasks included:

- Parsing the DrugBank XML file into structured data.
- Creating compact tables for drugs, interactions, targets, and enzymes.
- Removing duplicated drug entries and standardizing records.
- Engineering interaction count features.
- Engineering CYP enzyme and metabolic complexity features.
- Creating an interpretable safety complexity score.
- Preparing an active subset of drugs with interaction or CYP information.
- Creating train/validation/test splits.
- Explaining sparsity and long-tail behavior in the DrugBank data.
- Building the Phase 2 data pipeline and EDA presentation.

## Related Work I Reviewed

To understand how my part connected to the full capstone pipeline, I also reviewed team notebooks that I did not personally build, especially the broader EDA notebook. This helped me understand how DrugBank features connected with ChEMBL, SIDER, STITCH, BioBERT, JT-VAE, and GNN components.


## Why Only Some Team Files Are Included

Because CompoundIQ was group work, this portfolio does not upload every team notebook or every group presentation. Instead, it includes my DrugBank notebook, the Phase 2 presentation that I completed/organized, and written summaries of the other project phases.

This keeps the portfolio honest, professional, and focused on my individual contribution while still explaining the full context of the capstone project.

## Tools and Concepts Used

- Python
- Google Colab
- pandas / NumPy
- lxml XML parsing
- RDKit molecular data concepts
- NetworkX graph feature concepts
- scikit-learn train/validation/test split
- Parquet data storage
- Drug-drug interaction features
- CYP enzyme feature engineering
- Exploratory Data Analysis
