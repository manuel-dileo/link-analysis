# Link Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/manuel-dileo/link-analysis/blob/main/LinkAnalysis.ipynb)  
Sw project for the course of Algorithms for Massive Datasets, Master Degree in Computer Science at Unimi, a.y 20/21.
## Task
The task is to implement from scratch a system ranking nodes in a graph using the PageRank index (or other approaches based on link analysis), processing the IMDB dataset. Nodes in the graph will identify actors, and an edge will link two nodes if the corresponding actors played at least once in the same movie.
## Overview
I made a data structure for sparse Graph. I implemented from scratch PageRank, Topic-Sensitive PageRank, HITS algorithms. I analyzed their performances and compared their results on a subset of nodes of interest, that is the top 10 actors and actresses of all time by IMDB, by constructing similarity matrix between rankings. I empirically evaluated the performance and convergence of PageRank. My PageRank implementation is faster than the networkx base implementation.


