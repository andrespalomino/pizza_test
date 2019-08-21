Test
<p align="center"> <img src="1pizza.gif"/> </p>


- Sources include: Robot simulated packages and main control node in Qt gui
- Video demos of GUI
- Tested in Ubuntu 16.4 and ROS Kinetic

- Clone

```
mkdir -p ~/pizza_ws/src/
cd ~/pizza_ws/src/
git clone https://github.com/andrespalomino/pizza_test.git

```
- Catkin 

```
sudo apt-get install ros-kinetic-catkin python-catkin-tools
```

- Compile

```
$ rosdep install -y --from-paths . --ignore-src --rosdistro kinetic
$ cd ~/pizza_ws 	
$ catkin_make
$ source devel/setup.bash
```

- Launch

```
roslaunch pizza_test main.launch
```
