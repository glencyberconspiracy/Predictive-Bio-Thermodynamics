# Predictive Bio-Thermodynamics: In-Silico Modeling of Cellular Decisions

This repository contains a hybrid computational systems biology framework designed to model, simulate, and analyze the decision-making architecture of *Bacillus subtilis* during starvation-induced sporulation.

---

## Core System Simulation

### 1. System Transition Operators
* **What it does:** Sets up the mathematical rulebook for how resources change during reactions[cite: 1].
* **Layman's Explanation:** It tracks how raw materials (like inputs and proteins) turn into products. It calculates reaction speeds and includes safety locks ensuring the simulation doesn't use fuel that isn't there or create negative quantities[cite: 1].

### 2. Post-Trajectory Evaluation Dashboard
* **What it does:** Analyzes the recorded history of the cell after the timeline finishes[cite: 1].
* **Layman's Explanation:** It serves as an automated grading system. It acts like a stopwatch to log the exact second each survival layer turns on, while tracking the total cellular energy consumed to score the factory's final survival efficiency[cite: 1].

### 3. Biological Network Architecture Mapping
* **What it does:** Programs the biological identity of the organism into the computer[cite: 1].
* **Layman's Explanation:** It creates 26 specific storage bins (for energy, food, and target layers) and links them to 22 possible reaction assembly lines. This structures the exact domino effect of the starvation response[cite: 1].

### 4. Live Integration Execution Loop
* **What it does:** Powers the time machine to run the simulation forward step-by-step[cite: 1].
* **Layman's Explanation:** It takes a healthy starting cell with high energy but no incoming food, and advances time forward in 0.5-second blocks. At each tick, it asks the model rules how much resources should shift, updates the inventory levels, and prints the real-time survival status straight to your dashboard[cite: 1].

---

## Data Visualization & Trajectory Dynamics

### 5. Dynamic Data Visualization Layout
* **What it does:** Converts the raw columns of numbers stored in the simulation history into a side-by-side visual dashboard[cite: 1].
* **Layman's Explanation:** It behaves like a dual-screen monitoring station. Panel 1 tracks the direct trade-off between energy consumption (ATP Pool) and the disappearing food supply (Nutrient Level)[cite: 1]. Panel 2 captures the genetic chain reaction over time, visually mapping the master survival switch rising up, hitting the activation threshold, and triggering the protective signals[cite: 1].

---

## Thermodynamic Energy Landscapes

### 6. Thermodynamic Free Energy Mapping
* **What it does:** Uses probability data from thousands of mock cell configurations to build a 3D thermodynamic landscape[cite: 1].
* **Layman's Explanation:** It builds a topographic map of the cell's possible states. It calculates where cells naturally cluster (high-probability zones) and translates that into low-energy valleys, while using the equation $G = -\ln(P)$ to turn rare cellular states into steep, high-energy mountain walls that a cell must fight to climb over[cite: 1].

### 7. Topographic Landscape Overlay
* **What it does:** Renders a colorful 2D map with an overlaid historical vector line tracking the cell's path[cite: 1].
* **Layman's Explanation:** It plots the actual visualization of Waddington's developmental landscape. It draws colored ring contours to show mountain ranges and stable basins, tracing a path directly across the grid to show how our cell navigated the terrain from its growth basin to its hibernation basin[cite: 1].

### 8. Dynamic Continuous-Flux ODE Trajectory
* **What it does:** Simulates a realistic biological timeline by solving a continuous chain of chemical differential equations step-by-step[cite: 1].
* **Layman's Explanation:** It sets up an interactive simulation step. Instead of forcing data to jump instantly, it lets the internal model calculate a natural, smooth depletion curve, draining food and fuel reserves while checking how genetic response proteins coordinate over time[cite: 1].

### 9. Scale-Calibrated Spatial Mapping
* **What it does:** Calibrates visual axes and bounding coordinates to focus exactly on where biological data is generated[cite: 1].
* **Layman's Explanation:** It acts like adjusting a camera lens to zoom directly in on the active zone, explicitly constraining the vertical axis to match the physical maximum limit of the development traits so travel track coordinates match perfectly[cite: 1].

### 10. Biological Energy Surface Synthesis
* **What it does:** Explicitly formulas two distinct stable physical configurations separated by an unstable chemical ridge[cite: 1].
* **Layman's Explanation:** It programs the exact geography of the landscape, mathematically molding two separate bowls: a starting bowl for standard active cell growth and a destination bowl representing the secure vault of a mature spore, raising a steep mountain ridge between them[cite: 1].

### 11. Phenotypic Geodesic Tracking
* **What it does:** Forces a single coordinate point to travel smoothly across a saddle point from one thermodynamic extreme to the other[cite: 1].
* **Layman's Explanation:** It tracks the path from a high-energy, zero-development starting node, guides it smoothly up and over the mountain ridge, and drops it perfectly into the safe, low-energy hibernation vault[cite: 1].

---

## Genetic Mutation Simulations

### 12. In-Silico Knockout Trajectory
* **What it does:** Simulates a broken genetic circuit by artificially forcing a developmental variable to flatline mid-simulation[cite: 1].
* **Layman's Explanation:** It introduces a structural defect into our virtual factory. The code mimics a genetic deletion ($\Delta\textit{sigF}$) by allowing the cell to behave normally at first, but then triggering a permanent roadblock that completely halts any further developmental progress[cite: 1].

### 13. Phenotypic Comparison Mapping
* **What it does:** Overlays two separate historical tracking arrays onto the same thermodynamic coordinate grid[cite: 1].
* **Layman's Explanation:** It acts like a side-by-side diagnostic scan. It graphs the healthy cell smoothly navigating the environment next to the mutated cell, visually isolating exactly where the mutant gets stuck, fails to advance, and burns through its remaining resources[cite: 1].
