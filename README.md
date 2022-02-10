# masters_research_project
# Title
Data analysis approaches supporting efficient identification of principal components in time-series data. <br>
## Goal
Finding an optimal representative sample and most relevant features combination in time-series data.

## Abstract
In the field of data analysis, one of the most common scenarios is inaccurate detection due to the presence of noisy and redundant features in raw datasets. Theoretically, maximum accuracy should come from that model, which has obtained more information in the training phase. However, in practice, that hampers the efficiency of the machine learning model. For performing a model with an informative set optimal features resulting in less resource computation, the reduced curse of dimensionality effect and good expected predictor performance. If a representative sample can adequately describe the input information that will help to reduce the system memory consumption for training and to improve the system performance, etc. In this research work, we introduce a windows-based feature selection technique that characterizes important features. Additionally, we acquire the most favourable sample with enough information which minimize the training cost of the model. To achieve our goal; we use an algorithm that has built-in feature selection technology, namely “eXtreme Gradient Boosting (xgboost)”.  Later a rank correlation-coefficient has used to measure the degree of similarity and relationships between the most important features set of the whole dataset, and all of its possible windows.


## Used Technologies
Python, Java, Scikit-learn, Matplotlib, Xgboost, Decision Trees.
