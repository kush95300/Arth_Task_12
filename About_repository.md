# Arth Task 12

## Task Statement:

Write an Ansible PlayBook that does the following operations in the managed nodes:
   
   -  Create Ansible playbook to Configure Reverse Proxy i.e. Haproxy and update it's configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory.
   - Configure the same setup as 12.1 over AWS using instance over there.


## Solution 

### To do this task I created these ansible playbook :

   - Load_Balancer_and_webserver_Architecture_setup.yml   :  For automating above tasks. It will done everything over cloud media just in 2 minutes. It is portable script.

   - Delete_LB_and_webserver_setup.yml   :  This file again remove the whole setup for better testing and management.


Thanks guys..  :). 
