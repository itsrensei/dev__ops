
# Vagrant
an open-source tool for building and managing virtual development environments. It allows developers to create reproducible, portable, and lightweight virtual machines (VMs) that can be easily shared and distributed across different systems. Vagrant simplifies the process of setting up and configuring development environments, by automating the creation and management of VMs through a command-line interface. With Vagrant, developers can quickly spin up multiple VMs with different configurations, such as different operating systems, software packages, and network settings, to simulate different development and testing environments. Vagrant also integrates with popular virtualization technologies, such as VirtualBox, VMware, and Docker, to provide a consistent and streamlined development workflow.




## Installation
### Ubuntu

* Open the Terminal application:
* Now you will execute command line in your Terminal (each of them start with $)
* Install VirtualBox: `$ sudo apt-get install virtualbox`
* Install Vagrant: `$ sudo apt-get install vagrant`
* Add the Ubuntu 20.04 (Focal) image to your box list: `$ vagrant box add ubuntu/focal64` Warning: this step can take time
* Create your first virtual machine:
* `$ vagrant init ubuntu/focal64` -> it will generate a Vagrantfile with `base = "ubuntu/focal64"` - you don’t have to execute this command line everyday, only once, to create a new virtual machine
* `$ vagrant up` -> it will start your virtual machine
* `$ vagrant ssh` -> now you are inside your virtual machine.

## Windows

* Download VirtualBox from this [Here](https://www.virtualbox.org/wiki/Downloads)
* Install VirtualBox
* Download Vagrant from this [Here](https://developer.hashicorp.com/vagrant/downloads)
* Install Vagrant
* Open the [command Prompt](https://www.lifewire.com/how-to-open-command-prompt-2618089)
* Add the Ubuntu 20.04 (Focal) image to your box list:
    * `C:\Users\julien> vagrant box add ubuntu/focal64` Warning: this step can take time
    * Many other images are available [Here](https://app.vagrantup.com/boxes/search)
* Create your first virtual machine:
    * `C:\Users\julien> vagrant init ubuntu/focal64` -> it will generate a Vagrantfile with base = "ubuntu/focal64" -you don’t have to execute this command line everyday, only once, to create a new virtual machine
    * `C:\Users\julien> vagrant plugin install vagrant-vbguest` -> to avoid issue with the last version of Vagrant (2.2.4 or latest)
    * `C:\Users\julien> vagrant up` -> it will start your virtual machine
    * `C:\Users\julien> vagrant ssh` -> now you are inside your virtual machine.

## Mac OS

* Download VirtualBox from this [Here](https://www.virtualbox.org/wiki/Downloads)
* Install VirtualBox
* Download Vagrant from this [Here](https://developer.hashicorp.com/vagrant/downloads)
* Install Vagrant
* Open the Terminal application:
    * Now you will execute command line in your Terminal (each of them start with $)
    * Add the Ubuntu 20.04 (Focal) image to your box list: `$ vagrant box add ubuntu/focal64 `Warning: this step can take time
    * Many other images are available [Here](https://app.vagrantup.com/boxes/search)
* Create your first virtual machine:
    * `$ vagrant init ubuntu/focal64` -> it will generate a Vagrantfile with `base = "ubuntu/focal64"` - you don’t have to execute this command line everyday, only once, to create a new virtual machine
    * `$ vagrant up` -> it will start your virtual machine
    * `$ vagrant ssh` -> now you are inside your virtual machine.

## Feedback

If you have any feedback, please reach out to me at hello@itsdeemab.com

