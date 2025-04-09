# ISCB-Africa ASBCB 2025

**Venue:** Lagoon Beach Hotel & Conference Center, Cape Town, South Africa

**Website:** https://www.iscb.org/africa2025/home

**Date of the session:** April 10, 2025 12:00-16:00 SAST

**Instructors/Affiliation:** 
Loni Taylor, Meharry Medical College, Nashville, TN, USA.
Bishnu Sarker, Meharry Medical College, Nashville, TN, USA.
Animesh Acharjee, University of Birmingham, UK.

# 2. Key Computational Approaches for Multiomics Integration

## Overview:
Integrating multiple omics datasets (such as genomics, transcriptomics, proteomics, metabolomics, etc.) is crucial in systems biology to achieve a holistic understanding of biological processes.  Some key computational approaches for multiomics integration can include Preprocessing, Network-based, Machine learning, or Dimensionality reduction approaches.

This section will provide an overview of selected key computational techniques used to integrate multiomics data. It will focus on the methods that allow researchers to extract meaningful insights from large, heterogeneous datasets, such as Non-negative Matrix Factorization (NMF), machine learning, and Graph Neural Networks (GNNs).

In this session, we will focus on understanding and applying key computational techniques for integrating and analyzing multiomics data. Together, these approaches allow us to gain deeper insights from multiomics data, revealing complex biological relationships that would be difficult to detect through traditional methods. Understanding these computational tools will empower you to unlock the full potential of multiomics in disease research and personalized medicine.

## Topics:
+	Overview of computational challenges in multiomics integration
+	Introduction to Non-negative Matrix Factorization (NMF)
+	Machine learning techniques for multiomics data
+	Graph Neural Networks (GNNs) and their applications in biology

### 1.	Overview of Computational Challenges:
+	**Data Heterogeneity:** Different omics layers may be measured in different ways, using different technologies, leading to inconsistent formats and structures.
+	**Scalability:** Multiomics datasets are often large and require scalable computational methods that can handle large volumes of data efficiently.
+	**Data Fusion:** The challenge of combining different omics data types (such as genomics and proteomics) to extract meaningful insights while retaining their individual contributions.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIkgbucYXs49czJD6hoCmp6Ozbxzqc2D1WXQ&s" alt="data heterogeneity" width="400" height="200">
Data Heterogeneity: <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSIkgbucYXs49czJD6hoCmp6Ozbxzqc2D1WXQ&s">Kemp, Jessica & Kwon, Young Jik. (2021). Cancer nanotechnology: current status and perspectives. Nano Convergence. 8. 10.1186/s40580-021-00282-7. </a>

### 2.	Non-negative Matrix Factorization (NMF):
+	**What is NMF?** <br>Non-negative Matrix Factorization is a dimensionality reduction technique that factorizes a matrix into two lower-dimensional matrices with non-negative entries. It is particularly useful for extracting latent features from data, where the underlying factors are assumed to be non-negative (i.e., all data points are positive or zero).

+	**Why NMF for Multiomics?** <br>NMF helps identify hidden factors (e.g., gene expression profiles, protein interactions) that can explain the observed data. It’s useful for reducing the complexity of multiomics data and identifying key biological components or patterns.

+	**Applications:** <br>NMF has been used to identify gene expression patterns associated with disease, protein complexes in cellular networks, and metabolic pathways in diseases.

### 3.	Machine Learning for Multiomics:
+	**What is Machine Learning?** <br>Machine learning refers to a set of algorithms that learn patterns in data without explicit programming. In the context of multiomics, machine learning algorithms (like classification models, regression, clustering, etc.) can help predict biological outcomes (e.g., disease, drug response) by learning from integrated data.

+ **Why Machine Learning?** <br>Machine learning algorithms, such as classification, regression, and clustering methods, are essential tools for predictive modeling in multiomics research. These algorithms enable us to develop models that predict disease outcomes, classify disease subtypes, or assess responses to treatments based on large, high-dimensional biological data. By training models on integrated multiomics datasets, we can discover hidden patterns that may be overlooked using traditional statistical methods.

+	**Applications in Multiomics:** <br>Machine learning techniques can be used for predictive modeling (e.g., disease classification), clustering omics data to find subtypes of diseases, and discovering biomarkers associated with specific conditions.

+	**Challenges:** <br>Machine learning models for multiomics data face challenges like overfitting (due to high dimensionality) and interpretability (understanding why the model made a particular decision).

<img src="https://github.com/lotaylor23/tutorials/blob/main/Multiomics%20Data%20Integration%20using%20Graph%20Based%20Machine%20Learning/Images/ML.png" alt="MACHINE LEARNING">
Machine learning modified from: <a href="https://www.turing.com/kb/ultimate-battle-between-deep-learning-and-machine-learning">Deep Learning vs Machine Learning: The Ultimate Battle</a>

### 4.	Graph Neural Networks (GNNs):
+	**What are GNNs?** <br>Graph Neural Networks are a type of neural network designed to work with graph-structured data, where nodes represent entities (e.g., genes, proteins, metabolites) and edges represent relationships (e.g., protein-protein interactions, gene regulatory networks).

+	**Why GNNs for Multiomics?** <br>GNNs are excellent at capturing relationships and interactions between biological entities across different omics layers. They can model complex biological networks and help predict outcomes such as disease progression, drug efficacy, and interactions between genes and proteins.

+	**Applications:** <br>GNNs have been used in drug discovery, predicting drug-target interactions, and understanding how different molecular entities interact within a biological system.

### 5.	Integrated Approaches Using NMF, Machine Learning, and GNNs:
+	**Combining Approaches:** <br>In multiomics data analysis, a hybrid approach that combines NMF for dimensionality reduction, machine learning for prediction, and GNNs for modeling biological networks can provide a powerful tool for comprehensive analysis.

+	**Use Case Example:** <br>A system that integrates genomic data with proteomics and metabolomics using NMF for feature extraction, machine learning for predictive modeling, and GNNs to predict the impact of specific gene mutations on disease progression.

### 6.	Conclusion:
+	Integrating multiomics data requires sophisticated computational methods to handle the complexity, scale, and diversity of data types. Techniques like NMF, machine learning, and GNNs are instrumental in transforming raw data into actionable biological insights.


