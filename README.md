# Create 2 nodes shared a string message

 ROS workspace:
 create folder WallE_ws and folder src
use this command line "catkin_make" 

New package: 
use this command line "catkin_create_pkg --rodistro notice tutorials rospy roscpp std_msgs"

Publisher nodes using python: 
create scripts folder inside the tutorial folder
use this command line "wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/talker.py" to create publisher file
, "chmod talker.py" and "python3 talker.py " to run code

Subscriber nodes using Python: 
use this command line "wget https://raw.github.com/ros/ros_tutorials/kinetic-devel/rospy_tutorials/001_talker_listener/listener.py" to create publisher file
, "chmod listener.py" and "python3 listener.py " to run code


Reference:
https://www.udemy.com/course/ros-basics-program-robots/

http://wiki.ros.org/ROS/Tutorials/WritingPublisherSubscriber%28python%29
