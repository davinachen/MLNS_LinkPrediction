# MLNS_LinkPrediction
This repo serves as part of the Machine Learning in Network Science course assignment, with a goal of predicting missing links in an actor co-occurence network. Edges have been deleted at random from a graph. Your mission is to accurately reconstruct the initial network using both graph-theoretical and node feature information.

# Files
1. node_information.csv consists of 932 binary features for each node
2. train.txt file contains more than 10,000 pairs of nodes and indicators for the edge between them
3. test.txt file contains 3498 pairs of nodes and will be used to perform prediction
4. Code folder contains main notebooks using GNN, Node2Vec, Neural Networks algorithm to perform link prediction
5. Model Embedding folder contains the node embedding that was trained based on the graph (with num_walks = 500)

# Credits
- [2023 MLNS Kaggle Competition]( https://www.kaggle.com/competitions/mlns-2023)