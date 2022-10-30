# device-setup

An all-in-one Ansible playbook to install and configure tools in one command 

This playbook is 

## Installation 

### Ubuntu 

This installation method has been tested on Ubuntu 20.04+

1. Install Ansible
  1. Install Ansible: `pip3 install ansible`
1. Clone or download this repository to your local drive
1. Run `ansible-playbook main.yml --ask-become-pass` insde this directory. Enter your sudo password prompted for the 'BECOME' password

## TODOS

- macOS: Define configurations
- 

## More Info

The macOS configurations are heavily inspired by Jeff Geerling's Mac Dev Playbook project found [here](https://github.com/geerlingguy/mac-dev-playbook)
