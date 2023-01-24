# Mobile Robot Bootcamp

For the first lab, we will just focus on getting everyone set up with [ROS 2](https://docs.ros.org/en/humble/index.html) and ready to program and build robots.

In lab on Thursday, we will walk you through the basic concepts for ROS and play with some basic functionalities of it.

## Install Foxglove studio.
Foxglove studio is a visualization tool for ROS 2. It is relatively new but very powerful. Please download it on you laptop [here](https://foxglove.dev/studio).

## Install ROS2 Humble on your machine. (Recommended for Linux and Windows Users.)
In the past, ROS is very exclusive. Your kind of have to use a linux based system to use it. As an upgrade, ROS 2 now supports more [platforms](https://www.ros.org/reps/rep-2000.html#rolling-ridley-june-2020-ongoing), but the community still prefers linux over other platforms. Try your best to install 
ROS on your laptop, but this is definitely not a requirement to complete the course. Even if you have trouble installing it, please still bring your laptop to
the lab on Thursday. 

### Linux
If you have a linux system, great! Please follow the instructions [here](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html) to install ROS 2 Humble. If possible, you should do desktop install ```sudo apt install ros-humble-desktop```. Development tools are not required. 

### Windows
Method 1 (recommended): Windows setup is a bit harder than Linux machines. Please follow the instructions [here](https://docs.ros.org/en/humble/Installation/Windows-Install-Binary.html) to install ROS 2 Humble. 

Method 2: As an alternative, you can leverage the power of [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install) and install ubuntu 22.04 inside your windows machine. (For older version of Windows 10, follow instructions [here](https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/#:~:text=To%20install%20WSL2%20on%20Windows,%E2%80%9Cwsl%20%E2%80%93update%E2%80%9D%20command.).) Then, follow the linux installation instructions [here](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html) to install ROS inside your WSL.
* This is not recommended because you may run into firewall issures. Also, you cannot connect to remote robot through your laptop later. 

### Mac (not recommended)
Method 1: macOS is no longer a target platform for future ROS realeases, this means you need to compile from source.
If you have macOS Mojave (10.14) and have some free time, give [this](https://docs.ros.org/en/humble/Installation/Alternatives/macOS-Development-Setup.html) a try.
Otherwise, we will provide raspberry pi as alternatives during the lab.

Medthod 2: If you are a pro on docker, [here](https://hub.docker.com/r/osrf/ros2/) is a docker image for you. This is not recommended because you are not able to 
connect to your remote robot from docker. This is only good for compiling and testing code.

## Set up your Course Github Repo

Fork the [Mobile HRI Lab Page repository](https://github.com/FAR-Lab/Mobile_HRI_Lab_Hub); detailed instructions for creating your lab hub and updating your labs are [here](https://github.com/FAR-Lab/Developing-and-Designing-Interactive-Devices/blob/2022Fall/readings/Submitting%20Labs.md).

When submitting your assignments, you will update your assignments on your class lab hub, and post a link to your Github lab page on Canvas. Graders will review the assignments sometime after the due date. Late assignments (e.g. your assignment is missing/incomplete at our grading time, which is after the due date) will be penalized by one letter grade per day late.