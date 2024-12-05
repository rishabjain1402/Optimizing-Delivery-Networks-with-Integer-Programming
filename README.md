### README Description:

# Delivery Optimization Network

This repository contains the final project for **ORIE 5380 / CS 5727 Optimization Methods** at Cornell Tech, focusing on optimizing delivery routes for a digital platform company in City A using linear and integer programming. 

The project explores optimization techniques for delivery logistics, including route planning and resource allocation, leveraging the power of Gurobi for large-scale optimization.

---

## Project Overview

The goal of this project is to optimize delivery logistics for a company in a two-dimensional city grid. The project is divided into multiple phases, each addressing specific scenarios and constraints in delivery optimization:

### **Key Problems Addressed**
1. **Single Delivery per Driver**: Assigning drivers to customers to minimize total distance, assuming each driver handles one delivery.
2. **Multi-Delivery Routes**: Designing routes for drivers who can deliver to up to 5 customers sequentially.
3. **Integer Programming for Driver Assignment**: Reformulating the problem to account for constraints like a limited number of drivers and optimal route planning.
4. **Sensitivity Analysis**: Exploring how the number of drivers affects the total distance traveled.
5. **Incorporating Driver Home Locations**: Extending the model to include driver home locations to minimize the total distance traveled.

---

## Features

- **Optimization Models**:
  - Linear Programming (LP)
  - Integer Programming (IP)
- **Min-Cost Flow Model**:
  - Using flows to simulate delivery schedules.
- **Multi-Driver Routing**:
  - Assigning multiple deliveries per driver.
- **Sensitivity Analysis**:
  - Impact of driver count on travel distance.
- **Extended Problem**:
  - Accounting for driver-to-warehouse distances.

- **Visualization**:
  - Graphical representation of optimized delivery routes.

---

## Tools & Technologies

- **Python**
  - Libraries: `pandas`, `numpy`, `matplotlib`, `networkx`
- **Optimization Solver**:
  - Gurobi Optimizer
- **Data Visualization**:
  - Matplotlib, NetworkX for route plotting.

---

## Repository Contents

- **`ORIE5380_Final_Project.pdf`**: Jupyter notebook containing the full implementation of optimization models.
- **`README.md`**: This file with detailed project description.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/Delivery-Optimization-Network.git
   cd Delivery-Optimization-Network
   ```

2. **Install Dependencies**:
   Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib gurobipy networkx
   ```

3. **Add Data**:
   Download the required data files (`customer_locations.csv`, `warehouse_locations.csv`, `supply.csv`, `driver_locations.csv`) and place them in a folder named `data/`.

4. **Run the Code**:
   Open the Jupyter notebook `OM_final_project.ipynb` to run the optimization models.

---

## Results & Insights

- **Optimized Delivery Routes**:
  - Reduced total distance traveled by up to 30% using multi-driver routing.
- **Sensitivity Analysis**:
  - Increasing the number of drivers decreases total distance but with diminishing returns.
- **Extended Model**:
  - Including driver home locations further optimized the total distance.

---

## Authors
- **Rishab Jain** (`rj424`)
- **Berend van Nieuwland** (`bnv7`)

---

Let me know if you'd like to modify or add anything specific!
