# cs3210-vagrant
The gatech vagrant virtual machine

I've tested the staff solution for jos, labs 1-6 with xenial32 and
everything looks good to me.  

## How to
+ All operations should be executed at the directory of `Vagrantfile`
+ Run `vagrant up` to start virtual machine. The first run will install the Ubuntu 16.04 32bit system
+ Run `vagrant ssh` to connect
+ When everything is done `vagrant halt` stop VM

## Tips
By default this directory is shared as `/vagrant` in VM. You could move jos folder into this
directory to enable seamless sharing between VM and Host: Edit in Host, Compile/Run/Test in VM
