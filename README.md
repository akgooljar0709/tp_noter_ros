# TP RVIZ ROS BY GOOLJAR AKASH

## Installation

Make a git clone of the git repository
```sh
https://github.com/akgooljar0709/tp_noter_ros.git
```

## Partie 1
```sh
cd marker_ws
source devel/setup.bash
roscore
rosrun marker_visualiser publish_marker.py /visualization_marker:=/marker_test
rviz
```

## Partie 2
```sh

source devel/setup.bash
roscore
rosrun marker_visualiser publish_marker_array.py /visualization_marker:=/space_delimiter
rviz
```

## Partie 3
```sh

source devel/setup.bash
roscore
rosrun marker_visualiser randomwalk.py
rviz
```

## Partie 4
```sh

source devel/setup.bash
roscore
rosrun marker_visualiser random_walk.py
rviz
```

On RVIZ click on ADD AND BY TOPIC THEN SELECT THE TOPIC.



