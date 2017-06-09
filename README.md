Splunk Ansible Deployment
======================

## Installation
0. `apt-get install python-pip python-dev` install git/pip for your distribution 
1. `cd /opt/`
2. `sudo git clone https://github.com/ansible/ansible.git`
3. `sudo git submodule update --init --recursive`
4. `cd /etc/`
5. `sudo git clone https://github.com/jansett/splk-ansible.git ansible`
6. `pip install boto jinja2` (or install it from your distro package manager)


## New Features
* Copied from divious1

## TODO
* Docs
* Configure for generic deployment


