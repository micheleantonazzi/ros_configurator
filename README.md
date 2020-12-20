# ros-configurator

**NB -> tested only on ubuntu**

This package helps developers to configure their ros environment.

# Install package

Simply run in your terminal

```bash
pip install ros-configurator
```

# Instruction

This module provides a lot of shell commands, that guide you in the configuration of the ros environment. Run one of the following commands in a terminal:

* ```ros_config_set_ip_localhost```: this command sets ```ROS_MASTER_URI=http://127.0.0.1:11311/``` and ```ROS_HOSTNAME=127.0.0.1```.
* ```ros_config_set_ip:``` you can use this command to set the ROS_MASTER_URI and ROS_HOSTNAME variables to the current machine IP in the local network.
* ```ros_config_set_ros_master_uri```: this command asks you for an IP and sets the ROS_MASTER_URI variable to it.
* ```ros_config_list_source_files```: this command shows a list of the bash files sourced in your ros environment.
* ```ros_config_add_source_file```: this command asks you a bash file path and adds it to the source files list.
* ```ros_config_remove_source_file```: this command shows a list of the bash files sourced in your ros environment and you can specify one to remove.