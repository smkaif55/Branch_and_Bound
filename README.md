# Branch and Bound: Technique for Optimization Problems 🌳
**Systematic State-Space Search via Branching, Bounding, and Pruning**

[![Course](https://img.shields.io/badge/Course-SE%20214-blue)](#)
[![Instructor](https://img.shields.io/badge/Instructor-Ayesha%20Siddika-purple)](#)
[![Department](https://img.shields.io/badge/Department-Software%20Engineering-green)](#)
[![University](https://img.shields.io/badge/University-Daffodil%20International%20University-orange)](#)

## 📌 Overview
This repository contains the group presentation slides (`Branch_and_Bound_BY S M KAIF.pptx`) developed for **Course SE 214** under the instruction of **Ayesha Siddika** at the **Department of Software Engineering, Daffodil International University (DIU)**.

The presentation explains how **Branch and Bound (B&B)** solves combinatorial optimization problems by systematically dividing the solution space, computing upper/lower bounds, and pruning suboptimal branches—illustrated with complete step-by-step worked examples for both **0/1 Knapsack (Maximization)** and the **Travelling Salesman Problem (Minimization)**.

---

## 🗂️ Presentation Structure (14 Slides)

| Slide | Topic | Key Concepts Covered |
| :--- | :--- | :--- |
| **01** | **Title Slide** | *Branch and Bound: Technique for Optimization Problems* (`SE 214` Group Roster). |
| **02** | **What Is Branch and Bound?** | Core definition, state-space tree mechanics, and how B&B differs from backtracking. |
| **03** | **Core Components** | Branching, Bounding, and Pruning with a worked maximization pruning rule (`UB ≤ Current Best`). |
| **04** | **State Space Tree & Procedure** | 7-step working algorithm and live-node pruning walkthrough. |
| **05** | **Node Selection Strategies** | Comparing **FIFO** (BFS), **LIFO** (DFS), and **Least-Cost** (Best-First) search orders. |
| **06** | **0/1 Knapsack Formulation** | Problem setup (`Capacity = 16 kg`, 4 items) and binary integer linear formulation. |
| **07** | **Knapsack Step-by-Step (Setup)** | Sorting by profit-to-weight ratio (`P/W`) and computing the fractional upper bound (`UB = 115`). |
| **08** | **Knapsack Search Tree** | Depth-first (LIFO) exploration finding optimal profit **`90`** (`Items A + C`) in 13 nodes vs. 31 brute-force nodes. |
| **09** | **TSP Problem Setup** | 4-city symmetric cost matrix (`A, B, C, D`) and minimization pruning rule (`LB ≥ Best Tour`). |
| **10** | **TSP Tours & Lower Bound** | Enumerating tours and deriving the initial lower bound (`LB = 75`) via the two cheapest incident edges per city. |
| **11** | **TSP Search Tree** | Least-cost (best-first) search tree finding optimal tour **`A → B → D → C → A` (`Cost = 80`)** in 9 nodes. |
| **12** | **Real-World Applications** | Logistics routing, manufacturing mix, job assignment, scheduling, integer programming, and resource allocation. |
| **13** | **Algorithm Comparison** | Brute Force vs. Greedy vs. Dynamic Programming vs. Branch and Bound (advantages & limitations). |
| **14** | **Closing & Q&A** | Concluding remarks and discussion. |

---

## 🎓 Course Details
* **Course Code:** SE 214
* **Course Instructor:** Ayesha Siddika
* **Department:** Department of Software Engineering
* **Institution:** Daffodil International University (DIU)

---

## 👥 Presented By
* **S M Kaif** (`ID: 252-35-342`)
* **Mobassher Mahmud Mejba**
* **Isamuzaman Isam**
* **Jalis Mahmud Chaklader**
* **S. K. Tamzid Hasan Chomok**

