# Diamonds Data Exploration

## Dataset

The data consists of information regarding a dataset containing prosper loans and attributes for approximately 113,937 loans made to its clients, including Prosper Rating (Alpha), Prosper and credit scores, estimated loss, and other features. The dataset can be found in [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000), with feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000
).

## Summary of Findings

In the exploration, only loans made after July 2009 were included since the Prosper Rating (Alpha) was implemented after April 2009.I found that there was a strong relationship between the prosper rating (alpha) for a client and its estimated loss, with modifying effects from the prosper score and credit scores assigned to the borrower. The relationship is approximately linear between prosper score and credit score when they are all transformed to be on a logarithmic scale and with certain axes limits. I found surprising result indicated that low prosper rated loan was associated with high estimated loss. Also that estimated loss is assocated with high credit and prosper scores.

Outside of the main variables of interest, I verified the relationship between loan prosper rating and its borrower's home ownership and employment status , Stated Monthly Income and Debt to Income (DTI) ratio dimensions. For the dataset given, there was an interesting interaction in the categorical prosper
features. It was interesting to find that high stated monthly income borrower with low DT1 and own a home, was associated with high prosper rating.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the prosper and credit scores and estimated loss, of prosper clients and leave out most of the intermediate derivations. I started by introducing the prosper rating (alpha) variable together with the distributions of categorical features of the prosper dataset. This was followed by discovering pattern in prosper and credit scores, monthly stated income and DTI ratio distribution, then plot the transformed scatterplot.

Afterwards, I used correlation plot for numerical variables to discover correlation between prosper rating and other numeric features. Here, my special focus was on the relationship between prosper rating and estimated loss, prosper and credit scores. The other two categorical variables, employment and home ownership staus, are covered afterwards, using point, count and scatter and box plots. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
