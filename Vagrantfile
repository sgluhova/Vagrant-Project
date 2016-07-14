

# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.

# The code below installs Ubuntu 14.04 OS inside the virtual machine called new_box.  It also assigns a private IP address 
# to the virtual machine and specific port to use for ssh connection between host machine and virtual machine.  

Vagrant.configure("2") do |config|

config.vm.define "new_box" do |new_box|

        new_box.vm.box="ubuntu/trusty64"

        new_box.vm.network :forwarded_port, guest: 22, host: 10224, id: "ssh"

        new_box.vm.network :private_network, ip: "192.168.56.103"

        end


end
