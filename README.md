# Machine-Learning
Machine Learning (ML) is a sub‑field of Artificial Intelligence (AI) that focuses on creating computer systems able to learn from data, adapt to new information, and make decisions or predictions with minimal human intervention. At its core, ML is about discovering patterns, relationships, or structures in data and encoding them in mathematical models that generalize beyond the examples they were trained on.

## Fundamental Concept
**1. Learning From Data**
  Instead of being explicitly programmed with task‑specific rules, an ML algorithm ingests historical data (the training set) and infers a mapping from inputs 𝑋 to outputs     𝑌. Once trained, the model can process previously unseen inputs and output useful predictions or decisions.<br>
**2. Generalization**
  The hallmark of successful ML is generalization—performing well on new, unseen data. Techniques such as cross‑validation, regularization, and careful feature engineering     help ensure the model captures true signal rather than noise (overfitting).

## Types of Machine Learning
| Category                          | Goal                                                                                    | Typical Algorithms                                          | Example Use‑Cases                                   |
| --------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------------------------------------- | --------------------------------------------------- |
| **Supervised Learning**           | Learn a mapping $f: X \rightarrow Y$ from labeled data                                  | Linear/Logistic Regression, SVM, Random Forest, Neural Nets | Email spam detection, house‑price prediction        |
| **Unsupervised Learning**         | Discover hidden structure in unlabeled data                                             | K‑Means, Hierarchical Clustering, PCA, Autoencoders         | Customer segmentation, topic modeling               |
| **Semi‑Supervised Learning**      | Combine a small amount of labeled data with large unlabeled data                        | Self‑training, graph‑based methods                          | Medical image classification with scarce labels     |
| **Reinforcement Learning**        | Learn a policy that maximizes cumulative reward through interaction with an environment | Q‑Learning, Deep Q‑Networks, Policy Gradients               | Game playing (AlphaGo), robotics control            |
| **Self‑Supervised Learning**      | Create labels from the data itself to pretrain models                                   | Contrastive Learning, Masked‑Language Modeling              | Pre‑training large language models, vision encoders |
| **Online & Incremental Learning** | Update model continuously as data streams in                                            | Stochastic Gradient Descent, Hoeffding Trees                | Real‑time recommendation engines, stock trading     |


## Core Workflow<br>
**Problem Definition**<br>
  Clarify business or research objectives, the nature of inputs and desired outputs, and acceptable error tolerance.

**Data Collection & Integration**<br>
  Gather data from databases, APIs, sensors, or user logs. Ensure sufficient quantity, variety, and relevance.

**Data Pre‑processing / EDA**<br>
  Handle missing values, outliers, anomalies<br>
  Encode categorical variables, scale/normalize numerics<br>
  Visualize distributions, correlations, time trends

**Feature Engineering**<br>
  Transform raw inputs into informative representations (e.g., TF‑IDF for text, polynomial features, domain‑specific ratios).

**Model Selection**<br>
  Choose algorithms based on data size, feature types, interpretability needs, latency constraints, etc.

**Training**<br>
  Optimize model parameters using techniques such as Gradient Descent or Bayesian estimation.

**Validation & Hyperparameter Tuning**<br>
  Use hold‑out sets or k‑fold cross‑validation; employ grid/random/bayesian search to fine‑tune hyperparameters.

**Evaluation**<br>
  Metrics vary by task: accuracy, F1, ROC‑AUC for classification; RMSE, MAE for regression; Silhouette score for clustering; cumulative reward for RL.

**Deployment**<br>
  Wrap the model in APIs, micro‑services, mobile apps, or embedded firmware. Monitor latency, throughput, resource usage.

**Monitoring & Maintenance**<br>
  Track data drift, concept drift, model performance decay, and trigger retraining or rollback when necessary.

## Representative Algorithms
| Family                       | Example Algorithm                | High‑Level Idea                                                          |
| ---------------------------- | -------------------------------- | ------------------------------------------------------------------------ |
| **Linear Models**            | Linear/Logistic Regression       | Fit a straight‑line/decision boundary; interpretable                     |
| **Distance‑Based**           | KNN, K‑Means                     | Rely on similarity measures in feature space                             |
| **Tree‑Based Ensembles**     | Random Forest, Gradient Boosting | Combine many decision trees for robustness                               |
| **Kernel Methods**           | Support Vector Machines          | Map data to higher dimensions for linear separation                      |
| **Probabilistic Models**     | Naive Bayes, HMM                 | Model underlying probability distributions                               |
| **Neural Networks**          | MLP, CNN, RNN, Transformers      | Stack layers of nonlinear transformations to learn hierarchical features |
| **Evolutionary / Heuristic** | Genetic Algorithms, PSO          | Search parameter space via bio‑inspired operations                       |


## Common Application Domains
| Domain                  | ML Tasks                                  | Real‑World Examples                               |
| ----------------------- | ----------------------------------------- | ------------------------------------------------- |
| **Vision**              | Classification, detection, segmentation   | Medical imaging diagnostics, autonomous driving   |
| **Natural Language**    | Translation, sentiment, QA, summarization | Chatbots, document analysis                       |
| **Time Series**         | Forecasting, anomaly detection            | Energy demand prediction, predictive maintenance  |
| **Finance**             | Risk scoring, fraud detection             | Credit approval, anti‑money laundering            |
| **Healthcare**          | Diagnosis, drug discovery                 | Cancer detection, protein folding (AlphaFold)     |
| **Recommender Systems** | Ranking, collaborative filtering          | Streaming platform suggestions, e‑commerce upsell |


## List of Experiments: 
0. Exploratory data analysis (EDA)
1. Principal Component Analysis (PCA)
2. K nearest neighbors (KNN)
3. Linear discriminant analysis (LDA)
4. Linear Regression (LR)
5. Logistic Regression (LogReg)
6. Naive Bayes
7. Support Vector Regressor (SVM)
8. Feed Forward Neural Network (FF-NN)
9. Convolution Neural Network (CNN)
10. Hidden Markov Model (HMM)
