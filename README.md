# -Pathfinding-Visualizer-using-Dijkstra-s-Algorithm
# **Pathfinding Visualizer Using Dijkstra's Algorithm**

This project is a **Pathfinding Visualizer** that demonstrates the functionality of **Dijkstra's Algorithm** using the **SFML (Simple and Fast Multimedia Library)**. It provides an interactive and intuitive way to understand how Dijkstra's Algorithm finds the shortest path in a weighted grid-based environment.

---

## **Features**

### 🎨 **Interactive Grid Setup**
- **Left Click**:  
  - Set the **start point** (green), **end point** (red), and place **obstacles** (black).  
- **Right Click**:  
  - Clear any cell, resetting it to its default state (white).  
- Experiment with different grid configurations to visualize Dijkstra's Algorithm in action.

### 🔍 **Real-Time Pathfinding Visualization**
- **Press Enter** to begin pathfinding:
  - Cells being evaluated are marked in **yellow**.
  - The shortest path is highlighted in **blue**.
- The visualization dynamically adjusts to any grid modifications.
- If no path exists, a **message is displayed** to indicate failure.

### 💡 **Dynamic Feedback**
- The program includes small delays to provide a **step-by-step visualization** of the algorithm's progression.
- Real-time updates make the visualization engaging and educational.

---

## **How It Works**

### **Dijkstra's Algorithm**
- The algorithm calculates the shortest path from the **start point** to the **end point** by exploring the grid iteratively.
- Key features:
  - **Priority Queue**: Maintains cells by their current shortest distance from the start.
  - **Weighted Grid**: Each cell has an equal weight by default, and obstacles are impassable.
  - **Relaxation**: Updates the shortest known distances of neighboring cells.

### **Grid Visualization**
- The grid updates dynamically during the algorithm’s execution.
- **Color codes** help users follow the algorithm's steps:
  - **Yellow**: Cells currently being evaluated.
  - **Blue**: Finalized cells that form the shortest path.
  - **Green**: Start point.
  - **Red**: End point.
  - **Black**: Obstacles.

---

