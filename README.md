# 🧬 Genetic Algorithm – One Max Problem

This project demonstrates a **Genetic Algorithm (GA)** implementation for solving the **One-Max Problem**, where the goal is to maximize the number of `1`s in a binary chromosome.

The project includes:
- Python implementation (VS Code ready)
- Google Colab / Jupyter Notebook
- Fitness evolution visualization
- Best chromosome tracking per generation
- Presentation slides (Canva)

---

## 📌 Problem Statement

Each chromosome is a **16-bit binary string**.

**Objective:**  
Maximize the number of `1`s using genetic operations.

Example:

---

## ⚙️ Genetic Algorithm Components

- **Population Size:** 20
- **Chromosome Length:** 16
- **Selection:** Tournament Selection
- **Crossover:** Single-Point Crossover
- **Mutation Rate:** 1%
- **Generations:** 50

---

## 🧠 Algorithm Workflow

1. Initialize population with low fitness (~5)
2. Evaluate fitness
3. Select parents
4. Apply crossover
5. Apply mutation
6. Create next generation
7. Track best chromosome
8. Plot fitness improvement

---

## 📊 Results

- Best and average fitness increase over generations
- Chromosomes gradually converge toward optimal solution
- Fitness evolution graph included

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/genetic-algorithm-onemax.git
cd genetic-algorithm-onemax


