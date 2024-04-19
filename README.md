# Customer-Reviews-Analysis-and-Topic-Modeling

## Objective
In this project, I will analyze yhe underlying structure of documents automatically and visualize the clustering result using natural language processing models/tools. 

## Data and Code
The data is from [here](https://snap.stanford.edu/data/web-Amazon.html). The dataset that I use has been uploaded to the repo. It's a big file and cannot preview. The basic structure of it is as follows: 
- Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed. 
- Age: Positive Integer variable of the reviewers age.
- Title: String variable for the title of the review.
- Review Text: String variable for the review body.
- Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
- Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
- Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
- Division Name: Categorical name of the product high level division.
- Department Name: Categorical name of the product department name.
- Class Name: Categorical name of the product class name.

The code is uploaded as .ipynb file.

## Summary
- Used anonymous but real source women’s clothing E-Commerce reviews dataset (data size = 23486) to cluster and discovered latent semantic structures via **Python**.
- Preprocessed text by sentiment-based split, tokenization, stemmimg, removing stop words and implemented feature engineering by **term frequency- inverse document frequency (TF-IDF)** based on bigram.
- Bulit unsupervised learning model of **K-Means Clustering method** (K = 5) to grouped features.
- Performed **Latent Dirichlet Allocation (LDA)** method for topic modeling (topic number = 5).
