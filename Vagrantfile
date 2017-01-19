# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define :node1 do |node|
    node.vm.box = "ubuntu/trusty64"
    node.vm.hostname = "node1"
    node.vm.network :private_network, ip: "10.200.19.10"
  end

  config.vm.define :node2 do |node|
    node.vm.box = "ubuntu/trusty64"
    node.vm.hostname = "node2"
    node.vm.network :private_network, ip: "10.200.19.11"
  end 

  config.vm.define :haproxy do |node|
    node.vm.box = "ubuntu/trusty64"
    node.vm.hostname = "haproxy"
    node.vm.network :private_network, ip: "10.200.19.12"
  end 
  
end
