ansible-playbooks
Launching instance http://www.tothenew.com/blog/launching-and-configuring-an-aws-ec2-instance-using-ansible/
command: 
ansible-playbook playbook_name.yml –extra-vars volume-size=10 -e instance_type=t2.micro -e region=us=east-1 -e keypair=sample.pem -e count=1