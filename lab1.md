# Lab 1: Install a LAMP stack on an Azure Linux VM

1. Create a resource group: I used a existing resource group called Tayor
2. Create a virtual machine: I used a existing ubuntu lts virtual machine for this lab
3. Open port 80 for web traffic: This is done by running az vm open --port 80 -- tayo 
4. SSH into your VM
5. Install Apache, MySQL, and PHP:To install apache, i ran sudo apt-get update and sudo apt-get install apache2 command, for mysql, sudo apt install mysql-server and sudo apt install phy
6. Install WordPress:TThis was done using the following commands sudo mkdir -p /srv/www
sudo chown www-data: /srv/www
curl https://wordpress.org/latest.tar.gz | sudo -u www-data tar zx -C /srv/www

### Notes:

Tutorial: Install a LAMP stack on an Azure Linux VM
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-lamp-stack

Sample Gist
* https://gist.github.com/mikepfeiffer/96d659042f0575a617648a33c92b8f4a

Build and run a web application with the MEAN stack on an Azure Linux virtual machine
* https://docs.microsoft.com/en-us/learn/modules/build-a-web-app-with-mean-on-a-linux-vm/

MEAN Stack App
* https://github.com/MicrosoftDocs/mslearn-build-a-web-app-with-mean-on-a-linux-vm