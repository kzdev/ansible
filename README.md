short.works-ansible
====

Ansible code for ruby 2.2.0/rvm/PostgreSQL/Nginx in Amazon Linux or CentOS 6.5

## Preparation

Install Python/pip/Ansible

 1. `brew install python`

 2. `sudo easy_install pip`

 3. `sudo pip install ansible`

 4. `git clone git@github.com:morizyun/short.works-ansible.git`

 5. `cd short.works-ansible`

## Usage

### Production
 1. `yum install sudo -y`

 2. `export ANSIBLE_HOSTS=./ansible/hosts_production`

 3. `ansible-playbook -i hosts ekps.yml -u root --ask-pass --ask-sudo-pass -c paramiko`

 4. type `passw0rd` in Password

 5. set rails-project to `/var/rails/`

## Basic Information

1. PostgreSQL ROOT PASS : ``(nothing)
