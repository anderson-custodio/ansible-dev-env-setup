# Ansible Roles Dev

This ansible role installs and configures a development environment based on Ubuntu 20.04.  
A list of software is already pre-defined based on what I use on a daily basis.  
The ansible role is ready to run on a VM provisioned by Vagrant.

## Pre-requisites

Python 3, Ansible, Vagrant.

## How to use

Create a copy of `sample-playbook.yml` with the name `create-env-playbook.yml`, then fill all variables in the file.  
Provision the machine and run the ansible playbook with the command `vagrant up`.  
To access the VM, type `vagrant ssh`.  
To destroy the machine run `vagrant destroy`.
