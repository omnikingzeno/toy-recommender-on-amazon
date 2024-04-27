# 📌 Toy Recommendation System using Network Analysis
## 👉 Introduction
* This project is a toy recommendation system using network analysis.
* The dataset used in this project is the Toy dataset from https://www.kaggle.com/datasets/PromptCloudHQ/toy-products-on-amazon
* The goal of this project is to recommend toys to users based on the toys they have already bought.
* The recommendation system is based on the network analysis of the toy pairs.
    * The network analysis is done using the NetworkX library in Python.
* The recommendation system is implemented using the PageRank algorithm.
    * The PageRank algorithm is used to rank the toys based on their importance in the network.
    * The toys with the highest PageRank scores are recommended to the users.
    * Another method used to recommend is the asynchronous lable propagation algorithm.
* The recommendation system can be extended to recommend toys to users based on their preferences and buying patterns.
* The recommendation system can be extended to other domains such as e-commerce, social networks, and online advertising.
* The code for the recommendation system is available on GitHub at the following link: [GitHub](https://github.com/omnikingzeno/toy-recommender-on-amazon)

## 📓 Dataset
The dataset used in this project is the Toy dataset from https://www.kaggle.com/datasets/PromptCloudHQ/toy-products-on-amazon. The dataset has 10000 rows of bought toys. More details on the fields can be found out at the given kaggle link.

## 🌐 Network Analysis
The network analysis is done using the NetworkX library in Python. The toy pairs are represented as a directed graph, where the toys are the nodes and the toy pairs are the edges. The network analysis is done to find the importance of the toys in the network. The importance of the toys is measured using the PageRank algorithm. The PageRank algorithm and asynlpa are used to rank the toys based on their importance in the network and form communities. 

## 🎯 Recommendation System
The recommendation system is implemented using the PageRank algorithm. The PageRank algorithm is used to rank the toys based on their importance in the network. The toys with the highest PageRank scores are recommended to the users. The asynlpa algorithm is a probabilistic algorithm that assign labels to node based on the neighboring nodes. asynlpa is used to form communities and such communities represent a group which have properties in common.

## 📝 Conclusion
In this project, a toy recommendation system using network analysis is implemented. The recommendation system is based on the network analysis of the toy pairs. The recommendation system is implemented using the PageRank algorithm. The PageRank algorithm is used to rank the toys based on their importance in the network. The recommendation system is then evaluated using the metrics such as F1 score, recall, precision and more when compared to the truly bought products

## How to run?
The file named recommender2.ipynb can be run in a jupyter environment with python kernel. The file recommender.ipynb does not have the functionality as described here but uses other techniques such as weighted nodes based on number of reviews and also a simple string matching nltk library use for the recommendations.
## 📚 References
- David Easley and Jon Kleinberg, "Networks, Crowds, and Markets: Reasoning About a Highly Connected World", Cambridge University Press, 2010.
- NetworkX library in Python: https://networkx.org/
- PageRank algorithm: https://en.wikipedia.org/wiki/PageRank
- Toy dataset: https://www.kaggle.com/datasets/PromptCloudHQ/toy-products-on-amazon
- Asynchronouse label propagation algorithm: https://networkx.org/documentation/stable/reference/algorithms/generated/networkx.algorithms.community.label_propagation.asyn_lpa_communities.html
