# Machine Learning & Clustering Analysis
This repository contains Teachable Machine models mapped to specific clustering concepts as part of my AIML coursework.

## 🎙️ Problem 2: Environmental Sound Complexity
**Model:** [Link to problem2.html]
- **Analysis:** Focused on **DBSCAN (Density-Based Clustering)**. 
- **Finding:** Introducing background noise simulates "Outliers/Noise" in a density-based algorithm. Overlapping sounds (e.g., clapping + fan) create boundary points that challenge the model’s ability to define high-density clusters.

## 🧘 Problem 3: Human Activity Recognition
**Model:** [Pending - problem3.html]
- **Analysis:** Focused on **Hierarchical Clustering**.
- **Finding:** Ambiguous poses like "half-standing" represent intermediate nodes in a dendrogram. Activities like sitting and leaning share more features and would cluster closer together than walking.

## 📱 Problem 4: Object Similarity
**Model:** [Pending - problem4.html]
- **Analysis:** Focused on **K-Means Clustering**.
- **Finding:** Visually similar objects like remotes and phones have feature vectors with low Euclidean distance, leading to centroid confusion and cluster overlap.
