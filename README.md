# LAG-HWs

This repo contains a set of homework during the a.y. 23/24 for the course of [Computational linear algebra for large scale problems](https://didattica.polito.it/pls/portal30/gap.pkg_guide.viewGap?p_cod_ins=02TWYSM&p_a_acc=2024&p_header=S&p_lang=&multi=N) at PoliTo University.

### Homework 1: PCA
Involves conducting a Principal Components Analysis (PCA) on a dataset of customer information to explore spending habits and family status. Students are tasked with reducing dataset dimensionality using PCA, identifying customer clusters with the k-Means algorithm, and interpreting these clusters. The homework includes exercises on data preparation, encoding, PCA application, dimensionality reduction, k-Means clustering, and cluster interpretation. Submission requires a Jupyter notebook report and its PDF version, detailing the problem, procedures, and results, emphasizing code integration, analysis, and justification of choices made during the exercises.

### Homework 2: Google PageRank Algorithm
The homework is based on the article "The $25,000,000,000 Eigenvector: The Linear Algebra Behind Google" by Kurt Bryan and Tanya Leise. This assignment explores the mathematical concepts behind Google's PageRank algorithm, focusing on how Google uses linear algebra to rank the importance of web pages. The homework involves understanding the construction and analysis of the PageRank matrix, dealing with challenges such as dangling nodes and non-unique rankings, and applying modifications to ensure unique, sensible rankings. Exercises include theoretical questions and practical tasks involving the computation of PageRank using given or constructed link matrices. This project offers a deep dive into applied linear algebra, emphasizing its real-world application in search engine technology.

### Homework 3: Image Compression Benchmarking and Eigenvalues Approximation (Notebook is not shared due to privacy&policy constraints)
The goal is to explore and implement various image compression techniques, focusing on Singular Value Decomposition (SVD), Principal Component Analysis (PCA), and k-means clustering. The assignment is divided into several key sections, each with its objectives and requirements:

Introduction and Setup: Students are introduced to the necessary libraries and configurations for the assignment, including numpy, pandas, matplotlib, cv2, and sklearn. This section sets the groundwork for implementing the compression algorithms and evaluating their performance.

Function Definitions: Essential functions for computing absolute loss, Peak Signal-to-Noise Ratio (PSNR), and Structural Similarity Index (SSIM) are provided. These functions are crucial for analyzing the quality of compressed images in comparison to their original versions.

Test Images Selection: A variety of images are selected for testing the compression algorithms. These images include landmarks, nature scenes, and personal photos to ensure a diverse set of data for compression and analysis.

Singular Value Decomposition (SVD) Image Compression: This section delves into using SVD for compressing grayscale and RGB images. Students are expected to understand and implement the SVD technique, explore its effectiveness for image compression, and evaluate the quality of compression using the defined metrics.

Principal Component Analysis (PCA) Image Compression: Similar to the SVD section, PCA is used for compressing images. Students must apply PCA to both grayscale and RGB images, analyze the compression performance, and compare it against SVD in terms of quality and computational efficiency.

K-Means Clustering for Image Compression: Although not traditionally used for image compression, k-means clustering is explored as a potential method for this purpose. Students are to implement k-means clustering for image compression and assess its viability and performance compared to SVD and PCA.

Evaluation and Comparison: The assignment culminates in a comprehensive evaluation of the three techniques—SVD, PCA, and k-means clustering. Students are required to compare these methods based on compression ratio, image quality (using PSNR and SSIM), and computational efficiency. The comparison should highlight the strengths and limitations of each method and offer insights into their practical applications for image compression.
