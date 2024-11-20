# Using the ufactory xArm6 with realsense camera 

To try the motion generation with your robot you have to enter the following command in your terminal :

```
omni_python curobo/examples/isaac_sim/realsense_reacher.py --robot /home/theobloesch/Documents/xArm6Curobo/xArm6CuroboConfig.yaml --show-window
```

he first link is the path to the curobo program and the second link is the path to your Curobo config file that you have created in the previous tutorial.

## Code 

In the code there are several values that you can change to modify the object detection 

```
voxel_size = 0.03 # default value : 0.05  ##distance between block##
render_voxel_size = 0.009 # default value : 0.02  ##blocks size##
clipping_distance = 5.0 # default value : 0.7  ##depth of detection for the camera##
```