# Recommendation System

**Some recommendation system algorithms I implemented during my studies at Lanzhou University in 2023, which being developed based on tensorflow2 implementation.**

## Datasets
- MovieLens-100k: This dataset contains 100,000 movie rating data and can be used for the development and testing of movie recommendation systems.
- MovieLens-1m: With 1 million movie ratings, it has a larger data volume than MovieLens-100k and can provide more abundant information.
- MovieLens-20m: This is a very large movie dataset. However, due to its large size, it is not included in this project file. If you need this dataset, [download MovieLens-20m](http://files.grouplens.org/datasets/movielens/ml-20m.zip) and place the 'ml-20m' folder in the 'Recommender_System/data/ds' directory.
- music lastfm: A music-related dataset that may contain user's music playback records, ratings, and other information for music recommendations.
- book Book-Crossing: A book recommendation-related dataset that may include user's evaluations and reading records of books.
- Some satori knowledge graphs: Knowledge graphs can provide additional semantic information for the recommendation system, enhancing the accuracy and interpretability of recommendations.

## Algorithms
- UserCF (user-based collaborative filtering): Analyzes the similarity between users to recommend items liked by similar users to the target user.
- ItemCF (item-based collaborative filtering): Based on the similarity between items for recommendation. That is, if a user likes an item, the system will recommend similar items.
- LFM (Latent Factor Model): Mines the latent features of users and items to predict the user's preference for an item.
- SLIM: A sparse linear model for item recommendation in recommendation systems.
- GMF (Generalized Matrix Factorization): Applies matrix factorization technology to recommendation systems to improve recommendation accuracy.
- MLP (Multilayer Perceptron): A deep learning model that can learn complex nonlinear relationships and is used in recommendation systems.
- NeuMF (Neural Matrix Factorization): Combines neural networks and matrix factorization methods to improve recommendation performance.
- FM (Factorization Machine): An effective feature combination method that can be used to handle sparse data.
- DeepFM: Combines deep neural networks and factorization machines to simultaneously learn low-order and high-order feature interactions.
- MKR (Multimodal Knowledge Graph Recommendation): Utilizes multimodal information in knowledge graphs for recommendation.
- RippleNet: A recommendation algorithm based on knowledge graphs that recommends by propagating user preferences.
- KGCN (Knowledge Graph Convolutional Network): Utilizes the structural information of knowledge graphs and performs recommendation through convolutional neural networks.

## Evaluation metrics
- auc and f1 for click-through rate prediction (ctr): AUC (Area Under the Curve) is a metric for measuring the performance of binary classification models. It represents the probability that a randomly selected positive sample and a negative sample are predicted by the model such that the prediction value for the positive sample is greater than that for the negative sample. The F1 score is the harmonic mean of precision and recall and is used to comprehensively evaluate the performance of the model. In click-through rate prediction, AUC and F1 can measure the prediction accuracy of the model for whether a user will click on an item.
- precision and recall for topk evaluation: Precision represents the proportion of truly liked items among the recommended items. Recall represents the proportion of truly liked items that are recommended among all the items that the user truly likes. In topk evaluation, usually the top k items in the recommendation list are selected for evaluation to measure the accuracy and recall ability of the recommendation system.

## Requirements
- Python 3.11.
- Tensorflow 2.5.0.

## Running
Open the parent folder of this file as a project in PyCharm. Set up the Python 3.11 environment and install version 2.5.0 of tensorflow using pip.

Go to the source code file of Recommender_System/algorithm/xxx/main.py and click to run.

The MovieLens-20m dataset is too large and therefore not included in this project file. If you need this dataset, [download MovieLens-20m](http://files.grouplens.org/datasets/movielens/ml-20m.zip) and place the 'ml-20m' folder in the 'Recommender_System/data/ds' directory.
