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
   git clone https://github.com/your-repo/ship-navigation.git
   cd ship-navigation
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
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

## **Team Members**
This project was a collaborative effort by eight team members, with contributions spanning algorithm development, GUI design, testing, and documentation.

- **Your Name**
- **Team Member 2**
- **Team Member 3**
- **Team Member 4**
- **Team Member 5**
- **Team Member 6**
- **Team Member 7**
- **Team Member 8**

---

## **Acknowledgments**
We extend our gratitude to our project mentors and advisors for their guidance and support throughout the development of this project. Special thanks to [any specific individuals or organizations].

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

## **Future Work**
- Implement machine learning techniques for better obstacle prediction.
- Add support for 3D obstacle visualization.
- Optimize the algorithms for faster computations in larger environments.

---

## **Contact**
For more information or questions about this project, please contact:
- **Your Name**: your.email@example.com
- **GitHub Repository**: [link to repository]



# AutomaticNavigation_Algorithms

This is the Design and Innovation Project 

## How to Use

### 1. Clone this repo.
    git clone https://github.com/Aaryan126/Ship-Navigation-System.git

### 2. Install the required libraries.
    pip install -r requirements.txt

### 3. Construct maps/ obstacles and optimise the algos.

## Algorithms

Added on 2024-08-21 for DIP, by Huang Erdong (erdong.huang@ntu.edu.sg)

These codes were developed an open-source project on GitHub: https://github.com/AtsushiSakai/PythonRobotics
Feel free to explore this interesting GitHub repo which contain many algorithms related to your DIP. 

### - a_star.py
    code for A* algorithm (minimally modified from the original version in the abovementioned GitHub repo)
### - dynamic_window_approach_paper.py
    code for DWA
    The abovementioned GitHub repo modify the original DWA method (by the original DWA paper), but turns out to have worse performance.
    I modified the open-source GitHub codes to follow the original DWA method proposed in the original DWA paper.
### - dwa_astar_v4.py
    code for integration of DWA and A*
    Developed by myself. 
    You'll need to modify the import statements (line 1~8) according to how you organize the Python files, before you can successfully run this script. 
    Feel free to drop me an email if you can't figure out how to run this script. 
