# ansible-roles-code-best-practice

This Ansible code playbook is written according to best practices of using Ansible Role directory structure , variables  that consists of:

1. tasks
2. handlers
3. template
4. vars
5. files -> Note: The files does not exist forn this project as there was a not a need for it


This Ansible coding approach promotes reusability by using the Role structure plabook approach and variables

The code installs http Apache web server on target EC2 instances speciified in the host files of an Ansible control node. The code then copies a customized httpd.conf file to the target ec2 instances /etc/httpd/conf folder. The code then checks if the httpd.conf file has been modified and re configured and if so it restarts the https service so that the new httpd.conf files changes takes effect.
