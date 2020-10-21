For Just Rviz:
roslaunch diffdrive ddrobot_rviz.launch model:=diffdrive3.urdf 

For Rviz + Gui
roslaunch diffdrive ddrobot_rviz.launch model:=diffdrive3.urdf gui:=True

URDF Verification and Visualizaing tool
$ sudo apt-get install liburdfdom-tools 

For XML URDF File Description
check_urdf diffdrive5.urdf
