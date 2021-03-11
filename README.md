# Social-Network-Analysis

## DATASET:

#### The Marvel Universal Social Network : https://www.kaggle.com/csanhueza/the-marvel-universe-social-network.

#### The dataset contains heroes and comics, and the relationship between them. The dataset is divided into three files: node types (hero, comic), edges ( which comic the heroes appear) and hero-edge (heroes which appear together in the comics).


## PROBLEM DESCRIPTION:

#### There are hundreds of thousands of heroes in the Marvel Universe and they appear in an extensive list of comics. I'm interested in learning the relationship among heroes and how they appear in comics. 

#### There are several questions that I will analyze this social network to figure out the answers:
 
#### - What is the most popular heroes in Marvel comics?
#### - Which heroes usually appear together?
#### - How the teams are formed and the connections between members?


## GENERAL APPROACH:

#### I will explore this social network problem by evaluating the network size, density, centralization, reciprocity and hierarchy of different levels of network:

#### - Node: node level analysis to understand which nodes have higher degree centrality in the network. By determining the betweenness centrality and closeness centrality, I could define the importance or position of each actor in the Marvel universe social network.

#### - Sub-group level: sub-group level analysis to detect communities in Marvel network by finding dense subgraph because the team expects the graph to be relatively dense with high connectivity.
