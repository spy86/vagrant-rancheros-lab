# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|

  config.vm.define "rancheros" do |rancheros|
    rancheros.vm.box = "rancherio/rancheros"
    rancheros.vm.hostname = "ubuntu-rancheros"
    rancheros.vm.network "private_network", ip: "192.168.57.2"
    rancheros.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
    end
  end
end