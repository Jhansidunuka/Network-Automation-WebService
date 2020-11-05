# Network-Automation-WebService

This project is to implement a simple web server. 

Three servers are deployed and HAproxy is used to load balance between these three servers. Php script is deployed on Nginx webservers and HAproxy using Ansible.

This project need to have a SSH config that can be used by Ansible. SSH connection is made to the devices through the Bastion host, which manages the private network from an external network.

