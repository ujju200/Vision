# Vision-

**An Autonomous Bot Based On Image processing And Breadth-First Search Path Finding Algorithm.**

This project is based on the instructions in the following [Problem Statement](https://github.com/ujju20/Vision/blob/main/Vision2.0%20Problem%20Statement-1.pdf).

![Arena image](https://github.com/ujju20/Vision-/blob/main/test.png)

# Installation Guidelines

Along with this repository, it is needed to have the following repository:

[Vision_Arena](https://github.com/Robotics-Club-IIT-BHU/Vision-2.0-2020-Arena)

Could you follow the steps in these repositories and install the required packages?

You can run [Solution.ipynb](https://github.com/ujju20/Vision/blob/main/solution.ipynb) on the terminal.

# Approach

1. The arena was converted into a 2D matrix using image processing techniques where a particular node number denoted each arena square.

2. Breadth-First Search Path Finding Algorithm was used to determine the shortest path to the destination node.

3. Nodes were inserted into the list on a priority basis to prefer the inner path.

4. We used the differential drive to run the bot more efficiently

# Features

1. the arena and bot movements were visually represented using PyBullet.

2. Image processing techniques were used to manipulate the data, i.e., shape, color, and aruco marker detection in the programmable form.

3. Breadth-First Search Path Finding Algorithm determined the shortest path to reach the destination node

# Video

- [Run on Vision Arena](https://drive.google.com/file/d/16UYtqpRY0y2ey_q_UJsuPqzUj9xVu7Z1/view?usp=sharing)
