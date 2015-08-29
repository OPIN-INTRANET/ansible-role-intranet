# Checkpoint

[![Build Status](https://travis-ci.org/OPIN-INTRANET/ansible-role-intranet.svg)](https://travis-ci.org/OPIN-INTRANET/ansible-role-intranet)

http://www.opin.ca

The virtual machine required for local development of our Intranet.

Build the Virtual Machine

* Download this project and put it wherever you want.
* Create a local directory where Drupal will be installed and configure the path to that directory in config.yml (local_path, inside vagrant_synced_folders).
* Open Terminal, cd to this directory (containing the Vagrantfile and this README file).
[Mac/Linux only] Install Ansible Galaxy roles required for this VM: $ sudo ansible-galaxy install -r provisioning/requirements.txt --force
* Type in vagrant up, and let Vagrant do its magic.
