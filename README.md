To install aaPanel web hosting control panel on CentOS 7 or Ubuntu, follow these steps:

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
6. Follow the prompts to complete the installation process. You will be asked to provide a password for the aaPanel control panel and to select the components that you want to install.
7. After the installation is complete, you can access the aaPanel control panel by going to http://your-server-ip:8888 in your web browser. Replace “your-server-ip” with the IP address of your server.
