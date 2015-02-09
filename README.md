Getting Started
===============

VirtualBox
----------

Grab the version you need [here](https://www.virtualbox.org/wiki/Downloads).

Vagrant
-------

Same [here](https://www.vagrantup.com/downloads.html).

This repo
---------

1. `git clone` this repo
2. `cd` into the repo
3. Run `vagrant up` and this will install the Trusty64 VM
    1. If you encounter any weird errors try `vagrant plugin install vagrant-vbguest`, then run `vagrant destroy`, then `vagrant up`
4. Run `vagrant ssh` to access the VM
5. Run `exit` from the VM to return to the host

Notes
-----

If you mess anything up in the VM and want to start from scratch, just `exit` the VM and run `vagrant destroy` and `vagrant up` again.
