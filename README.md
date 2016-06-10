docker-apache2
==============

This container was written for use within Docker (https://www.docker.com/) 

This Docker container uses a minimal Ubuntu 14.04 (Trusty) Operating System and installs apache2. 

The default port that is portmapped to the host is 80. - This could be modified to run using any port that you specify.

Feel free to contribute to the project, and if you have any suggestions feel free to email me or post them.

You can obtain this Docker container by running the following commands:

### Root is required for these commands so su to root:
$ sudo su -
### Install Docker - Note this is "docker.io" and not "docker" 
$ apt-get install docker.io
### use docker to pull down my apache2 container
$ docker pull camarox53/docker-apache2
### use Docker to start the container & to bridge the network between it and the host.
$ docker run --net=host camarox53/docker-apache2

### The webserver is now running! :)
 Run one of the following to view it:
 
 $ firefox localhost 
 
 $ firefox [your Ip here]
 
 $ chromium-browser localhost
 
 $ chromium-browser [your ip here] 
 
