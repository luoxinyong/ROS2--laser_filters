# ROS2--laser_filters
安装laser_filters
一、首先获取laser_filters
通过链接https://github.com/ros-perception/laser_filters.git在分支中找到符合自己ros2版本的相应软件包（Ubuntu20.04 ros2 galactic）
安装路径作为一个功能包的形式安装在workspac/src中
二、安装相应软件包在系统
sudo apt-get install ros-<distro>-laser-filters
<distro>为相应版本
三、colcon build
使用laser_filters
一、运行相应节点，保证ros2 topic中话题/scan正在更新
二、最简单的使用，cd到laser_filters的example目录，ros2 launch 相应laser_filters的相关launch文件，通过相应的yaml文件可以修改滤波的范围与效果
