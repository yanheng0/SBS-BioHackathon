# PCOS Phenotype Navigator 
**Hackathon Solution: Bridging the gap in PCOS misdiagnosis in women's health**

## Inspiration
**Misdiagnosis in PCOS remained prevalent which stems from PCOS's heterogeneity, the absence of a single diagnostic test (overlapping symptoms with endometriosis) and persistent misconceptions among clinicians regarding PCOS**

## What it does
**Utilises a machine learning tool split into 3 tiers to identify PCOS driving fields:**\
**Tier 1: Logistic Regression for basic GP testing**\
**Tier 2: Random Forest Classifier for PCOS specialist**\ 
**Differential Diagnosis: XGBoost to distinguish PCOS from endometriosis**\ 

## How we build it
**Language/tool:** Python, Jupyter Notebook\ 
**Data:** 'PCOS_data_without_infertility.xlsx' and '_structured_endometriosis_data.csv' for model training\ 
**Libraries:** Pandas, Numpy, Matplotlib, Scikit-learn
