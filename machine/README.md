# Jenkins certification training machine

Machine for Jenkins certification training.


## Prerequisites

Before starting install the following tools

- VirtualBox
- Vagrant
- Ansible

## Getting started

Follow these steps for setting up the machine

1. Step into the machine directory ```$ cd machine```
2. Install required Ansible packages ```$ ansible-galaxy install -r requirements.yml```
3. Start the machine ```$ vagrant up```
4. Open the browser [http://localhost:38888](http://localhost:38888)