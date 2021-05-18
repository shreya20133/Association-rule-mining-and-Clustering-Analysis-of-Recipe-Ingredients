# Association-rule-mining-and-Clustering-Analysis-of-Recipe-Ingredients

#### The Association rule mining or Market Basket Analysis is performed in R language. The Recipes are the transactions and the list of ingredients in each recipe serve as items. We want to analyze what ingredients tend to occur together most frequently in recipes. We will also analyze which ingredients are most likely to occur given a particular set of ingredients. The analysis is visualized with various graph plots.
#### Clustering of Recipes was performed using k-means & Hierarchical methods to separate our recipe dataset into clusters. The number of clusters was chosen using silhouette analysis, choosing k that gave the largest average silhouette score and created clusters with similar sizes. For speed and accuracy, we used a sparse term frequency inverse document frequency matrix of 30 features.These clusters can be used as a means of classifying generated recipes, and we can compare against recipes in the dataset.

## Software Requirements:
#### R environment setup for Jupyter Notebook
#### Google colab

## References:
### http://cs229.stanford.edu/proj2017/final-reports/5244233.pdf 
### https://cran.r-project.org/web/packages/arulesViz/index.html 
### https://www.rdocumentation.org/packages/arulesViz/versions/1.3-3 
### https://www.rdocumentation.org/packages/arulesViz/versions/1.3-3/topics/plotly_arules

