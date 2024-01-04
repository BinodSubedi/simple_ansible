##Definig hosts in hosts file  
=> Definig Server as the host with ip address written below  
=> Used host:vars scope to define the wanted user and password for the ssh proccess.  

#The main ansible file  
=> Giving the host name as Server from host file defination and writing become as yes to use elevated privilleges  
=> First we ensure that docker is installed in the system we are trying to ssh into.
=> We also check for git to be installed and we clone the dockerfile repo from HAZESOFT-T1
=> We again ensure that docker-compose is installed and finally we run docker-compose command with detached mode so that  
our terminal doesnot hang up even when the process is done.
