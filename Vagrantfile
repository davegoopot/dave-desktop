# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "debian/jessie64"
  
  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
  end  
  
  ###############################################
  ##  Project specific changes
  ###############################################
  
  config.vm.provision :shell, path: "bootstrap"
end
