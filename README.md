Ejabberd
===========

This is an ansible program that will install Ejabberd chat server in as many server you want.


Contents
========

**ejabberd.yml** :      This is an installation script that with running it, Ejabberd will be istalled and config files will be copied.

**templates/ejabberd.yml**:       This is Ejabberd config file that you can replace it with your customized config file.

**templates/ejabberctl.cfg**:       This is Ejabberd config file that you can replace it with your customized config file.



Prerequisites
=============

* Debian Wheazy
* Ansible 2
* sshpass : apt-get install sshpass


Usage
=====


**1**- chmod a+x ejabberd.yml

**2**- Edit hosts file to add your hosts

**3**- Run ejabberd.yml with this command:   "ansible-playbook ejabberd.yml -vvvv"


