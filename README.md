Book Reviews Similarity Analysis
Overview

This project focuses on identifying similarity across a large-scale corpus of book reviews using scalable and efficient techniques. The goal is to measure textual resemblance between reviews while avoiding the computational cost of exact pairwise comparisons.

To achieve this, the project applies Locality Sensitive Hashing (LSH) and MinHash to approximate Jaccard similarity, enabling efficient similarity detection over more than 3 million book reviews using distributed processing with PySpark.

Problem Statement

Comparing large volumes of text data using exact similarity measures is computationally expensive and impractical at scale. This project addresses the challenge by leveraging probabilistic hashing techniques that significantly reduce computation while preserving meaningful similarity signals.
