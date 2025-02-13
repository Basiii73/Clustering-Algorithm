# Iris Dataset Clustering

## Objective
The objective of this project is to apply clustering techniques on the Iris dataset to identify natural groupings of data points. The assessment evaluates the implementation and understanding of two clustering algorithms: KMeans and Hierarchical Clustering.

## Dataset
We use the **Iris dataset** from the `sklearn` library, which consists of:
- 150 samples
- 4 features (Sepal Length, Sepal Width, Petal Length, Petal Width)
- No predefined labels used (since it's a clustering problem)

## Project Components

### 1. Loading and Preprocessing
- Load the Iris dataset from `sklearn.datasets`.
- Drop the species column as clustering is an unsupervised learning technique.
- Standardize the data using `StandardScaler`.

### 2. Clustering Algorithm Implementation
#### A) KMeans Clustering
- **Description**: Partitions data into K clusters by minimizing intra-cluster variance.
- **Why suitable for Iris dataset?**
  - The dataset is well-separated and relatively small.
  - KMeans performs well when clusters are roughly spherical.
- **Implementation**:
  - Use `KMeans` from `sklearn.cluster` with 3 clusters.
  - Visualize the clustering results using a scatter plot.

#### B) Hierarchical Clustering
- **Description**: Builds a hierarchy of clusters using a bottom-up approach.
- **Why suitable for Iris dataset?**
  - No need to predefine the number of clusters.
  - Provides a dendrogram to visualize the cluster structure.
- **Implementation**:
  - Use `AgglomerativeClustering` with 3 clusters.
  - Generate a dendrogram to illustrate hierarchical clustering.

## Results
- Clustering results are visualized using scatter plots.
- A dendrogram is plotted to analyze hierarchical clustering.

## Submission Guidelines
- The code is provided in a Jupyter Notebook format.
- Ensure explanations are clear and concise.
- Submit the GitHub repository link with the notebook.

## Dependencies
- Python 3.x
- `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `scipy`

## Usage
1. Clone the repository:
   ```bash
   git clone <repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook.

## Author
- Abdul Basith


