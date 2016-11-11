### ROS配置过程
*1.配置 Ubuntu 软件仓库	 
配置你的 Ubuntu 软件仓库(repositories) 以允许 "restricted"、"universe" 和 "multiverse"这三种安装模式
*2.添加 sources.list	 
配置你的电脑使其能够安装来自 packages.ros.org的软件包。 ROS Jade 仅支持Trusty (14.04)、Utopic (14.10) 和 Vivid (15.04)。 
sudo sh ‐c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release ‐sc) main" > /etc/apt/sources.list.d/ros‐latest.list'
*3.添加 keys	 
sudo apt‐key adv ‐‐keyserver hkp://pool.sks‐keyservers.net ‐‐recv‐key 0xB01FA116
*4.安装	 
首先，确保你的Debian软件包索引是最新的：  sudo apt‐get update 
桌面完整版安装： 包含ROS、rqt、rviz、通用机器人函数库、2D/3D仿真器、导航以及2D/3D感知功能。  
sudo apt‐get install ros‐jade‐desktop‐full
如图
![aaaa](https://cloud.githubusercontent.com/assets/22741656/20216775/698f8b98-a857-11e6-8694-17df6e732ce0.jpg)
*5.初始化 rosdep	 
在开始使用ROS之前你还需要初始化rosdep。rosdep可以方便在你需要编译某些源码的时候为其安装一些系统依赖，同时也是某些ROS核心功能组件所必需用到的工具。  sudo rosdep init rosdep update
*6.环境配置	 
如果每次打开一个新的终端时ROS环境变量都能够自动配置好（即添加到bash会话中），那将会方便很多：  echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc source ~/.bashrc 
如果你安装有多个ROS版本, ~/.bashrc 
 必须只能 source 你当前使用版本所对应的 setup.bash 。  
只想改变当前终端下的环境变量，可以执行以下命令：  source /opt/ros/jade/setup.bash
*7.安装rosinstall	 
rosinstall是ROS中一个独立分开的常用命令行工具，它可以方便让你通过一条命令就可以给某个ROS软件包下载很多源码树。  
要在ubuntu上安装这个工具，请运行： 
sudo apt‐get install python‐rosinstall
*8.检查ROS系统	 
输入以下指令进行检查： roswtf

`### ROS实验结果
![saaa](https://cloud.githubusercontent.com/assets/22741656/20216792/80d94384-a857-11e6-8265-2cd2619eefbd.png)
