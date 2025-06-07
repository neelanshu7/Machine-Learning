Definition:<br>
A simple, non-parametric algorithm used for classification and regression. It predicts the label based on the majority vote (or average) of its k closest neighbors in the training data.

Steps:<br>
Choose the number of neighbors (k)<br>
Compute distances between the query and training points<br>
Predict based on the nearest neighbors<br>

Pros: Intuitive, no training phase.<br>
Cons: Slow for large datasets, sensitive to irrelevant features.
