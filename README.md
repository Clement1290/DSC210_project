# DSC210_project
Codes for DSC210 Project (24 Fall)

# Introduction

This project implements three different approaches (Eigenvector centrality, PageRank and LeaderRank) to analyze social networks and identify the most influential nodes.

---

## Features

1. **Adjacency Matrix Construction**:
   - Converts the input edge list into an adjacency matrix for analysis.

2. **Algorithm implementation**:
   - Identifies the most important nodes in the network using Eigenvector centrality, PageRank, and LeaderRank.

3. **Top Nodes Visualization**:
   - Highlights the top 20 influential nodes in the network graph using color coding (red for top nodes).

4. **Result Analysis**

---

## File Structure

- **`leader_rank.py`**: The main script that implements the LeaderRank algorithm and visualizations.
- **`facebook_combined.txt`**: Example dataset used to test the algorithm.
- **`LeaderRank_Scores.xlsx`**: Output file containing LeaderRank scores for all nodes.


## Installation

### Prerequisites

Ensure you have Python 3.7+ installed. Then, install the required libraries.

### Steps

1. Install the dependencies:
```bash
pip install networkx numpy matplotlib pandas

