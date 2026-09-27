# 🏓 Ping Pong Game

A classic Ping Pong game built with Python and Pygame, featuring both a 
2-player mode and a smart AI opponent powered by the A* search algorithm.

## 📋 Overview

This project implements a fully playable Ping Pong game with real-time 
physics (ball collision, paddle movement, scoring) and two game modes:

- **Player vs Player:** Two human players compete using keyboard controls.
- **Player vs AI:** A single player competes against an AI-controlled 
  paddle that uses the **A\* search algorithm** to predict and track the 
  ball's position, with 3 adjustable difficulty levels (Easy, Medium, Hard).

## 🎮 Controls

| Player | Move Up | Move Down |
|---|---|---|
| Player 1 | ↑ | ↓ |
| Player 2 (Human mode) | W | S |

**Difficulty (AI mode):** Press `1` (Easy), `2` (Medium), or `3` (Hard) 
during gameplay to adjust the AI's speed.

First player to reach **5 points** wins. Press `R` to restart or `Q` to quit.

## 🧠 The AI Opponent (A* Algorithm)

Instead of simple ball-tracking logic, the AI opponent uses **A\* search**, 
a well-known pathfinding algorithm, to calculate the optimal paddle movement 
toward the ball's position — factoring in a heuristic distance estimate at 
each step to decide the most efficient move.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core game logic |
| **Pygame** | Graphics rendering, game loop, and input handling |
| **A\* Search Algorithm** | AI opponent decision-making |

## 📁 Files

- `ping_pong.py` — Classic 2-player version
- `ping_pong Astar.py` — Single-player version with A\* AI opponent
- `pong_table.png` — Game background asset

---
🎮 Built as a personal Python project by **Elsayed Mohamed**
