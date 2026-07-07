# Operating Systems Visualizer

🏆 **Winner – Deep Minds 5th Edition**

An interactive web-based tool that visualizes core Operating Systems concepts and algorithms, built to make complex OS topics — CPU scheduling, deadlock handling, process synchronization, and memory management — easy to understand through step-by-step, hands-on simulations.

## About

Operating Systems concepts like scheduling algorithms, deadlock avoidance, and synchronization problems are often hard to grasp from textbooks alone. This project turns those abstract algorithms into interactive, visual simulations so students can see exactly how each algorithm behaves — step by step — rather than just reading about it.

The project was awarded at **Deep Minds 5th Edition** for making complex system concepts accessible to students through interactive design.

## Features

The visualizer covers six major OS modules, each with its own interactive simulation page:

- **CPU Scheduling**
  Visualize different CPU scheduling algorithms:
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Round Robin (RR)
  - Priority Scheduling

- **Banker's Algorithm**
  Deadlock avoidance algorithm visualization:
  - Resource allocation matrix
  - Safety check algorithm
  - Resource request handling
  - Step-by-step execution

- **Producer-Consumer Problem**
  Visualize the classic Producer-Consumer synchronization problem:
  - Buffer visualization
  - Semaphore simulation
  - Multiple producers and consumers
  - Step-by-step execution

- **Dining Philosophers Problem**
  Interactive simulation of the Dining Philosophers problem:
  - Philosopher state visualization
  - Chopstick resource management
  - Deadlock risk indicator
  - Step-by-step execution

- **Readers-Writers Problem**
  Simulate the Readers-Writers synchronization problem:
  - Reader and writer process visualization
  - Starvation risk indicator
  - Semaphore simulation
  - Step-by-step execution

- **Resource Allocation Graph**
  Deadlock detection and avoidance visualization:
  - Interactive graph creation
  - Deadlock detection
  - Deadlock avoidance
  - Step-by-step analysis

- **Memory Management**
  Memory allocation and page replacement algorithms:
  - First-Fit / Worst-Fit
  - Page Replacement (FIFO)
  - Page Replacement (Optimal)
  - Page Replacement (LRU)

## Tech Stack

- **HTML5, CSS3, JavaScript** — core structure, styling, and interactivity
- **Chart.js** — for rendering graphs and data visualizations

## Project Structure

```
OS-main/
├── index.html                  # Landing page with links to all modules
├── Try _OS.html                 # CPU Scheduling Visualizer
├── bankers_algorithm.html       # Banker's Algorithm
├── producer_consumer.html       # Producer-Consumer Problem
├── dining_philosophers.html     # Dining Philosophers Problem
├── readers_writers.html         # Readers-Writers Problem
├── resource_allocation.html     # Resource Allocation Graph
└── memory_management.html       # Memory Management
```

## Getting Started

No installation or build step is required — this is a static, client-side project.

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. Navigate to any module from the home page to start the simulation.

## Usage

From the home page, select any of the six modules. Each module lets you configure input parameters (e.g., number of processes, burst times, resource instances) and then walk through the algorithm step by step, observing state changes, allocations, and outcomes in real time.

## Acknowledgment

This project was built as part of **Deep Minds 5th Edition**, where it won recognition for making complex Operating Systems concepts more accessible to students through interactive visual design.
