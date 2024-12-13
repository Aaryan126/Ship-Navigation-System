# Ship Navigation Optimization and Visualization

## **Overview**
This project was developed as part of the **Design and Innovation Project** by a team of eight peers. The objective was to enhance and optimize ship navigation algorithms to ensure efficient, safe, and accurate routing of ships to their destinations while avoiding both local and global obstacles. Additionally, the project provides visualizations to help better understand the navigation process and the decisions made by the algorithms.

---

## **Project Goals**
1. **Improve Navigation Algorithms**:
   - Enhance the Dynamic Window Approach (DWA) and A* algorithms for better obstacle avoidance and pathfinding.
   - Ensure safe navigation through both static and dynamic environments.

2. **Obstacle Avoidance**:
   - Account for **local obstacles** (e.g., rocks, buoys, other vessels in close proximity).
   - Account for **global obstacles** (e.g., larger areas to avoid, like restricted zones or shallow waters).

3. **Visualization**:
   - Provide real-time visualization of the ship’s route and its interaction with obstacles.
   - Demonstrate the effectiveness of the navigation algorithms through simulation.

---

## **Features**
- **Algorithm Integration**: Combines A* (global planning) and DWA (local planning) to provide a robust navigation solution.
- **Dynamic Obstacle Handling**: The ship dynamically avoids obstacles that enter its path.
- **Simulation Visualization**:
  - Visualize the ship’s path in real-time.
  - Show interactions with obstacles and adjustments made to the course.
- **Customizable Configurations**: Adjust ship parameters like speed, dimensions, and maneuverability.

---

## **Technologies Used**
### Programming Language:
- Python

### Libraries:
- **Core Libraries**:
  - `numpy`: Numerical computations for path planning.
  - `matplotlib`: For plotting paths and visualizations.
  - `opencv-python`: For handling background images and maps.

- **GUI Framework**:
  - `PyQt5`: Used for building the graphical user interface.

- **Custom Modules**:
  - `dwa_paper_with_width`: Implementation of the Dynamic Window Approach.
  - `a_star`: Implementation of the A* algorithm.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Aaryan126/Ship-Navigation-System.git
   cd Ship-Navigation-System
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
---

## **Usage**
1. **Input Parameters**:
   - Start and goal positions of the ship.
   - Obstacle configurations and map selection.
   - Ship dimensions and speed constraints.

2. **Run the Simulation**:
   - The application will compute the optimal path and dynamically adjust for any new obstacles.
   - Visualize the ship’s navigation in real-time.

3. **Output**:
   - A visual display of the ship’s path and obstacles.
   - Logs of the ship’s coordinates and distance to goals.

---

## **Example Videos**

We have included two example videos to demonstrate the use and functionality of the algorithms:

1. **Without Local Obstacles**: Demonstrates the ship navigating on the Singapore map without any local obstacles.

2. **With Local Obstacles**: Shows the ship navigating on the Singapore map while dynamically avoiding local obstacles.

These videos provide a clear understanding of how the algorithms work under different scenarios.

---

## **Team Members**
This project was a collaborative effort by eight team members, with contributions spanning algorithm development, GUI design, testing, and documentation.

- Aaryan Kandiah
- Chen LongTing
- Liu Zenan
- Tan Yue Jun Darren
- Chong Wen Ci
- Zhang Yitian
- Shi Wen
- Nixon Edward Winata
---

## **Acknowledgments**
We extend our gratitude to our project mentors and advisors for their guidance and support throughout the development of this project. Special thanks to Huang Erdong and Professor Jiang Xudong.

---

## **Future Work**
- Implement machine learning techniques for better obstacle prediction.
- Add support for 3D obstacle visualization.
- Optimize the algorithms for faster computations in larger environments.

---

## **Contact**
For more information or questions about this project, please contact:
- **Aaryan Kandiah**: aaryan001@ntu.edu.sg
- **GitHub Repository**: https://github.com/Aaryan126/Ship-Navigation-System/
