# Kubernetes Deployed on AWS using Ansible

1. Clone the Repo

2. vagrant up -> vagrant ssh

3. Run inside vagrant vm;
    pip install boto boto3 botocore  --upgrade
    pip install awscli --upgrade --user

4. AWS Configure
   run aws configure and enter your IAM cred and region

5. Move into vagrant directory 
   cd /vagrant/

6. Run ansible playbook;
    ansible-playbook main.yml

7. Thats it your k8s cluster is ready
