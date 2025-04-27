# Spectral Clustering-Based Analysis of ERC-721 Blockchain Transactions

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

## 📚 Overview

This project implements **Spectral Clustering** for both **Graphs** and **Hypergraphs** using synthetic and real-world datasets.  
For this major project, I have taken the **ERC-721 transaction dataset** for the **month of January 2020**. We analyze eigenvalues, perform clustering, and evaluate the quality using **Silhouette Score** and clustering metrics like **DB Index** and **Calinski-Harabasz Index (CH)**.

Additionally, it includes visualizations of eigenvalue spectra, clustered graphs, and a comparative analysis between Graph and Hypergraph clustering.

---

## 📒 Main Notebooks

- **`blockchain.ipynb`**: *Spectral Clustering on Blockchain Transaction Data*  
  This notebook focuses on applying spectral clustering techniques to analyze blockchain transaction data, specifically using the **ERC-721 dataset for January 2020**.
  - **Multiple Clusters Eigenvalue Spectrum on 1st Jan, 2020**: Analyze the eigenvalue spectrum of the graph representing transactions on January 1st, 2020.
  - **Clustering for all days of January 2020**: Perform clustering on the transaction data for every day in January 2020 to identify patterns and trends in the transactions.
  - **Calculation of Clustering Metrics**: Evaluate the quality of the clusters using standard clustering metrics such as:
    - **Silhouette Score**: Measure the cohesion and separation of the clusters.
    - **DB Index**: Assess the compactness and separation of the clusters.
    - **Calinski-Harabasz Index (CH)**: Evaluate the overall quality of the clustering solution.
  - **Hypergraph Clustering**: Apply hypergraph clustering to the ERC-721 transaction data, treating each token as a hyperedge.
  - **Comparison of Graph vs Hypergraph Clustering Methods**: Compare the results and performance of spectral clustering on traditional graphs versus hypergraphs.

- **`real_life_dataset.ipynb`**: *Hypergraph Clustering on Real-World Datasets*  
  This notebook explores the application of spectral clustering on a real-world dataset, demonstrating the technique on a **Dartboard.csv** dataset.
  - **Clustering on Real Life Dataset (Dartboard.csv)**: Apply hypergraph clustering to the Dartboard dataset to understand how clustering can be used in practical scenarios with real-world data.

- **`normal_spectral.ipynb`**: *Basic Graph Spectral Clustering Demonstration*  
  A foundational notebook that provides a simple introduction to spectral clustering on standard graphs.
  - **Spectral Clustering on Normal Graph**: Perform spectral clustering on a basic graph structure to understand the core principles of the method.
  - **Partitioning based on Different Eigenvalues**: Explore how different eigenvalues of the graph's Laplacian matrix influence the clustering results.
  - **Multiple Partitions**: Demonstrate the partitioning of a graph into multiple clusters based on spectral analysis.

- **`spectral_partition_Hypergraphs.ipynb`**: *Spectral Partitioning and Clustering for Hypergraphs*  
  This notebook delves into spectral partitioning and clustering specifically for **hypergraphs**.
  - **Spectral Clustering on Synthetic Hypergraph Dataset**: Apply spectral clustering on a synthetic hypergraph dataset to understand how the technique works in the context of hypergraphs.
  - **K Means vs Spectral Clustering**: Compare the results of spectral clustering with K-Means clustering to analyze the advantages and limitations of both methods when applied to hypergraphs.


---

## 📂 Folder Descriptions

- **clustering_graph**: Contains information about all the clusters formed using graphs on the ERC-721 dataset of January 2020, including:
  - The number of clusters formed with their size
  - The eigenvalue spectrum of the graph
  - The spectral clustered graph with visualizations.

- **clustering_hypergraph**: Contains all the data for clustering of hypergraphs using the ERC-721 transaction dataset. This includes:
  - The number of clusters formed with their size
  - The eigenvalue spectrum of the hypergraph
  - The spectral clustered graph with visualizations.

- **Hypergraph_Images**: Contains all the hypergraphs generated from the daywise transactions of the ERC-721 dataset, where each token is considered as a hyperedge.

- **Clustering_Metrics**: Includes the clustering metrics for both Graphs and Hypergraphs, including:
  - **Silhouette Score**
  - **DB Index**
  - **Calinski-Harabasz Index (CH)**

- **label_jan**: Contains the **ERC-721 transaction label dataset** for January 2020, used for labeling and evaluating the transaction data.

- **Research**: Contains all the research papers used during the project, which contributed to the methodology and understanding of spectral clustering on graphs and hypergraphs.

- **Presentation**: Contains the presentation slides for the project, detailing the methodology, results, and findings.

- **Report**: Contains the detailed report for the project, documenting the research, implementation, and analysis.

---

## 👨‍💻 Author

**Piyush Anand**  
Final Year B.Tech CSE Student  
📫 [LinkedIn](https://www.linkedin.com/in/piyush-anand-1915b0146/) | [GitHub](https://github.com/anandpiyush21)

Under the guidance of:
**Dr Prioduti Pradhan**
