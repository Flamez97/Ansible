# _*_ mode: ruby _*_
#vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version. (we support older styles for
# backward compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

    # The most common configuration options arw documented and commented below
    # For a complete reference, please see the online documentation at
    # https://docs.vagrantup.com
  
    # Every vagrant development environment requires a box You can search
    # for boxes st https://vagrantcloud.com/search
  
    #config.vm.box = /users/flamez97/virtualbox-centos8-efi.box"
    config.vm.box = "gbailey/amzn2"
    config.vm.network "private_network", ip: "192.168.56.2"
    config.vm.provision "ansible" do |ansible|
      ansible.playbook = "/"
      ansible.playbook = "/"
      ansible.playbook = "/"
    end
  end 