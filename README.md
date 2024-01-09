# PROJECT 2: Deploy-LAMP-STACK-onto-EC2-using-Ansible


![image](https://github.com/etidoumossoh/Deploy-LAMP-STACK-onto-EC2-using-Ansible/assets/113789743/87d5d3ed-cbca-4bef-a3a0-0b8fa5e53df5)

# INTRODUCTION 

- This project focuses on deploying a LAMP STACK using Ansible 

- Firstly, what is LAMP? (It is an acronym for Linux as the operating system, Apache for web server, MySQL as the database server, and PHP for the programming language)

# REQUIREMENTS 
- Create two EC2 instances. One is the Ansible- Controller and the other, the Demo-instance
- You must already have Ansible installed on the Controller.

# STEP ONE: Configure your Inventory 
-  This is used by Ansible to track the servers it manages
-  Create your inventory.ini file and include your servers using their IP address or hostname. In this case, we used the IP address

# STEP TWO: Create a Custom Configuration file 
- The 'ansible.cfg' file is the main configuration file for Ansible. It is an INI-format file that contains different sections and key-value pairs to control the behaviour of Ansible.

# STEP THREE: Create a PlayBook 
- In this step, we created a playbook that sets up a basic LAMP STACK
- We installed Apache, MySQL, PHP and PHP modules, Started Apache and enabled it to start on boot, and finally, tested the LAMP STACK by creating a PHP info file. 
