===================================
check ansible-playbook version and make sure:
    config file = ...../ec2/ansible.cfg


================boto,boto3,botocore===============
special locate of python using ansible_python_interpreter=/usr/local/bin/python in localhost (check temp in file 'inventory')

===============================================
check private key locate in ansible.cfg (private key for connect to ec2 instance)

===============================================
special proxy accept from subnet in roles/ec2-frontend/vars/main.yml

=====================================
run playbook with :
ansible-playbook ec2.yml --ask-vault-pass (passwd: pass#word1234)

