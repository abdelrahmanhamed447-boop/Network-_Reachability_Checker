# Network Reachability Checker

## 📌 Overview

A Python-based network reachability project that simulates OSPF shortest-path calculation using Dijkstra's algorithm.

The project models a network topology consisting of routers with weighted links and calculates the lowest-cost path between a source router and a destination router.

---

## 📑 Table of Contents

- [📌 Overview](#-overview)
- [📑 Table of Contents](#-table-of-contents)
- [🎯 Project Objectives](#-project-objectives)
- [🛠️ Technologies & Concepts](#️-technologies--concepts)
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

The algorithm evaluates the available paths and determines the lowest-cost route through the network topology.

---

## Priority Queue

Python's `heapq` module is used to implement a priority queue.

The priority queue allows the algorithm to process routers based on their current path cost.

---

## OSPF Path Simulation

The project uses the shortest-path calculation to simulate OSPF path calculation through the network topology.

The function:

```python
calculate_ospf_path(graph, start_router, end_router)

calculates the lowest cost between the selected routers.

⚙️ Configuration & Implementation

The project uses a network topology represented as a weighted graph.

The topology contains routers connected through links with different costs.

The source and destination routers are selected for the shortest-path calculation.

The Dijkstra-based path calculation processes the topology and determines the lowest-cost route between the selected routers.

The implementation uses Python's heapq module as a priority queue for processing the available paths.

🧪 Execution & Validation

The project was executed successfully in Python.

The documented execution calculates the path cost between the selected source and destination routers.

The program processes the configured topology and returns the calculated lowest-cost path.

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

The project documentation contains screenshots showing the Python implementation and execution of the Network Reachability Checker.

The documentation demonstrates the configured network topology, weighted router connections, shortest-path calculation, and program output.

📁 Project Structure
Network-Reachability-Checker/
│
├── README.md
│
└── Network _Reachability_Checker.pdf
⭐ Project Summary

This project demonstrates the implementation of a Python-based network reachability checker using Dijkstra's algorithm to calculate the lowest-cost path through a simulated router topology.

The project provides a practical simulation of OSPF shortest-path calculation using weighted network links and a priority queue.
