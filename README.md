# Motionplanning_Vrep
Comparison of various motion planning algorithm using V-rep vision based system.  
This repository contains the code for various offline motion planning algorithms. Motion planning is a term used in robotics for the process of breaking down the desired movement task into discrete motions that satisfy movement constraints and possibly optimize some aspect of the movement. It involves getting a robot to automatically determine how to move while avoiding collisions with obstacles. This repository includes the following offline motion planning algorithms:
- Grid based motion planning algorithms
  - Uniform cost search algorithm
  - Dijkstra algorithm
  - A* algorithm
- Sampling based motion planning algorithms
  - PRM Planner
  - RRT 
  - RRT*
## Dependencies:
- Opencv
- numpy
- queue
- PIL
- Coppeliasim

## Pre-requisites:
- Python programming knowledge
- Coppeliasim knowledge
- Opencv knowledge

## Simulation Environment:
In order to show how various offline motion planning algorithms works, I am also going to use the Copellasim simulation for representing these offline motion planning.  I will be using Pioneer 3-DX as the robot in the Copellasim environment . In the simulation, a camera is added, which basically shows the whole environment as an image. The main reason for the camera usage is to visualize these offline motion planning algorithms, which is understandable by everyone. The same simulation setup is used for all offline motion planning algorithms, in order to show the difference between these algorithms. 
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/copellasim.png)
## Simulation Output

### Uniform Cost Search:
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/UCS.png)

### Dijkstra:
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/djikstra.png)

### A*:
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/astar.png)

### PRM Planner:
PRM points
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/prm_points.png)
PRM construction
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/prm_cons.png)
PRM with A*
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/prm.png)

### RRT:
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/RRT.png)

### RRT*:
![alt text](https://github.com/shailendranpoyyamozhi/Motionplanning_Vrep/blob/main/Output%20images/RRT*.png)
