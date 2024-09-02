# ROS_Moveit_With_STOMP_Planner
I have configured the Moveit with STOMP planner in this workspace base on [MoveIt » Tutorials » STOMP Planner](https://moveit.github.io/moveit_tutorials/doc/stomp_planner/stomp_planner_tutorial.html)

# You may meet "fatal error: nlopt.hpp: No such file or directory  #include <nlopt.hpp>" when you build the workspace
method of fix:

sudo apt-get --reinstall libnlopt-dev 

sudo apt install libnlopt-cxx-dev

libnlopt-dev is not enoug
