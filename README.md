# Generating and Evaluating Counterfactual Retrofit Explanations for Irish Homes 
Code accompanying the research project _Generating and Evaluating Counterfactual Retrofit Explanations for Irish Homes (TU Dublin, 2026)_. 

Predicts a dwelling's Building Energy Rating (BER) with XGBoost, explains predictions with SHAP, generates retrofit counterfactuals with DiCE, audits them against Keane et al.'s five deficits, and compares SHAP and DiCE against the ALTAI framework.

## Contents
- `ber_counterfactuals.ipynb` — Jupyter notebook containing the full pipeline (run from top to bottom)
- `requirements.txt` — pinned package versions if you want to run the notebook outside Google Colab (**note:** untested)

## Notes

1. **Data.** This repository does not redistribute the dataset - you can download it from the link provided in the notebook.