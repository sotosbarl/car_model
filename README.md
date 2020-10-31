Just roslaunch car_model_gazebo test_world.launch
and spawn the model: rosrun gazebo_ros spawn_model -file `rospack find car_model_description`/urdf/car_model.urdf -urdf -x 0 -y 0 -z 1 -model car_model
