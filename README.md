## This project is preseneted for Full stack nano degree program.
### in this project we are required to deploy our Flask based project "Item catalog" into a lightsail amazon server

# General information:
- server's public IP address: 35.156.164.59
- URL: http://35.156.164.59.xip.io/
- SSh port 2200.
- App directory (WSGIScript File in/web root path): /var/www/FlaskApp/
- Software installed: 
  - apache2
  - WSGI for python
  - Virutalenv containing:
  -
    bleach           3.1.0     
    certifi          2018.11.29
    chardet          3.0.4     
    Click            7.0       
    Flask            1.0.2     
    Flask-HTTPAuth   3.2.4     
    Flask-SQLAlchemy 2.3.2     
    httplib2         0.12.0    
    idna             2.8       
    itsdangerous     1.1.0     
    Jinja2           2.10      
    MarkupSafe       1.1.0     
    oauth2client     4.1.3     
    packaging        18.0      
    passlib          1.7.1     
    pip              18.1      
    psycopg2-binary  2.7.6.1   
    pyasn1           0.4.5     
    pyasn1-modules   0.2.3     
    pyparsing        2.3.1     
    redis            3.0.1     
    requests         2.21.0    
    rsa              4.0       
    setuptools       40.6.3    
    six              1.12.0    
    SQLAlchemy       1.2.16    
    urllib3          1.24.1    
    webencodings     0.5.1     
    Werkzeug         0.14.1    
    wheel            0.32.3    
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
 
 
