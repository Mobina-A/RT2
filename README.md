# RT2_ SecondAssignment _ Jupyter

This Jupyter Notebook provides an interface for controlling and visualizing a robot's navigation in a ROS environment.

## Features

* Set and cancel navigation goals.
* Visualize robot's position and path in real-time.
* Monitor the number of reached and canceled goals.

## Installation

To run it in the docker
1) Clone the project
```bash
 git clone https://github.com/Mobina-A/RT2_SecondAssignment.git
```
2) Open Jupyter notebook
```bash
 jupyter notebook --allow-root --ip 0.0.0.0
```
Use the token specify on the Docker terminal to enter

3) Upload the files
4) Open a new terminal and run the assignment

```bash
 cd RT2_SecondAssignment/assignment_2_2023
```
```bash
 roslaunch assignment_2_2023 assignment1.launch
```
6) Run the jupyter file and set the location!

## Example
---------------------------------

<p align="center">
  <img src="Images/fig1.png?raw=true" alt="Fig.1: Reached/Cancelled Goal Figure" width="500" style="display:inline-block; margin: 0 10px;" />
  <br />
  <strong>Fig.1:</strong> Reached/Cancelled Goal Figure
</p>

<p align="center">
  <img src="Images/fig2.png?raw=true" alt="Fig.2: Robot Odometry Figure" width="500" style="display:inline-block; margin: 0 10px;" />
  <br />
  <strong>Fig.2:</strong> Robot Odometry Figure
</p>

<p align="center">
  <img src="Images/fig3.png?raw=true" alt="Fig.3: Gazebo Env." width="500" style="display:inline-block; margin: 0 10px;" />
  <br />
  <strong>Fig.3:</strong> Gazebo Env.
</p>




