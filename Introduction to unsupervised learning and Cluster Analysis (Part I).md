![[T2_2023_students.pdf]]

## Notes
### Unsupervised Learning
- **Unsupervised learning**: *try to find hidden structure in unlabeled data*
- **Goals**
	- *Summarization*: representation of unlabeled data
	- *Understading*: discover key concepts in the data
- **Considerations**: 
	- Biased by context
	- Few criterion to validate results
- **Representations of the clusters**
	- Relational (hierarchies)
	- Unstructured (partitions)
- **Tasks**
	- *Clustering*: grouping similar objects and distantiate those with more difference according a selected criteria.
		- *Based on connectivity* (hierarchical clustering)
		- *Based on centroids* (K-means)
		- *Distribution-based* models (expectation maximization)
		- Density models
		- Subspace models
		- Graph based models
	- *Factor analysis*: statistics to describe variablity among observed, correlated variables.
		- *Feature extraction* for *dimensionality reduction*.
			- Principal Component Analysis (PCA)
			- Independent Component Analysis (ICA)
			- Singular Value Decomposition (SVD)
	- *Visualization*: Study of visual representations of abstract data.
		- Explore similarities and dissimilarities in data
			- NN models:
				- Self-organized maps (SOM)
				- Adaptative resonance theory (ART)
			- Multi-dimensional scaling
				- Classical
				- Metric
				- Non-metric
				- Generalized
### Cluster Analysis
- **Definitions**
	- Assigning a set of *unlabelled objects* into groups (clusters) so that the objects in the *same cluster* are very *similar* (in some sense or another) to each other than those of the other clusters. 
	- Cluster analysis discover new categories in an unsupervised manner
- **Areas to apply**
	- Data mining
	- Statistical data analysis
- **Issues for clustering**
	- Natural --> groupness
	- Relate objects --> similarity/distance
	- Representation --> vector space, normalization
	- \# of clusters --> fixed a priori or data driven
	- Types --> hieratchical, partitional
- **Similarity distance measures**
	- *Types*
		- Cosine
		- Euclidean
		- Manhattan
		- etc
	- *Measure properties*
		- Symmetry --> $D(A,B) = D(B,A)$
		- Constancy of self-similarity --> $D(A,A)=0$
		- Positivity separation --> $D(A,B) = 0 | if a=B$
		- Triangular Inequality