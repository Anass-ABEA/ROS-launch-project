# ROS : Open an existing project

## code
Source the Terminal, create 2 folders (catkin_ws and src inside the folder catkin_ws)
```
source /opt/ros/noetic/setup.bash
mkdir catkin_ws
cd catkin_ws
mkdir src
catkin_make
```
Open terminal and navigate to `catkin_ws` then execute the command :
```
roscore
```
Open another tab and execute
```
source devel/setup.bash
```
```
cd src
catkin_create_pkg car_test roscpp rospy rosmsg
```
Now copy the `car_test` folder to the `src` folder and overwrite the files.
Execute the following commands :
```
cd ..
catkin_make
roslaunch car_test car.launch
```

# Info : 
[<img src="https://img.shields.io/badge/Video-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" target="_bank"/>](https://www.youtube.com/watch?v=QbLmGxX7V_M&ab_channel=AnassAITBENELARBII)
[<img src="https://img.shields.io/badge/Channel-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" target="_bank"/>](https://www.youtube.com/channel/UCTK0fGhApaJlERojmqmn_YQ/)

