# Network Reachability Checker

A Python-based network reachability checker that simulates OSPF path calculation using Dijkstra's algorithm to find the lowest-cost path between routers.

## Project Overview

This project represents a network as a weighted graph, where routers are nodes and network links are represented by costs.

Dijkstra's algorithm is used to calculate the lowest-cost path between a source router and a destination router based on the configured network topology.

## How It Works

1. The network topology is represented as a weighted graph.
2. Routers are represented as nodes.
3. Network links are represented by costs.
4. Dijkstra's algorithm calculates the lowest-cost path.
5. The program displays the calculated path and its total cost.

## Technologies Used

- Python
- Dijkstra's Algorithm
- OSPF Concepts
- Priority Queue (`heapq`)
- Graph-Based Path Calculation

## Example

The project calculates the lowest-cost path from:

`Router_A` → `Router_D`

The selected path is based on the configured network topology and link costs.


## Project Files

- `network_reachability_checker.py` – Python source code implementing the network reachability checker.
- `Network Reachability Checker.pdf` – Project documentation containing implementation screenshots.

## Skills Demonstrated

- Python Programming
- Network Routing Concepts
- OSPF Path Calculation
- Dijkstra's Shortest Path Algorithm
- Graph-Based Network Modeling
- Network Troubleshooting Concepts
- Basic Network Automation

## Documentation

Detailed project documentation, implementation details, and code screenshots are available in the project PDF:

**[Network Reachability Checker Documentation](./Network%20_Reachability_Checker.pdf)**
