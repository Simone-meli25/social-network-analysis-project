# Social Network Analysis: Catch Me If You Can Characters

## Introduction
This project applies Social Network Analysis (SNA) techniques to explore the intricate character interactions in the movie Catch Me If You Can. The goal is to analyze the underlying social structure and relational dynamics within the network of characters.

## Key Objectives:

- Network Construction: Building a character interaction network in Python.
- Graph Analysis: Visualizing the network and calculating key metrics such as:
  - Number of nodes and edges.
  - Average degree.
  - Network density.
- Community Detection: Identifying cohesive subgroups or communities within the network.
- Centrality Analysis: Pinpointing the most influential nodes based on various centrality measures.

## Project Workflow
### Data Preparation
  - Character interactions were extracted and mapped into a network structure.
  - Each node represents a character, and each edge denotes an interaction.

### Network Construction
- The graph was implemented using Python with libraries like:
    - NetworkX: For graph creation and analysis.
    - Matplotlib and Seaborn: For visualization.
- Key metrics calculated include:
    - Number of Nodes and Edges: Indicates the size of the network.
    - Average Degree: Reflects the typical number of connections per node.
    - Network Density: Measures the fraction of potential connections that are realized.

### Graph Visualization
- Visualizations highlighted the global structure and connectivity of the network.
- Key insights:
    - The network exhibits moderate interconnectedness.
    - A sparse graph indicates a small fraction of possible connections are realized.

### Community Detection
- Applied clustering techniques to identify subgroups.
- Communities reveal character groups with closer interactions, shedding light on narrative structure.

### Centrality Analysis
Analyzed centrality measures to rank nodes based on their influence within the network:
- Degree Centrality: Nodes with the most direct connections.
- Betweenness Centrality: Nodes bridging disparate parts of the network.
- Closeness Centrality: Nodes with shorter paths to all others.

### Results and Insights
- Graph Metrics:
  - The network consists of X nodes and Y edges (replace with actual values from the code).
  - The average degree of nodes is approximately Z (replace with actual values).
  - The density metric shows a sparse graph, indicating limited interactions between characters.

- Centrality Insights:
  - Characters A, B, and C (replace with actual characters) were identified as the most influential based on centrality measures.
  - Key nodes act as bridges, playing significant roles in connecting communities.

- Community Insights:
  - Detected cohesive subgroups that correspond to narrative groups or frequent interactions in the movie.

## Tools and Technologies
Python:
- NetworkX: Graph construction and metric calculation.
- Matplotlib and Seaborn: Network and data visualizations.
- Pandas: Data manipulation and preprocessing.
