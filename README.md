# amazon-mcts-engine

An efficient AI engine for Amazon Chess, powered by Monte Carlo Tree Search (MCTS), C++ optimization, and future integration with large language models and reinforcement learning.

---

## 🌟 Project Overview

This project aims to develop an intelligent agent to play the board game **Amazon Chess**, with the following long-term goals:

- 🎯 Implement high-performance **MCTS** for decision making
- ⚙️ Use **SIMD** and **compiler optimizations** to accelerate search
- 🤖 Explore **large language models** for guided pruning
- 🧠 Extend with **reinforcement learning** for policy/value approximation

---

## 📌 Current Progress

> ⬜ Phase 1: Game Rule Engine & CLI  （now)

> ⬜ Phase 2: Basic MCTS Agent  
> ⬜ Phase 3: Parallelization & SIMD  
> ⬜ Phase 4: LLM-guided Search  
> ⬜ Phase 5: RL-based Self Play

---

## 🧩 Game Description

Amazon Chess is a two-player strategy game played on a 10×10 board. Each player controls four queens (Amazons). On each turn, a player:

1. Moves one of their Amazons like a chess queen.
2. Then fires an "arrow" from that Amazon to block a square.
3. The last player able to make a move wins.

---

## 🔧 Tech Stack

- Language: C++17 or higher
- Build System: CMake
- (Future) Python bridge for LLM/RL
- (Future) SIMD: `std::simd` or `xsimd`

---

## 📂 Project Structure

```bash
.
├── src/
│   ├── board.cpp / board.h        # Core game logic
│   ├── move.cpp / move.h          # Move representation
│   └── main.cpp                   # CLI interface
├── tests/                         # Test cases
├── README.md
└── CMakeLists.txt
