# packer
This is a project to create an ami in aws. Our custom ami will be configured using ansible. The ansible.sh script is to install ansible in the instance. 
The docker.yml script would install and enable docker, as well as other applications needed in our custom ami using ansible palybook.
The aws_docker.pkr.hcl script would create our custom ami using packer.
