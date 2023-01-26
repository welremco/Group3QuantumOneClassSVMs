# Group3QuantumOneClassSVMs

This project is our first semester research project for the AI & DS masters at 
Maastricht University. It revolved around finding out whether quantum machine learning
methods would offer an advantage in the field of anomaly detection compared to classical methods.
The results of our research and experiments can be found in the [project report](Quantum_One_Class_Classification_Final_Report.pdf).

## Repository Overview

* Algorithm 1 and 2.ipynb contains our implementations 
of the One-Class SVM with Enhanced Feature Spaces as well as our
Variational Quantum One Class Classifier, including our artificial data generation and
our experiments with different hyperparameter settings.

* pennylaneLib-VQE-Dataset1.ipynb contains our implementation of a Variational Quantum Classifier.

* results/results.ipynb contains plots with our results from experiments on our artificial datasets.

* datasets is a pickle file with our artificial data, used in our Algorithm 1 and 2 notebooks.

* cern_data contains json files with data from the CERN ghost track reconstruction.

* cern_data_application.ipynb contains our experiments and result plots with the CERN ghost track data.

## Project Report Abstract

In this paper, we propose and evaluate three different quantum one-class classification (QOCC) algorithms for
anomaly detection and outlier detection. The first algorithm is
an One-Class Support Vector Machine (OC-SVM) with enhanced
feature spaces using a ZZFeatureMap, the second algorithm is a
Variational quantum one-class classifier, and the third algorithm
is a normal Variational quantum circuit. We evaluate the 
performance of the algorithms using the evaluation metric Macro
F1-score, since this gives us the best balance between correctly
identifying outliers and inliers. We also compare the results
with the classical one-class classification methods to highlight
the advantages of the proposed quantum one-class classification
methods. Our results show that the proposed QOCC algorithms
achieve a slight improvement in performance over the classical
methods in specific datasets, but generally seems to perform as
well or worse than classical methods. We also discuss the current
challenges and open problems and identify potential directions
for future research.


