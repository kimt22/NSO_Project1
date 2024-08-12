# Automated Service Deployment and Management in OpenStack

This project is an automated solution for deploying, operating, and managing scalable and resilient cloud-based service infrastructure within an OpenStack environment.

Key Features
Automated Deployment: Utilizes Ansible playbook and bash/shell scripts to set up a cloud environment in OpenStack automatically, 
                      including the creation of networks, routers, and virtual machines.
High Availability and Load Balancing: Implements load balancing with HAProxy and high availability with Keepalived across dual proxy nodes to eliminate a single point of failure.
Secure Access: Configures a BASTION host for secure SSH access to instances and centralized monitoring using Prometheus and Grafana.
Resource Cleanup: Includes script to clean up and release all resources allocated during the deployment phase, ensuring no residual resources are left behind.














# already exits 
#Simple flask services/applications for various assignments.
# 
# main.py: Online calculator, supports only 'add'.
# application2.py: Replies with a string containing the Time and hostname.
# assignment2.py: Replies with an HTML formatted string containing the Time and hostname.

#export FLASK_APP=<filename>
#export FLASK_RUN_HOST=<localhost|0.0.0.0>
#export FLASK_RUN_PORT=8210



Usage Example:
export FLASK_APP=main.py
export FLASK_RUN_HOST=localhost
export FLASK_RUN_PORT=8210
flask run

