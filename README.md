# DSC210_project
Codes for DSC210 Project (24 Fall)

# LeaderRank Algorithm

This project implements the **LeaderRank algorithm** to analyze networks and identify the most influential nodes. The algorithm highlights nodes with high global connectivity, including bridge nodes that connect different communities, ensuring a robust ranking for both sparse and dense networks.

---

## Features

1. **Adjacency Matrix Construction**:
   - Converts the input edge list into an adjacency matrix for analysis.

2. **LeaderRank Algorithm**:
   - Identifies the most important nodes in the network using a supernode-based approach and power iteration.

3. **Top Nodes Visualization**:
   - Highlights the top 20 influential nodes in the network graph using color coding (red for top nodes).

4. **Result Export**:
   - Saves the LeaderRank scores of all nodes in an Excel file for further analysis.

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

