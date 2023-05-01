# Ansible playbooks to install and uninstall MongoDB in private lab environments.

## 1) Clone this repository:
~~~
git clone https://github.com/jacobemery/mongodb_lab.git 
~~~
## 2) Run setup script: 
~~~
cd mongodb_lab 
~~~
~~~
./setup.sh
~~~
## 3) Run the playbooks:
Install MongoDB Enterprise, run as root:
~~~
ansible-playbook install_mongodb.yml 
~~~
Uninstall: 
~~~
ansible-playbook uninstall_mongodb.yml
~~~
