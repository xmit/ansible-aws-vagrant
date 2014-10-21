Multiple virtual boxes being provisioned with Ansible
==================================================

Download and install VirtualBox.

    https://www.virtualbox.org/wiki/Downloads

Download and install Vagrant

    https://www.vagrantup.com/downloads.html

Download and install Ansible

    http://docs.ansible.com/intro_installation.html

==================================================

Vagrantfile in aws folder

    Edit Vagrantfile, set the correct path of files and set your aws keys.

    $ cd aws
    $ vim Vagrantfile
    $ vagrant up --provider=aws

    $ vagrant ssh webserver 
    OR
    $ vagrant ssh memcache

Vagrantfile in vbox folder

    Edit the Vagrantfile and set the correct path of files.

    $ cd vbox
    $ vim Vagrantfile
    $ vagrant up 

    $ vagrant ssh webserver 
    OR
    $ vagrant ssh memcache

Get a beer and enjoy your life!
