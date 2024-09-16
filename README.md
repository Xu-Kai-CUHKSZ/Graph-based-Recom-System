# Xu-Graph-based-Recom-System
This is my group project for DDA4210 Advanced Machine Learning

<p>

The canteen of the Lower Campus of CUHKSZ has a rich menu of dishes. So we want to design
a food recommendation system for CUHKSZ students based on our collected student-dish interaction
data.
To achieve this, we mainly face two problems.
1. How to efficiently capture the collaborative signals in the data?
2. Since our collected data is small, how to train a strong model while avoiding over-fitting?
For the 1st problem, we use the Neural Graph Collaborative Filtering (NGCF) model to capture
the collaborative signals in high-order connectivity of the interactive data (Wang et al., 2019) .
For the 2nd problem, we modify the negative sampler in training process to strengthen the model
and simplify the NGCF to avoid overfitting.
