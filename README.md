# ROS2_Practice

####### Finding Latest Distribution of ROS2 #######
1. Go to https://docs.ros.org/en/rolling/Releases.html to find out the ROS2 version
2. Find out the EOL (End of Life) date
3. Find out the LTS (Long Time Support) version
4. Select required EOL & LTS version

Here in this project I will use Humble Hawksbill

####### Install ROS2 and Required software #######

*** I am using Ubuntu 22.04 ***

1. Install Terminator (Not mandatory. In this project, I will use terminator. sudo apt-get install terminator)
	i) Shortcut of terminator ( https://cheatography.com/svschannak/cheat-sheets/terminator-ubuntu/pdf_bw/ )
2. Install Visual Studio Code.
	i) Install C/C++ extension from Microsoft
	ii) Install Python extension from Microsoft
	iii) Install CMake from twxs
3. Install python3-pip (It will help to auto formating (ctrl+shift+i))
4. Install any tex editor (I will use gedit)
5. Install ROS2 Humble
	i) Go to https://docs.ros.org/en/humble/Installation.html
	ii) Go to Binary Packages
	iii) Choose Debian Packages
	iv) Set locate (just copy and paste those commands)
	v) Setup Sources (just copy and paste those commands)
	vi) Install ROS 2 packages (just copy and paste those commands)
		Use (sudo apt install ros-humble-desktop) for laptop
		Use (sudo apt install ros-humble-ros-base) for low storate device. e.g. Raspberry pi
	
	 
####### Setup Invironment #######

1. Go to gedit ~/.bashrc
	add source /opt/ros/humble/setup.bash at the end of .bashrc

####### Setup ROS2 build tool #######

1. sudo apt install python3-colcon-common-extensions
2. Go to gedit ~/.bashrc 
	add source /usr/share/colcon_argcomplete/hook/colcon-argcomplete.bash at the end of .bashrc


