# Distributed Algorithms with Gossip and Push-Sum

## Project Overview

This project focuses on implementing and simulating distributed algorithms—Gossip and Push-Sum—using **F#** and the **Akka.NET framework**. The simulation explores how these algorithms perform across various network topologies and evaluates their convergence behavior and performance.

## Objectives

- Simulate Gossip and Push-Sum algorithms for distributed networks.
- Experiment with different network topologies:
  - Line
  - 2D Grid
  - Full
  - Imperfect 3D Grid
- Analyze convergence times and the efficiency of the algorithms.
- Handle large-scale networks with up to:
  - **10,000 nodes** for Gossip.
  - **5,000 nodes** for Push-Sum.

## Features

- **Gossip Algorithm**: 
  - Spreads a piece of information across a network of nodes.
  - Tracks convergence based on how many nodes receive the message.

- **Push-Sum Algorithm**:
  - Computes a sum or average in a distributed network using a probabilistic approach.
  - Convergence is evaluated by observing changes in node values over iterations.

- **Network Topologies**:
  - **Line**: Nodes are connected in a sequential order.
  - **2D Grid**: Nodes are connected in a two-dimensional lattice structure.
  - **Full**: Every node is connected to every other node.
  - **Imperfect 3D Grid**: A 3D grid with random additional connections.

## Technologies Used

- **F#**: Functional programming language for implementing the algorithms.
- **Akka.NET Framework**: Actor-based model for managing distributed processes and simulating message passing.
- **.NET Environment**: Base platform for development and execution.

## Performance Evaluation

- Conducted simulations on networks with varying sizes and topologies.
- Measured convergence times and analyzed algorithm performance under different scenarios.
- Visualized results to provide insights into scalability and efficiency.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
