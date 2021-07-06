# Installing-and-running-the-arm-package-on-the-ROS-system
 

  

 ###   Download VirtualBox → install ubuntu 16.04 → install ROS kinetic <br><br><br>

 ## 1. Download VirtualBox
install VMware or VirtualBox.<br>
Through the following link, you can download VirtualBox https://www.virtualbox.org/ <br><br>


## 2. Install ubuntu 16.04
Install Ubuntu 16.04 from the following link: https://releases.ubuntu.com/16.04/<br>



### **How Virtualbox & Ubuntu 16.04 Works:**<br>

In VirtualBox create a new virtual machine  by pressing "**NEW**"
![‏‏لقطة الشاشة (75)](https://user-images.githubusercontent.com/52053143/124665123-02104680-deb5-11eb-8487-0093c4757726.png) <br>

Then a window will appear asking you to choose the data for the new virtual machine:

- Name and operating system

- Memory size

- Hard Disk  

Then you can follow the steps by following this video(In Arabic) https://www.youtube.com/watch?v=tLGitBOUTHc  

Also, the steps to download Ubuntu 16.04 have been explained through the following link https://ubuntu.com/tutorials/install-ubuntu-desktop-1604#1-overview   <br><br>


## 3-  Install ROS kinetic 

- Open **Terminal** and copy the commands from this link   https://s-m.com.sa/ros.txt  -- [This link belongs to the Smart Methods Foundation.](https://github.com/smart-methods/arduino_robot_arm)

<br>

- When we get to the command `sudo nano ~/.bashrc` so we scroll down and copy the following trace from the command page with the change of the name “Wesam” to the name that you gave then paste it below the last sentence<br><br>

![‏‏لقطة الشاشة (80)](https://user-images.githubusercontent.com/52053143/124670924-5b7c7380-debd-11eb-8c85-dee3748738d0.png) <br>

Then press **ctrl +o**   → **Enter** →  **ctrl +x**<br>
`$ source ~/.bashrc`

- Run a Rviz :

`$ roslaunch robot_arm_pkg check_motors.launch`


https://user-images.githubusercontent.com/52053143/124673269-3ab61d00-dec1-11eb-8b98-1d70f6e62451.mp4




