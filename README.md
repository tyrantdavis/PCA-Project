# Magic Gamma - Principal Component Analysis

## Scenario
In this project, the task is to categorize particles as either gamma (signal) or hadrons (background). Since the features are multi-colinear, Principal Component Analysis (PCA) will be utilized  to derive a new set of features and identify those that hold the most significant information. The dataset used for this analysis was produced by a Monte Carlo simulation program called Corsika, as detailed in the work by D. Heck et al., titled "CORSIKA, A Monte Carlo code to simulate extensive air showers," published by Forschungszentrum Karlsruhe FZKA 6019 in 1998.

**Data Sources:**

- [Magic Gamma Dataset]("https://raw.githubusercontent.com/tyrantdavis/datasets/refs/heads/main/telescope.csv")
- [Original Dataset](http://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope.)

## Project Goals
The initial objective is to carry out PCA in order to generate a fresh set of features, focusing on selecting those that hold the most valuable information. The final objective is to statistically differentiate between images produced by primary gamma rays, which are classified as the signal (class label g), and those depicting hadronic showers triggered by cosmic rays in the upper atmosphere, categorized as the background (class label h). 

Several questions will be asked:

1. How many features does the PCA recommend as optimal?

2. When comparing the two SVG models, one utilizing PCA features and the other based on the original data features, which of the two demonstrates a greater accuracy score?



#### Why use a Principal Component Analysis to predict the classification?
In the realm of Machine Learning, the effectiveness of any model we create significantly increases when we tailor the features to align with the specific questions we aim to address. While it may be tempting to incorporate every available feature from various datasets to gain a comprehensive understanding of our observations, this approach can lead to challenges during data processing and model training due to computational constraints and complexity. The key lies in finding ways to utilize the correlations present in the data to distill it down to fewer, more impactful features while still retaining the essential information. 

Such a scenario presents an excellent opportunity to apply Principal Component Analysis (PCA). PCA is a powerful method that allows us to condense the number of features in a dataset while preserving the critical information contained within it. By leveraging PCA, we can simplify our models, making them more efficient and easier to interpret, all while ensuring that we do not sacrifice the richness of the data we are working with.


## Data
A dataset that can be used to train the machine-learning model has been found. It is a CSV file containing 19020 telescope records. 


## Conclusions
TBD...

1. How many features does the PCA recommend as optimal?

2. When comparing the two SVG models, one utilizing PCA features and the other based on the original data features, which of the two demonstrates a greater accuracy score?