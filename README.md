# Binpacking-algorithms

## 📦 What is the Bin Packing Problem?

The **Bin Packing Problem (BPP)** is a classic **combinatorial optimization problem**.  
The goal is to pack a set of items, each with a given size, into the minimum number of bins of fixed capacity.  

- Each item must be placed in exactly one bin.  
- The total size of items in a bin cannot exceed its capacity.  
- The objective is to **minimize the number of bins used**.  

This problem is **NP-hard**, meaning that finding the optimal solution is computationally expensive for large instances.  
Therefore, different approaches are used, such as **exact methods**, **heuristics**, and **metaheuristics**.

---

## 📌 Project Description

In this project, we explored different methods to solve the **Bin Packing Problem**, including:  
- **Exact methods** (e.g., Integer Linear Programming)  
- **Heuristic methods** (e.g., First Fit, Best Fit)  
- **Metaheuristic methods** (e.g., Genetic Algorithms, Simulated Annealing)

- ## 🔬 Hyper-Heuristic Approach

In addition to exact, heuristic, and metaheuristic methods, we also studied a **hyper-heuristic approach**.  
A hyper-heuristic is a **high-level search method** that aims to automatically select or generate heuristics to solve a problem.  

- Instead of solving the Bin Packing Problem directly, the hyper-heuristic manages a set of low-level heuristics (e.g., First Fit, Best Fit, etc.).  
- It learns or decides **which heuristic to apply at each step**, depending on the state of the problem.  
- This makes the approach more **adaptive** and capable of finding better solutions across a wide range of instances.  

In our project, we reference a research article that proposes a **hybrid hyper-heuristic solution** for the Bin Packing Problem, combining the strengths of traditional heuristics with adaptive selection strategies.
