# Ansible_Role_For_k8s_Cluster_Redhat-8
OS: Redhat:8, Centos:8

Step 1. Setup Ansible Step 2. Install Roles Step 3. update your ansible host files Step 4. Ping your instance to check connectivity ansible all -m ping # it will ask for yes/no then type 'yes' Step 4. export MASTER_IP= step 4. Run your Playbook

ansible-playbook play-roles.yaml
