# Ansible Vagrant profile for a LEMP server

## Background

Vagrant and VirtualBox (or some other VM provider) can be used to quickly build or rebuild virtual servers.

This Vagrant profile installs Nginx and PHP (the 'EMP' part of 'LEMP') using the [Ansible](http://www.ansible.com/) provisioner.

## Getting Started

To use the vagrant file, you will need to have done the following:

  1. Download and Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  2. Download and Install [Vagrant](https://www.vagrantup.com/downloads.html)
  3. Install [Ansible](http://docs.ansible.com/intro_installation.html)
  4. Open a shell prompt (Terminal app on a Mac) and cd into the folder containing the `Vagrantfile`

Once all of that is done, you can simply type in `vagrant up`, and Vagrant will create a new VM, install the base box, and configure it.