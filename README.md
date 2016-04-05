# Ansible-MongoDB
## Standalone MongoDB Installation Playbook

I wrote and tested this script on CentOS 7 only.

This ansible playbook has only come about as I have recently found myself installing MongoDB constantly for developent and performance testing. 

Simply update the hosts file with the IP or names of your target servers and then run:

````$ ansible-playbook -i hosts site.yml````