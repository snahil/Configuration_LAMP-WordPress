# Configuration_LAMP-WordPress

SETTING UP FOR LAMP (linux,Apacha,Mariadb,php)

step 1 - Installing apacha
         

	 commands:

	 yum install httpd # need to configure yum repo for using it
	 systemctl enable httpd # it will autostart the service after system reboot
	 systemctl restart httpd # to restart the service
	 systemctl status # to check if the service is working or not 


step 2 - Installing Mariadb/Mysql 

	commands:

                  sudo yum install -y mariadb-server mariadb # for installing mariadb-server # we are using -y to automatically answer yes to all the quries. 
		  sudo systemctl start mariadb    # for starting mariadb services
		  sudo mysql_secure_installation
			# we are usign sudo as to get root rights


Install LAMP on your local Linux system (Laptop/Desktop) and setup WordPress
![Capture](https://user-images.githubusercontent.com/16596896/58789569-52649e00-85a3-11e9-8a3b-ce64b2e8100f.PNG)
![adsfasd](https://user-images.githubusercontent.com/16596896/58789605-68725e80-85a3-11e9-8451-477d12dc7a5c.PNG)
![gsdfgsdfg](https://user-images.githubusercontent.com/16596896/58789789-d0c14000-85a3-11e9-8ebc-64fd740127d1.PNG)
![fadsgadgadgs](https://user-images.githubusercontent.com/16596896/58789790-d0c14000-85a3-11e9-894c-a3c0b1e7a943.PNG)
