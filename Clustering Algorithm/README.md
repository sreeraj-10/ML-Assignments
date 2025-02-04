# ML - Clustering   

## Objective
This project demonstrates **unsupervised machine learning** techniques using **KMeans Clustering** and **Hierarchical Clustering** on the **Iris dataset**. The purpose is to group similar data points without predefined labels and visualize the clustering results.  

## Dataset 
The Iris dataset from `sklearn.datasets` is used for the evaluation, which contains **150 samples** of iris flowers with **four features** each (sepal length, sepal width, petal length, petal width).  

### 1. Loading and Preprocessing
- Load the dataset from `sklearn.datasets`.
- Handle missing values and perform feature scaling.
- Explanation of preprocessing steps included.

### 2. **Clustering Techniques Implemented**  
a) **KMeans Clustering**  
   - KMeans is a centroid-based clustering algorithm that assigns data points to clusters based on proximity to centroids.  
   - This project applies KMeans with **3 clusters** (as there are 3 species of iris).  
   - The results are visualized using scatter plots.

#### * Scatterplot

  ![Image](https://github.com/user-attachments/assets/473cba8a-3b1f-49c0-ac37-d88e26c48dcb)

b) **Hierarchical Clustering**  
   - Hierarchical clustering creates a tree-like structure of nested clusters.  
   - This project applies **Agglomerative Clustering** with **3 clusters** using the Ward linkage method.  
   - A Scatterplot **dendrogram** is generated to visualize the hierarchical relationships between clusters.

     #### * Scatterplot
    
     ![Image](https://github.com/user-attachments/assets/c9f92354-d0df-465a-bf49-a6d14065cbfb)

     #### * Dendrogram
    
     ![Image](https://github.com/user-attachments/assets/6d466dd4-947b-449a-af8c-0300fd29795e)

## Results
- KMeans and Hierarchical Clustering successfully group the Iris dataset into three distinct clusters.
- The clustering results confirm that the dataset has natural groupings corresponding to different iris species.
  
## Requirements

### Tools
- Jupyter Notebook 

### Python Libraries
- pandas
- numpy
- matplotlib
- sklearn
- seaborn
- scipy

## How to Use
1. Clone this repository.
2. Open and run the project notebook.

## Conclusion
This project highlights the effectiveness of unsupervised learning in identifying patterns in data. Both KMeans and Hierarchical Clustering demonstrate that the Iris dataset has well-separated clusters, making it as the example for applying clustering algorithms.
