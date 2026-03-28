# Operating_system_Lab-assignment

# 📘 Operating System Lab Assignment

This repository contains implementations of important **Operating System algorithms**:

- 🔐 Banker's Algorithm (Deadlock Avoidance)  
- ⚙️ CPU Scheduling Algorithms (FCFS & SJF - Non Preemptive)

---

## 📂 Files Included

- `bankers_algorithm.py` → Implementation of Banker's Algorithm  
- `fcfs_sjf.py` → Implementation of FCFS and SJF Scheduling  
- Output Screenshots (included below)

---

## 🧠 1. Banker's Algorithm

### 📌 Description
Banker’s Algorithm is used for **deadlock avoidance**. It determines whether the system is in a **safe state** and provides a **safe execution sequence**.

### ⚙️ Features
- Accepts Allocation, Maximum, and Available matrices  
- Computes **Need Matrix**  
- Checks system safety  
- Displays **Safe Sequence**

### ▶️ How to Run
```bash
python bankers_algorithm.py
