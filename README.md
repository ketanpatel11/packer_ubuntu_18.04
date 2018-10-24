# Packer Ubuntu 18.04 Vagrant Box

## Requirements

The following software must be installed/present on your local machine before you can use Packer to build the Vagrant box file:

  - [Packer](http://www.packer.io/)
  - [Vagrant](http://vagrantup.com/)
  - [VirtualBox](https://www.virtualbox.org/) (if you want to build the VirtualBox box)
  - [Ansible](http://docs.ansible.com/intro_installation.html)

## Usage

Clone repo, cd to directory and run:

    $ packer build ubuntu-18.04.json

After a few minutes, Packer will generate Ubuntu 18.04 vagrant box with latest patches. 

