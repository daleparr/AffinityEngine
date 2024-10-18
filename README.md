# AffinityEngine
Identifying product affinities and customer behavior insights.

# Product Affinity Insights & Predictions

## Overview
This project demonstrates product affinity discovery using the Apriori algorithm on an anonymized customer transaction dataset using circa 30,000 customer profiles. The goal is to uncover product affinities and predict future co-purchases, enabling more effective cross-sell and upsell strategies.

### Hypotheses
- **Hypothesis 1**: Identify strong co-purchase patterns between specific products.
- **Hypothesis 2**: Predict future product affinities for recent customers who have purchased key products.

## Methodology
Using the Apriori algorithm for market basket analysis. The dataset consists of anonymized customer transactions with columns such as:
- Sign-up date
- Last purchase date
- Total orders
- Country of origin
- Product purchases

The model generates association rules to identify product pairs frequently bought together.

## Results
- Casino has predictive value to trigger purchases of Racing Team, Patron, and Melrose.
- Cross-targeting recommendations for these products based on custom audience segmentation.

## Folder Structure
```plaintext
Product-Affinity-Insights/
│
├── data/
│   └── transactions.csv        # Anonymized dataset
│
├── notebooks/
│   └── apriori_analysis.ipynb   # Jupyter notebook with the Apriori implementation
│
├── outputs/
│   └── association_rules.csv    # Exported association rules
│
├── README.md                    # Project overview and documentation
│
├── requirements.txt             # Python dependencies
│
└── apriori_analysis.py          # Python script to run the Apriori analysis
