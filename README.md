# 4IT572_ANSIBLE
Instalace

sudo yum install git

pip3 install ansible boto boto3

https://github.com/JohniCZ/4IT572_ANSIBLE.git

ansible-vault create group_vars/all/aws.yml

ansible-playbook ec2_deploy.yml --ask-vault-pass
