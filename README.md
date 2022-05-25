# ROS Beginner Level Mini Project
### This is a simple starter task using turtlesim for those who have just started learning ROS.
### Using ROS nodes, ROS topics and ROS services, the following pattern is recursively traced on the turtlesim simulator.
<br>
<!-- Video of the project -->
<p align="center">
    <img src="https://github.com/Somya-Bansal159/ROS-beginner-demo/blob/main/Demo%20Video.gif">
</p>

### Open a new terminal and start roscore:
    $ roscore
### Keep the roscore running, and in a new terminal, you can install the turtlesim simulator using the following command:
    $ sudo apt-get install ros-$(rosversion -d)-turtlesim
### Now, clone the ROS package named as "captain_america" in the src folder of your catkin workspace.
### In the terminal, go to the root of the workspace, and build the package:
    $ catkin_make
### Source the setup file using:
    $ source ./devel/setup.bash
### Great! Now, run the launch file and watch the turtles roaming around in a not so beautiful pattern😅:
    $ roslaunch captain_america captain_america.launch
