## This project is preseneted for Full stack nano degree program.
### in this project we are required to deploy our Flask based project "Item catalog" into a lightsail amazon server

# General information:
- server's public IP address: 35.156.164.59
- URL to access the server: http://35.156.164.59.xip.io/
- Software installed: 
  - apache2
  - WSGI for python
  - Virutalenv containing:
    - Flask
    - SQL alchemy
  - postgresql used for database 
  - Configurations made:
    - SSH port of the server is set to port 2200
    - allow only port "80/tcp", "123/tcp", "123/udp", "2200/tcp" on ufw firewall
    - local timezone was set to "UTC"
    - creating a user called "grader" for Udacity graders to be able to properly grade the project
    - configuring the database "PostgreSql" to have a user named "catalog" with the ability to only create Databases
    - enabling the site "FlaskApp" in apache
    - making use of Virtual Environment to install all of the required modules of python inside it.
 # Refreneces:
 - http://www.islandtechph.com/2017/10/21/how-to-deploy-a-flask-python-2-7-application-on-a-live-ubuntu-16-04-linux-server-running-apache2/
 - https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
 - https://ae.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306
 
 
