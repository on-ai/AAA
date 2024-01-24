# Marketing-AAA NorthEast
## Overview
### Goal
The goal of this project is to provide market segmentation of AAA Northeast members that would help increase the penetration of AAA's financial products.

### Methodology
- **Predictive Analysis**: Classification model helps predict the probability of purchasing each product. The predicted probabilities are latter used for clustering. 

- **Clustering**: Clustering helps explore market segmentation and opportunities.

### Challenges
- **Unbalanced Data**: Most products have low penetration. Therefore, it creates unbalanced data when building classification models. To counter this issue, up-sampling is used in modeling process.

- **Model Improvement - AUC**: Several classification and ensemble models were applied to select best model. The best model and technique are identified in this project.

### Results
- The prediction performance is evaluated via the **AUC** value, on test set across most products. The high AUCs gives confidence to use the predicted probabilities of purchasing for clustering. 
- An ideal number of clustering is identified to **provide actionable recommendations and product strategy**. AAA could reduce its costs, and advertize their Credit Cards and Mortgage offers.

