# WaddleWorks — Graph Algorithms & Network Optimization

**Java | Graph Data Structures | BFS | DFS | Dijkstra's | Prim's | Kruskal's | Disjoint Sets**

## Overview
WaddleWorks is a Java-based graph algorithms project that models and analyzes two interconnected city networks: a weighted road network and an electrical grid. The project demonstrates how graph data structures and algorithms can be applied to real-world problems including route planning, neighborhood connectivity, shortest-path analysis, and electrical grid optimization.

The project implements a custom weighted, undirected graph and applies multiple graph algorithms to efficiently analyze and optimize the networks.

## Data Structures & Technical Implementation

### Weighted Graph — Network Representation
- Implemented a custom weighted, undirected graph using adjacency lists.
- Represented road networks using `Intersection` vertices and weighted edges representing traversal duration.
- Represented electrical grids using `Building` vertices and weighted edges representing wire length.
- Supported dynamic vertex and edge insertion/removal while maintaining graph connectivity.

### BFS & DFS — Graph Traversal
- Implemented Breadth-First Search (BFS) for level-based graph traversal and minimum-edge path analysis.
- Implemented recursive Depth-First Search (DFS) for graph exploration and connectivity analysis.
- Used visited sets and adjacency-list traversal to avoid repeated vertex exploration.

### Dijkstra's Algorithm — Shortest Paths
- Implemented Dijkstra's algorithm using a priority queue to calculate single-source shortest distances in weighted graphs.
- Applied shortest-path analysis to determine optimal routes and identify central locations within the electrical grid.
- Supported non-negative weighted edges with `Integer.MAX_VALUE` representing unreachable vertices.

### Prim's & Kruskal's — Minimum Spanning Trees
- Implemented Prim's and Kruskal's algorithms to construct minimum spanning trees for weighted graphs.
- Applied minimum spanning tree techniques to consolidate the electrical grid while maintaining connectivity and minimizing total wire length.
- Used priority queues to efficiently select minimum-weight candidate edges.

### Disjoint Set — Connectivity & Neighborhoods
- Implemented a Disjoint Set data structure with path compression and union-by-rank.
- Dynamically tracked connected components within the road network.
- Used representative roots to efficiently identify and count neighborhoods and determine whether newly added roads connect previously separate components.

## Key Features
- **Road Network Management:** Add weighted roads between intersections while tracking connected neighborhoods.
- **Neighborhood Analysis:** Identify connected components and organize intersections based on their number of connecting roads.
- **Minimum-Road Routing:** Determine the minimum number of roads between buildings using graph traversal.
- **Route Optimization:** Calculate routes that prioritize avoiding undesirable intersection types, with travel duration used as a tiebreaker.
- **Power Site Selection:** Identify the most central building based on average shortest-path distance to other buildings.
- **Electrical Grid Consolidation:** Construct a minimum spanning tree to remove unnecessary wiring while preserving full grid connectivity.
- **Dynamic Graph Operations:** Maintain graph structure as roads, buildings, and connections are added or removed.

## Key Learning Outcomes
- Implemented and applied fundamental graph algorithms to weighted, undirected networks.
- Developed a deeper understanding of graph traversal, shortest-path algorithms, minimum spanning trees, and connected components.
- Practiced selecting appropriate data structures—including adjacency lists, priority queues, and Disjoint Sets—based on algorithmic requirements.
- Applied algorithmic concepts to realistic network optimization problems while analyzing time and space complexity.
- Learned how individual algorithms can be adapted to solve more specialized optimization problems beyond their standard implementations.

## Technical Skills
**Languages:** Java
**Data Structures:** Graphs, Adjacency Lists, HashMaps, HashSets, Priority Queues, Disjoint Sets
**Algorithms:** BFS, DFS, Dijkstra's, Prim's, Kruskal's, Minimum Spanning Trees, Path Reconstruction
**Concepts:** Graph Traversal, Shortest Paths, Connected Components, Network Optimization, Greedy Algorithms, Time Complexity

## Source Code
This project was completed as part of Georgia Tech's CS 1332 Data Structures & Algorithms course. The implementation is maintained in a private repository in accordance with course academic integrity policies. This public repository contains a high-level project overview only.
This project was completed as part of Georgia Tech's CS 1332 Data Structures & Algorithms course. The implementation is maintained in a private repository in accordance with course academic integrity policies. This public repository contains a high-level project overview and technical documentation only; course implementation code is not included.
