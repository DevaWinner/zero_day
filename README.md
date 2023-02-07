# Vagrant Task
This task teaches me What ubuntu is and how to install and use Vagrant.

**On this task, we learn;**

* What is a virtual machine
* What is Vagrant
* Who wrote Vagrant
* What is Ubuntu
* What does “Ubuntu” mean
* How to use VMs with Vagrant
* What does the command uname do

I further learned that **Virtual Machine** can be downloaded from this [link](https://www.virtualbox.org/wiki/Downloads), and **Vagrant** can be downloaded from this [link](https://developer.hashicorp.com/vagrant/downloads)

## Some Command to set up Vagrant and add Ubuntu

**To add the Ubuntu 20.04 (Focal) image to your box list:
```
C:\Users\julien> vagrant box add ubuntu/focal64
```

**To create first virtual machine:
```
C:\Users\julien> vagrant init ubuntu/focal64
```

**To avoid issue with the last version of Vagrant
```
C:\Users\julien> vagrant plugin install vagrant-vbguest
```

**To start your virtual machine
```
C:\Users\julien> vagrant up
```

**To enter your virtual machine
```
C:\Users\julien> vagrant ssh
```

This and many more I am learning in the task
