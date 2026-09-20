# Network Reachability Checker

## 📌 Overview

A Python-based network reachability project that simulates OSPF shortest-path calculation using Dijkstra's algorithm.

The project models a network topology consisting of routers with weighted links and calculates the lowest-cost path between a source router and a destination router.

---

## 📑 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Project Objectives](#-project-objectives)
- [🛠️ Technologies & Concepts](#-technologies--concepts)
- [🔄 Project Workflow](#-project-workflow)
  - [Network Topology](#network-topology)
  - [Dijkstra's Algorithm](#dijkstras-algorithm)
  - [Priority Queue](#priority-queue)
  - [OSPF Path Simulation](#ospf-path-simulation)
- [⚙️ Configuration & Implementation](#️-configuration--implementation)
- [🧪 Execution & Validation](#-execution--validation)
- [🧠 Skills Demonstrated](#-skills-demonstrated)
- [📸 Documentation](#-documentation)
- [📁 Project Structure](#-project-structure)
- [⭐ Project Summary](#-project-summary)

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Simulate OSPF shortest-path calculation.
- Represent a router network topology using Python.
- Assign costs to links between routers.
- Calculate the lowest-cost path between routers.
- Implement Dijkstra's shortest-path algorithm.
- Use a priority queue to process routers based on path cost.
- Display the calculated path cost.

---

## 🛠️ Technologies & Concepts

- Python
- Dijkstra's Algorithm
- OSPF Path Calculation
- Network Topology
- Weighted Graph
- Priority Queue
- `heapq`

---

# 🔄 Project Workflow

## Network Topology

The project represents the network topology as a weighted graph.

The topology contains four routers:

- Router_A
- Router_B
- Router_C
- Router_D

Each connection between routers has an associated cost.

---

## Dijkstra's Algorithm

The project implements Dijkstra's algorithm to calculate the shortest path between the selected source and destination routers.

The algorithm initializes the distance to the source router as zero and the distances to the remaining routers as infinity.

It then evaluates neighboring routers and updates their distances when a lower-cost path is found.

---

## Priority Queue

Python's `heapq` module is used to implement a priority queue.

The priority queue allows the algorithm to process the router with the lowest current path cost first.

---

## OSPF Path Simulation

The project uses the shortest-path calculation to simulate OSPF path calculation through the network topology.

The function:

```python
calculate_ospf_path(graph, start_router, end_router)

calculates the lowest cost between the selected routers.

⚙️ Configuration & Implementation

The project uses a network topology represented as a weighted graph.

network_topology = {
    "Router_A": {"Router_B": 10, "Router_C": 2},
    "Router_B": {"Router_D": 5},
    "Router_C": {"Router_B": 3, "Router_D": 15},
    "Router_D": {}
}

The configured source router is:

start = "Router_A"

The destination router is:

destination = "Router_D"

The calculated result is stored using:

best_cost = calculate_ospf_path(
    network_topology,
    start,
    destination
)
🧪 Execution & Validation

The project was executed successfully in Python.

The documented execution calculates the path cost between:

Router_A → Router_D

The program returns the calculated lowest path cost and completes successfully.

The project documentation provides screenshots showing:

Python source code
Network topology
Router link costs
Dijkstra's algorithm implementation
Priority queue implementation
OSPF path calculation
Program execution and output
🧠 Skills Demonstrated
Python Programming
Network Automation Concepts
Network Topology Modeling
Graph Algorithms
Dijkstra's Algorithm
Shortest-Path Calculation
OSPF Concepts
Weighted Network Graphs
Priority Queue Implementation
heapq Usage
📸 Documentation

The project documentation contains screenshots of the Python implementation and execution.

The documentation demonstrates the network topology, weighted router connections, shortest-path calculation, and resulting program output.

📁 Project Structure
Network-Reachability-Checker/
│
├── README.md
│
└── Network _Reachability_Checker.pdf
⭐ Project Summary

This project demonstrates the implementation of a Python-based shortest-path calculation for a simulated network topology.

Using Dijkstra's algorithm and a priority queue, the project calculates the lowest-cost path between routers and provides a practical simulation of OSPF path calculation.
