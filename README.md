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
- [📊 Example Configuration](#-example-configuration)
- [🧪 Execution & Output](#-execution--output)
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

The project uses the shortest-path calculation to simulate the way OSPF can determine a lowest-cost route through a network topology.

The function:

```python
calculate_ospf_path(graph, start_router, end_router)
