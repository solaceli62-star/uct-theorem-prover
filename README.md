# UCT Theorem Prover

UCT-guided symbolic theorem proving system with MCTS search, proof trace logging, and reproducible evaluation framework.

---

## 🧠 Overview

This project explores search-based symbolic reasoning using:

- Monte Carlo Tree Search (MCTS)
- UCT selection strategy
- Rule-based symbolic environment
- Proof trace logging for analysis and reproducibility

The goal is to study whether heuristic search can discover valid symbolic proofs in constrained formal systems.

---

## 🎯 Goal

Example task:

n + 0 = n

The system attempts to prove it using:

- symbolic rewrite rules
- search over proof actions
- evaluation of proof completion

---

## 🧱 System Components

### 1. Proof Environment
Defines symbolic state transitions using rewrite rules.

### 2. Search Engine (MCTS)
Explores proof steps using UCT selection.

### 3. Policy Prior (optional)
Guides search with heuristic preferences.

### 4. Value Function
Estimates whether a state is close to a completed proof.

### 5. Proof Trace Logger
Records full proof trajectories for analysis.

---

## 🚀 Current Version (v0.2)

- Monte Carlo Tree Search (MCTS)
- UCT selection strategy
- Rollout-based evaluation
- Tree expansion and backpropagation

---

## 🔬 Planned Extensions

- v0.3: Neural policy/value models
- v0.4: Dataset generation from proof traces
- v1.0: Neural theorem prover system (research-grade)

---

## ▶️ Run

```bash
python main.py
