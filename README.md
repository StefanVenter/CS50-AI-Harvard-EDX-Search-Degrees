# CS50 AI - Degrees

## Overview

This project was completed as part of Harvard University's **CS50's Introduction to Artificial Intelligence with Python**.

The goal of the project is to determine how many "degrees of separation" exist between two actors by finding the shortest path of shared movie appearances connecting them.

The solution is implemented using **Breadth-First Search (BFS)**, a fundamental Artificial Intelligence search algorithm that guarantees the shortest path in an unweighted graph.

---

## Problem Description

Given two actors, the program identifies the shortest sequence of actors and movies that connects them.

Example:

Kevin Bacon

↓

A Few Good Men

↓

Tom Cruise

Degrees of Separation: 1

The program uses data from IMDb records and treats actors and movies as a graph structure where:

- Actors represent states (nodes)
- Shared movies represent connections (edges)
- Breadth-First Search is used to find the shortest path

---

## Concepts Covered

- Artificial Intelligence
- Search Algorithms
- Breadth-First Search (BFS)
- Graph Traversal
- State Space Search
- Python Programming
- Data Structures

---

## Technologies Used

- Python 3
- CSV Processing
- Object-Oriented Programming
- Queue-Based Search Algorithms

---

## Project Structure

```text
degrees/
│
├── degrees.py
├── util.py
├── small/
│   ├── people.csv
│   ├── movies.csv
│   └── stars.csv
│
└── large/
    ├── people.csv
    ├── movies.csv
    └── stars.csv
```

---

## Running the Project

Run with the small dataset:

```bash
python degrees.py small
```

Run with the large dataset:

```bash
python degrees.py large
```

Example usage:

```text
Name: Kevin Bacon
Name: Tom Cruise

1 degrees of separation.
1: Kevin Bacon and Tom Cruise starred in A Few Good Men
```

---

## Learning Outcomes

Through this project I gained practical experience with:

- Implementing Breadth-First Search
- Working with graphs and connected data
- Designing and traversing state spaces
- Applying Artificial Intelligence search techniques
- Building command-line Python applications

---

## Course Information

Harvard University

CS50's Introduction to Artificial Intelligence with Python

Project 0: Degrees

---

## Author

Stefan Venter

GitHub: https://github.com/StefanVenter
