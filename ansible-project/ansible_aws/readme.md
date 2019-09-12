===================================
check ansible-playbook version and make sure:
    config file = ...../ansible_aws/ansible.cfg (if not run: export ANSIBLE_CONFIG=ansible.cfg)


================boto,boto3,botocore===============
special locate of python using ansible_python_interpreter=/usr/local/bin/python in localhost (check temp in file 'inventory')

===============================================
check private key locate in ansible.cfg (private key for connect to ec2 instance)
generation ssh key and copy key "id_rsa.pub" in location "env/ssh/"

=====================================
run playbook with :
ansible-playbook ec2.yml --ask-vault-pass (passwd: pass#word1234)


==================================
special infomation for VPC and ec2 instance in :


role/common/defaults/main.yml
