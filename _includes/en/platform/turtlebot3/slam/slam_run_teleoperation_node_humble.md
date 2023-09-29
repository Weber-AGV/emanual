
Once SLAM node is successfully up and running, TurtleBot3 will be exploring unknown area of the map using teleoperation. It is important to avoid vigorous movements such as changing the linear and angular speed too quickly. When building a map using the TurtleBot3, it is a good practice to scan every corner of the map.

1. Open a new terminal and run the teleoperation node from the Remote PC.  
  Please use the proper keyword among `burger`, `waffle`, `waffle_pi` for the `TURTLEBOT3_MODEL` parameter.  
  ```bash
$ export TURTLEBOT3_MODEL=burger
$ ros2 run turtlebot3_teleop teleop_keyboard

   Control Your TurtleBot3!
   ---------------------------
   Moving around:
          w
     a    s    d
          x

   w/x : increase/decrease linear velocity
   a/d : increase/decrease angular velocity
   space key, s : force stop

   CTRL-C to quit
 ```

2. Start exploring and drawing the map.  
 ![](/assets/images/platform/turtlebot3/slam/slam_running_for_mapping.png)
