# Navvis Description Launch Instructions

There are two arguments that modify the launch of this package:

> **use_xacro**
> <br>*select whether you use a .urdf or .xacro file*
>
>**use_joint_state_publisher_gui**
>*<br>select whether the joint state gui opens -- this allows you to control the joints manually*

The recommended launch command is to use the xacro file and joint state publisher gui which looks like this:

>roslaunch navvis_description navvis.launch use_xacro:=true use_joint_state_publisher_gui:=true