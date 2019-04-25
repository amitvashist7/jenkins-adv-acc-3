# My Base Image. 
FROM ubuntu:latest

# Owner
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the APT Repo. 
RUN apt-get update

# Install Apache Packages  
RUN apt-get install apache2 -y 

# Install Apache Packages  
COPY amit.html /var/www/html/index.html

# Bring the Apache Up
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND" ]
