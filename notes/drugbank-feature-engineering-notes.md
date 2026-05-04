# DrugBank Feature Engineering Notes

## Goal

The goal of the DrugBank pipeline was to convert raw drug records and interaction data into structured features that could support drug interaction analysis.

## Main Feature Groups

- Interaction count features: how many known interactions a drug appears in.
- CYP enzyme features: whether a drug is connected to CYP metabolism pathways.
- Metabolic complexity features: how much enzyme-related information exists for the drug.
- Safety complexity score: an interpretable score combining interaction and metabolic information.
- Active subset: drugs with interaction or CYP information, useful for model training and EDA.

## Why This Matters

Drug interaction data is sparse. Many drugs have little recorded interaction data, while a smaller group of commonly used or heavily studied drugs has many interaction records. This creates long-tail behavior, which is important to explain when preparing data for machine learning.
