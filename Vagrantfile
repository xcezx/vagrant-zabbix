# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box_url = "xcezx/CentOS-6.5-x86_64-netboot"

  config.vm.define "monitor" do |monitor|
    monitor.vm.box = "monitor"
    monitor.vm.network "private_network", ip: "10.0.0.10"
  end

  config.vm.define "web" do |web|
    web.vm.box = "web"
    web.vm.network "private_network", ip: "10.0.0.101"
  end

end
