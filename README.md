# Sartris

**Sartris** is a modern implementation of **Tetris**, built with full support for official **Tetris Guidelines**. It provides an authentic gameplay experience while allowing players to adjust advanced input settings and even watch an intelligent bot play optimized games.

## Features

* **Guideline-Compliant Gameplay**
  Implements the **Super Rotation System (SRS)**, **T-Spin detection**, **Back-to-Back (B2B)** bonus tracking, and **Perfect Clear** recognition.

* **Customizable Controls**
  Players can personalize core control parameters such as:

  * **DAS (Delayed Auto Shift)**
  * **ARR (Auto Repeat Rate)**

* **AI Bot**
  Sartris includes an experimental bot that evaluates every possible placement for the current piece. For each placement, it simulates the resulting board and scores it based on multiple criteria, including:

  * Number of holes
  * Surface flatness
  * Maximum stack height
  * Line clears (with higher rewards for Tetrises)
  * Penalties for inefficient or low-value clears

  The bot selects the placement that maximizes the overall board evaluation score.

* **Responsive and Accessible**
  Built to run directly in your browser at [sartris.netlify.app](https://sartris.netlify.app), with no installation required.

## 🕹️ Gameplay

* **Objective:** Stack falling tetrominoes to form complete horizontal lines and clear them.
* **Modes:**

  * *Sprint Mode:* Race to clear 40 lines as fast as you can.
  * *Ultra Mode:* Aim for the highest score within a 2-minute time limit.
* **Controls:** Move, rotate, and drop pieces using standard Tetris inputs (customizable in settings).
* **Scoring:** Standard guideline scoring system with bonuses for T-Spins, B2B chains, and Perfect Clears.

## Live Demo

Play online here:
👉 [https://sartris.netlify.app](https://sartris.netlify.app)
