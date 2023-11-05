## Identifying-HCP-and-their-specialization
# Team INTEL - Doceree ML HAckathon
This repo contains the submission file for Doceree ML Hackathon
The hackathon revolved around analyzing ad server logs, which contained critical information about user behavior, including browser details, IP addresses, geographic locations, search patterns, site URLs, and other relevant data. The main objective was to build a model that could accurately predict whether a user belonged to the HCP (Healthcare Professional) category and discern their specialization id/taxonomy, representing their specific area of expertise within the healthcare field.
-->As this being a classification problem we tried to use the best ML model- XGBoost
-->Firstly we dealt with the categorical datas- we used the XGBoost tree_method- GPU histogram for the purpose
-->We also defined a method for data cleaning and preprocessing for missing vales and '|' marks in 'KEYWORD' column.
-->The model gave 99% accuracy. 
-->Then we used onehot encoding to encode the categories in Taxonomy for prediction.
