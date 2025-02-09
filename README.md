Ubuntu 22.04LTS is recommended
Ensure that it is a clean operating system, there is no other environment with Apache/Nginx/php/MySQL installed (the existing environment can not be installed)
Linux Panel Installation Command

aaPanel is developed based on Centos, we recommend using Centos to install it

Centos :
yum install -y wget && wget -O install.sh http://www.aapanel.com/script/install_6.0_en.sh && bash install.sh forum

The experimental Centos/Ubuntu/Debian/Fedora installation command supports ipv6. Note that this command is executed with root privileges (Centos8 is supported)

curl -sSO http://www.aapanel.com/script/new_install_en.sh && bash new_install_en.sh forum

Ubuntu/Deepin :
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && bash install.sh forum

Debian :
wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh && bash install.sh forum
==========================================================================================================
1. First, make sure that you have a clean installation of CentOS 7 or Ubuntu.
2. Update the system by running the following command:
______________________________________________________________
Ubuntu: sudo apt-get update
Centos: sudo yum update
______________________________________________________________
3. Install the necessary dependencies by running the following command:
____________________________________________________________________
Ubuntu: sudo apt-get install wget unzip zip curl git -y
Centos: sudo yum install wget
___________________________________________________________
4. Download the aaPanel installation script by running the following command:
______________________________________________________________________________________
ubuntu: wget -O install.sh http://www.aapanel.com/script/install-ubuntu_6.0_en.sh
Centos: wget -O install.sh http://www.aapanel.com/script/install_6.0_en.sh
______________________________________________________________________________________
5. Run the installation script by running the following command:
-------------------------------------------------------------------
cmd: bash install.sh aapanel
------------------------------------------------------------------------------------------------------
