# Model_environment_states
 The current version is used for testing the landing algorithm and apriltags detection, so you need the depenpencies and modifications:
 - https://github.com/LASER-Robotics/laser_vision
 - In this package copy the files in the "changes to apriltag_ros package" folder, and paste them in the apriltag_ros launch folder. ( this is for apriltag use the configuration files inside the sessions folder".
 Installation instructions:
 - Clone this package;
 - Build this package, using the catkin build command;
 - Go to the "start" folder and run the command "start.sh".
 - Now you need to publish in the /gazebo/set_model_state topic the pose, orientation and angle you want. 
