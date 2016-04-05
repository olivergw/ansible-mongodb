# Ansible-MongoDB
## Standalone MongoDB Installation Script

This has only come about as I have recently found myself installing MongoDB constandtly for developent and performance testing. 

Simply update the hosts file with the IP or names of your target servers and then run:

````$ ansible-playbook -i hosts site.yml````