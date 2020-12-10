## 天津扬天7kg1650机械臂  
本工程为天津扬天7kg1650机械臂的urdf模型和ros下的仿真以及moveit配置文件，由于这些文件厂商都不提供，使用工程可以减少开发时间，也可以应用于仿真。  
YT文件夹：扬天7kg1650机械臂urdf及rviz展示；  
YT_moveit_config文件夹：扬天7kg1650机械臂moveit配置文件，可用于路径规划。  
YTRobot.ttt为Vrep仿真文件  
将以上两个文件夹拷贝到catkin_ws路径下，在shell中执行：  
'''  
catkin_make  
'''  
模型展示：  
'''
  roslaunch YT display.launch  
'''  
MoveIt仿真及路径规划：  
'''  
roslaunch YT_moveit_config demo.launch  
'''  
