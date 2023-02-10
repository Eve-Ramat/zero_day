# Vagrant
This is a project on how to code using you# Vagrant
This is a project on how to code using your local computer

### Definition
: **Vagrant** is a tool that sits on top of a VM provider. Again, we chose to use VirtualBox as a provider, but other providers exist out there and Vagrant offers the possibilty to use dfferent providers 

### How to install Vagrant on your
- Open the Terminal application:
- Now you will execute command line in your Terminal (each of them start with $)
- Install VirtualBox: $ sudo apt-get install virtualbox
- Install Vagrant: $ sudo apt-get install vagrant
- Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 
* Warning: this step can take time
- Many other images are available here
- Create your first virtual machine:
- $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine
- $ vagrant up -> it will start your virtual machine
- $ vagrant ssh -> now you are inside your virtual machine.
r local computer
