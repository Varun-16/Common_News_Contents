Common_News_Contents
====================

This project is to achieve the objective of finding common news contents from multiple news sources. 

-> We crawl the news content descriptions from multiple news websites like ABC News, BBC News, CNN News and develop a similarity
graph. News contents from each source form their own cluster. 

-> A similarity graph is a graph which has news contents as its nodes and the edge between two nodes has an edge
weight equal to the cosine similarity between them.

-> The presence of an edge is determined by a threshold value.

-> The presence of a cycle in the similairty graph indicates commonality. 
