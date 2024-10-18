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
- 
- Cross sell opportunity using custom audiences in Bottom of Funnel.

By leveraging these custom audiences, we can implement cross-targeting strategies in the Bottom of Funnel (BOF) to drive engagement and conversions. 
This allows us to focus marketing efforts on users who show affinities for products like Casino, Racing Team, Patron, and Melrose, enhancing personalization and improving cross-sell opportunities.
