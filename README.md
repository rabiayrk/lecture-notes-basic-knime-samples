# Lecture notes: basic machine learning with KNIME

KNIME workflows that compare basic machine learning algorithms on small datasets. Each folder has the workflow (`.knwf`) and the dataset it uses.

| Folder | Workflows | Dataset |
|---|---|---|
| Classification | Decision tree, KNN, logistic regression, naive Bayes, random forest, SVM | Iris |
| Clustering | k-means vs hierarchical clustering | Iris |
| Dimensionality Reduction | PCA followed by KNN | Iris |
| Regression | Linear, polynomial, decision tree, random forest | TSLA daily prices |

## Open a workflow

In KNIME Analytics Platform: File > Import KNIME Workflow, then select a `.knwf` file. The CSV file next to it is the input.

The TSLA price data came from Yahoo Finance in 2020. To try newer data, download it again from finance.yahoo.com and replace the CSV.

Written in 2020.
