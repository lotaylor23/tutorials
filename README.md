# tutorials

## A Tutorial for Multiomics Data Integration using Graph Based Machine Learning

In recent years, the field of systems biology has made significant strides, driven by the explosion of multiomics data. Genomics, proteomics, transcriptomics, and metabolomics provide complementary insights into the molecular underpinnings of biology, but analyzing these data sets in isolation often limits our ability to uncover complex biological relationships. The true potential of multiomics lies in integrating these diverse data layers to create a holistic understanding of cellular and organismal processes.

However, integrating and analyzing multiomics data is no small task. The sheer volume, complexity, and heterogeneity of these datasets present unique challenges that require sophisticated computational approaches. In this session, we will delve into some of the most powerful techniques for tackling these challenges, including Non-negative Matrix Factorization (NMF), machine learning, and Graph Neural Networks (GNNs). These methods allow us to uncover hidden patterns and relationships across biological layers, which can lead to insights into disease mechanisms, drug responses, and the identification of novel biomarkers.

By applying these advanced tools to real-world multiomics datasets, this tutorial will not only enhance your computational skills but also provide a deeper understanding of how these techniques can be used to drive biological discoveries and improve clinical outcomes.

This repository provides a tutorial to introduce participants to the integration of multiomics data from genomics, proteomics, transcriptomics, and metabolomics, focusing on computational approaches to uncover hidden relationships between biological entities. It will cover techniques such as Non-negative Matrix Factorization (NMF), machine learning, and Graph Neural Networks (GNNs) to model multi-layered biological interactions and predict biological outcomes such as disease classification, drug responses, and biomarker discovery. Attendees will gain hands-on experience in processing and analyzing real-world multiomics datasets using open-source tools such as Python, pandas, scikit-learn.

### There are three code notebooks that will be used in this tutorial. Using these code notebooks we will cover:
1.	Non-negative Matrix Factorization (NMF)
2.	Machine Learning
3.	Graph Neural Networks (GNNs)

#### What is NMF?
Non-negative Matrix Factorization (NMF):
NMF is a matrix factorization technique that helps uncover hidden patterns in complex datasets by decomposing data into non-negative components. It is particularly useful in multiomics, where it can identify latent factors that represent biological processes shared across different layers of omic data. By applying NMF, we can reduce the dimensionality of multi-omics data, making it easier to analyze and visualize complex biological relationships.

#### Why Machine Learning?
Machine learning algorithms, such as classification, regression, and clustering methods, are essential tools for predictive modeling in multiomics research. These algorithms enable us to develop models that predict disease outcomes, classify disease subtypes, or assess responses to treatments based on large, high-dimensional biological data. By training models on integrated multiomics datasets, we can discover hidden patterns that may be overlooked using traditional statistical methods.

#### How can we apply GNNs?
GNNs are a powerful tool for modeling relationships and interactions in graph-structured data. In the context of multiomics, GNNs can model complex biological networks, where nodes represent biological entities (such as genes, proteins, metabolites) and edges represent interactions between them. GNNs can capture the intricate, non-linear relationships between molecular layers, improving our ability to predict biological outcomes like disease progression, drug efficacy, and biomarker identification.
