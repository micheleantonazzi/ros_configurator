# ros-configurator
[![pypi](https://img.shields.io/pypi/v/ros-configurator.svg)](https://pypi.org/project/ros-configurator/)
![](https://travis-ci.com/micheleantonazzi/ros_configurator.svg?branch=main)

**NB -> tested only on Ubuntu**

This package helps developers to configure their ROS environment.

# Install package

Simply run in your terminal

```bash
pip install ros-configurator
```

# Instruction

This module provides a lot of shell commands, that guide you in the configuration of the ROS environment. Run one of the following commands in a terminal:

* ```ros_config_set_ip_localhost```: this command sets ```ROS_MASTER_URI=http://127.0.0.1:11311/``` and ```ROS_HOSTNAME=127.0.0.1```.
* ```ros_config_set_ip:``` you can use this command to set the ROS_MASTER_URI and ROS_HOSTNAME variables to the current machine IP in the local network.
* ```ros_config_set_ros_master_uri```: this command asks you for an IP and sets the ROS_MASTER_URI variable to it.
* ```ros_config_list_source_files```: this command shows a list of the bash files sourced in your ROS environment.
* ```ros_config_add_source_file```: this command asks you a bash file path and adds it to the source files list. If the command is run in a ros workspace directory, you can type '.' and the corresponding bash file is automatically sourced.
* ```ros_config_remove_source_file```: this command shows a list of the bash files sourced in your ROS environment and you can specify one to remove.

**NB -> after using a command, remember to restart the terminal or source .bashrc**
