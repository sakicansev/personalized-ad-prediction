# Personalized Ad Display — Machine Learning Approach

## Overview
A machine learning study exploring how customer cookie data can be used to 
predict the most relevant advertisement category for each user.
Built as part of the MSc Data Analytics program at the University for the Creative Arts.

**Tools:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn  
**Algorithms:** Decision Trees, Random Forest (Multiclass Classification)  
**Paper:** See `Saki_Cansev_-_Q1050645.pdf` for the full academic write-up

## Problem Statement
Given customer behavioural data (browsing duration, visit frequency, 
shopping habits, device type), predict which of 5 ad categories a user 
is most likely to engage with: Sports, Cinematic, Artistic, Technology, or Fashion.

## Approach
- Data preprocessing: normalization, one-hot encoding of categorical variables
- Algorithm comparison: Decision Trees vs Random Forest
- Model evaluation across 5 criteria: accuracy, robustness, speed, 
  interpretability, and scalability
- Random Forest selected for its balance of accuracy and resistance to overfitting

## Key Results
- Random Forest achieved 50% accuracy on a small 10-row dataset
- Decision Tree visualizations produced for all 5 ad categories
- Low robustness score (0.083) acknowledged — attributed to very small dataset size

## Files
- `fina.ipynb` — Python implementation notebook
- `Saki_Cansev_-_Q1050645.pdf` — full academic paper with methodology and findings
