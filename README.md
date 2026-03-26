# Machine-Learning-Project-
This repository contains a Machine Learning project developed during the first year of my Master’s degree in Computer Engineering. It focuses on applying fundamental ML techniques and concepts studied throughout the course, including data processing, model training, and evaluation.

°Aim of the project
2.4 Track T4 – Semi-Supervised Learning (SSL)

Semi-supervised learning (SSL) is a machine learning paradigm that lies between supervised and unsupervised learning, and it leverages both a small set of labeled data and a larger amount of unlabeled data.

This approach is particularly useful in contexts where labeling data is expensive or requires specialized expertise, while data collection is relatively easy.

The objective of the project is to study and apply semi-supervised learning techniques to tabular data, analyzing how the limited availability of labels affects the performance of predictive models. Students are required to design a pipeline that combines labeled and unlabeled data, comparing purely supervised approaches with semi-supervised techniques, and discussing the benefits and limitations of each solution in realistic scenarios.

Students may apply one or more SSL techniques of their choice (e.g., unsupervised pre-training, self-training, label propagation). More information can be found at the following links:
https://scikit-learn.org/stable/modules/semi_supervised.html
,
https://arxiv.org/pdf/2006.05278
.

Students may consider a classification task of their choice, either among those mentioned in other tracks or starting from a dataset available on the UCI ML Repository (https://archive.ics.uci.edu/
). Starting from the original fully labeled dataset, labels must be partially removed to simulate a semi-supervised scenario, keeping only a fraction (between 1% and 10%) of the labeled data.

Semi-supervised learning techniques must then be applied to this new dataset and compared with supervised models trained exclusively on the labeled portion, evaluating the final performance using the full set of labels kept aside for evaluation.
