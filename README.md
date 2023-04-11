# Configuration Automation with Ansible
This project will implement 3 servers and HA proxy server for load balancing traffic between the servers. 
These tasks are accomplished by using the Ansible tool which will perform configuration on all servers.
To access the 3 web servers we will go through the bastion host as a jumping server. Connection to the bastion host and between bastion host and web servers is done via SSH by using public key authentication.
