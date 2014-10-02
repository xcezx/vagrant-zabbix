# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "xcezx/CentOS-6.5-x86_64-netboot"

  config.vm.provider "virtualbox" do |v|
    v.memory = 512
    v.cpus = 2
    v.customize ["modifyvm", :id, "--natdnsproxy1", "off"]
    v.customize ["modifyvm", :id, "--natdnshostresolver1", "off"]
  end

  config.vm.define "server" do |server|
    server.vm.hostname = "zbx-server"
    server.vm.network "private_network", ip: "10.0.0.10"
  end

  config.vm.define "agent" do |agent|
    agent.vm.hostname = "zbx-agent"
    agent.vm.network "private_network", ip: "10.0.0.101"
  end

end
