# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "dtest/pluk14_mariadb"

  config.vm.define :pluk do |pluk14_config|

    pluk14_config.vm.provider :virtualbox do |pluk_vb|
      pluk_vb.customize ["modifyvm", :id, "--name", "pluk14_mariadb"]
      pluk_vb.customize ["modifyvm", :id, "--memory", 1024]
    end

    # network
    pluk14_config.vm.hostname = "pluk14-mariadb.pythian.com"

  end
end
