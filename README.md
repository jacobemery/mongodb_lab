# Ansible playbooks to install and uninstall MongoDB

## 1) Install Ansible: 
~~~
pip3 install ansible 
~~~
## 2) Clone this repository: 
~~~
git clone https://github.com/jacobemery/mongodb_lab.git 
~~~
## 3) Run the playbooks:
~~~
cd mongodb_lab 
~~~
Install MongoDB Enterprise, run as root:
~~~
ansible-playbook install_mongodb.yml 
~~~
Uninstall: 
~~~
ansible-playbook uninstall_mongodb.yml
~~~
