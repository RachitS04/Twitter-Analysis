# Twitter-Analysis README

## Overview
This project focuses on analyzing social network data using **NetworkX** and **Pandas**. It processes a dataset of connections, builds a directed graph, performs centrality analysis, identifies key influencers, detects communities, and visualizes network structures. Additionally, the project integrates **Twitter API** to extract top friends from Twitter users.

## Features
- **Graph Construction:** Reads a dataset and constructs a directed graph.
- **Graph Analysis:** Computes degree centrality, betweenness, closeness, and density.
- **Influencer Detection:** Identifies the top influencers in the network.
- **Community Detection:** Uses the **Girvan-Newman algorithm** to detect communities.
- **Visualization:** Generates network graphs and degree distribution plots.
- **Shortest Path Calculation:** Computes shortest paths between random nodes.
- **Strongly Connected Component Analysis:** Finds the largest SCC and calculates graph diameter.
- **Twitter API Integration:** Fetches top 50 friends based on follower count.

## Data Structures Used
- **Adjacency List:** Represents the graph structure.
- **Dictionaries:** Stores centrality measures and shortest path calculations.
- **Lists:** Holds node and edge data.

## Technologies Used
- **Python**
- **NetworkX**
- **Matplotlib**
- **Pandas**
- **Tweepy (Twitter API)**

## How It Works
1. Loads dataset (`new_dataset.csv`) into a DataFrame.
2. Constructs a directed graph from the data.
3. Computes various graph properties like centrality and density.
4. Identifies top influencers based on in-degree centrality.
5. Detects communities using the Girvan-Newman algorithm.
6. Finds shortest paths between random nodes.
7. Analyzes strongly connected components and computes the largest SCC diameter.
8. Fetches Twitter user data, identifying top 50 most-followed friends.
9. Saves extracted insights into CSV files.

## Installation
### Prerequisites:
- Python 3.x
- Required Libraries:

  pip install pandas networkx matplotlib tweepy


## Future Enhancements
- **Real-time Data Processing:** Stream live data from social platforms.
- **Interactive Dashboards:** Build visual dashboards using Streamlit.
- **Scalability:** Optimize algorithms for large-scale networks.

## Conclusion
This project provides a comprehensive analysis of social network structures, helping understand relationships, detect influential users, and visualize network connectivity. The integration of Twitter API further enhances its real-world applicability.
