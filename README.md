# Here you have the Zabbix repository for Ubuntu Bionic and Debian 9 Stretch & Jessie
## To run them on a local machine based on Linux, you should download the files and make a cd to the Repository Folder. Ej:

    cd /home/user/zabbix-repository
  
## Once there you should run the follow command:

    python -m SimpleHTTPServer 8081
  
## It will start a local server on Python and them you must go to your repo configuration file wich is located both Debian and Ubuntu on:
  
    /etc/apt/sources.list.d/zabbix.list
    
## Them run:
    
    apt-get update
    
## That's all. Follow the steps on Zabbix's Official Site to make the instalation.
