# Customer-Reviews-Analysis-and-Topic-Modeling

## Objective
In this project, I will analyze yhe underlying structure of documents automatically and visualize the clustering result using natural language processing models/tools. 

## Data and Code
The data is from [here](https://snap.stanford.edu/data/web-Amazon.html). The dataset that I use has been uploaded to the repo. It's a big file and cannot preview. The basic structure of it is as follows: ID, Clothing ID, Age, Title, Review Text, Rating, Recommended IND, Positive Feedback Count, Division Name, Department Name, Class Name.

## Summary
- Used anonymous but real source women’s clothing E-Commerce dataset (data size = 23486) to parse out the text and
analyzed reviews to improve products via Python.
- Split the corpus into two-sentiment (positive and negative) category based on exploratory data analysis, imported nltk
package to use NLP tools with stopwords and prepossessed each document via tokenization and stemming.
- Implemented feature engineering by term frequency- inverse document frequency (TF-IDF) based on bigram to
reflect the importance of a word in a corpus.
- Bulit and trained unsupervised learning model of K-Means Clustering method (K = 5) to minimize the within-cluster
sum of squares and attained grouped features.
- Performed Latent Dirichlet Allocation (LDA) method for topic modeling (topic number = 5).
