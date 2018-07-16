# Introduction

In 2013, students of the Statistics class at FSEV UK were asked to invite their friends to participate in this survey.

* The data file (responses.csv) consists of 1010 rows and 150 columns (139 integer and 11 categorical).
* For convenience, the original variable names were shortened in the data file. See the columns.csv file if you want to match the data with the original names.
* The data contain missing values.
* The survey was presented to participants in both electronic and written form.
* The original questionnaire was in Slovak language and was later translated into English.
* All participants were of Slovakian nationality, aged between 15-30.

For this kernel, we use network analysis to analyze the features of HOBBIES & INTERESTS. We use different network analysis techniques and methods to analyze the features.

# What is a Network?

* A network is a set of nodes connected by a set of edges
    * **Nodes** are also called **vertices**
    *  **Edges** are also called **links**
    *  **Networks** are also called **graphs**
    
* A node represents an entity, this can be anything:
    * People
    * Cities
    * Symptoms
    * Psychological constructs
    
* An edge represents some connection between two nodes. Again, this can be anything:
    * Friendship / contact 
    * Distance
    * Comorbidity
    * Causality
    * Interaction

<center><img src="https://image.ibb.co/ekaGHT/graph1.png" alt="Network Example" style="width: 300px;"/></center>

# Types of network

* A network with weighted edges is called a **weighted graph**
* Otherwise it is called an **unweighted graph**
* If all edges are directed the network is called a **directed graph**
* If all edges are not directed the network is called an **undirected graph**

<center><img src="https://image.ibb.co/feNJWo/types_of_graph.png" alt="types_of_graph" style="width: 400px;"/></center>

A directed network with no cycles is called a **Directed Acyclic Graph (DAG)**. A cycle means that you can not start at a node and encounter it again by following directed edges. This includes no self-loops.

**DAGs** are very useful in that they represent a clear dependency structure between the nodes.

<center><img src="https://image.ibb.co/c6pMj8/types_of_graph2.png" alt="types_of_graph" style="width: 400px;"/></center>

# Real World Examples

<center><img src="https://image.ibb.co/ksnDxT/graph_of_real_world_1.png" alt="types_of_graph" style="width: 400px;"/></center>
<center><img src="https://image.ibb.co/jDHVcT/graph_of_real_world_2.png" alt="types_of_graph" style="width: 400px;"/></center>
<center><img src="https://image.ibb.co/cHPnP8/graph_of_real_world_3.png" alt="types_of_graph" style="width: 400px;"/></center>
<center><img src="https://image.ibb.co/mv9bHT/graph_of_real_world_4.png" alt="types_of_graph" style="width: 400px;"/></center>
<center><img src="https://image.ibb.co/cwnVcT/graph_of_real_world_5.png" alt="types_of_graph" style="width: 400px;"/></center>
