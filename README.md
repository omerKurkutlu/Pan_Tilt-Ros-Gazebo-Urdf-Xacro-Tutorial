# pan_tilt URDF and Xacro tutorial

## Create urdf and xacro file for pan_tilt
 This project consists of two parts.
 
      1-) pan_tilt.urdf  
      2-) pan_tilt.xacro 

 To launch these two piece of code, we have two launch file
 
      1-) urdf_demo.launch
      2-) xacro_demo.launch


## Output for both file will be same as below: 
![GifVid](https://user-images.githubusercontent.com/53236244/175957052-29bb00d5-3061-4bb7-bad7-4d300cbeff95.gif)


## How to Launch
Download this project inside your src folder. Then follow the commands below:
```bash
catkin_make
```
```bash
source ./devel/setup.bash
```
Launch urdf
```bash
roslaunch pan_tilt urdf_demo.launch
```
Launch xacro
```bash
roslaunch pan_tilt xacro_demo.launch
```

## Note!!!
You have to install the required packages
```bash
sudo apt update
```
```bash
sudo apt install ros-<your_ros_version>-joint-state-publisher-gui
```
