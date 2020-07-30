# SocialNetworkAnalysis2020-UniPi
Project on Google Trending Keywords for the course Social Network Analysis at University of Pisa in 2020

## Requirements:
* crawl the data from an online data source
* the network must have at least 10-15k nodes

## Network Analysis
* Degree distribution analysis
* Connected components analysis
* Path analysis
* Clustering Coefficient
* Density analysis
* Centrality analysis
The statistics computed on the crawled data must be compared with the ones of ER, BA, WS and configuration model graphs having the same number of nodes and edges.

## Community discovery
Identify, evaluate and validate the modular structure of the crawled network sample. The results of K-clique, Label Propagation, Louvain, and Demon/Angel must be evaluated and compared. If additional semantic information for the analysed graph are present use them to make sense of the identified partitions. For CD algorithm implementations (as well as for their evaluation and comparison) refer to the CDlib library. The analysis can be extended selecting approaches considered interesting among the one present in such library.

## Link Prediction
Design a supervised approach to link prediction using a classifier. Define the features, test the model(s), evaluate and discuss the results.

## Graphlets
Graphlets are small, connected, non-isomorphic induced subgraphs of a large network. The size of a graphlet is the number of the nodes it is composed of: for a same size multiple graphlets may exist. Define an approximate algorithm that allows to estimate the number of graphlets of size 3 and 4 and test it on your data. Which are the most frequent graphlets?

## Open problem
