# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "maepon/scotchionbox"
  config.vm.network "private_network", ip: "192.168.33.69"
  config.vm.hostname = "sib.localhost"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=666"]

end