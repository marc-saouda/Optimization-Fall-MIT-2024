# **MIT Optimization Course (Fall 2024)**
### **15.C57 / 15.C571 / 6.C57 / 6.C571 / IDS.C57**
This repository contains my implementations of **optimization problems** from the MIT Optimization Course (Fall 2024). It includes **integer optimization, robust optimization, stochastic programming, and dynamic programming** applied to real-world problems.

---

## **📌 Course Topics Covered**
- **Linear Optimization** (Production planning)
- **Integer Optimization** (Facility location)
- **Robust Optimization** (Uncertainty modeling)
- **Stochastic Optimization** (Decision-making under uncertainty)
- **Dynamic Programming** (Time-dependent optimization problems)
- **Network Flow Optimization** (Transportation, facility location)
- **Constrained and Non-Constrained Non-Linear Optimization** (Multimodal learning)


---

## **📝 Assignments Overview**
### 🔹 **Integer Optimization & Waste Management**
- **Optimizes landfill location selection** to minimize waste transportation costs.
- Uses **integer programming** to model the problem.
- Implements constraints for waste disposal and distance minimization.

### 🔹 **Robust & Stochastic Optimization**
- **Robust optimization reformulation** for network flows.
- **Stochastic optimization** for facility location problems.
- Implements **adaptive decision-making under uncertainty**.

### 🔹 **Cloud Computing: Energy Optimization**
- **Minimizes energy consumption in cloud data centers**.
- Uses **linear programming** to distribute jobs optimally.
- Compares solutions with and without machine capacity constraints.

---

## **🔎 Results & Insights**
| Problem | Method Used | Objective |
|---------|------------|-----------|
| Waste Management | Mixed-Integer Programming (MIP) | Minimize transportation cost |
| Robust Network Flow | Robust Linear Optimization | Minimize worst-case cost |
| Cloud Computing | Linear Programming (LP) | Minimize energy consumption |

Each model is implemented in **Julia (JuMP, Gurobi)**.

---

## **📜 License**
This project is licensed under the **MIT License**. See the `LICENSE` file for details.


