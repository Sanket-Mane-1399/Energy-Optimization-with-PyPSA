# Energy Optimization with PyPSA

This repository contains Jupyter Notebooks that demonstrate energy system optimization problems using **[PyPSA](https://pypsa.org/)** (Python for Power System Analysis).  
The notebooks progressively build from simple electricity market modeling to more advanced topics like capacity expansion and sector coupling.

## Repository Contents

1. **Simple Electricity Market**  
   - Introduces the fundamentals of electricity market clearing using PyPSA.  
   - Demonstrates how supply, demand, and prices interact in a simplified market.

2. **Capacity Expansion Planning**  
   - Explores long-term capacity expansion planning.  
   - Shows how investment decisions in generation technologies and transmission impact system costs and reliability.

3. **Sector Coupling**  
   - Extends the capacity expansion planning framework by integrating multiple energy sectors (e.g., electricity, heating, transport).  
   - Highlights how cross-sector interactions influence overall system design and optimization.  
   - **Note:** This notebook builds on the **Capacity Expansion Planning** model.

## Learning Objectives

   - Understand how to formulate energy optimization problems in PyPSA.  
   - Explore electricity market clearing in a simplified system.  
   - Learn how to perform capacity expansion planning for long-term investment decisions.  
   - Analyze the role of sector coupling in integrated energy system design.

## Solvers Used

The optimization models in this repository are solved using the following solvers:

1. **Gurobi**  
   - A commercial optimization solver known for high performance in linear, integer, and quadratic programming problems.

2. **HiGHS**  
   - An open-source solver for linear programming (LP), mixed-integer programming (MIP), and quadratic programming (QP), integrated via PyPSA.

*Note: This work was completed as part of assignments and workshops at the **TU Berlin, ENSYS Department**.*
