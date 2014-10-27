# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "dtest/pluk14_mariadb"

  config.vm.define :pluk do |pluk14_config|

    pluk14_config.vm.provider :virtualbox do |pluk_vb|
      pluk_vb.customize ["modifyvm", :id, "--name", "pluk14_test"]
      pluk_vb.customize ["modifyvm", :id, "--memory", 2048]
    end

    # network
    pluk14_config.vm.hostname = "pluk14-mariadb.pythian.com"
    pluk14_config.vm.network :private_network, ip: "192.168.6.110"

  end
end
