# Movie Plot Similarity Analysis

## Overview

This project explores the fascinating world of movie similarity analysis using natural language processing (NLP) and unsupervised learning techniques. Our goal is to quantify the similarity of movies based on their plot summaries and group them into clusters. This analysis can unlock insights into the relationships between movies and pave the way for advanced recommendation systems.

## Project Structure

1. **Data Collection**: We begin by importing a dataset containing movie plot summaries from both IMDb and Wikipedia. The dataset is merged into a single source for consistency.

2. **Tokenization and Stemming**: We break down the text into sentences and words while reducing words to their root form, making it more suitable for analysis.

3. **TF-IDF Vectorization**: The textual data is transformed into numerical format using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. This allows us to analyze movie plot summaries mathematically.

4. **K-Means Clustering**: K-Means clustering is applied to group movies based on their plot summaries. This clustering method helps us organize movies into clusters based on content similarities.

5. **Similarity Distance**: Cosine similarity is used to measure the similarity distance between movie plot summaries. It provides a nuanced view of the relationships between movies beyond traditional clustering.

6. **Dendrogram Visualization**: Dendrograms are constructed to visualize the similarity levels between movie titles. This unique approach complements the clustering results.

## Key Insights

The dendrogram visualization allows us to:

- Set Thresholds: We can determine clusters by setting a similarity threshold. Movies with similarity values above this threshold can be grouped together, offering recommendations or in-depth cluster analysis.

- Explore Hierarchy: By examining different branches and heights on the dendrogram, we gain insights into the hierarchical structure of clusters, understanding how movies are connected at various similarity levels.

- Refine Recommendations: Dendrograms provide valuable insights for improving recommendation systems, enhancing user experiences by suggesting movies based on their similarity to other films within the same cluster.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary Python libraries, including nltk, pandas, scikit-learn, and matplotlib.
3. Open the Jupyter Notebook or Python script provided to execute the analysis.
4. Explore and adapt the code to your specific needs and preferences.

## Comments and Customization
Throughout the project, I've added comments and explanations to enhance understanding and serve as a learning exercise. Feel free to explore the Jupyter Notebook for detailed code implementation.
