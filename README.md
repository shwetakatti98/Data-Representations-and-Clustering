# Data-Representations-and-Clustering
## ECE 219 - Project 2

The first part of the project explores the various unsupervised clustering models applied on textual data. The dataset being used for the same is the 20 Newsgroups and is available in scikit-learn.

We start by analyzing the performance of K-means clustering algorithm with 2 clusters. We consider the var- ious dimensionality reduction techniques such as SVD, NMF and also analyze the performance of the model with no reduction techniques. We then move on to implement clustering models for the entire 20 classes. Along with the above mentioned reduction techniques, we also explore another linear reduction technique called UMAP. We then extend our analysis to other clustering models such as Agglomerative clustering, DBSCAN and HDBSCAN. All these models are compared based on the evaluation metrics mentioned below and the best models are highlighted in the report. 

The evaluation metrics used are: 
- Homogeneity
- Completeness
- V-Measure
- Adjusted Rand Index
- Adjusted Mutual Information Score

In the second part of this project, we employ the VGG-16 architecture to extract features from the given tf flowers dataset. Deep Learning and Clustering of image data. Here, we use the tf flowers dataset provided to us with a VGG network which has been pretrained on the ImageNet dataset. We test this with various dimensionality reduction methods such as SVD, UMAP and autoencoder.


The three files are as follows:
- Project2_PART1.1.ipynb : Includes all questions of part 1 from 1 to 9 and question 17
- Project2_PART1.2.ipynb : Includes all questions of part 1 from 10 to 18
- Project2.Part2.ipynb : Includes all questions of part 2 from 19 to 25

Project2_PART1.2.ipynb and Project2.Part2.ipynb were both run on Google Colab and Project2_PART1.1.ipynb was run on Jupyter Notebook.
