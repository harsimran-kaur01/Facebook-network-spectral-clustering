# 📘 Spectral Clustering using Eigenvalues and Eigenvectors
# Facebook Network Analysis Project
# Application of Eigenvalues and Eigenvectors for Data Clustering using Facebook Network
# Objective: To apply spectral clustering using eigenvalues and eigenvectors to detect communities in a Facebook social network graph.
# Introduction
```
Social networks like Facebook are represented as graphs:
- Nodes → users
- Edges → friendships

Spectral clustering is used to identify hidden patterns in graph data using linear algebra concepts.
```
# Graph Representation
```
Adjacency Matrix (A)
Degree Matrix (D)
Graph Laplacian: L = D - A
```
# Eigenvalues & Eigenvectors
``` 
Eigenvalues and eigenvectors of the Laplacian matrix help reduce dimensionality and capture graph structure.
```
# Spectral Clustering Steps
```
1. Construct graph from dataset
2. Build adjacency matrix
3. Compute Laplacian matrix
4. Perform eigen decomposition
5. Select top k eigenvectors
6. Apply K-Means clustering
7. Visualize clusters
```
# Technologies Used
```
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- NetworkX
- Google Colab
```
# Dataset
```
Facebook social network graph dataset:
- Nodes represent users
- Edges represent connections between users
```
# Workflow
```
Step 1: Load dataset
Step 2: Build adjacency matrix
Step 3: Compute Laplacian matrix
Step 4: Perform eigen decomposition
Step 5: Select eigenvectors
Step 6: Apply K-Means clustering
Step 7: Visualize results
```
# Results
```
- Users are grouped into meaningful communities
- Strong connections appear within clusters
- Graph structure is preserved using spectral methods
```
# Applications
```
- Social network analysis
- Community detection
- Recommendation systems
- Fraud detection
- Link prediction
```
# Conclusion
```
Spectral clustering using eigenvalues and eigenvectors is an effective method for analyzing graph-based datasets like Facebook networks.
```
