# Clustering-and-data-visualization
This practical assignment (TP) aims to analyze a dataset related to sentiments expressed by Twitter users during the COVID-19 pandemic (2020-2021).
The dataset includes five emotional features extracted from tweets:  
- `valence_intensity` (valence),  
- `fear_intensity` (fear),  
- `anger_intensity` (anger),  
- `happiness_intensity` (happiness),  
- `sadness_intensity` (sadness).  

Each tweet is labeled with a sentiment: **negative (-1)**, **neutral (0)**, or **positive (1)**. The main objective is to explore whether these features can characterize the three sentiment trends using clustering techniques.

## Tasks to Complete

1. **Comparative Analysis of Features**  
   - Generate 10 figures showing the joint distributions of feature pairs.  
   - Provide visual interpretations of how these features relate to sentiments.  

2. **Clustering with K-means**  
   - Determine the optimal number of clusters (`K`) using:  
     - The Overlap criterion (from TP1).  
     - The Silhouette score.  
   - Evaluate results for `K=3` and the optimal values found using the metrics: **Precision**, **Recall**, and **F1-score**.  

3. **Hierarchical Clustering**  
   - Implement an agglomerative or divisive approach with Euclidean distance.  
   - Determine the number of clusters via intuitive or automatic thresholds.  
   - Generate and analyze dendrograms.  
   - Evaluate the obtained clusters (except for `K=3`) using the same metrics.  

4. **Evaluation for `K=3` (Hierarchical Clustering)**  
   - Compare performance with K-means results.  
