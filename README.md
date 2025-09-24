# 🎓 Reinforcement Learning Practices

## 📌 Description
This repository contains the practical assignments for the **Reinforcement Learning** course *(2025/2026)*.  

The **first practice** focuses on the implementation and analysis of the **Policy Iteration** and **Value Iteration** algorithms in a tabular *grid world* environment.  
The main goal is to understand the **foundations of reinforcement learning**, including:

- Bellman equations  
- Optimal policies  
- Convergence of algorithms  
- Comparison between deterministic and stochastic environments  

---

## ⚙️ Environment Setup
To run the project, follow these steps:

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
    ````

*(If no `requirements.txt` is provided, make sure `pygame` and `numpy` are installed).*

2. **Run the main script**

   ```bash
   python3 main.py --env_behavior deterministic --algorithm policy_iteration
   ```

   **Available options:**

   * `--env_behavior <deterministic/stochastic>`
   * `--algorithm <policy_iteration/value_iteration/both>`

---

## 📂 Repository Structure

* `main.py` → Main entry point to execute the algorithms.
* `env.py` → Definition of the *grid world* environment (Gym-like).
* `policy_iteration.py` → Implementation of the Policy Iteration algorithm.
* `value_iteration.py` → Implementation of the Value Iteration algorithm.

---

## 👥 Group Members

* Javier Viseras Comín
* Bernardo Ordás Cernadas
* Enrique Rodríguez Camacho

---

## 📖 Course

**Reinforcement Learning – Practice 1**
*Bellman Equations, Policy Iteration and Value Iteration*
Academic Year: **2025/2026**
