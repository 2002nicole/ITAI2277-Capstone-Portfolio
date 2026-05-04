# Applied AI Skills Learned

## Data Preparation for AI

I learned how important data preparation is before model training. For CompoundIQ, the raw DrugBank data was large and nested, so the work involved parsing, cleaning, reducing duplication, and turning raw records into features that a model could actually use.

## Feature Engineering

I practiced creating features that connect to the project goal. Instead of using generic columns only, I created interaction counts, CYP-related features, metabolic complexity features, and a safety complexity score.

## Model Pipeline Thinking

I learned how one person's data pipeline can support another person's model. In CompoundIQ, DrugBank features were not the final model by themselves, but they helped provide safety and interaction context for the GNN component.

## Responsible AI

Drug discovery and drug interaction prediction are high-stakes areas. I learned to describe AI outputs as research support, not medical advice, and to be clear about limitations, validation needs, and human review.
