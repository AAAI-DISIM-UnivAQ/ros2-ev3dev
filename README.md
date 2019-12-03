# ros2-ev3dev
ROS2 nodes on the ev3dev OS on Lego Mindstorm robotic kit

## Requirement

Be sure to communicate properly with the Lego robot. See this [tutorial](https://youtu.be/TNXqizQTZhs) from Nigel Ward .

## Steps

In order to run ROS2 programs on the Lego Mindstorm kit, there are many steps to achieve:

1. Install [Docker CE](http://www.docker.com/products/docker-desktop) on your host machine
2. Follow instruction to [install the docker image on your host](http://www.ev3dev.org/docs/tutorials/using-docker-to-cross-compile) in order to cross-compile ROS2 nodes into lego compatible executables
3. Follow [ROS official wiki](http://wiki.ros.org/ROS/Tutorials) to define your robotic project and nodes
4. Define `ros_master` to point to your host were you should run your `ros2_core`

...

(work in progress)

