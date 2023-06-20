# ec2_creation_with_webapp
create an ec2 instance and configure Apache webserver on the created instance using Ansible 
clone the git repo using
# git pull https://github.com/maviya03/ec2_creation_with_webapp
change the directory name to "ansible" using the following command
# mv ec2_creation_with_webapp
To run the playbook do some basic configuration 
 --> ensure "ansible" package is installed on the machine
 --> ensure a "var.yml" to has the correct AWS credentials are updated (a sample var.yml is added for your reference)
 run the  command 
 # ansible-playbook ec2-creation-with-webapp.yml
 webserver is configured
 chanage the files in document root of the new instance for any chnage in website "/var/www/html/"
