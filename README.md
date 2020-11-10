1)Put the 3 packages in a workspace

2) catkinize 
3) Before you can launch everything you should put the blue and yellow cones folders in  ~/.gazebo/models and change the path in each sdf file (/home/YOURNAME/.gazebo/models/blue_cone/blue_cone.dae)

4) Another thing you need to change is the path in the /car_model_gazebo/worlds/track3.world file to your specific path(/home/YOURNAME/.gazebo/models/yellow_cone/yellow_cone.dae about 600 times so feel free to use find and replace method)

5) You are ready. Just roslaunch car_model_gazebo artbot05.launch


